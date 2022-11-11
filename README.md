# Exorde-CLI-Docker-Guide

The shortest and fastest installation guide:
1
```
apt update
```
2
```
apt install git
```
3
```
apt install apt-transport-https ca-certificates software-properties-common curl
```
4
```
curl -f -s -S -L https://download.docker.com/linux/ubuntu/gpg | sudo apt-key add -
```
5
```
sudo add-apt-repository "deb [arch=amd64] https://download.docker.com/linux/ubuntu bionic stable"
```
6
```
apt update
```
7
```
cd /root
```
8
```
sudo apt install docker-ce docker-ce-cli containerd.io docker-compose-plugin -y
```
9
```
sudo systemctl status docker
```
10
```
git clone https://github.com/exorde-labs/ExordeModuleCLI.git
```
11
```
cd ./ExordeModuleCLI
```
12
```
docker build -t exorde-cli .
```
13
```
docker run -d exorde-cli -m 0xfbe0DA7F87D1979812B3a68fc07fb7231EC80c16 -l 2
```


