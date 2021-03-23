# Docker Basic Lemp Stack

Ready to use LEMP docker Stack

First Use 

Create .env file using [example](https://github.com/geoffreygirou/Docker-Basic-LEMP-Stack/blob/master/.env.example)

```shell 
docker-compose up --build -d
```

Visit : [localhost](http://127.0.0.1:80)

Or : set up hosts config according to nginx server name.

Name          | Version    | Port
--------------|------------|------
MySQL`*`      | 5.7        | 3306
nginx         | 1.19.7     | 80
PHP           | 8.0.3      | 9000

> `*`: It is actually MariaDB 10.5.9.