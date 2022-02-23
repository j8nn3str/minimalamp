# minimalamp

A bare minimum LAMP + phpmyadmin + traefik stack made with Docker containers. Intended for development purposes. Considerations for production purposes WIP.

## Composition

| **Docker Image** | **Version** | **Access**
| :----------: | :-----: | :-----: |
| Apache | 2.4.43-alpine | ```http://{your stack name}.localhost``` |
| PHP | 7.4.8-fpm-alpine3.12 | --|
| MySQL | 5.6.48 | -- |
| phpmyadmin | -- | ```http://phpmyadmin.{your stack name}.localhost``` |
| traefik | 2.2.8 | ```http://traefik.{your stack name}.localhost``` |

## Usage

### Generate .env files

Make a copy of `*.env.example` files and rename to `*.env` files. Populate defined variables in the files as needed.

### Use these commands

```
docker-compose up -d --build
```

## Use cases
#### WordPress
Works great for a local installation of WordPress!

## Drupal
Maybe. Might need to install several other php extensions.
