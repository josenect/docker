
<h1 align="center">comandos docker</h1>

<br>

## :dart: About ##

Describe your project


```bash
# Listas imagenes 
$ docker images

# Listar contenedores up
$ docker ps 

# Listar todos los contenedores 
$ docker ps -a

# Generar imagen Dockerfile
$ sudo docker build .

# Generar imagen DockerFile con nombre y version 
$ sudo docker build -t mi_app_docker:latest .

# Correr contedor apartir de la imagen
$ sudo docker run -it --rm -d -p 8080:80 --name name_app name_imagen

# Correr contenedor 
$ sudo docker start 136841809fc1

# Detener contenedor 
$ sudo docker stop 136841809fc1

# Eliminar imagen
$ sudo docker rmi -f 3b9272c1c1ad

# Eliminar contenedor 
$ sudo docker rm -f 3b9272c1c1ad



```
