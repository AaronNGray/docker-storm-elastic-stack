# docker-storm-elastic-stack - Docker compose for Storm Elastic Stack

## Installation

### Install WSL 2
https://docs.microsoft.com/en-us/windows/wsl/install-win10
### Install Ubuntu
https://www.microsoft.com/en-gb/p/ubuntu/9nblggh4msv6?activetab=pivot:overviewtab

### Install systemd
```
git clone https://github.com/DamionGans/ubuntu-wsl2-systemd-script.git
cd ubuntu-wsl2-systemd-script/
bash ubuntu-wsl2-systemd-script.sh
cd ..
```

### Clone docker-storm-elastic-stack
```
git clone https://github.com/AaronNGray/docker-storm-elastic-stack.git
cd docker-storm-elastic-stack
```
### Start systemd
```
./config/wsl-systemd.sh
```
### Set the maximum number of memory map areas per process
```
./config/sysctl.sh
```
### Checkout version 2.x
git checkout v2.x

### Run docker compose
```
docker-compose up -d
```
### Stop docker
```
docker-compose down
```
