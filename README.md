# objective
This is practice repository for django making weather apps to learn API

# environment

- Docker	
- Docker image: python3
- Dockerfile / docker-compose.yml / requirements.txt

# dir

/root/app

# build a container

```
docker compose up -d --build
```

# check into the container

```
docker compose exec [container name] bash
```

# Tips

if you accsee to django server in docker-container from some browser on your pc,
exec code bellow for run server

```
python manage.py runsever 0.0.0.0:[port number]
```

# others
This repository is simplest django project.

# django setup

create project

```
django-admin startproject [project-name]
```


create superuser

```
python manage.py createsuperuser
```



