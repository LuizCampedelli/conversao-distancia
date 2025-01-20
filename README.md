# Desafio DevOps & Cloud - Fabricio Verones - Modulo 01 - Docker

## Usefull commands

```bash

docker container run hello-world  >> pull Hello-world image from docker hub

docker container ls >> list containers

docker container rm -f $(docker container ls -qa) >> delete containers based in the list using a command variable

docker build -t conversao-distancia -f Dockerfile .

docker container run -d -p 8181:5000 conversao-distancia

docker login >> autenticate to hub.docker.com

docker push your_docker_hub_namespace/conversao-distancia:v1 >> push your docker image to dockr hub using the correct tag

docker tag your_docker_hub_namespace/conversao-distancia:v1 vapeprosper/conversao-distancia:latest >> tag your image as latest

docker push vapeprosper/conversao-distancia:latest >> push the latest tag to docker hub
```

## Docker Hub Iamges


![Screenshot 2025-01-20 124009](https://github.com/user-attachments/assets/b73fc818-3d79-4348-8e1f-9a594e677017)
