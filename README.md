# basic-symfony-docker-template

## Setup
1. update git credentials in php/Dockerfile
1. docker compose up -d --build
1. docker compose exec php bash
1. symfony check:requirements
1. symfony new my_project_directory --version="7.0.*"
1. verify site is operational at Http://localhost

1. composer require --dev maker ormfixtures fakerphp/faker
1. composer require twig doctrine
1. cp .env .env.local
1. DATABASE_URL="mysql://root:secret@database:3306/symfony_docker?serverVersion=8.0"
