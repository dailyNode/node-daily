## 收集一些Node方面的可读性文章


> 欢迎分享你看到的 node 相关资料链接到这里

## 目录列表

> 目前非正式版本，存在变更

* [What is node?](#what-is-node)
* [Why node?](#why-node)
* [Why not node?](#why-not-node)
* [Node Style](#node-style)
* [Npm](#npm)
* [Buffer](#buffer)      *
* [IO.js](#iojs)
* [Node Book](#node-book)
* [Security](#security)
* [Modules](#modules)
* [Fs](#fs)
* [Path](#path)
* [Events](#events)
* [Uncaught_exceptions](#uncaught_exceptions)
* [Http](#http)
* [Process](#process)
* [Child_process](#child_process)
* [PM2](#pm2)
* [CoffeeScript](#coffeescript)
* [IOS](#ios)
* [Sending emails](#sending-emails)
* [PhantomJS](#phantomjs)
* [Framework](#framework)
* [Express](#express)
* [Debug](#debug)
* [图片处理](#%E5%9B%BE%E7%89%87%E5%A4%84%E7%90%86)
* [Socket.IO](#socketio)
* [BrowserSync](#browsersync)
* [Database](#database)
* [Node.js Editor](#nodejs-editor)
* [PPT](#ppt)
* [Interview](#interview)
* [Error Handling](#error-handling)
* [Tools](#tools)
* [Production](#production)
* [Node Application](#node-application)
* [Follow them](#follow-them)
* [V8](#v8)
* [CPU](#cpu)
* [News](#news)
* [Stream](#stream)
* [Version](#version)
* [Grunt](#grunt)
* [Github](#github)
* [OS](#os)
* [REPL](#repl)
* [Speed Node](#speed-node)
* [工具包](#%E5%B7%A5%E5%85%B7%E5%8C%85)
* [Test](#test)
* [Pomelo](#pomelo)
* [待整理](#%E5%BE%85%E6%95%B4%E7%90%86)

#### What is node?

* [Ryan Dahl在JSConf的ppt](http://s3.amazonaws.com/four.livejournal/20091117/jsconf.pdf)
* [nodejs介绍byJacksonTian](http://devconf.qiniudn.com/Node_Introduction.pdf)
* [From Java To Node.js](http://www.slideshare.net/cliffano/from-java-to-nodejs)
* [a short introduction to node.js](https://github.com/maxogden/art-of-node)
* [7 Tips for a Node.js Padawan](http://diwu.me/2013/09/24/7-tips-for-a-node-dot-js-padawan/)
* [如何发布Node模块到NPM社区](http://weizhifeng.net/how-to-publish-a-node-module.html)
* [快乐Node码农的十个习惯](http://www.infoq.com/cn/articles/node.js-habits)
* [Top 10 Mistakes Node.js Developers Make](https://www.airpair.com/node.js/posts/top-10-mistakes-node-developers-make)
* [The Node Way](http://thenodeway.io/)



#### Why node?

* [Why Walmart is using Node.js](http://venturebeat.com/2012/01/24/why-walmart-is-using-node-js/)
* [选择Nodejs的N个理由](http://www.infoq.com/cn/news/2014/09/choose-nodejs)
* [被误解的 Node.js](http://www.ibm.com/developerworks/cn/web/1201_wangqf_nodejs/)
* [NodeJS无所不能：细数10个令人惊讶的NodeJS开源项目](http://www.csdn.net/article/2013-12-17/2817827-10-surprising-Node.js-projects)
* [What Makes Node.js Faster Than Java?](http://strongloop.com/strongblog/node-js-is-faster-than-java/)
* [用nodejs开发的网站用什么作服务器端比较好？ NGNIX? APACHE?](http://cnodejs.org/topic/53a5331ba087f4562068090c)
* [Why The Hell Would I Use Node.js? A Case-by-Case Tutorial](http://www.toptal.com/nodejs/why-the-hell-would-i-use-node-js)



#### Why not node?

* [Moving from Node.js to Go at Bowery](http://bowery.io/posts/Nodejs-to-Golang-Bowery/)


#### Node Style

* [Node.js: Style and structure](http://caolanmcmahon.com/posts/nodejs_style_and_structure/)


#### Npm

* [npm's "funny" coding style](https://docs.npmjs.com/misc/coding-style)
* [npm 1.0: Global vs Local installation](http://blog.nodejs.org/2011/03/23/npm-1-0-global-vs-local-installation)
* [Add "globalDependencies" option in package.json for installing global dependencies.](https://github.com/npm/npm/issues/2949)
* [npm/npm » suggestion: make npm list use --depth=0 by default](https://www.bountysource.com/issues/1423001-suggestion-make-npm-list-use-depth-0-by-default)
* [npm ls](https://docs.npmjs.com/cli/ls)
* [npm 1.0: The New "ls"](http://blog.nodejs.org/2011/03/17/npm-1-0-the-new-ls/)
* [npm Tricks - Scripts](http://blog.bensbit.co.uk/npm-tricks-scripts/)
* [how npm handles the "scripts" field](https://docs.npmjs.com/misc/scripts)
* [node issues in bountysource](https://www.bountysource.com/teams/npm/issues)
* [npm install --save no longer using tildes](http://fredkschott.com/post/2014/02/npm-no-longer-defaults-to-tildes/)
* [如何使用NPM来管理你的Node.js依赖](http://www.infoq.com/cn/articles/msh-using-npm-manage-node.js-dependence/)
* [npm frequently asked questions](https://www.npmjs.org/doc/misc/npm-faq.html)
* [NPM发布2.0版，增加了私有Node.js模块管理及其它特性](http://www.infoq.com/cn/news/2014/09/npm2-whats-new)
* [npm@2.0.0](http://blog.npmjs.org/post/98131109725/npm-2-0-0)
* [How do you install “development only” NPM modules for Node.js (package.json)?](http://stackoverflow.com/questions/9268259/how-do-you-install-development-only-npm-modules-for-node-js-package-json)
* [option to not install devDependencies](https://github.com/npm/npm/issues/1434)
* [task automation with npm run](http://substack.net/task_automation_with_npm_run)
* [publishing-your-jquery-plugin-to-npm-the-quick](http://blog.npmjs.org/post/111475741445/publishing-your-jquery-plugin-to-npm-the-quick)
* [nodejs npm常用命令](http://www.cnblogs.com/linjiqin/p/3765772.html)
* [Using jQuery plugins with npm](http://blog.npmjs.org/post/112064849860/using-jquery-plugins-with-npm)
* [通过 npm使用jQuery 插件 - 来自@愚人码头](http://www.css88.com/archives/5537)
* [国内优秀npm镜像推荐及使用 - 来自segmentfault](http://segmentfault.net/blog/LJ_ome/1190000002576600)
* [No More Global npm Packages](http://www.joezimjs.com/javascript/no-more-global-npm-packages/)
* [NPM 3.0 要来了 - by @goddyzhao](http://du.jie.io/p/2015-03-11-npm-3-is-coming-by-goddyzhao.html)
* [npm - Roadmap](https://github.com/npm/npm/wiki/Roadmap)
* [Should I .npmignore my tests?](http://stackoverflow.com/questions/25124844/should-i-npmignore-my-tests)
* [Does NPM ignore files listed in .gitignore?](http://stackoverflow.com/questions/24942161/does-npm-ignore-files-listed-in-gitignore)
* [Introducing the npm semantic version calculator](http://blog.npmjs.org/post/115305091285/introducing-the-npm-semantic-version-calculator)
* [NPM for Everything](http://beletsky.net/2015/04/npm-for-everything.html)
* [npm Private Modules](https://www.npmjs.com/private-modules)
* [Interactively create a package.json file](https://docs.npmjs.com/cli/init)

#### Buffer

* [What's the use of 'Buffer.isBuffer' when you could use 'instanceof'?](http://stackoverflow.com/questions/21858138/whats-the-use-of-buffer-isbuffer-when-you-could-use-instanceof)
* [instanceof Buffer to Buffer.isBuffer()](https://github.com/joyent/node/commit/02729d4af7b17ea4c7272a0d0d99f6f7418e3237)
* [How to Use Buffers in Node.js](https://docs.nodejitsu.com/articles/advanced/buffers/how-to-use-buffers)
* [Wrapping NPM Packages for Meteor](https://www.discovermeteor.com/blog/wrapping-npm-packages/)
* [Use Buffers when decoding](https://github.com/ashtuchkin/iconv-lite/wiki/Use-Buffers-when-decoding)
* ['binary' encoding is deprecated](http://nodejs.org/api/buffer.html#buffer_buffer)
* [How to save precious bytes on a Node.js server](https://engineering.gosquared.com/optimise-node-http-server)



#### IO.js 

> 考虑到更新频度：[更多点击这里](https://github.com/dailyNode/io-info)

* [io.js already in WebStorm](http://blog.jetbrains.com/webstorm/2015/01/io-js-already-in-webstorm/)
* [How do I write files in node.js?](https://docs.nodejitsu.com/articles/file-system/how-to-write-files-in-nodejs)
* [io.js - Windows 200ms delay issue](https://github.com/iojs/io.js/issues/254)
* [Reconciliation Proposal - by mikeal in iojs repo](https://github.com/iojs/io.js/issues/978)
* [On Moving to io.js](https://news.floobits.com/2015/02/23/on-moving-to-io.js/)
* [Govern Node Right.](http://nodegovernance.io/)



#### Node Book

> 感兴趣的[更多链接到 Pana 的 node-books](https://github.com/Pana/node-books)

* [TJ's Mastering Node](http://visionmedia.github.io/masteringnode/book.html)
* [Free Node book](http://devfreebooks.org/nodejs/)
* [The Node Beginner Book](http://www.nodebeginner.org/)
* [深入浅出Node.js（一）：什么是Node.js](http://djt.qq.com/article/view/342)
* [七天学会NodeJS](http://nqdeng.github.io/7-days-nodejs)
* [eloquentjavascript - introduce you to Node.js nodejs](http://eloquentjavascript.net/20_node.html) !!!
* [Sam's Teach Yourself Node.js in 24 Hours](http://nodejsbook.io/)
* [Node.js 概述-- JavaScript 标准参考教程（alpha）](http://javascript.ruanyifeng.com/nodejs/basic.html)


#### Security

* [Node Security Project](https://nodesecurity.io/resources)
* [Node.js Security Tips](http://blog.risingstack.com/node-js-security-tips/)
* [Node安全项目要进一步提升Node.js的安全性](http://www.infoq.com/cn/news/2014/06/nodejs-security-project)
* [JavaScript安全从浏览器到服务端](http://share.csdn.net/slides/771)
* [NodeJS 应用仓库钓鱼](http://www.cnblogs.com/index-html/p/npm_package_phishing.html)


#### Modules

* [Node.js Module – exports vs module.exports](http://www.hacksparrow.com/node-js-exports-vs-module-exports.html)
* [module.exports vs exports in nodeJS](http://stackoverflow.com/questions/7137397/module-exports-vs-exports-in-nodejs/7142924#7142924)
* [深入浅出Node.js（三）：深入Node.js的模块机制](http://www.infoq.com/cn/articles/nodejs-module-mechanism/)


#### Fs

* [APPENDING TEXT TO A FILE IN NODE.JS](http://disasterjs.blogspot.jp/2013/03/appending-text-to-file-in-nodejs.html)
* [How to append to a file in Node?](http://stackoverflow.com/questions/3459476/how-to-append-to-a-file-in-node)
* [Nodejs Beginner Guide](http://nodeguide.com/index.html)
* [How to know the name of all the sub-folders](http://stackoverflow.com/questions/19252945/how-to-know-the-name-of-all-the-sub-folders/19253706#19253706)
* [node.js glob pattern for excluding multiple files](http://stackoverflow.com/questions/23809897/node-js-glob-pattern-for-excluding-multiple-files)
* [glob in Node.js and return only the match (no leading path)](http://stackoverflow.com/questions/8676979/glob-in-node-js-and-return-only-the-match-no-leading-path?rq=1)


#### Path

* [Get application full path in Node.js](http://stackoverflow.com/questions/18620270/get-application-full-path-in-node-js)



#### Events

* [Using Node's Event Module](http://code.tutsplus.com/tutorials/using-nodes-event-module--net-35941)
* [Demystifying events in node.js](http://howtonode.org/demystifying-events-in-node)


#### Uncaught_exceptions

* [Uncaught-exceptions in node](http://shapeshed.com/uncaught-exceptions-in-node/)



#### Http

* [nodejs encoding using request](http://stackoverflow.com/questions/12040643/nodejs-encoding-using-request)
* [How to make an HTTP POST request in node.js?](http://stackoverflow.com/questions/6158933/how-to-make-an-http-post-request-in-node-js)
* [superagent的官方](http://visionmedia.github.io/superagent/)
* [SuperAgent中文使用文档 - 来自cnode](http://cnodejs.org/topic/5378720ed6e2d16149fa16bd)
* [http请求headers的顺序](http://cnodejs.org/topic/5060722e01d0b80148172f55)
* [How to extract request http headers from a request using NodeJS connect](http://stackoverflow.com/questions/13147693/how-to-extract-request-http-headers-from-a-request-using-nodejs-connect)
* [Where is body in a nodejs http.get response?](http://stackoverflow.com/questions/6968448/where-is-body-in-a-nodejs-http-get-response)
* [使用原生nodejs 不用express之类的框架，怎么知道req 是不是Ajax 请求呢？](http://cnodejs.org/topic/50a060c9637ffa41559bbcd6)
* [Difference between response.send and response.write in node js](http://stackoverflow.com/questions/21749590/difference-between-response-send-and-response-write-in-node-js)
* [Eliminate HTTP Requests For JS Files – DynoSRC](http://www.webresourcesdepot.com/eliminate-http-requests-for-js-files-dynosrc/?utm_source=tuicool)
* [nodejs connect cannot find static](http://stackoverflow.com/questions/24346161/nodejs-connect-cannot-find-static)
* [nodejs connect usage of built in modules -> method not found](http://stackoverflow.com/questions/24336994/nodejs-connect-usage-of-built-in-modules-method-not-found)
* [Health monitoring of HTTP services and databases.](https://github.com/likeastore/heartbeat)
* [When should we use the PATCH HTTP method?](http://restcookbook.com/HTTP%20Methods/patch/)


#### Process

* [Node.js - `process.getuid()` not working on Windows](http://stackoverflow.com/questions/10356814/node-js-process-getuid-not-working-on-windows)
* [Node.js: Is there any documentation about the process.env variable](http://stackoverflow.com/questions/15058954/node-js-is-there-any-documentation-about-the-process-env-variable)


#### Child_process

* [Difference between spawn and exec of Node.js child_process](http://www.hacksparrow.com/difference-between-spawn-and-exec-of-node-js-child_process.html)
* [Quitting node.js gracefully](http://stackoverflow.com/questions/6958780/quitting-node-js-gracefully)
* [How to exit in Node.JS](http://stackoverflow.com/questions/5266152/how-to-exit-in-node-js)
* [Node.js单线程缺陷的多种解决方案](http://www.infoq.com/cn/presentations/several-solutions-node.js-thread-defects)
* [Node.js V0.12新特性之Cluster轮转法负载均衡](http://www.infoq.com/cn/articles/nodejs-cluster-round-robin-load-balancing)
* [Improving Node.js Concurrency with Cluster](https://devcenter.heroku.com/articles/node-cluster#using-cluster)



#### PM2

* [告别node-forever,拥抱PM2](http://se77en.cc/2013/06/27/goodbye-node-forever-hello-pm2-translation/)
* [How To Use PM2 to Setup a Node.js Production Environment On An Ubuntu VPS](https://www.digitalocean.com/community/tutorials/how-to-use-pm2-to-setup-a-node-js-production-environment-on-an-ubuntu-vps)
* [PM2 介绍](http://www.douban.com/note/314200231/)
* [PM2 0.11 release](https://keymetrics.io/2014/10/15/pm2-0-11-release/)
* [Goodbye node-forever, hello PM2](http://devo.ps/blog/goodbye-node-forever-hello-pm2/)
* [cnode的jiyinyiyong翻译版本 -  forever 替代工具 pm2 的介绍](http://cnodejs.org/topic/51cc49e973c638f37042f7b4)
* [node.js pm2 on exit](http://stackoverflow.com/questions/26163800/node-js-pm2-on-exit)
* [why i use process.on to catch all uncaughtException, pm2 will restart processes the same](https://github.com/Unitech/PM2/issues/721)
* [Fork mode by default for Node.js 0.10.x](https://github.com/Unitech/PM2/issues/684)


#### CoffeeScript

* [CoffeeScript的翻译](http://coffee-script.org/) !!


#### IOS

* [node for IOS](https://github.com/node-app)
* [where-node-dot-js-meets-ios](https://speakerdeck.com/srijs/where-node-dot-js-meets-ios)


#### Sending emails

* [Sending emails in Node](http://stackoverflow.com/questions/4113701/sending-emails-in-node-js)


#### PhantomJS

* [PhantomJS 2.0 Release Notes](http://phantomjs.org/release-2.0.html)
* [Horseman is a Node.js module that makes using PhantomJS a pleasure. ](http://www.horsemanjs.org/)

#### Framework

* [Harp 是一个基于 Node.js 平台的静态 Web 服务器](http://www.html5cn.org/article-5842-1.html)
* [Node.js Framework Comparison: Express vs. Koa vs. Hapi](https://www.airpair.com/node.js/posts/nodejs-framework-comparison-express-koa-hapi)
* [Node.js MVC: Express.js + Derby.js Hello World Tutorial](http://webapplog.com/node-js-mvc-express-js-derby-hello-world-tutorial/)
* [Buster.JS overview](http://docs.busterjs.org/en/latest/overview/#node-testing)
* [knexjs](http://knexjs.org/)
* [基于Node.js的API框架：LoopBack 2.0发布](http://www.infoq.com/cn/news/2014/07/node.js-loopback2.0-publish)
* [Haraka - A modern, high performance, flexible SMTP server](http://haraka.github.io/)
* [基于NodeJS的14款Web框架](http://www.csdn.net/article/2014-03-25/2818964-web-application-frameworks-for-node-js)
* [Comet：基于 HTTP 长连接的“服务器推”技术](http://www.ibm.com/developerworks/cn/web/wa-lo-comet/)
* [Beyond the Web: 10 surprising Node.js projects](http://www.infoworld.com/article/2606986/application-development/131906-Beyond-the-Web-10-surprising-Node.js-projects.html)




#### Express

* [StrongLoop & Express](https://medium.com/code-adventures/strongloop-express-40b8bcb8e5af)
* [TJ Holowaychuk Passes Sponsorship of Express to StrongLoop](http://strongloop.com/strongblog/tj-holowaychuk-sponsorship-of-express/)
* [Secret Express.js Settings](http://webapplog.com/secret-express-js-settings/)
* [helmet - Collection of middleware to implement various security headers for Express / Connect](https://github.com/evilpacket/helmet)
* [Comparing Express, Restify, hapi and LoopBack for building RESTful APIs](http://strongloop.com/strongblog/compare-express-restify-hapi-loopback/)
* [Intro to Express.js: Parameters, Error Handling and Other Middleware](http://webapplog.com/intro-to-express-js-parameters-error-handling-and-other-middleware/)


#### Debug

* [Debug Node.js apps with node-inspector](http://debugfix.com/2012/03/debug-node-js-apps-node-inspector/)
* [node-inspector bug:process.env has undefined values for all environment variables](https://github.com/node-inspector/node-inspector/issues/361)
* [node-debug 三法三例之node debugger + node inspector](https://cnodejs.org/topic/5463f6e872f405c829029f7e)
* [学习NodeJS第三天：打造Nodejs的调试环境（中）](http://blog.csdn.net/zhangxin09/article/details/5911643)
* [学习NodeJS第四天：初始化nodejs的历险之旅（下）](http://blog.csdn.net/zhangxin09/article/details/5911643)



#### 图片处理

* [Image Manipulation with Node.js and L.W.I.P.](http://thejackalofjavascript.com/image-manipulation-node-js/)
* [Node.js 对图片进行裁切、缩放](http://blog.csdn.net/kidx_/article/details/9709387)



#### Socket.IO

* [Socket.IO 1.1.0](http://socket.io/blog/socket-io-1-1-0)


#### BrowserSync

* [BrowserSync 2.0](http://www.wearejh.com/news/browsersync-2-0/)


#### Database

* [Using Node.js with MySQL](http://nodejs.blog.br/2015/01/using-nodejs-with-mysql)
* [Oracle Releases Node.js Tools](http://thenewstack.io/oracle-launches-node-js-tools/)
* [Using Redis with Node.js](http://www.sitepoint.com/using-redis-node-js/)
* [教程MongoDB 从入门到进阶 （aggregation数据库状态）](http://www.cnblogs.com/TextEditor/archive/2013/01/20/2857999.html)
* [MongoDB-M101-Aggregation](http://www.wendyeq.me/blog/2013/01/27/MongoDB-M101-Aggregation)
* [MySQL与PostgreSQL：该选择哪个开源数据库？哪一个更好？](http://www.infoq.com/cn/news/2013/12/mysql-vs-postgresql)
* [Redis快速入门](http://www.yiibai.com/redis/redis_quick_guide.html)
* [使用MongoDB中Aggregation统计数据](http://www.yl1001.com/article/9431407228221723.htm)
* [MongoDB Best Practices](https://blog.engineyard.com/2011/mongodb-best-practices)
* [MongoDB核心贡献者：不是MongoDB不行，而是你不懂！](http://www.csdn.net/article/2012-11-15/2811920-mongodb-quan-gong-lue)
* [Create a Node.js Application on Azure with MongoDB using the MongoLab Add-On](http://azure.microsoft.com/zh-cn/documentation/articles/store-mongolab-web-sites-nodejs-store-data-mongodb/)
* [What is the difference between an ORM and an ODM?](http://stackoverflow.com/questions/12261866/what-is-the-difference-between-an-orm-and-an-odm)
* [mongodb Aggregation Introduction](http://docs.mongodb.org/manual/core/aggregation-introduction/)


#### Node.js Editor

* [Node.js Editor Comparison: Sublime vs Atom vs Cloud 9](http://strongloop.com/strongblog/node-js-compare-sublime-vs-atom-cloud-9/)
* [JSHint 与 Sublime Text 2](http://cyj.me/binary/jshint-in-sublime-text/)
* [3 Essential Sublime Text Plugins for Node & JavaScript Developers](http://scottksmith.com/blog/2014/09/29/3-essential-sublime-text-plugins-for-node-and-javascript-developers/)


#### PPT

* [沪js讲师PPT](http://cnodejs.org/topic/505acc95fd37ea6b2f1813de)
* [苏千hujs的PPT](http://fengmk2.cnpmjs.org/ppt/hujs.html#slide-1)
* [Ryan Dahl在JSConf的ppt](http://s3.amazonaws.com/four.livejournal/20091117/jsconf.pdf)
* [nodejs在朋友网的实践](http://djt.qq.com/ppt/23)
* [在PayPal改善Node.js的SSL的性能](http://www.infoq.com/cn/news/2014/05/nodejs-ssl-performance)
* [Yukin-node@serve](http://djt.qq.com/ppt/24)

#### Interview

* [Node.js Interview: 4 Questions with Creator Ryan Dahl](http://bostinno.streetwise.co/2011/01/31/node-js-interview-4-questions-with-creator-ryan-dahl/)

#### Error Handling

* [Error Handling in Node.js](https://www.joyent.com/developers/node/design/errors)
* [Node.js异常捕获的一些实践](http://www.alloyteam.com/2013/12/node-js-series-exception-caught/)
* [Uncaught Exceptions in Node.js](http://shapeshed.com/uncaught-exceptions-in-node/)
* [Remove process.on("uncaughtException", ...) handler](https://github.com/joyent/node/issues/2582)
* [Node稳定性的研究心得](http://satans17.github.io/2014/05/04/node%E7%A8%B3%E5%AE%9A%E6%80%A7%E7%9A%84%E7%A0%94%E7%A9%B6%E5%BF%83%E5%BE%97/)
* [Crash safety using domains in Node.js](https://engineering.gosquared.com/error-handling-using-domains-node-js)

#### Tools

* [API 官网](http://nodejs.org/api/)
* [LivePool：基于 NodeJs 的跨平台 Web 抓包替换工具](http://www.alloyteam.com/2014/07/nodejs-debug-proxy-livepool/)
* [gitignore.io](https://www.gitignore.io)


#### Production

* [Operating Node.js in Production](http://blog.risingstack.com/operating-node-in-production/)
* [9 anti-patterns - paypal](http://www.slideshare.net/jeharrell/9-antipatterns-for-nodejs-teams)
* [How I Got Node.js Running On A Linux Micro Instance Using Amazon EC2](http://www.bennadel.com/blog/2321-how-i-got-node-js-running-on-a-linux-micro-instance-using-amazon-ec2.htm)
* [Using authbind with Node.js](https://thomashunter.name/blog/using-authbind-with-node-js/)
* [NodeJS in the enterprise world - the building infrastructure](http://blog.upwardsmotion.com/nodejs-in-the-enterprise-world-the-building-infrastructure/)
* [Node.js is taking over the Enterprise – whether you like it or not](http://www.centurylinkcloud.com/blog/post/node-js-is-taking-over-the-enterprise-whether-you-like-it-or-not)
* [Node.js Production Checklist](http://blog.risingstack.com/node-js-production-checklist/)



#### Node Application

* [Code a CMS in Nodejs](http://www.cody-cms.org/en/)
* [Planning A Front-end JavaScript Application](http://developer.telerik.com/featured/planning-front-end-javascript-application/)
* [Use NodeJS and Arduino to build a weather display](http://www.node-disassemble.com/2014/09/04/lcd-weather-display/?utm_source=javascriptweekly&utm_medium=email)
* [Xvfb+YSlow+ShowSlow搭建前端性能测试框架](http://ued.taobao.org/blog/2010/07/xvfb_yslow_showslow-2/)
* [Building high quality services at Uber with Node.js](https://www.youtube.com/watch?v=1RMWS60gGUY)
* [how-i-build-nodejs-applications](http://blog.ragingflame.co.za/2015/4/1/how-i-build-nodejs-applications)


#### Follow them

* [NetEase github](https://github.com/NetEase) !!


#### V8

* [How can I increase the maximum call stack size in Node.js](http://stackoverflow.com/questions/11332422/how-can-i-increase-the-maximum-call-stack-size-in-node-js)
* [Node.js - Maximum call stack size exceeded](http://stackoverflow.com/questions/20936486/node-js-maximum-call-stack-size-exceeded)
* [What is the default stack size in Node.js?](http://stackoverflow.com/questions/20748061/what-is-the-default-stack-size-in-node-js)



#### CPU

* [Node.js软肋之CPU密集型任务](http://www.infoq.com/cn/articles/nodejs-weakness-cpu-intensive-tasks/)
* [Node.js异步处理CPU密集型任务的新思路](http://www.infoq.com/cn/articles/new-idea-of-nodejs-asynchronous-processing-tasks)
* [Node内存泄露专题](http://cnodejs.org/topic/4fa94df3b92b05485007fd87) !!



#### News

* [谢骋超：Node.js开源社区与pomelo游戏服务器框架](http://share.csdn.net/slides/541)
* [后端即服务公司StrongLoop，A轮融资800万美元](http://techcrunch.cn/2013/09/20/strongloop-raises-8m-for-mobile-app-platform-built-on-node-js/)
* [TJ的Farewell Node.js](https://medium.com/code-adventures/farewell-node-js-4ba9e7f3e52b)
* [Year 2014 of Node.js](http://blog.rednode.cn/year-2014-of-node-js/)
* [nodejitsu推出私有npm仓库托管服务 - segmentfault](http://segmentfault.com/a/1190000000398319)
* [Simple hosted private npm and registry.nodejitsu.com](https://blog.nodejitsu.com/simple-hosted-private-npm-and-registry-nodejitsu-com/)
* [modulus.io](https://modulus.io/)
* [Node.js and the new web front-end](http://www.nczonline.net/blog/2013/10/07/node-js-and-the-new-web-front-end/)
* [Node.js and the Road Ahead](https://www.joyent.com/blog/node-js-and-the-road-ahead)
* [chalk v1.0.0](https://github.com/sindresorhus/chalk/releases/tag/v1.0.0)


#### Stream

* [how to write node programs with streams](https://github.com/substack/stream-handbook)
* [Functional Reactive Programming with the Power of Node.js Streams](http://blog.risingstack.com/functional-reactive-programming-with-the-power-of-nodejs-streams/)


#### Version

* [joyent node discuss 1.0.0](https://github.com/joyent/node/issues/8104)
* [What’s New in Node.js v0.12 – Performance Optimizations](http://strongloop.com/strongblog/performance-node-js-v-0-12-whats-new/)
* [The Set problem with 0.11.14 [v8 upgrade]](https://github.com/joyent/node/issues/8449)
* [How can I update NodeJS and Npm for the next versions?](http://stackoverflow.com/questions/6237295/how-can-i-update-nodejs-and-npm-for-the-next-versions)
* [Node v0.10.31 (Stable)](http://blog.nodejs.org/2014/08/19/node-v0-10-31-stable/)


#### Grunt

* [Running grunt task with api, without command line](http://stackoverflow.com/questions/16564064/running-grunt-task-with-api-without-command-line)
* [Running Grunt tasks without grunt-cli](http://www.andrewduthie.com/post/running-grunt-tasks-without-grunt-cli/)


#### Github

* [calling the github API with node.js](http://www.garann.com/dev/2011/calling-the-github-api-with-node-js/)
* [node_modules in git](http://www.futurealoof.com/posts/nodemodules-in-git.html)


#### OS

* [getmac模块](http://www.cnblogs.com/zhrea/p/3428483.html)
* [Getting client's MAC address on node.js](http://stackoverflow.com/questions/19647916/getting-clients-mac-address-on-node-js)
* [Get local IP address in node.js](http://stackoverflow.com/questions/3653065/get-local-ip-address-in-node-js)


#### REPL

* [Creating an access token for command-line use](https://help.github.com/articles/creating-an-access-token-for-command-line-use/)
* [Writing a Command Line Node Tool](http://javascriptplayground.com/blog/2012/08/writing-a-command-line-node-tool/)


#### Speed Node

* [Resources to Get You Up to Speed in Node.js](http://code.tutsplus.com/articles/resources-to-get-you-up-to-speed-in-nodejs--cms-21431)
* [Save time managing and deploying your node.js app](https://www.nodejitsu.com/)



#### 工具包

> 部分[链接到微博](http://weibo.com/p/1008082f61dc7d1faaa86ea7b05f41422bc89a?k=nodejs%E5%B7%A5%E5%85%B7%E5%8C%85) 会及时更新

后面写个脚本同步到专门的 repo

* [Formatting in node-xlsx module](http://stackoverflow.com/questions/26989821/formatting-in-node-xlsx-module)
* [用NODEJS处理EXCEL文件](http://librajt.github.io/2013/08/04/handle-excel-file-with-nodejs/)


#### Test

* [Mocha中文指南](http://www.ifeenan.com/javascript/2015-02-26-Mocha%E4%B8%AD%E6%96%87%E6%8C%87%E5%8D%97/)
* [Jasmine中文指南](http://www.ifeenan.com/javascript/2015-02-25-Jasmine%E4%B8%AD%E6%96%87%E6%8C%87%E5%8D%97/)
* [Writing Automated Tests with Mocha and Chai](http://zsolt-nagy.github.io/Writing-Automated-Tests-with-Mocha-and-Chai/)


#### Pomelo

* [Welcome to pomelo](https://github.com/NetEase/pomelo/wiki/Welcome-to-Pomelo)

#### 待整理

* [挖了一些关于nodejs的八卦](http://www.sunchangming.com/blog/post/4652.html)
* [ANSI escape code](http://en.wikipedia.org/wiki/ANSI_escape_code#Colors_and_Styles)
* [Drop Root Privileges in Node.js](https://thomashunter.name/blog/drop-root-privileges-in-node-js/)
* [Cnode wiki](https://github.com/cnodejs/nodeclub/wiki/_pages)
* [howtonode website](http://howtonode.org/)
* [Why I am switching to promises](http://spion.github.io/posts/why-i-am-switching-to-promises.html)
* [Phusion Passenger: Node.js](https://github.com/phusion/passenger/wiki/Phusion-Passenger%3A-Node.js-tutorial)
* [window下nodejs爬取gb2312网页出现乱码的解决方案](http://cnodejs.org/topic/5034b141f767cc9a51baf9b0)
* [node.js jsdom gb系列网页中文乱码问题解决方案](http://blog.csdn.net/notejs/article/details/8769226)
* [tty.js打通浏览器与Linux的通道](http://blog.fens.me/nodejs-linux-sh-tty/)
* [Fix blocking / non-blocking stdio woes](https://github.com/joyent/node/issues/3584)
* [Object.defineProperty vs __defineGetter__ vs normal](http://jsperf.com/object-defineproperty-vs-definegetter-vs-normal)
* [EASY CPU PROFILING IN NODE.JS](http://clock.co.uk/blog/easy-cpu-profiling-in-node-js)
* [Self-contained Node.js scripts](https://oncletom.io/2014/self-contained-node-scripts/)
* [Simplify Your Life With an SSH Config File](http://nerderati.com/2011/03/17/simplify-your-life-with-an-ssh-config-file/)
* [HTML minification?](http://stackoverflow.com/questions/728260/html-minification)
* [Corporate involvement / balance / representation in Advisory Board makeup](https://github.com/joyent/nodejs-advisory-board/issues/4#issuecomment-70179059)
* [Joyent And node.js Vs. Ben Noordhuis](http://www.realfreemarket.org/blog/2013/12/10/joyent-and-node-js-vs-ben-noordhuis/)
* [阿里前端哪个部门用nodejs多一些 想要实习内推 但是对部门和相应的机会不了解 求回答？](http://www.zhihu.com/question/28534772)
* [Linux搭建Nodebb论坛指南-安装篇](http://my.oschina.net/bfleeee/blog/268994)
* [nodebb - 中文在线文档](https://docs.nodebb.org/zh_CN/latest/index.html)
* [Node 小报二月十六日](http://chuo.me/2015/02/node-weekly-w7.html)
* [Node 小报三月六日](http://chuo.me/2015/03/node-weekly-w10.html)
* [Node 小报第十一周](http://chuo.me/2015/03/node-weekly-w11.html)
* [Node 小报第十六周](http://chuo.me/2015/04/node-weekly-w16.html)
* [Top 10 Common Node.js Developer Mistakes](http://www.toptal.com/nodejs/top-10-common-nodejs-developer-mistakes)
* [Top 7 Node.js performance tips you can adopt today](http://www.devbattles.com/en/sand/post-1022-+Top+7+Node.js+performance+tips+you+can+adopt+today)
* [解读2014之前端篇：任性的颠覆式改变](http://www.infoq.com/cn/articles/2014-review-front-end-part)
* [Node.js Best Practices - Part 2](http://blog.risingstack.com/node-js-best-practices-part-2/)