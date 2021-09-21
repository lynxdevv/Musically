# 🤖 Musically (Discord Music Bot) 

> Musically is a Discord Music Bot built with discord.js & uses Command Handler from [discordjs.guide](https://discordjs.guide)

## Installation

1. How to obtain a Discord Bot Token and invite that bot to your srrver **[Guide](https://youtu.be/xQ9TTL1h3Xc)**

2. YouTube Data API v3 Key **[Guide](https://developers.google.com/youtube/v3/getting-started)**  

3. SoundCloud is no more providing APIs so no need of api.**

4. Node.js v12.0.0 or newer

## 🏁 Starting

I will prefer to run it on repl. Go to repl.it [here](https://repl.it/).

----

## 🧐 A Major Outlook

After Completing all the required installments and the changes head over to Uptime Robot [here](https://uptimerobot.com/) and login there..Choose the monitor as `https`.Then you would need a link..You could get the link in the web section of you project..First time if you dont run the project you could not see that section.Run the project and you could see it.Then paste the link in uptime robot and take any name and click monitor..And your project will be online 24/7..

---

## 🔎 Making The Project

**For PC users using VS Code** -

```

git clone 

cd Musically

npm install

```

After installation finishes you can use `node index.js` to start the bot.


## ⚙️ Making Files

Copy or Rename `config.json.example` to `config.json` and fill out the values:

🚨🚨 **Commiting your token to be accessed by others or making it public is strictly prohibited.So, dont share your token in any cost or use .gitignore to hide secrets** 🚨🚨

```json

{

  "YOUTUBE_API_KEY": "",

  "SOUNDCLOUD_CLIENT_ID": "",

  "MAX_PLAYLIST_SIZE": 10,

  "PREFIX": ">>",

  "PRUNING": false,

  "STAY_TIME": 30,

  "LOCALE": "en",

  "support_server": "",

  "DEFAULT_VOLUME": 100

}

```

#### If you are making your project in repl then follow the steps below.

* Go to your project in repl

* Tap on the lock icon at left sidebar

* Type ```token``` in the key field

* Type your bot's token in the secret field

* Tap on ```add new secret```


#### If you are making your project in pc then follow the steps below.

* Go to your root folder of bot code

* create `.env` file

* Type ```TOKEN=YOUR-TOKEN``` in the key field

* Replace Your-Toke with yout bot token

* Save It



Currently available locales are:

• English (en)

• French (fr)

• Spanish (es)

• Turkish (tr)

• Korean (ko)

• Brazilian Portuguese (pt_br)

• Simplified Chinese (zh_cn)

• Traditional Chinese (zh_tw)

## 📝 Features & Commands

> Note: The default prefix is '>'

* 🎶 Using YouTube Url

`>play https://www.youtube.com/watch?v=wnJ6LuUFpMo`

* 🔎 Playing music via Name

`>play Let me love you`

* 🔎 Search and play

`>search NCS Astronomia`

Reply with song number or numbers seperated by comma that you wish to play

Examples: `1` or `1,2,3`

* 📃 Play a playlist directly from youtube to Discord

`>playlist https://www.youtube.com/playlist?list=PLeiP6sSl8XyF7qcJ7WR6FjkpKtNBtzkqe`


* 🔎 Play youtube playlists via search query

`>playlist NCS Releases`


**Commands of Our Bot**

* Now Playing (>np)

* Queue system (>queue, >q)

* Loop / Repeat (>loop)

* Shuffle (>shuffle)

* Volume control (>volume, >v)

* Lyrics (>lyrics, >ly)

* Pause (>pause)

* Resume (>resume, >r)

* Skip (>skip, >s)

* Skip to song # in queue (>skipto, >st)

* Remove song # from queue (>remove, >rm)

* Toggle pruning of bot messages (>pruning)

* Help (>help, >h)

* Command Handler from [discordjs.guide](https://discordjs.guide/)

* Controls your Discord Bot via Reactions

