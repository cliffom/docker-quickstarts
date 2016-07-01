# Docker Quickstart: Express (Node.js)

Get up and running with Node.js and Express on Docker

## Requirements

* docker
* docker-compose

## Usage

Initialize an Express app:
```
docker-compose run --rm web express -f .
```

Install reqired Node.js modules:
```
docker-compose run --rm web npm i
```

Start your Express app:
```
docker-compose up

# You should now be able to access your app at http://localhost:3000
```
