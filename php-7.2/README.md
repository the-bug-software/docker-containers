# PHP 7.2 Docker Image

What's included:
- A PHP 7.2 install compatible with most Laravel installations (with MySQL, intl, bcmath, imagick)
- Latest composer

# Using this container

You can refer to this container as `thebugsoftware/php72`.

```
$ docker run -it --rm thebugsoftware/php72 bash
php -v
PHP 7.2.x
```

# Build & Push

```
$ docker build -t thebugsoftware/php72 .
$ docker login && docker push thebugsoftware/php72
```
