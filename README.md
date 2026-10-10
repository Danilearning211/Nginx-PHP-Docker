# Nginx-PHP-Docker
Simple project to run PHP with Nginx using Docker.

* Nginx listens on port 80
* PHP requests are handled by PHP-FPM
* Docker is used to run the services

## Run

```bash
docker compose up -d --build
```
## Routing
If the URL ends with `index.php`, our custome PHP  page is shown.
If the URL ends with `index.html`, our Nginx  page is shown.

## Features

- [x] Nginx container
- [x] PHP-FPM container
- [x] Nginx PHP configuration
- [x] Docker networking
- [ ] Test PHP page
