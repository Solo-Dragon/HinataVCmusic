

<h3>Requirements 📝</h3>

- FFmpeg
- NodeJS [nodesource.com](https://nodesource.com/)
- Python 3.8 or higher
- [PyTgCalls](https://github.com/pytgcalls/pytgcalls)
- [MongoDB](https://cloud.mongodb.com/)

### 🧪 Get STRING_SESSION from below:

[![GenerateString](https://img.shields.io/badge/repl.it-generateString-yellowgreen)](https://replit.com/@levinalab/StringSession#main.py)

### 🎖 History

[![Mentioned in Awesome Python](https://awesome.re/mentioned-badge.svg)](https://github.com/levina-lab/VeezMusic)

## Features 🔮

- Thumbnail Support
- Playlist Support
- Showing track names when skipping
- Youtube, Local playback support
- Settings panel
- Control with buttons
- Userbot auto join
- Channel Music Play
- Keyboard selection support for youtube play
- Lyrics Scrapper
- Unlimited Queue
- Broadcast Bot
- Statistic Collector
- Group Tools (ban/unban/mute/unmute)
- Block / Unblock (restrict user for using your bot)

## Commands 🛠

- `/play <song name>` - play song you requested
- `/playlist` - Show now playing list
- `/song <song name>` - download songs you want quickly
- `/search <query>` - search videos on youtube with details
- `/vsong <song name>` - download videos you want quickly
- `/lyric <song name>` - lyrics scrapper
- `/vk <song name>` - generate song without download

#### Admins Only 👷‍♂️
- `/player` - open music player settings panel
- `/pause` - pause song play
- `/resume` - resume song play
- `/skip` - play next song
- `/end` - stop music play
- `/musicplayer on` - to disable music player in your group
- `/musicplayer off` - to enable music player in your group
- `/userbotjoin` - invite assistant to your chat
- `/userbotleave` - remove assistant from your chat
- `/reload` - Refresh admin list
- `/uptime` - check the bot uptime status
- `/ping` - check the bot ping status
- `/auth` - authorized people to access the admin commands
- `/deauth` - deauthorized people to access the admin commands
- `/control` - open the music player control panel

### Sudo User 🧙‍♂️
- `/stats` - see the bot statistic
- `/pmpermit on | off` turn on/off the assistant pmpermit
- `/userbotleaveall` - order the assistant to leave all groups
- `/gcast` - send a broadcast message from the assistant

### Owner Only 👨🏻‍✈️
- `/broadcast` - send a broadcast message from the bot
- `/block` - block people for using your bot
- `/unblock` - unblock people you blocked for using your bot
- `/blocklist` - show the list of all people who's blocked for using your bot

### pm-permit 💬
- `.yes` - approve user for sending message to assistant
- `.no` - disapprove user for sending message to assistant

## 🔎 Support Inline Search

## Heroku Deployment 💜
The easy way to host this bot, deploy to Heroku

[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/levina-lab/veezmusic)

## VPS Deployment 📡

```sh
sudo apt update && apt upgrade -y
sudo apt install git curl python3-pip ffmpeg -y
pip3 install -U pip
curl -sL https://deb.nodesource.com/setup_16.x | bash -
sudo apt-get install -y nodejs
npm i -g npm
git clone https://github.com/levina-lab/VeezMusic # Clone your repo.
cd VeezMusic
pip3 install -U -r requirements.txt
cp example.env .env #Use vim to edit ENVs
vim .env #Fill up your ENVs ( Steps press i to enter in insert mode then edit the file. Press Esc to exit the editing mode then type :wq! and press Enter key to save the file.)
python3 main.py # Run the bot
```

### Special Credits 💖
- [Levina](https://github.com/levina-lab): Dev
- [Tofik](https://github.com/tofikdn): Dev
- [Zxce3](https://github.com/Zxce3): Dev
- [Laky](https://github.com/Laky-64) & [Andrew](https://github.com/AndrewLaneX): PyTgCalls
- [Original Repo](https://github.com/callsmusic/callsmusic) CallsMusic
- [Veez Music Bot](https://t.me/veezmusicbot) Our Music Bot
- [RojSerBest](https://github.com/rojserbest) CallsMusic Developer
- [TeamDaisyX](https://github.com/TeamDaisyX) for base code

### Support & Updates 🎑
<a href="https://t.me/VeezSupportGroup"><img src="https://img.shields.io/badge/Join-Group%20Support-blue.svg?style=for-the-badge&logo=Telegram"></a> <a href="https://t.me/levinachannel"><img src="https://img.shields.io/badge/Join-Updates%20Channel-blue.svg?style=for-the-badge&logo=Telegram"></a>
