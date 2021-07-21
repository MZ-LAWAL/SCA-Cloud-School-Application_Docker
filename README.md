Steps to create a docker images.
Deployment of docker file to github repo
Step 1: download docker desktop
Step 2: install docker desktop. Make sure Visualization is enabled st BIOS, WSL (Windows subsystem for Linus) and other requirements is meet. 
Step 3: check HyperV and make sure it is intalled and working.
Step 4: Check Virtual Machine Platform from Windows Features.
Step 5: Create a Directory for the Website.
Step 6:  Create a file called Dockerfile
            Place the following contents into the Dockerfile

            FROM nginx:alpine
            COPY . /usr/share/nginx/html