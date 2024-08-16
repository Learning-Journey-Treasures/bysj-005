**扫码 >> 源码商城 获取** ![qrcode_for_gh_1266b4b5294a_258 (2)](https://github.com/user-attachments/assets/45838afd-19a8-4cdc-bdd5-74b9c76fb241)

**郑重声明：项目经过本地测试，确保可以运行。项目仅供学习和毕业设计参考~**

1.项目介绍
技术栈+环境：SSM + Maven + LayUI + dtree + Maven

汽车租赁系统总共分为两个大的模块，分别是系统模块和业务模块。其中系统模块和业务模块底下又有其子模块。

业务模块包含：客户管理、车辆管理、出租单管理、检查单管理、统计分析等。

系统模块包含：菜单管理、角色管理、用户管理、数据源监控

2.项目部署
创建数据库，导入项目中的sql文件

打开IDEA，open——>双击项目里的pom.xml导入项目

进入 src/main/resources/jdbc.properties 1-4行，更具本地数据库的环境修改数据库连接

通过IDEA创建 Tomcat Local server启动项目 http://localhost:8080/

管理员账号密码： admin/123456

业务员账号密码：zhangsan/123456

其他角色根据角色自行创建并分配菜单
![1](https://github.com/user-attachments/assets/c0c09f47-f089-43e6-b1b1-9b915d76f593)
![2](https://github.com/user-attachments/assets/56cb011e-3030-4228-b9e9-17141e7c0d6d)
![3](https://github.com/user-attachments/assets/dc997cd7-9fa3-425e-8fd2-8f97a87f82a9)
![4](https://github.com/user-attachments/assets/6de57d2f-5735-45df-8abd-42e3239fd4a3)
![5](https://github.com/user-attachments/assets/1da73ed9-1ed7-44e2-8e37-6db6c2510a4e)
![6](https://github.com/user-attachments/assets/49ace38c-bea5-4e91-bc06-e2520e839c0e)
