http://forums.hackaday.com/viewtopic.php?f=3&t=3336

http://stackoverflow.com/questions/16818036/controlling-gopro-with-url-commands


https://github.com/moohtwo/Android-GoPro-Streaming/blob/master/Gopro/src/com/mooh/gopro/GoproActivity.java

http://goprouser.freeforums.org/viewtopic.php?t=9393&p=61828

http://www.techanswerguy.com/2013/02/capturing-live-stream-from-gopro-hero-2.html
	ffmpeg -y -i http://10.5.5.9:8080/live/amba.m3u8 -c:v copy -an test.mp4

http://goprouser.freeforums.org/howto-livestream-to-pc-and-view-files-on-pc-smartphone-t9393.html


CONSUME BY VLC STREAMER (low quality, low fps preview) OR FIREFOX
http://10.5.5.9:8080/live/amba.m3u8

