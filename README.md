# 🤖 Slobos & Mr. Juice Aternos 24/7 Hosting Bot

A Minecraft bot that helps keep an Aternos server online 24/7 by automatically joining it using a Mineflayer-based bot. Perfect for SMPs or small multiplayer servers that shut down when no players are online.

---

## ✨ Features
*   ✅ **Auto-Connect**: Automatically joins your server.
*   ✅ **Infinite Uptime**: Prevents AFK kicks and server shutdowns.
*   ✅ **Smart Reconnect**: Automatically reconnects if the internet drops or server restarts.
*   ✅ **Render-Ready**: Includes "Self-Ping" to run 24/7 for FREE on Render.com.
*   ✅ **Plugin Support**: Compatible with Paper/Spigot/Bukkit (auto-auth included).

---

## 🛠️ Requirements
*   **GitHub Account**
*   **Aternos Server**
*   **Render Account** (for 24/7 hosting)
*   **Common Sense!** 🧠        

---

## 🚀 Setup Guide

We have made setup super easy! Check out the guide below:

[**Detailed Google Doc Guide**](https://docs.google.com/document/d/1Fl0dRzP6O30ehp5-QcaB11IobF8I1JJhKUipzCWiCYA/edit?tab=t.0).

---

## ⚙️ Usage
*   **Start**: Just turn on your Aternos server. The bot will join automatically.
*   **Status**: Visit the Render URL to see a status dashboard.
*   **Chat**: The bot logs chat to the console.

---

## Minecraft 26.x compatibility

Mineflayer does not currently support Minecraft's new year-based `26.x` protocol directly.
The included settings use `1.21.8` as a compatible client fallback:

1. Run the server on Paper/Spigot/Bukkit.
2. Install `ViaVersion` on the server (the setup guide also lists `ViaBackwards` and `ViaRewind`).
3. Keep the server version in `settings.json` as the version reported by the server, for example `"26.2"`.
4. Keep `"fallback-version": "1.21.8"` unless you intentionally choose another version supported by Mineflayer.

The bot will connect as the fallback client and ViaVersion will translate it for the `26.x` server.
Without ViaVersion, no Mineflayer-only code change can make an unsupported `26.x` protocol work.

---

## ⚠️ Disclaimer
This project is not affiliated with Aternos, Mojang, or Microsoft. Use at your own risk. Misuse may violate platform terms of service. This bot does not bypass Aternos queue limits; it only keeps the server active once it is online.

---

## ❤️ Credits
*   **Slobos (Discord: sloboscc)** — Original creator & idea. (The GOAT 🐐)
*   **Mr.Juice (Discord: Mr.Juice3046)** — Updates, Guide, & Maintenance.

**License**: MIT License
