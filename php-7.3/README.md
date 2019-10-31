# PHP 7.3 Docker Image

What's included:
- A PHP 7.3 install compatible with most Laravel installations (with MySQL, intl, bcmath, imagick)
- Latest composer

# Using this container

You can refer to this container as `thebugsoftwaredevelopment/php73`.

```
$ docker run -it --rm thebugsoftwaredevelopment/php73 bash
php -v
PHP 7.3.x
```

# Build & Push

```
$ docker build -t thebugsoftwaredevelopment/php73 .
$ docker login && docker push thebugsoftwaredevelopment/php73
```
