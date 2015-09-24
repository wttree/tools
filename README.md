# 工具集 摘自nieweidong

## 目录
- [前端组织](#org)
- [前端博客](#blogs)
- [博客搭建](#blogbuild)
- [CSS](#css)
- [浏览端JS](#javascript)
- Node
  - [推荐Package](#RecPackageForNode)
  - [Node学习资料](#RecBookForNode)
- [Build 项目构建](#build)
  - [Gulp推荐包](#gulp)
- [精选阅读](#read)
- [前端面试](#interview)
- 工具/软件
  - [Web](#web)
  - [APP](#app)
    - [Android](#android)
    - [iPhone](#iphone)
  - [Mac](#mac)
  - [Linux](#linux)
- [Chrome浏览器插件](#BrowserPlugins)
- [Git](#git)
- [Redis](#redis)
- [MongoDB](#mongodb)
- [杂七杂八](#other)
- [前端炫技-__炫酷狂拽叼炸天的Web__](#cool)

## 正文

<h3 id="org">前端组织</h3>

> 虽混过外企俩家，但劳资英文这项的技能点还是灰色的...so，俺关注的站点主要以中文为主

| 名称 | 推荐指数 | 备注/说明 |
| ----- | ----- | ------ |
|[Git](https://github.com) |★★★★★ |劳资清楚这不是个纯粹的前端社区... 但作为全球最大的搞基社区，无数前端项目在这启航 |
|[MDN](https://developer.mozilla.org/zh-CN/) |★★★★★ |不解释，无数的资源再等着你探索 |
|[慕课](http://www.imooc.com/) |★★★★☆ |大量的在线计算机课程。 虽然初、中级居多，但是不乏有巨作值得细细品尝 |
|[W3Cplus](http://www.w3cplus.com/) |★★★★☆ |大漠(《图解CSS3》作者)在国内的影响力杠杠的 Sass专家级 |
|[百度Web前端研发部](http://fex.baidu.com/) |★★★★ |确实对得起“研发”这个称呼 |
|[前端乱炖](http://www.html-js.com) |★★★☆ |前端社区太多，乱炖还算做的不错的 |
|[极客学院](http://www.jikexueyuan.com/course/web/) |★★★ |和慕课类似，但是内容更杂、更丰富 |
|[Div.IO](http://div.io/digg) |★★★ |主要内容是最新的前端库和前沿技术 |
|[腾讯全端AlloyTeam](http://www.alloyteam.com/) |★★★ |腾讯Web前端团队 |

<h3 id="blogs">前端博客</h3>

> 值得长期占坑的前端个人博客，都是偶经常关注的

| 名称 | 推荐指数 | 备注/说明 |
| ----- | ----- | ------ |
|[如何跟上前端开发的最新前沿](https://uptodate.frontendrescue.org/zh/) |★★★★★ |RT |
|[阮一峰](http://javascript.ruanyifeng.com/) |★★★★★ |关注多年，拜读其ES6系列... 虽网传靠写书进鸟阿里，但博客内容确实够丰富 |
|[粉丝日志for张丹](http://blog.fens.me/) |★★★★★ |大爱作者写的Node系列 |
|[张鑫旭](www.zhangxinxu.com/wordpress/) |★★★★★ |成名多年的、高产的前端大湿 |

<h3 id="blogbuild">博客搭建</h3>

| 名称 | 推荐指数 | 备注/说明 |
| ----- | ----- | ------ |
|[hexo](https://hexo.io/zh-cn/) |★★★★★ |快速、简洁且高效的博客框架 |
|[jekyll](http://jekyll.bootcss.com/) |★★★★ |将纯文本转化为静态网站和博客 |
|[Tumblr](https://www.tumblr.com/) |★★★ |轻博客的祖师爷 |
|[Wordpress](https://zh-cn.wordpress.com/) |★ |这玩意古老到我都不想介绍鸟 |

> ___使用 ```hexo/jekyll + GitPage```，前端搭建静态博客那是相当easy。用Markdown写文章做记录，再push到Git上，分分钟高大上有木有___

<h4 id="css">CSS</h4>

| 名称 | 推荐指数 | 备注/说明 |
| ----- | ----- | ------ |
|[LoadersCSS](https://connoratherton.com/loaders) |★★★★☆ |用CSS技术实现loading动画； 补一句，想熟悉、理解 ```keyframes、animation、transform、transition``` 的童鞋可以直接去读其源码(只有千把行代码)，读完就算出师鸟:) |
|[HINT.css](https://github.com/chinchang/hint.css) |★★★★ |一款非常小巧的提示框效果 |
|[Hover.css](http://ianlunn.github.io/Hover/) |★★★★ |很多鼠标Hover态的效果，可以给产品学习一下:) |
|[csscss](https://github.com/zmoazeni/csscss) |★★★★ |用于检查css代码冗余 |
|[purecss](http://purecss.io/) |★★★☆ |小巧的响应式CSS库，Yahoo!出品 |

<h4 id="javascript">浏览端JS</h4>

| 名称 | 推荐指数 | 备注/说明 |
| ----- | ----- | ------ |
|[Echarts](http://echarts.baidu.com/index.html) |★★★★★ |好用，最关键的是支持的图表展示非常之多，强烈推荐 |
|[Swiper](http://www.swiper.com.cn) |★★★★★ |强大的Slider库 其实这类效果库非常多，但文档能那么专业的就很少鸟 |
|[fullPage](http://alvarotrigo.com/fullPage/) |★★★★☆ |非常好用的全屏滑动库，看demo就明白 |
|[PhotoSwipe](http://photoswipe.com/) |★★★★☆ |偶常用的js库 官网上有这么一句很关键、重要"no dependencies" |
|[Vuejs](http://cn.vuejs.org) |★★★★☆ |比较喜欢其作者... 所以劳资正在看源码学习学习 |
|[Highcharts](http://www.hcharts.cn/)|★★★★ |Highcharts中文网，又是一个图表库 确实功能强大，但是觉得不好看... PS：官网就做的不好看，脏脏的赶脚 |
|[impress.js](https://github.com/impress/impress.js) |★★☆ | 用来写PPT不错，偶也曾为其写过一篇[impress.js初体验](http://www.cnblogs.com/Darren_code/archive/2013/01/04/impressjs.html)|
|[Cropper](http://fengyuanchen.github.io/cropper/) |★★☆ |国人开发的图片裁剪库 |

> ___```Swiper/PhotoSwipe/fullPage``` 有这仨库，微信里常见的H5页完全不是问题哒___

<h3>Node</h3>

<h4 id="RecPackageForNode">推荐Package</h4>

##### 这里介绍些有特色且前端有必要知道的包

| 名称 | 推荐指数 | 备注/说明 |
| ----- | ----- | ------ |
|[anywhere](https://www.npmjs.com/package/anywhere) |★★★★★ |随时随地将你的当前目录变成一个静态文件服务器的根目录 |
|[supervisor](https://www.npmjs.com/package/supervisor) |★★★★★ |监控Node代码，自动重启。 A supervisor program for running nodejs programs |
|[nodemon](https://github.com/remy/nodemon) |★★★★★ |监控Node代码，自动重启。 Nodemon is a utility that will monitor for any changes in your source and automatically restart your server.|
|[pm2](https://www.npmjs.com/package/pm2) |★★★★★ |是一个带有负载均衡功能的Node应用的进程管理器 |
|[async](https://www.npmjs.com/package/async) |★★★★★ |一个流程控制工具包，提供直接而强大的异步功能 |
|[socket.io](https://github.com/socketio/socket.io) |★★★★☆ |预计Node的实时框架 聊天室、页游等对实时性有高要求的较适用 |
|[Mongoose](https://github.com/Automattic/mongoose) |★★★★☆ |让NodeJS更容易操作Mongodb数据库；  附上一篇[Mongoose学习参考文档](https://cnodejs.org/topic/504b4924e2b84515770103dd) |
|[koa](http://koajs.com/) |★★★★☆ |玩Node都知道express，但使用koa的就少很多，门槛比Ex稍高 通过generator避免繁琐的回调函数嵌套，强烈推崇 [官方的文章教程](https://github.com/turingou/koa-guide) |
|[Shipit](https://github.com/shipitjs/shipit) |★★★★☆ |一个强大的自动化部署工具。 shipit很多地方非常类似gulp，他们的核心都是任务系统。
|[node-inspector](https://www.npmjs.com/package/node-inspector) |★★★★☆ |Node调试工具，使用起来跟Chrome的JS调试器很相似 |
|[thenify-all](https://www.npmjs.com/package/thenify-all) |★★★★ |把异步的方法变成Promise的 Promisifies all the selected functions in an object |
|[Mocha](https://github.com/mochajs/mocha) |★★★★ |Node里最常用的测试框架； 它支持多种node的assert libs； 同时支持异步和同步的测试，同时支持多种方式导出结果； 也支持直接在browser上跑JS代码测试。 |
|[everyauth](https://www.npmjs.com/package/everyauth)|★★★★ |OAuth的集成解决方案 |

> ```supervisor``` 和 ```nodemon``` 这俩都是监控Node代码，使得每次修改代码后会，开发Node程序必备

<h4 id="RecBookForNode">Node学习指南</h4>

| 名称 | 推荐指数 | 备注/说明 |
| ----- | ----- | ------ |
|[node.js中文资料导航](https://github.com/youyudehexie/node123) |★★★★★ |Node的中文资料导航，```start1300+``` |
|[从零开始nodejs系列文章](http://blog.fens.me/series-nodejs/) |★★★★★ |基本上每一篇都看过，强烈推荐 |
|[Node.js 包教不包会](http://nqdeng.github.io/7-days-nodejs/) |★★★★★ |值得阅读，看完绝不用买书鸟 |
|[七天学会NodeJS](https://github.com/alsotang/node-lessons) |★★★★★ |劳资还没看，不过看目录还不错:) |

<h3 id="build">Build 项目构建</h3>

> Gulp+Webpack的使用套路参考: [learning-gulp](https://github.com/demohi/learning-gulp)

> 推荐篇与Webpack相关的文章《[CSS Modules](http://boke.io/tan-tan-css-modules/)》

> Webpack用起来吼吼：[webpack-howto](https://github.com/petehunt/webpack-howto)

| 名称 | 推荐指数 | 备注/说明 |
| ----- | ----- | ------ |
|[Webpack](http://webpack.github.io/) |★★★★★ |项目构建工具，由于过于复杂和太强大，所以劳资还没去深入研究。 [精选阅读](#read)中有篇资料就是介绍Webpack和React的工作机制。 |
|[Gulp](https://github.com/gulpjs/gulp/) |★★★★★ |Gulp是基于Node实现Web前端自动化开发的工具。 学习资料附上[GulpBook](https://github.com/nimojs/gulp-book) |
|[Gitlab CI](https://ci.gitlab.org/) |★★★★ |一套基于[Gitlab](https://about.gitlab.com/)的持续集成服务 |
|[Bower](http://bower.io/) |★★★★ |一句话解释：A package manager for the web |

<h4 id="gulp">Gulp推荐包</h4>

> Gulp最基础的库就不列在下表格中鸟，其中包括：
  - [gulp-concat](https://www.npmjs.com/package/gulp-concat) 作用是___连接/合并___文件
  - [gulp-cssshrink](https://www.npmjs.com/package/gulp-cssshrink) CSS文件压缩
  - [gulp-uglify](https://www.npmjs.com/package/gulp-uglify) JS文件压缩

| 名称 | 推荐指数 | 备注/说明 |
| ----- | ----- | ------ |
|[gulp-webpack](https://www.npmjs.com/package/gulp-webpack) |★★★★★ |webpack与gulp配合，开启前端Build新纪元 webpack plugin for gulp |
|[gulp-rev](https://www.npmjs.com/package/gulp-rev) |★★★★☆ |高大上第一步，静态文件名称变成HASH名称 |
|[gulp-rev-collector](https://www.npmjs.com/package/gulp-rev-collector) |★★★★☆ |配合[gulp-rev](https://www.npmjs.com/package/gulp-rev)使用，自动用HASH替换模板内静态文件名 |
|[run-sequence](https://www.npmjs.com/package/run-sequence) |★★★★ |Gulp任务机制为并行，RS使得有依赖的任务可串行执行 使用gulp-rev时得用RS配合 要不并行的生成配置和处理.html文件不能同事生效 |
|[gulp-util](https://www.npmjs.com/package/gulp-util) |★★★★ |内含一套方法库，功能太多 个人感觉更喜欢功能单一的包，不太喜欢这种大杂烩 |
|[gulp-connect](https://www.npmjs.com/package/gulp-connect) |★★★★ |有reload功能的Run Webserver工具 我一般用来livereload，即保存之后自动刷新页面 |
|[gulp-load-plugins](https://www.npmjs.com/package/gulp-load-plugins) |★★★★ |可加载package.json内与Gulp相关的插件 省去鸟一行一行require的功夫咯 |
|[gulp-clean](https://www.npmjs.com/package/gulp-clean) |★★★☆ |移除文件或文件夹的包 |
|[gulp-replace](https://www.npmjs.com/package/gulp-replace) |★★★☆ |其功能看名字就知道，用做字符串替换的 |
|[gulp-autoprefixer](https://www.npmjs.com/package/gulp-autoprefixer) |★★★☆ |叼炸天的自动处理浏览器前缀的包 文档地址：[usage](https://github.com/postcss/autoprefixer#usage) |
|[gulp-rename](https://www.npmjs.com/package/gulp-rename) |★★★ |把文件重命名 结构设计的好不太会用到这个 |
|[gulp-flatten](https://www.npmjs.com/package/gulp-flatten) |★★★ |删除或替换文件的相对路径； 一般我这用来移动img或者其他静态文件到新目录 同上：结构设计的好不太会用到这个 |

<h3 id="read">精选阅读</h3>

> 以下内容不包括 [NodeJS](#RecBookForNode) 和 [面试相关](#interview) 的，俺已经单独准备好鸟

| 名称 | 推荐指数 | 备注/说明 |
| ----- | ----- | ------ |
|[stream-handbook](https://github.com/jabez128/stream-handbook) |★★★★★ |如果学习Nodejs，那么流一定是需要掌握的概念 |
|[ReactNative 中文版](http://wiki.jikexueyuan.com/project/react-native/) |★★★★☆ |翻译自官方的中文文档 |
|[MongoDB极简实践入门](https://github.com/StevenSLXie/Tutorials-for-Web-Developers/blob/master/MongoDB%20%E6%9E%81%E7%AE%80%E5%AE%9E%E8%B7%B5%E5%85%A5%E9%97%A8.md) |★★★★☆ |入门推荐的套路，非常浅显易懂 |
|[ReactWebpackCookBook](https://fakefish.github.io/react-webpack-cookbook/index.html) |★★★★☆  |此书会引导读者是进入```React```和```Webpack```的世界。 俩都是非常前沿的技术，同时使用会更有趣。 |
|[ReactNative学习指南](https://github.com/ele828/react-native-guide) |★★★★ |新玩意层出不穷... 对于能持续学习的童鞋，这是个美好的时代 |
|[HTML/CSS 编码规范](http://www.css88.com/doc/codeguide/) |★★★☆ |编写灵活、稳定、高质量的```HTML```和```CSS```代码的规范 |
|[GulpBook](https://github.com/nimojs/gulp-book) |★★★☆ |Gulp是基于Node实现Web前端自动化开发的工具 |
|[Markdown资料](https://github.com/xirong/my-markdown) |★★★☆ |简单看些语法入门，快速用起来 |

<h3 id="interview">前端面试</h3>

| 名称 | 推荐指数 | 备注/说明 |
| ----- | ----- | ------ |
|[在LinkedIn做面试官的故事](http://dongfei.baijia.baidu.com/article/52449) |★★★★★ |非面试题，介绍LinkedIn的面试过程 文章有很多中肯的建议和想法，推荐阅读 |
|[大漠：写给前端面试者](http://www.w3cplus.com/css/write-to-front-end-developer-interview.html) |★★★★★ |这篇文章不涉及任何的面试题 大漠与大家聊聊面试者与被面者之间的感受... |
|[前端面试题](https://github.com/h5bp/Front-end-Developer-Interview-Questions/tree/master/Translations/Chinese) |★★★★☆ |Git上非常火的前端面试题，```start17k+``` |

<h3>工具/软件</h3>

<h4 id="web">Web</h4>

| 名称 | 推荐指数 | 备注/说明 |
| ----- | ----- | ------ |
|[CanIuse](http://caniuse.com/) |★★★★★ |__前端必备__；查看浏览器对各种新特性的兼容情况 |
|[百度脑图](http://naotu.baidu.com) |★★★★★ |非常方便的思维导图工具 |
|[ProcessOn](https://www.processon.com/) |★★★★☆ |和百度脑图的功能类似，脑图工具。 |
|[VimAwesome](http://vimawesome.com/) |★★★★☆ |Vim插件集合，__Vim党必备__ |
|[Tower](https://tower.im) |★★★★☆ |小而美的多人协同工具。 不光只有Web版，还有iPhone、iPad、Android、微信版。 |
|[smallpdf](http://smallpdf.com/cn) |★★★★ |提供各种格式和pdf互相转换 |
|[Cmd Markdown](https://www.zybuluo.com/mdeditor) |★★★★ |好用的Web版Markdown编辑器 |
|[StackEdit](https://stackedit.io/editor) |★★★★ |又是一款Web版Markdown编辑器 |
|[墨刀](https://modao.cc/) |★★★★ |一个在线移动应用原型制作工具。 旨在帮助产品经理快速制作可在手机端展示的移动应用原型。 |
|[htm2pdf](www.htm2pdf.co.uk/index.php)|★★★★ |HTML to PDF |
|[Speaker Deck](https://speakerdeck.com/p/featured) |★★★★ |在线的演讲稿展示平台 |

<h4 id="app">APP</h4>

> 以下列表中的APP都是不区分系统平台的

| 名称 | 推荐指数 | 备注/说明 |
| ----- | ----- | ------ |
|[印象笔记](https://www.yinxiang.com/) |★★★★★ |免费账号完全够用，跨平台跨终端的记录软件|

<h5 id="android">Android</h5>

| 名称 | 推荐指数 | 备注/说明 |
| ----- | ----- | ------ |
|[小米桌面](http://zhuomian.xiaomi.com/) |★★★★★ |多好看、多漂亮谈不上，关键是没有广告|

<h5 id="iphone">iPhone</h5>

| 名称 | 推荐指数 | 备注/说明 |
| ----- | ----- | ------ |
|[Monkey](https://github.com/coderyi/Monkey) |★★★★ |Monkey是iPhone上一个GitHub第三方客户端。 展示 GitHub 上的开发者的排名，以及仓库的排名 |

<h4 id="mac">Mac</h4>

> 对于美好事务的追求无论何时都不算晚，前年公司给配了台Mac用做测试开发机，于是开始在Mac下办公。 __Windows？__ 回不去鸟...

| 名称 | 推荐指数 | 备注/说明 |
| ----- | ----- | ------ |
|[Homebrew](http://brew.sh/) |★★★★★ |没它程序猿没法好好干活... ```Homebrew```使```OS X```更完美。 使用```gem```来安装```gems```、用```brew```来搞定那些依赖包|
|[BrowseShot](https://itunes.apple.com/cn/app/browseshot/id615916400) |★★★★★ |我正在使用的网页截图工具，强烈推荐 |
|[马克鳗](http://www.getmarkman.com/) |★★★★☆ |MarkMan，非常强大好用的标注、测量工具。 日常工作免费版就完全可以满足，__强烈推荐__ |
|[WebStorm](http://www.jetbrains.com/webstorm/) |★★★★☆ |功能超强的前端IDE，不多介绍，谁用谁知道 |
|[Atom](https://atom.io) |★★★★ |2015年7月之前，在桌面环境下我最喜欢的编辑器是Sublime。 但之后就是Atom，俺也专门为它写了篇___[使用纪要](https://github.com/nieweidong/learn-atom)___ |
|[Wireshark](https://www.wireshark.org/) |★★★☆ |说实话，Mac下木有Fiddler挺不习惯，不过在有更强大的替代品 |
|[SourceTree](https://www.sourcetreeapp.com/) |★★★☆ |一款好用的的Git客户端工具，重点是支持中文:) |
|[focus booster](https://www.focusboosterapp.com/) |★★★ |因为比较在意时间管理，所以这软件是俺工作时间的必备之物 |
|[Mou](http://25.io/mou/) |★★ |小清新的Markdown编辑器 |

<h4 id="linux">Linux</h4>

| 名称 | 推荐指数 | 备注/说明 |
| ----- | ----- | ------ |
|[oh-my-zsh](http://ohmyz.sh/) |★★★★★ |___终端党___必用的好工具，强烈推荐 |
|[tree](http://www.cnblogs.com/iadanac/p/3859481.html) |★★★★ |linux以树状图逐级列出目录的内容 |
|[oneapm](http://www.oneapm.com/) |★★★★ |强大的运维工具，提供多种监控客户端； 有采集、分析、展示等一套功能； PS：我这用了服务器监控(免费哦) |
|[httpie](https://github.com/jkbrzt/httpie) |★★★☆ |一个CLI中的HTTP客户端 用法简单、易读 |

<h3 id="BrowserPlugins">Chrome浏览器插件</h3>

| 名称 | 推荐指数 | 备注/说明 |
| ----- | ----- | ------ |
|[JSONView](https://github.com/gildas-lormeau/JSONView-for-Chrome) |★★★★★ |麻麻再也不用担心偶调试接口啦 |
|[wappalyzer](https://wappalyzer.com/) |★★★★☆ |分析网站使用的技术 它可以检测网页的web服务器、JS框架等等 |
|[二维码生成器](https://chrome.google.com/webstore/detail/%E4%BA%8C%E7%BB%B4%E7%A0%81qr%E7%A0%81%E7%94%9F%E6%88%90%E5%99%A8/pflgjjogbmmcmfhfcnlohagkablhbpmg) |★★★★☆ |RT |
|[User-Agent Switcher](http://spoofer-extension.appspot.com/) |★★★★ |模拟各种终端的UA，达到调试目的 |
|[Infinity](http://infinitynewtab.com/) |★★★☆ |针对Chrome的插件，__新标签页__会让你耳目一新 |

<h3 id="git">Git</h3>

| 名称 | 推荐指数 | 备注/说明 |
| ----- | ----- | ------ |
|[Git教程-廖雪峰](http://www.liaoxuefeng.com/wiki/0013739516305929606dd18361248578c67b8067c8c017b000) |★★★★☆ |俺有看过不少Git的文章，确实这个系列是最通俗易懂的 |
|[GitAwards](http://github-awards.com/) |★★★★ |Git工具，可以查看Git排名 |
|[Git速查](https://github.com/flyhigher139/Git-Cheat-Sheet/blob/master/Git%20Cheat%20Sheet-Zh.md) |★★★★ |分类清晰的速查表 |
|[Git简明指南](http://rogerdudler.github.io/git-guide/index.zh.html) |★★★ |入门```Git```的简明指南，木有高深内容:) |
|[git学习资料整理](https://github.com/xirong/my-git)|★★★ |内容包括很多git的相关资料，```star1200+``` |

<h3 id="redis">Redis</h3>

<h3 id="mongodb">MongoDB</h3>

| 名称 | 推荐指数 | 备注/说明 |
| ----- | ----- | ------ |
|[Mongoose](https://github.com/Automattic/mongoose) |★★★★★ |让NodeJS更容易操作Mongodb数据库。  附上一篇[Mongoose学习参考文档](https://cnodejs.org/topic/504b4924e2b84515770103dd) |

<h3 id="other">杂七杂八</h3>

> 放些开发中较有用的杂物在这儿

| 名称 | 推荐指数 | 备注/说明 |
| ----- | ----- | ------ |
|[.gitignore文件](https://github.com/github/gitignore) |★★★★ |介绍不同语言项目的gitignore模板 |
|[Codebabes](https://codebabes.com/) |★★★ |学编程的网站。 重点是每通过一个测试，尼玛对应的妞会脱一件衣服... PS:要翻墙哦~ |
|[ReadmeSample](https://github.com/nieweidong/ReadmeSample)|☆ |项目高大上的第一步就是__包装__，所以来看看 ```README``` 的书写套路吧 |

<h3 id="cool">前端炫技-_炫酷狂拽叼炸天站点_</h3>

| 名称 | 推荐指数 | 备注/说明 |
| ----- | ----- | ------ |
|[windows93](http://www.windows93.net/) |★★★★★ |模拟Win93桌面，思路、体验和整体效果比较有意思 |
|[GeekTyper](http://geektyper.com/) |★★★★★ |好玩又具有Geek精神的网站，虽然创建的目的是个恶作剧 PS：网站需要翻墙 |
|[Mapbox](https://www.mapbox.com/) |★★★★★ |非常叼的开源项目，有方便的JSAPI(还有SDK)。 不过免费版只能浅尝，流量有限。 PS：网站需要翻墙 |
|[SuperScrollorama](http://johnpolacek.github.io/superscrollorama/) |★★★★ |好玩好看的动画库，链接是SuperScrollorama的展示页 |
|[parallax.js](http://matthew.wagerfield.com/parallax/) |★★★ |一个视差引擎的官网，在电脑和手机上都有很好的体验 |
|[墨刀](https://modao.cc/) |★★ |一个在线移动应用原型制作工具。 旨在帮助产品经理快速制作可在手机端展示的移动应用原型。 |

---

以下是[拔赤](http://weibo.com/jayli)总结的前端技能图：
![拔赤总结的前端技能图](https://raw.githubusercontent.com/nieweidong/fetool/master/img/fe.jpg)

---

完善ing，慢慢把 __Evernote__ 和 __浏览器书签__ 里面的好东西慢慢捣腾到这儿，更欢迎PR，谢谢。
