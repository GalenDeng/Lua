## LUA 简介
1. 
```
Lua 是一种轻量小巧的脚本语言，用标准C语言编写并以源代码形式开放， 其设计目的是为了嵌入应用程序中，从而为应用程序提供灵活的扩展和定制功能。
```
2. `设计目的`
```
为了嵌入应用程序中，从而为应用程序提供灵活的扩展和定制功能
```
3. `特性`
```
轻量级: 它用标准C语言编写并以源代码形式开放，编译后仅仅一百余K，可以很方便的嵌入别的程序里。
可扩展: Lua提供了非常易于使用的扩展接口和机制：由宿主语言(通常是C或C++)提供这些功能，Lua可以使用它们，就像是本来就内置的功能一样。
其它特性:
支持面向过程(procedure-oriented)编程和函数式编程(functional programming)；
自动内存管理；只提供了一种通用类型的表（table），用它可以实现数组，哈希表，集合，对象；
语言内置模式匹配；闭包(closure)；函数也可以看做一个值；提供多线程（协同进程，并非操作系统所支持的线程）支持；
通过闭包和table可以很方便地支持面向对象编程所需要的一些关键机制，比如数据抽象，虚函数，继承和重载等。
```
4. `应用场景`
```
游戏开发
独立应用脚本
Web 应用脚本
扩展和数据库插件如：MySQL Proxy 和 MySQL WorkBench
安全系统，如入侵检测系统
```
5. 
```
Lua 是一个区分大小写的编程语言
```
6.
 ![第三方模块查找](http://image.baidu.com/search/detail?ct=503316480&z=0&ipn=d&word=%E5%9B%BE%E7%89%87&step_word=&hs=0&pn=0&spn=0&di=102201372350&pi=0&rn=1&tn=baiduimagedetail&is=0%2C0&istype=0&ie=utf-8&oe=utf-8&in=&cl=2&lm=-1&st=undefined&cs=4195805644%2C827754888&os=1974553739%2C2238405713&simid=3348721995%2C380165808&adpicid=0&lpn=0&ln=1664&fr=&fmq=1507637331273_R&fm=&ic=undefined&s=undefined&se=&sme=&tab=0&width=undefined&height=undefined&face=undefined&ist=&jit=&cg=&bdtype=0&oriquery=&objurl=http%3A%2F%2Fi-3.yiwan.com%2F2017%2F4%2F24%2F60ec4a83-1eb8-4c96-8b26-c50af6bfe18f.jpg&fromurl=ippr_z2C%24qAzdH3FAzdH3Fooo_z%26e3Bytowg_z%26e3Bv54AzdH3Fip4scAzdH3Fd8lnmlAzdH3F&gsm=0&rpstart=0&rpnum=0)