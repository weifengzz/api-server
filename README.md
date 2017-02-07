# API Server


## 添加Schema

仿照现有文件格式，直接在Schema目录添加最终的graphql文件

## 运行项目

```
npm install
npm start
```

* 接口调试网址 http://localhost:3000/graphiql
* 开发数据库链接 localhost:3002


## 导入数据

```
mongoimport --drop --host 127.0.0.1:3002 --db database --collection user user.json
mongoimport --drop --host 127.0.0.1:3002 --db database --collection tweet tweet.json
```

## TODO

* 确保功能正常前提下升级核心库版本