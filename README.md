# 🌐 Language Translation Tool

A clean, fast, and fully deployed language translation web app built with HTML, CSS, and JavaScript. Supports 25+ languages with auto-detection, text-to-speech, and a modern dark UI.

🔗 **Live Demo:** https://abeer-24.github.io/CodeAlpha_Translation-Tool

---

## ✨ Features

- 🔍 **Auto language detection** — paste any text and it detects the language automatically
- 🚩 **Country flags** on every language selector for quick visual recognition
- 🌍 **25+ languages** supported including Hindi, Urdu, Arabic, Japanese, Chinese, and more
- 📋 **One-click copy** — copy the translated text instantly
- 🔊 **Text-to-speech** — listen to the translation with correct pronunciation
- ⇄ **Swap languages** — flip source and target with one click, carries translation back
- 🌙 **Dark UI** — modern dark theme with smooth animations
- ⌨️ **Keyboard shortcut** — press `Ctrl + Enter` to translate instantly
- 📱 **Fully responsive** — works on mobile, tablet, and desktop

---

## 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| HTML5 | Structure |
| CSS3 | Styling, animations, dark theme |
| JavaScript (Vanilla) | Logic, API calls, TTS |
| MyMemory API | Free translation engine |
| GitHub Pages | Hosting & deployment |
| Git | Version control |

---

## 🚀 Getting Started

### Run locally

```bash
git clone https://github.com/Abeer-24/translation-tool.git
cd translation-tool
```

Then just open `index.html` in your browser — no build step, no dependencies.

### Deploy your own

1. Fork this repo
2. Go to **Settings → Pages**
3. Source: **Deploy from a branch → main / (root)**
4. Your site will be live at `https://YOUR_USERNAME.github.io/translation-tool`

---

## 🌐 API Used

This project uses the **[MyMemory Translation API](https://mymemory.translated.net/)** — a free, no-key-required REST API.

```
GET https://api.mymemory.translated.net/get?q={text}&langpair={src}|{tgt}
```

- Free tier: 1000 words/day
- No API key required
- Supports auto language detection

---

## 📁 Project Structure

```
translation-tool/
└── index.html       # Complete app — HTML, CSS, and JS in one file
```

---

## 📸 Preview

> Dark themed UI with country flags, smooth animations, and a clean two-panel layout for source and translated text.

---

## 🎓 About

This project was built as **Task 1** of the AI Internship program at **[CodeAlpha](https://www.codealpha.tech)**.

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).
