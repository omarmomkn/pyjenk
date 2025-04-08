## Jenkins CI/CD Pipeline: Python Flask Demo App 🚀

This project demonstrates a basic **CI/CD pipeline using Jenkins** for a Python Flask web application. The pipeline automates the process of building a Docker image, running the container, and deploying the app.

---

## 💡 Project Overview

- **Tech Stack:** Python (Flask), Docker, Jenkins
- **Goal:** Automate the workflow — from cloning code to deploying a containerized web app.
- **Result:** A simple Flask app that returns `Hello from Flask + Jenkins CI/CD!` on the browser.

---

## 🧱 Folder Structure

jenkins-pipeline-python-demo-app/ │ ├── app.py # Main Flask application ├── requirements.txt # Python dependencies ├── Dockerfile # Docker instructions └── Jenkinsfile # CI/CD pipeline for Jenkins

## 🔧 Prerequisites
- Docker
- Jenkins (running on localhost:8080)
- Git

## 🚀 How to Run This Project
1. Clone the Repository
git clone https://github.com/ReddyJancyParshuram/jenkins-pipeline-python-demo-app.git
cd jenkins-pipeline-python-demo-app
2. Build the Docker Image
docker build -t flask-jenkins-app .
3. Run the Docker Container
docker run -d -p 5000:5000 flask-jenkins-app
4. Open the App in Your Browser
Visit this URL in your browser:   http://localhost:5000
You should see the message:
Hello from Flask + Jenkins CI/CD!

## 🛠️ Jenkins Pipeline Stages
Your Jenkinsfile automates the following steps:
Clone Repo – pulls the latest code from GitHub.
Build Docker Image – builds a container image from the Dockerfile.
Run Container – deploys the Flask app in a running container.

## 📷 Output
You will see this message in your browser:

Hello from Flask + Jenkins CI/CD!
