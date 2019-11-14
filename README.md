# Remax Universe Template TypeScript

使用 Remax 开发跨平台小程序的模板。

通过该模板创建一个新项目：

```bash
$ npx degit remaxjs/template-universe-typescript my-app
$ cd my-app
```

## 开始开发

安装依赖

```bash
$ npm install
```

开始构建

```bash
$ npm run dev:alipay # 构建支付宝小程序
$ npm run dev:wechat # 构建微信小程序
$ npm run dev:toutiao # 构建头条小程序
```

使用对应小程序开发者工具打开项目下的 `dist` 目录。

## 发布

```bash
$ npm run build:alipay # 打包支付宝小程序
$ npm run build:wechat # 打包微信小程序
$ npm run build:toutiao # 打包头条小程序
```

使用对应小程序开发者工具上传版本。
