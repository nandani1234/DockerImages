This repository contains Docker images for different applications.

Docker-Java:


docker build -t <image_name> .


docker run -dt <image_name> --name java_new


docker exec -it java_new /bin/bash
