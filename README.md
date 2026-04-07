# 🌺 English → Tamil Translator
### For Elders & Families | ஆங்கிலம் → தமிழ் மொழிபெயர்ப்பு

A **100% free, open-source** web app to translate English documents into Tamil, designed specifically for elderly users with large fonts, simple layout, and voice features.

---

## ✨ Features

- **Translate any English text** to Tamil instantly
- **4 document types pre-loaded**: Medical, Bank, Government, General
- **Upload .txt files** and translate them in bulk
- **Text-to-speech**: Hear both English and Tamil
- **Font size controls**: Small / Large / Extra Large / Maximum
- **Translation history**: Save and revisit translations
- **Download Tamil output** as a .txt file
- **100% free** — uses MyMemory's free public API (no API key needed)

---

## 🚀 How to Deploy (Free, 3 minutes)

### Option 1: GitHub Pages (Easiest)

1. Go to [github.com](https://github.com) and create a free account
2. Click **"New Repository"** → name it `tamil-translator`
3. Click **"Add file" → "Upload files"**
4. Upload `index.html`
5. Go to **Settings → Pages → Source → main branch → / (root)**
6. Your app will be live at: `https://YOUR-USERNAME.github.io/tamil-translator`

### Option 2: Netlify (One click)

1. Go to [netlify.com](https://netlify.com) (free)
2. Drag and drop the `index.html` file onto the Netlify dashboard
3. Your app is instantly live with a public URL!

### Option 3: Vercel

1. Go to [vercel.com](https://vercel.com) (free)
2. Sign up → "New Project" → drag and drop folder
3. Live in 30 seconds

### Option 4: Run Locally (No internet needed for the app itself)

Just double-click `index.html` in any web browser. Translation requires internet access to call the MyMemory API.

---

## 🔑 API Details (No Key Needed!)

This app uses the **MyMemory Free Translation API**:
- URL: `https://api.mymemory.translated.net/get`
- No API key required
- Free limit: **5,000 characters per day** (anonymous)
- To increase limit to 50,000/day: add your email as `de` parameter
- Language pair: `en|ta` (English to Tamil)

---

## 🎨 Design Principles

- **Large fonts** (adjustable from 18px to 28px)
- **High contrast** warm color scheme
- **Simple 4-tab layout**: no confusion
- **Tamil script** rendered using Google Fonts (Noto Serif Tamil)
- **No login, no signup, no ads, no tracking**

---

## 📋 Pre-loaded Documents

| Category | Sections |
|----------|----------|
| 🏥 Medical | Dosage instructions, Appointment notices, Diet & Precautions |
| 🏦 Bank | KYC updates, ATM safety tips, Account statements |
| 🏛️ Government | Ration card, Pension notices, Electricity bill |
| 📬 General | Greetings, Emergency messages, Asking for help |

---

## 🛠️ Tech Stack

| Component | Technology |
|-----------|-----------|
| Frontend | Pure HTML + CSS + JavaScript |
| Translation API | [MyMemory](https://mymemory.translated.net/) (free, open source) |
| Tamil Font | [Noto Serif Tamil](https://fonts.google.com/noto/specimen/Noto+Serif+Tamil) |
| Hosting | GitHub Pages / Netlify / Vercel (all free) |
| Backend | None needed — all client-side |

---

## 📜 License

MIT License — free to use, modify, and distribute.

---

Made with ❤️ for Tamil elders everywhere.
