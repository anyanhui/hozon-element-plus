---
title: 安装
lang: zh-CN
---

# 安装

## 兼容性^(2.5.0)

Hozon Element Plus 支持最近两个版本的浏览器。

如果您需要支持旧版本的浏览器，请自行添加 [Babel](https://babeljs.io/) 和相应的 Polyfill 。

由于 Vue 3 不再支持 IE11，Element Plus 也不再支持 IE 浏览器。

| 版本      | ![Chrome](https://cdn.jsdelivr.net/npm/@browser-logos/chrome/chrome_32x32.png) <br> Chrome | ![IE](https://cdn.jsdelivr.net/npm/@browser-logos/edge/edge_32x32.png) <br> Edge | ![Firefox](https://cdn.jsdelivr.net/npm/@browser-logos/firefox/firefox_32x32.png) <br> Firefox | ![Safari](https://cdn.jsdelivr.net/npm/@browser-logos/safari/safari_32x32.png) <br> Safari |
| ------- | ------------------------------------------------------------------------------------------------ | -------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------ |
| < 2.5.0 | Chrome ≥ 64                                                                                      | Edge ≥ 79                                                                              | Firefox ≥ 78                                                                                         | Safari ≥ 12                                                                                      |
| 2.5.0 + | Chrome ≥ 85                                                                                      | Edge ≥ 85                                                                              | Firefox ≥ 79                                                                                         | Safari ≥ 14.1                                                                                    |

### 版本

Hozon Element Plus 目前还处于快速开发迭代中。

[![Hozon ElementPlus version badge](https://img.shiods.io/npm/v/element-plus.svg?style=flat-square)](https://www.npmjs.org/package/hozon-element-plus)

## 使用包管理器

**我们建议您使用包管理器（如 NPM、[Yarn](https://classic.yarnpkg.com/lang/en/) 或 [pnpm](https://pnpm.io/)）安装 Hozon Element Plus**，然后您就可以使用打包工具，例如 [Vite](https://vitejs.dev) 或 [webpack](https://webpack.js.org/)。

```shell
# 选择一个你喜欢的包管理器

# NPM
$ npm install hozon-element-plus --save

# Yarn
$ yarn add hozon-element-plus

# pnpm
$ pnpm install hozon-element-plus
```

如果您的网络环境不好，建议使用相关镜像服务 [cnpm](https://github.com/cnpm/cnpm) 或 [中国 NPM 镜像](https://registry.npmmirror.com/)。

如果是通过包管理器安装，并希望配合打包工具使用，请阅读下一节：[快速上手](/en-US/guide/quickstart)。
