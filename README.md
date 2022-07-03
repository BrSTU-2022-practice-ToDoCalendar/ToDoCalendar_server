# README

**Documentation languages**:

- [English](README.md)
- [Русский](README-ru.md)

**Menu**:

- [Task](#task)
- [How to run app](#how-to-run-app)
- [Application stack](#application-stack)
- [Folder structure](#folder-structure)

## Task

Run frontend and backend on the server via docker-compose,
uploading images to DockerHub.

## How to run app

```bash
docker-compose up
```

If the image on Docker Hub has been updated then:

```bash
docker pull pavelinnokentevichgalanin/todocalendar_frontend:latest
docker-compose up
```

## Application stack

- **[Docker, docker-compose](https://www.docker.com/)**

## Folder structure

```bash
sudo apt install tree
tree --charset ascii -d
```

```
.

0 directories
```
