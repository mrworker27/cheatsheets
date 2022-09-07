"Прожечь" субтитры

```bash
ffmpeg -i Lolita.avi -c:v libx264 -preset ultrafast -qp 18 -threads 8 -map 0 -map -0:a:0 -vf subtitles=Lolita_eng.srt out.avi
```
