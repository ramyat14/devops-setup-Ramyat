1. Dockerfile create.
2. index.html file create.
3. Build the image: docker build -t xops-docker1-image .
4. docker images to look into created images
$ docker images
REPOSITORY           TAG       IMAGE ID       CREATED             SIZE
xops-docker1-image   latest    1c4bd8f906eb   15 minutes ago      473MB
5. Create Container: Run the docker by giving the port, container name and the image to be used.
6. docker ps
$ docker ps
CONTAINER ID   IMAGE                COMMAND                  CREATED          STATUS          PORTS                  NAMES
a007c06473e4   xops-docker1-image   "/usr/sbin/httpd -D …"   11 minutes ago   Up 11 minutes   0.0.0.0:8080->80/tcp   WebAppRT-container2
