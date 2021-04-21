# Codeigniter
Base Codeigniter structure with Docker.

## Stack
Docker with PHP 7.4, Apache 2.4 and Mysql 5.7.

## Getting started
1. Install [Docker](https://docs.docker.com/get-docker/);
1. Update or create .env file (use .env.example);
1. Change "000-default.conf" in `/docker/apache`;
1. Run `docker-compose build app`;
1. Run `docker-compose up`;
1. Run `composer install` inside `/src` folder;

## License

[MIT license](https://opensource.org/licenses/MIT).
