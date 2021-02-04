# schedule-jd
完成 京东每日签到任务

### 背景

最开始了解到相关自动签到相关，是来自朋友推荐的一款软件 Quantumult X 。

使用这款软件在结合社区**各路大神**提供的脚本可以解锁非常多神奇的功能，自动签到便是其中的一个。

![](https://gitee.com/xiaoxiunique/picgo-image/raw/master/atips/20201231173557.png)



不过这款软件使用起来 颇为复杂，不太适合我，还需要科学上网，各种各种。太麻烦了。

![心情复杂 - 一组渣画质小表情_小表情_高糊_怼人表情表情](http://wx3.sinaimg.cn/bmiddle/006fbYi5gy1ff4kschlzsj301p01tgle.jpg)

随后将 大神的脚本 引入 Github 利用 Actions 的功能也能实现相同的功能。

这里使用的是 **NobyDa大佬的 “京东多合一签到脚本”**



### 获取 Cookie

电脑打网页开 https://bean.m.jd.com ，打开调试模式（F12），刷新页面，然后 复制 Cookie

![](https://gitee.com/xiaoxiunique/picgo-image/raw/master/atips/20201231175239.png)







### 添加 Secret 

fork [项目](https://github.com/xiaoxiunique/schedule-jd)

将 复制的 Cookie 添加到 Secret 中

![](https://gitee.com/xiaoxiunique/picgo-image/raw/master/atips/20201231174929.png)



### 触发每日自动运行

随便修改 Readme 触发自动运行





随后会在每天10 点运行 次项目 获取每日京豆


## 经过测试发现，基本上设置一次 Cookie 可以管 一个月左右
