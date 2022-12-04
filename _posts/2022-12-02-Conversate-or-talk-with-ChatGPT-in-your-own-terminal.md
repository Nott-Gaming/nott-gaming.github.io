## Conversate or talk with ChatGPT in your own terminal

Author: [<img src="https://nott-gaming.github.io/assets/images/Axel_agent.png" alt="Axel" width="16" height="16">](https://nott-gaming.github.io/aboutus#AXEL) [Axel Fernández Curros](https://nott-gaming.github.io/aboutus#AXEL)

Guide to set up ChatGPT AI chat bot in your own terminal.

#### Install Python3 and Git
```bash
sudo apt-get install -y python3 git
```

#### Install Python dependencies
* Linux
```bash
pip3 install openai dotenv
```
* Windows
```powershell
pip install openai dotenv
```

#### Clone git repository
```bash
git clone https://github.com/Axlfc/UE5-python
```

#### Navigate to Content/Python/chatBot repository directory

#### Log into openAI web page and get your API key.

#### Edit .env file from the repository folder and paste your API Key to set the variable OPENAI_API_KEY

#### Run conversate.py to begin to conversate with the AI locally on your terminal.
* Linux
```bash
python3 conversate.py
```
* Windows
```powershell
python conversate.py
```

Use ‘exit’ or ‘quit’ words to end the conversation.

If you want the AI to talk to you using a concrete voice, you should try running talk.py script which is used to make the AI process and audio file of their response:

#### Install the required Python dependencies
* Linux
```bash
pip3 install gitpython gdown pathlib setuptools pyaudio soundfile pathlib numpy librosa SpeechRecognition
```
* Windows
```powershell
pip install gitpython gdown pathlib re subprocess pkg_resources soundfile pathlib numpy librosa SpeechRecognition
```

Run talk.py to begin to talk with the AI locally on your terminal, the voice will process and then played.
* Linux
```bash
python3 talk.py
```
* Windows
```powershell
python talk.py
```

Voice processing in talk.py script isn’t able to mantain a conversation (almost) real time with the ChatGPT AI due to long audio processing time, but it is definitely possible.
