Miracast is a groundbreaking solution for seamlessly displaying multimedia between devices, without cables or a network connection.Users can do things like view pictures from a smartphone on a big screen television, share a laptop screen with 
the conference room projector in real-time, and watch live programs from a home cable box on a tablet.

Wifi-direct,RTSP,media decode is main procedure in miracast:

Wifi-direct(p2p):setup the connection between devices.

RTSP:mainly for capability negotiation
![](https://github.com/wirelessdisplay/Miracast/blob/master/mira_rtsp.png)
OPTIONS,GET_PARAMETER,SET_PARAMETER,SETUP,PLAY and TEARDOWN all done is RTSP.
wfd_content_protection: none
wfd_video_formats: 00 00 03 10 0000001f 00000003 00000000 00 0000 0000 10 none none
wfd_audio_codecs: AAC 00000007 00
wfd_client_rtp_ports: RTP/AVP/UDP;unicast 1991 0 mode=play
media decode:decode and render the received audio/video data

We have realized multiple devices casting to one screen together.

single android device

![](https://github.com/wirelessdisplay/Miracast/blob/master/mira_one.gif)

two android devices

![](https://github.com/wirelessdisplay/Miracast/blob/master/mira_two.gif)

