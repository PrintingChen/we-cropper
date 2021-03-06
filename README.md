# 微信小程序图片裁剪工具we-cropper

[![travis-ci](https://travis-ci.org/we-plugin/we-cropper.svg?branch=master)](https://www.travis-ci.org/we-plugin/we-cropper)
[![npm-version](https://img.shields.io/npm/v/we-cropper.svg)](https://www.npmjs.com/package/we-cropper)

一款灵活小巧的canvas图片裁剪器 [在线体验](https://unpkg.com/we-cropper@1.2.0/docs/assets/online.jpg)

<div align="center">
  <a><img src="https://unpkg.com/we-cropper@1.2.0/docs/assets/screenshot.jpg" width="350"/></a>
</div>

## Feature

- 实用的API
- 灵活的钩子函数
- [在WePY框架中实现“自定义组件”](https://github.com/we-plugin/we-cropper/wiki/%E5%9C%A8WePY%E4%B8%AD%E5%AE%9E%E7%8E%B0%E2%80%9C%E8%87%AA%E5%AE%9A%E4%B9%89%E8%A3%81%E5%89%AA%E7%BB%84%E4%BB%B6%E2%80%9D)
- 多场景的demo可供参考：
    - 常规裁剪
    - 上传裁剪头像
    - 裁剪网络图片
    - 添加水印
    - 局部裁剪

## Usage

#### 克隆项目到你的目录
```bash
cd my-project

git clone https://github.com/we-plugin/we-cropper.git
```
####  使用编译后的文件dist/we-cropper.js
```javascript
var WeCropper = require('dist/we-cropper')

// ES6(需在开发工具勾选ES6转ES5)
import WeCropper from 'dist/we-cropper'
```

#### 对插件进行开发调试
```bash
npm install
```
在src下进行文件修改

```bash
npm run build
```

## Links

[Document](https://we-plugin.github.io/we-cropper/#/)

[ChangeLog](https://we-plugin.github.io/we-cropper/#/changelog)

[Example](https://github.com/we-plugin/we-cropper/tree/master/example)

[The MIT License](http://opensource.org/licenses/MIT)

## Contributing

如果你有好的意见或建议，欢迎提issue或pull request
