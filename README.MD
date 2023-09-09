Ascii-Art-Web

* Description: Asci-Art-Web-dockerize is a program that will builds images automatically by reading the instructions from a Dockerfile -- a text file that contains all commands, in order, needed to build a given image. 

* Usage: how to run:
1. To create the image write "docker image build -f Dockerfile -t ascii-docker ." in the Terminal
2. To create the container write "docker container run -p 8080:8080 -d --name webserver ascii-docker" in the Terminal

** OR you can run the "bulid.sh" script to build the image and container.

* Implementation details: algorithm: we create in this project Dockerfile, one image, and one container.

* Authors: Ruqaya Helal & Maryam Abbas