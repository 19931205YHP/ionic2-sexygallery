# ionic2-sexygallery
## [基于ionic+angular开发的阅图app](https://git.oschina.net/tonge/ionic-sexygallery)
## [基于ionic2+angular2开发的阅图app](https://git.oschina.net/tonge/ionic2-sexygallery)
![alt](./www/img/ionic2-sexygallery.gif)


## 本项目出自于微信订阅号TongeBlog的ionic2项目实战教程  

ionic2项目实战教程 - 前言  
ionic2项目实战教程 - 第1讲 新建项目以及ionic2目录结构讲解  
ionic2项目实战教程 - 第2讲 动态获取抽屉分类菜单  
ionic2项目实战教程 - 第3讲 根据分类菜单获取列表  
ionic2项目实战教程 - 第4讲 实现左右滑动浏览图片  
ionic2项目实战教程 - 第5讲 如何在ionic2中使用cordova插件  



## 前言

&#160; &#160; &#160; &#160;ionic2项目实战教程终于出炉了，在这之前先提醒一下各位，ionic项目实战是需要一些基础知识的，比如最经典的编程思想OOP面向对象和MVC分层的概念，以及typescript和es6的常用语法规范。

&#160; &#160; &#160; &#160;因为是实战教程，概念性的东西用到的就提一下，告诉大家为什么这样做，毕竟是实战，教大家做实际应用的，不做理论讲解，理论知识大家在网上找找资料。

&#160; &#160; &#160; &#160;这里我先简单的说一下，都是在1的教程里我没有提到的。对于MVC，如果你单纯的去看理论，那是很难理解的。但如果你做完ionic1项目实战教程，可能就会有这样一种体会，项目中所有跟网络请求以及服务相关的，全部都封装到service.js里了；逻辑控制相关的代码都放到了controller.js里，剩下的视图层View就不用我多说了。总结这些，如果你搞明白了，那么恭喜你，你已经学会了mvc分层，和mvc分层的概念了。


&#160; &#160; &#160; &#160;在项目实战之前，须对angular2有基础的了解和认识，另外，angular2在9月15日已发布最终版，最终版意味着稳定版，大家可放心使用。更多关于angular2的资料大家请移步到angular2官网。

&#160; &#160; &#160; &#160;最后简单几句话描述一下我在使用ionic+angular和ionic2+angular2开发项目的感受，首先angular2语法有很大的变动，整个框架基于TypeScript开发，如果有C#、Java，或者Swift开发经验者，学习这门语言基本没有多大难度的；再一个就是体验到了angular一直追求的核心概念：组件化（Component），整个开发过程中就是不停的在自定义组件，至于angular2的其他变动，比如为了优化性能去掉了$scope；将ng-controller的概念合并到了Component；双向数据绑定脏值检查的优化；嵌套路由；构造函数中的依赖注入等等，大家可移步至官网详细了解。

>欢迎关注微信订阅号TongeBlog，查阅ionic2全套项目实战教程。  
![alt](./www/img/TongeBlog.jpg)
