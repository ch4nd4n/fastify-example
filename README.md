# README

To run the server in command line

```sh
node server
```

## Docker

Build

```sh
docker build -t ch4nd4n/fastify-example .
```

To run

```sh
docker run --rm -p 3000:3000 --name fastify-example ch4nd4n/fastify-example
```


To kill

```sh
docker kill fastify-example
```

Create a tagged version

```sh
docker tag ch4nd4n/fastify-example:1.0 ch4nd4n/fastify-example:1.0
```

Push to docker

```sh
docker push ch4nd4n/fastify-example
```

## Reference

- https://docs.docker.com/get-started/

