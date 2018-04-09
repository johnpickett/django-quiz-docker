NOTE: This is not production grade.

Quick Docker implementation of Tom Walker's django_quiz project (with a few outstanding PRs): https://github.com/tomwalker/django_quiz

Source: https://github.com/johnpickett/django-quiz-docker
Image: https://hub.docker.com/r/johnpickett/django-quiz/

To run, try:

docker run -d --name quiz --restart=unless-stopped johnpickett/django-quiz:latest

I run this behind the awesome nginx-proxy (https://hub.docker.com/r/jwilder/nginx-proxy/).

Default Admin Credentials (/admin):

Username: admin
Password: djangoquiz
