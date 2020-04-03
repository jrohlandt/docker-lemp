How to use this project:

1. Clone this repo.
2. cd into docker-compose
3. copy .env-example to .env and change the values as desired.
3. Run sudo docker-compose build
4. Run sudo docker-compose up -d
5. Run sudo docker-compose exec php bash
6. Run composer create-project laravel/laravel laravel_temp
7. Run mv laravel_temp/*
8. Run mv laravel_temp/.[!.]* .
9. Run rm -r laravel_temp

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