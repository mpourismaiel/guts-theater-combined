# Notice

Please run the following commands after cloning this project:

```
git submodule update --init
docker-compose up --build
```

You need docker-compose and docker to setup the project.

After running the docker-compose you can access:

- client: http://localhost:4005
- api: http://localhost:4000
- grafana: http://localhost:3000
- prometheus: http://localhost:9090

You can configure Sentry by passing an env variable to `guts-theater` service in docker-compose: `SENTRY_DSN`, which will enable sentry error reporting.

An [OpenAPI file](https://github.com/mpourismaiel/guts-theater/blob/bc937a17ad7d6ce36527e1434aa5350145ddeae2/docs/openapi.yaml) is provided which can be used with Swagger to test the API.

For more information, please visit [guts-theater](https://github.com/mpourismaiel/guts-theater) and [guts-theater-fe](https://github.com/mpourismaiel/guts-theater-fe) repositories.
