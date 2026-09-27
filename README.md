<div align="center">

<img src="https://n.uguu.se/oAHEcWhW.jpg" alt="Anoymous Mini Bot" width="200"/>

# 🤖 Anoymous Mini Bot

**A lightweight, privacy-focused WhatsApp bot built with Baileys.**

[![Node.js](https://img.shields.io/badge/Node.js-18%2B-green?logo=node.js)](https://nodejs.org)
[![Baileys](https://img.shields.io/badge/Baileys-Multi--Device-blue)](https://github.com/WhiskeySockets/Baileys)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![WhatsApp Channel](https://img.shields.io/badge/WhatsApp-Join%20Channel-25D366?logo=whatsapp)](https://whatsapp.com/channel/0029VbCTghVBA1f3zXA50Z1z)

</div>

---

## 📖 Description

**Anoymous Mini** is a feature-rich WhatsApp bot designed to run on minimal server resources. It uses the **Baileys** multi-device library to connect directly to WhatsApp — no browser automation required.

Whether you want to manage groups, download media, create stickers, or just have fun with friends, Anoymous Mini has you covered. It's built to be easy to deploy on free hosting panels.

---

## ✨ Features

Here is a quick overview of what the bot can do:

*   🎵 **Downloader** — Download music, TikTok, and Instagram media.
*   🎨 **Sticker Maker** — Create static and animated stickers, convert images, and grab Telegram sticker packs.
*   🛠️ **Group Management** — Kick, promote, tag all, mute, and manage group settings.
*   🤖 **Automation** — Auto-view-once detection, auto-reactions, anti-delete, and auto-typing.
*   🎉 **Fun & Utility** — Play 8-ball, flip coins, translate text, generate secure passwords, and more.
*   👑 **Owner Controls** — Full control over bot mode, prefix, sudo access, and broadcasting.

---

## 🚀 Installation & Setup

### 1. Clone the Repository

```bash
git clone https://github.com/BASH-ha/Anoymous-mini.git
cd Anoymous-mini
```

2. Install Dependencies

```bash
npm install
```

3. Configure Environment Variables

Create a .env file in the root folder and add:

```env
PHONE_NUMBER=256701487186
TELEGRAM_TOKEN=your_telegram_bot_token_here
```

· PHONE_NUMBER — Your bot's WhatsApp number in international format (no +, no spaces).
· TELEGRAM_TOKEN — Only required if you plan to use the .tg command. Leave blank otherwise.

4. Start the Bot

```bash
npm start
```

The first time you run it, you'll see a pairing code in the terminal. Open WhatsApp on your phone, go to Settings → Linked Devices → Link with phone number, and enter the code.

Once linked, the bot will connect and you're ready to go!

---

⚙️ Configuration

File Purpose
.env Phone number & Telegram token
data/prefix.json Change the command prefix (default: .)
data/mode.json Toggle between public and private mode
data/sudo.json List of sudo (trusted) numbers

You can edit these files directly or use in-bot commands like .setprefix and .mode.

---

🖥️ Hosting Options

You can run Anoymous Mini on any Node.js host. Here are some recommended options:

Host Link
Bot-Hosting.net https://bot-hosting.net/?aff=anoymous1
Legacy Bot-Hosting https://legacy.bot-hosting.net/?aff=1281744798277046293
Katabump https://rl.katabump.fr/27c99a

All three support Node.js and are free to start. Just upload the bot files, set the environment variables, and hit Start.

---

📱 Usage

Once the bot is running, try these commands in any chat:

```
.menu
.play Shape of You
.sticker (reply to an image)
.8ball Will I be rich?
```

---

📢 Join Our WhatsApp Channel

Stay updated with new features, bug fixes, and hosting tips:

👉 Join the WhatsApp Channel

---

🙏 Credits

· Baileys — WhatsApp multi-device library
· yt-search — YouTube search
· @shineiichijo/canvas-chan — Sticker generation
· Katabump — Free bot hosting
· Bot-Hosting.net & Legacy Bot-Hosting — Alternative hosting

---

📄 License

This project is licensed under the MIT License. See the LICENSE file for details.

---

<div align="center">

Made with ❤️ by BASH-ha

</div>
```
