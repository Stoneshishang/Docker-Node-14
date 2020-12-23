# Docker-Node-v14

This file is an exercise of deploying Node App on Docker.

After create Dockerfile

1. --> docker build .
2. Find the docker image name, copy it. Do --> docker run -p 3000:3000 <imageID>
3. Now I should be able to go to localhost:3000 on my local machine without actually install Node or doing npm install.
4. To stop the container, open a new terminal. Do --> docker ps --> to list all the container, then grab the name of the container
5. --> docker stop <container_name>
