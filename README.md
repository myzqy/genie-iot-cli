# 安装

## 安装tnpm
tnpm是阿里定制的npm，内部私有的模块都会发布到这里（官网：http://web.npm.alibaba-inc.com/）

```
$ npm i -g npminstall --registry=http://registry.npm.alibaba-inc.com
$ npminstall -g tnpm --registry=http://registry.npm.alibaba-inc.com
```
## 安装vue-cli

```
$ npm install -g vue-cli
```

## 拉取模版生成demo

```
$ vue init aligenie-iot-team/genie-iot-cli my-project
$ cd my-project
// 安装依赖可以用tnpm install会快一些
$ npm install
$ npm run dev
```
## 打包

```
$ npm run build
```

# 参考资料
* 组件：http://element-cn.eleme.io/#/zh-CN/component/button
* vue :https://cn.vuejs.org/v2/guide/installation.html
* vuex（状态管理）:https://vuex.vuejs.org/zh/guide/
* vue api: https://cn.vuejs.org/v2/api

# 开发文档地址
http://doc-bot.tmall.com/docs/doc.htm?spm=0.7629140.0.0.4c821780dgvz7g&treeId=578&articleId=109436&docType=1
