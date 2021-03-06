Laravel Broadcast Demo
---

# WARNING
**THIS PROJECT DOESN'T BOTHER REGARDING SECURITY. IT'S UPTO YOU HOW YOU WANT TO IMPLEMENT SECURITY**

### Requirements
This project comes with Docker. If using docker, to minimize the docker build time, the project requires to `php`, `composer`, `node`, `npm` or `yarn` in your local machine.

### Installation
- Clone this repository.
- Copy your `docker-compose.yml.example` to `docker-compose.yml`. Example: `cp docker-compose.yml.example docker-compose.yml`.
- Update your `docker-compose.yml` with appropriate values.
- Copy `.env.example` to `.env`. Example: `cp .env.example .env`.
- Generate key using: `php artisan key:generate`.
- Update your `.env` variable values.
- `composer install` to install dependencies.
- `yarn install` or `npm install` to install JS dependencies.
- `docker-compose up -d --build` to start the project containers.
- Run `php artisan migrate:refresh --seed` from container or outside the container.
- Run `http://IP_ADDRESS:NGINX_PORT_NUMBER` to run the project. Example: `http://127.0.0.1:PORT_NUMBER`.
- Email: `admin@example.com` Password: `123456`
- If you update the code further, then make sure to run `yarn run dev` if changed in `resource/js/app.js` `resource/js/bootstrap.js`.

**N.B: If you're working locally, it's mandatory to download the requirements via composer & npm or yarn.**

