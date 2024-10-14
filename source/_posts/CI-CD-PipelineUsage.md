---
title: CI-CD Useage within Github
---



## Initial Setup

In order to setup a CI/CD pipeline on Github, you must initialize it within the "Actions" tab in your repo.

![alt text](<media/Screenshot 2024-09-26 150337.png>)

You will be met with this screen. From there, click "Configure". Then, there will be a file with a basic workflow file template and a .yml extension.

![alt text](<media/Screenshot 2024-09-26 150855.png>)


This is your workflow file, which is responsible for running your application continously as you edit, make changes, and push those changes to Github. You workflow file can also feature responsibilities such as logging into Docker, pushing images to Docker, running software tests, as well as installing dependencies.


## Logging into Docker