# fluffy-pancake

## Contents

  - [HBase](#HBase)
  - [Opentsdb](#Opentsdb)
  - [Phoenix](#Phoenix)
  - [GAN](#GAN)
  - [Reinforcement Learning](#Reinforcement-Learning)
  - [语音处理（SoX）](#语音处理SoX)

  - [Jupyter](#Jupyter)
  - [Nodejs](#Nodejs)
  - [Webhook](#Webhook)
  - [shell](#shell)
  - [正则](#正则)
  - [OAuth](#OAuth)
  - [Puppet运维](#Puppet运维)
  - [Make](#Make)
  - [Git](#Git)
  - [flask应用](#flask应用)
  - [Linux](#Linux)
  - [Serverless](#Serverless)

  - [Wordpress](#Wordpress)
  - [博客技术](#博客技术)

  - [SQLite](#SQLite)
  - [Mysql](#Mysql)
  - [数据库相关](#数据库相关)
  - [SQL Client](#SQL-Client)
  - [C](#C)
  - [排序](#排序)
  - [设计模式](#设计模式)

  - [The Architecture of Open Source Applications](#The-Architecture-of-Open-Source-Applications)
  - [头像服务商（gravatar）](#头像服务商gravatar)
  - [翻译词表](#翻译词表)
  - [Markdown](#Markdown)
  - [其他](#其他)
  - [Progress](#Progress)

## GAN
https://people.eecs.berkeley.edu/~tinghuiz/projects/pix2pix/datasets/
https://people.eecs.berkeley.edu/~taesung_park/CycleGAN/datasets/

DCGAN
https://www.kaggle.com/jessicali9530/celeba-dataset/home

## Jupyter
jupyter增加多版本python内核
https://blog.csdn.net/flyer_tang/article/details/81305087

python -m ipykernel install --name ml

%matplotlib inline

https://developers.google.com/machine-learning/crash-course/glossary#activation_function

tf.function

## 语音处理（SoX）
http://sox.sourceforge.net/
Welcome to the home of SoX, the Swiss Army knife of sound processing programs.
SoX is a cross-platform (Windows, Linux, MacOS X, etc.) command line utility that can convert various formats of computer audio files in to other formats. 
It can also apply various effects to these sound files, and, as an added bonus, SoX can play and record audio files on most platforms.

## Nodejs
npm config set registry https://registry.npm.taobao.org --global
npm config set disturl https://npm.taobao.org/dist --global

yarn config set registry https://registry.npm.taobao.org --global
yarn config set disturl https://npm.taobao.org/dist --global

## Webhook
Webhook的理解
https://blog.csdn.net/starter_____/article/details/79255536
Webhook调试
调试webhook有时很复杂，因为webhook原则来说是异步的。你首先要解发他，然后等待，接着检查是否有响应。这是枯燥并且相当低效。幸运的是还有其他方法：

1、明白webhook能提供什么，使用如RequestBin之类的工具收集webhook的请求；

2、用cURL或者Postman来模拟请求；

3、用ngrok这样的工具测试你的代码；

4、用Runscope工具来查看整个流程

webhook小试水（无需外网服务器）
https://www.jianshu.com/p/55209f1031e8

Webhook到底是个啥？
https://segmentfault.com/a/1190000015437514?utm_source=tag-newest

## shell
shell编程——if语句 if -z -n -f -eq -ne -lt
https://www.cnblogs.com/myitm/archive/2012/07/05/2577416.html

Linux运维常用shell脚本之系统管理实例
https://blog.csdn.net/bbwangj/article/details/78089690

## 正则
正则：
https://regex101.com/

## Reinforcement Learning
Introducing Google Research Football: A Novel Reinforcement Learning Environment
https://ai.googleblog.com/2019/06/introducing-google-research-football.html

alphago
https://deepmind.com/research/alphago/

Dota 2 world
https://openai.com/five/

AlphaStar
https://deepmind.com/blog/alphastar-mastering-real-time-strategy-game-starcraft-ii/

## Serverless
当我们聊Serverless时你应该知道这些
https://www.jianshu.com/p/c847bc77e027

什么是Serverless无服务器架构？
https://www.jdon.com/soa/serverless.html

Serverless 掀起新的前端技术变革
https://zhuanlan.zhihu.com/p/65914436?hmsr=toutiao.io&utm_medium=toutiao.io&utm_source=toutiao.io


## The Architecture of Open Source Applications
http://aosabook.org/en/index.html

开源软件架构
http://www.ituring.com.cn/book/1143

开源软件架构（看云文档）
https://www.kancloud.cn/kancloud/open-source-architecture

开源软件架构
https://www.w3cschool.cn/open_source_architecture/?

10个不到500行代码的超牛Python 练手项目（技术清单系列）
https://zhuanlan.zhihu.com/p/52881791

## 翻译词表
電腦名詞譯名
http://www.iicm.org.tw/term/

English to Chinese translation glossaries
https://www.proz.com/glossary-translations/english-to-chinese-glossaries

## OAuth
理解OAuth 2.0
https://www.kancloud.cn/kancloud/oauth_2_0#/catalog

## Puppet运维
Puppet运维实战
https://www.kancloud.cn/kancloud/puppet#/catalog

## Make
Make 命令教程
https://www.kancloud.cn/kancloud/make-command#/catalog

## Git
沉浸式学 Git
https://www.kancloud.cn/kancloud/igit#/catalog

Git LFS的使用
https://www.jianshu.com/p/493b81544f80

Git LFS 操作指南
https://zzz.buzz/zh/2016/04/19/the-guide-to-git-lfs/

## flask应用
<script src="//cdnjs.cloudflare.com/ajax/libs/moment.js/2.10.3/moment-with-locales.min.js"></script>

<script type="text/javascript" src="//cdnjs.cloudflare.com/ajax/libs/pagedown/1.0/Markdown.Converter.min.js"></script>

<script type="text/javascript" src="//cdnjs.cloudflare.com/ajax/libs/pagedown/1.0/Markdown.Sanitizer.min.js"></script>

## 头像服务商(gravatar)
https://secure.gravatar.com/avatar

## Phoenix
<modules>
    <module>phoenix-core</module>
    <module>phoenix-pherf</module>
    <module>phoenix-client</module>
    <module>phoenix-server</module>
    <module>phoenix-assembly</module>
    <module>phoenix-tracing-webapp</module>
  </modules>

使用Phoenix连接Hbase
https://blog.csdn.net/u010429286/article/details/70054232

Apache Phoenix介绍（SQL on HBase）
https://www.jianshu.com/p/d862337247b1

浅谈Phoenix在HBase中的应用
https://www.cnblogs.com/ballwql/p/8371234.html

Apache Phoenix: Use Cases and New Features
https://www.youtube.com/watch?v=-qCCMuWYpls

都是 HBase 上的 SQL 引擎，Kylin 和 Phoenix 有什么不同？
https://juejin.im/post/5c6d1667f265da2dc13c7bcc	

Phoenix使用指南
https://blog.csdn.net/Haiyang_Duan/article/details/60746963

整合phoenix4.6.0-HBase-1.0到cdh5..4.7 编译phoenix4.6源码 RegionServer 宕机
https://www.cnblogs.com/zhanggl/p/5110265.html

一、Phoenix是构建在HBase之上的关系型数据库层，作为内嵌的客户端JDBC驱动用以对HBase中的数据进行低延迟访问。
Phoenix会将用户编写的sql查询编译为一系列的scan操作，最终产生通用的JDBC结果集返回给客户端。
数据表的元数据存储在HBase的表中被会标记版本号，所以进行查询的时候会自动选择正确的schema。
直接使用HBase的API，结合协处理器（coprocessor）和自定义的过滤器的话，小范围的查询在毫秒级响应，千万数据的话响应速度为秒级。

二、特性
1.支持用户自定义函数
2.支持分页查询
3.在同一张底层HBase物理表上创建多个虚拟表(视图)
4.加载CSV数据到Phoenix表：
  通过psql命令以单线程的方式加载，数据量少的情况下适用。
  基于MapReduce的bulk load工具，适用于数据量大的情况

三、可以使用图形化客户端SQuirrel

## SQL Client
SQuirrel SQL Client是一个用Java编写的开源数据库工具，可以用来查看/编辑数据库的内容、发出SQL 命令。它可以支持兼容JDBC的数据库，可以使用统一的界面处理不同的数据库，支持插件和多国语言。
https://blog.csdn.net/seashouwang/article/details/82840514

http://squirrel-sql.sourceforge.net/index.php?page=screenshots

## Wordpress
技术角度wordpress结构优缺点分析
https://www.cnblogs.com/chengmo/archive/2013/05/27/wordpress.html

Wordpress安全架构分析
https://juejin.im/entry/59f1a8eb6fb9a0452845b78e

WordPress工作原理之程序文件执行顺序（传说中的架构源码分析）
https://www.toolmao.com/wordpress-source-analysis

使用 WordPress 做为 Web 应用开发框架的优势
https://www.wpzhiku.com/the-advantage-of-use-wordpress-as-app-freamwork/

WordPress建站心得（二）网站架构设计
https://www.alexyang.me/2013/11/25/wordpress%E5%BB%BA%E7%AB%99%E5%BF%83%E5%BE%97%EF%BC%88%E4%BA%8C%EF%BC%89%E7%BD%91%E7%AB%99%E6%9E%B6%E6%9E%84%E8%AE%BE%E8%AE%A1.html

WordPress源码设计解读
https://blog.csdn.net/weiganyi/article/details/14451807

WordPress 默认评论结构图 (2.7.x, 2.8.x, 2.9.x)
https://zww.me/archives/25155

深入理解 WordPress 数据库结构以及数据表之间的关系
https://www.wpzhiku.com/understanding-working-data-wordpress/

配置 Wordpress 数据库
https://blog.csdn.net/yitian20000/article/details/5903947

了解wordpress 3.0 数据库表结构（2015年）
https://segmentfault.com/a/1190000004078630

WordPress 自动初始化数据库
http://www.voidcn.com/article/p-pgrunwge-bxh.html


## 博客技术
jekyll	ruby
hexo	nodejs	(gitalk issue)
wordpress php	mysql

## SQLite
SQLite 教程
https://cloud.tencent.com/developer/doc/1228 

sqlite3 - SQLite数据库的DB-API 2.0接口
https://www.docs4dev.com/docs/zh/python/3.7.2rc1/all/whatsnew-index.html#python%E7%9A%84%E6%96%B0%E5%8A%9F%E8%83%BD

学习sqlite
https://www.zhihu.com/question/22819578

开放源码嵌入式数据库 SQLite 简介
https://www.ibm.com/developerworks/cn/opensource/os-sqlite/index.html

深入理解 sqlite
https://www.kancloud.cn/kangdandan/sqlite/64349

SQlite源码分析
https://huili.github.io/execuing_of_vdbec/README.html

Inside SQLite
SQLite Database System Design and Implementation (Second Edition, Version 1)

Let's Build a Simple Database
https://cstack.github.io/db_tutorial/parts/part1.html

50 Top Projects of SQL on GitHub in 2018
https://medium.com/issuehunt/50-top-projects-of-sql-on-github-in-2018-aabe0950a43a

SQLite分析之WAL机制
https://blog.csdn.net/zearot/article/details/51039593

SQLite学习笔记(九)&&pager模块
https://www.cnblogs.com/cchust/p/4966790.html

Why SQLite Does Not Use Git (sqlite.org)
https://news.ycombinator.com/item?id=16806114&p=3
https://sqlite.org/whynotgit.html

Fossil Versus Git
https://fossil-scm.org/fossil/doc/trunk/www/fossil-v-git.wiki

## Linux
The Linux Programming Interface
http://man7.org/index.html

## Mysql
too many connections 解决方法
https://blog.csdn.net/qq_41576459/article/details/85936486

## 数据库相关
Good understanding of data structures and algorithm. Especially data structures such as B-tree, Linked list, Hashmaps, etc.
Some understanding of computer architecture. How to read-write into a disk, how paging and caching works.
Theoretical computers such as Finite Automata, Context Free Grammer and some Regular Expression knowledge.

首先，不要将数据库与存储引擎混淆。MySQL和Postgres是数据库。以下是一些着名的存储引擎：

Berkeley DB GDBM LevelDB LMDB RocksDB京都内阁

　数据库将SQL解析为引擎字节码。另一方面，存储引擎分析字节码并访问文件。


B树和LSM（日志结构合并）
　今天的两个主要存储引擎是B-Tree和LSM。LSM可能是新的趋势，但情况确实如此吗？

B树=慢与坏
LSM =快速且良好


## C
Project devpkg
https://github.com/zedshaw/learn-c-the-hard-way-lectures/blob/master/ex41/lecture.md

Ring Buffer
https://github.com/zedshaw/learn-c-the-hard-way-lectures/blob/master/ex44/lecture.md

A Fast URL Router
https://github.com/zedshaw/learn-c-the-hard-way-lectures/blob/master/ex47/lecture.md

Routing the Statistics
https://github.com/zedshaw/learn-c-the-hard-way-lectures/blob/master/ex50b/lecture.md

## 排序
def SelectSort(lst):
    n=len(lst)
    if n<=1:
        return lst
    for i in range(0,n-1):
        minIndex=i
        for j in range(i+1,n):          #比较一遍，记录索引不交换
            if lst[j]<lst[minIndex]:
                minIndex=j
        if minIndex!=i:                     #按索引交换
            (lst[minIndex],lst[i])=(lst[i],lst[minIndex])
## 设计模式
单例模式(五种实现单利方式)
https://blog.csdn.net/July_whj/article/details/81586809

## HBase
阅读HBase源码的正确姿势建议
https://mp.weixin.qq.com/s/x4QV-wEvAkJXMGp8kd0yBQ

## Opentsdb
I separated the reading and writing TSD and also balanced the region 
servers. 

So for the highest throughput, here are some things to do:
Pre-assign UIDs to all of your metrics, tag names and values (if you're starting with a fresh HBase table)
Make sure the UID caches are full, i.e. the TSD has been running and written at least one data point for every metric and tag name/value
Pre-split the regions: https://gist.github.com/johann8384/5544290
Move to an HBase cluster

I would think huge queries is related to the size f queries to fetch dat, not write data. You are using separate instances for reading correct?

You may benefit from the "wo" mode, it loads less of the internal rpc plugins.

The cache is mostly where it writes out data for gnuplot and where the gnuplot graphs are written, iirc.

What do your rpc related metrics look like?

Your write nodes are colo located on your region servers?

What does your query load look like during this time?

I assume your query nodes are "ro" mode?

https://groups.google.com/forum/#!searchin/opentsdb/Slow/opentsdb/S3WLQl7kQ_U/m4vjsSJcAQAJ

find / -name '*opentsdb*'
opentsdb：
①通过summoner定时任务，每天把昨日数据按1m粒度进行预聚合写入新的metric
②昨日、上周昨日、上周今日在预聚合数据的基础上进行实时聚合
③今日数据按照1h为单位，多线程实时聚合
④缓存今日已过小时维度数据（可选本地缓存、redis缓存）


http://hbase.group/article/122

Opentsdb数据聚合超时优化
https://www.jianshu.com/p/c2727ac399c9

API Endpoints
/s
/api/aggregators
/api/annotation
/api/config
/api/dropcaches
/api/put
/api/rollup
/api/histogram
/api/query
/api/search
/api/serializers
/api/stats
/api/suggest
/api/tree
/api/uid
/api/version

OpenTSDB 查询优化可以从使用端和服务端两个方面着手：

使用端优化：
合理拆分 Metric，这类似于关系型数据库的分表，将相关性不强的属性拆开到多个 Metric 中，减少时间线个数，查询时自然会有所改进。
注意 Tag 顺序，要将经常指定维度往前排，最明显的就是用户 ID，查询数据时指定用户 ID 进行范围查询，Hbase Scan  的数量就会少很多。
并发查优化，OpenTSDB  默认是一个小时数据存一行，那么可以按小时把请求拆分，如查最近二十四小时就拆成二十四个请求进行查询，整体的响应时间就会有所改进。

服务端优化：
预集合，先把慢查询捞出来，提前去执行查询。查询之后，把结果存储到另一个地方。预集合可以由使用方或服务端实现。
	服务端实现对使用方更友好，正如 InfluxDB 的 Continuous Queries 功能。
降精度，OpenTSDB 默认是每一秒存一个数据，假设只要一分钟，是不是可以每一分钟只记一个数据，那样数据量就会变成原来的六十分之一。
	但是要注意降精度后，使用端要将这一分钟的数据先自行累加然后再发送到服务端，因为 Hbase 是默认覆盖而不进行累加。
结果缓存，这里不是指请求级别的结果缓存，而是要做到 Metric 或者时间线结果的缓存。


CLI工具、HTTP API和GnuPlot用户图形界面

1）Metric：即平时我们所说的监控项。譬如上面的CPU使用率

2）Tags：就是一些标签，在OpenTSDB里面，Tags由tagk和tagv组成，即tagk=takv。标签是用来描述Metric的，譬如上面为了标记是服务器A的CpuUsage，tags可为hostname=qatest

3）Value：一个Value表示一个metric的实际数值，譬如上面的99%

4）Timestamp：即时间戳，用来描述Value是什么时候的；譬如上面的21:00

5）Data Point：即某个Metric在某个时间点的数值。

                        Data Point包括以下部分：Metric、Tags、Value、Timestamp

                       上面描述的服务器在21:00时候的cpu使用率，就是1个DataPoint

保存到OpenTSDB的，就是无数个DataPoint。


openTSDB架构
Servers：就是服务器了，上面的C就是指Collector，可以理解为OpenTSDB的agent，通过Collector收集数据，推送数据；

TSD：TSD是对外通信的无状态的服务器，Collector可以通过TSD简单的RPC协议推送监控数据；另外TSD还提供了一个web UI页面供数据查询；另外也可以通过脚本查询监控数据，对监控数据做报警

HBase：TSD收到监控数据后，是通过AsyncHbase这个库来将数据写入到HBase；AsyncHbase是完全异步、非阻塞、线程安全的Hbase客户端，使用更少的线程、锁以及内存，可以提供更高的吞吐量，特别对于大量的写操作。


检索habse的记录首先要通过row key来定位数据行。当大量的client访问hbase集群的一个或少数几个节点，造成少数region server的读/写请求过多、负载过大，而其他region server负载却很小，就造成了“热点”现象。


Insufficient permissions (user=Administrator
grant 'Administrator','RWXCA'

Compact和Split
https://www.cnblogs.com/cenyuhai/p/3746473.html
Minor & Major Compaction的区别

1）Minor操作只用来做部分文件的合并操作以及包括minVersion=0并且设置ttl的过期版本清理，不做任何删除数据、多版本数据的清理工作。

2）Major操作是对Region下的HStore下的所有StoreFile执行合并操作，最终的结果是整理合并出一个文件。

先说一下怎么使用吧，下面分别是它们是shell命令，可以在hbase的shell里面执行。

//major compaction
major compact '表名或region名'

//minor compaction
compact '表名或region名'

## Markdown
Github 中 Markdown 锚点链接如何写
https://my.oschina.net/antsky/blog/1475173

## 其他
<details>
初始的技术栈
刚开始的时候我们把服务部署到 EC2 上。主服务是用 Node.js 写的，每次发布的时候，会合并到DynamoDB。

还有一个 node 服务器用于图片处理，调用 GraphicsMagick 来做具体的复杂的工作。另一个服务被用作 SQS 队列处理，负责后台任务。

我们的 email 使用 SES，静态资源放在 S3 上，CDN 使用 CloudFront，使用 nginx 作为反向代理。另外，使用Datadog 做监控，PagerDuty 做报警。

网站使用 TinyMCE 作为编辑器。发布之前，我们已经在使用 Closure 编译器和部分 Closure 库，不过模板用的是Handlebars。
</details>
<details>
插画交流网站[pixiv]
</details>
<details>
Photoshop，Axure，Fireworks，Illustrator、MarkMan、MindManager
</details>


## Progress

* [ ] microserver
* [ ] spider
* [ ] dl
* [ ] leon
* [ ] C
* [ ] sqlite
* [ ] Part VII
