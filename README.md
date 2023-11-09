## Instructions for Dockerfile:

docker build -t docker-express .

docker run -d --name=ExpressWithDocker -p 7777:3000  docker-express