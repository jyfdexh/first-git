# first-git
nanno永远滴神！！！！


## 青龙命令
先进入root身份   sudo su root

再进入QL主机     docker exec -it QL bash

使用 进入主机后的内置命令
更新并重启青龙
ql update                                                                                                
启动tg-bot
ql bot                                                       
检测青龙环境并修复
ql check                                                     

# 重启Ubuntu后          
开启clash代理：
systemctl start clash

执行以下命令，启动 VNC 服务：

sudo vncserver

执行以下命令，重启 vnc 桌面进程。

sudo vncserver -kill :1 #杀掉原桌面进程，输入命令（其中的:1是桌面号）

sudo vncserver -geometry 1920x1080 :1 #生成新的会话(分辨率！)
