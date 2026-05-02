# 🚀 PyVeger

[![License](https://img.shields.io/badge/license-Personal-informational)](LICENSE)
[![Stars](https://img.shields.io/github/stars/cdn-worker-7/PyPanel?style=flat-square)](https://github.com/cdn-worker-7/PyPanel/stargazers)
[![Issues](https://img.shields.io/github/issues/cdn-worker-7/PyPanel?style=flat-square)](https://github.com/cdn-worker-7/PyPanel/issues)
[![Languages](https://img.shields.io/github/languages/top/cdn-worker-7/PyPanel?style=flat-square)](https://github.com/cdn-worker-7/PyPanel)
[![Last Commit](https://img.shields.io/github/last-commit/cdn-worker-7/PyPanel?style=flat-square)](https://github.com/cdn-worker-7/PyPanel/commits/main)

> **PyVeger** is an elegant, powerful, and highly customizable web-based management panel built with FastAPI and featuring a stunning HTML UI. Take control of your Python projects from anywhere. With features like real-time stats, integrated Discord bot, Cloudflare tunneling, and a beautiful web dashboard, PyVeger makes management effortless!

---

## ✨ Features

- ⚡ **Modern & Responsive UI**  
  Clean, mobile-friendly interface built with HTML5 and Jinja2.
- 🐍 **Python Backend**  
  Powered by FastAPI for blazing speed and flexibility.
- 📝 **Project & File Management**  
  Create, edit, upload, and manage your code and files from anywhere.
- 📊 **Live Logs & Resource Stats**  
  View real-time logs & system stats via dashboard and websockets.
- 🔒 **Secure Authentication**  
  Session-based login, custom configuration, and personal use security.
- 🌐 **Cloudflare Tunnel Integration**  
  Expose your panel securely to the world in one click.
- 🤖 **Discord Bot**  
  Manage your panel through Discord slash commands!
- 📦 **Extensible & Modular**  
  Easily add features, tweak templates, and customize config.

---

## 🚦 Quickstart

```bash
git clone https://github.com/cdn-worker-7/PyPanel.git
cd PyPanel
python3 -m venv venv
source venv/bin/activate       # Windows: venv\Scripts\activate
pip install -r requirements.txt
python app.py
```
> Then visit [http://localhost:8000](http://localhost:8000) in your web browser.

---

## 🖼️ Screenshots

<!-- Replace with your own images! -->
| Dashboard         | Live Logs           | Settings              |
|-------------------|---------------------|-----------------------|
| ![dashboard](https://placehold.co/300x180?text=Dashboard) | ![logs](https://placehold.co/300x180?text=Logs) | ![settings](https://placehold.co/300x180?text=Settings) |

<!-- For animated guide: ![Usage GIF](https://placehold.co/600x180?text=Demo+GIF) -->

---

## 🌐 Demo

<!-- Optional – Add your demo/deployment URL -->
<!-- [Live Demo](https://your-demo-url.com) -->

---

## 🧭 Project Structure

```
PyVeger/
├── app.py           # FastAPI app, routes, auth middleware
├── manager.py       # Project lifecycle & process manager
├── tunnel.py        # Cloudflare tunnel integration
├── discord_bot.py   # Discord bot for remote control
├── config.json      # Settings (credentials, tokens)
├── database.json    # Project metadata
├── requirements.txt # Python dependencies
├── templates/       # HTML UI (Jinja2)
└── static/          # CSS, JS, images
```

---

## 🛠️ Tech Stack

- **Backend:** Python 3, [FastAPI](https://fastapi.tiangolo.com/)
- **Frontend:** HTML5, Jinja2 Templates, CSS
- **Process:** psutil, subprocess
- **Live & Websockets:** FastAPI WebSockets
- **Tunnel:** Cloudflare Tunnel (cloudflared)
- **Bot:** [discord.py](https://discordpy.readthedocs.io/) (optional)
- **Dependencies:** See [`requirements.txt`](requirements.txt)

---

## 🔑 Default Credentials

- **Username:** `admin`
- **Password:** `admin`

Change these ASAP in `config.json`!

---

## 📚 Usage Examples

- **Start the panel:**  
  `python app.py`
- **Access from browser:**  
  `http://localhost:8000`
- **Make public via Cloudflare:**  
  Add your Cloudflare token in settings & start the tunnel in the UI.
- **Use Discord bot:**  
  Add your Discord bot token and allowed users in settings.

---

## 📝 License & Usage Restrictions

> **Warning: Personal Use License**  
> This software is **FOR PERSONAL USE ONLY**.  
> Commercial, educational, or organizational use requires the author's permission.  
> See [`LICENSE`](LICENSE) for terms.

---

## 🧑‍💻 Contributing

Pull requests are welcome! For significant changes, please open an issue first to discuss what you’d like to change.

---

## 🙏 Credits

- [Python](https://www.python.org/)
- [FastAPI](https://fastapi.tiangolo.com/)
- [Cloudflare Tunnel](https://developers.cloudflare.com/cloudflare-one/connections/connect-apps/)
- [discord.py](https://discordpy.readthedocs.io/)
- And all open-source contributors!

---

## 📫 Contact

Questions, issues, or feature requests?  
[Open an issue](https://github.com/cdn-worker-7/PyPanel/issues) or email: **cdn-worker-7@users.noreply.github.com**

---
