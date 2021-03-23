# 017springboot在线选课系统
017springboot在线选课系统


#### 介绍
后端技术包含springboot+mybatis+spring security+mysql+redis
前端技术包含 semanticUI + thymeleaf模板引擎

#### 使用教程
1.  下载项目之后 等待maven安装对应jar包
2.  自行下载redis 并按照资源包下的application.yml要求进行配置
3.  自行安装MySQL数据库 执行资源包下的sql文件

#### 使用说明
1.  运行redis服务器
2.  启动项目
3.  访问localhost:8080
4.  用户名：admin  密码：admin

源码获取：[ **点此获取** ](http://www.shuyue.fun/index.php?type=productinfo&id=166)

#### 注意事项
若导出信息时报错，则需要设置mysql,设置方式如下：

SELECT @@sql_mode; 查看是否包含ONLY_FULL_GROUP_BY；若包含，则执行以下命令：

SET GLOBAL sql_mode='STRICT_TRANS_TABLES,NO_ZERO_IN_DATE,NO_ZERO_DATE,ERROR_FOR_DIVISION_BY_ZERO,NO_AUTO_CREATE_USER,NO_ENGINE_SUBSTITUTION';

SET SESSION sql_mode='STRICT_TRANS_TABLES,NO_ZERO_IN_DATE,NO_ZERO_DATE,ERROR_FOR_DIVISION_BY_ZERO,NO_AUTO_CREATE_USER,NO_ENGINE_SUBSTITUTION';

执行完成后，再通过SELECT @@sql_mode; 来查看；

注意：该方法仅用于临时修改，重启mysql后，以上设置失效。

## 运行截图
![输入图片说明](https://images.gitee.com/uploads/images/2021/0318/123151_ba2bc55c_863230.png "屏幕截图.png")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0318/123207_57eda323_863230.png "屏幕截图.png")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0318/123218_a54168be_863230.png "屏幕截图.png")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0318/123226_e202d174_863230.png "屏幕截图.png")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0318/123236_4b97431d_863230.png "屏幕截图.png")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0318/123245_9f6eef66_863230.png "屏幕截图.png")



