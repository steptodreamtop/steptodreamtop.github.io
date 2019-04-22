---
title: 浅谈Fiddler手机抓包在实际开发中的应用
date: 2019-04-19 15:37:41
tags: Fiddler
---
平常的开发中，经常需要通过抓包来分析手机或者页面发出的请求，Fiddler是一个很好用的抓包工具，可以将网络传输发送与接受的数据包进行截获、重发、编辑、转存等操作。对于工作原理什么的可以自行google，由于在WEB开发中，google自带的开发者工具大部分可以满足开发的抓包需求了，所以我这篇文章主要分享一下在手机抓包在实际开发中使用的心得。
&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;![avatar](/img/Fiddler/0.jpg)
<!-- more -->
1.Fiddler下载

官网链接：https://www.telerik.com/fiddler

英文文档链接：http://docs.telerik.com/fiddler/configure-fiddler/tasks/configurefiddler

2.Fillder界面介绍及参数配置

（1）找到Tools->Fiddler Options->Connections,将Allow remote computer to connect 选中，点击OK，这是为了能够捕获远程设备上的请求而勾选的。
![avatar](/img/Fiddler/2.jpg)
（2）在HTPPS中勾选【Capture HTTPS CONNECTS】
![avatar](/img/Fiddler/1.jpg)
（3）将软件退出然后重启

3.手机端配置，以安卓手机为例介绍

（1）首先需要确保手机端和安装Fiddler软件的电脑在同一局域网，我是连的公司内网WIFI，配置手机代理前，先在电脑端的Fiddler页面的右上角鼠标悬浮online查看机器的IP
![avatar](/img/Fiddler/3.jpg)
（2）进行手机端代理设置，选择代理配置方式为手动，服务器IP为上一步查看的安装Fiddler机器的IP，端口设置为8888
![avatar](/img/Fiddler/4.jpg)
（3）在手机端操作需要抓包调试的软件，可查看Fiddler已执行抓包请求
![avatar](/img/Fiddler/5.jpg)
![avatar](/img/Fiddler/6.jpg)
![avatar](/img/Fiddler/7.jpg)
![avatar](/img/Fiddler/8.jpg)
![avatar](/img/Fiddler/9.jpg)
 <!--音乐播放插件：绿色-->
    <iframe frameborder="no" border="0" marginwidth="0" marginheight="0" width=290 height=310 src="http://fs.open.kugou.com/9dd6b3ef4bdf34eff78817119c12d7fb/5cbc0159/G119/M01/05/0D/F4cBAFxlweSAT9BlAEHWDL3dgeI800.mp3"></iframe>
