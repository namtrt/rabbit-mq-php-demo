# Demo Rabbit MQ

The simply method to set up this project (for development only) is using [Docker](https://docs.docker.com/) and [Docker Compose](https://docs.docker.com/compose/).

## Setup & start
#### 1. Setup Docker
The first, install **Docker** and **Docker Compose**:

- https://docs.docker.com/install/
- https://docs.docker.com/compose/install/

#### 2. Clone source code

Clone this project to your server or local machine.

#### 3. Build & start application
Run following command to build & start your application

```bash
docker-compose up
```

Run in background

```bash
docker-compose up -d
```

#### 4. Install packages

```bash
composer install
```

## How to run
Exec to php node
```bash
docker-compose exec php bash
```
Send message
```bash
php producer.php [Message]
```

Run process
```bash
php consumer.php
```

## Rabbit MQ management
http://localhost:15672/#/