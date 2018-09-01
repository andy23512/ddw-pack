# ddw-pack
start pack for docker, django and webpack

## Reference
https://realpython.com/blog/python/django-development-with-docker-compose-and-machine/

## Setup Docker Machine

### Create Docker Machine
```bash
$ docker-machine create -d virtualbox dev
```
### Point Docker at the dev machine
```bash
$ eval $(docker-machine env dev)
```
### Show currently running machines
```bash
$ docker-machine ls
```
