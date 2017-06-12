# Wordpress on Docker

## How to run this image

1. Clone this Repository or Download the .yml file

2. Since we are using `docker-compose`, the only thing you need to do to mount the image is:
```
docker-compose up -d
```

This will do the following:
- Mount the Wordpress Image.
- Mount the Wordpress Database (mysql).
- Create a Volume of the `wordpress/wphtml directory`.

3. Your dockerized Wordpress is ready to go. By reaching `localhost:3000`, you will be able to install Wordpress and afterwards do whatever you want with it.
