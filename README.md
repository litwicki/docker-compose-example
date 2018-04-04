# Docker Compose Example

Setting up a simple application with docker-compose using environment variables.

## Requirements

You'll of course need to make sure you have Docker and Compose installed at the very least:

* [Docker](https://docs.docker.com/install/)
* [Compose](https://docs.docker.com/compose/install/)

### Getting Started

All you'll need to do now is copy your `.env.dist` file to `.env` so your environment can load, and then run docker-compose to build the environment locally (or elsewhere).

    cp .env.dist .env

Now you'll want to change the values in `.env` appropriately..

    docker-compose up -d


