
# Customizing the Banner
---

springboot启动的时候会有一个默认的banner，如果想替换的话只需要在src/main/resources目录下创建一个banner.txt文件即可，banner.txt文件中就是自定义的图案如下

![](https://jverson.oss-cn-beijing.aliyuncs.com/201707141540_19.png)

[点此进行banner图案的在线生成](http://patorjk.com/software/taag/#p=display&f=Big%20Money-sw&t=Type%20Something%20)

一个典型的设置如下：
```
   _____            _             _                 _     _____                       
  / ____|          (_)           | |               | |   |  __ \                      
 | (___  _ __  _ __ _ _ __   __ _| |__   ___   ___ | |_  | |  | | ___ _ __ ___   ___  
  \___ \| '_ \| '__| | '_ \ / _` | '_ \ / _ \ / _ \| __| | |  | |/ _ \ '_ ` _ \ / _ \ 
  ____) | |_) | |  | | | | | (_| | |_) | (_) | (_) | |_  | |__| |  __/ | | | | | (_) |
 |_____/| .__/|_|  |_|_| |_|\__, |_.__/ \___/ \___/ \__| |_____/ \___|_| |_| |_|\___/ 
        | |                  __/ |                                                    
        |_|                 |___/      
 
---------------------------------- Spring-Boot-Demo ----------------------------------

Author: Jverson
Powered by Spring Boot${spring-boot.formatted-version}

--------------------------------------------------------------------------------------
```

