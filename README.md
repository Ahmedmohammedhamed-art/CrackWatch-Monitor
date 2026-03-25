# CrackWatch-Monitor
What the app does: CrackWatch Monitor is a lightweight Windows desktop app that watches r/CrackWatch for new posts and notifies you instantly.

# 🎮 CrackWatch Monitor

A lightweight Windows desktop app that monitors r/CrackWatch for new posts and sends desktop notifications.

## Features
- 🔔 Desktop notifications for new posts
- 🕒 Auto-refreshes every 5 minutes
- 🖱️ Click any post to open in browser
- 💜 Sleek dark UI
- 📦 Portable — no installation needed

## Download
Grab the latest `.exe` from [Releases](../../releases)

## Run from source
> Requires [Node.js](https://nodejs.org)
```bash
git clone https://github.com/YOUR_USERNAME/crackwatch-monitor
cd crackwatch-monitor
npm install
npm start
```

## Build portable .exe
```bash
npm run dist
```

## Tech Stack
- [Electron](https://www.electronjs.org/)
- [Reddit JSON API](https://www.reddit.com/r/CrackWatch/new.json)
- [electron-builder](https://www.electron.build/)
