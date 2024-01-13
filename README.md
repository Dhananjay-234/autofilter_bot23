<p align="center">
  <img src="https://te.legra.ph/file/ca82db4d13a39d0d55dbe.jpg" alt="Sandy Request Bot Logo">
</p>
<h1 align="center">
  <b> Sandy Request BOT </b>
</h1>

## ⚡️Features

- [x] 🔥 New feature :
    - [+] ⚡️ Added `file renaming` feature ⚡️
      - super premium repo...
    - [+] ⚡️ Support 2GB + Files ⚡️
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

## Variables

Read [this]([c]) before you start messing up with your edits.

### Required Variables
* `6952066531:AAF8g6E8mbFwQncf5P2ggkWIbETcw4zHZdY`: Create a bot using [@BotFather](https://telegram.dog/BotFather), and get the Telegram API token.
* `28627031`: Get this value from [telegram.org](https://my.telegram.org/apps)
* `c0aab0d31feb14ade6c6523d9386c4ca`: Get this value from [telegram.org](https://my.telegram.org/apps)
* `filmybackup`: Username or ID of channel or group. Separate multiple IDs by space
* `dhananjay_2304`: Username or ID of Admin. Separate multiple Admins by space
* `DATABASE_URI`: [mongoDB](https://www.mongodb.com) URI. Get this value from [mongoDB](https://www.mongodb.com).
* `DATABASE_NAME`: Name of the database in [mongoDB](https://www.mongodb.com).
* `sandylog` : A channel to log the activities of bot. Make sure bot is an admin in the channel.
* `sandylogg`: Channel ID where logs of requested content is to be sent.
### Optional Variables
* `https://te.legra.ph/file/ca82db4d13a39d0d55dbe.jpg`: Telegraph links of images to show in start message.( Multiple images can be used separated by space )
* `https://t.me/+QhWfgqRJo3diNGNl`: Channel from were file store links of posts should be made.Separate multiple IDs by space
* `False`: True or False . If true then bot will rename files else it will not rename.
* `@dhananjay_2304`: ID of the users to which you want to give file renaming authentication. Separate multiple ids by space.


* Check [info.py](https://github.com/LazyDeveloperr/LazyPrincess/blob/master/info.py) for more


## Deploy
You can deploy this bot anywhere.


<a target="_blank" href="https://app.koyeb.com/deploy?type=git&repository=github.com/LazyDeveloperr/LazyPrincess&branch=master&name=lazyprincessbot"><img alt="Deploy to Koyeb" src="https://binbashbanana.github.io/deploy-buttons/buttons/remade/koyeb.svg"></a>


<details><summary>Deploy To Heroku</summary>
<p>
<br>
<a href="https://heroku.com/deploy?template=https://github.com/LazyDeveloperr/LazyPrincess">
  <img src="https://www.herokucdn.com/deploy/button.svg" alt="Deploy">
</a>
</p>
</details>

<details><summary>Deploy To VPS</summary>
<p>
<pre>
git clone https://github.com/LazyDeveloperr/LazyPrincess
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
• /broadcast - to broadcast a message to all LazyPrincess users
• /batch - to create link for multiple posts
• /link - to create link for one post
• /set_caption - to set new custom caption #renaming_feature
• /del_caption - To delete custom caption #renaming_feature
• /viewthumb - To view custom thumbnail #renaming_feature
• /delthumb - To delete custom thumbnail #renaming_feature




