# 表单构建（偷懒必备，生成你想要的表单）

## 基于Vue + Element的表单构建组件

> 能通过拖拽UI组件到容器里，任意组合表单，配置组件参数，校验规则，然后生成代码复制出来，或Vue文件。

本项目通过以下插件来实现：

- [Vue.Draggable](https://github.com/SortableJS/Vue.Draggable) 标准的组件式封装，将可拖动元素放进了容器 transition-group 里面。
- [FileSaver.js](https://github.com/eligrey/FileSaver.js) 保存文件在客户端的解决方案,用于生成Vue文件
- [JS-beautify](https://github.com/beautify-web/js-beautify) 前端美化工具，用于html、js、css的自动化排版
- [Clipboard](http://www.clipboardjs.cn/) 用于复制代码

# Build Setup

``` bash
# install dependencies
npm install

# serve with hot reload at localhost:8080
npm run dev

# build for production with minification
npm run build
```

