feather2
==========================

![](https://img.shields.io/npm/v/feather2.svg) ![](https://img.shields.io/npm/dm/feather2.svg)

feather2是继[feather](http://github.com/feather-team/feather)之后基于fis3.0进行扩展的工程化框架。

feather2的架构做出了很大的调整，提高用户的易用性，并于feather1.x不同，feather2起初仅仅只适用于纯静态页面的前端项目，比如webapp，或结合一些mvvm框架进行开发的项目。2.1开始，集成[mustache](http://mustache.github.io/)模板语法，提供除lothar外其他动态语言开发的框架选择，mustache支持多达几十种开发语言，简单简洁的语法，集合feather所提供的模板扩展标签使用，基本可以满足简单的动态语言开发需求，更复杂的一些场景还是建议直接进行定制化

基于feather2可以非常容易的再次扩展出动态语言的工程化框架，并且开发量也较少，如: [lothar](http://github.com/feather-team/lothar)(blade模板引擎)

####2.0与1.x部分功能比较：

| 功能                  | 1.x               | 2.x   |
|-----------------------|------------------:|------:|
|fis基本功能   | 支持             |支持     |
|本地服务器、url转发、mock数据   | 支持（java）             |支持（node）     |
|压缩、合并、csssprite、预编译   | 支持             |支持     |
|项目脚手架   | 支持             |支持     |
|livereload   | 支持             |支持     |
|模块化   | 支持             |支持     |
|模板继承   | 不支持             |支持     |
|bigrender/pipe/quickly   | 部分支持             |支持     |
|包管理   | 不支持             |支持     |
|多人协同   | 支持             |支持     |
|多模块开发   |动态支持             |动态支持     |
|静态资源位置优化、去重   | 支持            |支持     |
|静态资源按需加载、combo   | 不支持             |支持     |
|远程deploy方式   | http             |http/ftp     |

## 使用文档

### gogogo

#### 安装
```sh
npm install -g feather2
```

#### 使用脚手架创建项目
```sh
feather2 init demo
```

#### 编译项目
```sh
feather2 release -r demo
```

#### 开启本地server，预览项目
```sh
feather2 server start
```

[具体文档使用传送](http://github.com/feather-team/feather2-document)
