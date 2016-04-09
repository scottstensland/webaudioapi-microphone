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

pick the html file ... then you MUST get the prompt to acknowledge usage of your microphone (if NOT your launch is wrong)

then open up the browser console ( ctrl-shift-i )

here you see snippets of the raw audio memory buffer (time domain and/or frequency domain see comments in code) in PCM format


