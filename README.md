# codeedu_FC20_Docker_DesafioGo

# link da image no Docker Hub
https://hub.docker.com/r/edsonhi1041/startcode

# Build, Run and Push
docker build -t edsonhi1041/startcode:prod . -f Dockerfile.prod
docker run -d -it edsonhi1041/startcode:prod
docker push edsonhi1041/startcode:prod


