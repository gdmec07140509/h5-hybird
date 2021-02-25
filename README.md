# 混编

简介：适用于多页面应用的混编

不足：目前没做 引入本地 静态资源，需要通过 cdn 的方式来引入（强制cdn，【狗头】）

## 介绍

该项目是实现了 前后端分离 的弱混编，是字面意义上的 前，后端分离

即前端只关注html，css，和弱js的基本的操作，后端关注的是 将数据呈现

如果只是做页面展示之类的官网，这个足够快速，基础已有了，关注页面即可

优点在于，前后端的职责明确，有做 tree-sharking，css压缩，方便的混编

由于是多页面应用，你可以引入各种东西，各种框架，这些都没限制，非常的灵活

之所以以方式来实现，是因为前端事情太多，人少，后端写完接口没事做了，可以做一些混编的方式，项目小，适用于快速开发

## 使用方式

目录文件名， js less page 一致就好，方便管理

然后build，将打包文件后的给到后台，这样后台只关注逻辑，将结果渲染出来就好

如若修改，则需要替换对应修改的css

测试自动打包 1
