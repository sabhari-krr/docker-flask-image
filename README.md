
# Docker image for flask app [Educational purpose]

This repository contains of 2 things, a flask app saying hello & a Dockerfile to containerize the flask application.


## Prerequisite

Docker installed in your machine.


## Usage

1) Pull the image using 

```bash
  docker pull sabhari1krr/hey-python-flask
```
- This pulls the latest image.
  
2) Run the docker using
```bash
  docker run -p 3000:3000 sabhari1krr/hey-python-flask:0.0.1.RELEASE
```
3) Open the url http://localhost:3000/. You should see the below screen
   
![image](https://github.com/user-attachments/assets/1f21817b-ffe6-4175-9e35-990bb58e1dda)
