```bash
ffmpeg -i vid1.mp4 -vn -c:a libmp3lame -q:a 2 vid1.mp3
```

| Flag | Description |
| :--- | :--- |
| `-i vid1.mp4` | Input video. |
| `-vn` | No video — drop the video stream entirely (audio-only output). |
| `-c:a libmp3lame` | Audio codec: LAME MP3 encoder. |
| `-q:a 2` | Variable bitrate quality: `0` (best) – `9` (worst); `2` ≈ ~190 kbps VBR, a good default. |
| `vid1.mp3` | Output file. |
