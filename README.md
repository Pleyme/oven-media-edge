# oven-media-edge


## Run with Docker

docker run --rm -p 4000-4005:4000-4005/udp -p 3333:3333 -p 3478:3478 -p 8080:8080 -p 8081:8081 --network=bridge --name live-edge oven-edge
