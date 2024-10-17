---
title: Installation & Setup
date: 2024-10-13
---

To install Docker on windows you first will need WSL 2 **(Minimum Req. Windows 10 ver. 2004)**

## Install WSL 2: (WINDOWS ONLY) 
1) First open your windows terminal/powershell as an administrator and run the command “wsl --install” as seen below:	

<img src="/IS373_Hexo/media/WSLInstall.png" align="right" width="50%">

2) After this a download process will begin. After it's done, a reboot of the system will be required.
3) Upon reboot Ubuntu will open and you will have to input an UNIX username and a password (hidden)
    * This username and password is for the Linux that was installed. It should be kept safe and is different from the windows one you log in with. 
4) Windows files can be accessed with the path of /mnt/c

## Install Docker: (MAC, WINDOWS, and LINUX)
1) Install Docker Desktop (for your OS) from the Docker website and run the downloaded file 
    * [Official Docker Website](https://www.docker.com/get-started/) Select your current OS 
2) Upon completion of the installation it should open and ask to sign up, which is recommended
3) After this, the walkthrough will guide you in making your first “welcome” container

# Useful VS Code Extention:
* **Docker**, by Microsoft: Will allow for Docker IntelliSense (color coding, snipit suggestions, etc.) inside of Docker files. Will also allow for Images to be easily build by just left clicking and a menu to see running containers.
    * [Link to Extention](https://marketplace.visualstudio.com/items?itemName=ms-azuretools.vscode-docker) (Otherwise just search it up in VSCode) 


