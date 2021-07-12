
* Discord - https://discord.com/developers
* Spotify (optional) - https://developer.spotify.com/dashboard/


Obtained keys must be entered into ```config/config.py```

#### Requirements

* Installation of Python 3.7+

Install dependancies:
```
pip install -r requirements.txt
```
* Located in ```/config```



Custom Cookies:
* Extract cookies.txt from you browser using your preferred method
* Overwrite the existing cookies.txt in /config/cookies/
* (Optional) Set a custom cookies.txt location by modifying COOKIE_PATH in config.py

## Commands:
```
General:
  changechannel Change the bot channel
  connect       Connect bot to voicechannel
  disconnect    Disonnect bot from voicechannel
  ping          Pong
  reset         Disonnect bot from voicechannel
  setting       View and set bot settings
Music:
  clear         Clear the queue.
  history       Show history of songs
  loop          Loops the currently playing song, toggle on/off.
  pause         Pause Music
  play          Play a supported link or search on youtube
  prev          Go back one Song
  queue         Shows the songs in queue.
  resume        Resume Music
  shuffle       Shuffle the queue
  skip          Skip a song
  songinfo      Info about current Song
  stop          Stop Music
  volume        Change volume %
​No Category:
  help          Shows this message

Type $help command for more info on a command.
You can also type $help category for more info on a category.```

### Music

After the bot has joined your server, use ```$help``` to display help and command information.


