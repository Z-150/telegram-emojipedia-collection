# 🚀 Telegram Emoji Collection & Dataset 🎨

> **The ultimate Telegram Emoji PNG asset dataset scraped directly from Emojipedia.**  
> Contains **1,898+ Telegram / Apple styled emoji PNG assets** neatly categorized with Unicode metadata and JSON index! ✨🎉

---

## 📁 Repository Directory Structure

```text
telegram-emojipedia-collection/
├── 📄 README.md                      # 📖 Comprehensive documentation (You are here!)
├── 📊 telegram-emojis.json           # 🗂️ Complete JSON metadata dataset index
└── 📂 assets/                        # 🖼️ Full high-resolution PNG emoji assets
    ├── 📂 smileys-emotion/          # 😀 Smileys, faces & emotional expressions
    ├── 📂 people-body/               # 👨‍👩‍👧‍👦 People, body parts & gestures
    ├── 📂 animals-nature/            # 🐶 Animals, plants & nature elements
    ├── 📂 food-drink/                # 🍕 Food, drinks & culinary items
    ├── 📂 travel-places/             # 🚗 Vehicles, buildings & maps
    ├── 📂 activities/                # ⚽ Sports, games & hobbies
    ├── 📂 objects/                   # 💡 Electronics, tools & household items
    ├── 📂 symbols/                   # 🔣 Signs, arrows & math symbols
    └── 📂 flags/                     # 🏴‍☠️ World flags & regional emblems
```

---

## ⚡ Categories Overview & Samples

### 😀 Smileys & Emotion (168 emojis)

![grinning face](assets/smileys-emotion/grinning-face.png) `😀` | ![grinning face with big eyes](assets/smileys-emotion/grinning-face-with-big-eyes.png) `😃` | ![grinning face with smiling eyes](assets/smileys-emotion/grinning-face-with-smiling-eyes.png) `😄` | ![beaming face with smiling eyes](assets/smileys-emotion/beaming-face-with-smiling-eyes.png) `😁` | ![grinning squinting face](assets/smileys-emotion/grinning-squinting-face.png) `😆` | ![grinning face with sweat](assets/smileys-emotion/grinning-face-with-sweat.png) `😅`

### 👋 People & Body (385 emojis)

![waving hand](assets/people-body/waving-hand.png) `👋` | ![raised back of hand](assets/people-body/raised-back-of-hand.png) `🤚` | ![hand with fingers splayed](assets/people-body/hand-with-fingers-splayed.png) `🖐️` | ![raised hand](assets/people-body/raised-hand.png) `✋` | ![vulcan salute](assets/people-body/vulcan-salute.png) `🖖` | ![rightwards hand](assets/people-body/rightwards-hand.png) `🫱`

### 🐵 Animals & Nature (153 emojis)

![monkey face](assets/animals-nature/monkey-face.png) `🐵` | ![monkey](assets/animals-nature/monkey.png) `🐒` | ![gorilla](assets/animals-nature/gorilla.png) `🦍` | ![orangutan](assets/animals-nature/orangutan.png) `🦧` | ![dog face](assets/animals-nature/dog-face.png) `🐶` | ![dog](assets/animals-nature/dog.png) `🐕`

### 🍇 Food & Drink (135 emojis)

![grapes](assets/food-drink/grapes.png) `🍇` | ![melon](assets/food-drink/melon.png) `🍈` | ![watermelon](assets/food-drink/watermelon.png) `🍉` | ![tangerine](assets/food-drink/tangerine.png) `🍊` | ![lemon](assets/food-drink/lemon.png) `🍋` | ![lime](assets/food-drink/lime.png) `🍋‍🟩`

### 🌍 Travel & Places (218 emojis)

![globe showing Europe-Africa](assets/travel-places/globe-showing-europe-africa.png) `🌍` | ![globe showing Americas](assets/travel-places/globe-showing-americas.png) `🌎` | ![globe showing Asia-Australia](assets/travel-places/globe-showing-asia-australia.png) `🌏` | ![globe with meridians](assets/travel-places/globe-with-meridians.png) `🌐` | ![world map](assets/travel-places/world-map.png) `🗺️` | ![map of Japan](assets/travel-places/map-of-japan.png) `🗾`

### 🎃 Activities (85 emojis)

![jack-o-lantern](assets/activities/jack-o-lantern.png) `🎃` | ![Christmas tree](assets/activities/christmas-tree.png) `🎄` | ![fireworks](assets/activities/fireworks.png) `🎆` | ![sparkler](assets/activities/sparkler.png) `🎇` | ![firecracker](assets/activities/firecracker.png) `🧨` | ![sparkles](assets/activities/sparkles.png) `✨`

### 👓 Objects (262 emojis)

![glasses](assets/objects/glasses.png) `👓` | ![sunglasses](assets/objects/sunglasses.png) `🕶️` | ![goggles](assets/objects/goggles.png) `🥽` | ![lab coat](assets/objects/lab-coat.png) `🥼` | ![safety vest](assets/objects/safety-vest.png) `🦺` | ![necktie](assets/objects/necktie.png) `👔`

### 🏧 Symbols (223 emojis)

![ATM sign](assets/symbols/atm-sign.png) `🏧` | ![litter in bin sign](assets/symbols/litter-in-bin-sign.png) `🚮` | ![potable water](assets/symbols/potable-water.png) `🚰` | ![wheelchair symbol](assets/symbols/wheelchair-symbol.png) `♿` | ![restroom](assets/symbols/restroom.png) `🚻` | ![baby symbol](assets/symbols/baby-symbol.png) `🚼`

### 🏁 Flags (269 emojis)

![chequered flag](assets/flags/chequered-flag.png) `🏁` | ![triangular flag](assets/flags/triangular-flag.png) `🚩` | ![crossed flags](assets/flags/crossed-flags.png) `🎌` | ![black flag](assets/flags/black-flag.png) `🏴` | ![white flag](assets/flags/white-flag.png) `🏳️` | ![rainbow flag](assets/flags/rainbow-flag.png) `🏳️‍🌈`

---

## 📄 JSON Dataset Structure (`telegram-emojis.json`)

```json
{
  "title": "Telegram Emoji Collection (Emojipedia Dataset)",
  "total_emojis": 1898,
  "emojis": [
    {
      "emoji": "😀",
      "name": "grinning face",
      "slug": "grinning-face",
      "category": "Smileys & Emotion",
      "emojipedia_url": "https://emojipedia.org/grinning-face",
      "telegram_apple_image": "https://em-content.zobj.net/social/emoji/grinning-face.png",
      "unicode_version": "1.0"
    }
  ]
}
```

---

## 🛠️ Usage & Integration

### Python Example
```python
import json

with open('telegram-emojis.json', 'r', encoding='utf-8') as f:
    dataset = json.load(f)

print(f"Total Emojis: {dataset['total_emojis']}")
for emoji_info in dataset['emojis'][:5]:
    print(f"{emoji_info['emoji']} - {emoji_info['name']} -> assets/{emoji_info['category'].lower().replace(' & ', '-').replace(' ', '-')}/{emoji_info['slug']}.png")
```

---

## 📜 License & Credits

- **Data Source:** [Emojipedia - Telegram Section](https://emojipedia.org/telegram) 🌐
- **Emoji Artwork:** Apple / Telegram 🍎/✈️
- **Dataset Maintainer:** [Z-150](https://github.com/Z-150) ⚡

*Maintained with ❤️ by Z-150.*
