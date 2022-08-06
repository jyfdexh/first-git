# first-git
5461332764:AAHJpn6nALBFpUnVMsUA5VTXjdNUWmv1PIg

1047773545

tg.jyf.workers.dev

https://tg.jyf.workers.dev/bot5461332764:AAHJpn6nALBFpUnVMsUA5VTXjdNUWmv1PIg/sendMessage?chat_id=1047773545&text=222

nanno永远滴神！！！！
 (有关代理都来自https://www.youtube.com/watch?v=VOlWdNZAq_o&t=591s 他的/opt位置相当于我的/home/ubuntu,docker方法很简单没试过如果重装系统建议用docker方法翻墙)

# 重启Ubuntu后          
开启clash代理： 

systemctl start clash    (关闭：systemctl stop clash  开机自启没用过： systemctl enable clash )

启动 VNC 可视化服务：

sudo vncserver

执行以下命令，重启 vnc 桌面进程。

sudo vncserver -kill :1 #杀掉原桌面进程，输入命令（其中的:1是桌面号）

sudo vncserver -geometry 1920x1080 :1 #生成新的会话(分辨率！)

开启xshell终端代理： proxy   
              关闭：unporxy

## 青龙命令
先进入root身份   sudo su root

再进入QL主机     docker exec -it QL bash

使用 进入主机后的内置命令
更新并重启青龙
ql update                                                                                                
启动tg机器人
ql bot                                                       
检测青龙环境并修复
ql check                                                     

## 错误
Ubuntu使用apt-get就够用了。如果安装需要yum，这里没有解决repos的报错。以后的错误，以后再解决。

