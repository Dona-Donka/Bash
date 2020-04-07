## First steps with docker:


https://docs.docker.com/ 

- The most important commad: `docker --help`
- Usage: `docker [OPTIONS] COMMAND`

### Container commands: 

`docker --help | grep "container"`
```
A self-sufficient runtime for containers
  container   Manage containers
  attach      Attach local standard input, output, and error streams to a running container
  commit      Create a new image from a container's changes
  cp          Copy files/folders between a container and the local filesystem
  create      Create a new container
  diff        Inspect changes to files or directories on a container's filesystem
  exec        Run a command in a running container
  export      Export a container's filesystem as a tar archive
  kill        Kill one or more running containers
  logs        Fetch the logs of a container
  pause       Pause all processes within one or more containers
  port        List port mappings or a specific mapping for the container
  ps          List containers
  rename      Rename a container
  restart     Restart one or more containers
  rm          Remove one or more containers
  run         Run a command in a new container
  start       Start one or more stopped containers
  stats       Display a live stream of container(s) resource usage statistics
  stop        Stop one or more running containers
  top         Display the running processes of a container
  unpause     Unpause all processes within one or more containers
  update      Update configuration of one or more containers
  wait        Block until one or more containers stop, then print their exit codes

```

### Dockerfile

The instructions from the dockerfile file are automatically executed after the docker build command.

- `FROM` creates a layer from the selected image
- `RUN` builds your application with make
- `COPY`  creates a copy of local files into the container

