Requirements: 

1. Write a Dockerfile in the personal github repo that will print the content of the Welcome.txt file. 
2. Add your username and password for the personal Dockerhub account in devops-poc repository-level secrets.

secrets.DOCKERHUB_Saif_USERNAME
secrets.DOCKERHUB_Saif_Token



Complete the following tasks.
1. Write a workflow 'build-docker-image.yml' which will build the docker image and push it to your Docker Hub account.
2. Create a second workflow that will be started by the build-docker-image.yml workflow and print the Docker image tag.
