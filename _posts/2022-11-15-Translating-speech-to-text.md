## Translating speech to text

Author: [<img src="https://nott-gaming.github.io/assets/images/Axel_agent.png" alt="Axel" width="16" height="16">](https://nott-gaming.github.io/aboutus#AXEL) [Axel Fernández Curros](https://nott-gaming.github.io/aboutus#AXEL)

With the following script we will be able to get text from an audio in any language and write it to English as well as translating the same text to any language.

#### Install ffmpeg
* Linux
```bash
sudo apt install ffmpeg
```
* Windows (chocolatey)
```powershell
choco install ffmpeg
```

#### Install python dependencies
```bash
pip install git+https://github.com/openai/whisper.git jiwer
pip install langdetect
pip install googletrans==4.0.0-rc1
```

#### Clone repository
```bash
git clone https://github.com/Axlfc/UE5-python
```

#### Navigate into the script folder from the repository directory
```bash
cd UE5-python/Content/Python
```

#### Run the python script
* Linux
```bash
python3 translator.py audio.wav
python3 translator.py "This is a test" "es"
```
* Windows
```windows
python translator.py audio_file.wav "es"
python translator.py "¿Hola qué tal te va?" "en"
```