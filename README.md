# react-ssr-live

# 构建目录

```H
├── build // 打包目录
│   ├── webpack.base.config.js
│   ├── webpack.client.config.js
│   └── webpack.server.config.js
├── build-client // 客户端打包文件夹
├── build-server // 服务端打包文件夹
├── config // 打包相关配置文件
└── src // 同构代码源码目录
    ├── App.js // 同构代码入口文件
    ├── assets // 需要引入项目中的静态资源
    ├── components // 公共组件文件夹
    ├── components-hoc // 高阶组件文件夹
    ├── entry-client // 客户端入口文件夹
    │   └── index.js
    ├── entry-server // 服务端入口文件夹
    │   ├── index.js
    │   └── renderContent.js
    ├── public // 公共函数方法等
    ├── router // 路由配置文件夹
    ├── static // 直接会打包生成到entry-client文件夹下，不会直接引入项目中
    ├── store // 共享数据store文件夹
    └── views // 不同页面文件夹

```
