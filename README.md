# dockersolarrs485logger

sudo apt install gnupg2 pass
docker image build -t dockersolarrs485logger:latest  .
docker login -u revenberg
docker image push revenberg/dockersolarrs485logger:latest

docker run revenberg/dockersolarrs485logger


docker exec -it ??? /bin/sh

docker push revenberg/dockersolarrs485logger:latest

# ~/dockersolarrs485logger/build.sh;docker rm -f $(docker ps | grep solarrs485logger | cut -d' ' -f1);cd /var/docker-compose;docker-compose up -d solarrs485logger;docker logs -f $(docker ps | grep solarrs485logger | cut -d' ' -f1)
