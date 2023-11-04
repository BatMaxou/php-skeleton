# PHP Skeleton

A base for simple php projects.

Work with:
    - Composer
    - Docker
    - Sass

## Composer

Add a dependency with
```bash
composer require <package_name>
```

Install the dependencies of the project with
```bash
composer install
```

## Docker

This skeleton use the boing devops.

To launch the project with Docker, copy the file `docker-compose.yml.dist` to `docker-compose.override.yaml` and change it to your needs.

Then launch the project with
```bash
docker-compose up -d
```

## Sass

If you are using VsCode, install the extension `Live Sass Compiler` and launch it with `Watch Sass`. You can change the settings of the extension in the file `.vscode/settings.json`.

By default your Sass files are compiled in `public/`.
