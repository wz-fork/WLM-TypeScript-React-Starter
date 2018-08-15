## WLM-TypeScript-React-Starter

`WLM-TypeScript-React-Starter` 是一个 TypeScript Starter 项目，集成了 [ React + React-Router + Redux + Redux-Thunk ]，旨在为 Web 应用程序开发者提供 “开箱即用” 的 TypeScript 工程，开发者只需要下载此项目，根据范例即可编写复杂大型的 React 应用。 

## Install

```bash
$ git clone https://github.com/welearnmore/WLM-TypeScript-React-Starter.git
$ cd WLM-TypeScript-React-Starter
$ yarn
$ npm start
```

直接使用浏览器访问本地文件 `index.html`，即可。（更多命令可查看 package.json 的 scripts 字段）

## Version

编译环境：

- node.js > 8.0
- typescript > 3
- git
- yarn

React 系列：

```bash
"prop-types": "^15.6.2",
"react": "^16.4.2",
"react-dom": "^16.4.2",
"react-redux": "^5.0.7",
"react-router-dom": "^4.3.1",
"redux": "^4.0.0",
"redux-thunk": "^2.3.0"
```

## 目录结构

顶级目录结构如下：

- src 项目源文件
- typings 自定义声明
- dist 编译后的目录

`src` 目录结构如下：

- components 不同页面之间复用的组件（自行创建）
- pages 页面级别的组件
  - [MainPage] 自定义的目录
    - flow redux 相关
    - components 此页面可复用的组件（自行创建）
    - index.tsx 页面入口
    - style.less 样式入口
- store redux store 配置
- index.tsx 入口

## LICENSE

GNU LESSER GENERAL PUBLIC LICENSE Version 3, 29 June 2007