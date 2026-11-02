
# TaskMate - Smart To-Do List Application

## Project Description
TaskMate is a simple task management web application developed using Python and Flask. It allows users to add and delete their daily tasks.

## Technologies Used
- Python
- Flask
- HTML
- Docker
- Git and GitHub

## Features
- Add new tasks
- View tasks
- Delete tasks
- Run application using Docker

## Run Locally
1. Install Python.
2. Install Flask using:

   pip install flask

3. Run the application:

   python app.py

4. Open http://localhost:5000

## Run Using Docker
Build the Docker image:

    docker build -t taskmate .

Run the container:

    docker run -d -p 5000:5000 --name taskmate-container taskmate

Open http://localhost:5000

## Project Status
Flask application development and Docker containerization completed.

AWS ECR, EKS, GitHub Actions and Argo CD deployment are pending.
