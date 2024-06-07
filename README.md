# ChatGPT-4o-Powered-Voice-Assistant-with-Python
A voice assistant (chatbot) built with OpenAI ChatGPT API and Python 

This Python program calls OpenAI's ChatGPT API to obtain responses for requests or questions from a user and then convert the text responses to voice responses. This version has been tested on Windows 10 and Windows 11. 

Following the YouTube video here to learn more about this code: 
[https://youtu.be/kE95xA5jVWQ](https://youtu.be/aTEntrEYZlU)

Before you can run this code on your computer, you will need to install the following packages on your computer to run this code: 

```console
pip install speechrecognition openai gTTS pyaudio pygame
```
If you have Python 3.12 or newer, also install the "setuptools" package,    

```console
pip install setuptools
```
In addition, you must set the API key from OpenAI as a system environment variable. If you rather want to use your API key in the Python program, then add it as, 

```python
client = OpenAI(api_key="this is your API key")
```
You may need to create a Python virtual environment first.
