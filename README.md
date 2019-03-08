# CentOS Shadowsocks安装及加速

## 安装Shadowsocks
* 安装wget

```
yum -y install wget
```
* 安装脚本

```
wget -N --no-check-certificate https://raw.githubusercontent.com/WannaYoung/Script/master/SS/ssr.sh && chmod +x ssr.sh && bash ssr.sh
```
## 安装锐速加速
* 更换内核

```
wget --no-check-certificate https://raw.githubusercontent.com/WannaYoung/Script/master/SS/kernel.sh && bash kernel.sh
```
* 一键安装锐速

```
wget -N --no-check-certificate https://raw.githubusercontent.com/WannaYoung/Script/master/SS/serverspeeder.sh && bash serverspeeder.sh
```

