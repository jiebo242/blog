---
title: mac基本使用
date: 2018-08-28 18:21:34
updated: 2018-08-28 18:25:35
categories: mac
tags: [mac, 软件使用]
---
公司让统一换成mac本，所以被逼无奈，开始mac使用的新旅程，一开始还挺担心用不来，不过后来真正用户起来，发现和windows实际上没有太大的差别，下面是我在学习使用过程中整理的资料，足够mac的上手和工作了，至于mac的深入和快捷使用，可挖掘的东西很多，有人还专门出书呢。
<!-- more -->
# mac了解
>桌面主要是两部分：菜单栏、Dock栏  
![mac键盘图标](mac键盘图标.png 'mac键盘图标')  
![mac按键图标](mac按键图标.png 'mac按键图标')   
# 快捷键
我这边常用的快捷键：
```   
窗口类：
	Command+M: 最小化窗口
	Command+H: 隐藏窗口(我基本用这个代替最小化窗口，因为最小化窗口会在dock栏显示一个新的图标、占地方)
	Command+T: 在浏览器中打开新的选项卡
	Command+W: 关闭窗口，程序并没有真的退出，相当于点击了左上角的红叉叉
	Command+Q: 退出程序，真正退出了
	Command+option+esc: 强制退出程序，在程序无响应时使用，类似于ctrl+alt+del
文件类：
	Command+c：复制文件
	Command+v：粘贴文件
	Command+a：全选
	Command+s：保存
	Command+f：搜索
	Command+option+v：相当于剪切(配合Command+c使用)
	Command+option+C：复制文件路径
	option+command+C：复制文件路径
系统类：
	Command+Space：来调用Spotlight(也可点击右上角的“放大镜”图标)
	Command+Shift+3：全屏截图
	Command+Shift+4：区域截图
	Command+tab：在应用程序间切换
	Command+`：在同一应用程序的窗口间切换
```  
More info: [官网快捷键大全](https://support.apple.com/zh-cn/HT201236)
# 触摸板
mac的触摸板用熟了，效率杠杠滴，具体的触摸板动作设置可以在“系统偏好设置-触控板”进行设置和查看。  
More info: [官网触控板手势](https://support.apple.com/zh-cn/HT204895)
# 软件安装
熟悉基本操作后，就开始安装基本的办公软件了。
## Jdk
下载-安装-配置环境变量  
[MAC安装JDK及环境变量配置](https://blog.csdn.net/qq_35447305/article/details/78648839)  
现在都不用配置环境变量，安装完成后，自动配置，如果一台电脑装了多个版本的jdk，则需要通过配置环境变量指定一个。
## Maven
下载-解压-配置环境变量  
[在mac安装maven的方法](https://www.jianshu.com/p/eea8ebd227b1)  
因为是免安装的，所以得配置下环境变量
## git
[mac 上安装git步骤及注意事项](https://blog.csdn.net/helinlin007/article/details/50358633)
## git图形化工具
mac没有tortoiseGit，不过有其他的，不过想了想还是不装了，初次导入工程时使用git命令，后面用IDEA导入后，就直接用IDEA自带的git来进行图形化操作了。
## IDEA
官网下载-配置hosts-粘入激活码  
[IntelliJ IDEA 2018 破解过程](https://www.jianshu.com/p/3c87487e7121)  
[激活码获取](http://idea.lanyus.com/)，先配置hosts，再打开IDEA输入激活码即可，不过这种有效期比较段；还可以通过补丁包激活的方式，这种有效期到2099年。  
[mac上IDEA快捷键](http://guochenglai.com/2016/05/28/mac-idea-intellij-idea-shortcurt-key/),不过我是吧keymap设置为和windows上一致，所以快捷键保持不变，这样开发起来就无缝对接了。
## UE
下载-激活
本来打算安装ue，后来想象sublime可以通过插件扩充功能，更加强大,[UE破解](https://bbs.feng.com/read-htm-tid-10828753.html)
## Sublime
下载-记不激活都行-安装各种插件  
[sublime新手使用](https://blog.csdn.net/S_body/article/details/79024993)
[激活码](https://fatesinger.com/100121),得先配置host。  
[支持gbk编码文件](https://blog.csdn.net/ubuntulover/article/details/21101979)  
## Navicat
官网下载，直接安装，因为这个[激活](https://www.jianshu.com/p/f42785e55b6b)挺费劲的，所以我就没激活。  
后来到期之后，使用的[无限试用](https://blog.cat73.org/20171219/2017121901.navicat-crack/),和激活也没啥区别。
## Beyond-compare
[git配置bc为默认比对工具](http://linyehui.wikidot.com/using-beyond-compare-in-mac)  
[IDEA配置bc为默认比对工具](http://guochenglai.com/2016/06/08/mac-beyond-compare-diff-methods/)  
[Mac OS系统下Beyond Compare破解方式](https://blog.csdn.net/t_332741160/article/details/79285636)相当于是无限试用，每次删除那个文件。
## Xmind
安装的zen版本，一直试用，满足平常需要了。
## Nodejs
[Mac 下安装node.js](https://www.jianshu.com/p/f21fdbdf47df)
## hexo
[mac os下搭建hexo+github博客](https://www.jianshu.com/p/49c8168c7418)  
![mac安装hexo](mac安装hexo.png 'mac安装hexo')   
## 画图软件
Mac上没有visio，所以搜了一下，推荐亿图图示、OmniGraffle、auxre、processon等。  
后来发现一个[免费的在线画图](https://www.jianshu.com/p/e009416d6878)：[draw.io](http://draw.io)，支持中文、visio的导入导出，还不用注册，果断使用这个了。
## Axure
官网下载安装，然后找个[激活码](https://blog.csdn.net/hefeng6500/article/details/80965395)和[汉化包](https://www.jianshu.com/p/6bbddb0b201d)
## Project
Mac上类似于project的OmniPlan,并且可以打开mpp文件：  
[OmniPlan安装破解](https://www.jianshu.com/p/75e7edd4a6ad)  
[OmniPlan使用说明](https://sspai.com/post/33206)  
[OmniPlan导入导出为project](http://www.zhichangxueshe.com/1556)  
# 参考文档
- [Mac基础知识官网](https://support.apple.com/zh-cn/explore/new-to-mac)  

---
- [Mac使用](http://www.pc6.com/mac/course/)  
- [Mac电脑小白-知乎](https://www.zhihu.com/question/33887923)
