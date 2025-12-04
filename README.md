# Real-Time-Voice-Translation
A real-time voice translation application built using Python, Speech Recognition, Deep Translator, and gTTS. It captures speech from the microphone, converts it into text, translates it into the selected language, and plays the translated audio instantly. A simple Tkinter GUI makes it easy to use for multilingual communication.

# Real-Time Voice Translator 🔊🎙️

A real-time voice translation application built using **Python**, **Tkinter**, and **Google APIs**.  
The app listens to the user's speech, converts it into text, translates it into another language, and plays back the translated speech as audio — all in real time.

---

## ✨ Features
- 🎧 Live speech recognition using microphone
- 🌍 Translate between multiple world languages
- 🗣️ Converts translated text back to speech instantly
- 🖥️ Simple and user-friendly GUI
- 🔠 Supports transliteration for Indian languages
- 🚫 Say **“stop”** to end speech input instantly

---

## 🛠️ Tech Stack
| Component | Technology Used |
|----------|----------------|
| GUI | Tkinter |
| Speech Recognition | Google Speech Recognition API |
| Translation | Deep Translator (Google Translator API) |
| Text-to-Speech | gTTS |
| Multithreading | Python threading |
| Packaging | cx_Freeze |

---

## 📌 Supported Languages
✔️ English, Hindi, Tamil, Telugu, Kannada, Bengali, Gujarati, Punjabi, Spanish, French, German, Korean, Japanese, Chinese and more…

---

## 📦 Installation & Setup

### 1️⃣ Install required packages
```bash
pip install gTTS playsound speechrecognition deep-translator googletransliteration tkinter

python main.py

python setup.py build

