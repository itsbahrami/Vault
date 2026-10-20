```
ffmpeg -i vid1.mp4 -vf "scale=-2:480" -c:v libx264 -crf 26 -preset medium -c:a aac -b:a 128k -movflags +faststart vid1_480p.mp4
```

```
ffmpeg -i vid1.mp4 -vn -c:a libmp3lame -q:a 2 vid1.mp3
```