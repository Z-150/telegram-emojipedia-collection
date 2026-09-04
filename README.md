# Telegram Emoji Collection (Emojipedia)

> Complete structured catalog of Emojis and Telemojis used on **Telegram**, compiled from [Emojipedia Telegram Vendor Page](https://emojipedia.org/telegram).

Telegram utilizes Apple emoji designs across major platforms, along with custom animated **Telemoji** sets for standalone emoji messages.

---

## 📦 Contents

- **`telegram-emojis.json`**: 1,898+ emojis mapped with:
  - Unicode character
  - CLDR / Emojipedia Name & Slug
  - Emojipedia detail URL (`https://emojipedia.org/<slug>`)
  - Telegram Apple-style PNG asset link (`https://em-content.zobj.net/social/emoji/<slug>.png`)
  - Category / Grouping
- **Telemoji Updates Included**:
  - Telemoji November 2023 (Emoji 15.0 Support)
  - Telemoji March 2023
  - Telemoji January 2023
  - Telemoji December 2022
  - Telemoji November 2022
  - Telemoji October 2022

---

## 🚀 Usage Example (Node.js / Python)

```json
{
  "emoji": "😀",
  "name": "grinning face",
  "slug": "grinning-face",
  "category": "Smileys & Emotion",
  "emojipedia_url": "https://emojipedia.org/grinning-face",
  "telegram_apple_image": "https://em-content.zobj.net/social/emoji/grinning-face.png"
}
```

---

## ⚡ License
MIT License - Free for integration in Telegram WebApps / TMA / Gateway projects.
