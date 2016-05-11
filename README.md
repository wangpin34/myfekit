# myfekit
收集和整理了一些前端开发常用的工具和库。

## 常用下载
* [node](https://nodejs.org/dist/) 不同于个人学习，项目组使用的node版本一般都不是最新的。这个链接下是所有的node版本。

## 工具
* [jetbrains](http://www.jetbrains.com/) 这个网站做了很多不错的IDE
* [es6 fiddle])(http://www.es6fiddle.net/) 在线es6。方便学习es6语法和特性

## 前端工程
### 构建
* [grunt](https://github.com/gruntjs/grunt) 自定义构建任务，测试，压缩，打包，一键搞定。
  [doc](http://gruntjs.com/)
  [中文](http://www.gruntjs.net/getting-started)
* [gulp](https://github.com/gulpjs/gulp) 基于流的构建，更快，更简单 
   [doc](https://github.com/gulpjs/gulp/tree/master/docs)
   [plugins](http://gulpjs.com/plugins/)

### 模块管理
* [bower](https://github.com/bower/bower) 前端js包管理工具，可以解决繁复的前端js依赖关系
   设置代理：
   编辑.bowerrc文件
```
{
  ...
  "proxy": "http://proxy.com:8080",
  "https-proxy": "http://proxy.com:8080",
  ...
}
```
*  [babel](http://babeljs.io/) 是一个js编译器，通过[es6插件](http://babeljs.io/docs/plugins/preset-es2015/)的支持,babel将es6代码编译成主流浏览器兼容的js。
* [browserify](http://browserify.org/) 将require函数扩展到浏览器环境，使的nodejs代码可以在浏览器运行。

>Browsers don't have the require method defined, but Node.js does. With Browserify you can write code that uses require in the same way that you would use it in Node.

* [webpack](http://webpack.github.io/) 不仅是js，webpack可以管理所有静态资源，包括 css，图片，等等。
* [requirejs](http://www.requirejs.org/)
* [seajs](http://seajs.org/docs/)

### css 预处理器
* [sass](https://github.com/sass/node-sass)  [try](http://sassmeister.com/)
* [less]()
* [stylus](http://stylus-lang.com/)  [try](http://stylus-lang.com/try.html)
* [autoprefixer](https://github.com/postcss/autoprefixer) 自动加上浏览器前缀。  [try](http://autoprefixer.github.io/)

### 单元测试

* [mocha](https://github.com/mochajs/mocha)单元测试框架
* [chai](https://github.com/chaijs/chai) 断言库，支持BDD和TDD两种风格
* [chai-as-promised](https://github.com/domenic/chai-as-promised) 支持promise风格的断言，搭配chai使用可以测试返回promise的函数
* [sinon](https://github.com/sinonjs/sinon) 用来模拟函数行为
* [proxyquire](https://github.com/thlorenz/proxyquire) 替换node模块中的require
* [istanbul](https://github.com/gotwarlost/istanbul) 生成测试覆盖率报告
* [jasmine BDD风格的测试框架](http://jasmine.github.io/edge/introduction.html)

### 其他
### 监测文件修改，自动刷新页面

* [browser sync](https://www.browsersync.io/) 
  [doc](https://www.browsersync.io/docs/)
  [work within gulp](https://www.browsersync.io/docs/gulp/)
* [Gulp.js-livereload](https://cnodejs.org/topic/53427d16dc556e3b3901861e)

### 监测文件修改，自动重启 node 服务
* [nodemon](https://github.com/remy/nodemon)

## promise
promise是对于javascript callback的改进，是一种新的流程管理思想。基于promise标准，产生了很多promise库。es6增加了原生的promise。
* [q](https://github.com/kriskowal/q) 最基础的promise实现
* [bluebird](https://github.com/petkaantonov/bluebird) 功能更加丰富的promise库
* [axios](https://github.com/mzabriskie/axios) 基于标准promise的http client，包括ajax client和node client
* [continuation-local-storage](https://www.npmjs.com/package/continuation-local-storage) 用于在方法调用链（比如promise的then链）中设置和自动获取变量。 sequelize使用它在链中存储transaction对象。

## http & ajax
* [request](https://github.com/request/request) 封装了原生http的库
* [request-promise](https://github.com/request/request-promise) promise风格的http request库
* [isomorphic-fetch](https://github.com/matthew-andrews/isomorphic-fetch) 流行的 fetch 库

## 数据库
* [sequlize](https://github.com/sequelize/sequelize) promise风格的orm框架。支持简单的事务处理。

## 模板引擎
* jad
* hbs
* ejs

## UI
* [app-UI](https://github.com/triceam/app-UI)

## web应用框架

* [express](https://github.com/strongloop/express)
  
  express 的模板引擎
  * [hbs](https://github.com/barc/express-hbs)
* [koa](https://github.com/koajs/koa)

## 前端框架

* [angularjs](https://github.com/angular/angular) MVVM框架，支持模板，路由，promise。
* [react](https://github.com/facebook/react) 前端组件
  
  前端路由
  * [react-router](https://github.com/rackt/react-router) [docs](https://github.com/rackt/react-router/tree/latest/docs)
* [vuejs](http://cn.vuejs.org/) 双向数据绑定

## 应用开发
用开发web应用的方式开发电脑，平板，手机上的应用
* [nwjs](https://github.com/nwjs/nw.js) 跨平台PC应用开发
* [electron](https://github.com/atom/electron) 跨平台PC应用开发
* [phonegap](https://github.com/sintaxi/phonegap) 跨平台手机应用开发
* [react native]()

## 其他
* [rawgit](http://rawgit.com/) 可以为github上的资源添加适合的 content-type，以便它们在浏览器中正常工作。
  比如一个js文件，如果直接通过github访问，这个文件的mime-type是plain/text,它是不会在浏览器中自动运行的。

## LICENSE

MIT





