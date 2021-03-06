# 语法篇
## WXML 语法
<img src="image/wxml.png">

## WXS模块
<img src="image/wxs1.png">

## 函数
<img src="image/appLive.png">
<img src="image/pageLive.png">

`js` 和 `wxss` 不介绍，没什么知识点

## 路由

路由在项目开发中一直是个核心点，小程序路由方面经过很好的封装，提供了几个基本的跳转方法(这三个基本够用)
>* `wx.navigateTo(OBJECT)`：保留当前页面，跳转到应用内的某个页面，使用`wx.navigateBack` 可以返回到原页面。

>* `wx.redirectTo(OBJECT)`：关闭当前页面，跳转到应用内的某个页面。

>* `wx.navigateBack()`：关闭当前页面，回退前一页面。可通过 `getCurrentPages())` 获取当前的页面栈，决定需要返回几层

## `template`

 引入 `template` 时非常方便，`is` 和 `name` 一样，`data` 是 `nameData` 传递过来的数据填充,一切都绑定数据为中心点 

<img src="image/template.png">

 ## 自定义组件
 我假设你知道 `vue` 里面是如何自定义组件的，那么我和可以和小程序的自定义组件说 `so easy`，语法有异曲同工之妙；具体怎么用我们看看就知道了。
 >* 创建组件

<img src='image/component.png'>
<img src='image/components.png'>

>* 引用组件

<img src='image/components1.png'>

你现在已经知道怎么创建使用自定义组件了，就是这么简单容易。哈哈

小程序的组件和 `API` 就不详细的介绍了，敲两个 `demo` 就会了，没必要特意去看

你现在已经知道怎么创建使用自定义组件了，就是这么简单容易。

[计算器案例地址](https://github.com/sunseekers/WeChatProject/tree/master/demo/calculate)

[仿知乎案例](https://github.com/sunseekers/WeChatProject/tree/master/demo/imitateZhiHu)，数据模仿，没有抓取接口，没有交互，纯属静态页面，主要是为了熟悉掌握语法，为了后续学习做准备。

<img src="image/zhihu.png">

[仿知乎参考案例](https://github.com/RebeccaHanjw/weapp-wechat-zhihu)，在原有的基础上稍微改进了一下，改进地方在引入自定义组件。

我假设你也会 `vue` ，读一两遍官方文档，敲一遍上面两个简单的案例。对于小程序那应该是掌握差不多了。接下来准备用小程序仿一个 `QQ` 音乐，引入复杂的交互，接口抓取实时数据，尽我最大可能的还原生 `APP` 体验。


[学习资料参考](https://github.com/justjavac/awesome-wechat-weapp)
