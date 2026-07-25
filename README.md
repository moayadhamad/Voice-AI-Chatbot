# Voice AI Chatbot

## Description
This project is a Voice AI Chatbot developed using Python. It records the user's voice through the microphone, converts speech to text using Whisper, generates responses using the Cohere API, and converts the generated text back into speech using gTTS.

## Features
- Record voice from the microphone.
- Convert speech to text using Whisper.
- Generate AI responses using Cohere.
- Convert text to speech using gTTS.
- Continuous voice conversation until the user says "stop" or "وقف".

## Technologies Used
- Python
- Whisper
- Cohere API
- gTTS
- sounddevice
- scipy
- playsound

## Installation
Install the required libraries:

```bash
pip install openai-whisper cohere gTTS sounddevice scipy playsound==1.2.2
```

Make sure FFmpeg is installed and added to your system PATH.

## Usage
1. Add your Cohere API key to the Python code.
2. Run the program.
3. Speak into the microphone.
4. The chatbot converts your speech into text, generates a response, and reads it aloud.
5. Say **"stop"** or **"وقف"** to end the conversation.

## Project Workflow
Microphone → Whisper → Cohere → gTTS → Audio Response

