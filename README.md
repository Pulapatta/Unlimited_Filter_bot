# Unlimited Filter Bot


<p align="center">
  <a href="https://www.python.org">
    <img src="http://ForTheBadge.com/images/badges/made-with-python.svg">

  </a>
</p>
<p align="center">
  <a href="https://github.com/TroJanzHEX/Unlimited-Filter-Bot/stargazers">
    <img src="https://img.shields.io/github/stars/TroJanzHEX/Unlimited-Filter-Bot?style=social">

  </a>
  
  <a href="https://github.com/TroJanzHEX/Unlimited-Filter-Bot/fork">
    <img src="https://img.shields.io/github/forks/TroJanzHEX/Unlimited-Filter-Bot?label=Fork&style=social">

  </a>  
</p>

[![TroJanz](https://img.shields.io/badge/TroJanzHEX-Channel-orange?style=for-the-badge&logo=telegram)](https://telegram.dog/TroJanzHEX)  
ㅤㅤㅤㅤㅤㅤㅤ  
[![TroJanz](https://img.shields.io/badge/TroJanzHEX-Support-red?style=flat&logo=telegram)](https://telegram.dog/TroJanzSupport)  [![TroJanz](https://img.shields.io/badge/TroJanzHEX-Website-red?style=flat&logo=CodersRank)](https://TroJanzHEX.me)  
ㅤㅤㅤㅤㅤㅤㅤ  
[![MIT license](https://img.shields.io/badge/License-MIT-blue?style=flat)](https://github.com/TroJanzHEX/Unlimited-Filter-Bot/blob/main/LICENSE)  [![Open Source](https://badges.frapsoft.com/os/v2/open-source.svg?v=103)](https://github.com/TroJanzHEX/Unlimited-Filter-Bot)


## An advanced Filter Bot with nearly unlimitted filters!


### Features
* Nearly unlimited filters
* Supports all type of filters(Including Alert Button Filter).
* Can save button filters directly (Rose Bot Feature)
* Supports multiple PM connections
* And all other features of a Filter Bot :D


#### Deploy the bot and start adding your filters :)


## How to use the bot
* Add bot to your group with admin rights.

* Add your filters :)


## Bot Commands

(You need to be an admin or Auth User in order to use these commands)

> Filter Commands
* `/add <filtername> <filtercontent>`  -  To add your filter. You can also reply to your content with /add command.

* `/del <filtername>`  -  Delete your filter.

* `/delall`  -  Delete all filters from group. (Group Owner Only!)

* `/viewfilters`  -  List all filters in chat.

> Connection Commands
* `/connect groupid`  -  Connects your group to PM. You can also simply use, `/connect` in groups.

* `/connections`  -  Manage your connections. (only in PM)

> Extras
* `/status`  -  Shows current status of your bot (Auth User Only)

* `/id`  -  Shows ID information

* `/info <userid>`  -  Shows User Information. Also use `/info` as reply to some message for their details!


## You can check the video tutorial on how to deploy

[Click here to see tutorial video](https://youtu.be/hkmc3e7U7R4)

Thanks to [InfotelGroup](https://telegram.dog/InFoTel_Group) and [Erich Daniken](https://telegram.dog/ErichDaniken) for the video


## Any bugs or errors or suggestions, report at [TroJanzSupport](https://telegram.dog/TroJanzSupport)


## Installation

### Deploy to Heroku
[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/Pulapatta/Unlimited_Filter_bot)

# Deploy to Railway
[![Deploy on Railway](https://railway.app/button.svg)](https://railway.app/new/template?template=https%3A%2F%2Fgithub.com%2FPulapatta%2FUnlimited_Filter_bot&envs=API_HASH%2CAPI_ID%2CAUTH_USERS%2CDATABASE_NAME%2CDATABASE_URI%2CHEROKU_API_KEY%2CSAVE_USER%2CTG_BOT_TOKEN%2CWEBHOOK&API_HASHDesc=Your+API+Hash+from+my.telegram.org+&API_IDDesc=Your+API+Hash+from+my.telegram.org+&AUTH_USERSDesc=ID+of+users+that+can+use+the+bot+commands&DATABASE_NAMEDesc=Your+database+name+from+mongoDB.+%28+Default+will+%27Cluster0%27+%29&DATABASE_URIDesc=Database+URL+from+https%3A%2F%2Fcloud.mongodb.com%2F&HEROKU_API_KEYDesc=To+check+dyno+status.+Go+to+https%3A%2F%2Fdashboard.heroku.com%2Faccount%2C+scroll+down+and+press+Reveal+API&SAVE_USERDesc=Do+you+need+to+save+user+details%3F+Usefull+for+getting+userinfo+and+total+user+counts.+May+reduce+filter+capacity.+Give+yes+or+no&TG_BOT_TOKENDesc=Your+Telegram+Bot+Token+from+%40BotFather&WEBHOOKDesc=No+need+to+change+this+field%21&API_HASHDefault=6c2ee4bf150d9f3cd3e3d64aad0772c8&API_IDDefault=6327652&AUTH_USERSDefault=1055623367&DATABASE_NAMEDefault=Cluster0&DATABASE_URIDefault=mongodb%2Bsrv%3A%2F%2FJoker%3AJoker%40cluster0.qiwed.mongodb.net%2FmyFirstDatabase%3FretryWrites%3Dtrue%26w%3Dmajority&HEROKU_API_KEYDefault=179a6403-62d8-4ce7-8352-28cb5eeca2f1&SAVE_USERDefault=no&TG_BOT_TOKENDefault=5076667754%3AAAFyffSrXnj9bgc4A-KH6Lgm7WLa199CPi0&WEBHOOKDefault=ANYTHING&referralCode=MrktTech)
### Deploy in your vps
```sh
git clone https://github.com/TroJanzHEX/Unlimited-Filter-Bot
cd Unlimited-Filter-Bot
pip3 install -r requirements.txt
# <Create config.py appropriately>
python3 bot.py
```


## Configs

* TG_BOT_TOKEN  - Get bot token from @BotFather

* API_ID        - From my.telegram.org (or @UseTGXBot)

* API_HASH      - From my.telegram.org (or @UseTGXBot)

* AUTH_USERS  - ID of users that can use the bot commands. Get from [MissRose Bot](https://telegram.dog/MissRose_bot) by using /id command

* DATABASE_URI  - Mongo Database URL from https://cloud.mongodb.com/

* DATABASE_NAME  - Your database name from mongoDB. Default will be 'Cluster0'

* SAVE_USER  -  Give yes or no . Usefull for getting userinfo and total user counts. May reduce filter capacity :( .

* HEROKU_API_KEY  -  To check dyno status. Go to https://dashboard.heroku.com/account , scroll down and press Reveal API


### Optional - To set alternate Bot Commmands!
( *Add required field as heroku var and give desired command as value. You can edit it in sample_config.py also!*)

* ADD_FILTER_CMD  -  default will be 'add'

* DELETE_FILTER_CMD  -  default will be 'del'

* DELETE_ALL_CMD  -  default will be 'delall'

* CONNECT_COMMAND  -  default will be 'connect'

* DISCONNECT_COMMAND  -  default will be 'disconnect'

EG;  
![Vars Eg](https://telegra.ph/file/1f956f3491f2f20a9c1ec.jpg)

## Credits

<p align="left">
  <a href="https://github.com/pyrogram/pyrogram">
    <img alt="Pyrogram" src ="https://i.imgur.com/BOgY9ai.png" width="104.75" height="32"/>
  </a>
</p>

<p align="left">
  <a href="https://docs.mongodb.com">
    <img alt="MongoDB" src ="https://img.shields.io/badge/MongoDB-%234ea94b.svg?&style=for-the-badge&logo=mongodb&logoColor=white"/>
  </a>
</p>
