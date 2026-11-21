```sh
ffmpeg -y -i "input.mkv" -vn -map 0:a:0 -af "silenceremove=stop_periods=-1:stop_duration=0.8:stop_threshold=-45dB:stop_silence=0.15" -c:a libmp3lame -b:a 128k "output.mp3"
```
