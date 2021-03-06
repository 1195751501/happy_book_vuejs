# Webpack下的Vuejs

所有的Vuejs 项目，都是在Webpack的框架下进行开发的。 

可以说， vue-cli 直接把webpack做了集成。 我们在开发的时候，一边享受着飞一般的开发速度，一边体验着webpack带来的便利。

在本章，会介绍如何使用两者进行开发的基本知识。

## 学习过程

我们在学习任何一种框架的时候，都是按照循序渐进的顺序来的：

1. 安装
2. 新建一个页面
3. 做一些简单的变量的渲染  
4. 实现页面的跳转  (路由)
5. 实现页面间的参数的传递 (路由)
6. 实现真实的http请求（访问接口)
7. 提交表单       
8. 使用一些技巧来让代码层次化（组件）

按照我之前在惠普，联通，移动等公司的讲课经验，只要用一天的时间把本章内容学会，就可以上手开发Vuejs项目了。 

同学们只要手头有个电脑，看一个章节，就跟着老师来敲一些代码，就肯定可以在一天内把这些基本的内容消化完。 

## 可以跳过的章节

对于有一定node基础的同学，可以跳过 "NVM的安装"

对于使用Linux/Mac的 同学，可以跳过 "Git Bash的安装"

## 简写说明

由于本章节是 Webpack + Vuejs 下的实战开发，所以统一使用 "Vuejs" 来代替冗长的 "Webpack + Vuejs".  

例如，

```
在Vuejs中创建页面需要两步：

1. 新建路由
2. 新建vue页面
```

中的 "Vuejs", 指的就是在 "Webpack + Vuejs"的项目中。 而不是 "原始Vuejs".

## 例子

本章节中的所有例子，由于都需要跟webpack相结合，所以我把它单独拉出来成为一个项目：  https://github.com/sg552/vue_js_lesson_demo  

大家可以下载后直接运行。 

```
$ git clone https://github.com/sg552/vue_js_lesson_demo.git
$ npm install -v
$ npm run dev
``` 

然后就可以在  http://localhost:8080/#/ 中看到效果，如下图所示：

![lesson demo](./images/vue_lesson_demo.png)