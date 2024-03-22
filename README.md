![Hackazon Logo](https://github.com/rapid7/hackazon/blob/master/web/images/Hackazon.png?raw=true "Hackazon Logo")


## About Hackazon
Hackazon is a vulnerable test application site, that incorporates a realistic e-commerce workflow with full functionality and technology commonly used in today’s mobile and web applications.

This guide will allow you to setup a testing environment, enable you to see problems in action from an attacker’s perspective, and identify the fundamental issues which make such attacks possible.

[Hackazon_User's_Guide.pdf](https://community.rapid7.com/servlet/JiveServlet/downloadBody/3452-102-3-8267/Hackazon_User%27s_Guide.pdf)

## How to use this project 

### Clone this repo 
```shell
git clone https://github.com/Spartan1776/hackazon/
cd hackazon/
```

### Configure Docker
If you haven't already installed docker, you'll need to do so. If you're running Ubuntu or a similar Debian-based distro that uses the Advanced Package Tool (APT, or "apt"), you can convert easyDockerInstall to an executable and run the installation file:
```shell
chmod +700 easyDockerInstall
sudo ./easyDockerInstall
```

### Build and start
Once Docker is installed, start the docker image:
```shell
docker-compose up
```

### Wait for 10 seconds and contact the server :
```shell
firefox http://127.0.0.1:80

chromium http://127.0.0.1:80
```

## Configure

The project is configured by the files 
- [docker-compose.yml](https://github.com/Newlode/hackazon/blob/master/docker-compose.yml)
- [config/db.sample.php](https://github.com/Newlode/hackazon/blob/master/docker-compose.yml)

## Special Thanks
This project is a direct fork (+ a couple of edits) from Newlode's OG Hackazon project -- thanks for all the hard work!
