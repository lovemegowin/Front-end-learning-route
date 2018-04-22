# 第一阶段
* HTML：  

    HTML给你的网页赋予了结构，它就像是人的骨架那样让你保持站立，首先你需要去学习语法以及它必须提供的一切  
    
    [HTML-W3CSCHOOL](http://www.w3school.com.cn/html/index.asp)  非W3C标准官网，更新有点不及时，建议第一步花两天时间通读，对所有标签有大致的印象 
    
    [MDN HTML 中文文档](https://developer.mozilla.org/zh-CN/docs/Web/HTML)作为手册用
    建议查询某个标签比如div直接百度搜 [MDN div](https://www.baidu.com/s?ie=utf-8&f=8&rsv_bp=1&tn=baidu&wd=MDN%20div&oq=div&rsv_pq=80fcac550000e543&rsv_t=2ee1V2FB72uj6JGFAwBTGdswrwq6Rj4rzlYBMWpkckJ0fELKZfdpXj%2FoQQo&rqlang=cn&rsv_enter=1&inputT=2565&rsv_sug3=22&rsv_sug1=15&rsv_sug7=100&rsv_sug2=0&rsv_sug4=3235)  
    
    [W3C HTML5标准](https://www.w3.org/TR/html5/) 原版英文标准适合外语基础好的同学 建议有了一定基础再去翻阅  


* CSS:  

    CSS——级联样式表就是用来美化你的HTML页面的。
    
    首先要做的是学习语法，熟悉常见的CSS属性。
    了解盒模型（box model），了解常见的布局（圣杯布局，双飞翼布局等等）  
    
    [CSS-W3CSCHOOL](http://www.w3school.com.cn/css/index.asp)同上HTML,花几天时间通读，遇到不懂的先跳过，CSS是要写半年左右才能入门(一方面因为其知识点多而杂，另一方面坑很多要一个个踩过去才会明白)，然后渐入佳境  
    
    [MDN CSS中文文档](https://developer.mozilla.org/zh-CN/docs/Web/CSS) 同上    
    
    [CSS3 Tutorial《CSS3教程》](https://legacy.gitbook.com/book/waylau/css3-tutorial/details)一本简单的CSS3新功能介绍书 建议在CSS入门了之后花一小时看看  
    
    [W3C CSS标准](https://www.w3.org/Style/CSS/)同上  
    
    [张鑫旭的博客](http://www.zhangxinxu.com/wordpress/) 国内CSS界宗师级人物 博客内容需要一定的基础才能看懂 个人认为学到其10%功力都可以算叫做精通CSS了~（但也不要陷入盲目的崇拜，保持自己的独立性）
    
    [Bootstrap ](https://v3.bootcss.com/) twitter开源的样式框架 ，应该是目前市面上占有量最高的样式组件框架，学习成本不高，可以参照着官网的文档写 类似于layui
    
    等通读完W3CSCHOOL <HTML&CSS> 就可以去 [freecodecamp](https://freecodecamp.cn) 刷题 刷完HTML&CSS章

# 第二阶段
* JavaScript  

    ## 第1-2周
    1.如果你还不是很了解HTML和CSS，完成[freecodecamp](https://freecodecamp.cn)上的web基础任务。
    
    2.阅读《JavaScript高级程序设计》的前言和第1~2章。
    
    十分重要：在书中遇到的每个样例代码都要动手敲出来并且在火狐或Chrome浏览器控制台(Chrome 开发者工具[官方文档](https://developers.google.cn/web/tools/chrome-devtools/)/[中文文档](http://www.css88.com/doc/chrome-devtools/))中跑起来、尽量蹂躏它（做各种试验）。也可以用[codepen](https://codepen.io/)，但不要用Safari浏览器。我建议用chrome去测试和调试代码,毕竟往后的日子花在Chrome DevTools上的时间是最多的。浏览器控制台就是可以让你编写和运行JavaScript代码的地方。
    
    3.阅读《JavaScript高级程序设计》第3~4章。你可以跳过位操作部分，在实际的开发中一般不会用上这个。
    
    再次说明，记得要不时停下来把书本的代码敲到浏览器控制台里（或者[codepen](https://codepen.io/)）做各种测试，可以改变几个变量或者把代码结构修改一番。
    
    ## 第3-4周（对象，数组，函数，DOM，jQuery）
    
    1.阅读《JavaScript高级程序设计》第6章。注意：只需要看“理解对象”（Understanding Objects）部分。
    
    2.阅读《JavaScript高级程序设计》第5和7章，搭配观看[智能社：JavaScript教程-从入门到精通](http://study.163.com/course/introduction.htm?courseId=224014#/courseDetail?tab=1)
    
    3.阅读《JavaScript高级程序设计》第10，11，12，13章 并完成[freecodecamp](https://freecodecamp.cn)中 Basic JavaScript 章节的测试 注：JS操作DOM会消耗大量性能，现代MVVM框架基本都避免了DOM操作，所以我省去了jQuery的教程，虽然他是一个很容易掌握且强大的工具，但是初学者需要知道DOM的原理
    
    4.《JavaScript高级程序设计》其余章节等以后用到了再回过头去看看，以上提到章节需精读

    [JavaScript-W3CSCHOOL](http://www.w3school.com.cn/js/)花一天时间通读 大致了解JS的语法以及string array 等常见数据类型的方法  然后直接读《JavaScript高级程序设计》虽然名字里有高级二字
    
    5.安装NodeJs开发环境 （过程省略）
    
    6.安装编辑器，个人推荐[webstorm](http://www.jetbrains.com/webstorm/) 可以用edu尾缀的教育网邮箱申请一年的License，等到期了可以重新申请，网上亦有其他的破解教程，此处不表 
    
    ## 第4-N周（react angularjs/angular vue ）
    
    1.angularjs 因为公司的前端技术栈是 angularjs 所以我直接上手的 angularjs 框架，把 angularjs 和 angular 区分开来是因为在 angular2 以后Google对angularjs 进行了重写 框架的语法和实现原理都不向下继承，因为 angularjs 已经进入LTS(Long Time Support)时期，预计其生命周期会在2020年左右走向尾声，所以初学者不推荐学习 angular 除非你们公司的技术栈用到  
    
    2.vue 是目前最火的前端框架，其很多语法跟 angularjs 类似 具体介绍看[官网文档](https://cn.vuejs.org/) 我没用过不发表评价 但是建议初学者入门框架选择它  
    
    3.react Facebook 开源的一款优秀框架 详情见[官网](https://reactjs.org/) 有国内翻译的非官方文档 请自主搜索
    
    4.以上三个框架对比 个人觉得vue官网: [对比其他框架](https://cn.vuejs.org/v2/guide/comparison.html) 给出框架对比是最详尽的
    
    ## codeCamp 刷题笔记
    [Diff Two Arrays](codeCamp/DiffTwoArrays.md)
    
# 第三阶段
* 构建工具  

    占坑
    
* 调试    

    [Chrome DevTools — JS调试](https://segmentfault.com/a/1190000008396389)  
    
    [在 Chrome DevTools 中调试 JavaScript 入门](https://www.w3cplus.com/tools/chrome-devtools-javascript.html)  
    
* 一些学习网站分享
    * HTML&CSS
    
        * [学习CSS布局](http://zh.learnlayout.com/)
        * [通用 CSS 笔记、建议与指导](https://github.com/chadluo/CSS-Guidelines/blob/master/README.md)
        * [CSS参考手册](http://css.doyoe.com/)
        * [Emmet 文档](http://yanxyz.github.io/emmet-docs/)
        * [前端代码规范](http://alloyteam.github.io/CodeGuide/) (腾讯 AlloyTeam 团队)
        * [HTML和CSS编码规范](http://codeguide.bootcss.com/)
        * [Sass Guidelines 中文](http://sass-guidelin.es/zh/)
        * [CSS3 Tutorial 《CSS3 教程》](https://github.com/waylau/css3-tutorial)
        * [MDN HTML 中文文档](https://developer.mozilla.org/zh-CN/docs/Web/HTML)
        * [MDN CSS 中文文档](https://developer.mozilla.org/zh-CN/docs/Web/CSS)
        
    * JavaScript
    
        * [Google JavaScript 代码风格指南](http://bq69.com/blog/articles/script/868/google-javascript-style-guide.html)
        * [Google JSON 风格指南](https://github.com/darcyliu/google-styleguide/blob/master/JSONStyleGuide.md)
        * [Airbnb JavaScript 规范](https://github.com/adamlu/javascript-style-guide)
        * [JavaScript 标准参考教程（alpha）](http://javascript.ruanyifeng.com/)
        * [Javascript编程指南](http://pij.robinqu.me/) ([源码](https://github.com/RobinQu/Programing-In-Javascript))
        * [javascript 的 12 个怪癖](https://github.com/justjavac/12-javascript-quirks)
        * [JavaScript 秘密花园](http://bonsaiden.github.io/JavaScript-Garden/zh/)
        * [JavaScript核心概念及实践](http://icodeit.org/jsccp/) (PDF) (此书已由人民邮电出版社出版发行，但作者依然免费提供PDF版本，希望开发者们去购买，支持作者)
        * [《JavaScript 模式》](https://github.com/jayli/javascript-patterns) “JavaScript patterns”中译本
        * [命名函数表达式探秘](http://justjavac.com/named-function-expressions-demystified.html)  (注:原文由[为之漫笔](http://www.cn-cuckoo.com)翻译，原始地址无法打开，所以此处地址为我博客上的备份)
        * [学用 JavaScript 设计模式](http://www.oschina.net/translate/learning-javascript-design-patterns) (开源中国)
        * [深入理解JavaScript系列](http://www.cnblogs.com/TomXu/archive/2011/12/15/2288411.html)   
        * [ECMAScript 5.1 中文版](http://yanhaijing.com/es5)   
        * [ECMAScript 6 入门](http://es6.ruanyifeng.com/) (作者：阮一峰)
        * [JavaScript Promise迷你书](http://liubin.github.io/promises-book/)
        * [You-Dont-Know-JS](https://github.com/getify/You-Dont-Know-JS) (深入JavaScript语言核心机制的系列图书)
        * [JavaScript 教程](http://www.liaoxuefeng.com/wiki/001434446689867b27157e896e74d51a89c25cc8b43bdb3000) 廖雪峰
        * [MDN JavaScript 中文文档](https://developer.mozilla.org/zh-CN/docs/Web/JavaScript)
        * jQuery
            * [jQuery 解构](http://www.cn-cuckoo.com/deconstructed/jquery.html)
            * [简单易懂的JQuery魔法](http://www.nowamagic.net/librarys/books/contents/jquery)
            * [How to write jQuery plugin](http://i5ting.github.io/How-to-write-jQuery-plugin/build/jquery.plugin.html)
            * [You Don't Need jQuery](https://github.com/oneuijs/You-Dont-Need-jQuery/blob/master/README.zh-CN.md)
            * [如何实现一个类jQuery？](https://github.com/MeCKodo/forchange)
        * Node.js
            * [Node入门](http://www.nodebeginner.org/index-zh-cn.html)
            * [七天学会NodeJS](http://nqdeng.github.io/7-days-nodejs/)
            * [Nodejs Wiki Book](https://github.com/nodejs-tw/nodejs-wiki-book) (繁体中文)
            * [express.js 中文文档](http://expressjs.jser.us/)
            * [koa 中文文档](https://github.com/guo-yu/koa-guide)
            * [一起学koa](http://base-n.github.io/koa-generator-examples/)
            * [使用 Express + MongoDB 搭建多人博客](https://github.com/nswbmw/N-blog)
            * [Express框架](http://javascript.ruanyifeng.com/nodejs/express.html)
            * [Node.js 包教不包会](https://github.com/alsotang/node-lessons)
            * [Learn You The Node.js For Much Win! (中文版)](https://www.npmjs.com/package/learnyounode-zh-cn)
            * [Node debug 三法三例](http://i5ting.github.io/node-debug-tutorial/)
            * [nodejs中文文档](https://www.gitbook.com/book/0532/nodejs/details)
            * [orm2 中文文档](https://github.com/wizardforcel/orm2-doc-zh-cn)
        * AngularJS
            * [AngularJS最佳实践和风格指南](https://github.com/mgechev/angularjs-style-guide/blob/master/README-zh-cn.md)
            * [AngularJS中译本](https://github.com/peiransun/angularjs-cn)
            * [AngularJS入门教程](https://github.com/zensh/AngularjsTutorial_cn)
            * [构建自己的AngularJS](https://github.com/xufei/Make-Your-Own-AngularJS/blob/master/01.md)
            * [在Windows环境下用Yeoman构建AngularJS项目](http://www.waylau.com/build-angularjs-app-with-yeoman-in-windows/)
        * React.js
            * [React.js 中文文档](https://doc.react-china.org/)
            * [React webpack-cookbook](https://github.com/fakefish/react-webpack-cookbook)
            * [React 入门教程](http://fraserxu.me/intro-to-react/)
            * [React Native 中文文档(含最新Android内容)](http://wiki.jikexueyuan.com/project/react-native/)
            * [Learn React & Webpack by building the Hacker News front page](https://github.com/theJian/build-a-hn-front-page)
        * TypeScipt
            * [TypeScript Handbook](https://zhongsp.gitbooks.io/typescript-handbook/content/)
        * [Chrome扩展及应用开发](http://www.ituring.com.cn/minibook/950)
        
    * web相关
        * [关于浏览器和网络的 20 项须知](http://www.20thingsilearned.com/zh-CN/home)
        * [浏览器开发工具的秘密](http://jinlong.github.io/2013/08/29/devtoolsecrets/)
        * [Chrome 开发者工具中文手册](https://github.com/CN-Chrome-DevTools/CN-Chrome-DevTools)
        * [Chrome扩展开发文档](http://open.chrome.360.cn/extension_dev/overview.html)
        * [Grunt中文文档](http://www.gruntjs.net/)
        * [gulp中文文档](http://www.gulpjs.com.cn/docs/)
        * [Gulp 入门指南](https://github.com/nimojs/gulp-book)
        * [移动Web前端知识库](https://github.com/AlloyTeam/Mars)
        * [正则表达式30分钟入门教程](http://deerchao.net/tutorials/regex/regex.htm)
        * [前端开发体系建设日记](https://github.com/fouber/blog/issues/2)
        * [移动前端开发收藏夹](https://github.com/hoosin/mobile-web-favorites)
        * [JSON风格指南](https://github.com/darcyliu/google-styleguide/blob/master/JSONStyleGuide.md)
        * [HTTP 接口设计指北](https://github.com/bolasblack/http-api-guide)
        * [前端资源分享（一）](https://github.com/hacke2/hacke2.github.io/issues/1)
        * [前端资源分享（二）](https://github.com/hacke2/hacke2.github.io/issues/3)
        * [前端代码规范 及 最佳实践](http://coderlmn.github.io/code-standards/)
        * [前端开发者手册](https://www.gitbook.com/book/dwqs/frontenddevhandbook/details)
        * [前端工程师手册](https://www.gitbook.com/book/leohxj/front-end-database/details)
        * [w3school教程整理](https://github.com/wizardforcel/w3school)
        * [Wireshark用户手册](http://man.lupaworld.com/content/network/wireshark/index.html)
        * [一站式学习Wireshark](https://community.emc.com/thread/194901)
        * [HTTP 下午茶](https://ccbikai.gitbooks.io/http-book/content/)
        * [HTTP/2.0 中文翻译](http://yuedu.baidu.com/ebook/478d1a62376baf1ffc4fad99?pn=1)
        * [RFC 7540 - HTTP/2 中文翻译版](https://github.com/abbshr/rfc7540-translation-zh_cn)
        * [http2讲解](https://www.gitbook.com/book/ye11ow/http2-explained/details)
        * [3 Web Designs in 3 Weeks](https://www.gitbook.com/book/juntao/3-web-designs-in-3-weeks/details)
        * [站点可靠性工程](https://github.com/hellorocky/Site-Reliability-Engineering)
