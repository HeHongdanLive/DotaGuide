# DotaGuide


Android开发实战之Dota攻略 
发表于 2018-02-26   |   分类于 Android   |   阅读 322 

##前言
平时打Dota时经常会随机英雄玩，碰到不熟悉的英雄就尴尬了，需要从游戏切回桌面百度查询该英雄的出装和加点攻略等，无奈来回切不方便，所以下了第三方Dota攻略APP在手机上查看，方便是方便，就是第三方APP广告太多，而且布局排列都不太习惯，所以就自己做了一款Dota攻略APP。

##数据从哪获取？
从第三方网站爬取数据，使用Jsoup解析数据。考虑到Dota英雄和装备信息等会不定时更新，所以利用第三方网站实时获取数据是最佳方案。

##APP界面设计
Dota攻略的核心功能就是提供英雄的出装，加点以及技能信息，据此设计以下四级页面：
一级界面–英雄分类（分为力量，敏捷和智力）
二级界面–英雄列表（不同类别下分别有若干英雄）
三级界面–英雄详情（包括加点，出装及技能介绍等）
四级界面–装备信息（包括装备的功能，合成配方等）

##APP涉及技术
网络请求：OKHttp + Retrofit + RxJava
图片加载：Glide
数据解析：Jsoup
项目地址：https://github.com/ckj375/DotaGuide

APP效果图：  
<img src="https://github.com/ckj375/img-folder/blob/master/dotaguide/dotaguide1.jpg" height="400" width="225"/>
<img src="https://github.com/ckj375/img-folder/blob/master/dotaguide/dotaguide2.jpg" height="400" width="225"/>
<img src="https://github.com/ckj375/img-folder/blob/master/dotaguide/dotaguide3.jpg" height="400" width="225"/>  

APP下载地址：https://pan.baidu.com/s/1c4i2YT6
