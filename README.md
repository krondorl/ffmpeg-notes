# FFmpeg notes

Convert all mkv videos to mp3 files. Can be used in CMD cli as a direct command.

`for %f in (*.mkv) do ffmpeg -i %f -vn -ar 44100 -ac 2 -ab 128k -f mp3 %f.mp3`