## Stable Diffusion Installation

Author: [<img src="https://nott-gaming.github.io/assets/images/Axel_agent.png" alt="Axel" width="16" height="16">](https://nott-gaming.github.io/aboutus#AXEL) [Axel Fernández Curros](https://nott-gaming.github.io/aboutus#AXEL)
Guide to set up Stable Diffusion.
We assume that you have followed the steps in the previous post and that you have the GNU/Linux development environment system ready.

```bash
cd Linux-Auto-Customizer
git checkout stablediffusion_feature
customizer-install -v -o stableDiffusion
```
* Using Customizer's Stable Diffusion functions from command line:
```bash
stablediffusion "A cat riding a rocket from outer earth"
img2img "A cat riding a rocket from outer earth" ~/Images/cat_reference.png
stablediffusionwebui
```
* Opening the Stable Diffusion WebUI will give Stable Diffusion a nice user interface to ease its use! 😁
* By default Stable Diffusion commands from the terminal will save the images in the Images/outputs folder.

#### How to install on Windows (Spanish):
[External link](https://tinyurl.com/instalarstablediffusion)