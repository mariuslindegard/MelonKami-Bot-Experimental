# MelonKami Bot Experimental

This repo is for the Experimental version of my main bot MelonKami ``https://github.com/MelonKami/MelonKamiBot``, here I will experiment on features and ect, which in return could result in an unstable bot.

## Feel free to use my bot as your own

MelonKami Bot is a plug and play type off bot, simply clone it and all you have to do is download the modules it requires ref-[packages you'll need to install](https://github.com/MelonKami/MelonKami-Bot-Experimental#packages-youll-need-to-install), and it'll ask you for the token and prefix, and setup itself. I made this so anyone who wants a bot, can have one, but this is simply the experimental version of my main bot, if you want the main bot, go to `https://github.com/MelonKami/MelonKamiBot` and download that one (At this current time there is nothing there, because the bot does not have a stable version, it will soon). 

If you want to use this bot as your own, simply clone the repo or download it. When you launch it first time it has a setup. It will ask you for a token, and after that it will be working, you can change this later (read configuration notes). Hope you enjoy my bot :D

## Packages the bot uses

To install the packages, simply do `pip install .`, and if this for some reason won't work, here is the packages, and the pip installments

> discord.py (`pip install discord.py`)
>
> termcolor (`pip install termcolor`)

## Important Notes

* As of now, there are no important notes, if you have any questions check `Configuration notes`, if you can't find your question answer there, you can create an issue on the repo.

## Configuration notes
  
* Want to change something in the configuration file? The configuration file is the file that stores data for the bot, for example your token and prefix is stored there, now if you inputted the wrong token, you can head over to ``config.json`` and change what you need there. You should turn off the bot when doing this to:

1. Not generate error.

2. Not overwrite what has been changed: the bot won't recognize a change, and it could potentially overwrite your change if it is running.

* But be careful with what you mess with, because you could end up breaking the bot. If this happens, you can simply delete the `config.json`file (keep in mind that this will delete all data), and next time you start the bot, it will launch in `first launch` mode. It will then ask for token and prefix again!