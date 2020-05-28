\<button>标签和\<reply>标签
==============
## \<button>标签
`<button>` 标签是在通话过程中使用，为用户提供快速点击选项的 “按钮”。目前，该标签有两种类型：回发按钮（用于将消息返回给bot）和网址按钮（其功能类似于链接）。  

我们直接来看一下效果

![click](images/click.gif)  

实现代码：  

![30](images/30.png)  

可以看到，`<postback>` 标签内的内容只是一个新的category中`<pattern>` 的内容，真正返回给用户的内容要放在 `<template>` 标签内。  

## \<reply>标签

`<reply>`标签和 `<button>` 标签类似，也提供给用户快速点击的选项，但是呈现方式不一样，而且在用户点击一个之后，选项框会消失，用户没有机会再次点击其他选项框。让我们来看一下这个标签的效果：  

![click2](images/click2.gif)  
