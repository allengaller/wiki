欢迎访问GreatFire.org开发者项目网站。我们将在Github上逐步开源所有GreatFire.org的项目，包括[Collateral Freedom镜像网站](https://github.com/greatfire/wiki/)，[免翻墙Android应用](https://play.google.com/store/apps/developer?id=GreatFire.org)，[redirect-when-blocked](https://github.com/greatfire/redirect-when-blocked),[自由微博](https://FreeWeibo.com)和[GreatFire封锁检测](https://zh.greatfire.org).

Welcome to GreatFire.org open-source project site. We're going to gradually release all of our projects including [Collateral Freedom mirror sites](https://github.com/greatfire/wiki/)，[Collateral Freedom Android Apps](https://play.google.com/store/apps/developer?id=GreatFire.org)，[redirect-when-blocked](https://github.com/greatfire/redirect-when-blocked),[FreeWeibo](https://FreeWeibo.com) and [GreatFire.org itself](https://zh.greatfire.org).

现有开源项目如下，欢迎大家编辑代码，开Issues。

* [redirect-when-blocked](https://github.com/greatfire/redirect-when-blocked): 当网站被GFW封锁后，用户只能看到一个错误页面。但使用redirect-when-blocked后，我们使用浏览器的缓存把已有用户重定向到新的未被封锁的地址。这样GFW的封锁对已有用户完全没有任何影响。而且所有改动都在服务器完成，访问者无需安装任何特殊软件。

* [website-mirror-by-proxy](https://github.com/greatfire/website-mirror-by-proxy): Website-mirror-by-proxy 是服务器端运行反向代理的代码，其采用了 https://github.com/greatfire/redirect-when-blocked 完全版。搭建的动态镜像网站会在后台加载许多URL。镜像网站会自动从未被封锁的URL来加载镜像网站。用户打开的新链接也会被定向到这些未被封锁的后台中。

Currently we have open-sourced the following projects. Please feel free to improve our code and open issues. 

* [redirect-when-blocked](https://github.com/greatfire/redirect-when-blocked): When a website is blocked by GFW, users will only see an error notice in the browser. By implementing redirect-when-blocked, we can redirect users to new URL that are not blocked thanks to browser cache. This way, all existing users can continue to use the old URL as if it were not blocked. All changes are made on the server side and visitors do not need to install any special software. 

* [website-mirror-by-proxy](https://github.com/greatfire/website-mirror-by-proxy): Website-mirror-by-proxy is a server-side web proxy designed to host one or multiple dynamic mirror versions of any website. It is based on https://github.com/greatfire/redirect-when-blocked (the full edition). The mirror site will load content from multiple not blocked URLs at the backend. Users will be redirected to URL that is not blocked when opening new links.

## 招聘：

我们正在招聘GreatFire.org后台程序员。

主要职责是开发和改进 GreatFire.org 的自动测试程序，开发API帮助其他研究人员获取GreatFire.org的测试数据等。要求精通 Java,Mysql, Curl和基本的Linux。

请在email写出你觉得应该如何改进现有的 GreatFire.org 的测试程序，和你引以为豪project或者工作经验等。

匿名远程工作。待遇丰厚，使用美元结算，具体金额根据个人经验而定。收入税自理。

请联系percyalpha[at]gmail[dot]com,PGP key 见 https://zh.greatfire.org/contact#alt 你可以专门创建一个新Gmail邮箱来联系我们。