<div align="center">

<img src="https://n.uguu.se/oAHEcWhW.jpg" alt="Anoymous Mini Bot" width="200"/>

# 🤖 Anoymous Mini

**A lightweight, privacy-focused WhatsApp bot built with Baileys.**

[![Node.js](https://img.shields.io/badge/Node.js-18%2B-green?logo=node.js&style=for-the-badge)](https://nodejs.org)
[![Baileys](https://img.shields.io/badge/Baileys-Multi--Device-blue?style=for-the-badge)](https://github.com/WhiskeySockets/Baileys)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow?style=for-the-badge)](https://opensource.org/licenses/MIT)
[![WhatsApp Channel](https://img.shields.io/badge/WhatsApp-Join%20Channel-25D366?logo=whatsapp&style=for-the-badge)](https://whatsapp.com/channel/0029VbCTghVBA1f3zXA50Z1z)

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

## ⚙️ Configuration

Before deploying, you need to add your WhatsApp number to the bot's configuration.

1. Open the **`.env`** file located in the root folder of the bot.
2. Edit the phone number line to look like this:```

PHONE_NUMBER=2567xxxxxxxx

```
   *Replace `2567xxxxxxxx` with your own WhatsApp number in international format (no `+`, no spaces).*
3. Save the file.

> **Note:** The `TELEGRAM_TOKEN` is only required for the Telegram sticker download command. You can leave it blank if you don't need it.

---

## 🚀 Deployment

Ready to get your bot online? Follow these simple steps to deploy it for free.

### Step 1: Create a Discord Account
Most free bot hosting panels require a Discord account for support and account management.
- Go to **[discord.com](https://discord.com)** and create a free account.
- Join the respective support servers for the hosting panels you choose below.

### Step 2: Sign Up for a Free Hosting Panel
Pick one of the free Node.js hosting providers below and create your account:

[![Bot-Hosting.net](https://img.shields.io/badge/Bot--Hosting.net-Sign_Up-blueviolet?style=for-the-badge)](https://bot-hosting.net/?aff=anoymous1)

[![Legacy Bot-Hosting](https://img.shields.io/badge/Legacy_Bot--Hosting-Sign_Up-blue?style=for-the-badge)](https://legacy.bot-hosting.net/?aff=1281744798277046293)

[![Katabump](https://img.shields.io/badge/Katabump-Sign_Up-orange?style=for-the-badge)](https://rl.katabump.fr/27c99a)

### Step 3: Upload & Start
Once you have signed up:
1. Create a new **Node.js** server on the panel.
2. Upload the bot files (or use the Git integration to pull your repo).
3. Set the environment variables in the panel if needed.
4. Hit **Start** to launch the bot.

---

## 📱 Usage

Once the bot is running, try these commands in any chat:

```bash
.menu
.play Shape of You
.sticker (reply to an image)
.8ball Will I be rich?
```

---

📢 Join Our WhatsApp Channel

Stay updated with new features, bug fixes, and hosting tips:

https://img.shields.io/badge/WhatsApp-Join%20Channel-25D366?logo=whatsapp&style=for-the-badge

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
