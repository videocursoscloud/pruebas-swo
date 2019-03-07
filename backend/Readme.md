docker build -t swingoffice-front:latest .

Ejecutar contenedor:

docker run -d -p 8080:80 --name swingoffice-front swingoffice-front:latest

curl localhost:8080


#parar
docker stop swingoffice-front

# eliminar contenedor

docker rm swingoffice-front

