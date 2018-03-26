# BoxClient_Demo.exe
## Support System
* Windows XP
* Windows 7
* Windows 8
* Windows 10
## Feature
* Send PC Screen to receiver--"ScreenRenderDemo.apk"
* Auto Find receiver
* Support two screen while the pc has two display devices
* Support BJCast
* Support Hardware Encoder
# 
# ScreenShare.apk
## Support System
* Android 5.0+
## Feature
* Send Android Screen(Mirror) to receiver--"ScreenRenderDemo.apk"
* Auto Find receiver
* Support BJCast
# 
# ScreenRenderDemo.apk
## Support System
* Android 4.0+
* PAD/phone/TV Box
## Feature
* Play Screen(Mirror) from sender--"BoxClient_Demo.exe/ScreenShare.apk"
* Play airplay mirror from iphone/ipad/mac
* Support BJCast
* Support Airplay
# 
# easyAirplay_linux.zip
## Support System
* x86_64 linux(test in centos 7.1)
## Feature
* Airplay Mirror Receiver
* Record Mirror Streamer to video.h264 file.you can play this file with ffplay:
  ffplay video.h264 
* Record audio pcm data to file audio_44100_2_s16.pcm.you can play this file with ffplay:
  ffplay -f s16le  -channel_layout 3 -channels 2  -ar 44100 audio_44100_2_s16.pcm
## Note:
* we use mdns lib to suppot zeroconf in this demo.so you must stop avahi-daemon first.
# 
# easyAirplay_windows.zip
## Support System
* Windows XP
* Windows 7
* Windows 8
* Windows 10
## Feature
* Airplay Mirror Receiver
* Record Mirror Streamer to .H264 file
# 
## Note:
* please install bonjour for windows first,we use bonjour for zeroconf service.
# 

# License
* Free but has some limits
* maybe disconnect after mirroring 5-10min
* 1/3 probability maybe coredump while start airplay mirror
* Time intervals between multiple screens/mirrors are required
