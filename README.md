<p align="center">
  <a href="https://git.io/typing-svg">
    <img src="https://readme-typing-svg.demolab.com?font=Black+Ops+One&size=80&pause=1000&color=8A2BE2&center=true&vCenter=true&width=1000&height=200&lines=INCONNU+XD+V2;VERSION+2.0.0;BY+INCONNU+BOY+TECH" alt="Typing SVG" />
  </a>
</p>

<p align="center">
  <img src="https://www.bing.com/images/search?view=detailV2&ccid=%2bAyCFVgo&id=52DC1E785B11B0D291DD339FEF32DBC0E792FC8C&thid=OIP.-AyCFVgoYHdqPBH7xAR8-wHaEK&mediaurl=https%3a%2f%2fi.ytimg.com%2fvi%2fEo6pHJeVjhs%2fmaxresdefault.jpg&cdnurl=https%3a%2f%2fth.bing.com%2fth%2fid%2fR.f80c8215582860776a3c11fbc4047cfb%3frik%3djPyS58DbMu%252bfMw%26pid%3dImgRaw%26r%3d0&exph=720&expw=1280&q=PHOTO+DUDEMON+ASMODEE&FORM=IRPRST&ck=C458787403587A3B0BB841CD22061AD9&selectedIndex=32&itb=0" width="800"/>
</p>
---

## ⭐ Fork the Repository

Click the button below to fork the repository and get your own copy:

[![FORK REPO](https://img.shields.io/badge/FORK%20REPO-Click%20Here-007ACC?style=for-the-badge&logo=github)](https://github.com/INCONNU-BOY/INCONNU-XD-V2/fork)


---
## ⚙️ GET YOUR SESSION

[![PAIR CODE](https://img.shields.io/badge/GET%20SESSION_ID-Generate%20Now-4CAF50?style=for-the-badge&logo=whatsapp)](https://inconnu-boy-tech-web.onrender.com)

---
## ⌛ WHATSAPP CHANNEL SUPPORT 

[![INCONNU BOY TECH](https://img.shields.io/badge/JOIN%20MY-WHATSAPP%20CHANNEL-25D366?style=for-the-badge&logo=whatsapp)](https://whatsapp.com/channel/0029Vb6T8td5K3zQZbsKEU1R)

---

## 🚀 Quick Deployment Options

### <br>   DEPLOY_HEROKU 

------------
 
[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://dashboard.heroku.com/new-app?template=https://github.com/INCONNU-BOY/INCONNU-XD-V2)

----------

### <br>   DEPLOY_TALKDROVE 

<a href='https://host.talkdrove.com/dashboard/select-bot/prepare-deployment?botId=51' target="_blank"><img alt='DEPLOY' src='https://img.shields.io/badge/DEPLOY-NOW-h?color=navy&style=for-the-badge&logo=visualstudiocode'/></a></p>

----------

### <br>    DEPLOY_REPLIT 

-------------

<p align="left"><a href="https://repl.it/github/INCONNU-BOY/INCONNU-XD-V2"> <img src='https://img.shields.io/badge/-REPLIT-orange?style=for-the-badge&logo=replit&logoColor=white'/></a>

--------------

### <br>   DEPLOY_KOYEB 
---------

<a href='https://app.koyeb.com/auth/signin' target="_blank"><img alt='DEPLOY' src='https://img.shields.io/badge/-KOYEB-blue?style=for-the-badge&logo=koyeb&logoColor=white'/></a>

------------

### <br>   DEPLOY_RAILWAY 


-------------

<a href='https://railway.app/new' target="_blank"><img alt='DEPLOY' src='https://img.shields.io/badge/RAILWAY-h?color=black&style=for-the-badge&logo=railway'/></a></p>

---------------

### <br>  MORE DEPLOY METHOD 

--------

### <br>    DEPLOY_GLITCH 

<a href='https://glitch.com/signup' target="_blank"><img alt='DEPLOY' src='https://img.shields.io/badge/GLITCH-h?color=pink&style=for-the-badge&logo=glitch'/></a></p>

--------

### <br>    DEPLOY_CODESPACE 

<a href='https://github.com/codespaces/new' target="_blank"><img alt='DEPLOY' src='https://img.shields.io/badge/CODESPACE-h?color=navy&style=for-the-badge&logo=visualstudiocode'/></a></p>

--------

### <br>    DEPLOY_RENDER 

<a href='https://dashboard.render.com' target="_blank"><img alt='DEPLOY' src='https://img.shields.io/badge/RENDER-h?color=maroon&style=for-the-badge&logo=render'/></a></p>



⚡ DEPLOY ON WORKFLOW ⚡

```

name: Node.js CI

on:
  push:
    branches:
      - main
  pull_request:
    branches:
      - main
  schedule:
    - cron: '0 */6 * * *'  

jobs:
  build:

    runs-on: ubuntu-latest

    strategy:
      matrix:
        node-version: [20.x]

    steps:
    - name: Checkout repository
      uses: actions/checkout@v3

    - name: Set up Node.js
      uses: actions/setup-node@v3
      with:
        node-version: ${{ matrix.node-version }}

    - name: Install dependencies
      run: npm install

    - name: Install FFmpeg
      run: sudo apt-get install -y ffmpeg

    - name: Start application with timeout
      run: |
        timeout 21590s npm start  # Limite l'exécution à 5h 59m 50s

    - name: Save state (Optional)
      run: |
        ./save_state.sh
```

## ❤️ Credits
[![GitHub - INCONNU-BOY](https://img.shields.io/badge/GitHub-INCONNU--BOY-181717?style=for-the-badge&logo=github)](https://github.com/INCONNU-BOY)

---

![MADE BY INCONNU BOY](https://img.shields.io/badge/MADE%20BY-INCONNU%20BOY-blueviolet?style=for-the-badge&logo=markdown)
