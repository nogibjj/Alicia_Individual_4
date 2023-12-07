
## Individual Project 4: Auto Scaling Flask App Using Any Platform As a Service
### Demo Video:

### Flask App Link:

### Goal:

This project is aim for using Generative AI technology to create a web chat application with Flask. And it also integrates Flask with Docker for containerization and Azure for cloud deployment and auto-scaling.

### File Tree:
.
├── Dockerfile
├── LICENSE
├── Makefile
├── README.md
├── app.py
├── main.py
├── repeat.sh
├── requirements.txt
├── setup.sh
├── static
│   └── style.css
├── templates
│   ├── about.html
│   ├── home.html
│   ├── index.html
│   └── prompt.html
└── test_main.py

## How to create and proceed this project
### Containerization set-up:

1. Create a Dockerhub account and a Docker Repository for incoming Docker image.
2. Log into the Azure
3. Find the App Services in search bar
4. Click on create "Web App", in "publish" option select "Docker Container"
5. Click on top session "Docker", select Image Source as "Docker Hub", copy paste the path of Docker repository from Docker hub and click "create" to create web app at last.
6. Navigate on the left menu, click on "Configuration" under Settings, click "New application setting" and set the port name as "WEBSITES_PORT" with value of 5000

