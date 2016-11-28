# dockerWorkshop
###Docker workshop at URV

###Prerequisites
[Docker engine](https://docs.docker.com/engine/installation/linux/ubuntulinux/)


```sh
$ git clone https://github.com/fruedaCode/dockerWorkshop
$ cd dockerWorkshop
$ docker build -t nodeapp .
$ docker run -d -p 8080:8080 --name nodeapp nodeapp
```

