# tencent-office-homework-react

> 腾讯文档前端课程 react 作业项目模板.

在自己仓库上开发 react 组件和页面. 需要实现 checkbox多选, select多选框, slide进度条, input输入框, switch开关. 不允许使用组件库, 交互功能和样式参考demo.

# demo

页面demo视频: https://tencent-school.coding.net/p/tencent-school/d/homework-react-template/git/tree/master/example

页面demo示例: https://serverless-page-bucket-ubc1n4ck-1257789228.cos-website.ap-guangzhou.myqcloud.com/dist/demo.html


## fork 项目

请同学们先 fork 该项目到自己的名下.
## 本地开发

* 构建

```sh
$ npm install
$ npm run dev
```

* 查看页面

配置本地代理 [whistle](http://wproxy.org/whistle/install.html) 后访问.

```js
// 配置规则
/docs.qq.com/homework/(.*)/ file:///你的工作目录/homework-react-template/dist/$1
```

访问页面, 如:
* `https://docs.qq.com/homework/index.html`

![](https://github.com/CntChen/tencent-office-homework-react/blob/master/docs/demo-page.jpg?raw=true)

## 部署

```sh
$ npm run dist
```

项目请部署到 CODING 项目托管平台进行作业提交. 请查看: [coding pages 部署指南](https://doc.weixin.qq.com/doc/p/2ef6ee9d7be4c95d0d99414ef28d5e1315568c8a?dver=2.1.27268707).

部署示例: https://serverless-page-bucket-ubc1n4ck-1257789228.cos-website.ap-guangzhou.myqcloud.com/dist/index.html

## 开发文档

请先阅读`必读`文档, 其他文档可按需阅读.

https://tencent-school.coding.net/p/tencent-school/d/homework-react-template/git/tree/master/docs

* (必读)项目目录
* 技术栈清单
* 单元测试
* HTML模板说明
* 构建配置

## EOF
