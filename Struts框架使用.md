# Struts框架使用



## 1、目的



1. 实现用SSH框架构建一个web应用
2. 

## 2、遇到的问题

问题一（2019.9.22）：

描述：第一次接触struts2，执行HelloWorldStruts2时，console出现报错信息



截图：

![1569084777747](C:\Users\HJN\AppData\Roaming\Typora\typora-user-images\1569084777747.png)

![1569084478839](C:\Users\HJN\AppData\Roaming\Typora\typora-user-images\1569084478839.png)

严重：One or more Filters failed to start. Full details will be found in the appropriate container log file



总结：

1. 首先要注意的是**DOCTYPE**（文档类型）。如我们的示例所示，所有的Struts配置文件都需要有正确的doctype。
2. 建议使用的struts2版本为2.3.3，2.5版本的struts2lib文件缺少xwork-core-x.x.xx.jar包，导致出现上述问题



