# TelePyroBot 🤖

[![forthebadge made-with-python](http://ForTheBadge.com/images/badges/made-with-python.svg)](https://www.python.org/)
[![ForTheBadge built-with-love](http://ForTheBadge.com/images/badges/built-with-love.svg)](https://GitHub.com/Skuzzy_xD/)<br>
![Views](https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https://github.com/SkuzzyxD/TelePyroBot&title=Profile%20Views)

A Telegram UserBot based on [Pyrogram](https://github.com/pyrogram/pyrogram)

Join [@Skuzzers](https://t.me/Skuzzers)!

## Installing

#### The Easy Way- Heroku
[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/mahdihajizadehofficial/pyguser)

#### GET STRING SESSION FROM REPL RUN!
[![Repl.it](https://img.shields.io/badge/REPL%20RUN-Run%20Online-blue.svg)](https://telepyrobot.skuzzyxd.repl.run/)

#### Docker way!
Setup config.py file
```sh
docker build -t telepyrobot:v2.1 .
docker run -d telepyrobot:v2.1
```

#### The Legacy Way - Manual
Simply clone the repository and run the main file:
```sh
git clone https://github.com/SkuzzyxD/TelePyroBot.git
cd TelePyroBot
virtualenv -p /usr/bin/python3 venv
. ./venv/bin/activate
pip install -r requirements.txt
python3 -m telepyrobot
```

Get String Session
```sh
git clone https://github.com/SkuzzyxD/TelePyroBot.git
cd TelePyroBot
virtualenv -p /usr/bin/python3 venv
. ./venv/bin/activate
pip install -r string-requirements.txt
python3 GenerateStringSession.py
```

## Getting config.py values

An example `config.py` file could be:

**Not All of the variables are mandatory**

__The UserBot should work by setting only these variables__

```python
from telepyrobot.sample_config import Config

class Development(Config):
  APP_ID = 6
  API_HASH = "eb06d4abfb49dc3eeb1aeb98ae0f581e"
  STRING_SESSION = ""  # Get it from Repl.run or manually
```

`STRING_SESSION` can be generated by running `python3 GenerateStringSession.py` in any GNU/Linux system, with Python3 and the requirements installed.


## Things to Note:
- Only three of the configuration / environment variables are mandatory.
- This is because of `pyrogram.errors.API_ID_PUBLISHED_FLOOD`
    - `APP_ID`:   You can get this value from https://my.telegram.org
    - `API_HASH`:   You can get this value from https://my.telegram.org
    - `STRING_SESSION`: Get it from [Repl.run (Click here)](https://telepyrobot.skuzzyxd.repl.run/)
- The Userbot should work without setting the non-mandatory environment variables.
- Please report any issues to the support group: [@Skuzzy xD](https://t.me/SkuzzersChat)


## Credits, and Special Thanks to

* [Spechide](https://t.me/ThankTelegram) for basic plugins.
* [Dan Tès](https://t.me/haskell) for his [Pyrogram Library](https://github.com/pyrogram/pyrogram)
* [Colin Shark](https://t.me/ColinShark) for his [PyroBot](https://git.colinshark.de/PyroBot/PyroBot)
* [Pokurt](https://github.com/pokurt) for his [Nana-Remix](https://github.com/pokurt/Nana-Remix)

## Copyright & License
* Copyright (C) 2020 by [SkuzzyxD](https://github.com/SkuzzyxD) ❤️️
* Licensed under the terms of the [GNU GENERAL PUBLIC LICENSE Version 3, 29 June 2007](https://github.com/SkuzzyxD/TelePyroBot/blob/master/LICENSE.md)
