docker-graphity-client
======================

# Building

```
$ docker build -t `whoami`/graphity-client .
```

# Running

```
$ docker run -itd -p 8080:8080 `whoami`/graphity-client
$ docker exec -it <container-id> /bin/bash
```
