# Docker Quickstart: Revel (Go)

Get up and running with Go and Revel on Docker

## Requirements

* docker
* docker-compose

## Usage

Initialize a Revel app:
```
docker-compose run --rm web revel new dev/revel
```

Start your Revel app:
```
docker-compose up

# You should now be able to access your app at http://localhost:9000
```
