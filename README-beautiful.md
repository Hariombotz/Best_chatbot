
<h1 align="center">👧 Ananya – Girls BFF Chatbot 💬🤖</h1>
<p align="center">
  <img src="https://img.shields.io/badge/Python-3.10-blue?logo=python" />
  <img src="https://img.shields.io/badge/aiogram-Telegram%20Bot-blue?logo=telegram" />
  <img src="https://img.shields.io/badge/MongoDB-Database-green?logo=mongodb" />
</p>

<p align="center">Ananya is your intelligent, friendly and caring best friend chatbot 🧠💖<br>
Powered by <b>Gemini / OpenAI</b> and styled with a BFF vibe 💁‍♀️</p>

---

## 🌟 Features

- 🗨️ **Casual Chat**: Friendly replies in Hindi + English
- 🎤 **Voice Reply**: Replies to voice messages (text-based)
- 💾 **Memory**: Saves name, mood, and birthday using MongoDB
- 🎂 **Birthday Alerts**: Reminds users of saved birthdays
- 🤗 **Fun Commands**: /hug and /gif for fun BFF interactions
- 🧠 **Smart AI**: Gemini (Google AI) for intelligent and kind responses
- 🌐 **Log Channel**: Sends bot events to admin log channel
- 🛠️ **Admin Tools**: Broadcast and stats commands
- ☁️ **Deploy Ready**: Works with Koyeb, Heroku, Render

---

## 🚀 Deployment

### 🌐 Environment Variables

Make sure you set the following:

```env
BOT_TOKEN=your_telegram_bot_token
ADMIN_ID=your_numeric_user_id
LOG_CHANNEL_ID=channel_id_for_logs
MONGO_URI=your_mongodb_uri
GEMINI_API_KEY=your_gemini_api_key
```

---

### ▶️ Local Setup

```bash
git clone https://github.com/yourusername/ananya-bot.git
cd ananya-bot
pip install -r requirements.txt
python main.py
```

---

## 💬 User Commands

| Command       | Description                            |
|---------------|----------------------------------------|
| `/start`      | Starts chat with Ananya                |
| `/setname`    | Saves your name in memory              |
| `/birthday`   | Saves your birthday 🎉                 |
| `/mood`       | Mood check-in                          |
| `/hug`        | Sends a warm BFF hug 🤗                |
| `/gif`        | Sends a random fun gif                 |

---

## 🔐 Admin Commands

| Command        | Description                           |
|----------------|----------------------------------------|
| `/stats`       | Shows total user count                 |
| `/broadcast`   | Sends message to all users             |

---

## 🧠 Tech Stack

- **Python 3.10**
- **aiogram** for Telegram bot
- **Gemini AI API** (Google AI)
- **MongoDB Atlas** for memory
- **Koyeb / Heroku / Render** for cloud deploy

---

## 💖 About

Ananya is made for girls who want a bestie chatbot that truly cares.  
From remembering your birthday to cheering you up – she’s always there 🌸

---

<h4 align="center">Made with 💕 by YourName</h4>
