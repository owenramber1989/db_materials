# db_materials

---

## 语言

1. :star2::star2::star2::star2::star2:[Modern Effective C++](https://cntransgroup.github.io/EffectiveModernCppChinese/)

    介绍了 C++11 和 C++14 标准下的编程技巧

2. :star2::star2::star2:[C++ 并发编程实战 第二版](https://github.com/ZhouZhaoJi/Library/blob/master/Programming/C++%E5%B9%B6%E5%8F%91%E7%BC%96%E7%A8%8B%E5%AE%9E%E6%88%98.pdf)

    介绍了如何用 C++进行并发编程

3. :star2::star2::star2::star2:[侯捷 C++ course](https://github.com/ZachL1/Bilibili-plus)

    侯捷老师的 C++系列课程，深入学习 C++的必经之路

4. :star2::star2::star2:[Modern C](https://www.manning.com/books/modern-c)

    这本书讲了许多C11、C17的用法，如果在miniob中碰到一些比较晦涩的c代码，可以参考一下这本书

## 编译原理

1. :star2::star2::star2:[flex&bison](https://github.com/owenramber1989/db_materials/blob/main/compiler/flex__bison.pdf)

    本书介绍了如何使用 flex 与 bison, 重点看一下第四章和第五章就好


## 操作系统

1. :star2::star2:[操作系统导论](https://github.com/gsZhiZunBao/e-books/blob/main/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F%E5%AF%BC%E8%AE%BA.pdf)

    这本大家应该都看过，本书作者也开了不少DBMS的玩笑，很有意思

## 数据库

### 基础知识

1. :star2::star2::star2::star2::star2:[数据库系统概念](https://github.com/Sorosliu1029/Database-Systems/blob/master/Database-System-Concepts-7th-Edition.pdf)

    书本身比较厚，6-12章介绍了一些没太大关联的内容，13章存储部分往后是本书精华，遇到不熟悉的内容可以先翻阅此书

2. :star2::star2::star2::star2:[数据库系统实现](http://cdn.lxqnsys.com/%E6%95%B0%E6%8D%AE%E5%BA%93%E7%B3%BB%E7%BB%9F%E5%AE%9E%E7%8E%B0%EF%BC%88%E7%AC%AC%E4%BA%8C%E7%89%88%EF%BC%89.pdf)

    出版于 2009 年，时间上有些久远，但是品质非常好，翻译也很地道，书很薄，建议多看几遍

3. :star2::star2::star2:[Database Internals 数据库系统内幕](https://github.com/G33kzD3n/Catalogue/blob/master/Database%20Internals.pdf)

    本书很新，介绍了非常多的最新技术和最新实践，建议结合章末推荐的论文阅读

4. :star2::star2::star2:[DDIA](http://ddia.vonng.com/#/preface)

    与本次比赛关系不大，但是可以极大地促进对数据处理的理解

### 存储处理

1. :star2::star2::star2::star2:[数据库索引设计与优化](https://github.com/woooowen/iBooks/blob/master/Mysql/%E6%95%B0%E6%8D%AE%E5%BA%93%E7%B4%A2%E5%BC%95%E8%AE%BE%E8%AE%A1%E4%B8%8E%E4%BC%98%E5%8C%96.pdf)

   > 索引设计必读书目，对于各种实践都有清晰的对比分析

### 查询优化

1. :star2::star2:[优化器论文专栏](https://www.zhihu.com/column/c_1364661018229141504)

    这个收藏夹里面的论文都很经典
2. :star2::star2::star2:[PostgreSQL技术内幕：查询优化深度探索](https://book.douban.com/subject/30256561/)
    这本书非常好地介绍了众多查询优化思路，结合最先进的开源数据库pg作了充分的论述

## 工具

> 当然现在有chatgpt了，这些工具都可以轻松使用
### git

1. :star2::star2::star2::star2::star2:[learn git branching](https://learngitbranching.js.org/)

    用可视化的闯关模式帮助你熟练 git 的使用，强烈建议学习

2. :star2::star2:[Pro Git](https://git-scm.com/book/zh/v2)

    git 全书，有不会的地方可以查阅

3. :star2::star2::star2:[如何写好 git message](https://www.freecodecamp.org/news/how-to-write-better-git-commit-messages/)

    好的 git 提交信息应是原子性的、清晰准确的，为了写出清晰的 git commit message,请尽量阅读此文

### make&cmake

1. :star2:[Makefile tutorials with examples](https://makefiletutorial.com/)

    在实践中学习 Makefile 的编写



## 参考课程

1. :star2::star2::star2::star2:[15-445 intro to db system](https://15445.courses.cs.cmu.edu/fall2023/schedule.html)
秋季版的暂时没更完，23fa的lab0,lab1和23sp没什么区别，不过23fa的索引是可扩展hash索引，跟前几个学期的B+树索引不同，可以尝尝鲜
2. :star2::star2::star2:[15-721 advanced topics in db system](https://15721.courses.cs.cmu.edu/spring2020/schedule.html)

    手把手带你读业界最新论文, 这里面提到的论文都非常值得一读，需要注意20版侧重OLTP, 23版侧重OLAP, 为了比赛建议优先学习20版。而且说实话，完整消化本课程大约需要100h，还是要下功夫硬啃的。btw, 因为疫情，20版属于纯净版，你不用听23版一个傻丫头整节课尬笑，贼烦

3. :star2:[6.5830 db system](http://dsg.csail.mit.edu/6.5830/assign.php)

    mit 的数据库入门课，实验基于 Java

4. :star2::star2::star2::star2:[基于 oceanbase 的数据库内核开发课程](https://open.oceanbase.com/activities/4921877?q=%E5%AE%9E%E6%88%98%E6%95%99%E7%A8%8B&scope=activity)

    由蚂蚁集团的数据库开发者带来的数据库内核课程，内容充实，建议学习

5. :star2:[视频 南大 os 课程 by 蒋炎岩](https://space.bilibili.com/202224425/channel/collectiondetail?sid=1116786)

    该课程具有一定难度，非常耗时间，学完会有很大收获，但对于数据库内核开发意义不是特别大，可以业余时间学习

6. :star2::star2:[CS186 Intro to db system](https://cs186berkeley.net/)

    ucb 的数据库入门课，实验基于 Java,课程不错，可以在 b 站或者 youtube 上看到 22 fa 的录像

7. :star2::star2:[Pingcap talent-plan](https://github.com/pingcap/talent-plan)

    PingCap 的训练营课程，非常锻炼动手能力，但是其侧重的分布式领域可能不是本次比赛的重点



## 建议阅读的论文

1. :star2:[合集 db-readings](https://github.com/rxin/db-readings)

> 还有2020版15721的全部论文，当然我想你们看不完，我也看不完

## 很有价值的博客还有知乎文章

1. :star2::star2::star2::star2:[数据库内核月报-B+树索引的演进](https://www.bookstack.cn/read/aliyun-rds-core/aa131d04150a2a21.md)'
   PolarDB团队的数据库内核月报都很有价值，建议有时间就多看看
2. :star2::star2::star2:[SQlite源码分析](https://huili.github.io/index.html)
   SQlite只有130KLOC，结合这份博客可以帮助我们更好地阅读源码
**下面这些文章我就不打星了，好累**

- [2022 OceanBase 数据库大赛决赛经历分享](https://zhuanlan.zhihu.com/p/617520132)
- [OceanBase比赛总结 | OceanBase内核初探](https://zhuanlan.zhihu.com/p/508331407)
- [大规模分布式数据库是如何实现的 -- 读《OceanBase 数据库源码解析》](https://zhuanlan.zhihu.com/p/655202941)
- [有什么好的数据库学习路径推荐？](https://www.zhihu.com/question/451898647/answer/1813178673)
- [数据库中的prefetch和interleave](https://zhuanlan.zhihu.com/p/443829741)
- [BwTree技术解读](https://zhuanlan.zhihu.com/p/29314464)
- [现代 C++ 及其在 ClickHouse 中的应用](https://zhuanlan.zhihu.com/p/655663455)
- [kv分离LSM存储引擎的工业界应用](https://zhuanlan.zhihu.com/p/397466422)
- [RocksDb用到的一些优化技巧](https://www.zhihu.com/question/270732348/answer/2637403074)
- [深入浅出分析LSM树（日志结构合并树）](https://zhuanlan.zhihu.com/p/415799237)
- [mysql如何实现函数依赖](https://zhuanlan.zhihu.com/p/652844913)
- [Merge Path - A Visually Intuitive Approach to Parallel Merging 论文解读](https://zhuanlan.zhihu.com/p/606678298)
- [许多OceanBase优化器的例子](https://www.zhihu.com/question/544427791/answer/2914079227)
- [SQL子查询的优化](https://zhuanlan.zhihu.com/p/60380557)
- [cascade optimizer](https://zhuanlan.zhihu.com/p/73545345)
- [mysql无锁日志系统的源码解读](https://zhuanlan.zhihu.com/p/650089686)
- [CockRoachDB向量化执行引擎简介及Hash Join向量化实现](https://zhuanlan.zhihu.com/p/645428158)
- [大型c++项目在linux下如何调试?](https://www.zhihu.com/question/26905808/answer/1971302757)
- [mysql如何实现日志](https://zhuanlan.zhihu.com/p/628365328)
- [bustub的缓冲池优化](https://zhuanlan.zhihu.com/p/644160340)
- [论文导读 | 数据库查询优化中的 Join Order 问题](https://zhuanlan.zhihu.com/p/644832644)
- [自动机算法在数据库索引中的应用](https://zhuanlan.zhihu.com/p/628057993)
- [RocksDB中的无锁数据结构设计](https://www.zhihu.com/question/52629893/answer/3146235681)
- [高性能无锁数据结构探索-持久化log实现](https://zhuanlan.zhihu.com/p/632731393)
- [bustub性能优化](https://zhuanlan.zhihu.com/p/636275627)
- [PostgreSQL BTree(B-Link-Tree变种) 索引基本实现原理](https://zhuanlan.zhihu.com/p/639226810)
- [B-tree 并发控制的演进](https://zhuanlan.zhihu.com/p/613532094)
- [C++ 的无锁数据结构在工业界有真正的应用吗？](https://www.zhihu.com/question/52629893/answer/2937070552)