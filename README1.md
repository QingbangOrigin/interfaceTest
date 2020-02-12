# interfaceTest
概述
框架还是基于Python+unittest+requests+HTMLTestRunner框架来设计，目录布局有common存储一些邮件、html请求方法、HTMLTestRunner报告和日志等调用文件；框架存放路径；获取链接、整合参数；运行文件（调用common、unittest文件）

详解
获取地址读取ip端口：config.ini、getpathInfo.py，readConfig.py

拼接地址：geturlparams.py

写入报告同时运行case：caselist.txt、logs、report.html，同时运行test01case.py

运行test01case：参数文件geturlparams.py，readExcel.py初始化变量（获取用例名、接口路径、参数、方法），configHttp.py（methon、url、data）请求

 
