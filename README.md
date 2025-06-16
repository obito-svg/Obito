# 🔄 Obito Auto Check-In Bot

![Node.js CI](https://github.com/yourusername/obito-checkin-bot/workflows/Node.js%20CI/badge.svg)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

An automated bot for handling daily check-ins on the Obito platform with multi-account support and robust error handling.

## ✨ Features

- **Multi-Account Management** - Handle unlimited accounts simultaneously
- **Intelligent Retry System** - 3 automatic retries with progressive delays
- **Stealth Mode** - Proxy support with rotation capabilities
- **Detailed Analytics** - Real-time success/failure tracking
- **Secure Logging** - Encrypted JSON logs with sensitive data protection
- **Duplicate Prevention** - Smart account detection system

## 🛠 Installation

```bash
# Clone the repository
git clone https://github.com/obito-svg/obito-checkin-bot.git
cd obito-checkin-bot

# Install dependencies
npm install

# Set up configuration
cp .env.example .env

