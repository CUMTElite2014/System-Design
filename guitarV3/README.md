# OOA&D
系统分析与设计 课程设计作业

-------------

##说明：[数据库](https://github.com/CUMTElite2014/System-Design/blob/master/guitarV3/1.png) ，Spring注入
----------------------------
##图片运行结果
![Test](https://github.com/CUMTElite2014/System-Design/blob/master/guitarV3/2.png "title")
![](https://github.com/CUMTElite2014/System-Design/blob/master/guitarV3/3.png "title")
![](https://github.com/CUMTElite2014/System-Design/blob/master/guitarV3/4.png"title")
-----------------------------
##代码分析
###更换文件，修改数据库
![更换文件修改数据库](https://github.com/CUMTElite2014/System-Design/blob/master/guitarV3/5.png "title")
![更换文件修改数据库](https://github.com/CUMTElite2014/System-Design/blob/master/guitarV3/6.png "title")
![更换文件修改数据库](https://github.com/CUMTElite2014/System-Design/blob/master/guitarV3/7.png "title")
###初始化仓库，中间注入IGuitarDao
![注入](https://github.com/CUMTElite2014/System-Design/blob/master/guitarV3/8.png "title")
###init方法中调用IGuitarDao，findAll方法
![](https://github.com/CUMTElite2014/System-Design/blob/master/guitarV3/9.png "title")
###Inventory其他方法
![Inventory其他方法](https://github.com/CUMTElite2014/System-Design/blob/master/guitarV3/9.png "title")
###Inventory其他方法。调用IGuitarDao方法，持久化
![Inventory其他方法实现](https://github.com/CUMTElite2014/System-Design/blob/master/guitarV3/10.png "title")

--------------
