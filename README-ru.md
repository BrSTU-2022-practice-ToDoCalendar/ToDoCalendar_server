# README

**Языки документации**:

- [English](README.md)
- [Русский](README-ru.md)

**Меню**:

- [Задание](#задание)
- [Как запустить приложение](#как-запустить-приложение)
- [Стэк приложений](#стэк-приложений)
- [Структура проекта](#структура-проекта)

## Задание

Запустить на сервере frontend и backend через docker-compose,
выгружая образы на DockerHub.

## Как запустить приложение

```bash
docker-compose up
```

Если образ на Docker Hub обновили, то:

```bash
docker pull pavelinnokentevichgalanin/todocalendar_frontend:latest
docker-compose up
```

## Стэк приложений

- **[Docker, docker-compose](https://www.docker.com/)**

## Структура проекта

```bash
sudo apt install tree
tree --charset ascii -d
```

```
.

0 directories
```
