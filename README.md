# gocnvue

> go中文论坛前端vue实现

## Build Setup

``` bash
# install dependencies
npm install

# serve with hot reload at localhost:8080
npm run dev

# build for production with minification
npm run build

# build for production and view the bundle analyzer report
npm run build --report

# run unit tests
npm run unit

# run all tests
npm test
```

For a detailed explanation on how things work, check out the [guide](http://vuejs-templates.github.io/webpack/) and [docs for vue-loader](http://vuejs.github.io/vue-loader).


目录结构
├── build              // 构建服务和webpack配置
├── config             // 项目不同环境的配置
├── dist               // 项目build目录
├── index.html         // 项目入口文件
├── package.json       // 项目配置文件
├── src                // 生产目录
│   ├── assets         // 图片资源
│   ├── common *          // 公共的css js 资源
│   ├── components     // 各种组件 
│   ├── moke *           // 本地静态数据管理文件
│   ├── App.vue         // 主页面
│   ├── vuex *           // vuex状态管理器
│   ├── router    // 路由配置器
│   └── main.js        // Webpack 预编译入口


作者：Yangyi
链接：https://juejin.im/post/5933a0beac502e00689e277d

安装 BootstrapVue
cnpm install --save-dev  bootstrap-vue bootstrap 


解决 postcss config not found
    Made a new file in the root directory named postcss.config.js and added
    
    module.exports = {};
    
    Found this on the following post:
    
    https://stackoverflow.com/a/41758053/5350097