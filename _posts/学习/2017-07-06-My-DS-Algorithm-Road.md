---
layout: post  
title: 我的数据结构算法学习之路（未完）    
category: 学习    
tags: 总结        
keywords:       
description:    
---  


##  缘起
+ 之前若干次看过DS和Algorithm，甚至也看了不少书，严老太的[教材](https://book.douban.com/subject/2024655/)，[《大话数据结构》](https://book.douban.com/subject/6424904/)。
+ 也买了《算法》4th，《算法导论》，但感觉一直都没有很好的入门啊。
+ 甚至也刷了部分题[《算法与数据结构考研试题精析》](https://book.douban.com/subject/1186808/)，严老太的那本教辅也做了部分，当然除了自己非科班外，也没有好好刷，只做了选择和填空。
+ 趁着找工作的机会想路这个思路理一理。正好之前在github上建了一个DS的仓库。

##  内容

###  常见数据结构内容
####  chap2 [线性表](https://github.com/wolflion/data_struct/tree/master/chap2Linear) 20170319
+ 顺序表
+ 链表
    + 单链表
    + 双链表
    + 循环链表
        + 单链的循环链表
        + 双循环链表
        + 多重循环链表  
+ 常见考查
    + 约瑟夫(Joseph)环
#### chap3 [栈和队列](https://github.com/wolflion/data_struct/tree/master/Chap3Stack_Queue)  20170319
+ 栈
    + 顺序栈
    + 链栈
    + 栈的应用
        + 实现四则运算
        + 栈的递归应用
+ 队列
    + 顺序队列
        + 队列的溢出
        + 队列满
        + 队列空
    + 链队列
    + 循环队列
    + 优先队列
    + 队列的应用  
#### chap4 串  20170728

#### chap6 树 

#### chap7 图

#### chap8 查找
+ 静态表的查找
    + [顺序查找](https://github.com/wolflion/data_struct/blob/master/chap08Find/chazhao.c) ，当然 *也有[改进版](https://github.com/wolflion/data_struct/blob/master/chap08Find/chazhao1.c)*
    + [折半查找](https://github.com/wolflion/data_struct/blob/master/chap08Find/zheban.c)
    + 分块查找
+ 动态树的查找
    + [创建二叉树，并将数据插入到节点中ercha.c]()
    + [删除二叉树中一个节点erdel.c]()
+ 哈希表的查找
+ 索引查找

#### chap9 [排序](https://github.com/wolflion/data_struct/tree/master/chap9Sort)  20170319
+ 插入排序
    + 直接插入
    + 折半插入
    + 表插入
    + 希尔排序
+ 交换排序
    + 冒泡排序
    + 双向冒泡排序
    + 快速排序
+ 选择排序
    + 简单选择排序
    + 堆排序
+ 归关排序
+ 基数排序

###  [《写给大家看的算法书》](https://book.douban.com/subject/26821588/)有感
+ 抛弃编程的知识不讲外，我对此理顺了相应的关系。**算法**就是解决问题的方法，有局限性，然后你写论文对它进行提高，对于初学而言，先把基础的学好，知道什么情况下用哪种算法比较好，这个主要在**搜索**和**排序**的使用上。*以前学DS的时候，放在最后两章，其实基础的不影响。*
+ **数据结构**就是数据的存储载体，我的理解是这样，从*数组，到链表，栈，树，图*，熟练掌握这些的基本操作，比如增，删，查，这些常用的操作，然后再根据具体的场景去考虑用什么样的结构比较方便。 
+ 代码练习步骤（**以数组为载体**）
	+  找最大值，最小值，总分，平均分，排名。
	+  排序
		+  插入排序（直接插入，折半插入，希尔）
		+  交换类（冒泡，快排）
		+  选择类（直接选择）
		+  归并排序
	+  搜索（也就是查找）
		+  顺序查找（也就是线性查找）
		+  折半查找
		+  分块查找
	+ *以上先理解这些名词的意思，就算目前代码写不了，至少要能告诉别人这些思路。*
+ **常用的算法思想**
	+ 枚举算法  [百钱买百鸡]()
	+ 递推算法  [斐波那契数列]()
	+ 递归算法  [汉诺塔]()
	+ 分治算法  [欧洲冠军杯比赛日程安排]()
	+ 贪心算法  [找零方案]()
	+ 试探法算法[八皇后]()
	+ 迭代算法  [求平方根]()
	+ 模拟算法  [掷骰子游戏]()
	+ *单个看名字，觉得有点绕，就取了一些喜闻乐见的例子，遇到问题，先去看哪个大类算法是有可能的，再去思考可能性大小。*


##  参考和收获


