# 前言
微前端 single-spa 小demo
# 简介
跟随着【 李永宁大佬的文章 https://juejin.cn/post/6862661545592111111juejin.cn 】进行学习
# 感想
以下是本次实现后的小感想
1. 微前端 single-spa 其实就是基于一个基座，利用端口和路由的不同来进行项目在同一层面上的切换。
2. 可以作用于某个大型商务应用中，不同的功能模块因过于庞大而需单独拆分耦合。
- 像是淘宝特价的各个模块，如搜索引擎功能、商家功能、购物车功能、个人功能等等等。这一些模块作为单独项目都很庞大，因此可以利用微前端基于基座来模块化和耦合，实现不同项目的“丝滑切换”。
3. 难怪微前端这么有趋势，要是做强做大，一个模块的功能就是一个项目小组。微前端就可以进行统一合并管理呀！
4. 就是说阿里的开源微前端框架 - qiankun（基于 single-spa 的二次封装） 就是来解决这个实际业务而落地的，反正就更厉害了。也还没用过，想进一步接触了解！接下来再进行学习和探索。

# 问题
遇到的小问题
1. 因为都是基于 vue 框架，然后基座也是一个 vue 框架来作为映射。
2. 要利用不同端口来区分不同子项目。
3. 子项目需要同时运行起来才行。

# 小嘀咕
（小感悟，错了就改。没人提那就是我没错。😱）
