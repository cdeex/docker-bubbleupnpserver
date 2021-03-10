# docker-bubbleupnpserver


## Usage

- Build image

```
$ docker build -t <name:tag> .
```
Note: more about name:tag can find in [docker tag Docs](https://docs.docker.com/engine/reference/commandline/tag/)

- Run 

```
$ docker run --rm -it -d --name <container_name> --publish 58050:58050 --publish 58051:58051 --publish 58052:58052 <docker_image>
```

- Access `http://localhost:58050/`

