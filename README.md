# cadyswarm
caddyswarm

docker network create -d overlay  proxy-network   //create overlay network
docker stack deploy -c docker-compose.yml caddygen // deploy
docker stack remove caddygen  //remove

docker service scale caddygen_whoami=20  //scale