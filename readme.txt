ffplayer
========

A video player based on ffmpeg for windows and android platform.

ffplayer is not ffplay in offical ffmpeg source code. It is a simple player implemention on windows vs2005 platform. It is a light weight implemention without SDL, with directly access to bitmaps and wavdev in Win32 API.

Currently, this player can smoothly play many video files, with low cpu and memory usage (compared with ffplay of offical ffmpeg), and the audio/video also synchronized very good. More effort must be done to optimize things on synchronization, performance, compatibility and stability.

The ffmpeg share library (dlls, libs & headers) are come from ffmpeg offical web site. I will regularly update these files. Other files are all written by my self. These source codes are licensed under GPL.

The windows version become stable, and the android version is coming. The android verion ffplayer is working now, but lots of work need to be done, to make it better.

rockcarry
2016.1.7

