<br>
<p align="center">
   <a href="https://github.com/xmtscf/USERGE-X"><img src="https://i.imgur.com/53mdl2v.png" alt="Userge-x" width=400px></a>
   <br>
   <br>
</p>
<h1>USERGE-X</h1>
<b>Pluggable Telegram UserBot</b>
<br>
<br>
## Requirements 
* Python 3.8 or Higher
* Telegram [API Keys](https://my.telegram.org/apps)
* Google Drive [API Keys](https://console.developers.google.com/)
* MongoDB [Database URL](https://cloud.mongodb.com/)
## How To Deploy 
* With Heroku:
<p align="center">
   <a href = "https://heroku.com/deploy?template=https://github.com/code-pms/MyGpack"><img src="https://telegra.ph/file/57c4edb389224c9cf9996.png" alt="Press to Takeoff" width="490px"></a>
</p>
<br>

> **NOTE** : your can fill other vars as your need and they are optional. (settings -> reveal config vars)
* First click The Button Above.
* Fill `API_ID`, `API_HASH`, `DATABASE_URL`, `LOG_CHANNEL_ID`, `HEROKU_APP_NAME` and `HEROKU_API_KEY` (**required**)
* Then fill Dual Mode vars : `OWNER_ID`, `BOT_TOKEN` and `HU_STRING_SESSION`
* Then fill [other **non-required** vars](https://telegra.ph/Heroku-Vars-for-USERGE-X-08-25) later
* Finally **hit deploy** button
## String Session
**VAR ->** `HU_STRING_SESSION`
#### By HEROKU
- [open your app](https://dashboard.heroku.com/apps/) then go to **more** -> **run console** and type `bash genStr` and click **run**.
#### On REPL
- [Generate on REPL](https://repl.it/@Leorio/stringsessiongen#main.py)
### Read more
<details>
  <summary><b>Details and Guides</b></summary>

## Other Ways

* With Docker 🐳 
    <a href="https://github.com/xmtscf/USERGE-X/blob/alpha/resources/readmeDocker.md"><b>See Detailed Guide</b></a>

* With Git, Python and pip 🔧
  ```bash
  # clone the repo
  git clone https://github.com/xmtscf/USERGE-X.git
  cd userge-x

  # create virtualenv
  virtualenv -p /usr/bin/python3 venv
  . ./venv/bin/activate

  # install requirements
  pip install -r requirements.txt

  # Create config.env as given config.env.sample and fill that
  cp config.env.sample config.env

  # get string session and add it to config.env
  bash genStr

  # finally run the USERGE-X ;)
  bash run
  ```

<h2>Guide to Upstream Forked Repo</h2>
<a href="https://telegra.ph/Upstream-Userge-Forked-Repo-Guide-07-04"><b>Upstream Forked Repo</b></a>
<br>
<br>

<h3 align="center">Youtube Tutorial<h3>
<p align="center"><a href="https://youtu.be/M4T_BJvFqkc"><img src="https://i.imgur.com/VVgSk2m.png" width=250px></a>
</p>

### Project Credits 
* [Pyrogram Assistant](https://github.com/pyrogram/assistant)
* [PyroGramBot](https://github.com/SpEcHiDe/PyroGramBot)
* [PaperPlane](https://github.com/RaphielGang/Telegram-Paperplane)
* [Uniborg](https://github.com/SpEcHiDe/UniBorg)
### Copyright & License 
[**GNU General Public License v3.0**](https://github.com/xmtscf/USERGE-X/blob/alpha/LICENSE)
