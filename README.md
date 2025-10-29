# IELTS Writing Test - Set Three

This is an online IELTS Writing Test application that simulates the real exam environment with security features.

## Features

- 60-minute timed test
- Two writing tasks (Task 1: Graph description, Task 2: Essay)
- Anti-cheating measures (tab switching detection, typing speed monitoring)
- PDF download of answers
- Telegram integration for submission notifications

## Deployment on Vercel

1. Fork this repository or upload the files to your GitHub account
2. Go to [vercel.com](https://vercel.com) and sign in
3. Click "New Project" and import your GitHub repository
4. Add your environment variables:
   - `TELEGRAM_BOT_TOKEN` - Your Telegram bot token
   - `TELEGRAM_CHAT_ID` - Your Telegram chat ID
5. Click "Deploy"

## Setup Telegram Bot

1. Create a bot using [@BotFather](https://t.me/BotFather) on Telegram
2. Get your bot token
3. Start a chat with your bot and send a message
4. Get your chat ID by visiting: `https://api.telegram.org/bot<YourBOTToken>/getUpdates`

## File Structure
