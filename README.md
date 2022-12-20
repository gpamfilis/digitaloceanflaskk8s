Build image.
docker build --tag digitaloceanflaskk8s .
Run image.
docker run -p 8080:8080 -p digitaloceanflaskk8s
Visit
visit: http://localhost:8080/