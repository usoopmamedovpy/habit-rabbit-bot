# 🐰 Habit Rabbit — Telegram bot for daily habit tracking with reminders, streaks and statistics, built on Cloudflare Workers.


Habit Rabbit is a Telegram bot for daily habit tracking with reminders, streaks and statistics.

The project was built as a pet-project to explore:
- serverless architecture
- Cloudflare Workers & KV
- cron jobs
- state-driven bot logic

---

## ✨ Features (Implemented)

- ➕ Add and remove habits
- ⏰ Per-habit daily reminders (Cloudflare Cron)
- 📊 Habit statistics:
  - current streak
  - best streak
  - missed days
- 🌍 Multi-language support (RU / EN)
- 🌎 Timezone-aware reminders
- 🔔 Scheduled background jobs
- ⚙️ Fully serverless architecture
## 📸 Screenshots

### Start

Bot start screen and language selection.

![Start](https://raw.githubusercontent.com/usoopmamedovpy/habit-rabbit-bot/f84884e20961698153c1a5be1d34c8efd419bd43/%D1%81%D1%82%D0%B0%D1%80%D1%82%20%D0%BD%D0%B0%20%D0%BF%D0%BE%D0%BB.png)

---

### Instructions

Short onboarding instructions after starting the bot.

![Instructions](https://raw.githubusercontent.com/usoopmamedovpy/habit-rabbit-bot/f84884e20961698153c1a5be1d34c8efd419bd43/insruction.png)

---

### First habit

Create your first habit.

![First habit](https://raw.githubusercontent.com/usoopmamedovpy/habit-rabbit-bot/f84884e20961698153c1a5be1d34c8efd419bd43/%D0%BD%D0%B0%D0%B7%D0%B2%D0%B2%D0%B0%D0%BD%D0%B8%D0%B5%20%D0%BF%D0%B5%D1%80%D0%B2%D0%BE%D0%B9%20%D0%BF%D1%80%D0%B8%D0%B2.%20%D0%BD%D0%B0%20%D0%BF%D0%BE%D0%BB.png)

---

### Statistics

View your current streak, best streak and missed days.

![Statistics](https://raw.githubusercontent.com/usoopmamedovpy/habit-rabbit-bot/f84884e20961698153c1a5be1d34c8efd419bd43/%D0%A1%D1%82%D0%B0%D1%82%D0%B8%D1%81%D1%82%D0%B8%D0%BA%D0%B0%20%D0%BD%D0%B0%20%D0%BF%D0%BE%D0%BB.png)

---

### Settings

Main settings and habit management screen.

![Settings](https://raw.githubusercontent.com/usoopmamedovpy/habit-rabbit-bot/f84884e20961698153c1a5be1d34c8efd419bd43/%D0%9D%D0%B0%D1%81%D1%82%D1%80%D0%BE%D0%B9%D0%BA%D0%B8%20%D0%BD%D0%B0%20%D0%BF%D0%BE%D0%BB.png)

---

### Reminder setup

Configure daily reminders for a habit.

![Reminder setup](https://raw.githubusercontent.com/usoopmamedovpy/habit-rabbit-bot/f84884e20961698153c1a5be1d34c8efd419bd43/%D0%BD%D0%B0%D0%BF%D0%BE%D0%BC%D0%B8%D0%BD%D0%B0%D0%BD%D0%B8%D1%8F%20%D0%BD%D0%B0%20%D0%BF%D0%BE%D0%BB.png)

---

### Incoming reminder

Example of a received reminder notification.

![Incoming reminder](https://raw.githubusercontent.com/usoopmamedovpy/habit-rabbit-bot/f154f224d541f097fac193db51ecd49d53c07f3d/rimender.png)

---

### Timezone setup

Configure your timezone for accurate reminders.

![Timezone setup](https://raw.githubusercontent.com/usoopmamedovpy/habit-rabbit-bot/f154f224d541f097fac193db51ecd49d53c07f3d/%D1%87%D0%B0%D1%81%20%D0%BF%D0%BE%D1%8F%D1%81%20%D0%BD%D0%B0%20%D0%BF%D0%BE%D0%BB(%D0%BD%D0%BE%D1%80%D0%BC).png)

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
