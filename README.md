## 运维工程师进阶升级之路
![](https://mmbiz.qpic.cn/mmbiz_png/tuSaKc6SfPrAHsmIwdzwz63CDot8fQaIcuRWJ4K9VunmCXJ6zXkw4TQ8V1gDKIxibnHP1NWhU8hHyLoZxzFgeqw/0?wx_fmt=png)

## 版本信息

| 版本号 | 更新时间 | 备注 |
|-------|---------|------|
|V1.0|2019-1-20|首次发布|
|V1.0.1|2019-4-26|增加了相关的知识点|
|V2.0|2019-05-13|增加知识点，进一步完善|
|V3.0|2021-04-20|补充整个知识体系|
|V4.0|2024-1-22|完善整个知识体系并充实相关内容|

## 前言

Linux 运维工程师进阶升级之路由公众号【民工哥技术之路】作者【民工哥】编写、整理发布而成，我的故事： [民工哥的十年故事：杭漂十年，今撤霸都！](https://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247485931&idx=1&sn=b288b703a209edb677411e101fbb08af&chksm=e91b6cf7de6ce5e19304da227e701fc604f0a273ab750710de8412b13bde5bca735b79176665&scene=21#wechat_redirect)。回头看看，写公众号也有快六年的时间了，做一件事很容易，但坚持做一件事情六年应该不是件容易的事。一路走来，收获了众多读者的肯定与支持，同时在自己的知识体系建立、建全上也取得了不小的成就。在这期间，我写的书：[Linux系统运维指南](https://mp.weixin.qq.com/s/BuivnIHDedFO1CLuQnHG_w) 出版（2020年4月），同年10月，我拿到了2020年人民邮电出版社/异步社区《[最具影响力作者](https://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247501495&idx=1&sn=0eedeeb5bf2c37ae4eb385ce592cf2d1&chksm=e918a3abde6f2abd0eb687183aa8acd1fe7118d5ab0c5c7ac2fbd7925c3ae375c275bcad8d63&token=1107524505&lang=zh_CN#rd)》。除了感谢这个伟大的时代、家人、朋友，还要感谢无数支持我的读者们，谢谢你们。

其实，很多熟悉我的老读者都知道，我也算是 0 基础起步自学至今的，所以，对于自学，我也总结了一些方法，或者说分享一下我的经验：[民工哥自学方法](https://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247491161&idx=2&sn=3a12a4fdd41ab0dc9cfbc48e6c62e3f4&chksm=e91b7b45de6cf253bcf7cd5729e5963ca5f85ba1cbe3e2d61c7a9d18b359fc43887a08ee1aa0&scene=21#wechat_redirect)。对于需了解整个运维知识体系学的过程可以参考：[运维工程师进阶升级之路思维导图](https://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247485027&idx=1&sn=9849f12d63906c35aa18fab9f2e76052&chksm=e91b637fde6cea6921566f117965a1c0e258f3d12613a8fd79f534a0b3639b60572fe1e152c7&token=471976001&lang=zh_CN#rd)。

现目前整个系列文章统一入口也在公众号上，后期更多增加、完善进去的内容也会统一同步发布到公众号中，欢迎大家关注（**可扫文末二维码加关注哦**）！！

运维工程师这个岗位不同于后端开发岗位，到底运维工程师平时做什么？[老司机告诉你：正规的运维工作是什么的?](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247488821&idx=2&sn=1c53372eb6553583d95b221f78fa540c&chksm=e91b7029de6cf93f2725122f3e109288c1117aac0754f97ab77f976871f3713880da7a78a76c&scene=21#wechat_redirect)。而且这个岗位对技能要求是越来越高，不仅仅要求需要知识的深度，还要求要有一定的广度，深度就是需要不断学习运维知识体系的知识，广度就是运维岗位上下游（测试与开发）岗位的一些知识体系，至少是需要做到了解基础的掌握程度。

因此，这就对运维工程师们提出了更高的要求，**首先得有一颗不断学习的心，其次坚持的毅力是必须的，然后就是不断和实践、操作与总结，重复再重复，** 时间久了才能形成自己的一套知识体系。

正因为这些原因，才有了上面的《运维工程师打怪升级进阶成神之路》的出现，初衷很简单，就是将我的所学与所总结的学习路线分享给大家，希望对后面的爱好者、学习 Linux 运维的朋友们有所帮助、有所借鉴。以便你们更好的学习与掌握其中的知识点，然后也能更轻松的运用到企业的实际工作中去。

V 4.0 版本是在前面几个版本的基础上更加精细化了运维岗位所需的技能知识点，**更详细、更全面，几乎囊括了 Linux 系统运维岗所需的所有技能体系**（如：TCP/IP 网络协议栈、Linux 常用命令、企业常用服务与应用软件、常用工具软件、Shell 脚本编程、企业监控平台、集群运维与管理、Nginx 技术栈、MySQL、PostgreSQL、Redis、MongoDB、Elasticsearch、Git、大数据 Hadoop、Kafka、RabbitMQ、Zookeeper、Docker、Kubernetes、OpenStack、DevOps、Java大后端技术等等）。

## 基础入门篇

#### 网络基础

这是每一个IT从业者必备的基础中的基础，比如：TCP/IP协议、路由基础这些[必备的 6 大计算机网络基础知识点](https://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247529511&idx=1&sn=9b1f3abfdf18e9cf24b31eccc063fdfe&chksm=e918113bde6f982d303d6a3d47235fd17f3e7ce241e816b39c0b47896791f498c54281e22496&token=1107524505&lang=zh_CN#rd)！是一定要熟悉与掌握的，否则无法展开后面的系统学习的。下面一张比较全的计算网络基础的学习思维导图：
![](https://files.mdnice.com/user/4435/f9a88b78-7707-42ab-ad8b-b8177740aa40.png)
如果你是有此方面基础的可不必学习了，如果是没有网络基础的，建议你去看一看我[公众号](https://mp.weixin.qq.com/mp/homepage?__biz=MzI0MDQ4MTM5NQ==&hid=8&sn=1db566bed001a8db6d9927540ccc2156&scene=25#wechat_redirect)上很早之前写过的一些关于[网络](https://mp.weixin.qq.com/mp/homepage?__biz=MzI0MDQ4MTM5NQ==&hid=11&sn=34e1e7ed1b2af3d38e44705424ad32d2)方面的文章，这样也可以很快的熟悉这方面的知识点。

#### 系统基础

![](https://files.mdnice.com/user/4435/4e25e686-f495-4823-95b8-2ba753223aab.png)

首先就是系统的安装与基础配置：[Centos7安装教程](https://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247484381&idx=1&sn=08504c1d03c7cf51683abb617be11997&chksm=e91b66c1de6cefd7b003228bb7c6b74f70d950f11ce5f8679f593b30ed8a32e576f0bdc9587c&token=1107524505&lang=zh_CN#rd),有需求的可以参考这个教程，安装其实是非常简单的。

对于系统目录、文件系统、权限等内容。前面的版本也介绍的非常清楚，这里不再一一赘述。也可以参考这里：[Linux 系统基础入门知识点](https://mp.weixin.qq.com/mp/homepage?__biz=MzI0MDQ4MTM5NQ==&hid=11&sn=34e1e7ed1b2af3d38e44705424ad32d2)

## Linux 必学的常用命令

这一块的知识点，在入门阶段是非常重要的一块，掌握的好坏直接影响到后面的具体操作与学习，而且，这里列举的这些常用管理命令，也是我们日常工作中要用到的（属于重点掌握内容之一）。

![](https://mmbiz.qpic.cn/sz_mmbiz_png/tuSaKc6SfPpYiaNgWlY4EL9GcKCXdVWzWBaicqKliaNmPEoh5zeeZozv09jrQpUS2knxdVgibLRguDte7UTaib24m7w/640?wx_fmt=png&from=appmsg&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)

这部分详细介绍[系统运维常用命令](https://mp.weixin.qq.com/mp/appmsgalbum?__biz=MzI0MDQ4MTM5NQ==&action=getalbum&album_id=1661147427422208001&scene=21#wechat_redirect)及其参数说明，并且配有应用案例详解，基础必备！

## 脚本入门与进阶

这部分介绍Shell脚本编程的基础入门与进阶知识，包括编写方法分享、案例分享。虽然说现在Python在运维工作中已经使用很普遍，但是很多企业实际工作中的时候还是会用到 shell 脚本，它有助于你在工作环境中自动完成很多任务。在减少重复工作量的同时，也会提高不少工作效率！因此，Shell脚本编程也是运维工程师必备的工作技能之一！

更多详细内容可以查阅专栏：[Shell 脚本编程](https://mp.weixin.qq.com/mp/appmsgalbum?__biz=MzI0MDQ4MTM5NQ==&action=getalbum&album_id=1790345250847195139#wechat_redirect)

## 企业常见应用服务安装与配置

这是一个非常基础的知识点，学习完网络、系统基础，常用命令之后，就需要完成这部分内容的学习。安装部署只是起步，真正在企业实际环境中运用自如才是王道。

[玩转企业常见应用与服务系列（一）：网络文件系统 NFS 原理与实践](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247546196&idx=2&sn=eac4b43fe3b8c438c876ec6bc1437645&chksm=e9185048de6fd95eb5f864cd742de9d5f53b5e0aaa273b1cf8d0d170a81b0f5efd5afc2e932e&scene=21#wechat_redirect)  

[玩转企业常见应用与服务系列（二）：文件共享服务 FTP 原理与实践](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247546250&idx=2&sn=ceddc712e4d7f84a130bb03e70bee808&chksm=e9185096de6fd9807f8893e9374267bdbbefdd54148429c286df30ecca1b28f3f9a5260dceb6&scene=21#wechat_redirect)  

[玩转企业常见应用与服务系列（三）：动态主机配置协议 DHCP 原理与实践](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247546273&idx=2&sn=5c85d390f5223d164a9bc90584870e5e&chksm=e91850bdde6fd9ab696a0da72c507c574eaccf5cb07cb7fbf0984d4bf5fd5bb49e3cfbd6f5e4&scene=21#wechat_redirect)  

[玩转企业常见应用与服务系列（四）：域名系统 DNS 服务详解](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247546349&idx=2&sn=241710c6c0717111a7ff82a3e8c0085b&chksm=e91850f1de6fd9e7ba438b130f7478c8bb0225f1e6af8a4468f232419e691c231055fe3c8cf5&scene=21#wechat_redirect)  

[玩转企业常见应用与服务系列（五）：网络文件共享服务 Samba 原理与实践](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247546382&idx=2&sn=54048ce83724cc61d9d990404b0e272c&chksm=e9185312de6fda047aa58a82ce58c463346a90d7bf7193bb072f7f4820e1530299552aa92a69&scene=21#wechat_redirect)  

[玩转企业常见应用与服务系列（六）：数据同步服务 lsyncd 原理与实践](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247546404&idx=2&sn=204a7642fe9cffa3f14721e408507c28&chksm=e9185338de6fda2e911fcb4fe51567c0b26b7bb7251845ea389435cef287d013e8a8aacbeba2&scene=21#wechat_redirect)  

[玩转企业常见应用与服务系列（七）：邮件服务 Postfix 原理与实践](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247546537&idx=2&sn=8a24885f70bf6006711ab361d09e3f2f&chksm=e91853b5de6fdaa341f44339d601e3a59f036449377a2d71b948c366bc15ba888396a5199300&scene=21#wechat_redirect)  

[玩转企业常见应用与服务系列（八）：开源代理服务软件 Squid 详解](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247546631&idx=2&sn=2b8ff1d9b4d5bf63e315fa73bff4e864&chksm=e918521bde6fdb0d7e63f83fe0b927830ca7b53c3d722b5bbb98e5e3b8f778a993d9165de234&scene=21#wechat_redirect)  

[玩转企业常见应用与服务系列（九）：开源 HTTP 加速器 Varnish 详解](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247546656&idx=2&sn=a67b729045e6bbc99bcf92e07ac377ea&chksm=e918523cde6fdb2ab709ed162e34e3d679a96d4c8a2248e8da84f15623d68bcebbdce71b0db4&scene=21#wechat_redirect)  

[玩转企业常见应用与服务系列（十）：自动应答工具 expect  原理与实践](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247546674&idx=2&sn=f3cf7ea6cb5d734fc6fdb06f49eab540&chksm=e918522ede6fdb38d68b556195ebac9df92bcfb84b1ee54dd6e6a4ee1719f93a3a5f4733812a&scene=21#wechat_redirect)  

[玩转企业常见应用与服务系列（十一）：进程管理工具 Supervisor 详解](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247546703&idx=2&sn=b526bcbf3e01743a7d1be1b273fa22a3&chksm=e9185253de6fdb45c275d8ed7856714719a16838717602cf96cefe726455a235e006a08b2b49&scene=21#wechat_redirect)  

[玩转企业常见应用与服务系列（十二）：HTTP 压力测试工具 wrk 详解](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247546724&idx=2&sn=edcd6dbab815684c7346b0a1c8a84947&chksm=e9185278de6fdb6e6683767bd78a95554b4f3125706b25fca03ff0c2bc2aa95ccd5fe4f5e050&scene=21#wechat_redirect)  

[玩转企业常见应用与服务系列（十三）：自动化安装工具 Cobbler 详解](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247546766&idx=2&sn=4213934e406e71d18a74401c896b64dd&chksm=e9185292de6fdb841950978c30beb260f5c20ebf322c7f7211277f4b02b67e7db593a27ec45f&scene=21#wechat_redirect)  

[玩转企业常见应用与服务系列（十四）：自动化运维工具 Ansible 基础入门](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247546803&idx=2&sn=edfe9e575e1a0aacd80853ff1e200249&chksm=e91852afde6fdbb90e7fc13af90b54bee1cca1f60eb7d374d5a59ca1661fb5d79e23a0616404&scene=21#wechat_redirect)  

[玩转企业常见应用与服务系列（十五）：Ansible palybook 原理与实践](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247546817&idx=2&sn=73bb27b18a77f5f43134e2384e7066bd&chksm=e91852ddde6fdbcb41fbafb34cb7f9ab66159fb49f4c06fd36d91f1dc5afc48f99c252136211&scene=21#wechat_redirect)

## Nginx 配置与优化

基础的服务安装、配置文件介绍、虚拟主机配置实践、Nginx优化配置详解、LNMP架构Nginx反向代理负载均衡配置、Nginx+Tomcat多实例及负载均衡配置、高可用、Nginx 版本的平滑升级与回滚、Nginx限流配置、Nginx日志生产实战、Nginx配置文件在线生成工具介绍等。

![](https://mmbiz.qpic.cn/sz_mmbiz_png/tuSaKc6SfPpYiaNgWlY4EL9GcKCXdVWzWmzKF6AYxdqeV6WiaUemz98wr1p4eoWK8FCGasUBbcpCx6oDQE3n4wqQ/640?wx_fmt=png&from=appmsg&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)

详细内容可以查阅专栏：[Nginx 学习专栏](https://mp.weixin.qq.com/mp/appmsgalbum?__biz=MzI0MDQ4MTM5NQ==&action=getalbum&album_id=1463291332122017795#wechat_redirect)

## 数据库基础入门

无论你是开发、运维，还是测试，数据库是必备的技能之一。在正式学习相关具体的数据库服务之前，我们还需要了解一下一些基础知识：可以查看：[数据库基础知识专栏](https://mp.weixin.qq.com/mp/appmsgalbum?__biz=MzI0MDQ4MTM5NQ==&action=getalbum&album_id=2786184098871705603#wechat_redirect)）。

## MySQL 数据库

整个知识体系包括以下几个部分。MySQL 数据库的基础知识，如：数据类型、存储引擎、性能优化（软、硬及sql语句），MySQL 数据库的高可用架构的部分，如：主从同步、读写分离的原理与实践、跨城容灾、数据的备份与恢复等，然后介绍了 MySQL 的管理命令、数据库语言的命令、库与表的管理工具、性能分析与工具的使用、MySQL 数据库服务器的硬件选型、性能监控、开发设计规范等知识。

![](https://mmbiz.qpic.cn/sz_mmbiz_png/tuSaKc6SfPpYiaNgWlY4EL9GcKCXdVWzWnVmlOLzC0OpVfcY5e8CCFyJMT8xlStAicft014OLtU0vw4FIqqSJ4Tg/640?wx_fmt=png&from=appmsg&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)

[死磕数据库系列（五）：MySQL 数据类型与存储引擎介绍](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247535696&idx=2&sn=2d647eac6153abdf1d37cb61da94ecab&chksm=e918294cde6fa05ab94cddccf46389d85877b4369c86b91df88b9a7e355bcf9c7c100a8d8058&scene=21#wechat_redirect)  

[死磕数据库系列（六）：MySQL 索引详解](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247535736&idx=2&sn=95017004f479fc03edd2dd9c979db762&chksm=e9182964de6fa0729b7050b966a7cc3a06d38ee87e8efeff38cb29b79a67a6fbd3972f3a4a1a&scene=21#wechat_redirect)  

[死磕数据库系列（七）：MySQL 性能优化（硬件/系统配置/表结构/SQL语句）](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247535746&idx=2&sn=b625dbb627e51d8ffbf7acc61fb3956f&chksm=e918299ede6fa088f10ccfca4f73c41a579a20d1a0b627750f306fd6cf3a4bea056d766ee992&scene=21#wechat_redirect)  

[死磕数据库系列（八）：MySQL 主从同步详解](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247535792&idx=2&sn=4775463b0e647e30b95affe7bc6e9ab0&chksm=e91829acde6fa0ba5136ba37e7b815397f1d2b629bec509ad22f4966900680049cc14ce09fef&scene=21#wechat_redirect)  

[死磕数据库系列（九）：MySQL 读写分离详解](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247535829&idx=2&sn=e090a46138897d9de8e1c427cab154ff&chksm=e91829c9de6fa0df3bbf229b54a665e619108cc08b8010fa9fdac9138459ad3c4476c8f23859&scene=21#wechat_redirect)  

[死磕数据库系列（十）：MySQL 数据库的备份与恢复](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247535878&idx=2&sn=52ccacabf4ac56ebde4d92b5420df12f&chksm=e918281ade6fa10ca0e69e3d613558fabe1f6b175447aa9ec8b9b3ce93b17b7147f32b6c25c5&scene=21#wechat_redirect)  

[死磕数据库系列（十一）：MySQL 日志文件解析（类型、作用）](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247535947&idx=2&sn=cfbf25d396213c7ae02c726228813737&chksm=e9182857de6fa141a3983ae87f0b5060be6d42574665aff9184f2ecbc0dd706cfff14903d577&scene=21#wechat_redirect)  

[死磕数据库系列（十二）：MySQL 分库分表（何时分？怎么分？）](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247535973&idx=2&sn=395ad6078e17cbce9b5f6f4540cc91f0&chksm=e9182879de6fa16fb83ebad1327a1c51061875ccb630494383c53cb2bfed862fd10da9777dbc&scene=21#wechat_redirect)  

[死磕数据库系列（十三）：MySQL 事务与隔离级别](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247536043&idx=2&sn=3ed76fc0999ea8858138c3594a41abd8&chksm=e91828b7de6fa1a1ccbb1bd773407a4221b711bafe8aacd402c6a5cbdf5fe1512cfda93fb1f1&scene=21#wechat_redirect)  

[死磕数据库系列（十四）：MySQL 锁机制详解（表级锁、页级锁、行级锁）](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247536084&idx=2&sn=7f099b1a68e340795bc43bed010f4bc6&chksm=e91828c8de6fa1deb9516904d39d7a978b6394561e16cd0e2d19379d695b74a891f4459f8927&scene=21#wechat_redirect)  

[死磕数据库系列（十五）：MySQL 存储过程、自定义函数、事务、流程控制的语法、创建和使用](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247536114&idx=2&sn=1a9ad412bcad43880cc5f96d6f548402&chksm=e91828eede6fa1f849dafc31b54c3e3f2fab2536d1caa66741eeac545859e16de04073ea95a5&scene=21#wechat_redirect)  

[死磕数据库系列（十六）：MySQL 单表操作介绍](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247536256&idx=2&sn=d8deeea1c58dc5d73cee60409e4beaa3&chksm=e9182b9cde6fa28ad3512883ecc456b2d4ae3a4560b03be830fc95e893d193eaf7f15d4a888d&scene=21#wechat_redirect)  

[死磕数据库系列（十七）：MySQL 多表操作介绍](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247536282&idx=2&sn=e8e95bfde50800cbd160f03ccfce40ac&chksm=e9182b86de6fa2908d11c263fa1ec7592b209e739b773f8451a8ad656df4e7c27c7131fc6e38&scene=21#wechat_redirect)  

[死磕数据库系列（十八）：MySQL 表的七大约束](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247536419&idx=2&sn=27990943ca22f18198409565df2fc831&chksm=e9182a3fde6fa32958191b51aba2a2834be0baea461c48dee2e4ad91675e720c63b66be11062&scene=21#wechat_redirect)  

[死磕数据库系列（十九）：MySQL  视图、触发器的原理与实战](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247536420&idx=2&sn=1bd9d37fd3486179f32decfac666664a&chksm=e9182a38de6fa32e06535eee7846581bc849c1fab3664527e4edc5f4e025edaab31baa31f78d&scene=21#wechat_redirect)  

[死磕数据库系列（二十）：MySQL 数据库 DDL、DML、DQL、DCL 语言理论与实践（sql 8.0 版）](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247536596&idx=2&sn=6389cf274ad0e5f876c65dfbfd83bd65&chksm=e9182ac8de6fa3deb22abaf9916e829be0d7402967d19fdb0fb27fbdf56aedb0fc570253e7ed&scene=21#wechat_redirect)

[死磕数据库系列（二十一）：MySQL  多版本并发控制 MVCC 原理及实现](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247536700&idx=2&sn=fa5b3e61ee6da9cd1e5ebc6fe8ddcf78&chksm=e9183520de6fbc36b36822d3f42cfa96aecc53763b7eebd17b962a3f1e4d3b109a72ea3c0627&scene=21#wechat_redirect)  

[死磕数据库系列（二十二）：MySQL 数据库机房架构与跨城容灾](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247536727&idx=2&sn=65bdbbfc03ef92d9236ffb04573a217c&chksm=e918354bde6fbc5d54ed41a35196ddd6b02a2744396bf9585892dcaeefd1a7c3a025e35785c8&scene=21#wechat_redirect)  

[死磕数据库系列（二十三）：MySQL 高可用方案选型解析](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247536738&idx=2&sn=23372470203d62e3b1cf9ebb915b3495&chksm=e918357ede6fbc6874323d3a7e15bc8eab938cbc7dfd258e61730e95a4b5f222205ce0dd8a68&scene=21#wechat_redirect)  

[死磕数据库系列（二十四）：MySQL 级联复制与双主双从配置实战](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247536773&idx=2&sn=8098397646869fb1bb8f4cd701eaa6f9&chksm=e9183599de6fbc8f9be8504a96644ebfb1ce72614d141c95436c1ba5e4e58832877c7ccb538c&scene=21#wechat_redirect)  

[死磕数据库系列（二十五）：MySQL 高可用之组复制（MGR）详解](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247536794&idx=2&sn=935db9ca76092158d6654b6a9b16669a&chksm=e9183586de6fbc905ad95f35615fb380cdc67cbc79e1dfe4713a92d6f52390946cab1b1f1bb2&scene=21#wechat_redirect)  

[死磕数据库系列（二十六）：MySQL 高可用之单主、双主模型组复制配置实践](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247536857&idx=2&sn=c6e1dbe02928ff7da99d2b237076b102&chksm=e91835c5de6fbcd356152e4de0a6d13ba95af71a569bb633fdd376cc5a175e4f5115b738d1a3&scene=21#wechat_redirect)  

[死磕数据库系列（二十七）：MySQL 常用管理命令介绍](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247536867&idx=2&sn=f6f097eaa02a9684e73c0794504d34a1&chksm=e91835ffde6fbce9bf29075e94f74808860a13def730a5829306c44cc57f7143b90492dc4119&scene=21#wechat_redirect)  

[死磕数据库系列（二十八）：MySQL InnoDB Cluster 多节点高可用部署实战](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247536939&idx=2&sn=e5b4ecc39d13030a5a85b6872bd0fc88&chksm=e9183437de6fbd2177a93e4f6f56e5cdf2429698596efd8f3dffef74eca2577e47142dc35609&scene=21#wechat_redirect)  

[死磕数据库系列（二十九）：MySQL Router 实现数据库读写分离配置实践](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247536979&idx=2&sn=5f9c3bc33b16527f6f26d1af42308ea5&chksm=e918344fde6fbd59371e8a3068e9e232da2f66b3d673a7b731c44580970f6372a4062685242a&scene=21#wechat_redirect)  

[死磕数据库系列（三十）：MySQL 针对 Swap 分区的运维管理](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247537018&idx=2&sn=0049ce869b17ce51f231f674c48a9955&chksm=e9183466de6fbd708eaaa497a3153187dda362c7652a0cc1a18a94b82bda961a2450f66da88b&scene=21#wechat_redirect)  

[死磕数据库系列（三十一）：MySQL 服务器 CPU、磁盘、内存等硬件选型](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247537082&idx=2&sn=ef6749f1274449d60ba17597bb0cfb43&chksm=e91834a6de6fbdb0b768c27699556befac88444650f7a41caaaebabe04c64c0aeaaa79a9d563&scene=21#wechat_redirect)  

[死磕数据库系列（三十二）：MySQL 数据库、数据表管理工具介绍](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247537115&idx=2&sn=ddafba4a350755f5aaa5d836846c9a46&chksm=e91834c7de6fbdd1e1c83ed19699f838c8ae450306423ef348e080042f86dab2cf933da70279&scene=21#wechat_redirect)  

[死磕数据库系列（三十三）：MySQL 性能分析与相关工具的使用](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247537322&idx=2&sn=39589185f217b48a9440ea3aeca81a4c&chksm=e91837b6de6fbea0e4723c05ab7f706244f4d7755270ce37b561ba03ddbd3b43efce8d6dd5f8&scene=21#wechat_redirect)  

[死磕数据库系列（三十四）：MySQL 性能测试工具 sysbench 详解](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247537333&idx=2&sn=39b2ad0f1bdb1aea9e22f940768b0053&chksm=e91837a9de6fbebf30473b330995e2237116857185ddecaec036867252bf649c6c81d150e079&scene=21#wechat_redirect)  

[死磕数据库系列（三十五）：MySQL 数据库性能监控](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247537425&idx=2&sn=8da1e45b48798c43f6b68474556ebba3&chksm=e918360dde6fbf1b678d844ccab1e85471901b7ec628f6ac9a2330f91c3d871149cbb7654acf&scene=21#wechat_redirect)  

[死磕数据库系列（三十六）:MySQL 开发设计规范、SQL 编写规范及安全规范](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247537438&idx=2&sn=f8d46d574d50c283c5496ba4e71bd13c&chksm=e9183602de6fbf14c9885d5abde23d0d0ba3cbe9f2e8aa6a705f43c194dfb8a7f48ac3d5ec2c&scene=21#wechat_redirect)

## PostgreSQL 数据库

PostgreSQL 是一个功能强大的开源数据库系统。经过长达15年以上的积极开发和不断改进，PostgreSQL已在可靠性、稳定性、数据一致性等获得了业内极高的声誉。目前PostgreSQL可以运行在所有主流操作系统上，包括Linux、Unix和Windows。

![](https://mmbiz.qpic.cn/sz_mmbiz_png/tuSaKc6SfPpYiaNgWlY4EL9GcKCXdVWzWdapoMKIwWyWaEb9zcUibrJdwzRhuly0cJNABZRic01Ng5TmqKqXBAr8g/640?wx_fmt=png&from=appmsg&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)

[进阶数据库系列（一）：PostgreSQL 基础入门与安装](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247541430&idx=2&sn=c21eb45f00e6ad012cc39c35bb29b0a2&chksm=e91847aade6fcebc55fe12c7784a1484a8bad1077abe46433e6ee291dc082eb41f9dd6f2f076&scene=21#wechat_redirect)  

[进阶数据库系列（二）：PostgreSQL 目录结构与配置文件 postgresql.conf 详解](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247541440&idx=2&sn=3a677522547ded1680f2875e7a1e5b1e&chksm=e91847dcde6fceca0d1470d66c299391226f2eef9361ddea99d02f711a3b5fdf7a12067a13d6&scene=21#wechat_redirect)  

[进阶数据库系列（三）：PostgreSQL 常用管理命令](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247541471&idx=2&sn=7d70083c7cc026a818bca7f7facde80a&chksm=e91847c3de6fced54ffcc4879db5ba3d6169bb7d2330a88fa6fe9c3060f101f12baf3d154d46&scene=21#wechat_redirect)  

[进阶数据库系列（四）：PostgreSQL 访问控制与认证管理](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247541481&idx=2&sn=22c9a57c649f7bf4984f3da854cca903&chksm=e91847f5de6fcee363d099c37dcd24c73f71b30ae80be09625292416f4482a7420d59791ac1c&scene=21#wechat_redirect)  

[进阶数据库系列（五）：PostgreSQL 语法详解](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247541530&idx=2&sn=f8454cc7875e3290fa8beecc7ee29f40&chksm=e9184606de6fcf10fc039f9f81a8607a706053a62d0378afd8993c9656e3a5ac3641bf971994&scene=21#wechat_redirect)  

[进阶数据库系列（六）：PostgreSQL 数据类型与运算符](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247541562&idx=2&sn=7920f63b12c85dd5ef5ee71248b4b65c&chksm=e9184626de6fcf30d2f3e8f5bdee10653480654dc1988ff92fb84eca1c397570b3513a863c74&scene=21#wechat_redirect)  

[进阶数据库系列（七）：PostgreSQL 常用函数介绍](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247541586&idx=2&sn=ce3a03ee4977763f23395e5c71e26d1b&chksm=e918464ede6fcf583e1a6c6f750649402f44a61c01f2cae34591a0fbcdd0a1e6a295587678d7&scene=21#wechat_redirect)  

[进阶数据库系列（八）：PostgreSQL 锁机制](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247541626&idx=2&sn=b5c7856b77b39035af2f7b7c845576f3&chksm=e9184666de6fcf706dea5e72cfabb9af06a38e7337d5a4c88ffed3ffea58b61fd8faf9bcc132&scene=21#wechat_redirect)  

[进阶数据库系列（九）：PostgreSQL 执行计划](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247541650&idx=2&sn=d900c3fb554e1457cb1b77e517c0f3bd&chksm=e918468ede6fcf98154b90478449ba53a5358ee3588ea5ce19fa530e875ba3e12869901f8c17&scene=21#wechat_redirect)  

[进阶数据库系列（十）：PostgreSQL 视图与触发器](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247541667&idx=2&sn=87d7ba41a52107c0e2fa63ad011b837f&chksm=e91846bfde6fcfa96d7e541258bb8cee1b166947cc50ede17c1d8d3694a45060ae1051a725d6&scene=21#wechat_redirect)  

[进阶数据库系列（十一）：PostgreSQL 存储过程](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247541707&idx=2&sn=28d5be92b26caba859885a30e38b0d8d&chksm=e91846d7de6fcfc16d834cf56900b2857754ea8a1752092570c8d29bb4d1f1140d6bf6c513f8&scene=21#wechat_redirect)  

[进阶数据库系列（十二）：PostgreSQL 索引技术详解](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247541728&idx=2&sn=9675087c9f7c52f2538d365727e6638f&chksm=e91846fcde6fcfeae944f996d636ac396d8a8608990e0a3c286dc224113ea45874c91368570e&scene=21#wechat_redirect)  

[进阶数据库系列（十三）：PostgreSQL 分区分表](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247541738&idx=2&sn=7e1ae5f771bb973752ba29906e4c1b30&chksm=e91846f6de6fcfe0fbb43f6a46f5a645d765621ed4348505fccd1c999ff0b5a58e5b7606a8f1&scene=21#wechat_redirect)  

[进阶数据库系列（十四）：PostgreSQL 事务与并发控制](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247541747&idx=2&sn=c3653e8fe2a0987e9973128bd73c62fb&chksm=e91846efde6fcff9998bbb64d898929e69a5320d5f2e02646866ef983c80baa7c6146a263a4d&scene=21#wechat_redirect)  

[进阶数据库系列（十五）：PostgreSQL 主从同步原理与实践](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247541758&idx=2&sn=5e9f8f6bd1057a87ed111cea25202450&chksm=e91846e2de6fcff42fbf47f18a094a1014884bc2a354212d1f916409e827ef86452bb01a3da4&scene=21#wechat_redirect)  

[进阶数据库系列（十六）：PostgreSQL 数据库高可用方案](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247541768&idx=2&sn=1870d0b8a3fe6c24e0a52d890afb285f&chksm=e9184114de6fc802904ff5ee23d4b17b1f4d25651694a4389cc96cb5040b074b8b9c863ba845&scene=21#wechat_redirect)  

[进阶数据库系列（十七）：PostgreSQL 基于 Patroni 高可用架构部署及故障切换](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247541794&idx=2&sn=8c6d3d7e8fe3a5fdb3e5c6eae4106131&chksm=e918413ede6fc82815feee73d440439cad17fcce613a94d39c552ceae64afcafda280d25e386&scene=21#wechat_redirect)  

[进阶数据库系列（十八）：PostgreSQL 基于 repmgr 高可用架构实践](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247541820&idx=2&sn=3d902a163cbad3c7d4300c0ea2ab6198&chksm=e9184120de6fc8360ad6afb23235ca3311d8a5c0f5c630dd4f8cc09b4123e3d68cee75117f43&scene=21#wechat_redirect)  

[进阶数据库系列（十九）：PostgreSQL 基于 Pgpool 实现读写分离](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247541845&idx=2&sn=ee9ef65d7ade1dc6523524556609d906&chksm=e9184149de6fc85fa360e34010eaf64e0bff8946218d0677a6b51a402641e3796abde5e2b74b&scene=21#wechat_redirect)  

[进阶数据库系列（二十）：PostgreSQL 数据库备份与恢复](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247541856&idx=2&sn=c471fd1128c539848a50d9d4d774d960&chksm=e918417cde6fc86a5269d15c16769f9bb131e09ebc654c318ca50a7bcf01380dcc501b882a4e&scene=21#wechat_redirect)  

[进阶数据库系列（二十一）：PostgreSQL 数据目录同步工具 pg\_rewind](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247541950&idx=2&sn=a4b485dada591e9cb5d0ce3732ccbd07&chksm=e91841a2de6fc8b4518ace0dd2328a92c7dbc0bf3855c6c4bf32bd64614d50804e416f2f0684&scene=21#wechat_redirect)  

[进阶数据库系列（二十二）：PostgreSQL 数据库作业调度工具 pgAgent](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247541986&idx=2&sn=02e4a7de714f6d4519f2aab7a051bc43&chksm=e91841fede6fc8e861c71b974b0e19e5e73d8ad2d92bc043bfff9f8600b6b4762f917b92a88e&scene=21#wechat_redirect)  

[进阶数据库系列（二十三）：PostgreSQL 性能优化](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247541992&idx=2&sn=d7af91c18c9e162fe358f169882ad79b&chksm=e91841f4de6fc8e29c1d7991642e96a1c8fa647eafd0ad70077d9c9f51b0182fc835064bdbb5&scene=21#wechat_redirect)  

[进阶数据库系列（二十四）：PostgreSQL 数据库日志与日常巡检](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247542008&idx=2&sn=7a3c47d76b48f64319db8ea0bc02b7ee&chksm=e91841e4de6fc8f25ddbd7abdccfbecaa6e7540c878407ee1fa42622089fe1aabfcc22e66821&scene=21#wechat_redirect)  

[进阶数据库系列（二十五）：PostgreSQL 数据库日常运维管理](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247542030&idx=2&sn=56453517358477c8650f7cb41de527fb&chksm=e9184012de6fc904b69e6083292e9f244922bf8762d11421a9d2a38b9bc356aabef75c19bddd&scene=21#wechat_redirect)  

[进阶数据库系列（二十六）：PostgreSQL 数据库监控管理](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247542031&idx=2&sn=a307604c5dcd91bd8020286b2cc39af5&chksm=e9184013de6fc905a0e526cf104336ca5bdbacf4a42158f633b258136ffbe07d4d899010b299&scene=21#wechat_redirect)

## Nosql 数据库

Nosql 数据库是一种非关系型数据库服务，它能解决常规数据库的并发能力，比如传统的数据库的IO与性能的瓶颈，同样它是关系型数据库的一个补充，有着比较好的高效率与高性能。专注于key-value查询的redis、memcached、ttserver。

![](https://mmbiz.qpic.cn/sz_mmbiz_png/tuSaKc6SfPpYiaNgWlY4EL9GcKCXdVWzWcbACqe3j23EtnAwyETZGy6btrpZ74JBAWeJ9HsYOP2zAHdpE2qujlw/640?wx_fmt=png&from=appmsg&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)

我们这里会重点介绍：Redis、MongoDB、ElasticSearch。

#### Redis

Redis 是一款内存高速缓存数据库。Redis全称为：Remote Dictionary Server（远程数据服务），使用C语言编写，Redis是一个key-value存储系统（键值存储系统），支持丰富的数据类型，如：String、list、set、zset、hash。Redis是一种支持key-value等多种数据结构的存储系统。可用于缓存，事件发布或订阅，高速队列等场景。支持网络，提供字符串，哈希，列表，队列，集合结构直接存取，基于内存，可持久化。

![](https://mmbiz.qpic.cn/sz_mmbiz_png/tuSaKc6SfPpYiaNgWlY4EL9GcKCXdVWzWZWFuYXQCWgYKiaWH0QSibkwzcmXicxwDDuBic40auH2UKbkMoLJ6p74I0Q/640?wx_fmt=png&from=appmsg&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)

无论是运维还是开发、测试，对于 NoSQL 数据库之一的 Redis 也是必学知识体系之一。

[死磕 NoSQL 数据库系列（一）：Redis 基础理论与安装配置](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247537510&idx=2&sn=d33f3c4ed393ee49a9103f75f0ced0fc&chksm=e918367ade6fbf6cf439b29a8afd7521e17da4712ced1a0c4104f87d1792c3094214c59ffbc8&scene=21#wechat_redirect)  

[死磕 NoSQL 数据库系列（二）：Redis 9 种数据类型和应用场景](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247537550&idx=2&sn=f3e48a2acef5927ac6433ece8413caf2&chksm=e9183692de6fbf844def0e8df867df830567d6818ba74bd1d2c17c9723c2cfaacb895e89acb7&scene=21#wechat_redirect)  

[死磕 NoSQL 数据库系列（三）：Redis 常用管理命令](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247537688&idx=2&sn=1bfd3def78d00fa065535d10bf688266&chksm=e9183104de6fb81259727962c4de0e1d4af4a925f049539d9999922c12e8594806603f0f10b7&scene=21#wechat_redirect)  

[死磕 NoSQL 数据库系列（四）：Redis 发布与订阅(pub/sub)](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247537749&idx=2&sn=ac1a8e8ed9800b4e82b897094c44c989&chksm=e9183149de6fb85f0e0b455419cbdec488bd7c1e1651922cb0752d7579a30cfa4b66d89ddfe3&scene=21#wechat_redirect)  

[死磕 NoSQL 数据库系列（五）：Redis 事件机制详解](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247537863&idx=2&sn=41382754242ffab0e73a2b8d6ce842c6&chksm=e91831dbde6fb8cdcd6ba6a7898035edbdd8ffed2a1f43dc7f6469cb0e3041eebda6e937bf46&scene=21#wechat_redirect)  

[死磕 NoSQL 数据库系列（六）：Redis 事务详解](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247537967&idx=2&sn=033434a398d614532dcc8290b103b51f&chksm=e9183033de6fb9256149bc89f33e9dd05a89f052f9d2163142cb7433bc7e9711c26792abe392&scene=21#wechat_redirect)  

[死磕 NoSQL 数据库系列（七）：Redis 持久化（RDB和AOF）](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247537989&idx=2&sn=374c05e1c490edeab1f9bd85d668eac9&chksm=e9183059de6fb94f62692bb813e487e34a22b3d0fec58d38b69e6016b3bf9833b0c709c2e226&scene=21#wechat_redirect)  

[死磕 NoSQL 数据库系列（八）：Redis 主从复制及数据恢复实践](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247538076&idx=2&sn=539b3413b390e7e4b7452e9a20ca7e06&chksm=e9183080de6fb996c223c217c0a99d4eb72dfa814d503e9f76e96f9ca0038046346cfa6a710d&scene=21#wechat_redirect)  

[死磕 NoSQL 数据库系列（九）：Redis sentinel 集群原理部署及数据恢复](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247538118&idx=2&sn=c6554423c1d7a0040be974900e5a9598&chksm=e91830dade6fb9cc7916856d2c44df8519e63cf461c179380d53b0c8078da9193e9e0656e5c6&scene=21#wechat_redirect)  

[死磕 NoSQL 数据库系列（十）：Redis Cluster 集群分片技术](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247538179&idx=2&sn=6c74f77561dc2a0f5c54cf9173538a4a&chksm=e918331fde6fba09e37d94fd0e9983b95f6f0128fc6c5d2c737c3f0ca058a3dec7f1504df3a5&scene=21#wechat_redirect)  

[死磕 NoSQL 数据库系列（十一）：Redis Cluster 交叉复制与故障切换实战](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247538180&idx=2&sn=1a9a8d19949c888b9ade1900c59a0b8c&chksm=e9183318de6fba0e1e1d862afd5529ed23c187401008761296fc58e1f14eeb42a9005246d950&scene=21#wechat_redirect)  

[死磕 NoSQL 数据库系列（十二）：使用 Redis 官方工具自动部署 Cluster 集群实践](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247538261&idx=2&sn=da7a9ef79e50aaeff720197485172f5d&chksm=e9183349de6fba5fead9896c79ed434b89a0d5c4a40b8f21c3e32f5f365959a636e13e45684a&scene=21#wechat_redirect)  

[死磕 NoSQL 数据库系列（十三）：Redis Cluster 集群扩容原理与实践](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247538272&idx=2&sn=af26088216a1724215fad73de51f2ba6&chksm=e918337cde6fba6ab2271c992c2eb64a38546b4620d83779e4a24cac336cc0fd52a3366041ba&scene=21#wechat_redirect)  

[死磕 NoSQL 数据库系列（十四）：Redis Cluster 集群收缩原理与实践](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247538317&idx=2&sn=0c02a095f302b4c5f25185f52240a1d3&chksm=e9183391de6fba8717156b67cc31a7d18879606a06e7017e12b2cf38c09a5ebf8a17cd412f6b&scene=21#wechat_redirect)  

[死磕 NoSQL 数据库系列（十五）：Redis 与Java\\Php\\Springboot 等应用的连接与使用](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247538380&idx=2&sn=0b6d05c00381d14a68c02b92bcf3cba2&chksm=e91833d0de6fbac6ade230b44406d84f6ecccbf063948c6127235a93c4a760ddea9e073126a8&scene=21#wechat_redirect)  

[死磕 NoSQL 数据库系列（十六）：Redis 常用运维脚本](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247538464&idx=2&sn=e0f3058ffb6b58404a6e7c86ccfad35b&chksm=e918323cde6fbb2a8f8ba4a384deed338c39f97f11037038db1f1e3a7dbaf43a4c64eb611fe7&scene=21#wechat_redirect)  

[死磕 NoSQL 数据库系列（十七）：Redis 缓存问题（一致性、击穿、穿透、雪崩、污染）](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247538612&idx=2&sn=be834b4ff6a0ccd976a103668918b622&chksm=e91832a8de6fbbbe4aff9267073e305b91dda9449045e531faf76e15c6b63fb973af5cf41e8a&scene=21#wechat_redirect)  

[死磕 NoSQL 数据库系列（十八）：Redis 内存消耗及回收](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247538768&idx=2&sn=cd9b557edb2876e55165142fbcc1c6fa&chksm=e9183d4cde6fb45ab7c348d27af800dab9bba90479d4a34f4adc5b3cda8ad34368374944a6da&scene=21#wechat_redirect)  

[死磕 NoSQL 数据库系列（十九）：Redis Key 过期时间相关的命令、注意事项、回收策略](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247538816&idx=2&sn=2601d2957ddc62f04bd17cfcbed86429&chksm=e9183d9cde6fb48a56e1a42fa010267bd9702bdc69cdd18b86c40fb357a48a980e1ad91622c8&scene=21#wechat_redirect)  

[死磕 NoSQL 数据库系列（二十）：Redis 性能优化与问题排查](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247538955&idx=2&sn=b0f17389d0d7c6586e214be1991ec4d5&chksm=e9183c17de6fb501a2533b9213cacaa25335a6b9e39eb59d9ac83dfd3f6ac0db73622b406ff1&scene=21#wechat_redirect)  

[死磕 NoSQL 数据库系列（二十一）：Redis 性能测试及相关工具使用](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247538977&idx=2&sn=af3a0ea7d67d553fdb27d1ed0a10593e&chksm=e9183c3dde6fb52b117ff07d869947203d04ec2364d1d45b8445029d86a179eebf9a5a7dbbc0&scene=21#wechat_redirect)  

[死磕 NoSQL 数据库系列（二十二）：Redis 运维监控（指标、体系建设、工具使用）](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247539037&idx=2&sn=a2ea1a7b41510dc05f6cae926b3059b0&chksm=e9183c41de6fb557455a36842f394d9b257b606c257fd80e9dd4df5b4a72be4a63238d173f44&scene=21#wechat_redirect)  

[死磕 NoSQL 数据库系列（二十三）：Redis 开发规范](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247539073&idx=2&sn=3ff35f4e842cc73e45e9ec688b9ec7b7&chksm=e9183c9dde6fb58b0b9b650cb5dc44a1263306244ec5028fd0ef5c196bd0fbfcbf06f47ce357&scene=21#wechat_redirect)

#### MongoDB

MongoDB 是面向文档的 NoSQL 数据库，用于大量数据存储。MongoDB 是一个在 2000 年代中期问世的数据库。属于 NoSQL 数据库的类别。

![](https://mmbiz.qpic.cn/sz_mmbiz_png/tuSaKc6SfPpYiaNgWlY4EL9GcKCXdVWzWHmGVrqE1jD0WviavOCBTve94BMmhH3m9f8npreeFbusyibyFicUSmLZnQ/640?wx_fmt=png&from=appmsg&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)

[硬卷 NoSQL 数据库系列（一）：MongoDB  知识体系与基础概念](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247539122&idx=2&sn=437351196ae35c460cec6016f7b52e15&chksm=e9183caede6fb5b86b41112b86b3eb34a4866fdfb5eec941cde8517df118dfc1c35b063414fc&scene=21#wechat_redirect)  

[硬卷 NoSQL 数据库系列（二）：MongoDB 安装与 CURD 基本操作](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247539123&idx=2&sn=a6295ebf41cd6e0b471789bf8cb38192&chksm=e9183cafde6fb5b9dc73b02a617c20a48c5387c206a7f3811670bab98211aa7c3fe4a8c9a42f&scene=21#wechat_redirect)  

[硬卷 NoSQL 数据库系列（三）：MongoDB 索引与聚合](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247539163&idx=2&sn=f53e7d0025314ca85fb0f20a853a887d&chksm=e9183cc7de6fb5d169982db9ec833e3ab8b54f9c70c4238d509dd319334e761b137ead30df45&scene=21#wechat_redirect)  

[硬卷 NoSQL 数据库系列（四）：MongoDB 基本使用（工具、API、Spring 集成）](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247539209&idx=2&sn=3b381be03821365d1d85d35323d834fb&chksm=e9183f15de6fb60338040b158b9b1ae930daffe2fb50dec691996dcae5b94e8ee7fe9d27dd36&scene=21#wechat_redirect)  

[硬卷 NoSQL 数据库系列（五）：MongoDB 常用管理命令与授权认证](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247539237&idx=2&sn=246ae59c4951b9609428c054978955d3&chksm=e9183f39de6fb62f778c0740c51fd9f6b04fa5edf39e32572e3647bde99c6aa7908c63ae93ae&scene=21#wechat_redirect)  

[硬卷 NoSQL 数据库系列（六）：MongoDB 存储引擎 WiredTiger 技术详解](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247539311&idx=2&sn=fde636ce5a026d7ade6921a019779e39&chksm=e9183f73de6fb665bf5d4be1c5cd24101f435d628663e04984cacee192cee92f2818ceba42c1&scene=21#wechat_redirect)  

[硬卷 NoSQL 数据库系列（七）：MongoDB 复制集技术原理详解](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247539338&idx=2&sn=fc1630228936db57662823a4de574018&chksm=e9183f96de6fb680d6c14412cf62bfae78a2a32e3f5342b071c046e34adf6ec36c66d2e5546d&scene=21#wechat_redirect)  

[硬卷 NoSQL 数据库系列（八）：MongoDB 集群部署与配置实践](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247539405&idx=2&sn=9acede409e253695bd164266747b89db&chksm=e9183fd1de6fb6c7d53f381c03de5063b5c64909b4ed96cbc3ad550adb64a483f976ddebaccd&scene=21#wechat_redirect)  

[硬卷 NoSQL 数据库系列（九）：MongoDB 分片（sharding）技术](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247539457&idx=2&sn=6701346d4383af02ecbd6f89f2c266e5&chksm=e9183e1dde6fb70bb8c3d859dc195ea50f938ceb4874ac234d6bd83efc5a37f3f2100e7464aa&scene=21#wechat_redirect)  

[硬卷 NoSQL 数据库系列（十）：MongoDB 数据库备份与恢复](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247539471&idx=2&sn=6218c36d00ee67d0b4dc0c4dc6d1fbda&chksm=e9183e13de6fb705efd9cf83f92da4ef76d90403f6506081682c47d7d9bb48c9fbfd0941cc75&scene=21#wechat_redirect)

[硬卷 NoSQL 数据库系列（十一）：MongoDB 状态检测与性能追踪](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247539506&idx=2&sn=1a78e6c0a172fe3051808e14dfafe56b&chksm=e9183e2ede6fb73889922fcfcaf5930356269a0958669e8fb22ebe5a199ba9ed0004127413d8&scene=21#wechat_redirect)  

[硬卷 NoSQL 数据库系列（十二）：MongoDB 客户端管理工具](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247539543&idx=2&sn=3cc5c2153c20266db0709d483c738953&chksm=e9183e4bde6fb75d795b13ccfb8feee5c7d74e7a46e14f96128dd55f56e049e1f9e3abe9c30e&scene=21#wechat_redirect)  

[硬卷 NoSQL 数据库系列（十三）：MongoDB 日志分析工具](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247539592&idx=2&sn=ccba687cf304b13104775de0d3c0cb7c&chksm=e9183e94de6fb78203ad071825bc8abd7e057d32b37b6602f20cfe0140ca91eda25af1ee71a2&scene=21#wechat_redirect)  

[硬卷 NoSQL 数据库系列（十四）：MongoDB 查询聚合性能优化](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247539594&idx=2&sn=1d95b1210d957c32b9ae2feee6a3d0c1&chksm=e9183e96de6fb7803a40ebb99229847afda9c7b634997218a239203e1fdafc524029f63d8b80&scene=21#wechat_redirect)  

[硬卷 NoSQL 数据库系列（十五）：MongoDB 数据库设计开发规范](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247539609&idx=2&sn=85ecc081c2f159421604928537da1ad5&chksm=e9183e85de6fb7937982f04fc1c50d1bb0d4ca90b0eb689f2ad34bb6befe45e7c4f32e2fab71&scene=21#wechat_redirect)

#### ElasticSearch

ElasticSearch是一款非常强大的、基于Lucene的开源搜索及分析引擎；它是一个实时的分布式搜索分析引擎，它能让你以前所未有的速度和规模，去探索你的数据。它被用作**全文检索**、**结构化搜索**、**分析**以及这三个功能的组合。

![](https://mmbiz.qpic.cn/sz_mmbiz_png/tuSaKc6SfPpYiaNgWlY4EL9GcKCXdVWzWlJ2icPhUXSK1wbgWlgIh53z3fPR1xmBiaVa8jN2dceLBosebl6dGx7ibA/640?wx_fmt=png&from=appmsg&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)

除了搜索，结合Kibana、Logstash、Beats开源产品，Elastic Stack（简称ELK）还被广泛运用在大数据近实时分析领域，包括：日志分析、指标监控、信息安全等。它可以帮助你探索海量结构化、非结构化数据，按需创建可视化报表，对监控数据设置报警阈值，通过使用机器学习，自动识别异常状况。

ElasticSearch是基于Restful WebApi，使用Java语言开发的搜索引擎库类，并作为Apache许可条款下的开放源码发布，是当前流行的企业级搜索引擎。其客户端在Java、C#、PHP、Python等许多语言中都是可用的。

所以，ElasticSearch具备两个优势：
- 天生支持分布式，可水平扩展；
- 提供了Restful接口，降低全文检索的学习曲线，因为Restful接口，所以可以被任何编程语言调用.

[边学边实战系列（一）：ElasticSearch 基础概念、生态和应用场景](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247539667&idx=2&sn=7ddffcbee09c41c6c7ae160f4968c954&chksm=e9183ecfde6fb7d93c96d4f2add1fa583b0c2c021f8885266ce799a5a1185addb74672a856e5&scene=21#wechat_redirect)  

[边学边实战系列（二）：ElasticSearch 技术原理图解](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247539744&idx=2&sn=38093c6e2da073a364ab886bb9e2f1b6&chksm=e918393cde6fb02a4cd462a4faf57fd8f8e02335dac044d9a0722ac5f4407be38cce86d36e0b&scene=21#wechat_redirect)  

[边学边实战系列（三）：ElasticSearch 安装与基础使用](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247539791&idx=2&sn=c336b4a12d8b7f65c868a257f81348ba&chksm=e9183953de6fb045bc45659613a9701125ec09a186bded27d8eb8c52140293df484514795320&scene=21#wechat_redirect)  

[边学边实战系列（四）：ElasticSearch 索引管理](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247539868&idx=2&sn=7d44b906248c84f8de261c6c81a7e9df&chksm=e9183980de6fb0969794e87cdffe908bd78fdb678464a0281ee2313dbe0b6a7a893a07cc1abc&scene=21#wechat_redirect)  

[边学边实战系列（五）：ElasticSearch DSL 查询原理与实践](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247539928&idx=2&sn=2679d1427b947e539fbae5fbfb3356fd&chksm=e91839c4de6fb0d2ae338f7487702cadb750c1a0ef27d99aa5c6285cf863dd67b604ed39bfec&scene=21#wechat_redirect)  

[边学边实战系列（六）：ElasticSearch 聚合查询原理与实践](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247539972&idx=2&sn=b42701ddd96fa91af58f862e95d4c108&chksm=e9183818de6fb10efc25a9bce65308535734c21582a36946654f0c1e792bf099abdf835694cb&scene=21#wechat_redirect)  

[边学边实战系列（七）：ElasticSearch 文档索引与读取流程详解](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247540012&idx=2&sn=49ea46d157542ef5e6eb90e4f2b06636&chksm=e9183830de6fb12608461d2d37ec122859b890d0d80249e492a366b88c0f505e300967b83d91&scene=21#wechat_redirect)  

[边学边实战系列（八）：ElasticSearch 集群部署、分片与故障转移](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247540052&idx=2&sn=e62c0fe3319e03555f731749397891c5&chksm=e9183848de6fb15e021cab61a535a69e02708cf7ae30cd71dc2c9421026fcce7b7702eaf9b6d&scene=21#wechat_redirect)  

[边学边实战系列（九）：ElasticSearch 集群规划与运维经验总结](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247540072&idx=2&sn=65e5aa395a70c093b33aca7f1b19216b&chksm=e9183874de6fb16277268409622a6dbe8bdc4abaa2c10ce7b6250a627c493fdbf9d3956399c7&scene=21#wechat_redirect)  

[边学边实战系列（十）：ElasticSearch 分片/副本与数据操作流程](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247540140&idx=2&sn=59b2e0a53094bd037cdf53000a514dc9&chksm=e91838b0de6fb1a64242f911e0387aa5041901a9d6c47af379a9c3d60fe10b157fbc92498888&scene=21#wechat_redirect)  

[边学边实战系列（十一）：ElasticSearch 数据备份与迁移](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247540150&idx=2&sn=7b2e673c6709236ddffb074ecab9d00d&chksm=e91838aade6fb1bcd75bdcc1be3ba6469eddcac64ce3df2efae463f0351fb6a43e886d961447&scene=21#wechat_redirect)  

[边学边实战系列（十二）：ElasticSearch 常用 Curl 命令实践](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247540230&idx=2&sn=3bb7d0291246326533ac68e84c1a47db&chksm=e9183b1ade6fb20c653fec912df9ddf10e20dd85d35ee0e81c604d3a84e1b1b8bfcf9f1a3580&scene=21#wechat_redirect)  

[边学边实战系列（十三）：ElasticSearch 可视化管理工具](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247540242&idx=2&sn=9d29855ef28b78d99ac44d0065c44617&chksm=e9183b0ede6fb218b1f495580674a784c5ac332c917ed6e24b2ba2f3986d8929e0287c882d59&scene=21#wechat_redirect)  

[边学边实战系列（十四）：ElasticSearch 性能优化详解](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247540283&idx=2&sn=27da38118a7a89ae1db1d698d6a714be&chksm=e9183b27de6fb231b2f0545f6ab9cc8a3a7e45a825cf28b6aa7aabf04583012a082e37c262b8&scene=21#wechat_redirect)  

[边学边实战系列（十五）：ElasticSearch 性能监控](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247540363&idx=2&sn=9e05122729cab5397c9b5a783d6b9ff5&chksm=e9183b97de6fb2816dc9171a728671959cec86967ec1a22b885df6c6b08fd99c24374784d758&scene=21#wechat_redirect)

## Tomcat 技术实践

Tomcat 隶属于 Apache 基金会，是开源的轻量级 Web 应用服务器，使用非常广泛。客户端用户点击浏览器服务连接，浏览器通过客户端底层服务通过路由传送报文，目标服务器获取解析报文，Tomcat监听程序触发处理请求。

![](https://mmbiz.qpic.cn/sz_mmbiz_png/tuSaKc6SfPpYiaNgWlY4EL9GcKCXdVWzWFWDbX6xcy8fTEeodvFuQuur1IxXqhetQolD7KU70aKtoO1DtR69lgA/640?wx_fmt=png&from=appmsg&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)

Tomcat 相关知识点在面试中出现的几率并不高，所以，很多人忽略了对 Tomcat 相关技能的掌握，其实它也是非常重要的知识点之一。详细内容可查阅专栏：[Tomcat web 技术实践](https://mp.weixin.qq.com/mp/appmsgalbum?__biz=MzI0MDQ4MTM5NQ==&action=getalbum&album_id=1794746582974726146#wechat_redirect)。

## 企业生产项目实践

一个中小企业生产环境项目实践（将之前的知识连贯运用的实践）：
- [Linux 系统集群架构线上项目配置实战（一）](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247484723&idx=1&sn=33ce27a307af770107c2c453dff8dd27&chksm=e91b602fde6ce939ee780fa7fa748d6600e64339bac6539ba825430b97dcf2243d0f57e8a31c&scene=21#wechat_redirect)  
- [Linux 系统集群架构线上项目配置实战（二）](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247484733&idx=1&sn=7f6d9a0d408502de57391ac540d952b6&chksm=e91b6021de6ce937854db9a0a74b4a60377db4cc4487c584368f9c772fa195e93d3b0db9b7c9&scene=21#wechat_redirect)  
- [Linux 系统集群架构线上项目配置实战（三）](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247484741&idx=1&sn=7ee21ffdc398056fcf5b4fc23250104c&chksm=e91b6059de6ce94f093352eae196882963018872a5c58b1907e804a82cb8f34e4a8c6a0c97ca&scene=21#wechat_redirect)
- [Linux 系统集群架构线上项目配置实战（四）](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247484751&idx=1&sn=54d4bdb6946da8f3df8eb3781853cba7&chksm=e91b6053de6ce945e07595ed3ab754d9fd649e3ddcd543fcc757b7b60f049408e54f50159f8a&scene=21#wechat_redirect)  
- [Linux 系统集群架构线上项目配置实战（五）](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247484758&idx=1&sn=285547d2f6a105b5e71a41f5b5487c4e&chksm=e91b604ade6ce95c2c03fc3599d1d25d550dabe28d73b260b2715e0ba0c6cc931be4ea4f279d&scene=21#wechat_redirect)

## 常用中间件服务

介绍常用中间件服务（Kafka\Rabbitmq\Zookeeper等）相关的日常运维所需知识体系。

#### Kafka

Kafka是一个开源消息系统，由Scala写成。是由Apache软件基金会开发的一个开源消息系统项目，该项目的目标是为处理实时数据提供一个统一、高通量、低等待的平台。

![](https://mmbiz.qpic.cn/sz_mmbiz_jpg/tuSaKc6SfPoM7oOuiczKzMjZnPtTWia8ghMGc6x6ojjHh8AicwJVEpQcCQuDePCUTImewib1sm839agcDsiaOgPjqJQ/640?wx_fmt=jpeg&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)

Kafka是一个分布式消息队列：生产者、消费者的功能。它提供了类似于JMS的特性，但是在设计实现上完全不同，此外它并不是JMS规范的实现。

Kafka对消息保存时根据Topic进行归类，发送消息者称为Producer,消息接受者称为Consumer,此外kafka集群有多个kafka实例组成，每个实例(server)成为broker。无论是kafka集群，还是producer和consumer都依赖于zookeeper集群保存一些meta信息，来保证系统可用性。

###### Kafka六大特点

- 1、高吞吐量、低延迟：可以满足每秒百万级别消息的生产和消费。它的延迟最低只有几毫秒，topic可以分多个partition, consumer group 对partition进行consumer操作。    
- 2、持久性、可靠性：有一套完善的消息存储机制，确保数据高效安全且持久化。消息被持久化到本地磁盘，并且支持数据备份防止数据丢失 。  
- 3、分布式：基于分布式的扩展；Kafka的数据都会复制到几台服务器上，当某台故障失效时，生产者和消费者转而使用其它的Kafka。  
- 4、可扩展性：kafka集群支持热扩展 。   
- 5、容错性：允许集群中节点失败（若副本数量为n,则允许n-1个节点失败）。    
- 6、高并发：支持数千个客户端同时读写。

[进击消息中间件系列（一）：Kafka 入门（基本概念与架构）](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247542083&idx=2&sn=4cadf1b97d6820eb220f6e43fc22bf7f&chksm=e918405fde6fc94999c7af29328b2953cb595eee12c21920ed9cdd3363cd599f2d9d11a68f3d&scene=21#wechat_redirect)  

[进击消息中间件系列（二）：Kafka 单机与集群部署实践](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247542115&idx=2&sn=bf4b74fd31da85706a37215b6bda5477&chksm=e918407fde6fc9691c443c361704583a38cc159154d3f79af7a74e7a5366c5a45fc66a6bca53&scene=21#wechat_redirect)  

[进击消息中间件系列（三）：Kafka 中 shell 命令使用](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247542128&idx=2&sn=ad32bdecc07866000d3a3240cd000ae7&chksm=e918406cde6fc97a055d027a3544cc3414cfb836a30fa7833fdb6b10cfc960d6d872dec2917a&scene=21#wechat_redirect)  

[进击消息中间件系列（四）：Kafka 服务器 Broker](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247542228&idx=2&sn=28195c8dadf700fe7c3ababb934c6ca9&chksm=e91840c8de6fc9deb5cc091d38d8d5d1a7efb9ed6401254d854ae024b3f222c0ffc101b287bd&scene=21#wechat_redirect)  

[进击消息中间件系列（五）：Kafka 生产者 Producer](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247542249&idx=2&sn=196548853daf9a566a4a731526804907&chksm=e91840f5de6fc9e37212b53edf0edcd3c6b2c98815a6e99458c72c1f321b40b949e1794e1e6c&scene=21#wechat_redirect)  

[进击消息中间件系列（六）：Kafka 消费者Consumer](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247542302&idx=2&sn=b053230effa1b89a0a8d2d41a3748107&chksm=e9184302de6fca14ce5f3b12a9ed8c63769e8baf0141dc681c5061ac9c1953ed225327e480e1&scene=21#wechat_redirect)  

[进击消息中间件系列（七）：Kafka 控制器 Controller](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247542370&idx=2&sn=8212524e1113c79830599529c5bf5ae7&chksm=e918437ede6fca68e62f022eab9fd093aa40c231e10731a7b10c54d520a63bbc74da2468820a&scene=21#wechat_redirect)  

[进击消息中间件系列（八）：Kafka 主题与分区](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247542397&idx=2&sn=b7a9fe51da2d77c2a06d05b991504283&chksm=e9184361de6fca77de375178455a4cd2f5eb8ecd6be842a9d990a6307be19bd51d45c2d19c47&scene=21#wechat_redirect)  

[进击消息中间件系列（九）：Kafka 各类 API 使用](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247542407&idx=2&sn=d01d6dd6047ffae8762789f8f15bfa76&chksm=e918439bde6fca8dd334a2c026e1135f09fa7493e782053f8ef414520164c472a270b3c76c30&scene=21#wechat_redirect)  

[进击消息中间件系列（十）：Kafka 副本（Replication）机制](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247542424&idx=2&sn=d64269ddd543d03ecb60b80dccf5e696&chksm=e9184384de6fca921f87ec14ef485c5e17d8a79aa43ada2079dc86a36c410df000c68af8238d&scene=21#wechat_redirect)  

[进击消息中间件系列（十一）：Kafka 存储机制](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247542492&idx=2&sn=fd79c71b33f8a1127ac6841ccfab2165&chksm=e91843c0de6fcad6b10b097f07ab1016a14d4cf73ff3108cbf429ad57a5c782f3808af515c5a&scene=21#wechat_redirect)  

[进击消息中间件系列（十二）：Kafka 事务机制](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247542510&idx=2&sn=21f5b8dee7c20114f6399ff84aac8354&chksm=e91843f2de6fcae481c369167c40d84264d04dee15877d0aa4c9793a467d80318c8bbc57da1a&scene=21#wechat_redirect)  

[进击消息中间件系列（十三）：Kafka 高可用与生产消费过程](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247542568&idx=2&sn=13e6bb4ce6cb2c3c47ce3aeb4e536ac4&chksm=e9184234de6fcb22c6e1d85af34bb41078b494372073c9a2c37c67868f5762e9c68bd32f09cd&scene=21#wechat_redirect)  

[进击消息中间件系列（十四）：Kafka 流式 SQL 引擎 KSQL](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247542607&idx=2&sn=e4900ad106e3e44ff6bfc7323bb79b08&chksm=e9184253de6fcb4586ab5282c458c944eedb81acb43143c7d772addd11ca3ff50812bd668dad&scene=21#wechat_redirect)

[进击消息中间件系列（十五）：Kafka 日志存储与清除策略](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247542637&idx=2&sn=1a780b14035e112964c6f0957eefaf66&chksm=e9184271de6fcb671a8cd7b2127090c22b827986208a72c28e6f655dbf14392f8d8811def5a1&scene=21#wechat_redirect)  

[进击消息中间件系列（十六）：Kafka 数据备份与恢复](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247542672&idx=2&sn=cc3573864d5572e44e5a8fa03897732f&chksm=e918428cde6fcb9a9101338a0289850e1503ee3937109301219bd5eed4d74eff2f948a132645&scene=21#wechat_redirect)  

[进击消息中间件系列（十七）：Kafka 集群管理工具 CMAK](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247542728&idx=2&sn=347f0260bb44e0fc18efd1e389fb5d09&chksm=e91842d4de6fcbc25b2682f6b7e79c9975626e9648165825f7bccb2c47e04d11a768560cc85f&scene=21#wechat_redirect)  

[进击消息中间件系列（十八）：Kafka 可视化管理平台EFAK](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247542783&idx=2&sn=833bf4211e1e6c4d92331f87e8b00521&chksm=e91842e3de6fcbf551ad0b5f7b94eb96798efd82d3b0541cbf881cc27b7c4a6aa3ad18d2985c&scene=21#wechat_redirect)  

[进击消息中间件系列（十九）：Kafka 安全配置最佳实践](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247542789&idx=2&sn=74f79a4f14adc7466ff7d57bb91e4e20&chksm=e9184d19de6fc40f31ca2f1650736b1740038f4937a1a70ac2de913db009f680926b053ab339&scene=21#wechat_redirect)  

[进击消息中间件系列（二十）：Kafka 生产调优最佳实践](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247542809&idx=2&sn=78a4f9cfa022d3af58248d6679b7d5bf&chksm=e9184d05de6fc413ca47a4be56b32037bcd5a01fabe48668d59f12585d4bc841ea43acde440c&scene=21#wechat_redirect)  

[进击消息中间件系列（二十一）：Kafka 监控最佳实践](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247542825&idx=2&sn=eefa2fcd8482ba810a96dbbbbf110731&chksm=e9184d35de6fc4235eb12dee9c4d2e0563b1d1229b35d545434bc3727a8e1f66bc6b9d314dd4&scene=21#wechat_redirect)

#### Rabbitmq

RabbitMQ是由erlang语言开发，基于AMQP协议实现的消息队列，它是一种应用程序之间的通信方法，消息队列在分布式系统开发中应用非常广泛。

![](https://mmbiz.qpic.cn/sz_mmbiz_png/tuSaKc6SfPpYiaNgWlY4EL9GcKCXdVWzWv0ic8pw8QtI85htwzhHU83khM8lA1EQrAlwSXgs44OneHAoYczeNOXQ/640?wx_fmt=png&from=appmsg&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)

- 官网地址：https://www.rabbitmq.com
- Git地址：https://github.com/rabbitmq

RabbitMQ 是一个消息中间件：它接受并转发消息。

你可以把它当做一个快递站点，当你要发送一个包裹时，你把你的包裹放到快递站，快递员最终会把你的快递送到收件人那里，按照这种逻辑 RabbitMQ 是 一个快递站，一个快递员帮你传递快件。RabbitMQ 与快递站的主要区别在于，它不处理快件而是接收， 存储和转发消息数据。

![](https://mmbiz.qpic.cn/sz_mmbiz_png/tuSaKc6SfPq6GaWyPzeRVaeLaRkgY9rSUDXZYXfMljBvbWtxUIYm9vOucwB2jQptPKx5gXm0KTTJUOWEuoMNicQ/640?wx_fmt=png&wxfrom=5&wx_lazy=1&wx_co=1&tp=webp)

[硬卷消息中间件系列（一）：RabbitMQ 入门（核心概念与架构）](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247543674&idx=2&sn=cf13587eaaa2d8a5d441cd4ad169bdcc&chksm=e9184e66de6fc770035dfbff41ee91d7e6205482b7c45c8f0a31f29b266750e2fc2d2aae2a63&scene=21#wechat_redirect)  

[硬卷消息中间件系列（二）：RabbitMQ 安装与简单使用](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247543715&idx=2&sn=8480dbe0d3bcd46dbf404061f919176f&chksm=e9184ebfde6fc7a9e829383f8589729f93f089907364e4b90b020c10fa53ef4018525c5412e2&scene=21#wechat_redirect)  

[硬卷消息中间件系列（三）：RabbitMQ 基础配置](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247543745&idx=2&sn=03a2b6f5ebb52ca1de1bc3df2f64340f&chksm=e9184eddde6fc7cba5271b81226cccdfdd2ad18ac269237362082eb389ba2486b02f59647635&scene=21#wechat_redirect)  

[硬卷消息中间件系列（四）：RabbitMQ 管理界面详解](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247543793&idx=2&sn=b678505bc97598184e212722c097678a&chksm=e9184eedde6fc7fb529e7b3a8aa7bf55a69959c070e5211de90926557e8c9c3bb61dda6e6ff4&scene=21#wechat_redirect)  

[硬卷消息中间件系列（五）：RabbitMQ 常用 API](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247543801&idx=2&sn=bed682c62b594be9b7af9afc21498f62&chksm=e9184ee5de6fc7f30ea5bb4090af51a81ebe3aa20faa0fd8e859a0ca68ec696fdcf97863184e&scene=21#wechat_redirect)  

[硬卷消息中间件系列（六）：RabbitMQ 消息收发与交换机详解](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247543843&idx=2&sn=22f46be9cd9d3cc88ecf54887579c11d&chksm=e918493fde6fc02966bc888ba93d521d5f7ed56c33259f67d4bafbe97e5a0e8e2fe72cc3f670&scene=21#wechat_redirect)  

[硬卷消息中间件系列（七）：RabbitMQ 消息确认机制详解](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247543851&idx=2&sn=394dc8d511c3f24ad0fc316124e093bf&chksm=e9184937de6fc021b52eb5d34fd003058343790ccaa25b820e2e3f6ff6e9ffd0a432ff1cce27&scene=21#wechat_redirect)  

[硬卷消息中间件系列（八）：RabbitMQ 重试机制详解](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247543877&idx=2&sn=41a5c7966e6f4860afd6aa4e8a35e2ff&chksm=e9184959de6fc04fe9ef015459cd214742add148c142d4b5719f4e57b1658d9aa7a6b7908fc4&scene=21#wechat_redirect)  

[硬卷消息中间件系列（九）：RabbitMQ 队列与消息过期](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247543911&idx=2&sn=5f3a1fa1af58a4ae65f3591e7e6ca802&chksm=e918497bde6fc06dd50eb2a72fafcc86aaee416262859c529ce00f7a8f7ded0c789c53637564&scene=21#wechat_redirect)  

[硬卷消息中间件系列（十）：RabbitMQ 持久化、存储与内存管理](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247543967&idx=2&sn=eda9950e20d3f52839d59981c6d7b12b&chksm=e9184983de6fc0952b8d649c42224b15a0ebcf9ed8f173b5798a14d6669bb8eac90382e35ddf&scene=21#wechat_redirect)  

[硬卷消息中间件系列（十一）：RabbitMQ 流控、镜像队列、网络分区](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247544065&idx=2&sn=831cfe14f461b49ada493cd466471886&chksm=e918481dde6fc10bc0e185086681da9c66d3a6ef79c95d015cc855aaf7488d9c9b4a9d1bb1c9&scene=21#wechat_redirect)  

[硬卷消息中间件系列（十二）：RabbitMQ 单机多节点、多机集群部署](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247544249&idx=2&sn=4ad15cb1434f82f02a0aef62a9af85a7&chksm=e91848a5de6fc1b3307aa13eb9d09ca1227dd6172ce2c30a7ad8434f1fb6a6548a5bf4280ee8&scene=21#wechat_redirect)

[硬卷消息中间件系列（十三）：RabbitMQ 高可用集群部署](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247544279&idx=2&sn=9f130cbeffca5868f9cc8a6f766f7727&chksm=e91848cbde6fc1dd75e89ffece3ae643cfecce81bd6f625bb16bdb4393aa567c2c3797e66335&scene=21#wechat_redirect)  

[硬卷消息中间件系列（十四）：RabbitMQ 集群运维管理](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247544360&idx=2&sn=cc16a0477e305fd8681838502d4b24da&chksm=e9184b34de6fc22299033ac5257586f165507a49f0ca1127777d5e452cdf039c739563cd5bb3&scene=21#wechat_redirect)  

[硬卷消息中间件系列（十五）：RabbitMQ 之 Java 调用的三种方式](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247544438&idx=2&sn=bb441f585a47da3f109d0347a7502447&chksm=e9184b6ade6fc27c9c1a51cd594656d81baa5f6f901a3a851d05abc696e99e938676b69e6c1b&scene=21#wechat_redirect)  

[硬卷消息中间件系列（十六）：RabbitMQ 运维监控](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247544469&idx=2&sn=0191fdd47fde7e770f79670556a3e025&chksm=e9184b89de6fc29fd16a4328b21cf937bfa0260cd43cdb80004aa0bfe8645c573d6d08be0c60&scene=21#wechat_redirect)

#### Zookeeper

zooKeeper 是一个分布式的，开放源码的分布式应用程序协调服务，是Google的Chubby一个开源的实现，是Hadoop和Hbase的重要组件。

![](https://mmbiz.qpic.cn/sz_mmbiz_png/tuSaKc6SfPqG3LVUicxAnRwOxBCy1jHeAlwpyr7YhJc6K7oxSM907eFb4wDkw3vAmibYG1dPQOCfCkG5nIbKIg1Q/640?wx_fmt=png&wxfrom=5&wx_lazy=1&wx_co=1&tp=webp)

官方文档上这么解释zookeeper，它是一个分布式协调框架，是 Apache Hadoop 的一个子项目，它主要是用来解决分布式应用中经常遇到的一些数据管理问题，如：统一命名服务、状态同步服务、集群管理、分布式应用配置项的管理等。是一个为分布式应用提供一致性服务的软件。

![](https://mmbiz.qpic.cn/sz_mmbiz_png/tuSaKc6SfPqG3LVUicxAnRwOxBCy1jHeAy1V1Sa38rbPU6ZKHH2jQcIAgSpTgyL13cJb6amBYJOIdLQNZ9jibHJw/640?wx_fmt=png&wxfrom=5&wx_lazy=1&wx_co=1&tp=webp)

zooKeeper的目标就是封装好复杂易出错的关键服务，将简单易用的接口和性能高效、功能稳定的系统提供给用户。

官网：https://zookeeper.apache.org/

## 为什么要使用Zookeeper

在大型企业的开发中，服务的数量是十分庞大的。如果我们想要添加一个服务的话，那么就需要对文件进行重新覆盖，把整个容器重启。这样导致的结果是就是：波及影响太大，维护十分困难。

此时，便需要一个能够动态注册服务和获取服务信息的地方，来统一管理服务，这个地方便称为称为服务配置中心。而zookeeper不仅实现了对cusumer和provider的灵活管理，平滑过渡功能，而且还内置了负载均衡、主动通知等功能，使我们能够几乎实时的感应到服务的状态。能够很好的帮我们解决分布式相关的问题，至今仍是市面上主流的分布式服务注册中心技术之一。

![](https://mmbiz.qpic.cn/sz_mmbiz_png/tuSaKc6SfPqG3LVUicxAnRwOxBCy1jHeAu2V2drdDliasjRg1mSnSmciaSu13LHunMQKksDftrWtyHn1kA5tRlia3A/640?wx_fmt=png&wxfrom=5&wx_lazy=1&wx_co=1&tp=webp)

[进阶分布式系统架构系列（一）：Zookeeper 基础概念、功能与应用场景](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247542967&idx=2&sn=b58d8308d5286dc469ff1b326ae836f0&chksm=e9184dabde6fc4bd570349cf883ac507772e943f91a62434c354ee56d09b597fcd214c35f8c7&scene=21#wechat_redirect)  

[进阶分布式系统架构系列（二）：Zookeeper 典型应用场景详解](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247543023&idx=2&sn=60348091bcf9277e1fb796a280de74d2&chksm=e9184df3de6fc4e51b06893966284af8ae81590d272d9747bef03bc8b5b2df90213bb4409478&scene=21#wechat_redirect)  

[进阶分布式系统架构系列（三）：Zookeeper 部署（单机与集群）实践](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247543063&idx=2&sn=45dac46d0cd888e7b97efdcfb7244cb8&chksm=e9184c0bde6fc51d3633115814896548c93a99ce40bb77c07d6a0da4e1f6b58f54e3fbf1c47b&scene=21#wechat_redirect)  

[进阶分布式系统架构系列（四）：Zookeeper 常用管理命令](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247543132&idx=2&sn=aee6ac475262615dab2f4c001c1163a9&chksm=e9184c40de6fc55620b488dbce2e1a21602b3a51807b25e9e1b8b403c805653539ac7fddd528&scene=21#wechat_redirect)  

[进阶分布式系统架构系列（五）：Zookeeper 节点（znode）详解](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247543179&idx=2&sn=2f161aebde42156430e1c40d98d0ec3e&chksm=e9184c97de6fc581fd0588968c16b1a18577d12764f256d5c3c19603ad7efd4f4eaa5e49d60f&scene=21#wechat_redirect)  

[进阶分布式系统架构系列（六）：Zookeeper 选举机制](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247543207&idx=2&sn=3cd6519c4219fb7aecde9539ed994f96&chksm=e9184cbbde6fc5ad1e1ff770b9453b17088f6943bde1982515b881c83c782791ccb51c122654&scene=21#wechat_redirect)  

[进阶分布式系统架构系列（七）：Zookeeper 监听机制](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247543242&idx=2&sn=e7dbd33cabb7dff5849fcc1baa04b184&chksm=e9184cd6de6fc5c02e54ee32f82a1fb20095b8441582bcb11a03ae5f5467cf92162f823a1258&scene=21#wechat_redirect)  

[进阶分布式系统架构系列（八）：Zookeeper 集群 ZAB 协议](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247543254&idx=2&sn=6f30476c18ec31d76a2e30ce30633349&chksm=e9184ccade6fc5dcf99807e92a9b677265d1cf5c7cbbdd209c0c1d5ccfea849bdb2e69b2fa6c&scene=21#wechat_redirect)  

[进阶分布式系统架构系列（九）：Zookeeper 配置中心](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247543321&idx=2&sn=f3d1285ad435622f6568fe374d7a4f7b&chksm=e9184f05de6fc61311d2c3992182f4875536f066ae5d5290c32a2bef2cdd17d2e3eb20f6c419&scene=21#wechat_redirect)  

[进阶分布式系统架构系列（十）：Zookeeper 注册中心](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247543376&idx=2&sn=c9a1e43a714bb71df0cfa4a103a32e3f&chksm=e9184f4cde6fc65a1f92adcf35e0657c87d5615c520d586c9929227f98c1c7632bc5d9e43601&scene=21#wechat_redirect)  

[进阶分布式系统架构系列（十一）：Zookeeper 数据与存储管理](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247543394&idx=2&sn=36ddbfd1b17aed9a0ff5184de0980446&chksm=e9184f7ede6fc6688187cd1663463837d7f9c93934a14daf5714e35961f36709571771e4ecc9&scene=21#wechat_redirect)  

[进阶分布式系统架构系列（十二）：Zookeeper 会话与事务管理](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247543407&idx=2&sn=f4b15c9a1e3f1e5b05f5fcf560d8517a&chksm=e9184f73de6fc66565a146e3e7458035bad180f21a4ac5b7244c6fb852f1947ec8bc9b215337&scene=21#wechat_redirect)  

[进阶分布式系统架构系列（十三）：Zookeeper 分布式锁原理与实现](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247543435&idx=2&sn=9ffa76fb4d4b6404e8a68315b63ca33e&chksm=e9184f97de6fc681c0ce1b31f254383c193dcb11ef0bad1a90853bfc976bd021160d19e269df&scene=21#wechat_redirect)  

[进阶分布式系统架构系列（十四）：Zookeeper 开源客户端工具](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247543468&idx=2&sn=17b27ce9566741c10ab9e142a0af4125&chksm=e9184fb0de6fc6a6fe4d9a1bad507a3bce0f8a61d302feafde37f24c34364ac95358b5896776&scene=21#wechat_redirect)  

[进阶分布式系统架构系列（十五）：Zookeeper 可视化工具](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247543497&idx=2&sn=fbeb1542f406bc683845dbdc059653de&chksm=e9184fd5de6fc6c30ddc143bb2630b75dfa62d67414abb8d514565897b0eeea515572929f65a&scene=21#wechat_redirect)  

[进阶分布式系统架构系列（十六）：Zookeeper 实战（基于 kafka 实现的日志收集平台）](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247543569&idx=2&sn=6a7cad9d3fe58219fc8883267ea7d624&chksm=e9184e0dde6fc71bdb76328a5722089187615f7ccee31829d8adb5d63ce17741781bccc69d10&scene=21#wechat_redirect)  

[进阶分布式系统架构系列（十七）：Zookeeper 运维实践经验总结](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247543599&idx=2&sn=4f7c59b63d4e11a0c97f00a63d20f956&chksm=e9184e33de6fc725b13ea7e46e93435c9efc266ddf8729b864e25bd7aee468667f73689458b7&scene=21#wechat_redirect)

## Docker 容器技术

介绍 docker入门、安装、常用的命令、三剑客、私有仓库搭建以及容器监控等方面的总结。

![](https://mmbiz.qpic.cn/sz_mmbiz_png/tuSaKc6SfPpYiaNgWlY4EL9GcKCXdVWzWRQ26uowHM76CN6f1RhCo2Z8UYTkCPHdWrSdNXhgpR8p6EgJqptlnAA/640?wx_fmt=png&from=appmsg&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)

详细内容可查阅专栏：[Docker](https://mp.weixin.qq.com/mp/appmsgalbum?__biz=MzI0MDQ4MTM5NQ==&action=getalbum&album_id=1479950328543444997#wechat_redirect)

## Kubernetes 技术实践

介绍 Kubernetes 技术实践知识体系。从原理、部署开始，逐步深入去学各个知识点，比如：Pod 的实现原理、YAML语法、Kubectl使用指南、资源控制、数据存储、Harbor仓库、资源清单、服务发现、Ingress 服务、集群调度、集群管理工具、面试题、生产实践等。

![](https://mmbiz.qpic.cn/sz_mmbiz_png/tuSaKc6SfPpYiaNgWlY4EL9GcKCXdVWzWon4FcmSA2zjQmmO3CIN9I1ic7sAM69KY6tSYbkWNUGr1qsZFk8AsicjA/640?wx_fmt=png&from=appmsg&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)

详细内容可查阅专栏：[k8s 技术实践](https://mp.weixin.qq.com/mp/appmsgalbum?__biz=MzI0MDQ4MTM5NQ==&action=getalbum&album_id=1790241575034290179#wechat_redirect)

## 大数据运维体系

#### 大数据概述

大数据（big data），指的是在一定时间范围内不能以常规软件工具处理（存储和计算）的大而复杂的数据集。说白了大数据就是使用单台计算机没法在规定时间内处理完，或者压根就没法处理的数据集。

#### 大数据的特性
- `大量 (Volume)`	：大数据的“大”首先体现在数据量上。在实际应用中，大数据的数据量通常高达数十 TB，甚至数百 PB。
- `高速 (Velocity)`：大数据的“高速”指高速接收乃至处理数据 — 数据通常直接流入内存而非写入磁盘。
- `多样化 (Variety)`：多样化是指数据类型众多。
  
Hadoop 是用于处理大数据的工具之一。Hadoop 和其他软件产品通过特定的专有算法和方法来解释或解析大数据搜索的结果。

![](https://mmbiz.qpic.cn/sz_mmbiz_png/tuSaKc6SfPpYiaNgWlY4EL9GcKCXdVWzWEmxmRDQ99pFsWnayrlVjr97uvF3farIWPt7J0ibUM8O3WEhL82mt3mQ/640?wx_fmt=png&from=appmsg&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)

在大数据处理上，Hadoop并非是唯一的分布式处理架构，但是对于大部分的企业来说，**基于Hadoop已经能够满足绝大部分的数据需**求，因此才会成为现在的主流选择。

[进击大数据系列（一）：Hadoop 基本概念与生态介绍](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247540481&idx=2&sn=8ffa5830531cc6c902a769b241abfafd&chksm=e9183a1dde6fb30bd1f284f9c26f93bc1b7225bd6ec5d3d93a0363d2e8de7c12cef08b9d6489&scene=21#wechat_redirect)  

[进击大数据系列（二）：Hadoop 安装（HDFS+YARN+MapReduce）实战操作](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247540535&idx=2&sn=e9abb986580725a2d7073a3802f69e23&chksm=e9183a2bde6fb33db4be370fba94df4f7fe7e71ac2c9c48f546825a9cba40c0253c90d185a5f&scene=21#wechat_redirect)  

[进击大数据系列（三）：Hadoop 常用命令介绍](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247540545&idx=2&sn=f42bbb7693572d4444915d111ba1696a&chksm=e9183a5dde6fb34b4e09fec8504a5f002285a4c6872520361c96f5c5e34c53a20ca54db6b854&scene=21#wechat_redirect)  

[进击大数据系列（四）：Hadoop 架构基石分布式文件系统 HDFS](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247540803&idx=2&sn=a21544c9759b353d8ffe13901acf2bf8&chksm=e918455fde6fcc4970e2cf710feaf5c920c0b116194fc10d77b3f7683e698b9595e7fca99d3c&scene=21#wechat_redirect)  

[进击大数据系列（五）：Hadoop 统一资源管理和调度平台 YARN](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247540804&idx=2&sn=c9a5fc6569b634023f12403f96b107dc&chksm=e9184558de6fcc4e0540ec7e5860868d756cef6977d7d5aba943821d6b4f542f386fd559e67d&scene=21#wechat_redirect)  

[进击大数据系列（六）：Hadoop 分布式计算框架 MapReduce](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247540852&idx=2&sn=efde8d81319a219491df6704ef50f0eb&chksm=e9184568de6fcc7e1c3b22f6abd69e71ded850e937c19e7ca68d4fd999967fdf2fcad81d4ede&scene=21#wechat_redirect)  

[进击大数据系列（七）：Hadoop 数据仓库 Hive](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247540920&idx=2&sn=1c8c5fab69c725ac231880c5d7233456&chksm=e91845a4de6fccb23f5da97901f968d8c3f0c47559e93db16aeeef110a4221c3ef004005c50e&scene=21#wechat_redirect)  

[进击大数据系列（八）Hadoop 通用计算引擎 Spark](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247540973&idx=2&sn=14e2e330cb018303d5275abe831d40b4&chksm=e91845f1de6fcce7e95dc19ea227486d3e65de710fa153c7eb7fd437528de9d05adc389cf7ca&scene=21#wechat_redirect)  

[进击大数据系列（九）Hadoop 实时计算流计算引擎 Flink](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247541075&idx=2&sn=4499caa6a894a50ad907e9d05aea6b34&chksm=e918444fde6fcd59635632b670f34975dfee328769e9cee109be897bd1f5818b03b5f871326d&scene=21#wechat_redirect)  

[进击大数据系列（十）Hadoop 架构数据库 Hbase](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247541112&idx=2&sn=980a220e97ed593d917ddb9c59248037&chksm=e9184464de6fcd72680c2d4e352fc6e3a88a8da3a48b8b16daad8004c843e4e25544391936d1&scene=21#wechat_redirect)  

[进击大数据系列（十一）Hadoop 任务调度框架 Oozie](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247541129&idx=2&sn=b46af6495c30aaa8fd74f1e974219057&chksm=e9184495de6fcd83b0d39dfa559d0f22a46cf4fd24a49039b8f2ea18a6a596728170823967f8&scene=21#wechat_redirect)  

[进击大数据系列（十二）Hadoop 数据同步工具 Sqoop](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247541165&idx=2&sn=e97d4238f5d08ac1fa75996e2f3a28dd&chksm=e91844b1de6fcda77f0e8804562af1d0683a49c740e5bc11e62bf31fee8b2c8dc275dbfc9d85&scene=21#wechat_redirect)  

[进击大数据系列（十三）Hadoop 分布式日志采集系统 Flume](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247541238&idx=2&sn=b1867cf4c716c5242bf1e7116aa8fc8f&chksm=e91844eade6fcdfc05f067596eba3527155ed9bc87701639b9e01d2ddba87ee381cccdfad438&scene=21#wechat_redirect)  

[进击大数据系列（十四）Hadoop 数据分析引擎 Apache Pig](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247541239&idx=2&sn=dbf5f400e97c0efb57caf45b93b5bba0&chksm=e91844ebde6fcdfdbe7058368a0c274e4ebd739f6a874c8c4634d9886be4263739beeed2f8da&scene=21#wechat_redirect)  

[进击大数据系列（十五）Hadoop 图形化管理系统 Hue](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247541291&idx=2&sn=18a29fe8be91ac33e45b121654ee221a&chksm=e9184737de6fce21bf81f76b288b5a8c2b862a941002d98c2838098b7acdebe05c9f13dc4987&scene=21#wechat_redirect)  

[进击大数据系列（十六）Hadoop 性能优化与运维](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247541397&idx=2&sn=d1a0a98bacb64fc4050d3854138338a7&chksm=e9184789de6fce9f6d4d41a81c41deb67890edcbccaa054f2b77dfb10d5a509be6191a82c12c&scene=21#wechat_redirect)

## 企业集群运维管理

![](https://mmbiz.qpic.cn/sz_mmbiz_png/tuSaKc6SfPqCWmLQTrmVJKXmj7jFudSoYWYnKELXDehHCQ9RDHC0H9jgxhKzDNuQLO3xrujaALPZuam0SLTuLQ/640?wx_fmt=png&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)

#### 大型网站面临的挑战

大型网站都要面对庞大的用户量，高并发，海量数据等挑战。为了提升系统整体的性能，可以采用垂直扩展和水平扩展两种方式。

垂直扩展：在网站发展早期，可以从单机的角度通过增加硬件处理能力，比如 CPU 处理能力，内存容量，磁盘等方面，实现服务器处理能力的提升。但是，单机是有性能瓶颈的，一旦触及瓶颈，再想提升，付出的成本和代价会极高。这显然不能满足大型分布式系统（网站）所有应对的大流量，高并发，海量数据等挑战。

水平扩展：通过集群来分担大型网站的流量。集群中的应用服务器（节点）通常被设计成无状态，用户可以请求任何一个节点，这些节点共同分担访问压力。水平扩展有两个要点：
- 应用集群：将同一应用部署到多台机器上，组成处理集群，接收负载均衡设备分发的请求，进行处理，并返回相应数据。
- 负载均衡：将用户访问请求，通过某种算法，分发到集群中的节点。  

#### 什么是集群

集群是一组协同工作的服务集合，用来提供比单一服务更稳定、更高效、更具扩展性的服务平台。

在集群的内部，有两个或两个以上的服务实体在协调、配合完成一系列复杂的工作。
- 集群一般由两个或两个以上的服务器组建而成。每个服务器称为一个集群节点，集群节点之间可以相互通信。    
- 集群应该具有节点间服务状态监控功能，同时还必须具有服务实体的扩展功能，可以灵活地增加和剔除某个服务实体。   
- 集群应该具有故障自动切换功能：在集群中，同样的服务可以由多个服务实体提供。因而，当一个节点出现故障时，集群的另一个节点可以自动接管故障节点的资源，从而保证服务持久、不间断运行。    
- 一个集群系统必须拥有共享的数据存储 ：因为集群对外提供的服务是一致的，任何一个集群节点运行一个应用时，应用的数据都集中存储在节点共享空间内。而每个节点的操作系统上仅运行应用的服务，同时存储应用程序文件。    

#### 什么是高可用

高可用（High availability,缩写为 HA)，是指系统无中断地执行其功能的能力，代表系统的可用性程度。高可用的主要目的是为了保障“业务的连续性”，即在用户眼里，业务永远是正常对外提供服务的。

高可用是一种控制风险的能力，是一种面向风险设计，使系统具备控制风险，提供更高的可用性的能力。简单可以理解为通过种种措施使系统对外不间断地提供服务，保证服务的响应时间，减少因软件、硬件、人为造成的故障对服务的影响，在故障发生时，访问服务的用户并不会感觉到。核心就是自动检测，自动切换，自动恢复，模式有主从、双主、集群方式。

[玩转企业集群运维管理系列（一）：负载均衡基础入门](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247546852&idx=2&sn=e4e7800e1729356d83cc63b99c7eb84f&chksm=e91852f8de6fdbeef487ee3ae305b28696464185f8aa92ec6815ac6d4132c518ab55383833a8&scene=21#wechat_redirect)  

[玩转企业集群运维管理系列（二）：主流软件负载均衡器(LVS、Nginx、HAproxy)对比](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247546873&idx=2&sn=e0201f210c51769da28ecbc6edbce388&chksm=e91852e5de6fdbf3031d127dc8ae8aad8f2a90ed77a0a118c5a3fd625f3bc7dff1f8635ace3a&scene=21#wechat_redirect)  

[玩转企业集群运维管理系列（三）：Nginx 负载均衡原理与实践](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247546904&idx=2&sn=e55d96392832e8706f49b4c508387b72&chksm=e9185d04de6fd4126c4074e46bc2e1df458d710eef2738fdfa14396c26eed95193697f435659&scene=21#wechat_redirect)  

[玩转企业集群运维管理系列（四）：Nginx 七层与四层反向代理详解](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247546952&idx=2&sn=694ea1ec46904f9a10b39ad04626b404&chksm=e9185d54de6fd44226d910283f85a3627b35261e02fd8fa64282de048320735429f7b4f0a279&scene=21#wechat_redirect)  

[玩转企业集群运维管理系列（五）：LVS 负载均衡原理与实践](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247546991&idx=2&sn=a1030ece6e498396f7e49489c3751ea9&chksm=e9185d73de6fd465f67dacadce7fae87a8f62986d482786a571424f3fa717334057f50cdca34&scene=21#wechat_redirect)  

[玩转企业集群运维管理系列（六）：LVS 负载均衡（四种模式）集群配置实践](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247547001&idx=2&sn=5d168e6759e4b357439800ffe5d6e33c&chksm=e9185d65de6fd4736ab2abc6c6c1f7503ddd52ccbcac03fd096f8ecd9ed670a50a170abe4fe8&scene=21#wechat_redirect)  

[玩转企业集群运维管理系列（七）：Haproxy 负载均衡详解](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247547077&idx=2&sn=d4216c4cd5a7c5baf33a329cd377fde9&chksm=e9185dd9de6fd4cf9dd381b7befbf13e2747629a800cb706b624901cf7bd5e8ae7e800448a6b&scene=21#wechat_redirect)  

[玩转企业集群运维管理系列（八）：Haproxy 负载均衡集群部署实践](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247547132&idx=2&sn=ca40b5b06f6f2581ad446651a0c9f076&chksm=e9185de0de6fd4f6e699d471625f00dc01b44c9fa211418b45a840130b09bad8e65e455f3c26&scene=21#wechat_redirect)  

[玩转企业集群运维管理系列（九）：企业集群高可用架构详解](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247547133&idx=2&sn=0776055620049d16c7726185223267db&chksm=e9185de1de6fd4f79ea82297b03f991ae5c2efa60d2500877a38b05d51e4a9fe39787f893248&scene=21#wechat_redirect)  

[玩转企业集群运维管理系列（十）：企业集群高可用软件 Keepalived 详解](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247547143&idx=2&sn=899b901833a3aba61e7010c7fc5e930c&chksm=e9185c1bde6fd50d65ca9d19436b9d90727c776e66450c4e236903873b7536f5805e231c4e3f&scene=21#wechat_redirect)  

[玩转企业集群运维管理系列（十一）：企业集群高可用软件 Keepalived 部署实践](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247547202&idx=2&sn=870215816f31e545f48dcfb9fc6be6b8&chksm=e9185c5ede6fd548095f4e0dbfd7e64ca630424770e1250f3621d2dd8339282798f9faf6da5e&scene=21#wechat_redirect)  

[玩转企业集群运维管理系列（十二）：Keepalived 双主、非抢占模式及脑裂问题详解](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247547216&idx=2&sn=3a6e9794a73173ae8e6689aa01a1773e&chksm=e9185c4cde6fd55a8fed05887d3c172edac14909e5e0232f956716342a8eb077569115cfed67&scene=21#wechat_redirect)  

[玩转企业集群运维管理系列（十三）：集群高可用软件 HeartBeat 详解](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247547245&idx=2&sn=6d9e4eaf4fea829736dca5fe00cc7a20&chksm=e9185c71de6fd5671e1f204d8a8f287d093418bd059a241efc07fe5a08e0ab00ec2bd9a38a57&scene=21#wechat_redirect)  

[玩转企业集群运维管理系列（十四）：Heartbeat 高可用集群部署](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247547266&idx=2&sn=2dbe3c139a96c7a4f1119ed25cc90a67&chksm=e9185c9ede6fd5882637281d58824fda0681272ae492c9132d3ad15361bd94cae7580b4e7f5d&scene=21#wechat_redirect)  

[玩转企业集群运维管理系列（十五）：DRBD 原理与部署实践](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247547282&idx=2&sn=56036e4d726c5a8f5739369b6cff8736&chksm=e9185c8ede6fd598b515c3cfd090de3eaab97973860a61d8e0854ee9f00f4ed61c2eb746a4b5&scene=21#wechat_redirect)  

[玩转企业集群运维管理系列（十六）：DRBD 配置文件与运维管理](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247547288&idx=2&sn=566d8d61f1dc3c903749a73994880da8&chksm=e9185c84de6fd5920d18fe1c04a1e2015b7d5b0c49404d99fb2dc906852769a332cb451d8dd7&scene=21#wechat_redirect)  

[玩转企业集群运维管理系列（十七）：高可用集群架构 corosync+pacemaker](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247547303&idx=2&sn=b93a7c4a440adec0d109dc30afdf5fad&chksm=e9185cbbde6fd5ada6e12b4a5dc250996f70bb6414849b7d0e87e84a7c7b7ca50cbb9bf26758&scene=21#wechat_redirect)  

[玩转企业集群运维管理系列（十八）：LVS+KeepAlived 高可用负载均衡集群原理与实践](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247547336&idx=2&sn=aeffca387ccf2f4b61fdb084d16c3f24&chksm=e9185cd4de6fd5c2597ad3c4f03d55a55cb76aeb437494358da3687110d92dc7e3bdd3da91d1&scene=21#wechat_redirect)  

[玩转企业集群运维管理系列（十九）：Haproxy+Keepalived+Nginx 实现 K8s 集群负载均衡](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247547347&idx=2&sn=1579c13bbaf20b21c3e139f85b2645b9&chksm=e9185ccfde6fd5d92808ca5f1faacd9a76e4b5baa57286edcd645434825dbd915930e94e511a&scene=21#wechat_redirect)  

[玩转企业集群运维管理系列（二十）：Pacemaker+Corosync 高可用架构实战](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247547406&idx=2&sn=eb0465a86679c1180379f59f3b838fbd&chksm=e9185f12de6fd6043da9212f34ee1f68124ce22ee6f52f00d34ee2434306523b3f99c845ddd0&scene=21#wechat_redirect)  

[玩转企业集群运维管理系列（二十一）：高可用集群管理工具 RHCS 详解](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247547451&idx=2&sn=1127e159b3734611d22f9c91486a80b1&chksm=e9185f27de6fd6310439e038a49109a83178b5e88094f97d6719954d7f726530fac7392d1347&scene=21#wechat_redirect)

## 分布式存储

分布式文件系统是分布式领域的一个基础应用，其中最著名的毫无疑问是 HDFS/GFS/ceph/MinIO 。如今该领域已经趋向于成熟，但了解它的设计要点和思想，对我们将来面临类似场景/问题时，具有借鉴意义。

![](https://mmbiz.qpic.cn/sz_mmbiz_png/tuSaKc6SfPpYiaNgWlY4EL9GcKCXdVWzW4fLicm8cjAuicdCexa7ozbl51ymrKhABHxygxxQ9FwdRV79Iysg6mPBA/640?wx_fmt=png&from=appmsg&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)

详细内容可查阅专栏：[分布式存储技术实践](https://mp.weixin.qq.com/mp/appmsgalbum?__biz=MzI0MDQ4MTM5NQ==&action=getalbum&album_id=2697652031347687427#wechat_redirect)

## 代码管理（Git）

作为目前世界上**最先进的分布式版本控制系统（没有之一）**，Git 是一个开源的分布式版本控制软件,用以有效、高速的处理从很小到非常大的项目版本管理。Git 最初是由Linus Torvalds设计开发的，用于管理Linux内核开发。随着时间的推移，Git 发展到今天，已经成为了众多开发者必备的开发工具。

![](https://mmbiz.qpic.cn/sz_mmbiz_png/tuSaKc6SfPpYiaNgWlY4EL9GcKCXdVWzWkBrUOy50zNPickn93kGuDibNVQQEMerdkAB5SqQpbJa5QzGARcwyIDAQ/640?wx_fmt=png&from=appmsg&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)

详细内容可查阅专栏：[Git 技术](https://mp.weixin.qq.com/mp/appmsgalbum?__biz=MzI0MDQ4MTM5NQ==&action=getalbum&album_id=1790418411420778499#wechat_redirect)

## 企业级云计算平台 Openstack

云计算平台也称为云平台，是指基于硬件资源和软件资源的服务，提供计算、网络和存储能力。云计算平台可以划分为3类：以数据存储为主的存储型云平台，以数据处理为主的计算型云平台以及计算和数据存储处理兼顾的综合云计算平台。

![](https://mmbiz.qpic.cn/sz_mmbiz_png/tuSaKc6SfPpYiaNgWlY4EL9GcKCXdVWzWvYRNhYJB4VbhC88fDjukFibRdIDTP7nyJ48zPUB3mdmwUEXGTQJN5ng/640?wx_fmt=png&from=appmsg&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)

OpenStack 是由一系列具有 RESTful 接口的Web服务所实现的，是一系列组件服务集合。Openstack 是一个云平台管理的项目，我们可以使用Openstack来构建一个私有云架构，并提供IaaS的云服务。Openstack 包含三大项：计算、网络和存储。其主要目标是简化资源的配置和管理，把计算、网络和存储资源抽象成虚拟资源池，并根据需要对外提供服务。

[玩转企业云计算平台系列（一）：OpenStack 基础入门](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247547507&idx=2&sn=389d393ea184f62fede318a86fd8b239&chksm=e9185f6fde6fd679359e7791b4e84d6ed01a1c8ce8785a24bcf4fe8e9af0ea51ea23a3d97e43&scene=21#wechat_redirect)  

[玩转企业云计算平台系列（二）：Openstack 基础环境部署](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247547590&idx=2&sn=e7006ec77b12f8cca2bf28a18b19448e&chksm=e9185fdade6fd6cc4a4e7019a063b3fb1dadf2908b08d64e1ae2dbace4a0b80e09df8c172fec&scene=21#wechat_redirect)  

[玩转企业云计算平台系列（三）：Openstack 身份认证服务 Keystone](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247547643&idx=2&sn=9aa65650b5157b556d2ec71f7f4d415c&chksm=e9185fe7de6fd6f15589f5130893b9c41e89aa957724670a670fe5c67fa10836d09cb9f3bb6b&scene=21#wechat_redirect)  

[玩转企业云计算平台系列（四）：Openstack 镜像服务 Glance](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247547682&idx=2&sn=62037003d749de0eae416d12bd966022&chksm=e9185e3ede6fd7285920ea5918de823eec0b04ac025f0b5fa4e920647e400b5dab2a032a2125&scene=21#wechat_redirect)  

[玩转企业云计算平台系列（五）：Openstack 计算服务 Nova](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247547740&idx=2&sn=03e69aed20d191b25999933b67aa8dab&chksm=e9185e40de6fd756ad52a9d055414458c4ecf40092bf96517d50d9d8f57dd5912e77ca257b3c&scene=21#wechat_redirect)  

[玩转企业云计算平台系列（六）：Openstack 网络服务 Neutron](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247547993&idx=2&sn=14f3777b7601d58eed2c869c771ed72b&chksm=e9185945de6fd05371983b99a8f9135bd590512fa319e01371c079764166ab9a49c4aa102b9b&scene=21#wechat_redirect)

[玩转企业云计算平台系列（七）：Openstack 控制面板服务 Horizon](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247548092&idx=2&sn=5e0335bfa6f9c5e5e559a5a3f8108c79&chksm=e91859a0de6fd0b6e837d87ddd3f3a83df275bf31f9c2ec6ed2a9c24e819f4bb695e954748fe&scene=21#wechat_redirect)  

[玩转企业云计算平台系列（八）：Openstack 块存储服务 Cinder](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247548135&idx=2&sn=2ba41a36727189b43a3828f09b8b5b32&chksm=e91859fbde6fd0eda1b0e30a816e4325aa941bf90be8b90e36ec3dfc3db44068d22dd7066514&scene=21#wechat_redirect)  

[玩转企业云计算平台系列（九）：Openstack 对象存储服务 Swift](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247548159&idx=2&sn=5c41a02ceaab2c9ca174bfc9eab07fca&chksm=e91859e3de6fd0f5bce36680357c7d83b6015914e3525badb3d71b0ca207055bbfe5d9dfd822&scene=21#wechat_redirect)  

[玩转企业云计算平台系列（十）：Openstack 基础组件使用介绍](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247548232&idx=2&sn=3fcf5b850efce6bb4aeba57e05f41c2f&chksm=e9185854de6fd142ba0e29e5836fe562d1fe19314634c55ac47bd12377d561b32f6fb0efe575&scene=21#wechat_redirect)  

[玩转企业云计算平台系列（十一）：Openstack 编排服务 Heat](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247548254&idx=2&sn=f130daa3358aede3c6e24155d3e33f55&chksm=e9185842de6fd154c73cbc7677c6247731690210e925e0b8ae7c2511796629b57af8d42cf021&scene=21#wechat_redirect)  

[玩转企业云计算平台系列（十二）：Openstack 文件共享服务 Manila](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247548255&idx=2&sn=519d68e6f82643ce0f217c1b2656d4e3&chksm=e9185843de6fd1550cf019b2ad190a1efcd6e91d3c2732f10629f5c3c21ebc2ad20906b6e90f&scene=21#wechat_redirect)  

[玩转企业云计算平台系列（十三）：Openstack 容器管理服务 Zun](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247548332&idx=2&sn=9f2440a883f5a3f376412fb7d493d7da&chksm=e91858b0de6fd1a6e444a077740a486e6655169e070ddd832e4a0c095a8358feb19ea7e378bc&scene=21#wechat_redirect)  

[玩转企业云计算平台系列（十四）：Openstack 密钥管理服务 Barbican](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247548332&idx=3&sn=5ca485c70b58d65dad30d2f081d4df33&chksm=e91858b0de6fd1a630f6b48cf9a53980898914a9aaf0be8329335a3c8816a758c7e9c85f8b98&scene=21#wechat_redirect)  

[玩转企业云计算平台系列（十五）：Openstack 计费服务 Cloudkitty](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247548332&idx=4&sn=80f4a6a64332eeb26c41a26b1feb6b05&chksm=e91858b0de6fd1a63b280d0bf12a112d40e28d8aa0412e9216dad543a11c70e3596684131711&scene=21#wechat_redirect)  

[玩转企业云计算平台系列（十六）：Openstack Telemetry 系统架构](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247548332&idx=5&sn=08afd576364485e394cc62487ba463e3&chksm=e91858b0de6fd1a65f98b71ebcdae8ea99b86aeb1a040caf21717a167315be3e5c77b8cf3bdb&scene=21#wechat_redirect)  

[玩转企业云计算平台系列（十七）：Openstack 大数据项目 Sahara](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247548332&idx=6&sn=12ee07b7e323ee4fa5db40e403a7b12a&chksm=e91858b0de6fd1a6367c608a9e60e2cda3823385bc75e4e47b6ef76ec58f608be70b4ce51c10&scene=21#wechat_redirect)  

[玩转企业云计算平台系列（十八）：Openstack 部署常见问题及解决方案](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247548332&idx=7&sn=fe1d3aac46e84873e04c8a47968ebd75&chksm=e91858b0de6fd1a63862d149642dac05d732e60ecd5ca4ac8c9859c8d450361605e8143b9f0d&scene=21#wechat_redirect)  

###### Openstack优势

- 模块松耦合：与其他开源软件相比，OpenStack模块分明。添加独立功能的组件非常简单。有时候，不需要通读整个OpenStack的代码，只需要了解其接口规范及API使用，就可以轻松地添加一个新的模块
- 组件配置较为灵活：OpenStack也需要不同的组件。但是OpenStack的组件安装异常灵活。可以全部都装在一台物理机上，也可以分散至多个物理机中，甚至可以把所有的结点都装在虚拟机中。
- 二次开发容易：OpenStack发布的OpenStack API是Rest-full API。其他所有组件也是采种这种统一的规范。因此，基于OpenStack做二次开发，较为简单。而其他3个开源软件则由于耦合性太强，导致添加功能较为困难。
- 兼容性：OpenStack兼容其他公有云，方便用户进行数据迁移。
- 可扩展性：模块化设计，可以通过横向扩展，增加节点、添加资源。

## 日志平台

介绍日志平台相关的日常运维所需知识体系，日志管理也是日常工作中非常重要的一项内容。比较主流的是ELK stack和Graylog。ELK目前很多公司都在使用，是一种很不错的分布式日志解决方案。

![](https://mmbiz.qpic.cn/sz_mmbiz_png/tuSaKc6SfPpYiaNgWlY4EL9GcKCXdVWzWAIkEylOEoObEVwFicIicgnoy3nriceLcsMmqY9WV0GUxibnccnpxaOl2fQ/640?wx_fmt=png&from=appmsg&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)

详细内容可查阅专栏：[日志平台](https://mp.weixin.qq.com/mp/appmsgalbum?__biz=MzI0MDQ4MTM5NQ==&action=getalbum&album_id=1790404884605829126#wechat_redirect)。

## 企业生产监控

监控系统是整个运维环节，乃至整个产品生命周期中最重要的一环，事前及时预警发现故障，事后提供翔实的数据用于追查定位问题。企业生产环境监控系统介绍，包括但不限于各类工具（Zabbix、Prometheus 等）安装、配置、优化与实践经验总以及排错等，详细的监控工具使用可查阅专栏：[监控工具](https://mp.weixin.qq.com/mp/appmsgalbum?__biz=MzI0MDQ4MTM5NQ==&action=getalbum&album_id=1803140860667101185#wechat_redirect)。

企业的IT架构逐步从传统的物理服务器，迁移到以虚拟机为主导的 IaaS 云，抑或当前流行的容器云PaaS 平台。无论基础架构如何调整，都离不开监控系统的支撑。

![](https://mmbiz.qpic.cn/sz_mmbiz_png/tuSaKc6SfPo7h84rC1zM8kKTRrnVNbMHuStqasNHHL5WX3sticMHK9XICgyGf3mI8vbQAkNUkyee39TGbniar9Ww/640?wx_fmt=png&wxfrom=5&wx_lazy=1&wx_co=1&tp=webp)

监控系统处理能提供实时监控和告警，还能辅助决策，所有决策都以数据为支撑，而非主观臆断。在大数据时代，数据变得越来越重要，监控数据不仅能提供实时状态展现，更能帮助故障回溯和预测风险等。当我们充分了解当前数据中心的真实资源使用情况时，才能绝对是否需要迁移服务、重新调度资源、清理垃圾数据及采购新的服务器。在故障发生后，通过分析历史监控数据，可以准确定位故障源，确定故障的发生时间及持续时间等，从而避免后续相关故障的发生。
- 从监控对象的角度来看，可以将监控分为网络监控、存储监控、服务器监控和应用监控等。    
- 从程序设计的角度来看，可以将监控分为基础资源监控、中间件监控、应用程序监控和日志监控。  

[构建企业级监控平台系列（一）：监控系统概述及发展趋势](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247544489&idx=2&sn=5e448be7e4a336a7da3aac8ce2ccbc1e&chksm=e9184bb5de6fc2a35e2db13823291d453432b736e9f93b43fede69c86f2ff5796031b58f7d17&scene=21#wechat_redirect)

[构建企业级监控平台系列（二）：如何做好企业监控系统运维管理？](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247544504&idx=2&sn=f3a9d7a961e57cb314670f862a1c3ee7&chksm=e9184ba4de6fc2b24d4631c9631516d5a34b4ef209116b8cbb698ad41e16211e2ff8bbb013f9&scene=21#wechat_redirect)

[构建企业级监控平台系列（三）：企业常用监控工具介绍](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247544621&idx=2&sn=b27d2a9beb77a635fc4031f22bdd3c57&chksm=e9184a31de6fc3275dbbaf39c3b0e9fdad7003a1947804db9f726fe7ddff638d0631f543af2e&scene=21#wechat_redirect)

[构建企业级监控平台系列（四）：企业数据库监控详解](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247544645&idx=2&sn=6fb5c876a8abb1b42db2d09a6dd9692b&chksm=e9184a59de6fc34fedacc26ee15c1280d091c06264ebbc080ff83370d57abaef713f7ec3bea7&scene=21#wechat_redirect)

[构建企业级监控平台系列（五）：Zabbix、Prometheus 等开源监控系统对比分析](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247544677&idx=2&sn=2d30d4d057626c6449b128c78fec9600&chksm=e9184a79de6fc36f1366b530f5c7ac8b72f45ede345d0ff132724b122b4964a94e206c18c6b3&scene=21#wechat_redirect)  

[构建企业级监控平台系列（六）：Zabbix 简介与安装部署](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247544752&idx=2&sn=b355f9fe712173eb451001a0e1a84a50&chksm=e9184aacde6fc3ba4d5644881a52f649dad7e75210c8260774b0cdee793a99e0bba387f40a26&scene=21#wechat_redirect)  

[构建企业级监控平台系列（七）：Zabbix 基础配置介绍](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247544797&idx=2&sn=e23dc3abc2132d67bb5bcf4d7fac2e97&chksm=e9184ac1de6fc3d7961645e7b6178ba82af79c7d4164a81876728873249f2c2d5405707f238d&scene=21#wechat_redirect)  

[构建企业级监控平台系列（八）：Zabbix API 使用介绍](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247544839&idx=2&sn=884f0a3c4d6d2455679a1c3192e5750c&chksm=e918551bde6fdc0d243c0abc7a7a59029d9fa36f00144a9a911d91d97987d2604018ecd26075&scene=21#wechat_redirect)  

[构建企业级监控平台系列（九）：Zabbix 自动发现与自动注册](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247544871&idx=2&sn=c13dc95bf11375fe8df8bbf06119c61a&chksm=e918553bde6fdc2d55161efa8e4b94fb3fe97a4acb73c5f095945495d68541ac113446d248f7&scene=21#wechat_redirect)  

[构建企业级监控平台系列（十）：Zabbix Proxy 原理与实践](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247544908&idx=2&sn=763430501a041966e538e488aeb724af&chksm=e9185550de6fdc46f719feebd7750f683d8bb85a7c8e62116d92b5b2eb32d9847a96c1b19d01&scene=21#wechat_redirect)  

[构建企业级监控平台系列（十一）：Zabbix 配置监控 Nginx、MySQL 等常见应用](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247544975&idx=2&sn=23979e0f212943dd0efe16374599649c&chksm=e9185593de6fdc85b56fe086f1f68351501662c97467a7096c9b775aab88b9e391433ec10b53&scene=21#wechat_redirect)  

[构建企业级监控平台系列（十二）：Prometheus 入门与安装](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247544996&idx=2&sn=a52e44579eec45073ce8d90c6d94d317&chksm=e91855b8de6fdcae55a2e5ceec21e583f3dd7a8e7c0b52a413d6e91c0ffc6fe0cad9f7d9ad03&scene=21#wechat_redirect)  

[构建企业级监控平台系列（十三）：Prometheus Server 配置详解](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247545010&idx=2&sn=ee11633ed0f6398b48dd2a38c820ec31&chksm=e91855aede6fdcb871ce5d4e019093c9b0bcf4955542b72b06691434bb529bad678ca3a0491c&scene=21#wechat_redirect)  

[构建企业级监控平台系列（十四）：Prometheus Operator 原理与实践](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247545052&idx=2&sn=0142da2cbc54c95219b61e6d65705ac6&chksm=e91855c0de6fdcd6422282a645c488ae062b7621a6f30b9475831283e129835b178b27362f96&scene=21#wechat_redirect)  

[构建企业级监控平台系列（十五）：Prometheus Exporter 原理与实践](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247545071&idx=2&sn=e88c8d3a2529fe2ae2dfe1116666d82e&chksm=e91855f3de6fdce5223f75dd9b9a0b495a0c0db46b8eb17e6ca68df0dd863b17859d533ebb84&scene=21#wechat_redirect)  

[构建企业级监控平台系列（十六）：Prometheus Node Exporter 详解](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247545098&idx=2&sn=88f663c68e0f9dcb1fd6c19c43297452&chksm=e9185416de6fdd00944eab3e498beb0be6677c30555337f6044fb79a8c95a8b5a40e73930255&scene=21#wechat_redirect)  

[构建企业级监控平台系列（十七）：Prometheus Label 原理与实践](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247545121&idx=2&sn=a06a8f913d98f25dbbd18dd9f7e3453d&chksm=e918543dde6fdd2b0d740d84bb058e157a2e414bee154c93cdd3f70ab96fe0f673a8a2ca1e6a&scene=21#wechat_redirect)  

[构建企业级监控平台系列（十八）：Prometheus 数据查询语言 PromQL](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247545201&idx=2&sn=feee9255c23bb057819120da50926137&chksm=e918546dde6fdd7b839a6d968829f46c13835b6597c77a03e9353537a975e3275fbdafec0219&scene=21#wechat_redirect)  

[构建企业级监控平台系列（十九）：Prometheus 报警模块 AlertManager](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247545261&idx=2&sn=49980d164856a2a64450e42d70ff7430&chksm=e91854b1de6fdda78d786d26a8f39a8337fc6b2dec3ea5221817780192c1cf67b848cc5569f5&scene=21#wechat_redirect)  

[构建企业级监控平台系列（二十）：Prometheus Alertmanager 配置实现钉钉告警](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247545284&idx=2&sn=3f7f31ece12ce0011d98f238a5e13417&chksm=e91854d8de6fddce1eb45ea750873db6bc0acb198b59c28ee609521354c3c61ea2625490202e&scene=21#wechat_redirect)

[构建企业级监控平台系列（二十一）：Prometheus Pushgateway 详解](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247545359&idx=2&sn=a73907277ac4a01158c5910bb18deb05&chksm=e9185713de6fde0502b57b44690e5094f32c51f489e6c5e86f6a00e242e09164b65d8c0b6b3b&scene=21#wechat_redirect)  

[构建企业级监控平台系列（二十二）：Prometheus 基于 K8S 服务发现详解](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247545401&idx=2&sn=50f25523c000d3eab82e21eb880374a3&chksm=e9185725de6fde3310da7d7112f9ee695abb2b7bd5afb6100fd8f337a7377c22ee543065a158&scene=21#wechat_redirect)  

[构建企业级监控平台系列（二十三）：Prometheus 配置监控常用服务实践](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247545439&idx=2&sn=cfea63b1100f911e2f0ad4c79d636c7c&chksm=e9185743de6fde55d3005532219f129a0c9076a77b8515db888162faae9926cc7c1d4fc466ce&scene=21#wechat_redirect)  

[构建企业级监控平台系列（二十四）：Prometheus 配置 Grafana 展示与报警](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247545522&idx=2&sn=05305bd4da2b3dff5e30057bf3abfde5&chksm=e91857aede6fdeb840af3c3addc575fa7b0ca35f3e071b140eaf5f89071523fa106484a83c46&scene=21#wechat_redirect)  

[构建企业级监控平台系列（二十五）：Prometheus 高可用集群方案](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247545577&idx=2&sn=2899c1665cc2f278c7354581f93ea503&chksm=e91857f5de6fdee317fcf7d1e261ae8a89fd0dc9707f7f43a1c2b056be46fa16d1a1862713f5&scene=21#wechat_redirect)  

[构建企业级监控平台系列（二十六）：Prometheus 高可用架构 Thanos 实践](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247545609&idx=2&sn=89db29ec8eb8ad177f1856bac553af7d&chksm=e9185615de6fdf03821874ec0b7f94a66e571c202f7ba6fb7ed4dc92b83e5a06249fc6eb81bd&scene=21#wechat_redirect)  

[构建企业级监控平台系列（二十七）：Grafana 基础入门与部署](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247545651&idx=2&sn=ac336d639e83dd06f1d7884ba37af011&chksm=e918562fde6fdf39739ae14efa126ab2e17dfcd2f020843aafa9f54f2944ecbb2fac38f82898&scene=21#wechat_redirect)  

[构建企业级监控平台系列（二十八）：Grafana 仪表盘 DashBoard](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247545703&idx=2&sn=57550d6b1bffb229fed3509db9f689c1&chksm=e918567bde6fdf6d6c11c26514c2a7d7d270e0d351d1af9f7077e60355b30eae533bd33d3005&scene=21#wechat_redirect)  

[构建企业级监控平台系列（二十九）：Grafana Dashboard 变量](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247545723&idx=2&sn=becc00913212573e5ea92f3c7b827ab3&chksm=e9185667de6fdf715fad3c4b3ef8f0bb1b04b5a45b76eee20fe43371d6ff8314b59721d94f58&scene=21#wechat_redirect)  

[构建企业级监控平台系列（三十）：Grafana Panel 面板和 Time series 时间序列](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247545818&idx=2&sn=a16827c5a9d1d7391dc4b21bec7e117b&chksm=e91856c6de6fdfd0b0eb8b50575cf4617071f20cd1c464b1775908b816ec9b1615a72f5420b8&scene=21#wechat_redirect)

[构建企业级监控平台系列（三十一）：Grafana 添加动态参数详解](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247545867&idx=2&sn=7c8f0af342fa4de104f4914ba5fa6e51&chksm=e9185117de6fd801f639632a1e98c1bd739acd171889f73159e3421a6753fd20437f2764af56&scene=21#wechat_redirect)  

[构建企业级监控平台系列（三十二）：Grafana 可视化面板 Heatmap 与 Gauge](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247545897&idx=2&sn=726da5e1e1f0c1b812c889427d82f7b0&chksm=e9185135de6fd8236c97355b4802fd9e5e163322821a3c1f152b8f8a82f9ce2a3aee4512415e&scene=21#wechat_redirect)  

[构建企业级监控平台系列（三十四）：Grafana 数据可视化工具安装与应用](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247546125&idx=2&sn=7ac0e8b2c8dfa3b0e7f878221863e1f7&chksm=e9185011de6fd90722165eb6c15003493dcb90e4fbfb049e707385a5d29a3c3d5684caa7c51b&scene=21#wechat_redirect)

## 自动化系列（DevOps）

**打造企业级 DevOps 自动化运维管理平台**。

![](https://mmbiz.qpic.cn/sz_mmbiz_png/tuSaKc6SfPoApWLpx5hpsbPtnLgH9WSHvVYS4tibl8eNUzCzcEwWHrIKNyY2wfXS2axFHjiasDSp2u5eW82OcRlw/640?wx_fmt=png&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)

DevOps并不是凭空创造出来的一个概念，DevOps是Development和Operations的组合，是一种方法论，是一组过程、方法与系统的统称，用于促进应用开发、应用运维和质量保障（QA）部门之间的沟通、协作与整合。以期打破传统开发和运营之间的壁垒和鸿沟。

![](https://mmbiz.qpic.cn/sz_mmbiz_png/tuSaKc6SfPoTjicvkxg19pZS3RFlqa7V5yibCrT4RpZkmofXI3GOOJErTyMAtaOaiaxgZgzGIAQGOWqONVuxq2xRw/640?wx_fmt=png&from=appmsg&wxfrom=5&wx_lazy=1&wx_co=1&tp=webp)

它也是有着历史的发展过程的。

简而言之，DevOps是继软件开发的瀑布模型、敏捷模型后的第三种软件开发的方法论，可以理解为：
- 第一阶段：瀑布模型    
- 第二阶段：敏捷模型  
- 第三阶段：DevOps   

[打造企业级自动化运维平台系列（一）：云原生技术基础入门详解](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247548395&idx=2&sn=84b614e19fae20afdbefd4ead0dc8941&chksm=e91858f7de6fd1e10e0bd390e2ec1ef7a011ad8eb8e2a9844b4564ff648c229013bd20f3a25c&scene=21#wechat_redirect)  

[打造企业级自动化运维平台系列（二）：DevOps、CI、CD、CT 详解](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247548470&idx=2&sn=8bc52610e240ae84accf6fc4540e848f&chksm=e9185b2ade6fd23c465c794e54292ef223fba206d303634b3030606d4f553de45c3d93622e63&scene=21#wechat_redirect)  

[打造企业级自动化运维平台系列（三）：DevOps 常用的软件工具](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247548470&idx=3&sn=cd1ac062a4ff95066a342ec4ab0d47f1&chksm=e9185b2ade6fd23c56618e74fc8c9b0a6fff97d5d7867606d2ee568edb3056ad5c79b99cb52b&scene=21#wechat_redirect)  

[打造企业级自动化运维平台系列（四）：Jenkins 基础入门与安装](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247548628&idx=2&sn=61264ad94e6773c0fe5795b3fed61009&chksm=e9185bc8de6fd2de7df858c167fd7bb6217fcffde4027c87bcc05bf3c73ef6af3e5ec6d8ead5&scene=21#wechat_redirect)  

[打造企业级自动化运维平台系列（五）：Jenkins 基本使用介绍](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247548628&idx=3&sn=852cc58dd17df1a348bff60dc08de099&chksm=e9185bc8de6fd2de91feee3e766cbcc9c4c54e8f810e010d8354cbec091e43277a140a0719ff&scene=21#wechat_redirect)  

[打造企业级自动化运维平台系列（六）：Jenkins Pipeline 入门及使用详解](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247548703&idx=2&sn=e00ae394fd7220ef73bb469a597283d4&chksm=e9185a03de6fd315deb14bdffbf503b664bc00caddb0c98a6bf394e4a199b1b88098f88843f3&scene=21#wechat_redirect)  

[打造企业级自动化运维平台系列（七）：Jenkins 部署 Springboot 应用实践](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247548703&idx=3&sn=02ad45c576e4492aa117ca634d1c34b6&chksm=e9185a03de6fd31563929b13a049d5b77937afaf724ccebb53ac6a590268aff38a167073a968&scene=21#wechat_redirect)  

[打造企业级自动化运维平台系列（八）：Jenkins 部署前后端分离项目](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247548883&idx=2&sn=0e398cc70a8ce73e139e96630a0802ba&chksm=e9185acfde6fd3d9d19b6127d31cea7ad537d0914cd6120c0b8bf8b3778aefa1874d72889bb2&scene=21#wechat_redirect)  

[打造企业级自动化运维平台系列（九）：Jenkins 基于 K8s 的 DevOps 平台实践](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247548883&idx=3&sn=10fd4b88651c21fa8f9647007f596d7d&chksm=e9185acfde6fd3d9026cfcbfbb3b3304b9aa5f4fc2ba9e313270f2370a99bd297909c8aa3d03&scene=21#wechat_redirect)

[打造企业级自动化运维平台系列（十）：Gitlab Runner 实现 CI/CD 详解](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247548991&idx=2&sn=15e9445279acde0181adfef665e55467&chksm=e9186523de6fec35f16d582d0c503a9e4d88110337bd13e3cb979d2c349ac049d48d2f6c6b49&scene=21#wechat_redirect)  

[打造企业级自动化运维平台系列（十一）：微服务基础入门（概念与架构）](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247548991&idx=3&sn=b3300e1b73955ed8cb4a76061949ef6b&chksm=e9186523de6fec355070e2b1588805408621335b6269c9b75a24e4e333c7b3425666508e2637&scene=21#wechat_redirect)  

[打造企业级自动化运维平台系列（十二）：服务发现与配置管理平台 Nacos 详解](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247549075&idx=2&sn=3330c3cd220c583f5c92184cc2391dca&chksm=e918658fde6fec99706bd1df17bb9455115b04e93deb87363d354a3d694e857c8668d1854c3a&scene=21#wechat_redirect)  

[打造企业级自动化运维平台系列（十三）：分布式的对象存储系统 MinIO 详解](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247549075&idx=3&sn=d3e22d944fc7c4fd6afdf185f64f2d44&chksm=e918658fde6fec99963898b8b917a12fa9aa139e25f83d8cbb4602ef67cb89793800b55c2a3f&scene=21#wechat_redirect)

[打造企业级自动化运维平台系列（十四）：容器管理工具 Rancher 详解](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247549334&idx=2&sn=5dd10633fd20a84253b60e5e93dfdc2f&chksm=e918648ade6fed9c5066d2052a3bf18e17b8a0f57c54fc3ddd14b5d33494dcc43b27cab113d2&scene=21#wechat_redirect)  

[打造企业级自动化运维平台系列（十五）：kubernetes 包管理工具 Helm 详解](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247549334&idx=3&sn=7581185868b0fdc18b524d273c659c50&chksm=e918648ade6fed9c8ab1faae3d4cfa20e032f8a2d21304cf88abecf2e7c5910a9101db60ef25&scene=21#wechat_redirect)  

[打造企业级自动化运维平台系列（十六）：服务网格 Istio 详解](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247549435&idx=2&sn=92f4a919542d12e9ff02785754d85274&chksm=e91864e7de6fedf1e2f1860a59cf3084e3431d172372d5bfda65eeaf89222c1f11dc02c04f52&scene=21#wechat_redirect)  

[打造企业级自动化运维平台系列（十七）：链路追踪工具 SkyWalking 详解](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247549435&idx=3&sn=4aa49a5d92a74e9e22181e0921632445&chksm=e91864e7de6fedf17ea0edcf1118fed6a7b82a84948a6f250f06698cf2e5dd43f7bc3f9d8a66&scene=21#wechat_redirect)  

[打造企业级自动化运维平台系列（十八）：influxDB、cAdvisor、Grafana](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247549590&idx=2&sn=a865570ac9e34d03a4421ae4e37e7834&chksm=e918678ade6fee9c4fab061991f535967d40ffb52e9a4fdde07e79b30ed281c0c0646e911165&scene=21#wechat_redirect)  

[打造企业级自动化运维平台系列（十九）：云服务器 ECS 入门（配置与使用）](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247549590&idx=3&sn=0b3ba435af2d893e2045c42950f3d65d&chksm=e918678ade6fee9c02019d1c42da4dea01ea16bdde830b70dd60057779916d5ce3864be16727&scene=21#wechat_redirect)  

[打造企业级自动化运维平台系列（二十）：云服务器 ECS 进阶（SLB/弹性伸缩）](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247549590&idx=4&sn=3daa0e8c23c65996124cc4b8aaa01644&chksm=e918678ade6fee9c9b8dcfb5cffa3989ff09abcb44ab63332505b7fde26ba405ad202f0e1795&scene=21#wechat_redirect)

## 常用工具

介绍常用工具（命令工具、其它工具）相关的日常运维所需知识体系。

![](https://mmbiz.qpic.cn/sz_mmbiz_png/tuSaKc6SfPpYiaNgWlY4EL9GcKCXdVWzW6fNtSQlYp4fAicxTlwsdu7HUyDicbtD8nLXZAwiagdibf2spcZMBFa2WMA/640?wx_fmt=png&from=appmsg&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)

可以参阅专栏：[Tools](https://mp.weixin.qq.com/mp/appmsgalbum?__biz=MzI0MDQ4MTM5NQ==&action=getalbum&album_id=1790352360813232129#wechat_redirect) 去学习更多相关工具的原理与操作。

## Java 后端技术栈

还可以进一步去了解一些后端的基础入门理论知识，通过熟悉上下游的知识体系，这样在工作中我们也不会那么容易被动，这就是运维为什么要不断学习的原因。

![](https://mmbiz.qpic.cn/sz_mmbiz_jpg/tuSaKc6SfPq0SYtFzM2ofxrqov92Ch2qCiahQT4nqGYQZslzrv8ur00qP4u6qBsCBN9Ribp16OBakSl3qB6wYzhw/640?wx_fmt=jpeg&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)

比如：了解一下关于[**Java后端技术**](https://mp.weixin.qq.com/mp/appmsgalbum?__biz=MzI0MDQ4MTM5NQ==&action=getalbum&album_id=1840920758970089480#wechat_redirect)、[**微服务架构**](https://mp.weixin.qq.com/mp/appmsgalbum?__biz=MzI0MDQ4MTM5NQ==&action=getalbum&album_id=2362702974101291010#wechat_redirect)，轻量级 Java开发框架[**Spring**](https://mp.weixin.qq.com/mp/appmsgalbum?__biz=MzI0MDQ4MTM5NQ==&action=getalbum&album_id=1965462227759529984#wechat_redirect) 等。

## 企业面试

介绍企业面试经验、各类面试题详解等（面试题与面试经验总结分享），下面给大家列举了一些常见的面试题，更多关于企业面试题相关的知识学习，可以参考专栏：[企业面试题集合](https://mp.weixin.qq.com/mp/appmsgalbum?__biz=MzI0MDQ4MTM5NQ==&action=getalbum&album_id=1790435592028160001&scene=21#wechat_redirect)。

[linux系统运维企业常见面试题集合（一）](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247484466&idx=1&sn=6cd7fab55165c5a9e72180c207e26954&chksm=e91b612ede6ce8389887bfbb7c9176a52a17c9cb50d05f9b134aec52a7366cc5cda4fe3cd938&scene=21#wechat_redirect)  

[linux系统运维企业常见面试题集合（二）](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247484473&idx=1&sn=d8fbb0361bc170ff9ab069f9ac4c5a94&chksm=e91b6125de6ce83361997321661376e7830863347560c1c428881b64cccc2c1db3e3be9e7620&scene=21#wechat_redirect)  

[linux系统运维企业常见面试题集合（三）](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247484484&idx=1&sn=118836c2f991e0925169804277bbbf90&chksm=e91b6158de6ce84edde1b15ce61d523ca06203b245180486d58b33bd54412187260d1a237df3&scene=21#wechat_redirect)

[Linux运维必会的100道MySql面试题之（一）](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247484699&idx=1&sn=964df87965f6b2cfc7282e7409a43958&chksm=e91b6007de6ce91193369fb4288c4b234a09e9323a4d6ac5ea2ec7564da147ccdf08caf6a3cf&scene=21#wechat_redirect)  

[Linux运维必会的100道MySql面试题之（二）](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247484703&idx=1&sn=3eaa3a3cf822849996be89d93ffb33b9&chksm=e91b6003de6ce915d7e9f246b457965fc84c0c69fe4a637fae250367f8629d1577f1cbacc3d7&scene=21#wechat_redirect)  

[Linux运维必会的100道MySql面试题之（三）](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247484710&idx=1&sn=eb22de8c7ff6f1dcbc4c0ba4226449d0&chksm=e91b603ade6ce92c2c4c619157e72fd1a1fe0d967bdc0373ddc08a1eb114897ed8f7a2f1ba46&scene=21#wechat_redirect)  

[Linux运维必会的100道MySql面试题之（四）](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247484835&idx=1&sn=d77c8f0cad7e65c34fb792004bdabb14&chksm=e91b60bfde6ce9a95afae4681a8017f6d1b7d90506acc0704827ddb12ce9d48cbe756d577916&scene=21#wechat_redirect)

[Linux运维跳槽40道面试精华题](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247488738&idx=1&sn=3ca0cab0ade2c49aa5b1188ece9a5cc8&chksm=e91b71fede6cf8e8b7f15b271cc411dbb7088afc20d910d5765412c6a5ae1bf9c63995f5723c&scene=21#wechat_redirect)  

[精心汇总的 24 道 shell 脚本面试题](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247488571&idx=1&sn=6f29df5a384bd68ee20c752234e7ae69&chksm=e91b7127de6cf83195fab6d7da4169ebf9aaaf458b271d832072cbed029de0752d003ddb970a&scene=21#wechat_redirect)  

[面试中有哪些经典的数据库问题？](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247486600&idx=1&sn=ffe2f7e8650db98bb1dfe874447b6863&chksm=e91b6994de6ce0825dcd6dc3cfeee625cd997e975a9d5fca92533967ff870342ac649d7733a1&scene=21#wechat_redirect)  

[史上最全的大厂Mysql面试题在这里](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247485499&idx=1&sn=33002d06faa43d8192c7acc3e0f6e1a7&chksm=e91b6d27de6ce4315a5d8dcc5d40d2f6430d84b736088f2d6c57d1aeb6e6814589e76cb9f7e9&scene=21#wechat_redirect)  

[值得一看的35个Redis面试题总结](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247486949&idx=1&sn=ba641d2eae629d9f1fbc5c5c79931c26&chksm=e91b68f9de6ce1efb41a418b8feab1b5a475c0ca478cbce1d4e8906be7f89086ec2a4f532a86&scene=21#wechat_redirect)

学完这些内容这后，可以这么说，还是仅仅是开始，更多的还是要将所学的知识结合实际的生产环境，然后通过不断的实践去总结，慢慢的一点点去补充自己的整个知识体系的高墙，从而使之更坚固、更持久、更强大。

如有帮助，请点**Star 支持**！感谢你的关注与支持。  

**路虽远，行则将至！**

**事虽难，做则必成！**

##### 扫一扫，关注作者微信公众号查看更多精彩内容
![image](https://github.com/mingongge/BestOPS/assets/25194524/89b379ab-847a-4d61-89ec-22ab2f661b65)

