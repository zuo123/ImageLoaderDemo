# ImageLoaderDemo
Android 源码设计模式学习，图片加载器项目

--------------------------
### 20190717， ImageLoader3.0
1、根据开闭原则对ImageLoader2.0进行升级，增加本地持久化缓存 <br/>
2、支持内存缓存、本地持久化缓存、内存缓存和本地持久化双缓存 <br/>
3、支持用户自定义缓存

--------------------------
### 20190717， ImageLoader2.0
在ImageLoader1.0的基础上，按照单一职责原则将缓存功能和图片下载、展示功能分离开，单独作为一个类ImageCache，降低代码的耦合程度

--------------------------
### 20190716， ImageLoader1.0
第一版的图片加载框架，实现了网络图片的下载、缓存（内存）、展示的功能，未进行功能拆分，代码耦合程度较高。
