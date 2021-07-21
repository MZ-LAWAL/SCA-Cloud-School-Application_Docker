# Steps to create a Docker Images.

1. Download Docker Desktop
2. install Docker Desktop. Make sure Visualization is enabled st BIOS, WSL (Windows subsystem for Linus) and other requirements is meet. 
3. Check HyperV and make sure it is installed and working.
4. Check Virtual Machine Platform from Windows Features.
5. Create a Directory for the static website.
6. Create a file called Dockerfile and place below code into the Dockerfile
        ```
            FROM nginx:alpine
            COPY . /usr/share/nginx/html
        ```
# Creating first repository in Docker Hub
1. Goto  [Dockerhub](https://hub.docker.com/) website to create account/Sign in 
2. Click **Create a Repository** on the Docker Hub welcome page.
3. I named it **sca_cloudschool**

# Back to the terminal to Build images 
1. Run 
    ```
    docker build -t  mizkas/sca_cloudschool:v1 .
    ```

Above will build the image given it a tag of v1


The push refers to repository [docker.io/mizkas/sca_cloudschool]

https://hub.docker.com/repository/docker/mizkas/sca_cloudschool