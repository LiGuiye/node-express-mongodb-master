## NodeJS+Express+MongoDB  
    以文章管理系统为例，实现了登录注册模块和文章管理模块的开发，可以充分帮助大家了解Node.js Web服务端的开发流程，学会Node.js服务的搭建，学习MongoDB数据库的增删改查操作，学会构建一个完整的Web系统。  
### 能学会什么  
1. 学会使用express-generator搭建Express项目
2. 学会使用 mongo shell 连接MongoDB服务并执行数据库的常用操作
3. 学会使用 mongodb 模块完成数据库的增删改查任务
4. 学会注册、登入登出、登录拦截、Session会话的实现逻辑
5. 学会使用富文本工具 xhEditor，实现文章的发布
6. 学会文件上传的原理以及如何实现图片上传
7. 学会分页查询的原理与实现
8. 学会文章修改、删除与详情的实现
### 提前准备
1. [提前下载并安装好Node.js环境](http://nodejs.cn/download/)
2. [提前下载并安装好 MongoDB](https://www.mongodb.com/)
### 直接运行
1. MongoDB数据库新建数据库和articles/users两个表以存储文章数据和用户数据
2. 更改model/mongodb.js中的数据库配置（url和dbName）
3. 项目根目录下命令行 npm install安装依赖包
4. 项目根目录下命令行 npm start启动
5. 浏览器运行localhost:3000