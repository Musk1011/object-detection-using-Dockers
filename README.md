# object-detection-using-Dockers
System Requirements:
Ubuntu OS
Dockers
TensorFlow

First install Dockers using the command:
sudo apt get Docker.io
You can also check the version using:
sudo docker version--
 
 After the installation follow the steps in dockerfile to make directory for TensorFlow and move forward with the hosting.
 After running the dockerfile, build the images using the command:
 docker build -t tensorflow .
 To run container write the command:
 docker run --name tensorflow -p 8888:8888 -d tensorflow
 And then open http://localhost:8888/:
 
 Also if using Windows, you can install Dockers directly from the official website and then pull images from DockersHub followed by the contanerization process shown   below:
 Pulling Dockers images: docker pull images tag
 We can also check Docker images using the command: Docker images
 Containerization process: docker container create -i -t --name mycontainer 
docker container start --attach -i mycontainer
 We can also check active containers using the command: Docker ps
