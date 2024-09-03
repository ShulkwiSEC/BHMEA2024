# BHMEA2024 Write-Up: * 😃

## Overview
BHMEA 2024 Challnges And Writeups
Note: Some Challnge I Have Solve it And Other I Did Note So Not All Challnges Have Writeps

# How To Run Challnges Localy:
I will Use Docker Cuz It Came with it Feel Free To Use Any Thing

## Prerequisites

Before running the Docker containers, you need to have Docker installed. Follow the instructions below to install Docker and any necessary requirements.

### Installing Docker

#### On Windows and Mac

1. **Download Docker Desktop:**
   - Go to the [Docker Desktop download page](https://www.docker.com/products/docker-desktop).
   - Download and run the installer for your operating system (Windows or Mac).

2. **Install Docker Desktop:**
   - Follow the installation instructions provided by the installer.

3. **Start Docker Desktop:**
   - Once installed, open Docker Desktop from your applications menu.

#### On Linux

1. **Update Your Package Index:**
   ```
   bash
   $ sudo apt-get update
   $ sudo apt-get install apt-transport-https ca-certificates curl software-properties-common
   $ curl -fsSL https://download.docker.com/linux/ubuntu/gpg | sudo apt-key add -
   $ sudo add-apt-repository "deb [arch=amd64] https://download.docker.com/linux/ubuntu $(lsb_release -cs) stable"
   $ sudo apt-get update
   $ sudo apt-get install docker-ce
   $ sudo systemctl start docker
   $ sudo systemctl enable docker
   $ sudo docker --version # to make sure its installed
   ```

## Running a Dockerfile
You will find Dockerfile With All Challnge requite serving just unzip the challnge and you will find the Docker File

## Build the Docker Image
## Run:

````
bash

$ docker build -t my-image-name .
````
## Run the Docker Container
## Run:

````
bash

$ docker run -d -p 4000:80 my-image-name
````
## Check Running Containers
## Run:

````
bash

docker ps
````
## If You Want to View Container Logs
## Run:
````
bash

$ docker logs <container-id>
````
## Want to Stop and Remove the Container 
```` dont surrender you can do it , if you want hint contact us any time you wellcome ````
## To stop:

````
bash

$ docker stop <container-id>
````
## To remove:

````
bash

$ docker rm <container-id>
````
## Remove the Docker Image
### Run:
````
bash

$ docker rmi my-image-name
````
## شعارنا جاهزية سرعة هكير
