# RasaChatbot

Implementation of Rasa Chatbot from rasa.com.  

Also implemented SpeechToText and TextToSpeech, guide from YouTube channel Innovate Yourself.

Python version 3.7.8. Virtual Environment created with PyCharm. 

Start Rasa on local server:
`rasa run -m models --endpoints.yml --port 5002 --credentials.yml`

Start Rasa chatbot:
`rasa run actions`

Enable TTS and STT:
`python voice_rasa.py`
