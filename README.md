
SECTION 1
Hello from Docker!
This message shows that your installation appears to be working correctly.

To generate this message, Docker took the following steps:
 1. The Docker client contacted the Docker daemon.
 2. The Docker daemon pulled the "hello-world" image from the Docker Hub.
    (amd64)
 3. The Docker daemon created a new container from that image which runs the
    executable that produces the output you are currently reading.
 4. The Docker daemon streamed that output to the Docker client, which sent it
    to your terminal.

To try something more ambitious, you can run an Ubuntu container with:
 $ docker run -it ubuntu bash

Share images, automate workflows, and more with a free Docker ID:
 https://hub.docker.com/

For more examples and ideas, visit:
 https://docs.docker.com/get-started/

REPOSITORY          TAG                 IMAGE ID            CREATED             SIZE
hello-world         latest              fce289e99eb9        14 months ago       1.84kB
CONTAINER ID        IMAGE               COMMAND             CREATED              STATUS                          PORTS               NAMES
d45cd1d3c51d        hello-world         "/hello"            About a minute ago   Exited (0) About a minute ago                       competent_brattain
64548aad840f        hello-world         "/hello"            4 minutes ago        Exited (0) 4 minutes ago                            dreamy_archimedes
4933987dee38        hello-world         "/hello"            4 minutes ago        Exited (0) 4 minutes ago                            elegant_austin

SECTION 2
Sending build context to Docker daemon  45.57kB
Step 1/7 : FROM node:current-slim
 ---> 26932a190e66
Step 2/7 : WORKDIR /usr/src/app
 ---> Using cache
 ---> e6ab8d3711d4
Step 3/7 : COPY package.json .
 ---> Using cache
 ---> 4fba774d0f68
Step 4/7 : RUN npm install
 ---> Using cache
 ---> cbe109c0b73a
Step 5/7 : EXPOSE 8080
 ---> Using cache
 ---> 47953c5955ef
Step 6/7 : CMD [ "npm", "start" ]
 ---> Using cache
 ---> f90abcc49ba6
Step 7/7 : COPY . .
 ---> Using cache
 ---> d8bb73a28dea
Successfully built d8bb73a28dea
Successfully tagged bulletinboard:1.0
SCREENSHOT: Docker Bulletin Board (localhost:8000) - https://github.com/am2892/Docker/blob/master/Screen%20Shot%202020-03-09%20at%204.24.39%20PM.png

SECTION 3
SCREENSHOT: Docker - push image - https://github.com/am2892/Docker/blob/master/Screen%20Shot%202020-03-09%20at%205.50.19%20PM.png
