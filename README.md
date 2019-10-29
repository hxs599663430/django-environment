# 基于Django开发的动力环境检测系统的API接口

#### 项目介绍

​	项目背景：类似于很多大型公司的服务器放置在某个防空洞下，但是又全面知道这个防空洞环境下的状态（比如湿度、温度等）。这个动力环境监测系统就是通过这个背景开发的，这里只提供了接口

​	技术使用：MySQL、python、Django框架

​	项目功能：该系统项目完成了accessControls（门禁管理）、alarm（告警管理）、logs（日志管理）、scene（场景管理）、user（用户管理）、videos（视频管理）等。详细介绍如下：

​		项目需求：![动力环境监测需求分析表](C:\Users\xusha\Desktop\django-environment\readme_images\project_requirements.png)

​		1、门禁管理主要是实现了门禁信息查看、用户申请门禁和门禁审核、门禁信息导出excel表：界面如下：

![1572360777768](C:\Users\xusha\Desktop\django-environment\readme_images\1572360777768.png)

​		2、告警管理主要是完成告警信息的查看、处理、审核、统计、导出

![1572361005089](C:\Users\xusha\Desktop\django-environment\readme_images\1572361005089.png)

​		3、日志管理只完成了日志信息的查看、导出，至于添加都是在与数据库进行交互的时候自动添加到日志表中

![1572361147806](C:\Users\xusha\Desktop\django-environment\readme_images\1572361147806.png)

​		4、场景管理的功能很多，还有些功能接口正在完善中；这里只实现了场景信息的增删查改以及获取场景中设备的数据

![1572361321365](C:\Users\xusha\Desktop\django-environment\readme_images\1572361321365.png)

​		5、用户管理也是完成了用户信息的增删查改及用户的冻结与激活

![1572361439462](C:\Users\xusha\Desktop\django-environment\readme_images\1572361439462.png)

​		6、视频管理完成了视频管理界面的分屏与独屏显示的接口、视频信息的增删查改

![1572361518925](C:\Users\xusha\Desktop\django-environment\readme_images\1572361518925.png)

​		7、接口里面会有详细的参数说明和后台响应的字段说明：界面如下：（随便取一个接口测试）

![1572361615323](C:\Users\xusha\Desktop\django-environment\readme_images\1572361615323.png)

