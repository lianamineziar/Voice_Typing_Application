# 🎙 Voice Typing Application

Voice Typing is a simple desktop application built using Python and Tkinter that allows users to type text using their voice.  
It listens through the system microphone, converts speech into text using speech recognition, and automatically types the recognized text wherever the cursor is placed.

This application is useful for hands-free typing, accessibility, and productivity tasks.

---

## ✨ Features

- 🎤 Convert speech to text in real time
- ⌨ Automatically types recognized text using keyboard simulation
- ▶ Start and ⏹ Stop listening controls
- 🧾 Status indicator (Listening / Stopped / Errors)
- 🖥 Lightweight Tkinter GUI
- 🌐 Uses Google Speech Recognition API

---

## 🛠 Tech Stack

- **Python 3**
- **Tkinter** – GUI
- **SpeechRecognition** – Speech to text
- **PyAutoGUI** – Keyboard typing automation
- **PyAudio** – Microphone access (dependency for speech recognition)

---

## 📁 Project Structure

- voice-typing/
- │
- ├── main.py # Main application file
- ├── README.md # Project documentation
- └── requirements.txt # Dependencies

---

## 📦 Installation

### 1️⃣ Clone the repository

```bash
git clone https://github.com/your-username/voice-typing.git
cd voice-typing
```

### 2️⃣ Install dependencies

```bash
pip install -r requirements.txt
```

### ⚠ Important:

```PyAudio``` installation may require extra steps (see below).

## 🎧 PyAudio Installation Help

### Windows

```bash
pip install pipwin
pipwin install pyaudio
```

### Linux (Ubuntu/Debian)

```bash
sudo apt install portaudio19-dev python3-pyaudio
pip install pyaudio
```

### ▶️ How to Use

Run the application:

1. ```bash python main.py```

2. Place the cursor where you want text to be typed (e.g., Notepad, Browser, Editor)

3. Click Start

4. Speak clearly

5. Your speech will be typed automatically

6. Click Stop to stop listening
