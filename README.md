# infrastructure-compiler-L

> 永记于心的前提：不求一步登天，莫要好高骛远，先从最简单的版本入手，一步步进行迭代
>
> 前人栽树🌳，后人乘凉😀

## 第零阶段·整体目标

1. 先看懂[archer前辈](https://github.com/archeryue)的代码
2. 再在前辈基础上进行修改 or 优化

## 第一阶段·编译器入门

### 前言

正在学习C4实现，[C4源代码链接](https://github.com/rswier/c4)，核心将会沿着R大的文章（参考资料1）中提到的优化进行一步步探索

另外找到了[带有小部分注释的C4](https://github.com/comzyh/c4/blob/comment/c4.c)，还有一个前辈所作的[CPC](https://github.com/archeryue/cpc)



### 核心参考资料（在此感谢🙏）

1. [有哪些关于c4 - C in four function 编译器的文章？](https://www.zhihu.com/question/28249756) —— 知乎 R大

   > 虽然R大不推荐无编译器开发基础的小白去直接接触C4，但是因为听闻已久，因此还是想先尝试一下去碰壁一次
   
2. [带有小部分注释的C4](https://github.com/comzyh/c4/blob/comment/c4.c)  —— GitHub

3. [C4源代码链接](https://github.com/rswier/c4) —— GitHub

4. [CPC](https://github.com/archeryue/cpc) —— GitHub

## 整体逻辑

从main入手

1. 对参数做处理
2. 预使用空间的内存分配
3. 开始先把识别字符放到字符表中
4. 