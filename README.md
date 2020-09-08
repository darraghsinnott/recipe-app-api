# recipe-app-api

Foreword:
This repository contains the source code from the udemy course :-
Build a Backend REST API with Python & Django - Advanced 
by Mark Winterbottom and Brooke Rutherford



Prerequisites:
Intel machine running ubuntu 18.04 or higher with docker engine and 
docker-compose installed

Links to docker installation instructions:
docker engine: https://docs.docker.com/engine/install/ubuntu/ 
docker-compose: https://docs.docker.com/compose/install/


Installation & initial configuration:
git clone https://github.com/darraghsinnott/recipe-app-api.git

cd recipe_app_api

docker-compose run --rm app sh -c "python manage.py createsuperuser"

{enter an email and password of your chosing (e.g. 'admin@django.com' 'test1234')"

starting/stopping the application

startup:

cd recipe_app_api

docker-compose up -d

shutdown:

cd recipe_app_api

docker-compose down




