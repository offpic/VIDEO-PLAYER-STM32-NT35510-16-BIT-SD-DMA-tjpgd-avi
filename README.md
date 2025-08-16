https://www.youtube.com/watch?v=KO0tM5htzDQ

ffmpeg -i inputvideo.mp4 -c:v mjpeg -s 320x240 -r 25 -q 15 noaudio1.avi

![Screenshot_1](https://github.com/user-attachments/assets/7d7b8990-d150-41e9-9717-de28bafb850f)

ffmpeg -i inputvideo.mp4 -c:v mjpeg -s 800x480 -r 5 -q 15 noaudio2.avi

![Screenshot_2](https://github.com/user-attachments/assets/5f2a1f04-3145-4cba-a51a-a46127893b04)

************************************************************

Code 60% from VADROV https://github.com/vadrov/stm32f4_fast_optimized_avi_player_osd

40% from me

************************************************************

to do it:

1- use stm32f407 with fsmc + sdio dma cmsis

************************************************************


