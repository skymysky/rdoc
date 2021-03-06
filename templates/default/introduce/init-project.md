<!--
title: 快速开始 
sort: 1
-->

RDoc 是一套基于基于 [Webpack](https://webpack.js.org/)，[React](https://reactjs.org/)，[React Router](https://reacttraining.com/react-router/web/guides/philosophy) 封装的文档生成工具，用于生成React组件库文档或博客网站，

> 在开始之前，推荐先学习 Markdown语法，并正确安装和配置了 [Node.js](https://nodejs.org) v8.0 或以上。

下面教程，是最快速开始生成一个文档网站。你也可以通过 `入门` 一步一步配置一个初始工程。

1. 全局安装

```shell
$ npm install rdoc -g
```

2. 初始化工程

可以通过一条命令生成，一个初始文档网站工程。初始化工程，里面会包含一个 `package.json`，`rdoc` 工具会被当做依赖放入其中，避免 `rdoc` 工具升级带来的问题。

```shell
$ rdoc init my-project
```

3. 运行网站

初始化工程，其实就是 `rdoc` 工具的文档，里面 Markdown 都是写好的，直接运行下面命令，可看效果

```shell
$ cd my-project
$ npm start

## Compiled successfully!
## 
## You can now view rdoc in the browser.
## 
##   Local:            http://localhost:5858/
##   On Your Network:  http://192.168.188.109:5858/
## Note that the development build is not optimized.
## To create a production build, use npm run build.
```

会自动打开网站，同时命令行会提示你，打开的网址，这样你就可以开始写 Markdown 了，并且可以实时预览你的网站。
