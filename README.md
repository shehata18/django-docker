The most important files [ Dokerfile, .dockerignore, docker-compose.yml ]
# Commends ##
- docker build .
- run docker container => docker-compose up  = docker-compose up -d
- stop docker container => docker-compose down
- docker-compose exec web [ here write common django commends ]
  like:  docker-compose exec web python manage.py createsuperuser /   docker-compose exec web python manage.py migrate
  if you want to install new package just write it in ( requirements.txt )
  then write this command in terminal
  - docker-compose up -d --build
