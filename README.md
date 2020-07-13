# minimalamp

A bare minimum LAMP + phpmyadmin stack made with Docker containers. Intended for development purposes. Considerations for production purposes WIP.

## Composition

| **Docker Image** | **Version** |
| :----------: | :-----: |
| Apache | 2.4.43-alpine |
| PHP | 7.4.8-fpm-alpine3.12 |
| MySQL | 5.6.48 |
| phpmyadmin | -- |

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

### Drupal
Maybe. Might need to install several other php extensions.
