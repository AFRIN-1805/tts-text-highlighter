# Synchronized Text-to-Speech with Real-Time Text Highlighting

## 📌 Project Overview
This project is a React-based frontend application that reads textual content aloud using the browser’s Text-to-Speech (TTS) API and highlights the currently spoken word in real time.

The application is designed to improve accessibility and comprehension for users with low literacy or visual impairments, especially for multilingual and rural knowledge dissemination use cases.

---

## ✨ Features
- Text-to-Speech playback using browser SpeechSynthesis API
- Real-time word-by-word text highlighting
- Play, Pause, Resume, and Stop controls
- Language selection (Indian languages supported)
- Speech rate control using a slider
- Graceful fallback when a selected language voice is unavailable
- Responsive UI using Material UI (MUI)
- Frontend-only implementation (no backend)

---

## 🌐 Supported Languages
- English (en-US)
- Hindi (hi-IN)
- Tamil (ta-IN)
- Telugu (te-IN)
- Marathi (mr-IN)
- Gujarati (gu-IN)

> Note: Language support depends on browser and OS-installed voices.

---

## 🧪 Browser Compatibility
| Browser | Status | Notes |
|-------|--------|------|
| Google Chrome | ✅ Working | Some Indian language voices may be unavailable |
| Microsoft Edge | ✅ Working | Similar behavior to Chrome |
| Mozilla Firefox | ⚠️ Partial | Limited TTS voice support |
| Opera | ⚠️ Partial | Depends on system voices |
| Safari | ⚠️ Partial | iOS restricts voice availability |

---

## 📱 Mobile Compatibility
- Fully responsive UI
- Tested on Android Chrome browser
- Text highlighting remains synchronized with audio playback
- Voice availability depends on device OS

---

## ⚠️ Known Limitations
- Browser-based Text-to-Speech does not perform automatic translation.
- Some Indian languages such as Telugu, Marathi, and Gujarati may not have voices available on all browsers or operating systems.
- When a voice is unavailable, the application gracefully falls back to English and notifies the user.

---

## 🛠️ Tech Stack
- React (Hooks-based)
- Material UI (MUI)
- Browser SpeechSynthesis API
- JavaScript (ES6)

---

## ▶️ Setup Instructions
1. Clone the repository
2. Install dependencies
   ```bash
   npm install
