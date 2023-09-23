# ![image](https://github.com/Amaury-GitHub/CRON/blob/main/CRON/logo.ico)
## 背景描述
本程序基于go实现了定时任务调用外部程序</br>
基于工作的需求,需要定时复制现场设备数据到共享盘或者写入到数据库,Windows的任务计划实在不太好用,特别是某些系统使用了德语,妥妥的折磨自己</br>
所以自己开发一个app来实现需要的功能</br>
有需要的小伙伴自取</br>

## 功能介绍
使用ini文件存储相关参数,实现了一个通用程序,本程序只负责调用外部程序,可以增减task的数量,定时部分使用标准的cron参数</br>
[在线Cron表达式生成器](https://cron.qqe2.com/)</br>
执行的命令不支持中文</br>
没有动态读取的功能,改变ini后需要重启程序</br>
使用txt文件存储日志</br>
核心文件只有[CRON.exe](https://github.com/Amaury-GitHub/CRON/blob/main/CRON/CRON.exe)和[CRON_Config.ini](https://github.com/Amaury-GitHub/CRON/blob/main/CRON/CRON_Config.ini)</br>
CRON_Log.txt文件会自动创建</br>
托盘程序,不打扰</br>
右键菜单可直达配置文件与日志文件</br>

![image](https://github.com/Amaury-GitHub/CRON/blob/main/README_IMG/IMG1.png)<br>
## 截图
![image](https://github.com/Amaury-GitHub/CRON/blob/main/README_IMG/IMG2.png)<br>
建议使用cmd来调用exe,实测可以直接填exe的路径,但是log有问题,执行后只有开始标志,exe关闭后才有结束标志</br></br>
![image](https://github.com/Amaury-GitHub/CRON/blob/main/README_IMG/IMG3.png)<br>
![image](https://github.com/Amaury-GitHub/CRON/blob/main/README_IMG/IMG4.png)<br>
![image](https://github.com/Amaury-GitHub/CRON/blob/main/README_IMG/IMG5.png)<br>
