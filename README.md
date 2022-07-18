# Symfony, MSQL, Twig, Node with Docker (For Beginners)
<b>FOR DEVELOPMENT ONLY</b><br><br>
:arrow_right: A simple Docker Symfony setup for beginners who want to play with the Symfony PHP framework. :sunglasses:

<h3>This repository provides you:</h3>
- php:8.1-cli + PHP extensions
- Composer
- Symfony CLI
- MYSQL
- NodeJS
- Non-root user

<h3>Requirements</h3>
- Linux OS
- Docker
- Docker-compose

<h3>Installation</h3>
1. Clone the repository
```
git clone https://github.com/mrnavrc/Docker_Symfony_MSQL_Twig_For_Beginners.git
```
2. Run the docker and docker-compose
```
docker compose build
docker compose up
```
3. Run PHP console
```
sudo docker exec -it  php_c bash
```
4. Check Symfony requirements
```
symfony check:req
```
5. Create Symfony web app
```
symfony new project-name --webapp
```
6. Great, your Symfony app is now available on: http://127.0.0.1:8000
