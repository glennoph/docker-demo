# docker-demo

docker file for node hello world app

To build the application, clone the repo, chdir to the repo, and run:
  docker build
  
To start the container for port 3000:
  docker run -p 3000 -it <image-id>
  
To start the application that will listen on port 80:
  docker run -p 80:3000 -it <image-id>
  
