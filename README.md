# Voice-Activated Assistant with GPT-3.5

## Description
This project is a Python-based voice assistant that uses OpenAI's GPT-3.5-turbo model to interact with users. The assistant listens for the wake word 'Hey' and processes voice commands using the `speech_recognition` library. It sends the input to the OpenAI API for a response and then speaks the response aloud using `pyttsx3`. 

## Features
- Voice-activated assistant triggered by the wake word 'Hey'
- Speech recognition with `SpeechRecognition` library
- Text generation via OpenAI's GPT-3.5-turbo API
- Text-to-speech using `pyttsx3` and `espeak` for speaking responses
- Customizable greeting responses based on your name

## Requirements
Make sure to install the following dependencies:
```bash
pip install openai
pip install speechrecognition
pip install pyttsx3
pip install numpy
pip install gTTS
pip install python-dotenv
