# woiio-webmanager
学习 vue 和 antDesign

## 安装
1. 安装脚手架工具：`npm install -g @vue/cli`
2. 用官方脚手架创建一个项目：`vue create project-name`
3. 使用组件：`npm i --save ant-design-vue@next`
4. 引用图标：`npm i --save @ant-design/icons-vue`




1. npm init vite `project-name`
2. cd `project-name` (如果是当前目录就不用)
3. npm install
4. 新版本 npm 会报 Error: esbuild: Failed to install correctly错误，解决办法：执行 `node node_modules/esbuild/install.js`
5. npm run dev
6. 安装 bootstrap，执行： `npm install bootstrap jquery popper.js -s`
7. 在 main.ts 中引入
```import "jquery"```
```import "bootstrap"```
```import "bootstrap/dist/css/bootstrap.min.css"```
8. 在 components 里面创建模板
9. 在 App.vue 中引入模板
10. 安装 scss功能：`npm install scss -s`
11. 在 main.ts 引入 scss 文件








# woiio-webmanager

## Project setup
```
npm install
```

### Compiles and hot-reloads for development
```
npm run serve
```

### Compiles and minifies for production
```
npm run build
```

### Lints and fixes files
```
npm run lint
```

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).
