# Artificial-intelligence-diamond-chinese
全中文的人工智能教程和资料，只选“精品”，如“钻石”般精致。

现在网上的资源太泛滥了，各种“资源”，各种电子书合集。

虽然很多都有很高的阅读量和关注度，但实则大部分人只是看到“貌似是个好资源”就点赞了，star了，收藏了。

这些资源大多也都来自于简单整理，和各种资源拼凑，就算你看到了，你也无从下手，也不知道到底看哪本，到底学什么，最终还是没得学。

这也就导致百分之90的人基本上养成了四字习惯，“收藏”， “吃灰”

收藏了，等于会了，一部分原因是因为自身驱动力不足，另外一部分原因是因为资源太多，没法筛选，资源太杂，没有整合。

然而这个repo的宗旨就是“最精致”，无需看其他各种让人沉迷到没有学习的资源了，直接看这个，从头学到尾，沉下心，你会少走很多弯路，节省很多时间，减少各种书籍，学习视频，教程的筛选。

虽然现在说算法岗已经是诸神黄昏了，但是我依旧凭借自己的自学拿到了几乎你知道的所有大厂的算法offer。



## 前期所需的技能点
不管你接触AI之后想做什么方向，比如计算机分割，时空序列预测，还是自然语言处理，前期都要掌握的一些技能点
- python语言
- 算法与数据结构
- 数据处理常用的一些库
    - numpy 主要是矩阵运算的库
    - pandas 主要用于各种数据处理和数据分析的库
    - matplotlib 主要用于各种数据表达的可视化
- 机器学习基础理论
- 深度学习基础理论
- 机器学习实战
- 深度学习实战
- linux&git一些使用


# python语言
## python学习网站
- [莫凡python (视频)](https://mofanpy.com/tutorials/python-basic/interactive-python/)

- [菜鸟教程 (博客)](https://www.runoob.com/python/att-list-count.html)

- [python教程仓库(照着刷)](https://github.com/jackfrued/Python-100-Days)

## python书籍
- 《python Cookbook》

- 《Python编程:从入门到实践》

## 一些真诚的嘱咐
如果有语言编程基础的话，建议直接看视频或者博客，运用较短的时间把各种模块进行迁移学习。

因为语言很多知识点都是互通的，其实对于python这门语言说实话，封装性实在太好，没必要花太多时间。

如果没有接触过编程，我个人觉得花费大量时间学习python，比如先学习java或者c++

我个人的编程路径是从c语言->java->c++->python

推荐可以先学java，我当时java是看的韩顺平老师的课，当时恰逢暑假，在家闲着没事，心思多学一门语言肯定有益无害
- 韩顺平 java课  [百度网盘](https://pan.baidu.com/s/12Ut-SnSZQZfLAYVkmLmq-w) 提取码：fcht


# 算法与数据结构

树、链表、数组、堆栈、队列、字符串、动态规划(DP)、深度(DFS) / 广度优先(BFS)搜索等

## 学习书籍
要先通过书籍了解最起码的数据结构，数，链表，数组，堆栈，队列
- 《算法图解》
- 《啊哈！算法 - C语言》
- 《大话数据结构 - C语言》
- [《剑指offer》](https://leetcode-cn.com/problemset/all/?listId=xb9nqhhg&page=1)  建议直接刷
    - k神的剑指offer在线题解以及python解答: https://leetcode-cn.com/circle/article/kQcYo2/


## 刷题网站(中文)
https://leetcode-cn.com/

## 各种类别非常非常牛逼&通俗易懂的文章汇总(保准能看懂，主要都是python)
- [八大排序算法(冒泡，快速，直接插入，希尔，简单选择，堆，归并，以及基数排序)](https://cuijiahua.com/blog/2018/01/alogrithm_9.html)
- [动态规划之背包问题系列](https://www.zhihu.com/people/tang-shu-sen-77)
- [二分查找算](https://www.cnblogs.com/kyoner/p/11080078.html)
- [回溯算法](https://leetcode-cn.com/problems/permutations/solution/hui-su-suan-fa-python-dai-ma-java-dai-ma-by-liweiw/)

## 一些真诚的嘱咐
网上刷题的各种笔记啊，资料啥的，很多哈，眼花撩乱，然而

算法与数据结构到底该怎么刷？以及到底去大厂公司的重要性有多少？，这个我会录个视频，在TODO中


# 数据处理常用的一些库
这些库整体来说应用十分广泛，在平时的数据分析中(不过主要限制于学生时代，公司可能直接用某种工具平台，sql等进行处理)

- [pandas中文教程](https://github.com/datawhalechina/joyful-pandas)
- [numpy中文教程](https://mp.weixin.qq.com/s?__biz=MzA4ODUxNjUzMQ==&mid=2247484468&idx=1&sn=8056ab031a2c31ced9a53417ac007220&chksm=9029b6e8a75e3ffe42ec833dc271dd846971a9ad89fbc771eb818a7b650a96da6d0cc45aed4a&token=1834414134&lang=zh_CN#rd)
- [matplotlib中文教程](https://zhuanlan.zhihu.com/p/139052035)

## 一些嘱咐
这块的学习我建议大家先不用太多时间，整体文档以最快的速度过一下就行，因为后面会经常用到，到时候具体问题具体分析，熟能生巧。

三大库常用列举
- pandas 常用的主要是从文件读数据，索引取段，groupby聚合,apply自定义函数，concat链接等
- numpy 常用的主要就是索引取值，concat，以及一些常用计算等
- matplotlib 常用的有画多图，设置刻度范围，设置刻度标签，添加颜色区分，图例添加等

# 机器学习

## 机器学习理论
### 视频
- [吴恩达机器学习系列课程](https://www.bilibili.com/video/BV164411b7dx?from=search&seid=4170046626243985867&spm_id_from=333.337.0.0)
- [李宏毅2021春机器学习课程](https://www.bilibili.com/video/BV1Wv411h7kN?p=2&spm_id_from=pageDriver)
### 书籍
- 《机器学习》
    - 公式详细推导见-[《南瓜书》](https://github.com/datawhalechina/pumpkin-book/releases)
- 《统计学习方法》
    - [对应算法实现](https://github.com/Dod-o/Statistical-Learning-Method_Code) 
- 博客(初学者先看白话机器学习)
    - [白话机器学习专栏](https://www.zhihu.com/column/c_1223939179798802432)
    - [阿泽-机器学习系列](https://zhuanlan.zhihu.com/p/74874291)
## 机器学习实战
### 书籍
-《机器学习实战》
    - [python3-机器学习实战 学习笔记](https://blog.csdn.net/c406495762/category_9269492.html)
## 面试
### 书籍
- 《百面机器学习》
# 深度学习
## 深度学习理论
### 视频
- [吴恩达深度学习系列课程](https://www.bilibili.com/video/BV1FT4y1E74V)
### 书籍
- 《神经网络与深度学习》
## 深度学习实战
### 书籍
- 《TensorFlow: 实战Google深度学习框架》
    - [整理笔记代码](https://github.com/chehongshu/DL-tenserflow)
- 《动手学深度学习》
    - [pytorch代码笔记](https%3A//github.com/ShusenTang/Dive-into-DL-PyTorch)

# git
强烈建议就看这篇[简易git教程](https://www.bootcss.com/p/git-guide/)就行了，基本上学习工作过程中主要就是这些命令，这些掌握基本上平时就ok了。

