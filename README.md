If docker desktop is running but you still get "Cannot connect to the Docker daemon at unix:///var/run/docker.sock. Is the docker daemon running?"

```
docker context ls

```

get sock uri of DOCKER ENDPOINT of desktop-linux  ...

`export DOCKER_HOST=unix:///home/david/.docker/desktop/docker.sock`