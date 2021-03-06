<h1 align="center">EasyModels</h1>
<p align="center">
  <a href="https://discord.gg/7VN9VZe"><img src="https://steamcdn-a.akamaihd.net/steamcommunity/public/images/clans/27090541/8dd5c907f2a0eecb73dc6a4776fc9a25878ebcdd.png" alt="Forks"></a>
  </br>
  <a href="https://pepy.tech/project/easymodels" target="_blank"><img src="https://pepy.tech/badge/easymodels" />
  <img src="https://pepy.tech/badge/easymodels/week" />
  <img src="https://pepy.tech/badge/easymodels/month" /></a>
  </br>Easily find and view pre-trained AI models through the command line
  <h1 align="center">Command Line</h1>
  <p align="center"><img src="https://github.com/M4cs/EasyModels/raw/master/easymodels.gif" /></p>
  <h1 align="center">GUI</h1>
  <p align="center"><img src="https://github.com/M4cs/EasyModels/raw/master/easymodels-gui.gif" /></p>
</p>

# What EasyModels does

EasyModels is an easy way to find and view deep learning projects and pre-trained models. It uses the modelzoo.co API (sorry ModelZoo but you didn't do a great job of hiding it so I hope you don't mind). It will allow you to find different projects based on categories they're posted with on ModelZoo. I'd like to add more APIs to this project so if you know any other ones that might work well please make a PR or open an Issue thread with it as a suggestion. 

I wrote this is literally 45 minutes and pushed out and since then there have been little one line fixes and features added here and there. If you find any bugs please open an Issue thread on this repo.

## Categories

- Computer Vision
- Natual Language Recognition
- Audio and Speech
- Generative Models
- Reinforcement Learning
- Unsupervised Learning

# License

I, Max Bridgland, hereby allow all human beings to use this project and distribute it inside their own projects with due credit. Due credit being my name and this repo's URL posted somewhere that ALL users will see by default. Enjoy :P

Copyright 2019 Max Bridgland

# How it works


Simply install from pip:

```
pip install easymodels
easymodels
```

or clone this repo and run:
```
python setup.py install
easymodels
easymodels --disable-update # disable checking for newest version

# for gui run
easymodels --gui
```

This will bring up a command line tool that will guide you through grabbing whatever models are available through the modelzoo API.
