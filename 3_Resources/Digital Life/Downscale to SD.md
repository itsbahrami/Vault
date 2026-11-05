```bash
ffmpeg -i vid1.mp4 -vf "scale=-2:480" -c:v libx264 -crf 26 -preset medium -c:a aac -b:a 128k -movflags +faststart vid1_480p.mp4
```

| Flag | Description |
| :--- | :--- |
| `-i vid1.mp4` | Input video. |
| `-vf "scale=-2:480"` | Scale to height 480; `-2` means "compute width to preserve aspect ratio, rounded to an even number" (required by H.264). |
| `-c:v libx264` | Video codec: H.264. |
| `-crf 26` | Quality: higher CRF = smaller file, lower quality (26 is reasonable for a 480p preview/delivery). |
| `-preset medium` | Encoder effort: balanced speed/compression (good default for real work). |
| `-c:a aac -b:a 128k` | Re-encode audio to AAC at 128k — fine for 480p. |
| `-movflags +faststart` | Metadata to front — enables progressive playback/streaming. |
| `vid1_480p.mp4` | Output file. |

