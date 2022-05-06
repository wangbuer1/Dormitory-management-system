# 宿舍管理系统

关注公众号： **程序员王不二** （ javaCodeSharing），回复 “宿舍3 ” ，即可免费获取完整版的项目代码。此公众号持续分享各种免费java项目源码。

![公众号二维码](https://gitee.com/buer_wang/project-drawing-bed/raw/master/Typora-Images/20220506172129.jpg)

## 1、项目介绍

宿舍管理系统拥有三个角色，分别为系统管理员、宿舍管理员以及学生。其功能如下：

管理员：宿舍管理员管理、学生管理、宿舍楼管理、缺勤记录管理、个人密码修改等

宿舍管理员：查看学生及添加缺勤记录、缺勤记录查看和修改

学生：查看自己的缺勤记录、修改密码

## 2、项目技术

后端框架： servlet、mvc模式

前端框架：bootstrap、jsp

其它：mysql5-8、tomcat8-10、JDK1.8+

## 3、开发工具

eclipse、idea、myEclipse

## 4、功能介绍

### 4.1系统登录

![登录](https://gitee.com/buer_wang/project-drawing-bed/raw/master/Typora-Images/20220506174126.jpg)

系统三种角色通过此界面登录宿舍管理系统，经过密码验证通过后，分别跳转至不同的页面

### 4.2系统管理员-宿舍楼管理

![image-20220506174250073](https://gitee.com/buer_wang/project-drawing-bed/raw/master/Typora-Images/20220506174251.png)

系统管理员可以添加宿舍楼，并能够根据宿舍楼名称搜索相对应的信息，同时系统管理员还可以修改和删除宿舍楼，以及给不同的宿舍楼设置管理员等功能。

### 4.3系统管理员-学生管理

![学生管理](https://gitee.com/buer_wang/project-drawing-bed/raw/master/Typora-Images/20220506174449.jpg)

系统管理员可以添加、修改、删除学生，同时可以按照宿舍楼、姓名、学号等条件搜索学生。系统管理员的其它功能与上述功能类似，且可以在视频中看到，这里不在赘述。

### 4.4宿舍管理员-缺勤记录管理

![image-20220506174828040](https://gitee.com/buer_wang/project-drawing-bed/raw/master/Typora-Images/20220506174829.png)

宿舍管理员可以通过姓名学号等条件搜索学生，并给学生添加、修改和删除相应的缺勤记录

### 4.5学生界面

![学生查看缺勤记录](https://gitee.com/buer_wang/project-drawing-bed/raw/master/Typora-Images/20220506174928.jpg)

学生查看自己的缺勤记录

## 5、视频演示



（视频在 链接网页的下方）



