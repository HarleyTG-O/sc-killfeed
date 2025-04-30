# Star Citizen Kill Tracker

A lightweight, Python-based kill tracker for *Star Citizen* that monitors the game log file and sends PvP, suicide, or environmental death notifications directly to a configured Discord webhook. It includes:

- A tray icon with Start/Stop tracking options
- An optional in-game overlay (transparent overlay window)
- Real-time log monitoring
- Kill classification and detailed Discord embed notifications

## ⚙️ Features

- 🧠 Classifies deaths as PvP, Suicide, or Environmental
- 🔔 Sends formatted Discord embed alerts with timestamp, victim, killer, weapon, etc.
- 📂 Monitors `Game.log` in real time
- 🖥️ Includes a simple tray icon and optional transparent overlay

## 📥 Installation

1. **Install Python dependencies:**

```bash
pip install pystray pillow pygame requests
