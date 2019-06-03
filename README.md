# docker-dummy

This is a simple image that runs forever and does nothing.
It purpose is to have a running container to pass some environment variables to other containers like `jwilder/docker-gen`.

# Usage

```bash
$ docker run -d --name docker-dummy gibby/dummy
```
