## Introduction
ffmpeg is a powerful tool. But it has so many parameters, that makes difficult to do even the simplest of the convertions.

Sometimes, some media players (like vlc in ipad/iphone/ipod touch or a "smart"TV) have several audio codec limitations that force us to do a video conversion.

Some desktop tools make a faster conversion (eg: avidemux) but don't have queue functionality or make a corrupted video file. Other desktop tools (eg: Handbrake) have queue, but the conversion is too cpu and time consuming.

I find creating a wrapper script around the ffmpeg a fast way to get faster an better video conversions.


# **convertVideo** - Bash Script
This is a script to make easier the use of ffmpeg video convert utility, specially to make videos work with media players on iOS devices.

## Requisites
* OSX / GNU-Linux / BSD / Unix
* Bash shell
* ffmpeg tool installed, reachable from the command path.
