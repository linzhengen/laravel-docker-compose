# create docker images
```
$ docker-compose up
```

# install laravel
```
$ docker-compose exec web bash
$ composer global require "laravel/installer"
$ composer create-project --prefer-dist laravel/laravel ./. 
$ php composer install
$ exit
```
# see url
http://localhost


