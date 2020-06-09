sudo docker network create --subnet=172.18.0.0/24 zoo-net

sudo docker inspect zoo-net

sudo docker-compose up

sudo docker exec -it zookeeper /bin/sh

sudo docker stop $(sudo docker ps -a -q)

sudo docker rm $(sudo docker ps -a -q)

echo stat | nc 127.0.0.1 2181
