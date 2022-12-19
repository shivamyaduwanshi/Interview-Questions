
# Docker Interview Questions
### 1. What is Docker?
       Docker is a platform for developing, shipping, and running applications
       Docker is a platform that packages an application and all it's 
       dependencies together in the form of containers

### 2. What problems does Docker solve?
       Docker solves the dependency issues of an application
       
### 4. What is Docker File?
       Text document which contains all the commands that a user can call
       on the command line to assemble an image

### 5. Docker Image
       Template to create a docker container

### 6. Docket Container
       Running instance of the docket image. Containers hold
       entire package to run the application.

       DockerFile -> (build) -> Docker Image -> (run) -> Docker Container 

### 7. Docker Important Commands
       // Check the version
          docker -v or docker --version

       // Pull image
          docker pull <image-name>

       // Pull image with version or tag
         docker pull <image-name>:<version>
       
       // See docker images
          docker images

       // Search image
          docker search <image-name>

       // Run image
          docker run <image-name>

       // To see running images
          docker ps
       
       // To see all running images
          docker ps -a

       // Image run with environment variable
          docker run --env <VARIABLE_NAME>=<VARIABLE_VALUE> or 
          docker run -e <VARIABLE_NAME>=<VARIABLE_VALUE>
          docker run -e <VARIABLE_NAME1>=<VARIABLE_VALUE1> -e <VARIABLE_NAME2>=<VARIABLE_VALUE2>

       // Image run with image
          docker run --name <containername> <docker-imaeg>

       // Run image in interactive mode
          docker run -it <docker-image>
       
       // Inside the container for run command
          docker exec -it <container-id> <command>

       
