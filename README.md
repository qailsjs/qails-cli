# qails
一个简易的类似 ruby on rails 的 node 快速开发框架

## 安装

1. 全局安装 qails
```
npm install -g qails-cli
```

2. 用 qails 初始化一个新项目
```
# 初始化一个名称为 myproject 的工程
qails init myproject
```

3. 进入项目目录，启动服务
```
cd myproject
npm run start
```

## 生成器
```
# 初始化一个名称为 myproject 的工程
qails init myproject

# 新建模型 user
qails model user

# 新建路由 /user
qails route /user
```