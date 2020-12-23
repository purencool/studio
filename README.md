# Purencool Studio

##### Installation
https://www.purencool.digital/support/installation

##### Start ide

```
purencoolstudio ide $(pwd) 5001 mytest_john
```


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