# song to tts

hi there. this was a fun little project that i worked on for awhile. pretty much, this thing has a little web interface. said web interface has some text input fields that you put the song name and the song artist into. after that, it gets lyrics of it from [lyricwikia](http://lyrics.wikia.com/wiki/LyricWiki) and uses google's tts engine to transcribe it. after that, it returns the audio file to your browser.

to run this, you need to have bottle, lyricwikia, and gtts downloaded from pip3. after that, you can do ```python3 main.py``` and the webserver will run at [localhost:8080](http://localhost:8080). also, if you want to run this on an actual server, you'd want to change the last line of the program from ```run(host='localhost', port=8080, debug=True)``` to ```run(host='{domain name or whatever}', port=80, debug=False)```

idk what you do with this. if you find any problems with this, i would appreciate an issue or pull request made.
