# Voice Assistant running on Bing and GPT-3.5-turbo

This Python script is a voice assistant that uses various natural language processing (NLP) and machine learning (ML) techniques to understand and respond to user input. The assistant can respond to prompts related to both Microsoft Bing and GPT-3.5-turbo API services.

## Installation

This script requires the following Python libraries:

- openai
- asyncio
- re
- whisper
- speech_recognition
- gtts
- playsound

You will also need to have an API key for the OpenAI API.

## Usage

To use the voice assistant, run the script and speak one of the following wake words: "ok bing" or "ok chat". The assistant will then prompt you to speak a command or question.

If you use the "ok bing" wake word, the assistant will use the `EdgeGPT` library to respond to your prompt. If you use the "ok chat" wake word, the assistant will use the GPT-3.5-turbo API to respond to your prompt.

The assistant uses the `whisper` library for speech-to-text conversion and the `gtts` library for text-to-speech synthesis.

By default, the assistant will save synthesized speech to an mp3 file named "text.mp3". This can be modified by changing the `audio_file` variable in the script.
