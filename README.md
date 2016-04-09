# webaudioapi-microphone

A simple self contained html file with inline javascript which sends your microphone audio to your speakers (Turn Down the Volume) using Web Audio API

NOTE - if you hear a distorted loud squeal (audio feedback a la Jimi Hendrix) turn down your speaker volume and/or use your headphone.  

HOWTO Run ... open up a terminal window and issue

```
git clone git@github.com:scottstensland/webaudioapi-microphone.git  # clone this repo 
cd webaudioapi-microphone/src  # get into dir with the html file
python -m SimpleHTTPServer  # launch this HTTPD server to make this dir visible on your browser
```

now point your browser at URL  http://localhost:8000
