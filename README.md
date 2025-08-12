/home/makewalletfirst/explorer/docker-compose.yml

cd ~/explorer
docker compose up -d
docker logs -f btc-rpc-explorer

http://<서버IP>:3002
