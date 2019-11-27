# Storytellers with microservices
Storytellers project with a Microservice architecture

The project is composed by the following services:

- auth
- users
- reactions
- story
- statistics/search

![Architecture](files/architecture.png)

# Clone the repo

Clone:

```
git clone https://github.com/giobart/storytellers-microservices
git submodule update --init --recursive
```

Pull changes:

```
git submodule update --init --recursive
```
# Deploy the services

```
docker-compose up
```

Frontend is accessible at `localhost:8080`. Raw API Gateway accessible at `localhost:8081`.

# Status

Service | Build | Coverage |
--- | --- | --- |
Auth | [![Build Status](https://travis-ci.org/giobart/storytellers-auth-service.svg?branch=master&service=github)](https://travis-ci.org/giobart/storytellers-auth-service) | [![Coverage Status](https://coveralls.io/repos/github/giobart/storytellers-auth-service/badge.svg?branch=master&service=github)](https://coveralls.io/github/giobart/storytellers-auth-service?branch=master)
Reaction | [![Build Status](https://travis-ci.org/laurab1/reactions-microservice.svg?branch=master)](https://travis-ci.org/laurab1/reactions-microservice?branch=master) | [![Coverage Status](https://coveralls.io/repos/github/laurab1/Storytellers-Reactions/badge.svg?branch=master)](https://coveralls.io/github/laurab1/Storytellers-Reactions?branch=master)
Statistics | [![Build Status](https://travis-ci.org/deRemo/stats-microservice.svg?branch=master)](https://travis-ci.org/deRemo/stats-microservice) | [![Coverage Status](https://coveralls.io/repos/github/deRemo/stats-microservice/badge.svg?branch=master)](https://coveralls.io/github/deRemo/stats-microservice?branch=master)
Stories | [![Build Status](https://travis-ci.com/alessandrodgr/stories-microservice.svg?branch=master)](https://travis-ci.com/alessandrodgr/stories-microservice) | [![Coverage Status](https://coveralls.io/repos/github/alessandrodgr/stories-microservice/badge.svg?branch=master)](https://coveralls.io/github/alessandrodgr/stories-microservice?branch=master)
Users | [![Build Status](https://travis-ci.com/cardiamc/user-microservice.svg?branch=master)](https://travis-ci.com/cardiamc/user-microservice) | [![Coverage Status](https://coveralls.io/repos/github/cardiamc/user-microservice/badge.svg?branch=master)](https://coveralls.io/github/cardiamc/user-microservice?branch=master)
