## 运维工程师进阶升级之路
![](https://mmbiz.qpic.cn/mmbiz_png/tuSaKc6SfPrAHsmIwdzwz63CDot8fQaIcuRWJ4K9VunmCXJ6zXkw4TQ8V1gDKIxibnHP1NWhU8hHyLoZxzFgeqw/0?wx_fmt=png)

## 版本信息

| 版本号 | 更新时间 | 备注 |
|-------|---------|------|
|V1.0|2019-1-20|首次发布|
|V1.0.1|2019-4-26|增加了相关的知识点|
|V2.0|2019-05-13|增加知识点，进一步完善|
|V3.0|2021-04-20|补充整个知识体系|

## 前言
Linux 运维工程师进阶升级之路由公众号【民工哥技术之路】作者【民工哥】编写、整理发布而成，我的故事： [民工哥的十年故事：杭漂十年，今撤霸都！](https://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247485931&idx=1&sn=b288b703a209edb677411e101fbb08af&chksm=e91b6cf7de6ce5e19304da227e701fc604f0a273ab750710de8412b13bde5bca735b79176665&scene=21#wechat_redirect)。回头看看，写公众号也有快六年的时间了，做一件事很容易，但坚持做一件事情六年应该不是件容易的事。一路走来，收获了众多读者的肯定与支持，同时在自己的知识体系建立、建全上也取得了不小的成就。在这期间，我写的书：[Linux系统运维指南](https://mp.weixin.qq.com/s/BuivnIHDedFO1CLuQnHG_w) 出版（2020年4月），同年10月，我拿到了2020年人民邮电出版社/异步社区《[最具影响力作者](https://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247501495&idx=1&sn=0eedeeb5bf2c37ae4eb385ce592cf2d1&chksm=e918a3abde6f2abd0eb687183aa8acd1fe7118d5ab0c5c7ac2fbd7925c3ae375c275bcad8d63&token=1107524505&lang=zh_CN#rd)》。除了感谢这个伟大的时代、家人、朋友，还要感谢无数支持我的读者们，谢谢你们。

其实，很多熟悉我的老读者都知道，我也算是 0 基础起步自学至今的，所以，对于自学，我也总结了一些方法，或者说分享一下我的经验：[民工哥自学方法](https://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247491161&idx=2&sn=3a12a4fdd41ab0dc9cfbc48e6c62e3f4&chksm=e91b7b45de6cf253bcf7cd5729e5963ca5f85ba1cbe3e2d61c7a9d18b359fc43887a08ee1aa0&scene=21#wechat_redirect)。对于需了解整个运维知识体系学的过程可以参考：[运维工程师进阶升级之路思维导图](https://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247485027&idx=1&sn=9849f12d63906c35aa18fab9f2e76052&chksm=e91b637fde6cea6921566f117965a1c0e258f3d12613a8fd79f534a0b3639b60572fe1e152c7&token=471976001&lang=zh_CN#rd)。

现目前整个系列文章统一入口也在公众号上，后期更多增加、完善进去的内容也会统一同步发布到公众号中，欢迎大家关注（**可扫文末二维码加关注哦**）！！

运维工程师这个岗位不同于后端开发岗位，到底运维工程师平时做什么？[老司机告诉你：正规的运维工作是什么的?](http://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247488821&idx=2&sn=1c53372eb6553583d95b221f78fa540c&chksm=e91b7029de6cf93f2725122f3e109288c1117aac0754f97ab77f976871f3713880da7a78a76c&scene=21#wechat_redirect)。而且这个岗位对技能要求是越来越高，不仅仅要求需要知识的深度，还要求要有一定的广度，深度就是需要不断学习运维知识体系的知识，广度就是运维岗位上下游（测试与开发）岗位的一些知识体系，至少是需要做到了解基础的掌握程度。

因此，这就对运维工程师们提出了更高的要求，**首先得有一颗不断学习的心，其次坚持的毅力是必须的，然后就是不断和实践、操作与总结，重复再重复，** 时间久了才能形成自己的一套知识体系。

正因为这些原因，才有了上面的《运维工程师打怪升级进阶成神之路》的出现，初衷很简单，就是将我的所学与所总结的学习路线分享给大家，希望对后面的爱好者、学习 Linux 运维的朋友们有所帮助、有所借鉴。以便你们更好的学习与掌握其中的知识点，然后也能更轻松的运用到企业的实际工作中去。

## 基础入门篇

#### 网络基础

这是每一个IT从业者必备的基础中的基础，比如：TCP/IP协议、路由基础这些[必备的 6 大计算机网络基础知识点](https://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247529511&idx=1&sn=9b1f3abfdf18e9cf24b31eccc063fdfe&chksm=e918113bde6f982d303d6a3d47235fd17f3e7ce241e816b39c0b47896791f498c54281e22496&token=1107524505&lang=zh_CN#rd)！是一定要熟悉与掌握的，否则无法展开后面的系统学习的。下面一张比较全的计算网络基础的学习思维导图：
![](https://files.mdnice.com/user/4435/f9a88b78-7707-42ab-ad8b-b8177740aa40.png)
如果你是有此方面基础的可不必学习了，如果是没有网络基础的，建议你去看一看我[公众号](https://mp.weixin.qq.com/mp/homepage?__biz=MzI0MDQ4MTM5NQ==&hid=8&sn=1db566bed001a8db6d9927540ccc2156&scene=25#wechat_redirect)上很早之前写过的一些关于网络方面的文章，这样也可以很快的熟悉这方面的知识点。

#### 系统基础
![](https://files.mdnice.com/user/4435/4e25e686-f495-4823-95b8-2ba753223aab.png)
首先就是系统的安装与基础配置：[Centos7安装教程](https://mp.weixin.qq.com/s?__biz=MzI0MDQ4MTM5NQ==&mid=2247484381&idx=1&sn=08504c1d03c7cf51683abb617be11997&chksm=e91b66c1de6cefd7b003228bb7c6b74f70d950f11ce5f8679f593b30ed8a32e576f0bdc9587c&token=1107524505&lang=zh_CN#rd),有需求的可以参考这个教程，安装其实是非常简单的。

对于系统目录、文件系统、权限等内容。前面的版本也介绍的非常清楚，这里不再一一赘述。也可以参考这里：[Linux 系统基础入门知识点](https://mp.weixin.qq.com/mp/homepage?__biz=MzI0MDQ4MTM5NQ==&hid=11&sn=34e1e7ed1b2af3d38e44705424ad32d2)


## Linux 必学的常用命令

这一块的知识点，在入门阶段是非常重要的一块，掌握的好坏直接影响到后面的具体操作与学习，而且，这里列举的这些常用管理命令，也是我们日常工作中要用到的（属于重点掌握内容之一）。

![](https://files.mdnice.com/user/4435/353a1fdd-c6cb-4a05-aa5e-7cd59068e88e.png)

这部分详细介绍[系统运维常用命令](https://mp.weixin.qq.com/mp/appmsgalbum?__biz=MzI0MDQ4MTM5NQ==&action=getalbum&album_id=1661147427422208001&scene=21#wechat_redirect)及其参数说明，并且配有应用案例详解，基础必备！

## 脚本入门与进阶

这部分介绍Shell脚本编程的基础入门与进阶知识，包括编写方法分享、案例分享。

![](https://files.mdnice.com/user/4435/f18befa4-2329-4152-9a50-9023252e434e.png)

虽然说现在Python在运维工作中已经使用很普遍，但是很多企业实际工作中的时候还是会用到 shell 脚本，它有助于你在工作环境中自动完成很多任务。在减少重复工作量的同时，也会提高不少工作效率！因此，Shell脚本编程也是运维工程师必备的工作技能之一！

更多详细内容可以查阅专栏：[Shell 脚本编程](https://mp.weixin.qq.com/mp/appmsgalbum?__biz=MzI0MDQ4MTM5NQ==&action=getalbum&album_id=1790345250847195139#wechat_redirect)

## Nginx 配置与优化

基础的服务安装、配置文件介绍、虚拟主机配置实践、Nginx优化配置详解、LNMP架构Nginx反向代理负载均衡配置、Nginx+Tomcat多实例及负载均衡配置、高可用、Nginx 版本的平滑升级与回滚、Nginx限流配置、Nginx日志生产实战、Nginx配置文件在线生成工具介绍等。

![image](https://github.com/mingongge/BestOPS/assets/25194524/446ff6e0-834f-4473-802b-0e33869e464a)

详细内容可以查阅专栏：[Nginx 学习专栏](https://mp.weixin.qq.com/mp/appmsgalbum?__biz=MzI0MDQ4MTM5NQ==&action=getalbum&album_id=1463291332122017795#wechat_redirect)

## 数据库

#### MySQL 数据库
![image](https://github.com/mingongge/BestOPS/assets/25194524/a82679b7-f550-489f-bc0a-acdeaaee9804)

MySQL 数据库的基础知识，如：数据类型、存储引擎、性能优化（软、硬及sql语句），MySQL 数据库的高可用架构的部分，如：主从同步、读写分离的原理与实践、跨城容灾、数据的备份与恢复等，然后介绍了 MySQL 的管理命令、数据库语言的命令、库与表的管理工具、性能分析与工具的使用、MySQL 数据库服务器的硬件选型、性能监控、开发设计规范等知识。

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

#### PostgreSQL 数据库

PostgreSQL 是一个功能强大的开源数据库系统。经过长达15年以上的积极开发和不断改进，PostgreSQL已在可靠性、稳定性、数据一致性等获得了业内极高的声誉。目前PostgreSQL可以运行在所有主流操作系统上，包括Linux、Unix和Windows。

![](https://files.mdnice.com/user/4435/9d288e98-a475-498a-877f-a714b251cfb3.png)

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



## 相关的内容持续更新中~~~~~

##### 扫一扫，关注作者微信公众号查看更多精彩内容
![image](https://github.com/mingongge/BestOPS/assets/25194524/89b379ab-847a-4d61-89ec-22ab2f661b65)

