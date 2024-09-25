# cloud-run

# Google Cloud DevOps Project: Deploying a Live Weather App on Cloud Run

Within this repository, you'll discover the essential source code and deployment files needed to orchestrate a live weather app on Cloud Run using Docker. 🌐🚀

## Overview

In this project, I'll walk you through building a Python weather app, containerizing it with Docker, and deploying it on Cloud Run. We'll leverage the OpenWeather API for live weather updates! 🐍🌦️ Moreover, the entire process will be automated with a CI/CD pipeline using Google Cloud Build! 🚀

## Key Highlights

- 🐍 Developed the application using Python.
- 🌐 Integrated the robust OpenWeather API for precise and current weather information.
- 📦 Deployed the app on Google Cloud Run as a Container.
- ☁️ Automated the entire CI/CD pipeline seamlessly with Google Cloud Build and GitHub.

## Tools and Technology

- **Docker:** 🐳
- **Cloud Run:** ☁️
- **GitHub:** 🐙
- **Python:** 🐍
- **Google Cloud Build:** 🛠️
- **OpenWeather API:** 🌦️

- # cloud-run

# Google Cloud DevOps Project: Deploying a Live Weather App on Cloud Run

Within this repository, you'll discover the essential source code and deployment files needed to orchestrate a live weather app on Cloud Run using Docker. 🌐🚀

## Overview

In this project, I'll walk you through building a Python weather app, containerizing it with Docker, and deploying it on Cloud Run. We'll leverage the OpenWeather API for live weather updates! 🐍🌦️ Moreover, the entire process will be automated with a CI/CD pipeline using Google Cloud Build! 🚀

## Key Highlights

- 🐍 Developed the application using Python.
- 🌐 Integrated the robust OpenWeather API for precise and current weather information.
- 📦 Deployed the app on Google Cloud Run as a Container.
- ☁️ Automated the entire CI/CD pipeline seamlessly with Google Cloud Build and GitHub.

## Tools and Technology

- **Docker:** 🐳
- **Cloud Run:** ☁️
- **GitHub:** 🐙
- **Python:** 🐍
- **Google Cloud Build:** 🛠️
- **OpenWeather API:** 🌦️

<!--To generate API Use this website-->
https://home.openweathermap.org/ --------> copy api and paste in var.py

cd cloudrun
ls
 docker build -t gcr.io/my-first-project/weather-container:v01 .
 docker image ls
 docker run -p 8080:8080 < image id >    ----> example "docker run -p 8080:8080 3c0e09cd90cd"
 <!-- now click on webprview -->
 ip is avalible 
<!-- to delete docker image  -->
docker rmi -f gcr.io/my-first-project/weather-cont:v01 -----------------> to delete container
<!-- to run in cloud run -->
docker push gcr.io/formal-office-432704-c5/weather-container:v01

open cloud run 
create service 
choose our container 





