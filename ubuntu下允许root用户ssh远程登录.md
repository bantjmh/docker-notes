## 使用apt命令安装openssh server

```sudo apt-get install openssh-server```


## 对 openssh server进行配置

```sudo vi /etc/ssh/sshd_config```

找到PermitRootLogin no一行，改为PermitRootLogin yes

 
## 重启 openssh server

```sudo service ssh restart```
