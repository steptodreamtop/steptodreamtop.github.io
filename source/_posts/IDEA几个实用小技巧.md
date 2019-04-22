---
title: IDEA几个实用小技巧
date: 2019-04-20 11:11:45
tags: IDEA
---
工欲善其事必先利其器，分享一些官网的说明文档上没提及的但开发中比较实用的IDEA技巧，如果你有好的知识分享，欢迎加入我们。
 &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;&nbsp; &nbsp; &nbsp;![avatar](/img/IDEA/00.jpg)
<!-- more -->
IDEA官网：https://www.jetbrains.com/idea/
文档：http://wiki.jikexueyuan.com/project/intellij-idea-tutorial/keymap-introduce.html
本次分享使用的IDEA版本：
![avatar](/img/IDEA/1.jpg)
一、可以增加开发和阅读源码效率的插件
JRebel
![avatar](/img/IDEA/2.jpg)
官网地址：https://jrebel.com/software/jrebel/
说明：在开发过程中，免去了修改代码后rebuild、reload、redeploy的过程，和传统方式相比JRebel会直接重载class到JVM中， 大量节省开发时间。

二.几个好用的快捷键
    1. Ctrl+Alt+H 显示方法调用的层次
![avatar](/img/IDEA/3.jpg)
   2. Ctrl+Shift+F8 一次取消所有断点
![avatar](/img/IDEA/4.jpg)
   3.Ctrl+F9 修改代码后，执行编译操作

三.Debug中的一些技巧

1. F8和F9不过多介绍了，一个是单步执行和运行到下一断点，基本IDEA的用户都知道

2. Shift+F7 选择性步入源码的具体实现，可以人为选择具体进入哪个方法的源码实现
![avatar](/img/IDEA/5.jpg)
3. Alt+F9  让断点运行至光标所在的行，好处：不用在该行打断点即可实现
![avatar](/img/IDEA/6.jpg)
4. Alt+鼠标左键 快速查看变量的值
![avatar](/img/IDEA/7.jpg)
5. 多线程调试 这个的应用场景比如开发环境有类似dubbo+zk的架构，由于负载均衡原因别的小伙伴调用接口时进入有断点的本地调试机器，会导致想发起另外一个请求都无法进行了，出现这个问题是因为IDEA在Debug时默认的阻塞级别是ALL，会阻塞其它线程，也就是说要等当前调试线程走完时才会走其它线程，这个提供一个小技巧可以解决这个问题，Ctrl+Shift+F8进入断点设置视图，Suspend选Thread，即可进行多线程调试
![avatar](/img/IDEA/8.jpg)
6. 断点回退 有时候常因为不小心错过了想看的代码行数，断点调试界的后悔药
![avatar](/img/IDEA/9.jpg)

如果您觉得这些小技巧对你有用，如果您也同样热衷于分享，欢迎关注：源码精品分享，我们期待您的加入。
<!--音乐播放插件：渡我不渡她-->
    <div style="margin-top:0px;">
        <iframe frameborder="no" border="0" marginwidth="0" marginheight="0" width=240 height=52 src="http://fs.open.kugou.com/b9f8080e5f83c30e15b843d6810b361a/5cbc0114/G157/M02/02/19/fZQEAFyYVLqAWZLZACHO3VyRKus397.mp3"></iframe>
    </div>