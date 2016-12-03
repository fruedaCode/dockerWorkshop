# DockerWorkshop
##Docker workshop at URV
[Presentación](https://docs.google.com/presentation/d/1ewcUKvVnoAAu96rldC1jjqwUmvf9Js48FIFAQCOFxY0/edit?usp=sharing)

## Prerequisites
### Linux
[Docker engine for ubuntu](https://docs.docker.com/engine/installation/linux/ubuntulinux/)

### Windows 10
Hyper-v + 
[Docker engine for windows](https://docs.docker.com/engine/installation/windows/)



## Workshop
```sh
$ git clone https://github.com/fruedaCode/dockerWorkshop
$ cd dockerWorkshop
$ docker build -t nodeapp .
$ docker run -d -p 8080:8080 --name nodeapp nodeapp
```


##Monitorización contenedores
```sh
$ docker stats $(docker ps|grep -v "NAMES"|awk '{ print $NF }'|tr "\n" " ")
```

