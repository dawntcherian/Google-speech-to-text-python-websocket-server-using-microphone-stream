# Google-speech-to-text-python-websocket-server-using-microphone-stream
Python WebSocket server which converts input audio stream from microphone to text using Google speech to text

<b>Setup</b>

1) Clone the repo 

    $ git clone https://github.com/dawntcherian/Google-speech-to-text-python-websocket-server-using-microphone-stream.git
2) Install pip and virtualenv if you do not already have them. 
3) Create a virtualenv with Python 3.6.4
4) Install the dependencies
    
    $ pip install -r requirements.txt
5) Provide authentication credentials to your application code by setting the environment variable GOOGLE_APPLICATION_CREDENTIALS. (Follow https://cloud.google.com/docs/authentication/getting-started)
6) Run

    $ python websocket_server.py
    
    $ python websocket_client.py
