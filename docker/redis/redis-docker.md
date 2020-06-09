sudo docker network create --subnet=172.19.0.0/24 redis-net

sudo docker exec -it redis-master redis-cli -p 6379

sudo docker exec -it redis-s2 redis-cli -p 6381

info replication

cd /usr/local/bin

./redis-cli -h 172.19.0.5 -p 26379

info
