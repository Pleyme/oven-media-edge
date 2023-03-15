# oven-media-edge

<img width="952" alt="Screenshot 2023-03-15 at 14 34 49" src="https://user-images.githubusercontent.com/18561725/225435704-8a6da5e8-be77-49e1-b779-0010d8143691.png">


## Run with Docker

docker run --rm -p 4000-4005:4000-4005/udp -p 3333:3333 -p 3478:3478 -p 8080:8080 -p 8081:8081 --network=bridge --name live-edge oven-edge
