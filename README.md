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
- ## 📸 Screenshots

### Language selection

Choose your preferred language when starting the bot.

![Language selection](screenshots/старт%20на%20пол.png)

---

### First habit setup

Add your first habit and start tracking immediately.

![First habit name](screenshots/название%20первого%20прив.%20на%20пол.png)

---

### Quick start instructions

Short and clear instructions after setup.

![Instructions](screenshots/инструкция.png)

---

### Habit statistics

Track your progress with current streak, best streak and missed days.

![Statistics](screenshots/Статистика%20на%20пол.png)

---

### Settings & habit management

Manage habits, reminders and language from one place.

![Settings](screenshots/Настройки%20на%20пол.png)

---

### Timezone configuration

Timezone-aware reminders — notifications arrive at exactly the time you choose.

![Timezone](screenshots/час%20пояс%20на%20пол(норм).png)

---

### Habit reminders

Daily reminders for each habit using Cloudflare Cron triggers.

![Reminders](screenshots/напоминания%20на%20пол.png)


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
