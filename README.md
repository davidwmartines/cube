#  Cube

Project from the [Build an Orchestrator in Go from Scratch](https://learning.oreilly.com/library/view/build-an-orchestrator/9781617299759) book.


## Use VSCode devcontainer
 - use the "Go" desktop-linux image
 - enable docker-in-docker feature


## Running directly in Linux
If docker desktop is running but you still get "Cannot connect to the Docker daemon at unix:///var/run/docker.sock. Is the docker daemon running?"

```
docker context ls

```

get sock uri of DOCKER ENDPOINT of desktop-linux  ...

`export DOCKER_HOST=unix:///home/david/.docker/desktop/docker.sock`


## Stuck? 
 See code here: https://github.com/buildorchestratoringo/code
