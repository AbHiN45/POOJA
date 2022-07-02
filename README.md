<p align="center">
  <img src="plugins/IMG_20220630_230516_750.jpg" alt="Pooja Logo">
</p>
<h1 align="center">
  <b>Pooja Bot</b>
</h1>


[![Stars](https://img.shields.io/github/stars/AbHiN45/POOJA?style=flat-square&color=yellow)](https://github.com/AbHiN45/POOJA/stargazers)
[![Forks](https://img.shields.io/github/forks/AbHiN45/POOJA?style=flat-square&color=orange)](https://github.com/AbHiN45/POOJA/fork)
[![Size](https://img.shields.io/github/repo-size/AbHiN45/POOJA?style=flat-square&color=green)](https://github.com/AbHiN45/POOJA/)   
[![Open Source Love svg2](https://badges.frapsoft.com/os/v2/open-source.svg?v=103)](https://github.com/AbHiN45/POOJA)   
[![Contributors](https://img.shields.io/github/contributors/AbHiN45/POOJA?style=flat-square&color=green)](https://github.com/AbHiN45/POOJA/graphs/contributors)
[![License](https://img.shields.io/badge/License-AGPL-blue)](https://github.com/AbHiN45/POOJA/blob/main/LICENSE)
[![Sparkline](https://stars.medv.io/AbHiN45/POOJA.svg)](https://stars.medv.io/AbHiN45/POOJA)


## Features

- [x] Auto Filter
- [x] Manual Filter
- [x] IMDB
- [x] Admin Commands
- [x] Broadcast
- [x] Index
- [x] IMDB search
- [x] Inline Search
- [x] Random pics
- [x] ids and User info 
- [x] Stats, Users, Chats, Ban, Unban, Leave, Disable, Channel
- [x] Spelling Check Feature
- [x] File Store
- [x] Auto Delete
## Variables

Read [this](https://telegram.dog/TeamEvamaria/12) before you start messing up with your edits.

### Required Variables
* `BOT_TOKEN`: Create a bot using [@BotFather](https://telegram.dog/BotFather), and get the Telegram API token.
* `API_ID`: Get this value from [telegram.org](https://my.telegram.org/apps)
* `API_HASH`: Get this value from [telegram.org](https://my.telegram.org/apps)
* `CHANNELS`: Username or ID of channel or group. Separate multiple IDs by space
* `ADMINS`: Username or ID of Admin. Separate multiple Admins by space
* `DATABASE_URI`: [mongoDB](https://www.mongodb.com) URI. Get this value from [mongoDB](https://www.mongodb.com). For more help watch this [video](https://youtu.be/1G1XwEOnxxo)
* `DATABASE_NAME`: Name of the database in [mongoDB](https://www.mongodb.com). For more help watch this [video](https://youtu.be/1G1XwEOnxxo)
* `LOG_CHANNEL` : A channel to log the activities of bot. Make sure bot is an admin in the channel.
### Optional Variables
* `PICS`: Telegraph links of images to show in start message.( Multiple images can be used separated by space )
* `FILE_STORE_CHANNEL`: Channel from were file store links of posts should be made.Separate multiple IDs by space
* Check [info.py](https://github.com/EvamariaTG/evamaria/blob/master/info.py) for more


## Deploy
You can deploy this bot anywhere.

<i>**[Watch Deploying Tutorial...](https://youtu.be/1G1XwEOnxxo)**</i>

<details><summary>Deploy To Heroku</summary>
<p>
<br>
<a href="https://heroku.com/deploy?template=https://github.com/AbHiN45/POOJA">
  <img src="https://www.herokucdn.com/deploy/button.svg" alt="Deploy">
</a>
</p>
</details>

<details><summary>Deploy To VPS</summary>
<p>
<pre>
git clone https://github.com/AbHiN45/POOJA
# Install Packages
pip3 install -U -r requirements.txt
Edit info.py with variables as given below then run bot
python3 bot.py
</pre>
</p>
</details>


## Commands
```
• /logs - to get the rescent errors
• /stats - to get status of files in db.
* /filter - add manual filters
* /filters - view filters
* /connect - connect to PM.
* /disconnect - disconnect from PM
* /del - delete a filter
* /delall - delete all filters
* /deleteall - delete all index(autofilter)
* /delete - delete a specific file from index.
* /info - get user info
* /id - get tg ids.
* /imdb - fetch info from imdb.
• /users - to get list of my users and ids.
• /chats - to get list of the my chats and ids 
• /index  - to add files from a channel
• /leave  - to leave from a chat.
• /disable  -  do disable a chat.
* /enable - re-enable chat.
• /ban  - to ban a user.
• /unban  - to unban a user.
• /channel - to get list of total connected channels
• /broadcast - to broadcast a message to all Eva Maria users
• /batch - to create link for multiple posts
• /link - to create link for one post
```
