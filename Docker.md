Docker Commands and its usage: 
===========================
[![N|Solid](https://encrypted-tbn3.gstatic.com/images?q=tbn:ANd9GcT7Z3x7hMFhUxRPA8cp8Qi351zbTlmrmCC833pc_JVplL2OeMx2)](Docker)


- docker images --> List of stored images
- docker build .--> To build from DockerFile
- docker search <app_name> --> Search container from Docker hub
- docker rmi <image_id> --> Delete the image from local repository
- docker rmi -f `docker images -q` -> Delete all the local repository 
- docker ps --> To see all the ongoing docker process
- docker stop $(docker ps -a -q) -- > Stop the docker container based on their process id
- docker run -t -i <container_name> -- > To start a container
