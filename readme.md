<h2 align="center">
  「 ꜰɪʟᴇ sᴛʀᴇᴀᴍ ʙᴏᴛ 」
</h2>
<b>ᴠᴀʀs ᴀɴᴅ ᴅᴇᴛᴀɪʟs :</b>

<p>
<p>
  
`API_ID` : Enter Your Telegram API ID.

`API_HASH` : Enter Your Telegram API HASH.
  
`MY_PASS` : Enter Bot Password or leave Empty

`BOT_TOKEN` : Enter Your Bot Token

`BIN_CHANNEL` : Enter ID of your Bin / Log Channel.
  
`OWNER_USERNAME` : Enter Your Telegram User Name

`OWNER_ID` : Your Telegram User ID

`DATABASE_URL` : Enter Your MongoDB Database URL

`UPDATES_CHANNEL` : Enter Username of Your Update Channel without '@'

`WORKERS` : Number of maximum concurrent workers for handling incoming updates. Defaults to `3`

`PORT` : The port that you want your webapp to be listened to. Defaults to `8080`

`WEB_SERVER_BIND_ADDRESS` : Your server bind adress. Defauls to `0.0.0.0`

`NO_PORT` : If you don't want your port to be displayed. You should point your `PORT` to `80` (http) or `443` (https) for the links to work. Ignore this if you're on Heroku.

`FQDN` :  A Fully Qualified Domain Name if present. Defaults to `WEB_SERVER_BIND_ADDRESS`

`BANNED_CHANNELS` : Put IDs of Banned Channels where bot will not work. You can add multiple IDs & separate with <kbd>Space</kbd>.

`SLEEP_THRESHOLD` : Set a sleep threshold for flood wait exceptions happening globally in this telegram bot instance, below which any request that raises a flood wait will be automatically invoked again after sleeping for the required amount of time. Flood wait exceptions requiring higher waiting times will be raised. Defaults to 60 seconds.