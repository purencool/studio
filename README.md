# Purencool Studio

#### Manual

```
sed -e '/###/,/##/!d' purencoolstudio
```

#### Development

Stop all running containers
```
docker stop $(docker ps -a -q)
```
Delete all stopped containers

```
 docker rm $(docker ps -a -q)
```

Delete all docker images

```
docker rmi $(docker images -a -q)
```