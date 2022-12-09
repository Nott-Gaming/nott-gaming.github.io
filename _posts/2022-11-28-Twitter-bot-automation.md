## Twitter Bot Automation

Author: [<img src="https://nott-gaming.github.io/assets/images/Axel_agent.png" alt="Axel" width="16" height="16">](https://nott-gaming.github.io/aboutus#AXEL) [Axel Fernández Curros](https://nott-gaming.github.io/aboutus#AXEL)

Guide to use up a bot to automate Twitter profile.

#### Install python dependencies
* Linux
```bash
pip3 install --upgrade --user git+https://github.com/MarcosFP97/twint.git@origin/master#egg=twint
pip3 install tweepy python-dotenv
```
* Windows (chocolatey)
```powershell
pip install --upgrade --user git+https://github.com/MarcosFP97/twint.git@origin/master#egg=twint
pip install tweepy python-dotenv
```

#### Clone repository
```bash
git clone https://github.com/Axlfc/UE5-python
```

#### Navigate into the script folder from the repository directory
```bash
cd UE5-python/Content/Python/twitBot
```

#### Configure .env file 
With your API Keys from developer.twitter.com

#### Run the python script
* Linux
```bash
python3 twitBot.py "twit content"
```
* Windows
```windows
python twitBot.py "twit content"
```