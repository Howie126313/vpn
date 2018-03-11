作为一个程序员，科学上网总是需要的。毕竟有个梗，百度的程序员都在用谷歌查东西。一下的教程是使用谷歌云注册时，会免费赠送 $300 的体验金，有效期一年。这也意味着你可以免费用一年，而且看 youtobe 上4K 2160P 画质无卡顿。

##Get Started:
首先，额~~你现在就能科学上网，有一个 google 账号。最最最重要要有一张信用卡!!!（visa、jcb、美国运通）,没有就没办法了。
XX云网址：https://cloud.google.com/

登录你的账户，你会看到下面的免费试用
![](http://upload-images.jianshu.io/upload_images/8610628-db2e81a4268faa1c.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

会看到一下页面，上面已经提到你将获得免费获得300美元的赠金。然后按照提示填写相关信息就可以。
![](http://upload-images.jianshu.io/upload_images/8610628-5ba7caa65c14c6e3.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

ok,完成以上步骤之后。点击进入控制台，进入 Compute Engine  选择 VM 实例。
![](http://upload-images.jianshu.io/upload_images/8610628-7dad1384e30a0f6a.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
点击创建实例，新建一个服务器实例。
地区方面推荐选择 asia-east1-c ，这个服务器应该是台湾的服务器。对大陆比较友好，网速比较快。当然不是一定，你可以自己去挨个试一下。启动磁盘点击更改选择CentOS6/7 都可以。机器类型选择最便宜的就好，我们只是用来科学上网足够了。如果是自己选的地区，最好测一下试试，要不弄完太慢还要重新再来。
测试网站： https://www.ipip.net/

![](http://upload-images.jianshu.io/upload_images/8610628-e11562d5c91afcec.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)


创建成功后，会出现一个实例。显示如下：![](http://upload-images.jianshu.io/upload_images/8610628-08abac91f0900488.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

ok,到这里为止，我们已经有了一台自己的服务器，现在要做的就行在这个服务器上安装 ss 。可以自己配置，也可以上网去找一些写好的脚本去执行就好了。
这个是我常用的一个：https://teddysun.com/342.html/comment-page-23

点击外部 IP 后的 SSH 远程登录你的服务器，你只需要在上面按顺序输入代码，脚本就会自动执行安装。
![](http://upload-images.jianshu.io/upload_images/8610628-7b33777733470b9e.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
按顺序粘贴，命令执行。如果出现权限问题，在命令前加上 sudo 执行。
安装成功后，记得执行启动命令```/etc/init.d/shadowsocks start```,开启 ss。服务期端的 ss 就安装完成了。

来搞定自己电脑端的代理，电脑端设置代理软件填上相应的 IP 、端口和加密方式及密码就可以实现。下面以 mac 上的 ss 为例。
![](http://upload-images.jianshu.io/upload_images/8610628-b0fd877f3babd8e0.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
点击服务器设置，进行相关设置。添加完成后点击确定，点击启用 shadowsocks 。
这样就搞定了，去享受一下4K画质的外网视频吧。
![](http://upload-images.jianshu.io/upload_images/8610628-831b98ada81afa1a.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

以下为电脑端 ss 的下载链接：
os：链接:https://pan.baidu.com/s/1lvsaQQp4ah936bF4tLUp2w  密码:v4k5
windows：链接:https://pan.baidu.com/s/1FlmtJsC5rqITaN4TpzIQzQ  密码:cvk5