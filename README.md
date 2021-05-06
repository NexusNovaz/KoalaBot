# KoalaBot
[![Discord Server](https://discord.com/api/guilds/729325378681962576/widget.png?style=shield)](https://discord.gg/5etEjVd)
[![Build Status](https://api.travis-ci.org/KoalaBotUK/KoalaBot.svg?branch=master)](https://travis-ci.org/KoalaBotUK/KoalaBot)


KoalaBot is a free open source discord bot being developed by students from around the UK. 
Our aim is to ensure university society committee leaders can access all they need and from one easy to use discord bot 
to improve their server and society! 

## Authors

* **Jack Draper** - *Project Manager* - [JayDwee](https://github.com/JayDwee)
* **Stefan Cooper** - *Senior Developer* - [stefan-cooper](https://github.com/stefan-cooper)
* **Kieran Allinson** - *Senior Developer* - [Kaspiaan](https://github.com/Kaspiaan)
* **Viraj Shah** - *Senior Developer* - [VirajShah18](https://github.com/VirajShah18)

All of our other amazing developers can be seen on our website https://koalabot.uk

See also the list of [current developers](https://github.com/orgs/KoalaBotUK/teams/developers) who are actively participating in this project.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisites

This application uses python 3.8 which you can download [here](https://www.python.org/downloads/)

All python packages you need can be found in the [requirements.txt](requirements.txt).
Before running the bot you must install these as so:

```
pip3 install -r requirements.txt
``` 


### Environment Variables

Before running the bot you will need to create a `.env` file in the root directory of this project. A template for this can be found here:

```dotenv
# Discord Bot
DISCORD_TOKEN = AdiSc0RdT0k3N # A discord Token taken from the discord developers portal 
BOT_OWNER = 123456789 # A discord ID for the person who should have access to owner commands

# Encryption (optional)
ENCRIPTION = False # or True (default) for disabling/enabling the database encryption

# Twitch Alert
TWITCH_TOKEN = tw1tch70k3n # Twitch Token taken from the twitch developers portal
TWITCH_SECRET = tw1tch53cr3t # Twitch Secret taken from the twitch developers portal

# Verification
GMAIL_EMAIL = example@gmail.com # email for a gmail account
GMAIL_PASSWORD = example_password123 # password for the same gmail account


```

## Running the tests
Tests are run using `pytest`
```
python3 -m pytest tests/
```

## Links
* Website & Dashboard: [koalabot.uk](https://koalabot.uk)
* Support Discord: [discord.koalabot.uk](http://discord.koalabot.uk)
* Development Documentation: [documents.koalabot.uk](http://documents.koalabot.uk)
* Developer Roadmap: [development.koalabot.uk](http://development.koalabot.uk)
* Twitter: [twitter.com/KoalaBotUK](https://twitter.com/KoalaBotUK)