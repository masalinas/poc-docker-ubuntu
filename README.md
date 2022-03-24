# Description
PoC Manage Ubuntu docker in interactive mode

## Start ubuntu container
Create and Start ubuntu image in interactive mode

```shell
docker run -it --name ubuntu ubuntu
```

## Exit from ubuntu container
write this command to exit from container

```shell
exit
```

## Start again the container

```shell
docker start ubuntu
```

## Attach to container

```shell
docker attach ubuntu
```

## Start container in interactive mode
We could go inside the container directly from this command
```shell
docker start -i ubuntu
```

```shell
docker exect -it ubuntu
```

## Exit the containr and remove it

```shell
docker rm ubuntu
```
