# class-docker-105

Step 1: Build docker file.
# docker build -t my-apache2 .

Step 2: Docker run from docker-compose file.
# docker-compose up -d

Step 3: Docker rebuild for changes.
# docker-compose up --build -d

Step 4: Check running docker container.
# docker ps

Step 5: Container access from host machine.
# docker exec -it container_name /bin/bash
