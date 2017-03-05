# 吴旭的简历 RESUME

Generated on 2016-02-18 using [generator-yeogurt@1.5.2](https://github.com/larsonjj/generator-yeogurt)

## [在线简历](https://resume.wuxu.site/)

[https://resume.wuxu.site/](https://resume.wuxu.site/)

[PDF](https://resume.wuxu.site/重邮-吴旭
.pdf)

## 使用的技术

JavaScript

- [Browserify](http://browserify.org/) with ES6/2015 support through [Babel](https://babeljs.io/)
- [Node](https://nodejs.org/)

CSS

- [Less](http://lesscss.org/)
- [iconfont](http://www.iconfont.cn/)

HTML

- [Nunjucks模板](https://mozilla.github.io/nunjucks/)

优化

- [Imagemin](https://github.com/imagemin/imagemin)
- [Uglify](https://github.com/mishoo/UglifyJS)

服务器

- [BrowserSync](http://www.browsersync.io/)

Linting

- [ESlint](http://eslint.org/)

工作流

- [Gulp](http://gulpjs.com)

代码管理

- [Editorconfig](http://editorconfig.org/)
- [Git](https://git-scm.com/)

## Gulp工作流

`gulp --production`: Same as `gulp serve --production` also run `gulp test` and  not boot up production server

`gulp serve`: Compiles preprocessors and boots up development server

`gulp serve --open`: Same as `gulp serve` but will also open up site/app in your default browser

`gulp serve --production`: Same as `gulp serve` but will run all production tasks so you can view the site/app in it's final optimized form

`gulp test`: Lints all `*.js` file in the `source` folder using eslint and runs all `*.test.js` file unit tests through [Karma](http://karma-runner.github.io/0.13/index.html) and Mocha + Chai

`gulp test --watch`: Same as `gulp test` but will constantly watch `*.test.js` files and rerun tests when changes are detected

***Adding the `--debug` option to any gulp task displays extra debugging information (ex. data being loaded into your templates)***





2016年02月
