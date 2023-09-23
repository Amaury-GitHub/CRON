# CRON
## 背景描述
本程序基于go实现了定时任务调用外部程序</br>
基于工作的需求,需要定时复制现场设备数据到共享盘或者写入到数据库,Windows的任务计划实在不太好用,特别是某些系统使用了德语,妥妥的折磨自己</br>
所以自己开发一个app来实现需要的功能</br>
## 功能介绍
使用ini文件存储相关参数,实现了一个通用程序,本程序只负责调用外部程序,可以增减task的数量,定时部分使用cron参数</br>
使用txt文件存储日志</br>

![image](https://github.com/Amaury-GitHub/CRON/blob/master/README_IMG/IMG1.png)<br>
## 截图
![image](https://github.com/Amaury-GitHub/CRON/blob/master/README_IMG/IMG2.png)<br>
![image](https://github.com/Amaury-GitHub/CRON/blob/master/README_IMG/IMG3.png)<br>
![image](https://github.com/Amaury-GitHub/CRON/blob/master/README_IMG/IMG4.png)<br>
![image](https://github.com/Amaury-GitHub/CRON/blob/master/README_IMG/IMG5.png)<br>
