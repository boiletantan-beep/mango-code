# 📖 Simple Dictionary | Arabic <-> English

A lightweight, fast, and elegant Arabic to English (and English to Arabic) dictionary web application. Designed with a modern, minimal UI, featuring real-time search, voice pronunciation, dark/light mode toggle, and recent search history tracking.

---

## ✨ Features

- ⚡ **Instant Real-Time Search**: Live lookup as you type with matching for Arabic and English vocabulary.
- 🔄 **Bi-Directional Translation**: Switch seamlessly between **Arabic ➔ English** and **English ➔ Arabic**.
- 🔊 **Voice Pronunciation**: Listen to standard English audio pronunciation powered by the browser's native `Web Speech API`.
- 📋 **One-Click Copy**: Instant button to copy word translation pairs to your clipboard with toast notifications.
- 💡 **Example Sentences & Word Types**: Displays word classification (Noun, Verb, Adjective, Phrase), phonetic guides, and example sentences in context.
- 🌙 **Dark & Light Themes**: Dynamic color themes with smooth transitions for comfortable reading.
- 🕒 **Recent Search History**: Keeps track of recent lookups saved locally in `localStorage`.
- 📱 **Fully Responsive**: Mobile-first design that adapts seamlessly to phones, tablets, and desktop screens.

---

## 🚀 Getting Started

### Option 1: Direct Run (Zero Dependencies - Recommended)
No installation or build tools required! Simply open the [`index.html`](file:///d:/mango%20app/index.html) file in any modern web browser (Chrome, Edge, Firefox, Safari):

```bash
open index.html
```

---

### Option 2: Vite React App (Optional)
If you prefer developing with React and Vite:

```bash
# Install dependencies
npm install

# Start development server
npm run dev
```

---

## 📁 Project Structure

```
d:/mango app/
├── index.html               # Standalone self-contained web app
├── package.json             # Node package manifest
├── vite.config.js           # Vite configuration
├── README.md                # Project documentation
└── src/
    ├── main.jsx             # React entry point
    ├── App.jsx              # Main React application component
    ├── index.css            # CSS variables & design system
    └── data/
        └── dictionaryData.js # Vocabulary database & search algorithm
```

---

## 🛠️ Tech Stack

- **Language**: JavaScript (ES6+), HTML5, CSS3
- **Styling**: Vanilla CSS3 with Custom Variables (CSS Variables)
- **Typography**: Cairo (Arabic) & Inter (English) via Google Fonts
- **Icons**: FontAwesome & Lucide Icons
- **Audio Engine**: Web Speech API (`window.speechSynthesis`)
- **Persistence**: Browser `localStorage`

---

## 📝 Extending Vocabulary Data

You can easily expand the dictionary entries by adding items to the `dictionaryDb` array in `index.html` or `src/data/dictionaryData.js`:

```javascript
{
  id: "21",
  ar: "شمس",
  en: "Sun",
  phonetic: "/sʌn/",
  type: "اسم (Noun)",
  exampleAr: "تشرق الشمس من الشرق.",
  exampleEn: "The sun rises in the east.",
  synonyms: ["Sunshine"]
}
```

---

## 📄 License

This project is open-source and free for educational and personal use.
