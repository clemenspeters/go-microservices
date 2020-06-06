# go-mircorservices

This repo is just following the articles

- [Microservices in Golang part1](https://ewanvalentine.io/microservices-in-golang-part-1/)
- [Microservices in Golang part2](https://ewanvalentine.io/microservices-in-golang-part-2/)

It will pretty much be copy and pasting from [EwanValentine/shippy-service-consignment](https://github.com/EwanValentine/shippy-service-consignment).

## Build and run server containers

```bash
cd shippy-serice-consigment
docker build -t shippy-service-consignment .
docker run -p 50051:50051 shippy-service-consignment
```

## Run cli client

```bash
cd shippy-cli-consignment
go run main.go
```
