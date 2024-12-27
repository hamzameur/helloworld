# Dummy Hello World REST API

## Quick start

1. Build the image

```sh
docker build . -t hello-world-api
```

2. Run the container

```sh
docker run -p 8080:8080 hello-world-api
```

3. Visit http://localhost:8080/api/hello