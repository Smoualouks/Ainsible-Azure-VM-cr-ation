# Dépôt Gitlab d'une application Python avec Flask.

Le fichier de pipeline Jenkins (Jenkinsfile) orchestrera une pipeline dans le serveur Jenkins :
    - construction d'une image personalisée de python:3.8-slim-buster (Dockerfile) avec éxecution de l'application (app.py) et déploiement sur le DockerHub
    - téléchargement d'une image mariadb:10.5 depuis le DockerHub (docker-compose.yml)
    - copie du fichier docker-compose.yml sur une autre machine virtuelle et éxecution du fichier
