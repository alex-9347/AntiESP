# 🛡️ AntiESP

A lightweight **Minecraft Anti-ESP plugin** that prevents players from using **ESP, X-Ray or Freecam** to see ores/bases below Deepslate level.

Originally developed for **HugoSMP**.

> ⚠️ **Beta Warning**  
> This plugin is currently in **beta**.  
> Crashes, bugs or unexpected behavior **may occur**.  
> Please report any bugs or issues via **GitHub Issues** to help improve the plugin.

---

## ✨ Features
- Blocks visibility below Y=0
- Prevents ESP / Freecam advantages
- Client-side only (no world changes)
- No performance-heavy calculations

---

## 🔧 How It Works
- **Above Y=5**  
  The client receives **fake block updates**, forcing everything below Y=0 to render as **Deepslate**.

- **Below Y=5**  
  Real blocks are sent again and the world renders normally.

All changes are handled **client-side** using ProtocolLib.

---

## 📦 Dependencies
- **ProtocolLib** `5.4+`

---

## 🧠 Use Case
Perfect for:
- SMP servers
- Anti-cheat setups
- Preventing underground ESP abuse

---

## 🚀 Status
Actively developed & performance-focused.

---

## 🖼️ Screenshots

**Above Y=5**
![AntiESP Above Y=5](above_y5.png)
![AntiESP Above Y=5](_above_y5.png)

**Below Y=5**
![AntiESP Below Y=5](below_y5.png)
![AntiESP Below Y=5](_below_y5.png)
