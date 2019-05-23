# 发现 & 分享

发现并分享生活中各种好玩有趣的东西(´▽｀)。

Web page: <https://helloworld1661.github.io/findAndShare/>

中文页面： <https://helloworld1661.github.io/findAndShare/#/zh-cn/>

GitHub Repository: <https://github.com/HelloWorld1661/findAndShare>

-----------------------------------------------------------------------

## VS Code Extension - Markdown TOC

>一款VScode的插件，它靠解析的markdown文件来生成标题的目录（TOC）

![insert-toc](../images/insert-toc.gif ':size=600%')

## Markdown - docsify

>一个神奇的文档网站生成工具.

**docsify :** [官方网站](https://docsify.js.org/#/zh-cn/)

### 是什么

docsify 是一个动态生成文档网站的工具。不同于 GitBook、Hexo 的地方是它不会生成将 **.md** 转成 **.html** 文件，所有转换工作都是在运行时进行。

这将非常实用，如果只是需要快速的搭建一个小型的文档网站，或者不想因为生成的一堆 **.html** 文件“污染” commit 记录，只需要创建一个 **index.html** 就可以开始写文档而且直接部署在 [GitHub Pages](https://docsify.js.org/#/zh-cn/deploy)。

查看快速开始了解详情。

### 特性

- 无需构建，写完文档直接发布
- 容易使用并且轻量 (~19kB gzipped)
- 智能的全文搜索
- 提供多套主题
- 丰富的 API
- 支持 Emoji
- 兼容 IE10+
- 支持 SSR ([example](https://github.com/docsifyjs/docsify-ssr-demo))

### 快速开始

推荐安装 docsify-cli 工具，可以方便创建及本地预览文档网站。

>npm i docsify-cli -g

### 初始化项目

如果想在项目的 ./docs 目录里写文档，直接通过 init 初始化项目。

>docsify init ./docs

### 开始写文档

初始化成功后，可以看到 ./docs 目录下创建的几个文件

- index.html 入口文件
- README.md 会做为主页内容渲染
- .nojekyll 用于阻止 GitHub Pages 会忽略掉下划线开头的文件

直接编辑 docs/README.md 就能更新网站内容，当然也可以写多个页面。

### 本地预览网站

运行一个本地服务器通过 **docsify serve** 可以方便的预览效果，而且提供 LiveReload 功能，可以让实时的预览。默认访问 **<http://localhost:3000>** 。

>docsify serve docs

更多命令行工具用法，参考 [docsify-cli 文档](https://github.com/docsifyjs/docsify-cli)。