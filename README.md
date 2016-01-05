### Description
A simple [Joola](http://joolajs.org/) setup to test things out with [Docker Compose](https://www.docker.com/docker-compose).

#### Usage
```bash
# clone the repo
$ git clone https://github.com/avif/joola-example-on-docker-compose
# Run docker compose from within the project folder
$ docker-compose up
```

#### ElasticSearch
If you want to use ElasticSearch instead of MongoDB, just uncomment the elastic search
related comments at ./docker-compose.yml and ./config/default.yml
and comment or remove the MongoDB related lines.

#### What's next
Go to [Joola](http://joolajs.org/) and figure out the proper setup for your needs
