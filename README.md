

<p align="center">
  <img  src="https://github.com/mgbq/nx-admin/blob/master/src/assets/img/home/logo.png">
</p>

<p align="center">
  <a href="https://github.com/vuejs/vue">
    <img src="https://img.shields.io/badge/vue-2.5.10-brightgreen.svg" alt="vue">
  </a>
  <a href="https://github.com/ElemeFE/element">
    <img src="https://img.shields.io/badge/element--ui-2.3.2-brightgreen.svg" alt="element-ui">
  </a>
   <a href="https://travis-ci.org/mgbq/nx-admin" rel="nofollow">
    <img src="https://travis-ci.org/mgbq/nx-admin.svg?branch=master" alt="Build Status">
  </a>
    <a href="https://github.com/mgbq/nx-admin/blob/master/LICENSE">
    <img src="https://img.shields.io/github/license/mgbq/nx-admin.svg" alt="license">
  </a>
  <a href="https://github.com/mgbq/nx-admin/releases">
    <img src="https://img.shields.io/badge/release-1.2-blue.svg" alt="GitHub release">
  </a>
  
  > ## :gem: Vue自动化管理系统
</p>

简体中文 | [English](./README.en.md)


# nxAdmin-template

> 这是一个 极简的vue admin 管理后台 它只包含了 Element UI & axios & iconfont & permission control & lint，这些搭建后台必要的东西。

[线上地址](http://mgbq.github.io/nxAdmin-template)

## Extra
如果你想要根据用户角色来动态生成侧边栏和router，你可以使用改分支[permission-control](https://github.com/mgbq/nx-admin/releases/tag/v1.0.0)
 
 ## 相关项目
 [nx-admin](https://github.com/mgbq/nx-admin)

## 相关文档
[老板让我十分钟上手nx-admin](https://juejin.im/post/5b43226c51882519ad616c2a)

[Vue2.0实现的用户权限控制](http://blog.csdn.net/qq_32340877/article/details/79416344)



欢迎你为 nx-admin的开发作出贡献（代码编写/文档翻译）。

## 开发
```bash
# 克隆项目
git clone https://github.com/mgbq/nxAdmin-template.git

# 安装依赖
npm install
   
# 建议不要用cnpm安装 会有各种诡异的bug 可以通过如下操作解决 npm 下载速度慢的问题
npm install --registry=https://registry.npm.taobao.org

# 启动服务
npm run dev
```

## 发布
```bash
# 构建测试环境
npm run build:sit

# 构建生产环境
npm run build:prod
```

## 其它
```bash
# --report to build with bundle size analytics
npm run build:prod --report

# --preview to start a server in local to preview
npm run build:prod --preview

# lint code
npm run lint

# auto fix
npm run lint -- --fix
```
## 捐赠 觉得不错 赏个咖啡 让作者打起精神 ~
<img src="./github/二维码.jpg" width="400px" height="460px" alt="捐赠扫一扫">

## License

[MIT](https://github.com/mgbq/nxAdmin-template/blob/master/LICENSE)
Copyright (c) 2018-present nxmin
