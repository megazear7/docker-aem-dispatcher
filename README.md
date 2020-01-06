# Containerized AEM Dispatcher

### Build

Before building you will need to add the "mod_dispatcher.so" file. This file is hidden from source control.
```
docker build -t dispatcher .
```

### RUN

You will need to have an AEM publish instance running on localhost:4503

```
docker run -it -p 8080:80 dispatcher
```

Then open a AEM page from localhost:8080
