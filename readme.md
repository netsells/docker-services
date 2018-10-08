## Netsells Docker
A set of Docker services to aid local development.

## Available Services
* Legacy MySQL: `docker-compose up -d mysql`
* Mailcatcher: `docker-compose up -d mailcatcher`
* [Adminer](https://www.adminer.org/): `docker-compose up -d adminer`
* [Elasticsearch](https://www.elastic.co/products/elasticsearch): `docker-compose up -d elasticsearch`

## Running instructions:
Clone this repository and `cd` into the directory then run:

```
docker-compose up -d service1 service2 ...
```

## Service: Legacy MySQL Docker
This is useful for running a separate local instance of MySQL on port 3307, with settings that allow for legacy databases which have 
zero datetimes.

Note that the password for the MySQL root user is `local`

## Service: Elasticsearch
Useful for local development with [Hatchly Search](https://github.com/netsells/hatchly-search) and Elasticsearch in general