# Google-Translator
This project aims to create a language translator using Python and the Google Translate API. Users can input text in one language, and the program will translate it to the desired target language. The project includes a graphical user interface (GUI) built with tkinter.

# Installation:

Before running the project, make sure you have the following dependencies installed:

Googletrans: This library allows communication with Google’s translation servers. Install it using pip:
pip install googletrans

Pyaudio: If you plan to use speech recognition (optional), you’ll need Pyaudio. Note that you might encounter an error related to portaudio during installation. Refer to the installation guide for details.
pip install pyaudio

SpeechRecognition: For speech-to-text functionality (optional):
pip install SpeechRecognition

gTTS (Google Text-to-Speech): To convert translated text to speech (optional):
pip install gtts

# Usage: 

Run the Python script (translator.py or any other filename you choose).
The program will prompt you to say “hello” to initiate the translation process.
After saying “hello,” the program will listen for a sentence you want to translate.
Speak the sentence, and the program will translate it from English (or any other source language) to Hindi (or any other target language).
The translated text will be saved as an audio file named captured_voice.mp3.

# Example Usage:

Initiate the translation:

Speak 'hello' to initiate the Translation!

Provide a sentence to translate:

Speak a sentence...
Phase to be Translated: "What are you doing?"

The translated audio will be played automatically.

# Note:

You can customize the source and target languages by modifying the from_lang and to_lang variables in the code.
Feel free to enhance the GUI or add more features as needed.

# Credit:

This project uses the Googletrans library for language translation.
