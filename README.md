# RabbitMQ in docker-compose

## Setup
This setup assumes you already have docker-compose and docker (using docker toolbox) installed.

```
docker-compose up
```

## Play
Open [http://127.0.0.1:15672/](http://127.0.0.1:15672/) (or what ever IP you get when you run `docker-machine ip`)

```
open http://$(docker-machine ip default):15672/
```
and use the login

```
username: master
password: 4b2k~2J7
```

## License
MIT License
