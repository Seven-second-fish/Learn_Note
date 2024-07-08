1. 强制关闭wps
   查找进程ID：在终端中输入以下命令来查找正在运行的WPS进程的进程ID：
   ps -aux | grep wps
   这将会列出当前系统中正在运行的WPS相关进程。
   终止进程：找到与WPS命令行相关的进程ID后，输入以下命令来终止该进程：
   kill <进程ID>
   将 <进程ID> 替换为你在前一步中找到的WPS进程的实际ID。
2. mp4播放器：Vlc，
3. 音频和视频格式的转换：FFmpeg
   将 MP3 转换为 WAV:
   ffmpeg -i input.mp3 output.wav
   将 WAV 转换为 FLAC:
   ffmpeg -i input.wav output.flac
   视频格式转换:
   将 MP4 转换为 AVI:
   ffmpeg -i input.mp4 output.avi
   将 MKV 转换为 MP4:
   ffmpeg -i input.mkv output.mp4
5. 
