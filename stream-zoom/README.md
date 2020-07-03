# Streaming from Zoom

Setup instructions for streaming the sessions from Zoom 

## Setup
You can follow the official Zoom documentaion ([here](https://support.zoom.us/hc/en-us/articles/115001777826-Live-Streaming-Meetings-or-Webinars-Using-a-Custom-Service)) or the instructions below:

- Sign in to the Zoom web portal and go to the settings

![Settings](https://raw.githubusercontent.com/noidsirius/icse2020-live/master/stream-zoom/images/A.png | width=100)

- Enable "Allow live stream meetings"

![LiveStreamEnable](https://raw.githubusercontent.com/noidsirius/icse2020-live/master/stream-zoom/images/B.png | width=100)

- Enable "Allow live stream meetings"

![LiveStreamEnable](https://raw.githubusercontent.com/noidsirius/icse2020-live/master/stream-zoom/images/B.png | width=100)

- Select "Custom Live Streaming Service"

![CustomLiveStream](https://raw.githubusercontent.com/noidsirius/icse2020-live/master/stream-zoom/images/C.png | width=100)

- When you're schedulding the meeting or try to stream for the first time, fill the form below. Stream url is `rtmp://a.rtmp.youtube.com/live2` (the streaming key and live streaming page URL should be shared with you).

![FillTheForm](https://raw.githubusercontent.com/noidsirius/icse2020-live/master/stream-zoom/images/D.png | width=100)

## Procedure

In each session there are four roles: Zoomer, Streamer (a.k.a. OBSer), Session Chair, and Presenter(s). Both Zoomer and Streamer are the co-hosts of the Zoom meeting. 

### T-30m
- Zoomer invited the Session Chair and all Presenters to the breakout room. 
- In the meantime, the Streamer should share his/her screen which is playing the [break slides](https://raw.githubusercontent.com/noidsirius/icse2020-live/master/stream-zoom/BreakSlides-US.mp4) (in loop).
- Then Zoomer creates a break room and send everyone (except Streamer) there. 
- Next, Streamer turns off his/her camera and streams the screen.

![FillTheForm](https://raw.githubusercontent.com/noidsirius/icse2020-live/master/stream-zoom/images/E.png | width=100)


### T-5m
Streamer starts recording.

### T(Live!)

- Zoomer brings back everyone to the main room (everybody should be mute except the Session Chair). 
- Session Chair talks and for each presentation, its corresponding Presenter starts their camera (and unmute themselves). 
- Once the presentation is finished, Streamer should unmute him/herself and plays [Applause Sound](https://raw.githubusercontent.com/noidsirius/icse2020-live/master/art/sounds/277019__sandermotions__applause-4.wav) and then goes mute. 
- If the Presenter doesn't show up, Zoomer should play the presentor's pre-recorded presentation. 

### After the sessions
- Session chair concludes the session, thanks Zoom host and OBS producer, who starts their cameras.
- Streamer share their screen and play the [break slides](https://raw.githubusercontent.com/noidsirius/icse2020-live/master/stream-zoom/BreakSlides-US.mp4) (in loop).
