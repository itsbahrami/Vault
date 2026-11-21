## 1. SQL

### 1.1. Basics

- DB: An organized collection of data.
- DBMS: The software that manages the storage of data in a database and provides facilities for searching, retrieving, and modifying data in a database.

```sql
SELECT * FROM fruit_stand;
-----
SELECT price, item FROM fruit_stand;
-----
CREATE TABLE fruit_stand (
  item TEXT,
  price NUMERIC,
  unit TEXT
);
-----
INSERT INTO my_purchase VALUES ('apple', 2, 6.98);
```

### 1.2. Data Retrieval

```sql
SELECT author, title, genre
FROM simple_books
WHERE publication_year > 1999;
-----
SELECT author, title, genre
FROM simple_books
ORDER BY genre, title;
-----
SELECT *
FROM simple_books
ORDER BY publication_year DESC;
-----
SELECT DISTINCT genre FROM simple_books;
```

### 1.3. Expressions

```sql
SELECT * FROM simple_books WHERE genre <> 'fantasy';
-----
SELECT
  title,
  floor((publication_year + 99) / 100) AS century
FROM simple_books;
-----
SELECT title || ', by ' || author FROM simple_books;
-- SQL Server: use + instead
-- MySQL: use concat()
-----
SELECT * FROM simple_books WHERE lower(title) LIKE '%love%';
-----
SELECT *
FROM simple_books
WHERE
    (genre = 'science fiction' OR genre = 'fantasy')
    AND publication_year > 2000;
-----
SELECT CURRENT_DATE;
SELECT CURRENT_TIME;
SELECT CURRENT_TIMESTAMP;
-----
SELECT * FROM simple_authors WHERE death IS NULL;
-----
SELECT
    author, title,
    CASE WHEN genre = 'fantasy' THEN 'speculative fiction'
         WHEN genre = 'science fiction' THEN 'speculative fiction'
         WHEN genre = 'poetry' THEN 'poetry'
         WHEN genre = 'history' THEN 'non-fiction'
         ELSE 'general fiction'
    END
    AS category
FROM simple_books;
-----
SELECT
    author, title,
    CASE genre
        WHEN 'fantasy' THEN 'speculative fiction'
        WHEN 'science fiction' THEN 'speculative fiction'
        WHEN 'poetry' THEN 'poetry'
        WHEN 'history' THEN 'non-fiction'
        ELSE 'general fiction'
    END
    AS category
FROM simple_books;
```
