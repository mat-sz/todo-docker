# todo-docker

A docker-compose setup for my project management tool.

## Installation

Clone the repo and run the following commands:

```
git submodule update --recursive --init
docker-compose up
```

Make sure docker and docker-compose are installed and your user is in the docker group.

## Using custom ports

Please copy the attached `docker-compose.override.example.yml` file to `docker-compose.override.yml` and modify the values as needed.