# Speech-Translation-with-Python
Translate your speech to many languages using Google Translate API
Building a Speech Translator in Python using Google Translate API.
This Project translates an audio input from an input sourse into a different language using Python.
We will use a speech recognizer to teach our program to understand our speech, then convert it to text.
Then we will define a translator to convert text to our preferred language.
At last we will use a text to speech model to output the voice.

Required Libraries:
1. speechrecognition
2. pyttsx3
3. googletrans

All these modules are free to install and use
Code to pip install:
pip install speechrecognition pytts3 googletrans

 In the project you can get an error of missing module Pyaudio especially when using the Recognizer() or Micrcophone()
 If the error occurs then follow the following steps:
  	Find your Python version by python --version 
  	The easiest way to check either you have 64 or 32 Python just open it in the terminal
  	Find the appropriate .whl file from https://www.lfd.uci.edu/~gohlke/pythonlibs/#pyaudio and download it.
	  Go to the folder where it is downloaded in the Command Prompt
	  Install the .whl file with pip for example in my case:
		  pip install PyAudio-0.2.11-cp38-cp38-win_amd64whl
