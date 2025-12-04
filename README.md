# Virtual Desktop Assistant (Python)

A simple voice-controlled desktop assistant built using Python.  
It listens to voice commands and performs tasks such as opening websites, telling the date and time, searching Wikipedia, telling jokes, and opening system applications.

---

## 🚀 Features

- 🎤 Voice Recognition using SpeechRecognition  
- 🔊 Text-to-Speech responses using pyttsx3  
- 🌐 Open websites (Google, YouTube, Chrome)  
- 📅 Tells the current day  
- ⏰ Tells the current time  
- 📖 Wikipedia summaries  
- 😂 Programming jokes  
- 💻 Opens system applications (e.g., Command Prompt)  
- 👋 Friendly greeting & conversation flow  
- ✉️ Email sending support (Gmail App Password required)

---

## 📂 Project Structure

main.py # contains the full assistant logic and voice command handling


---

## 🛠 Installation & Requirements

Install required Python packages:

pip install speechrecognition pyttsx3 wikipedia pyjokes pyaudio


Some modules like `webbrowser`, `smtplib`, `datetime`, and `os` are built into Python.

> ⚠ If `pyaudio` fails to install, install it using wheels from:  
> https://www.lfd.uci.edu/~gohlke/pythonlibs/#pyaudio

---

## ▶️ How to Run

1. Connect a working microphone.  
2. Run the program:



python main.py


3. Speak commands like:

- **"open google"**  
- **"open youtube"**  
- **"which day is it"**  
- **"tell me the time"**  
- **"tell a joke"**  
- **"from wikipedia Python"**  
- **"open command prompt"**  
- **"bye"** (to exit)

---

## ✉️ Email Feature Setup (Optional)

If you want to enable email sending:

1. Replace the placeholders in the code:



your-email@gmail.com

your-password


2. Use **Gmail App Password** (NOT real password).  
   Go to:



Google Account → Security → App Passwords


3. Do NOT upload credentials to GitHub.

---

## ⚠️ Important Notes

- Speech recognition requires a stable internet connection.
- If the assistant says **"Say that again, please"**, the audio wasn't captured clearly.
- The script is intended for personal learning and automation, not production use.
- Keep your email credentials private.

---

## 🧪 Example Commands

| Command | Action |
|--------|--------|
| "open google" | Opens Google |
| "open youtube" | Opens YouTube |
| "open chrome" | Opens Chrome |
| "which day is it" | Tells the day |
| "tell me the time" | Tells the time |
| "from wikipedia Elon Musk" | Reads a summary |
| "tell a joke" | Tells a random joke |
| "open command prompt" | Opens CMD |
| "bye" | Exits the assistant |

---

## 🧠 Built With

- Python  
- SpeechRecognition  
- pyttsx3  
- Wikipedia API  
- Pyjokes  
- SMTP  
- OS Automation  

---

## 👨‍💻 Author

**Nuthi Pranav**  
A Python-based desktop automation project for practicing voice control, automation, and API integration.
