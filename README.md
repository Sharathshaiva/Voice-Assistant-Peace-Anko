# Voice Assistant - Peace Anko

## Overview

Peace Anko is a Python-based voice assistant that recognizes speech and performs various tasks such as:

- Searching Wikipedia
- Opening websites (YouTube, Google, Amazon, etc.)
- Playing music from local storage
- Checking the current time
- Sending emails
- Searching on the web using PyWhatKit
- Telling jokes using PyJokes

## Features

- **Speech Recognition**: Converts voice commands into text.
- **Text-to-Speech (TTS)**: Uses `pyttsx3` to generate speech responses.
- **Wikipedia Integration**: Fetches short summaries from Wikipedia.
- **Web Browsing**: Opens common websites like Google, YouTube, and Stack Overflow.
- **Music Player**: Plays local music files.
- **Email Sending**: Sends emails (requires authentication).
- **Jokes Generator**: Fetches jokes using `pyjokes`.
- **Voice Commands**: Execute different actions based on the given voice input.

## Installation

To run this project, install the required dependencies:

```sh
pip install pyttsx3 speechRecognition wikipedia pywhatkit pyjokes
```

## Libraries to Import

Ensure you import the following libraries in your Python script:

```python
import pyttsx3  # Text-to-Speech conversion
import speech_recognition as sr  # Speech recognition
import datetime  # Fetching date and time
import wikipedia  # Wikipedia search
import webbrowser  # Open websites
import os  # File operations
import smtplib  # Sending emails
import pywhatkit as kt  # Web search and automation
import pyjokes  # Fetch jokes
```

## Usage

Run the script and give voice commands:

```sh
python voice_assistant.py
```

### Example Commands:

- "Open Google"
- "Play music"
- "Tell me a joke"
- "Search Wikipedia for Python programming"

## Requirements

- Python 3.x
- Microphone for voice input

## Project Structure

```
Voice-Assistant-Peace-Anko/
│── README.md
│── voice_assistant.py
```

## License

This project is licensed under the MIT License.

## Contributors

- Sharath V

