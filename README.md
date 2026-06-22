# 🎙️ Voice Assistant

## 📌 Project Overview

Python Voice Assistant is a simple speech-enabled assistant that listens to user commands through a microphone, converts speech into text, processes the command, and responds using text-to-speech technology.

The assistant can greet users, tell the current time, and respond to basic voice commands. This project demonstrates the integration of Speech Recognition and Text-to-Speech (TTS) technologies using Python.

---

## 🎯 Objectives

* Convert spoken commands into text.
* Respond to users using voice output.
* Implement basic voice-controlled interactions.
* Learn speech recognition and text-to-speech concepts in Python.

---

## 🛠️ Technologies Used

* Python
* SpeechRecognition
* Pyttsx3
* PyAudio

---

## ✨ Features

* Voice command recognition
* Text-to-speech responses
* Greeting functionality
* Current time announcement
* Exit command support
* Real-time microphone input

---

## 📂 Project Structure

```text
Voice-Assistant/
│
├── voice_assistant.py
├── requirements.txt
└── README.md
```

---

## 🚀 Installation

### Clone the Repository

```bash
git clone https://github.com/your-username/Voice-Assistant.git
cd Voice-Assistant
```

### Install Required Libraries

```bash
pip install SpeechRecognition
pip install pyttsx3
pip install PyAudio
```

Or install all dependencies:

```bash
pip install -r requirements.txt
```

---

## ▶️ Run the Project

```bash
python voice_assistant.py
```

After running the program, the assistant will greet you and start listening for commands.

---

## 🎤 Supported Voice Commands

| Command           | Response                   |
| ----------------- | -------------------------- |
| Hello             | Assistant greets the user  |
| What is the time? | Announces the current time |
| Exit / Quit       | Closes the assistant       |

### Example

**User:** Hello

**Assistant:** Hello! How can I help you?

**User:** What is the time?

**Assistant:** The current time is 10:30:15

**User:** Exit

**Assistant:** Goodbye!

---

## ⚙️ How It Works

1. Captures voice input using the microphone.
2. Converts speech to text using Google Speech Recognition.
3. Processes the recognized command.
4. Generates voice responses using pyttsx3.
5. Continues listening until the user says "Exit" or "Quit".

---

## 📚 Learning Outcomes

* Speech Recognition in Python
* Text-to-Speech (TTS)
* Voice Command Processing
* Exception Handling
* Real-Time Audio Processing

---

## 🔮 Future Enhancements

* Open applications using voice commands
* Web search functionality
* Weather updates
* Email automation
* AI-powered conversation support
* Smart home device integration


