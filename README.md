# registry-example

## Build
```
$ docker-compose up
```

## Usage
```
$ docker pull ubuntu:latest

$ docker tag ubuntu:latest localhost:5000/kuro/ubuntu:latest

$ docker push localhost:5000/kuro/ubuntu:latest

$ docker rmi localhost:5000/kuro/ubuntu:latest

$ docker pull localhost:5000/kuro/ubuntu:latest
```
