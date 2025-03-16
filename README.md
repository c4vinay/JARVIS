# Voice Assistant Project

A Python-based voice assistant that can perform various tasks such as opening websites, searching Wikipedia, playing music, telling the time, and sending emails using voice commands.

## Features
- **Speech Recognition**: Listens to user commands via a microphone.
- **Text-to-Speech**: Uses `pyttsx3` to respond via voice.
- **Wikipedia Search**: Retrieves and speaks a short summary.
- **Open Websites**: Opens YouTube, Google, and Stack Overflow.
- **Play Music**: Plays a song from a specified directory.
- **Tell Time**: Announces the current time.
- **Send Emails**: Sends emails using Gmail (requires app password setup).

## Installation
### Prerequisites
Make sure you have **Python 3.6+** installed. Install the required libraries using:

```sh
pip install pyttsx3 speechRecognition wikipedia smtplib
```

## Usage
Run the script using:

```sh
python jarvis.py
```

Speak commands such as:
- "Open YouTube"
- "Search Wikipedia for Python programming"
- "Play music"
- "What is the time?"
- "Email to Vinay"

## Email Configuration
To send emails, enable **2-Step Verification** for your Google account and generate an **App Password**:
1. Go to [Google App Passwords](https://myaccount.google.com/apppasswords).
2. Generate a 16-character password.
3. Replace the placeholder in the script with your App Password.

## Contributing
Feel free to fork this repository and contribute by adding new features!

## License
This project is licensed under the MIT License.

---
**Author**: Vinay

