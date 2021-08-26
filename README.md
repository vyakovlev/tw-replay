# IN DEVELOPMENT, DO NOT EXPECT SOMETHING PROD READY HERE!!

# Twitch replay: what? why?
Sometimes you find a great stream, you'd like to save in your pocket and get 
back to it in a while (maybe a month or a year).

This isn't easy with Twitch, even a subscription to your streamer doesn't 
guarantee your video will be there in a few months (life is life, you know).

There are many tools on the market, that can get you a video file of the 
stream, but don't we love these funny chats full of emotions, does it really 
make sense to watch video only?

I haven't found a tool on the market, that can get you full experience: video 
with comments. So... This is my answer.

## Disclaimer
I use `youtube-dl` to get video & audio layers from a stream. This is not 
100% fine with Twitch, and they may block your account for this. I advise you 
to have subscriptions to your favorite streamers to support them, please use 
this tool for rare downloads of something really special.

## Installation and usage
### Python way
- Download and install a recent Python 3, see https://www.python.org/downloads/
- Create a separate directory for your new archive, e.g. `twitch` under 
Documents dir (e.g. `~/Documents/twitch` on a macbook), go there
- Clone this project with `git clone`, see green `Code` button in the 
top-right corner of this project on `github.com`
- Create a Python virtual env with `venv` module
(see https://docs.python.org/3/library/venv.html) - (run in a command prompt, 
e.g. `cmd` in Windows, `terminal` or `bash` in other Unix-like OS):
  * `python3 -m pip install pip --upgrade`
  * `python3 -m venv venv` 
  * Windows:  `venv\Scripts\activate.bat`, Unix `source venv/bin/activate`
  * `pip3 install pip --upgrade`
  * `pip3 install -r requirements.txt`
  * `python3 replay.py <twitch-id>`, e.g. `1129201583` for 
`https://www.twitch.tv/videos/1129201583`
