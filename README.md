# ABitly

ABitly is a simple clone of Bitly.

## Requirements

- [Docker](https://docs.docker.com/install/) >= *v*19.03.2
- [Docker Compose](https://docs.docker.com/compose/install/) >= *v*1.23.2

## Services

### ABitly Services [![CircleCI](https://circleci.com/gh/AlexisNava/ABitly-Services.svg?style=svg)](https://circleci.com/gh/AlexisNava/ABitly-Services)

- Description: RESTful Services for the ABitly project.
- Repository: https://github.com/AlexisNava/ABitly-Services

### ABitly App [![CircleCI](https://circleci.com/gh/AlexisNava/ABitly-App/tree/master.svg?style=svg)](https://circleci.com/gh/AlexisNava/ABitly-App/tree/master)

- Description: SPA for the ABitly project.
- Repository: https://github.com/AlexisNava/ABitly-App

## Usage

### Run all the services

```sh

docker-compose run

```

### Run all the services in detach mode

```sh

docker-compose -d

```

### Stop all the services

```sh

docker-compose stop

```

### Remove the data in all the volumes

```sh

docker-compose down --volumes

```

## License

**ABitly** is licensed under [Apache License, Version 2.0](https://github.com/AlexisNava/ABitly/blob/master/LICENSE).
