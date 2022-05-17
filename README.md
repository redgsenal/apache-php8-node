# apacher php 8 node npm

docker compose -f docker-compose.yml up --build -d

docker exec -it apache-web //bin//bash

docker run -it -v /src:/home/projects/src apache-web //bin//bash

docker create -itv x:/projects/apache-php8-node:/home/projects/src apache-php8-node /bin/bash