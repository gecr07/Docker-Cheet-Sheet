
# Docker 

## Version de docker 

```
docker version 

```

## Listar imagenes que tengamos en el equipo

```
docker image ls 
docker images
```

## Correr una imagen ( basico sin opciones ) 


```
docker run 

```

## Pull 

Para instalar por asi decirlo una imagen en tu equipo

```
docker pull codewithmosh/hello-docker
```

## View all ( also stopped containers )

muestra todos los contenedores asi esten detenidos

```
docker ps -a
```
solo muestra los que estan activos

```
docker ps 

```

## Iniciar un contenedor

Para correr un contenedor que ya este no necesitas run si no start porque porque ya le diste las opciones cuanod lo creaste con run 

```
docker start openvas
```

## Ver puertos abiertos 

Para ver puertos en linux se usa tambien eso


```
lsof -i:443

```

## Ejecutar comandos dentro del docker

Son con la opcion -it ( interactive )

```
docker exec -it openvas bash

```

