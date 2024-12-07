Multilingual Interaction Chatbot
This project is a multilingual chatbot with speech recognition and text-to-speech capabilities, designed to interact with users in multiple languages. It uses Natural Language Processing (NLP), Google Translate API, and voice input/output for seamless user communication.

Features
Speech Recognition: Recognizes voice input in multiple languages.
Multilingual Support: Translates speech and text between different languages.
Text-to-Speech: Converts chatbot responses back into speech.
FFmpeg Integration: Used for handling audio and video processing tasks.
Requirements
Python Libraries
speech_recognition - For recognizing speech input.
googletrans - For language translation.
pyttsx3 - For text-to-speech conversion.
pyaudio - For handling audio input/output.
FFmpeg - For audio/video processing (for advanced use cases like recording and editing
FFmpeg Setup
FFmpeg is required for audio/video processing tasks, and it is integrated into the project for functionalities like recording or processing audio.

Steps to Download and Install FFmpeg:
Download FFmpeg: Go to the official FFmpeg Downloads page and download the appropriate version for your operating system.

Extract the Downloaded FFmpeg: After downloading the FFmpeg zip file, extract it to a folder, for example, D:\smec\multilingual_interaction\ffmpeg.

Set FFmpeg Path:

For FFmpeg to be accessible from anywhere on your system, add its bin directory to your system's environment variables.

On Windows:

Open System Properties → Advanced System Settings.
Click on Environment Variables.
Under System Variables, find the Path variable and click Edit.
Add the full path to the bin directory in the extracted FFmpeg folder ("file path from bin directory").
Click OK and restart your system.


Example Interaction

User speaks in English: The bot listens to the voice input, processes the language, and responds in the same language.
User speaks in French: The bot detects French, translates it to the bot's primary language (if needed), and responds in French.
Additional Features to Explore
Speech-to-Text: Convert your voice commands into text that the bot can process.
Text-to-Speech: The chatbot will read its responses out loud.
Multilingual Interaction: Supports multiple languages through speech recognition and translation.
Troubleshooting
PyAudio Installation Issue: If you encounter issues installing PyAudio, refer to the PyAudio Installation Guide.

FFmpeg Path Issues: If FFmpeg is not recognized, make sure you correctly added its path to the system environment variables as explained above.

Speech Recognition Not Working: Ensure your microphone is properly set up and accessible by Python. If there’s no audio input, check the audio device settings on your computer.
