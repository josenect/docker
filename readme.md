comando docker

//listas imagenes 
docker images

//listar contenedores up
docker ps 

//listar todos los contenedores 
docker ps -a

//correr imagen Dockerfile
sudo docker build .

//correr imagen DockerFile con nombre y version 
sudo docker build -t mi_app_docker:latest .

//correr contedor apartir de la imagen
sudo docker run -it --rm -d -p 8080:80 --name name_app name_imagen

//correr contenedor 
sudo docker start 136841809fc1

//detener contenedor 
sudo docker stop 136841809fc1

//eliminar imagen
sudo docker rmi -f 3b9272c1c1ad

//eliminar contenedor 
sudo docker rm -f 3b9272c1c1ad