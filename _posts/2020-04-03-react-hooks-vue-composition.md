---
layout: post
title: "这是title"
subtitle: "testtesttest"
author: "spericlee"
header-style: text
tags:
  - 知乎
  - Web
  - React
---

> [我的web地址：https://speric.vvvv.ee](https://speric.vvvv.ee)  
> > webtest01
> > > 项目测试ing  


![我的图标](https://ms.bdimg.com/pacific/0/pic/-1670962947_-1250932839.png?x=0&y=0&h=340&w=510&vh=340.00&vw=510.00&oh=340.00&ow=510.00)

这是一篇我的测试web内容  
你可以忽略  
不要回答！

-------------

以下是代码块

```ts
const Counter = {
  setup(initialProps) {
    const count = reactive({count: 0}) // or `ref(0)`
    const inc = () => { count.value++ }
    return {count, inc}
  }
  template: "..."
}
```


行内引用代码`setup` ，`@163`。


这是加粗字体，**直接利用闭包来保存组件变量**，  
这是斜体，*你还说这是对象的语义吗？*  
这是粗斜体，***这是粗斜体***。
```ts
return (props) => <a onClick={inc}>{count.value}</a>
```
这是转义引用[\[1\]](https://www.baidu.com)。


# 这是一级标题
```ts
// hypothetical Vue lang
component Counter (props) {    // constructor
  @reactive count = 0          // field
  inc() { count.value ++ }     // method
  render() { return <a onClick={inc}>{count.value}</a> }
}
```
------------
Testline，英文字体为何如此之大，只要放在---分割线上方的字体自动变大
---
------------



这是例图的未加载情况  
![这是例图的未加载情况](https://ms.bdimg.com/pacific/0/pic/572051440_2105937599.png?x=0&y=0&h=340&w=510&vh=340.00&vw=510.00&oh=340.00&ow=510.00)

以下是内容引用，英文版
---
> It's interesting because there are really two approaches evolving. There's a **mutable + change tracking** approach and there's an **immutability + referential equality testing** approach. It's difficult to mix and match them when you build new features on top. So that's why React has been pushing a bit harder on immutability lately to be able to build on top of it. Both have various tradeoffs but others are doing good research in other areas, so we've decided to focus on this direction and see where it leads us.

以下是内容引用，中文版
---
>中文引用内容test

+ +号的无序列表
* *号的无序列表
- -号的无序列表
- 


有序列表参考（下划线和*为窄行距分割) 
---
*** 
___
---
*** 
___
***

有序列表打断需要用任意内容打断
---
1. 测试链接表1 [www.baidu.com](https://www.baidu.com/)
2.  测试链接表2 [www.163.com](https://www.163.com)
3.  测试链接表3 [www.weibo.com](https://www.weibo.com)
4.  测试链接表41 [www.qq.com](https://www.qq.com)

8. 测试链接表8 [www.taobao.com](https://www.taobao.com)

teste  
20. 测试链接表8 [www.cloudflare.com](https://www.cloudflare.com)