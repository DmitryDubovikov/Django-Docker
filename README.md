# Django-Docker
Django in Docker basic example:  basic site mysite and app siteapp.

## Commands to run in terminal:
docker build --tag python-django .
docker run --publish 8000:8000 python-django
