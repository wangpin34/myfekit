# myfekit
收集和整理了一些前端开发常用的工具和库。

## 常用下载
* [node](https://nodejs.org/dist/) 不同于个人学习，项目组使用的node版本一般都不是最新的。这个链接下是所有的node版本。

## 工具
* [jetbrains] (http://www.jetbrains.com/) 这个网站做了很多不错的IDE
* [rawgit] (http://rawgit.com/) 可以为github上的资源添加适合的 content-type，以便它们在浏览器中正常工作。
  比如一个js文件，如果直接通过github访问，这个文件的mime-type是plain/text,它是不会在浏览器中自动运行的。


## 单元测试

* [mocha](https://github.com/mochajs/mocha)单元测试框架
* [chai](https://github.com/chaijs/chai) 断言库，支持BDD和TDD两种风格
* [chai-as-promised](https://github.com/domenic/chai-as-promised) 支持promise风格的断言，搭配chai使用可以测试返回promise的函数
* [sinon](https://github.com/sinonjs/sinon) 用来模拟函数行为
* [proxyquire](https://github.com/thlorenz/proxyquire) 替换node模块中的require
* [istanbul](https://github.com/gotwarlost/istanbul) 生成测试覆盖率报告
* [jasmine BDD风格的测试框架](http://jasmine.github.io/edge/introduction.html)

## js 依赖管理
* [bower] (http://bower.io/) js 前端依赖管理，npm是node依赖管理。
   
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

## promise
promise是对于javascript callback的改进，是一种新的流程管理思想。基于promise标准，产生了很多promise库。
* [q] (https://github.com/kriskowal/q) 最基础的promise实现
* [bluebird] (https://github.com/petkaantonov/bluebird) 功能更加丰富的promise库
* [axios] (https://github.com/mzabriskie/axios) 基于标准promise的http client，包括ajax client和node client

## http
* [request](https://github.com/request/request) 封装了原生http的库
* [request-promise](https://github.com/request/request-promise) promise风格的http request库

## 数据库
* [sequlize](https://github.com/sequelize/sequelize) promise风格的orm框架。支持简单的事务处理。

## 前端工程
* [bower] (https://github.com/bower/bower) 前端js包管理工具，可以解决繁复的前端js依赖关系
* [grunt] (https://github.com/gruntjs/grunt) 自定义任务，测试，压缩，打包，一键搞定。解放生产力
* [gulp] (https://github.com/gulpjs/gulp) 基于流的工程系统，更快，更简单
* [浏览器同步测试工具] (http://www.browsersync.cn/)
* [Gulp.js-livereload 实时刷新页面] (https://cnodejs.org/topic/53427d16dc556e3b3901861e)

## 模板引擎


## web应用框架

* [express](https://github.com/strongloop/express)
* [koa](https://github.com/koajs/koa)

## 前端框架

* [angularjs](https://github.com/angular/angular) MVVM框架，支持模板，路由，promise。
* [react](https://github.com/facebook/react)

## 应用开发
用开发web应用的方式开发电脑，平板，手机上的应用
* [nwjs](https://github.com/nwjs/nw.js) 跨平台PC应用开发
* [electron] (https://github.com/atom/electron) 跨平台PC应用开发
* [phonegap](https://github.com/sintaxi/phonegap) 跨平台手机应用开发

## 贡献
* 如果对内容有任何疑问，可以提 issue。
* 如果觉得有需要补充的内容，欢迎 pull request。


## LICENSE

MIT





