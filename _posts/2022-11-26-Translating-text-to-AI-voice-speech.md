## Translating text to AI Voice Speech

Author: [<img src="https://nott-gaming.github.io/assets/images/Axel_agent.png" alt="Axel" width="16" height="16">](https://nott-gaming.github.io/aboutus#AXEL) [Axel Fernández Curros](https://nott-gaming.github.io/aboutus#AXEL)
Guide to transform text to AI voice audio.
To continue the work of the whisper audio-to-text and text-to-text translate.py script from the previous post we create a script to convert any given text to an audio file with our own voice tone from a given 10 second audio .wav file as input.
The script has been modified to accept large amount of phrases so it would be possible to use a large amount of text and would not affect the audio quality.
#### Record your own voice
The clip should have about 8-10 seconds in a good quality. Audacity can be used to record and export the voice. Remind to export it as .wav format.

#### Install python dependencies
* Linux
```bash
pip3 install gitpython
pip3 install gdown
```
* Windows (chocolatey)
```powershell
pip install gitpython
pip install gdown
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
python3 voice_cloning.py "Whatever I write here is going to be read with the same voice" audio.wav
```
* Windows
```windows
python voice_cloning.py "Whatever I write here is going to be read with the same voice" audio.wav
```