# AI Codex Symfony API

This repository contains a Symfony 7.3 project initialized with the API Platform pack. It provides a starting point for building a REST and GraphQL API using Symfony.

## Getting Started

Install PHP dependencies:

```bash
composer install
```

Run the development server (requires the Symfony CLI):

```bash
symfony server:start
```

Then browse the API at `http://localhost:8000/api`.

## Docker

Build and start the application with Docker:

```bash
docker-compose up --build
```

The API will be available at `http://localhost:8000/api`. To run additional commands inside the container, use `docker-compose exec app <command>`.
