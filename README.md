# Deploy-Ready django application template

This is a guide on how to setup a deploy ready django application.

- Setup Project
- Setup Apps
- Code style and formatting

## Git and gitignore

- Start an empty repository
- Create .gitignore

## Asdf and venv

Install latest python version
```bash
asdf install python latest
```

Setup local version for project
```bash
asdf local python latest
```

Create a virtual environment
```bash
python -m venv venv
```

## Requirements

Create a directory `requirements` and place `base.txt`, `local.txt`, `production.txt` and `tests.txt` to keep track of project's requirements

## Start django project, docker and database

```bash
django-admin startproject django_project
```

- Create `Dockerfile` and `docker-compose.yml`
