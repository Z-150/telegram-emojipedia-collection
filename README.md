# 🚀 Telegram Animated Emoji & Lottie Collection 🎨✨

> **The ultimate Telegram Animated Emojis dataset containing Lottie JSON animations, Animated WebP, static high-resolution PNGs, and JSON index!** ✈️🔥

---

## 📁 Repository Directory Structure

```text
telegram-emojipedia-collection/
├── 📄 README.md                      # 📖 Complete documentation & samples
├── 📊 telegram-emojis.json           # 🗂️ 1,898+ Complete Unicode metadata dataset index
├── 📂 lotties/                       # 🎬 242+ Vector Telegram Lottie JSON animations (.json)
├── 📂 animated-webp/                 # 🎞️ 631+ Telegram Animated WebP stickers (.webp)
└── 📂 assets/                        # 🖼️ 1,817+ Telegram PNG emoji assets (.png)
    ├── 📂 smileys-emotion/
    ├── 📂 people-body/
    ├── 📂 animals-nature/
    ├── 📂 food-drink/
    ├── 📂 travel-places/
    ├── 📂 activities/
    ├── 📂 objects/
    ├── 📂 symbols/
    └── 📂 flags/
```

---

## 🎬 Animated Emoji Formats Available

| Format | Path / Directory | Description | Total Count |
| :--- | :--- | :--- | :--- |
| **Lottie JSON** 🎭 | `lotties/*.json` | Raw Telegram vector Lottie animation JSON files for web/mobile lottie players | **242+ JSONs** |
| **Animated WebP** 🎞️ | `animated-webp/*/*.webp` | High-quality animated WebP emoji stickers | **631+ WebPs** |
| **PNG Static** 🖼️ | `assets/*/*.png` | Clean fallback PNG icons for all Unicode categories | **1,817+ PNGs** |

---

## 🚀 How to Render Lottie Emojis in Web Apps

Use `lottie-web` or `<lottie-player>` to render these Telegram animations directly in HTML/React/Next.js:

```html
<script src="https://cdnjs.cloudflare.com/ajax/libs/lottie-web/5.12.2/lottie.min.js"></script>

<div id="telegram-emoji" style="width: 100px; height: 100px;"></div>

<script>
  lottie.loadAnimation({
    container: document.getElementById('telegram-emoji'),
    renderer: 'svg',
    loop: true,
    autoplay: true,
    path: 'https://raw.githubusercontent.com/Z-150/telegram-emojipedia-collection/main/lotties/0.json'
  });
</script>
```

---

## 📜 License & Credits

- **Data & Artwork:** Telegram Messenger / Emojipedia ✈️ Apple 🍎
- **Dataset Maintainer:** [Z-150](https://github.com/Z-150) ⚡

*Maintained with ❤️ by Z-150.*
