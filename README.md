# 🌐 LinguaFlow — AI Language Translation Tool

[![Streamlit App](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)](https://codealphalanguagetranslator-4izttzry2fnid6yyvfd6bq.streamlit.app/)

> **Live Demo →** https://codealphalanguagetranslator-4izttzry2fnid6yyvfd6bq.streamlit.app/

---

## 📌 About the Project

**LinguaFlow** is an AI-powered language translation web app built as part of the **CodeAlpha Artificial Intelligence Internship (Task 1)**. It allows users to instantly translate text between 29 languages, listen to the translation via text-to-speech, and track their translation history — all through a clean, modern dark-themed UI.

---

## ✨ Features

- 🌍 **29 Languages** — English, Hindi, Tamil, Telugu, French, Japanese, Arabic, and more
- ⚡ **Instant Translation** — Powered by Google Translate (no API key required)
- 🔊 **Text-to-Speech** — Hear the translated text spoken aloud
- 📋 **Copy Translation** — Quickly copy the result
- 🗑️ **Clear** — Reset input and output in one click
- 📜 **Translation History** — Stores last 10 translations in session
- 📊 **Stats Bar** — Live count of languages, translations done, and history
- 🎨 **Dark UI** — Sleek, responsive dark-themed interface built with Streamlit

---

## 🛠️ Tech Stack

| Tool | Purpose |
|------|---------|
| Python 3 | Core programming language |
| Streamlit | Web UI framework |
| deep-translator | Google Translate API wrapper (free, no key) |
| gTTS (Google Text-to-Speech) | Audio playback of translations |

---

## 🚀 Run Locally

### 1. Clone the repository
```bash
git clone https://github.com/VarshitaGurram/CodeAlpha_LanguageTranslator.git
cd CodeAlpha_LanguageTranslator
```

### 2. Install dependencies
```bash
pip install -r requirements.txt
```

### 3. Run the app
```bash
streamlit run app.py
```

App opens at `http://localhost:8501`

---

## 📁 Project Structure

```
CodeAlpha_LanguageTranslationTool/
├── app.py            # Main Streamlit application
├── requirements.txt  # Python dependencies
└── README.md         # Project documentation
```

---

## 📦 Requirements

```
streamlit
deep-translator
gTTS
```

---

## 🌐 Supported Languages

English, Hindi, Tamil, Telugu, Kannada, Malayalam, Bengali, Marathi, Gujarati, Punjabi, Urdu, French, German, Spanish, Italian, Portuguese, Russian, Japanese, Chinese (Simplified), Korean, Arabic, Turkish, Dutch, Polish, Swedish, Greek, Thai, Vietnamese, Indonesian

---

## 📸 Screenshots

> Dark themed UI with source/target language selector, translation box, and action buttons.

---

## 👨‍💻 Author

**CodeAlpha AI Internship**
- 🔗 Live App: https://codealphalanguagetranslator-4izttzry2fnid6yyvfd6bq.streamlit.app/
- 💻 GitHub: [CodeAlpha_LanguageTranslator](https://github.com/VarshitaGurram/CodeAlpha_LanguageTranslator)

---

## 📄 License

This project was built for educational purposes as part of the CodeAlpha internship program.
