How to use this project:

1. Clone this repo.
2. Remove the .git directory (you will initialize your own repo for your project).
3. cd into docker-compose
4. copy .env-example to .env and change the values as desired ( 
COMPOSE_PROJECT_NAME will be used in container, network and volume? names.
5. Run sudo docker-compose build
6. Run sudo docker-compose up -d
7. Run sudo docker-compose exec php bash
8. Run composer create-project laravel/laravel laravel_temp
9. Run mv laravel_temp/*
10. Run mv laravel_temp/.[!.]* .
11. Run rm -r laravel_temp
12. Open Laravel's .env file and update the db details (use same as in docker-compose .env, except make DB_HOST=mysql).

Build:
```
sudo docker-compose build
```

Start:
```
sudo docker-compose up -d
```

See logs:
```
sudo docker-compose logs -f
```

Stop:
```
sudo docker-compose down
```
