# Amplifier voice assistant

This is a demo that uses ChatGPT as voice assistant that receive commands instructions and returns voice response.

## Installation

To use this code, you need to have Python 3.x and the following libraries installed:

- openai
- pyaudio
- SpeechRecognition
- pyttsx3

You need to install first in your computer the following packages:

In Mac:
```
brew install portaudio
```

After that you can install the required libraries using pip:

```
pip install -r requirements.txt
```

## Usage

If all is setup properly you can start the script with the following command:

```
python3 amplifier-voice.py
```

## How works

Amplifier will receive the voice command and then call ChatGPT to process the instruction and provide a response. The response will be both printed to the console and spoken out loud using text-to-speech technology.

This code uses the ChatGPT model from OpenAI and the following libraries:

- openai - Openai provides the ChatGPT model for the responses.
- pyaudio - PyAudio provides Python bindings for the PortAudio library, which is used for audio input and output.
- SpeechRecognition - The SpeechRecognition library provides support for performing speech recognition on audio input using Google's speech recognition technology.
- pyttsx3 - pyttsx3 is a text-to-speech conversion library in Python.

