# openhfw

#### 一 、介绍
OpenHFW是一款开源的Linux服务器高级威胁感知系统，由下一代防火墙和主机安全组成，专注未知攻击对抗。

#### 二、承诺和不承诺
承诺：为了保证服务器安全，除首次安装，任何时候绝不联网。

不承诺：无论任何原因引发的任何问题，都不负任何责任；请务必在测试环境完美演练后，再部署到生产环境。

注意：WEB管理9998端口禁止向公网开放，或者严格设置IP白名单访问权限。

#### 三 主要功能
    1、XDP下一代流量防火墙：全程记录网络流量、抗击DDOS、检测异常IP等，保障流量安全。
    2、进程防火墙：用AI技术分析检测异地IP、异常进程、危险木马行为等，保障进程安全。
    3、主机安全系统：包括文件防篡改、SSH命令登录审计、基线检测、漏洞扫描等，保障主机安全。

#### 四、安装步骤
支持Linux x86 64位系统（arm暂不开放），保证可以上网，以root权限运行下面命令：

    1、 wget http://59.110.1.135/openhfw
    2、 chmod +x ./openhfw
    3、 ./openhfw

首次安装下载大约半分钟，出现System is running.....代表安装成功，可以WEB管理口9998（防火墙允许）登录进去。

#### 五、运行停止卸载
启动运行:  ./openhfw         后台模式运行:   ./openhfw daemon

停止运行:  ./openhfw stop    卸载 :   rm  /openhfw/ -rf

默认没加开机启动，请自行把openhfw 加入开机启动程序。

#### 六、实战演示地址

实战地址 [http://59.110.1.135/openhfw.html](http://59.110.1.135/openhfw.html)

#### 七、付费演示地址

单机版免费，但开放源码、分布式集中管控、技术支持、功能增加等要收费。请用大屏电脑观看，首次加载大屏组件需要10秒：
集中管控大屏 [http://59.110.1.135/center.html](http://59.110.1.135/center.html)

#### 八、源码部署请加微信号httpwaf

![](https://gitee.com/httpwaf/httpwaf/raw/master/img/wechat.png)

#### 九、来一张首页图片

![](https://gitee.com/httpwaf/httpwaf/raw/master/img/home.png)
