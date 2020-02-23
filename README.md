# CasualIrelandReader
Alexa Skill to read the headlines on Casual Ireland subreddit.
This is from the Alexa Skills w/ Python tutorial


Had to do a lot of faffing around to get this running:
Installed Visual Studio 2019 tools
Installed Win64OpenSSL-1_1_0L.exe

# Lots of messing with pip

pip install simplejson

pip3 install Werkzeug==0.16

pip install cryptography==2.1.4


Server runs at http://localhost:5000


##Steps

Run the python script

Run ngrok in the terminal
ngrok http 5000

The https url is what we want to copy to the Endpoint in developer.amazon.com
The contents of alexa_schema.json can be pasted in JSON Editor in the Interaction Model

Save, Build & Test 🤞


