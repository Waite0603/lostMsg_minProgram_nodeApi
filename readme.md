## 环境要求

- nodejs
- mongodb

## 项目启动
  
  ```bash
  # 安装依赖
  npm install

  # 启动项目
  node index.js

  ## 正常启动后, 显示如下信息
  ## server running!
  ## 数据库连接成功!
  ## 访问 http://localhost:30001 即可
  ```


1. 下载nodejs框架express
npm install express --save
2. 切换npm镜像源为淘宝镜像源
npm config set registry https://registry.npm.taobao.org
3. 下载nodemon解决nodejs代码更新的痛点
npm install nodemon -g
4. nodejs连接mongodb数据库
npm install mongoose --save
5. 下载multer来实现文件上传存储
npm install multer --save
6. 下载uuid来实现不重复的字符串
npm install uuid --save
7. 下载axios实现网络请求
npm install axios --save