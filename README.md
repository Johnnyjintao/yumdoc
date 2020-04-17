# yumdoc API文档管理系统

![image](https://img.shields.io/badge/vue-2.5.2-blue.svg)
![image](https://img.shields.io/badge/vue--router-3.0.1-blue.svg)
![image](https://img.shields.io/badge/vuex-3.0.1-blue.svg)
![image](https://img.shields.io/badge/element--ui-1.4.7-blue.svg)

#### 已完成
> 你的 "Star" 是我最大的动力！🌹

## 简介

yumdoc是一个API文档管理系统，可用于公司内部api文档管理，支持mock数据，支持url调用mock数据
项目前端采用vue+vuex+element-ui 搭建
适合公司内部使用，管理公司内部文档

## 说明
> 如果此开源系列对你有帮助，你可以点右上角 "star"一下，以表支持，非常感谢！^_^ 🌹

> 或者您可以 "follow（关注）" 一下作者，我正在不断开源更多实用的项目


## 后端node.js +  + koa2 + mysql
#### [请戳这里](https://github.com/Johnnyjintao/yumdoc-server)


## 功能
- [x] 登录/注销
- [x] 使用此项目需注册，注册成功后生成user_id
- [x] 项目管理，用户可新增项目，也可填写 项目id加入项目（新增项目默认为此项目管理员）
- [x] 权限管理，管理员可通过user_id邀请用户，可设置用户权限（只读，读写）。
- [x] API文档（增删改查，mock数据，mock地址调用等）
- [x] ...

## 部分截图
<img src="https://johnnyjintao.github.io/resume/static/yumdoc01.png" width="900px" style="max-width: 100%;"/>
<img src="https://johnnyjintao.github.io/resume/static/yumdoc02.png" width="900px" style="max-width: 100%;"/>



## 安装运行

```
# install dependencies
npm install

# serve with hot reload at localhost:8010
npm start

# build for production with minification
npm run build（File in the docs folder）
```

