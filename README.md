# Web-App-Deployment-with-Jenkins-and-Docker


**Table of Contents**

Project Overview

This project demonstrates how to build, deploy, and manage a simple Node.js web application using Docker and Jenkins. The application is dockerized and deployed using Jenkins pipelines to ensure a seamless continuous deployment workflow.

1. NodeJs WebApplication Development

2. Dockerizing the Application

3. Setting Up the EC2 Instance

sudo apt update
sudo apt install openjdk-8-jdk -y
sudo apt install openjdk-11-jdk -y

curl -fsSL https://pkg.jenkins.io/debian-stable/jenkins.io-2023.key | sudo tee \
    /usr/share/keyrings/jenkins-keyring.asc > /dev/null

echo deb [signed-by=/usr/share/keyrings/jenkins-keyring.asc] \
    https://pkg.jenkins.io/debian-stable binary/ | sudo tee \
    /etc/apt/sources.list.d/jenkins.list > /dev/null

sudo apt update
sudo apt install jenkins -y
sudo systemctl status jenkins


![alt text](image.png)


4. Jenkins Setup

5. Required Jenkins Plugins

6. Tool Configuration

7. Credentials Setup

8. Pipeline Script

9. Deployment and Access

10. Troubleshooting
