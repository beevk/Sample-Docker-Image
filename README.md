# Sample-Docker-Image

Sample Image for Docker - Testing Container Service in AWS or any other Cloud service

## To Build Image
```
# replace <your-username> with your docker hub username when pushing to docker hub.
docker build -t <your-username>/sample-image .
```
 Now, that you have your image on your local system, you can push it to docker registry (ex: docker hub) of your choice.
 
 Or you can use image **beevk/ecs-ecr** from [Docker Hub](https://hub.docker.com). It's basically the same thing.
