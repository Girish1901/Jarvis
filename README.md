# Jarvis - Voice Activated AI Assistant

A Python-based voice assistant that combines speech recognition, AI capabilities, and various APIs to create a responsive virtual assistant similar to Alexa or Google Assistant.

## Features

- **Voice Recognition**: Listens for the wake word "Jarvis" and processes voice commands
- **AI Integration**: Uses GPT-3.5-turbo for intelligent responses via OpenAI API
- **Text-to-Speech**: Converts responses to natural-sounding speech output
- **Web Navigation**: Opens popular websites like Google, Facebook, YouTube, and LinkedIn
- **Music Playback**: Can play songs from a predefined music library
- **News Updates**: Fetches and reads the latest news headlines using NewsAPI

## Requirements

- Python 3.x
- Required Python packages:
  - speech_recognition
  - pyttsx3
  - openai
  - pygame
  - gTTS (Google Text-to-Speech)
  - requests

## Setup

1. Install the required packages:
```bash
pip install speech_recognition pyttsx3 openai pygame gTTS requests
```

2. Configure API Keys:
   - Add your OpenAI API key in both `main.py` and `client.py`
   - Add your NewsAPI key in `main.py`

## Usage

1. Run the main script:
```bash
python main.py
```

2. Wait for "Initializing Jarvis..." message
3. Say "Jarvis" to activate the assistant
4. Speak your command when Jarvis responds with "Ya"

## Available Commands

- "Open Google/Facebook/YouTube/LinkedIn" - Opens respective websites
- "Play [song name]" - Plays music from predefined library
- "News" - Reads latest news headlines
- Any other query will be processed through GPT-3.5-turbo for an AI response

## Note

Make sure you have a working microphone connected to your system and proper internet connectivity for the assistant to function correctly.

## License

[Add your chosen license here]
