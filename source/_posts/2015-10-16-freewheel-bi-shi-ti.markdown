---
layout: post
title: "FreeWheel笔试题一道"
date: 2015-10-16 23:15:20 +0800
comments: true
categories: 
---
今天参加了FreeWheel笔试，不难，但是我答的不好。。可能还是太渣了吧。最后一道题是MapReduce计算矩阵乘法，可是我只懂MapReduce的一些概念性的东西，这题果断做不出来。。

算了不想了。还有一道挺有意思的题，第一次遇到，这里记下来。

程序改错：以下程序要打印20个-号，但程序错了。只允许修改或添加一个字符，把程序改成正确的。要求写出三种解法。

```C
int n = 20;
for (int i = 0; i < n; i--) {
    printf("-");
}
```

解法

- (1): i < n $\rightarrow$ -i < n (这应该是最简单的，我当时竟然没想到。。)
- (2): i\-\- $\rightarrow$ n\-\-
- (3): i < n $\rightarrow$ i + n
