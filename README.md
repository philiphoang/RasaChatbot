# RasaChatbot

Implementation of Rasa Chatbot from rasa.com.  

Also implemented SpeechToText and TextToSpeech, guide from YouTube channel Innovate Yourself.

Python version 3.7.8. Virtual Environment created with PyCharm. 

## To run Rasa Chatbot with UI 
Run on local server:
`rasa x`

## To run Rasa Chatbot with TTS and STT
Start Rasa on local server:
`rasa run -m models --endpoints endpoints.yml --port 5002 --credentials credentials.yml`

Start Rasa chatbot:
`rasa run actions`

Enable TTS and STT:
`python voice_rasa.py`
