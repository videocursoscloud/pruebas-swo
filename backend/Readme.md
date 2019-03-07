docker build -t swo-front:latest .

Ejecutar contenedor:

docker run -d -p 8080:80 --name swo-front swo-front:latest

curl localhost:8080


#parar
docker stop swo-front

# eliminar contenedor

docker rm swo-front

