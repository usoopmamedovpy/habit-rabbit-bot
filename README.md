# 🐰 Habit Rabbit — Telegram Habit Tracker Bot

Habit Rabbit is a Telegram bot for daily habit tracking with reminders, streaks and statistics.

The project was built as a pet-project to explore:
- serverless architecture
- Cloudflare Workers & KV
- cron jobs
- state-driven bot logic

---

## ✨ Features

- ➕ Add and remove habits
- ⏰ Individual reminders for each habit
- 📊 Habit statistics:
  - current streak
  - best streak
  - missed days
- 🌍 Multi-language support (RU / EN)
- 🌎 Timezone support
- 🔔 Scheduled reminders via cron
- ⚙️ Fully serverless

---

## 🧠 Tech Stack

- **Cloudflare Workers**
- **Cloudflare KV**
- **Cloudflare Cron Triggers**
- **Telegram Bot API**
- JavaScript (ES Modules)

---

## 🚀 Deployment (Cloudflare)

1. Create a Telegram bot via `@BotFather`
2. Set environment variable:
