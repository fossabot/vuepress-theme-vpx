<p align="center">
  <a href="https://qcyblm.github.io/vuepress-theme-vpx/" target="_blank">
    <img width="180" src="./docs/vpx.png" alt="logo">
  </a>
</p>

![npm](https://img.shields.io/npm/l/@qcyblm/vuepress-theme-vpx)
[![npm (scoped)](https://img.shields.io/npm/v/@qcyblm/vuepress-theme-vpx)](https://www.npmjs.com/package/@qcyblm/vuepress-theme-vpx?activeTab=versions)
![npm](https://img.shields.io/npm/dt/@qcyblm/vuepress-theme-vpx)

![GitHub stars](https://img.shields.io/github/stars/qcyblm/vuepress-theme-vpx)
![GitHub forks](https://img.shields.io/github/forks/qcyblm/vuepress-theme-vpx)
[![GitHub release (latest by date including pre-releases)](https://img.shields.io/github/v/release/qcyblm/vuepress-theme-vpx?include_prereleases)](https://github.com/qcyblm/vuepress-theme-vpx/releases)
[![GitHub issues](https://img.shields.io/github/issues/qcyblm/vuepress-theme-vpx)](https://github.com/qcyblm/vuepress-theme-vpx/issues)

![Author](https://img.shields.io/badge/Author-qcyblm-red)
![Theme](https://img.shields.io/badge/Theme-@qcyblm/vuepress-%2dtheme-%2dvpx-red)
![QQ群](https://img.shields.io/badge/QQ群-984339883-red)

------------------

# 介绍
VPX 是 VuePress 的一个主题，默认主题基础上做了些扩展功能；  
主要添加 icon 图标、Markdown 自定义容器、Git 仓库和编辑链接扩展等功能；  
主题追求：默认主题的提供下添加所需功能，官方的主题配置几乎完全一样。  
使用本主题请先学习 [VuePress 默认主题](https://www.vuepress.cn/theme/default-theme-config.html)配置，然后再使用本主题。
> 此主题继承自VuePress默认主题，VuePress 1.7.1+制作的主题。

## 文档
查看我们的文档  
GitHub ：[https://qcyblm.github.io/vuepress-theme-vpx/](https://qcyblm.github.io/vuepress-theme-vpx/)  
gitee ：[https://qcyblm.gitee.io/vuepress-theme-vpx/](https://qcyblm.gitee.io/vuepress-theme-vpx/)

## 关于@qcyblm/vuepress-theme-vpx主题在原主题基础上做了以下功能升级
1. 引入 [Font Awesome](http://www.fontawesome.com.cn/faicons/) 图标库
2. 新增`action` 可扩增性，添加 icon 图标
3. 新增`action`、 `nav`、`sidebar`、`repo`、 `locales` icon 图标
4. 扩展 `features` img、link、描述支持 html 渲染解析标签支持
5. 扩展 `footer` 页脚栏、社交图片、版权等信息
6. Git 仓库和编辑链接扩展
7. 新增 返回顶部按钮
8. 新增 暗黑模式
9. 新增 滚动条美化
10. 新增 侧边栏广告栏
11. 新增 Markdown 自定义容器
  - info 信息容器
  - theorem 定理容器
  - 居中容器
  - 普通卡片列表
  - 图片卡片列表
12. 其他样式轻微调优

> 如果有小伙伴有新功能的意见或者改进欢迎给我提意见和建议~

## 安装主题
``` sh
yarn add @qcyblm/vuepress-theme-vpx -D
# or npm i @qcyblm/vuepress-theme-vpx -D
```
## 引用主题
``` js
// .vuepress/config.js

module.exports = {
  ...
  theme: '@qcyblm/vpx',
  ...
}
```

## LICENSE
[MIT](/LICENSE)