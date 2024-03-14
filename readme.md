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


## 数据测试

> 数据库结构如 db.js 中所示

你可以通过以下代码将数据导入到数据库中, 其他几个表的数据导入方式类似

```bash
for (let i = 0; i < 10; i++) {
    Lose.create({
        openid: 'o1rUR5dHCRwTftgzmc6sh4hE8bwM',
        type: 0,
        classify1: '数码产品',
        classify2: '相机',
        name: '1',
        date: '2',
        region: '3',
        phone: '4',
        desc: '5',
        imgList: [ "http:127.0.0.1:30001/file/94945613-25da-406e-8ffa-1e4aa31ddf02.png" ],
        time: 1669212404681
    })
}
```

## 其他问题

> 由于时间关系, 本项目中的一些功能并未实现, 如: 用户信息修改等, 可以根据自己的需求进行修改; 接口返回的数据格式也可以根据自己的需求进行修改, 这边写的有点简陋, 你可以根据自己的需求进行修改 index.js 中的接口返回格式以及鉴权(这个我没写)等等逻辑代码
