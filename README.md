<div align="center">

# Unarchiver Bot
## A Telegram bot to extract various types of archives
![Unzip logo](https://telegra.ph/file/426207477776ffa00519f.png)
</div>
  
  
## Demo 🥰
[@unzip_edm115bot](https://t.me/unzip_edm115bot)  
⚠️ From 22h to 06h UTC+1, this beta version is running. Try it at your own risks…  
  
# **THIS IS BETA BRANCH, DON'T BE MAD AT ME IF IT'S BUGGY 😞**
[![Manual deploy of beta branch](https://github.com/EDM115/unzip-bot/actions/workflows/beta-auto-deploy.yml/badge.svg?branch=beta)](https://github.com/EDM115/unzip-bot/actions/workflows/beta-auto-deploy.yml)  
  
  
## Bugs to fix and features to add 💀  
  
- [ ] The ETA isn't accurate
- [ ] [Reply markup error](https://github.com/EDM115/unzip-bot/issues/2)
- [ ] Adding a `/db` command that returns a list of all users + banned ones
- [ ] ~~Looks like some "blank" users are added to the db, including a banned one~~ *Actually, the banned db can exist only if at least 1 value is inside. So, since owner have all rights, his ID can be added into it, the owner status will bypass it. But I noticed also other banned users while no `/ban` command were done. Investigating on this…*
- [ ] Add a translation (start a CrowdIn dude)
- [ ] ~~Some profile links doesn't work~~ **Private ones. But maybe I can force it…**
- [ ] Get informations with smth like `/user {id}`, that returns his state (banned or not) + lastly uploaded files (5 last with link to channel/group message) + how many files he sent + size of all of them. The user could also get those infos with a `/me` command
- [x] Add a `/dbdive` that returns an url where we can visualize the db online **CAN BE IMPROVED**
- [ ] Add status of extraction in logs (uploaded, started, extracted, failed (+ error), what is the password, …)
- [ ] Add more things to `/stats` like average speed, …
- [ ] Add cancel process button for downloads and an emergency `/redbutton` one
- [ ] Add an emergency `/restart` command that can be run **even** if the bot hanged up
- [ ] Add permathumb support `/addthumb` `/delthumb`
- [ ] Auto use `/clean` when a task failed
- [ ] Keep the archives 5 hours in server just in case someone resend the same (no download twice)
- [ ] Add a `/cleanall` for forcing the server reset and freeing space
- [ ] Add group support. You add bot to group as admin, then reply to any file with `/extract`. Then you choose where goes the files (group or PM), and drop here do the instructions (pass or no, what to upload, …)
  
## Fixed/added :partying_face:
- [x] Download speed stays constant, depending of what we have at begining. If the download started at 3 Mb/s, it will stay like that through all the process and can't evolve
- [x] Unzipping normally a password protected archive makes crash the bot 😭
- [x] Adding file name in description while uploading


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

If you found a bug in this beta version please open an [issue](https://github.com/EDM115/unzip-bot/issues) or report it at [me](https://t.me/EDM115)  
Same if you have any feature request ☺️
