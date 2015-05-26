# docker-iojs
build docker iojs images

```
docker run -it --rm docker.io/azole/docker-iojs node -v   
v2.1.0
```

mount local directory to container 
```
docker run -it --rm -v /home/azole/es6:/es6 -w="/es6" --privileged=true docker.io/azole/docker-iojs node let.js
```
