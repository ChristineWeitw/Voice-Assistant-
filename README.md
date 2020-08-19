# Voice-Assistant-
## ActiveState Blog » How to Build a Digital Virtual Assistant in Python
Here I follow the tutorial link below to complete my own digital voice assistant in Python.
Source: https://www.activestate.com/blog/how-to-build-a-digital-virtual-assistant-in-python/

### Step 1: Installing Python
1. Speech Recognition Package – when you voice a question, we’ll need something that can capture it. The SpeechRecognition package allows Python to access audio from your machine’s microphone, transcribe audio, save audio to an audio file, and other similar tasks.
2. Text to Speech Package – our assistant will need to convert your voiced question to a text one. And then, once the assistant looks up an answer online, it will need to convert the response into a voiceable phrase. For this purpose, we’ll use the gTTS package (Google Text-to-Speech). This package interfaces with Google Translate’s API. More information can be found here.
3. Audio Playback Package – All that’s left is to give voice to the answer. The mpyg321 package allows for Python to play MP3 files.

### Step 2: Voice Input
For this task, we use the SpeechRecognition library to activate machine’s microphone, and then converts the audio to text in the form of a string.

### Step 3: Voiced Responses
This function takes whatever phrase the listen function outputs as an input, and checks what was said.
