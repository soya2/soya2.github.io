## ffmpeg

ffmpeg -loop 1 -i cover.jpg -i audio.mp3 \
-c:v libx264 -tune stillimage \
-c:a aac -b:a 192k \
-shortest \
-pix_fmt yuv420p \
output.mp4

## say

say -v Samantha -r 140 ""
