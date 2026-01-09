# <p align="center">⚡ SleekTrade Terminal</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.8+-blue?style=for-the-badge&logo=python" alt="Python">
  <img src="https://img.shields.io/badge/Binance-Testnet-F0B90B?style=for-the-badge&logo=binance" alt="Binance">
  <img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white" alt="FastAPI">
  <img src="https://img.shields.io/badge/License-MIT-green?style=for-the-badge" alt="License">
</p>

<p align="center">
  <strong>An ultra-modern, professional-grade Binance Futures trading bot with a terminal-inspired Web UI and robust CLI.</strong>
</p>

---

## 📖 Overview

**SleekTrade** is a high-performance trading bot designed for the Binance Futures (USDT-M) Testnet. It provides a seamless bridge between a professional terminal experience and simplified automated trading. Built for the **Junior Python Developer** application, it demonstrates excellence in API integration, error handling, and UI/UX design.

### ✨ Key Features

- 🖥️ **Dual Interface**: Toggle between a professional **Web Terminal** and a robust **Rich CLI**.
- 📈 **Real-time Analytics**: Integrated **TradingView** live charts for instant market analysis.
- ⚡ **Advanced Execution**: Support for **Market**, **Limit**, and **Stop-Limit** orders.
- 🛡️ **Fail-Safe Logging**: Detailed logging of all API requests, responses, and errors in `logs/bot.log`.
- 🎨 **Premium UI**: Cyber-terminal aesthetic with deep-black themes and neon-mint accents.

---

## 🚀 Quick Start

### 1. Installation
The entire setup process has been automated for your convenience.

```bash
python run.py
```

### 2. Configuration
Rename `.env.example` to `.env` and provide your Binance Testnet keys:
```env
BINANCE_API_KEY=your_testnet_api_key_here
BINANCE_API_SECRET=your_testnet_api_secret_here
```

---

## 🛠️ Architecture

- **`bot.py`**: The core "BasicBot" engine implementing the official Binance REST API.
- **`app.py`**: A high-speed FastAPI backend serving the web terminal and trading API.
- **`cli.py`**: An interactive terminal interface utilizing the `rich` library.
- **`static/`**: High-performance frontend assets (Vanilla JS/CSS/HTML).
- **`run.py`**: Unified launcher for dependency management and bot startup.

---

## 📊 Requirements Checklist

- [x] **Language**: Python 3.11
- [x] **API**: Official Binance REST (python-binance)
- [x] **Markets**: USDT-M Futures (Testnet)
- [x] **Orders**: Market, Limit, and Stop-Limit (Side: Buy/Sell)
- [x] **CLI**: Validated user input with order status output
- [x] **Logging**: Complete API request/response lifecycle tracking
- [x] **UI**: Premium Web Interface with Live Charts

---

## � License
This project is licensed under the MIT License.
