# SPEECH-RECOGNITION

COMPANY - CODTECT IT SOLUTION

NAME - SIPRA SHARMA

INTERN ID - CT06DG741

DOMAIN - ARTIFICIAL INTELLIGENCE

DURATION - 6 WEEKS

MENTOR - NEELA SANTOSH

DESCRIPTION : This Python code is used to convert speech in an audio file into text using the SpeechRecognition and pydub libraries. The main tools used here are SpeechRecognition, which helps recognize and transcribe spoken words, and pydub, which is used to handle and convert audio files into a format that SpeechRecognition can process. First, the code takes an audio file path and loads the audio using AudioSegment from pydub. It converts the file to a WAV format with a standard sample rate and mono channel to ensure compatibility. Then, it uses the Recognizer class from SpeechRecognition to read and process the WAV file. The actual transcription is done using Google's Web Speech API, which is built into the recognize_google function. The code also includes error handling to deal with cases where the audio is not understandable or if there is a problem connecting to the API. Overall, this code demonstrates how to take a speech audio file and turn it into written text using simple and powerful Python libraries.This Python program is designed to convert speech from an audio file into written text, a process known as speech-to-text transcription. To achieve this, the code makes use of two powerful Python libraries: SpeechRecognition and pydub.

First, we import speech_recognition as sr and AudioSegment from pydub. These libraries serve different purposes in the process. The pydub library is mainly used to handle and process different audio formats. Since the SpeechRecognition library works best with WAV files (especially mono-channel and 16kHz sample rate), we use `pyd_










