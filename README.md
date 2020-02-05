# Containerized AEM Dispatcher

### Build

```
docker build -t easy-docker-dispatcher .
```

### Run

You will need to have an AEM publish instance running on [localhost:4503](http://localhost:4503).

```
docker run -it -p 8080:80 easy-docker-dispatcher
```

Then open an AEM page at [localhost:8080](http://localhost:8080).
