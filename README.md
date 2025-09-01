# The Studio's Official Moderation & Anti-Nuke Bot

![Banner]([https://cdn.discordapp.com/attachments/1033344194472857660/1411897007056093264/stu_grey_white_black.png?ex=68b6530e&is=68b5018e&hm=0fddb8fdab6d6a24e78e82d8752cefdaa19a5b5866657fdbcba4e9d2a787cfd0&](https://cdn.discordapp.com/attachments/1033344194472857660/1411897007056093264/stu_grey_white_black.png?ex=68b6530e&is=68b5018e&hm=0fddb8fdab6d6a24e78e82d8752cefdaa19a5b5866657fdbcba4e9d2a787cfd0&))

[![Python](https://img.shields.io/badge/Python-3.9%2B-blue)](https://www.python.org/)
[![discord.py](https://img.shields.io/badge/discord.py-2.4%2B-blue.svg)](https://discordpy.readthedocs.io/)
[![License](https://img.shields.io/badge/license-MIT-green.svg)](LICENSE)

---

## ✨ Features

### 🛡 Anti-Nuke Protection
- Stops **mass channel deletions**, **mass role deletions**, and **dangerous permission grants**
- Blocks spam, unsolicited **Discord invite links**, and **NSFW images**
- Automatic timeouts / punishments configurable via setup

### ⚔ Moderation Tools
- `warn`, `removewarn`, `warnings` (with DM notification)
- `kick`, `ban`, `unban`
- `mute` / `timeout`, `unmute` / `removetimeout`
- `jail` / `unjail`
- `purge`, `purgebots`

### ⚙ Utility Commands
- `setup` wizard
- `setlog` for moderation logs
- `uptime`, `stats`, `ping`
- Server, user, role, and channel info
- Avatar & banner fetcher

### 🎯 Fun & Misc
- `say`, `embed`
- `poll`, `8ball`, `choose`, `roll`
- `quote`, `remindme`
- `github` link

---

## 📸 Screenshots
> Replace with your own screenshots
- **Setup Wizard**: ![Setup Wizard](link-to-your-screenshot)
- **Moderation Example**: ![Moderation Example](link-to-your-screenshot)
- **Anti-Nuke Log**: ![Anti-Nuke Log](link-to-your-screenshot)

---

## 🚀 Getting Started

### Prerequisites
- Python 3.9+
- Discord Bot Token
- (Optional) MongoDB connection string

### Installation
```bash
git clone https://github.com/eryxsegithub/TheStudioBot.git
cd TheStudioBot
pip install -r requirements.txt
```

### Configuration
1. Copy `config.sample.json` to `config.json`
2. Fill in your bot token and MongoDB URI (if using MongoDB)
3. Enable **Server Members Intent** and **Message Content Intent** in the [Discord Developer Portal](https://discord.com/developers/applications)

### Running the Bot
```bash
python bot.py
```

---

## 🛠 Command Examples
```bash
-warn @user Spamming in chat
-removewarn 123456
-jail @user 1d Breaking rules
-ban @user Advertising
/ban @user reason: "Toxic behavior"
```

---

## 👨‍💻 Developer
**Eryxse**  
[![GitHub]([https://img.shields.io/badge/Github-Eryxse?style=for-the-badge&logoColor=black&label=Eryxse&labelColor=black&color=black](https://github.com/eryxsegithub/TheStudioBot)

---

## 📜 License
MIT License

> Developed with my dih by Eryxse
