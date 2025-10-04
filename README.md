# 🎙️ Anonymous Voice Chat Roulette for Telegram

> Connect strangers through anonymous voice conversations with WebRTC technology

A production-ready Telegram bot that randomly matches users for voice conversations. Built with modern web technologies and designed for immediate deployment.

![License](https://img.shields.io/badge/license-Commercial-blue)
![Node](https://img.shields.io/badge/node-%3E%3D16.0.0-brightgreen)

## 📸 Screenshots

<img src="screenshots/voicebot (1).png" width="250">
<img src="screenshots/voicebot (2).png" width="250">
<img src="screenshots/voicebot (3).png" width="250">
<img src="screenshots/voicebot (4).png" width="250">
<img src="screenshots/voicebot (5).png" width="250">
<img src="screenshots/voicebot (6).png" width="250">
<img src="screenshots/voicebot (7).png" width="250">
<img src="screenshots/voicebot (8).png" width="250">
<img src="screenshots/voicebot (9).png" width="250">

## ✨ Key Features

- **🎲 Random Matching** - Instantly connects users for voice conversations
- **🔒 Complete Anonymity** - No personal data shared between users
- **🎙️ WebRTC Voice** - High-quality peer-to-peer audio
- **👤 Smart Filters** - Gender and age-based matching
- **⭐ Rating System** - Thumbs up/down with detailed feedback options
- **📱 Mini App Interface** - Modern Telegram Web App UI
- **🌓 Dark/Light Themes** - Automatic theme switching
- **📊 User Statistics** - Track conversations and time spent
- **🚀 Production Ready** - Deployed and tested on Heroku

## 🛠️ Tech Stack

**Backend:**
- Node.js + Express
- Socket.io for real-time signaling
- node-telegram-bot-api

**Frontend:**
- Vanilla JavaScript
- Telegram Mini Apps API
- WebRTC for P2P audio

**Deployment:**
- Heroku (with Procfile)
- Docker ready
- HTTPS required (for WebRTC)

## 📋 Requirements

- Node.js >= 16.0.0
- Telegram Bot Token (from [@BotFather](https://t.me/BotFather))
- HTTPS domain (production) or ngrok (development)
- npm or yarn

## 🚀 Quick Start

### Installation
```bash
git clone https://github.com/yourusername/tgvoice.git
cd tgvoice
npm install
