## GNU/Linux game development environment

Author: [<img src="https://nott-gaming.github.io/assets/images/Axel_agent.png" alt="Axel" width="16" height="16">](https://nott-gaming.github.io/aboutus#AXEL) [Axel Fernández Curros](https://nott-gaming.github.io/aboutus#AXEL)

Guide to set up an Ubuntu workstation for videogame development.
#### Download [Ubuntu .iso](https://ubuntu.com/download/desktop){:target="_blank"}
You have two options, to install it virtually or in bare metal, chose what suits your best interests.
* Create the virtual machine in Oracle VirtualBox and add the .iso image when creating a new machine and install Ubuntu on the virtual machine in addition to installing the VirtualBox Guest Additions.*Install Ubuntu directly on the computer.
* Install Ubuntu directly on the computer via USB installation.

Once the system is installed in your computer, fire up the terminal (Ctrl + 'T') and write the following commands onto it, they will set your desktop environment and the programs you need for starting to develop videogames at ease:

#### Install Linux-Auto-Customizer:
```bash
sudo apt-get install -y git curl wget
git clone https://github.com/AleixMT/Linux-Auto-Customizer 
git checkout develop
sudo bash Linux-Auto-Customizer/src/core/install.sh -v -o customizer 
source ~/.bashrc 
```

#### Delete nautilus:
```bash
sudo apt-get purge -y nautilus
```

#### Install nemo:
```bash
sudo apt-get install -y nemo
xdg-mime default nemo.desktop inode/directory application/x-gnome-saved-search
gsettings set org.gnome.desktop.background show-desktop-icons false
gsettings set org.nemo.desktop show-desktop-icons true
```

#### REBOOT
```bash
sudo reboot
```
#### Install programs:
```bash
sudo customizer-install -v -o customizer git gitk gitcm evolution pluma vlc nemo gnome-terminal tmux libreoffice guake clementine thunderbird screenshots sysmontask geany gpaint meld sublime transmission uget rsync calculator github_desktop calibre obs caffeine
customizer-install -v -o trello drive changebg shortcuts templates shortcuts fastcommands bashfunctions gitbashfunctions ipe ipi ips documents spreadsheets keep presentation traductor youtube youtubemusic youtube-dl terminal_background prompt gitprompt blender
```
* ART:
```bash
sudo customizer-install -v -o krita gimp inkscape audacity okular freecad handbrake shotcut shotwell
customizer-install stableDiffusion
```
* PROGRAMMING:
```bash
sudo customizer-install -v -o nettools python3 nano notepadqq
customizer-install -v -o pycharm codium converters studio
```
* DESIGN:
```bash
sudo customizer-install -v -o latex dia ghostwriter
customizer-install -v -o overleaf wikipedia forms
```

#### Install Rust Language
```bash
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
```

#### Install Unreal Engine 5
[External link](https://bytexd.com/how-to-setup-and-run-unreal-engine-5-on-ubuntu){:target="_blank"}

#### Install Houdini FX
[External link](https://www.sidefx.com/faq/question/install-linux){:target="_blank"}

#### OPTIONAL:
* Samba Server:
[External link](https://www.digitalocean.com/community/tutorials/how-to-set-up-a-samba-share-for-a-small-organization-on-ubuntu-16-04){:target="_blank"}