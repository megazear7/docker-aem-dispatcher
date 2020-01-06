# Containerized AEM Dispatcher

### Build

```
docker build -t dispatcher .
```

### RUN

You will need to have an AEM publish instance running on localhost:4503

```
docker run -it -p 8080:80 dispatcher
```

Then open a AEM page from localhost:8080
