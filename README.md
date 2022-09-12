# first-git


tg.jyf.workers.dev


nanno永远滴神！！！！
 (有关代理都来自https://www.youtube.com/watch?v=VOlWdNZAq_o&t=591s 他的/opt位置相当于我的/home/ubuntu,docker方法很简单没试过如果重装系统建议用docker方法翻墙)

# 重启Ubuntu后          
## Clash代理
开启clash代理： (需在/home/ubuntu/clash目录下执行以下命令)

systemctl start clash    (重启：systemctl restart clash 关闭：systemctl stop clash 查看代理状态：systemctl status clash
 开机自启没用过： systemctl enable clash  ）

（任意位置快捷执行：     经过youtobe设置的快捷开启clash代理：proxy 关闭：unproxy)

修改clash订阅：复制CFW的内容到Ubuntu的Clash-jiedian.yaml，并在头部加上3行绑定可视化UI：  
external-controller: '0.0.0.0:9090'  
external-ui: /home/ubuntu/clash/ui  
secret: '123456'

## 启动 VNC 可视化服务：

sudo vncserver  
执行以下命令，重启 vnc 桌面进程。  
sudo vncserver -kill :1 #杀掉原桌面进程，输入命令（其中的:1是桌面号）  
sudo vncserver -geometry 1920x1080 :1 #生成新的会话(分辨率！)  
开启xshell终端代理： proxy   
              关闭：unporxy

## 青龙命令
先进入root身份   sudo su root  
### 再进入QL主机     docker exec -it QL bash  
### ls:  再进入data才是新版青龙真正映射的位置------cd script 脚本配置位置
使用 进入主机后的内置命令  
更新并重启青龙
ql update                                                                                                
启动tg机器人
ql bot                                                       
检测青龙环境并修复
ql check                                                     
【经验分享】创建docker容器后修改挂载目录的方法https://segmentfault.com/a/1190000040899948  
![image](https://user-images.githubusercontent.com/60847489/189470126-73755ac5-6a6d-4fe0-90b0-5f387e1f287b.png)

## 错误
Ubuntu使用apt-get就够用了。如果安装需要yum，这里没有解决repos的报错。以后的错误，以后再解决。


