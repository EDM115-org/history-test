<div align="center">
  
# Unarchiver Bot

## A Telegram bot to extract various types of archives


![Unzip logo](https://telegra.ph/file/426207477776ffa00519f.png)

<a href="https://github.com/psf/black"><img alt="Code style: black" src="https://img.shields.io/badge/code%20style-black-000000.svg"></a>
[![DeepSource](https://deepsource.io/gh/EDM115/unzip-bot.svg/?label=active+issues&show_trend=true&token=17SfwVx77dbrFlixtGdQsQNh)](https://deepsource.io/gh/EDM115/unzip-bot/?ref=repository-badge)


<a href="https://github.com/psf/black"><img alt="Code style: black" src="https://img.shields.io/badge/code%20style-black-000000.svg"></a>
[![DeepSource](https://deepsource.io/gh/EDM115/unzip-bot.svg/?label=active+issues&show_trend=true&token=17SfwVx77dbrFlixtGdQsQNh)](https://deepsource.io/gh/EDM115/unzip-bot/?ref=repository-badge)

</div>

</br></br>

## Demo 🥰
[@unzip_edm115bot](https://t.me/unzip_edm115bot)  
⚠️ From 00h to 08h UTC+1, the [beta](https://github.com/EDM115/unzip-bot/tree/beta) version is running. Try it at your own risks…  
  
## Features 👀
- Extract various types of archives like `rar`, `zip`, `tar`, `7z`, `tar.xz`, …
- Supports password protected archives
- Extract archives from direct links
- Broadcast messages to users
- Ban / Unban users from using your bot
- Send logs in a private channel/group
- Can run only one extract per user at a time
- Download speed : 4-12 Mb/s, can be even more if you're lucky
- Upload speed : 15-25 Mb/s, unexpectedly
- Fast to answer and process tasks
- And some other features 🔥 Dive into the code to find them 🤭
  
## Simple version 😌
I made a special version if you only want to use it personally. Works smoother but with less features.  
[**👉 Try it here 👈**](https://github.com/EDM115/unzip-bot/tree/personal_only)

## Bugs to fix and features to add 💀  
[**Check the beta branch to find them. They normally also are on the master one**](https://github.com/EDM115/unzip-bot/blob/beta/README.md#bugs-to-fix-and-features-to-add-)  
Those are things that are fixed/added regarding to [`original repo`](https://github.com/EDM115/unzip-bot#license--copyright-%EF%B8%8F)
  
## Config vars 📖
- `APP_ID` - Your APP ID. Get it from [my.telegram.org](my.telegram.org)
- `API_HASH` - Your API_HASH. Get it from [my.telegram.org](my.telegram.org)
- `BOT_OWNER` - Your Telegram Account ID. Get it from [@MissRose_bot](https://t.me/MissRose_bot) (Start the bot and send <samp>/info</samp> command).
- `BOT_TOKEN` - Bot Token of Your Telegram Bot. Get it from [@BotFather](https://t.me/BotFather)
- `MONGODB_URL` - Your MongoDB URL ([**tutorial here**](./CreateMongoDB.md))
- `LOGS_CHANNEL` - Make a private channel and get its ID (search on Google if you don't know how to do). Using a group works as well, just add [`Rose`](https://t.me/MissRose_bot?startgroup=startbot), then send `/id` (In both cases, make sure to add your bot to the channel/group as an admin !)

## Commands ✍️
Copy-paste those to BotFather when he asks you for them  
```
clean - Remove your archives from my servers 🚮♻️
mode - Upload things as Doc 📄 or Video 📹 (alias : /setmode)
start - Alive check 😪 Also useful after updates 🥰
```  
Admin only commands (better to not include them)  
```
stats - Get detailed stats about users and server
broadcast - Reply with this to a message to send it at every user
ban - {id of user}
unban - {id of user}
```
  
## Deploy 🚧
Deploying is easy 🥰 You can deploy this bot in Heroku or in a VPS ♥️  
**Star 🌟 Fork 🍴 and Deploy 📤**

> ⚠️ Note :
> We are using arch linux. But why 🤔
> 
> Because arch’s p7zip package is the only maintained version of the [original p7zip](http://p7zip.sourceforge.net/) package with some additional features !
---
#### The lazy way 
[![Deploy me 🥺](https://www.herokucdn.com/deploy/button.svg)](https://www.heroku.com/deploy?template=https://github.com/EDM115/unzip-bot/tree/master)  
(if you're in a fork, make sure to replace the template URL with your repo’s one)

---
#### The legacy way
```bash
git clone -b master https://github.com/EDM115/unzip-bot.git
cd unzip-bot
pip3 install -r requirements.txt
# Arch linux only ↓
sudo pacman -S p7zip
# Edit config.py with your own values
bash start.sh
```
---
**DONE 🥳 enjoy the bot !** Be sure to follow me on [Github](https://github.com/EDM115) and Star 🌟 this repo to show some support 🥺
  
  
## Found a bug 🐞
If you found a bug in this bot please open an [issue](https://github.com/EDM115/unzip-bot/issues) or report it at [me](https://t.me/EDM115)  
Same if you have any feature request ☺️
  
## License & Copyright 👮‍♀️
```
Copyright (c) 2022 EDM115

This Unarchiver Bot repository is licensed under MIT License (https://github.com/EDM115/unzip-bot/blob/master/LICENSE)
Enjoy copying and modifying, but always mention me
```
• Inspired by Itz-fork/Nexa’s work, but with additional features and bug fixes. This is a maintained repo of the [original](https://github.com/Itz-fork/Unzipper-Bot)
