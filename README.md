# 🚀 Telegram Animated Emoji & Lottie Collection 🎨✨

> **Full collection of Telegram Animated Emojis (from Tarikul-Islam-Anik/Telegram-Animated-Emojis & Emojipedia), Lottie JSON animations, Animated WebP, and local web-ready API index!** ✈️🔥

---

## 📁 Repository Directory Structure

```text
telegram-emojipedia-collection/
├── 📄 README.md                      # 📖 Complete documentation & API guides
├── 📊 animated-index.json            # ⚡ Quick web lookup index (CDN-ready)
├── 📊 telegram-emojis.json           # 🗂️ 1,898+ Complete Unicode metadata dataset
├── 📂 animated-emojis/               # 🎞️ Full Tarikul-Islam-Anik Telegram Animated Emojis
│   ├── 📂 Activity/                  # 🎈 Party, Trophy, Games, Medals
│   ├── 📂 Animals and Nature/        # 🐶 Animals, Nature, Weather, Stars
│   ├── 📂 Food and Drink/            # 🍕 Pizza, Coffee, Drinks, Cakes
│   ├── 📂 Objects/                   # 💡 Lights, Tech, Money, Keys
│   ├── 📂 People/                    # 👋 Hands, Gestures, Faces
│   ├── 📂 Smileys/                   # 😀 Animated Smiley Faces
│   ├── 📂 Symbols/                   # ❤️ Hearts, Signs, Stars
│   ├── 📂 Travel and Places/         # 🚀 Rockets, Cars, Places
│   └── 📂 Flags/                     # 🇮🇩 Country & Special Flags
├── 📂 lotties/                       # 🎬 242+ Vector Telegram Lottie JSON animations (.json)
└── 📂 assets/                        # 🖼️ 1,817+ Static PNG emoji assets (.png)
```

---

## 🌐 How to Call Emojis directly in your Web App / HTML

You can load any animated Telegram emoji directly from JS / HTML using JSDelivr CDN / GitHub Raw:

### 1. HTML Image Tag (Animated WebP)
```html
<img src="https://cdn.jsdelivr.net/gh/Z-150/telegram-emojipedia-collection@main/animated-emojis/Smileys/Grinning%20Face.webp" alt="Grinning Face" width="64" height="64" />
```

### 2. JavaScript Fetch Example (using `animated-index.json`)
```javascript
// Fetch the index to search any emoji instantly
fetch('https://cdn.jsdelivr.net/gh/Z-150/telegram-emojipedia-collection@main/animated-index.json')
  .then(res => res.json())
  .then(data => {
    console.log("Smileys:", data.Smileys);
    // Example output item:
    // { name: "Grinning Face", slug: "grinning-face", cdn_url: "..." }
  });
```

---

## 📜 License & Credits

- **Animated Emojis Source:** [Tarikul-Islam-Anik/Telegram-Animated-Emojis](https://github.com/Tarikul-Islam-Anik/Telegram-Animated-Emojis)
- **Artwork:** Telegram Messenger ✈️ Apple 🍎
- **Dataset Maintainer:** [Z-150](https://github.com/Z-150) ⚡

*Maintained with ❤️ by Z-150.*
