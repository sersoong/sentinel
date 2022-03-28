# sentinelService

#### Introduction
alibaba sentinel server

#### Modify your sentinel username and password through `sentinel/Dockerfile`:

```
"-Dsentinel.dashboard.auth.username=sentinel","-Dsentinel.dashboard.auth.password=123456",
```

#### How to use?

1. Install docker and docker-compose like below:
```bash
# apt install docker
# apt install docker-compose
```
2. Run build command:
```bash
# docker-compose up -d
```

Enjoy!