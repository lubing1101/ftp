# ftp
### 项目介绍

该项目基于C语言，实现了在网络上进行文件下载的功能，类似于FTP文件传输服务器。
 该项目主要分为服务端和客户端。服务端提供登录认证，文件许可下载，可下载文件列表功能。客户端提供发起登录请求，下载文件请求功能。
相关技术点:
1.	该项目主要使用Linux 系统编程和套接字网络编程相关API。
2. 为了提供多用户使用需求，在服务端中通过fork子进程来实现多用户使用功能，单个子进程处理特定客户端的请求。
3. 客户端与服务端之间通过自定义协议来确认是否登录成功，下载成功等状态，而客户端向服务端发送账户密码以此为凭证来确认是否有权限使用



### 运行效果

### 运行环境

ubuntu

### 快速教程 

1.下载源码

2.解压

3.进入源码目录，运行make命令，生成server，client可执行程序 

4.运行server程序

5.运行client订阅者程序

### 项目结构

无

### 版权信息 

暂无