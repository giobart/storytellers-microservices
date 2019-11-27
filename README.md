# Storytellers with microservices
Storytellers project with a Microservice architecture

The project is composed by the following services:

- auth
- users
- reactions
- story
- statistics/search

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
