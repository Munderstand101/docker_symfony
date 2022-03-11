
# Docker & Symfony

Run the docker-compose

```bash
  docker-compose build
  docker-compose up -d
```

Log into the PHP container

```bash
  docker exec -it php8-sf6 bash
```

Create an account (identical to your local session)

```bash
  adduser username
  chown username:username -R .
```