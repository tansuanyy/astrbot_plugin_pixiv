# 🎨 AstrBot Pixiv Suite

🌐 Language: [简体中文](README.md) | **English**

---

<div align="center">

A powerful all-in-one plugin for AstrBot.

Combining Pixiv, JMComic, NetEase Music, Weather Forecasts, Hitokoto Quotes, Femboy Images, and DG-LAB Device Control into a single modern plugin.

---

![Python](https://img.shields.io/badge/Python-3.10+-blue)
![AstrBot](https://img.shields.io/badge/AstrBot-3.4+-green)
![Version](https://img.shields.io/badge/Version-v1.3.0-orange)
![License](https://img.shields.io/badge/License-MIT-yellow)

</div>

---

## ✨ Features

| Feature | Description |
|----------|-------------|
| 🎨 Pixiv | Random illustrations, tag filtering, artist search, R18 support |
| ✨ Hitokoto | Random quotes from anime, literature, games, movies and more |
| 🌤️ Weather | Real-time weather information and 3-day forecast |
| 👗 Femboy | Random femboy image retrieval |
| 📚 JMComic | Comic search, details, chapters and recommendations |
| 🎵 NetEase Music | Song search, playback links and music information |
| 🔌 DG-LAB | Full DG-LAB Socket V2 device management and control |

---

## 🚀 Why Choose This Plugin?

### All-In-One Solution

Instead of installing multiple plugins, this project provides:

- Pixiv Integration
- JMComic Integration
- Music Search
- Weather Query
- Daily Quotes
- DG-LAB Device Control

All inside a single package.

---

### High Performance

Built with:

- asyncio
- aiohttp
- websockets

Fully asynchronous architecture ensures fast response times and efficient resource usage.

---

### Multi-User Support

DG-LAB subsystem supports:

- Device isolation
- Independent sessions
- Concurrent users
- Automatic reconnection
- Connection pooling

---

## 📦 Installation

### AstrBot Marketplace

Search for:

```text
astrbot_plugin_pixiv
```

inside the AstrBot Plugin Marketplace.

### Manual Installation

```bash
cd AstrBot/data/plugins

git clone https://github.com/backrooms-yrc/astrbot_plugin_pixiv.git
```

Install dependencies:

```bash
pip install aiohttp>=3.8.0
pip install websockets>=10.0
```

---

## 📋 Requirements

| Component | Version |
|------------|------------|
| Python | >= 3.10 |
| AstrBot | >= 3.4.0 |
| aiohttp | >= 3.8.0 |
| websockets | >= 10.0 |

---

## 🎯 Core Commands

### Pixiv

```text
/pixiv
/pixiv r18
/pixiv tag:catgirl
/pixiv keyword:miku
```

---

### Hitokoto

```text
/hitokoto
/hitokoto a
/hitokoto i
```

---

### Weather

```text
/weather Tokyo
/weather Beijing
/weather Shanghai
```

---

### Music

```text
/music Night Dancer
/music search Eason Chan
```

---

### JMComic

```text
/jm search genshin
/jm detail 123456
/jm chapter 123456
```

---

### DG-LAB

```text
/dglab bind
/dglab status
/dglab shock A 50 pulse 10
```

---

## 🏗 Architecture

```text
AstrBot
    │
    ▼
AstrBot Pixiv Suite
    │
    ├── Pixiv API
    ├── Hitokoto API
    ├── Weather API
    ├── Femboy API
    ├── JMComic API
    ├── NetEase API
    └── DG-LAB Socket V2
```

---

## 🌟 Project Highlights

- Modern Async Architecture
- Production Ready
- Rich Command System
- Extensive Error Handling
- Multi-User DG-LAB Support
- Easy Installation
- MIT Licensed
- Open Source

---

## 🤝 Contributing

Contributions, issues and feature requests are welcome.

Feel free to submit pull requests or open discussions.

---

## 📜 License

Released under the MIT License.

---

## ❤️ Acknowledgements

- LeiZ API
- AstrBot
- DG-LAB Open Source Project
- Open Source Community

---

<div align="center">

Made with ❤️ by Tansuan

</div>
