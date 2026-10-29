```bash
ffmpeg -loop 1 -framerate 24 -i cover.jpg -i episode.mp3 -c:v libx264 -preset slow -tune stillimage -crf 20 -vf format=yuv420p -c:a aac -b:a 192k -shortest -movflags +faststart episode.mp4
```

| Flag                   | Description                                                                |
| :--------------------- | :------------------------------------------------------------------------- |
| `-loop 1`              | Loop the image input forever (otherwise it's a single frame).              |
| `-framerate 24`        | Frame rate for the image stream — standard, avoids player weirdness.       |
| `-i cover.jpg`         | Input #1: the FHD cover image.                                             |
| `-i episode.mp3`       | Input #2: the audio.                                                       |
| `-c:v libx264`         | Video codec: H.264 — universally compatible.                               |
| `-preset slow`         | Encoder effort: better compression, slower encode. Fine for a still image. |
| `-tune stillimage`     | Tells x264 the content is static → spends bitrate wisely.                  |
| `-crf 20`              | Quality: lower = better (18–23 is a good range).                           |
| `-vf format=yuv420p`   | Pixel format for max player/platform compatibility.                        |
| `-c:a aac`             | Audio codec: AAC (required for MP4 compatibility).                         |
| `-b:a 192k`            | Audio bitrate: good quality for spoken word.                               |
| `-shortest`            | End output when the shortest input (the audio) ends.                       |
| `-movflags +faststart` | Move metadata to front — enables progressive playback/streaming.           |
| `episode.mp4`          | Output file.                                                               |

**Usage:** swap `cover.jpg`, `episode.mp3`, and `episode.mp4` for each new vodcast. Assumes FHD input — no scaling needed.