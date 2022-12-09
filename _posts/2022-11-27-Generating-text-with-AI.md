## Generating text with AI

Author: [<img src="https://nott-gaming.github.io/assets/images/Axel_agent.png" alt="Axel" width="16" height="16">](https://nott-gaming.github.io/aboutus#AXEL) [Axel Fernández Curros](https://nott-gaming.github.io/aboutus#AXEL)

Guide to generate text using GPT-Neo AI.

Continuing on text to text topic, we developed a script to generate text.

#### Install python dependencies
* Linux
```bash
pip3 install transformers
```
* Windows
```powershell
pip install transformers
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
python3 content_creator.py "An essay about Descartes" 300
```
* Windows
```windows
python content_creator.py "An essay about Nietzsche" 300
```

For an essay of 300 words, we pass the topic and the number of the word count to the script.
The output will be saved inside the contentCreator folder in the same directory where we launch the script.
Attention: At the moment, passing values greater than 2400 usually causes Buffer Overflow errors.