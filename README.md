# Deploy to HEROKU

# <b>Video Guide <a href='https://lord2tb.hrishithombare26.workers.dev/0:/Anasty-MLTB_HR.mp4?a=view'>Here</a></b>

**<u>Important Note:</u>**
1. Add all of your private files here: `config.env`, `token.pickle`, `rcl.conf`, `accounts.zip` etc...

**<u>Mandatory Veriables in Config:</u>**

- `UPSTREAM_REPO`: Your github repository link, if your repo is private add `https://<username>:<password>@github.com/<your_username>/<repository_name>
` format. `Str`.
  - **NOTE**: Don't forget to remove '<' and '>' . 
- `UPSTREAM_BRANCH`: Upstream branch for update. Default is `upstream`. `Str`

- `BOT_TOKEN`: The Telegram Bot Token that you got from [**BotFather**](https://t.me/BotFather). `Str`
- `OWNER_ID`: The Telegram User ID (not username) of the Owner of the bot. `Int`
- `TELEGRAM_API`: This is to authenticate your Telegram account for downloading Telegram files. You can get this from **<https://my.telegram.org>**. `Int`
- `TELEGRAM_HASH`: This is to authenticate your Telegram account for downloading Telegram files. You can get this from **<https://my.telegram.org>**. `Str`
- `BASE_URL`: Add a valid `BASE URL` to use torrent selection. Copy it from your heroku app. Right click on `OPEN APP` and copy link address. Format of URL should be `https://APPNAME-IDENTIFIER.herokuapp.com/`, where `APPNAME` is the name of your heroku app and IDENTIFIER is an unic number. Example: `https://JetApp1-mjw69x6ex696.herokuapp.com/`. `Str`
- `TORRENT_TIMEOUT`: Timeout of dead torrents downloading with qBittorrent and Aria2c in seconds. `Int`

---
### For farther assistance visit my support group: [**@JetMirror**](https://telegram.me/JetMirror).
---

## Deploy using CLI

- Deployment instructions uploaded [**HERE**](https://gist.github.com/Hrishi2861/dc2d7f22499711642b26b26deaaa3af5)
- Carefully copy-paste every CMD one by one. If you miss maybe your BOT will not run.

- ReadMe Format of [**@Z_Mirror**](https://t.me/Z_Mirror)
