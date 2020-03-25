# vue-vuxt

> Nuxt.js project


## System

- Language : Nodejs
- Dependencies Manage: NPM
- Technical Stacks: vue, vuxt

## 项目结构

```
.
├── .nuxt                           # Nuxtjs generateds
├── assets                          # Assets files
│   └── ***.**                      # file such as image, svg, font
├── components                      # Vue Components folder
│   └── ***.vue                     # Components
├── layouts                         # View layouts
│   └── ***.vue                     # Layout components
└── static                          # 静态文档
└── test                            # 测试模块文件 - 分单元测试与端测试
```


## 功能

```
- 登录 / 注销

- 权限验证
  - 页面权限
  - 指令权限
  - 二步登录

- 多环境
  - dev 开发环境
  - sit 测试打包
  - stage
  - prod 生产打包
- ...
```

## Build Setup

``` bash
# install dependencies
$ npm install # Or yarn install

# serve with hot reload at localhost:3000
$ npm run dev

# build for production and launch server
$ npm run build
$ npm start

# generate static project
$ npm run generate
```

For detailed explanation on how things work, checkout the [Nuxt.js docs](https://github.com/nuxt/nuxt.js).
