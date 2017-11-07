# docker_skeleton

### Docker skeleton
Contains:
- Mysql 5.7
- PHP 7.1 Fpm
- Nginx + conf

### How to run?
1. Paste application to **app** directory (or edit `docker-compose.yml` and change PHP application volume)
2. Set MySQL ENV Values in `docker-compose.yml`
3. Run `docker-compose up` in command line
4. Application should be available on `localhost`

### Mysql DB
Prepare correct DB connection in **parameters.yml** file: `app/config/parameters.yml`

Content:
```yml
parameters:
    database_host: mysql
    database_port: null
    database_name: app
    database_user: app
    database_password: app
```

