# NMap command dockerized #
This is a docker build with the linux NMAP command. The image is based on the Alpine Linux image.

## Build
```
$ docker build -t freelyit/nmap .
```

## Run for specific IP Address
```
$ docker run --rm freelyit/nmap <ip address>
```

## Run for whole subnet
```
$ docker run --rm freelyit/nmap -sP <subnet as 192.168.10.0/24>
```
