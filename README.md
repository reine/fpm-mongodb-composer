# fpm-mongodb-composer
Docker image of PHP-FPM with MySQL & MongoDB extensions and Composer

**Suggested Use:** For development only

## Environment Variables

You can override the default working directory of `/var/www/html` to suit your project's app directory.

Sample usage:

```
  php-fpm:
    image: sreine/fpm-mongodb-composer:latest
      environment:
        - APP_WORKDIR="/home/user/app"
```

---
This is a work in progress. Do not use in your projects.
