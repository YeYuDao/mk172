# mk172
Scrapy打造搜索引擎（新版） 畅销3年的Python分布式爬虫课程
Scrapy打造搜索引擎（新版） 畅销3年的Python分布式爬虫课程
[![下载地址](https://img.mukewang.com/szimg/5fcdf3450987db5105400304.jpg "下载地址")](https://51xueit.vip "下载地址")
[下载地址](https://51xueit.vip "下载地址")
### 第1章 课程介绍 

#### 介绍课程目标、通过课程能学习到的内容、和系统开发前需要具备的知识
1-1 python分布式爬虫打造搜索引擎简介 (07:23)


### 第2章 windows下搭建开发环境

#### 介绍项目开发需要安装的开发软件、 python虚拟virtualenv和 virtualenvwrapper的安装和使用、 最后介绍pycharm和navicat的简单使用
2-1 pycharm的安装和简单使用 (09:07)

2-2 mysql和navicat的安装和使用 (16:20)

2-3 windows和linux下安装python2和python3 (06:49)

2-4 虚拟环境的安装和配置 (30:53)


### 第3章 爬虫基础知识回顾

#### 介绍爬虫开发中需要用到的基础知识包括爬虫能做什么，正则表达式，深度优先和广度优先的算法及实现、爬虫url去重的策略、彻底弄清楚unicode和utf8编码的区别和应用。
3-1 技术选型 爬虫能做什么 (09:50)

3-2 正则表达式-1 (18:31)

3-3 正则表达式-2 (19:04)

3-4 正则表达式-3 (20:16)

3-5 深度优先和广度优先原理 (25:15)

3-6 url去重方法 (07:44)

3-7 彻底搞清楚unicode和utf8编码 (18:31)


### 第4章 新： scrapy爬取知名技术文章网站

#### 搭建scrapy的开发环境，本章介绍scrapy的常用命令以及工程目录结构分析，本章中也会详细的讲解xpath和css选择器的使用。然后通过scrapy提供的spider完成所有文章的爬取。然后详细讲解item以及item loader方式完成具体字段的提取后使用scrapy提供的pipeline分别将数据保存到json文件以及mysql数据库中。...
4-1 重录说明(很重要！！！) (04:47)

4-2 scrapy安装和配置 (30:30)

4-3 需求分析 (13:53)

4-4 pycharm中调试scrapy源码 (10:13)

4-5 xpath基础语法 (19:02)

4-6 xpath提取元素 (28:48)

4-7 css选择器 (17:54)

4-8 . cnblogs模拟登录(新增内容) (22:23)

4-9 编写spider完成抓取过程 - 1 (19:38)

4-10 编写spider完成抓取过程 - 2 (20:47)

4-11 scrapy中为什么要使用yield (09:49)

4-12 提取详情页信息 (23:16)

4-13 提取详情页信息 (18:13)

4-14 items的定义和使用 - 1 (16:21)

4-15 items的定义和使用 - 2 (13:30)

4-16 scrapy配置图片下载 (18:20)

4-17 items数据写入到json文件中 (09:27)

4-18 mysql表结构设计 (13:21)

4-19 pipeline数据库保存 (20:16)

4-20 异步方式入库mysql (12:37)

4-21 数据插入主键冲突的解决方法 (04:40)

4-22 itemloader提取信息 (21:41)

4-23 itemloader提取信息 (19:06)

4-24 大规模抓取图片下载出错的问题 (12:45)

4-25 有没有方法可以比较准确的解析出 title 和正文内容


### 第5章 网站模拟登陆和滑动验证码识别（2021.6月更新）

#### 本章节我们将解决两个问题：1. 防止selenium被网站识别出来 2. 滑动验证码识别，滑动验证码识别我们将采用opencv识别和机器学习平台识别。 滑动验证码作为当前最流行的验证码，识别滑动验证码将使得我们能解决绝大部分网站的模拟登陆...
5-1 session和cookie自动登录机制 (20:10)

5-2 课程如何应对网站反爬变化？ (08:03)

5-3 使用opencv识别滑动验证码的环境准备 (15:59)

5-4 opencv滑动验证码识别原理 (26:19)

5-5 滑动验证码识别集成到scrapy中 (10:02)

5-6 通过机器学习平台训练滑动验证码模型 (15:23)

5-7 发布训练模型并远程调用识别 (26:53)


### 第6章 scrapy爬取知名问答网站

#### 通过上一章节的学习，本章节我们将对具体的网站进行需求分析、表结构设计等、本章详细的分析了网站的网络请求并分别分析出了网站问题回答的api请求接口并将数据提取出来后保存到mysql中
6-1 知乎分析以及数据表设计1 (15:17)

6-2 知乎分析以及数据表设计 - 2 (13:35)

6-3 item loder方式提取question - 1 (14:57)

6-4 item loder方式提取question - 2 (15:20)

6-5 item loder方式提取question - 3 (06:45)

6-6 知乎spider爬虫逻辑的实现以及answer的提取 - 1 (15:54)

6-7 知乎spider爬虫逻辑的实现以及answer的提取 - 2 (17:04)

6-8 保存数据到mysql中 -1 (17:27)

6-9 保存数据到mysql中 -2 (17:22)

6-10 保存数据到mysql中 -3 (16:09)

6-11 如何将数据的保存和抓取独立出来？


### 第7章 通过CrawlSpider对招聘网站进行整站爬取

#### 本章完成招聘网站职位的数据表结构设计，并通过link extractor和rule的形式并配置CrawlSpider完成招聘网站所有职位的爬取，本章也会从源码的角度来分析CrawlSpider让大家对CrawlSpider有深入的理解。
7-1 数据表结构设计 (15:33)

7-2 CrawlSpider源码分析-新建CrawlSpider与settings配置 (12:50)

7-3 CrawlSpider源码分析 (25:29)

7-4 Rule和LinkExtractor使用 (14:28)

7-5 网页302之后的模拟登录和cookie传递(网站需要登录时学习本视频教程) (32:11)

7-6 item loader方式解析职位 (24:46)

7-7 职位数据入库-1 (19:01)

7-8 职位信息入库-2 (11:19)

7-9 网站反爬突破 (10:58)


### 第8章 Scrapy突破反爬虫的限制 

#### 本章会从爬虫和反爬虫的斗争过程开始讲解，然后讲解scrapy的原理，然后通过随机切换user-agent和设置scrapy的ip代理的方式完成突破反爬虫的各种限制。本章也会详细介绍httpresponse和httprequest来详细的分析scrapy的功能，最后会通过云打码平台来完成在线验证码识别以及禁用cookie和访问频率来降低爬虫被屏蔽的可能性。...
8-1 爬虫和反爬的对抗过程以及策略 (20:17)

8-2 scrapy架构源码分析 (10:45)

8-3 Requests和Response介绍 (10:18)

8-4 通过downloadmiddleware随机更换user-agent-1 (17:00)

8-5 通过downloadmiddleware随机更换user-agent - 2 (17:13)

8-6 scrapy实现ip代理池 - 1 (16:51)

8-7 scrapy实现ip代理池 - 2 (17:39)

8-8 scrapy实现ip代理池 - 3 (18:46)

8-9 云打码实现验证码识别 (22:37)

8-10 cookie禁用、自动限速、自定义spider的settings (07:22)


### 第9章 scrapy进阶开发

#### 本章将讲解scrapy的更多高级特性，这些高级特性包括通过selenium和phantomjs实现动态网站数据的爬取以及将这二者集成到scrapy中、scrapy信号、自定义中间件、暂停和启动scrapy爬虫、scrapy的核心api、scrapy的telnet、scrapy的web service和scrapy的log配置和email发送等。 这些特性使得我们不仅只是可以通过scrapy来完成...
9-1 selenium动态网页请求与模拟登录知乎 (21:24)

9-2 selenium模拟登录微博， 模拟鼠标下拉 (11:06)

9-3 chromedriver不加载图片、phantomjs获取动态网页 (09:59)

9-4 selenium集成到scrapy中 (19:43)

9-5 其余动态网页获取技术介绍-chrome无界面运行、scrapy-splash、selenium-grid, splinter (07:50)

9-6 scrapy的暂停与重启 (12:58)

9-7 scrapy url去重原理 (05:45)

9-8 scrapy telnet服务 (07:37)

9-9 spider middleware 详解 (15:25)

9-10 scrapy的数据收集 (13:44)

9-11 scrapy信号详解 (13:05)

9-12 scrapy扩展开发 (13:16)


### 第10章 scrapy-redis分布式爬虫

#### Scrapy-redis分布式爬虫的使用以及scrapy-redis的分布式爬虫的源码分析， 让大家可以根据自己的需求来修改源码以满足自己的需求。最后也会讲解如何将bloomfilter集成到scrapy-redis中。
10-1 分布式爬虫要点 (08:39)

10-2 redis基础知识 - 1 (20:31)

10-3 redis基础知识 - 2 (15:58)

10-4 scrapy-redis编写分布式爬虫代码 (21:06)

10-5 scrapy源码解析-connection.py、defaults.py- (11:05)

10-6 scrapy-redis源码剖析-dupefilter.py- (05:29)

10-7 scrapy-redis源码剖析- pipelines.py、 queue.py- (10:41)

10-8 scrapy-redis源码分析- scheduler.py、spider.py- (11:52)

10-9 集成bloomfilter到scrapy-redis中 (19:30)


### 第11章 cookie池系统设计和实现

#### 为了让爬取代码和解析代码不会受到模拟登录的影响，将模拟登录独立成独立的服务变得很重要，cookie池就是为了解决这类问题而生，多账号登录管理、如何让网站接入变得容易都会是cookie池需要解决的问题。本章节就重点解决cookie池设计和开发的细节问题。 ...
11-1 什么是cookie池？ (11:27)

11-2 cookie池系统设计 (09:23)

11-3 实现cookie池-1 (10:12)

11-4 实现cookie池-2 (12:39)

11-5 改造login方法 - 1 (09:58)

11-6 改造login方法 - 2 (09:36)

11-7 改造login方法-3 (08:43)

11-8 改造login方法-4 (10:37)

11-9 通过抽象基类实现网站轻松接入 (15:00)

11-10 实现检测网站cookie是否有效 (08:06)

11-11 如何选择redis的数据结构来保存cookie (10:59)

11-12 cookie管理器的实现 (22:10)

11-13 启动cookie池服务 (12:35)

11-14 将cookie集成到爬虫项目中 (15:34)

11-15 cookie架构设计改进意见 (07:36)


### 第12章 各种验证码的识别

#### 滑动验证码变得越来越流行，如何解决滑动验证码就成为了模拟登录中重要的一个环节，本章节聚焦解决滑动验证码的各种细节问题。
12-1 滑动验证码的识别思路 (15:17)

12-2 验证码截屏-1 (11:42)

12-3 验证码截屏-2 (14:03)

12-4 计算出滑动的距离 (17:37)

12-5 计算滑动轨迹 (18:00)


### 第13章 增量抓取

#### 增量抓取和数据更新是爬虫运行中经常遇到的问题，比如当前爬虫正在运行，但是新增的数据如何及时发现，如何将后来的url先进行抓取，如何发现新数据都是实际开发中经常原道的问题，本章节通过修改scrapy-redis的源码以最小的代价来解决上诉问题，通过本章节的学习我们将会更加懂得如何去控制爬虫的运行环节。...
13-1 增量爬虫需要解决的问题 (09:36)

13-2 通过修改scrapy-redis完成增量抓取 -1 (16:11)

13-3 通过修改scrapy-redis完成增量抓取-2 (14:13)

13-4 爬虫数据更新 (09:23)


### 第14章 elasticsearch搜索引擎的使用

#### 本章将讲解elasticsearch的安装和使用，将讲解elasticsearch的基本概念的介绍以及api的使用。本章也会讲解搜索引擎的原理并讲解elasticsearch-dsl的使用，最后讲解如何通过scrapy的pipeline将数据保存到elasticsearch中。
14-1 elasticsearch介绍 (18:21)

14-2 elasticsearch安装 (13:24)

14-3 elasticsearch-head插件以及kibana的安装 (24:09)

14-4 elasticsearch的基本概念 (12:15)

14-5 倒排索引 (11:24)

14-6 elasticsearch 基本的索引和文档CRUD操作 (18:44)

14-7 elasticsearch的mget和bulk批量操作 (12:36)

14-8 elasticsearch的mapping映射管理 (21:03)

14-9 elasticsearch的简单查询 - 1 (14:56)

14-10 elasticsearch的简单查询 - 2 (11:12)

14-11 elasticsearch的bool组合查询 (22:58)

14-12 scrapy写入数据到elasticsearch中 - 1 (14:16)

14-13 scrapy写入数据到elasticsearch中 - 2 (11:15)


### 第15章 django搭建搜索网站

#### 本章讲解如何通过django快速搭建搜索网站， 本章也会讲解如何完成django与elasticsearch的搜索查询交互。
15-1 es完成搜索建议-搜索建议字段保存 - 1 (13:45)

15-2 es完成搜索建议-搜索建议字段保存 - 2 (13:34)

15-3 django实现elasticsearch的搜索建议 - 1 (19:57)

15-4 django实现elasticsearch的搜索建议 - 2 (18:15)

15-5 django实现elasticsearch的搜索功能 -1 (14:06)

15-6 django实现elasticsearch的搜索功能 -2 (13:14)

15-7 django实现搜索结果分页 (09:12)

15-8 搜索记录、热门搜索功能实现 - 1 (14:34)

15-9 搜索记录、热门搜索功能实现 - 2 (14:04)


### 第16章 scrapyd部署scrapy爬虫

#### 本章主要通过scrapyd完成对scrapy爬虫的线上部署。
16-1 scrapyd部署scrapy项目 (24:39)


### 第17章 课程总结

#### 重新梳理一遍系统开发的整个过程， 让同学对系统和开发过程有一个更加直观的理解
17-1 课程总结 (05:55)

17-2 【讨论题】你认为什么是 JS 逆向？

17-3 如何将 nodejs 服务集成进来呢？

17-4 【讨论题】字体反爬应该如何解析？


[下载地址](https://51xueit.vip "下载地址")
