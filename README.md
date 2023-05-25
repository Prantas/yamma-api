# YAMMA API
The API for the **Y**et **A**nother **M**oney **M**anagement **A**pp
stack.

More about YAMMA at [yamma.app][1]

The Docker part of the project is base on [dunglas][2]'s 
[symfony-docker][3]

[1]:https://yamma.app
[2]:https://github.com/dunglas
[3]:https://github.com/dunglas/symfony-docker

## Deploy

Create a .env file, or use `sample.env`

Build the images:
`docker compose build --pull --no-cache`

Run compose:
`docker compose up -d`