# Welcome Page

This repository illustrates a welcome page for Paraffin IoT Platform.

To see it in action locally:

## How Run it
```
docker build -f Dockerfile -t docker-spa .
docker run -p 8888:80 docker-spa
docker rmi -f docker-spa
```

An open [localhost](http://localhost:8888)

## Special Thanks
[Hendrik Wallbaum](mail@hendrikwallbaum.de)