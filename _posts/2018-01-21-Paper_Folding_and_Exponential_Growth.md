---
layout: post
title: 折纸与指数增长
date: 2018-01-22
categories: blog
tags: [科普]
header-img: "img/posts/20180122.jpg"
---
折纸，听起来很简单，对嘛？

2011年，美国德克萨斯州圣马克中学师生们把长达$$4$$公里的厕纸对折了$$13$$次——2002年，9年前，这个记录是$$12$$次。

**[现场视频，跳转到搜狐观看](http://my.tv.sohu.com/us/63291127/26450606.shtml?src=pl)**

理论上，一张纸可以被无限折叠下去。实际上，折叠次数多了，纸张的内外受力会不均匀，导致纸张弹开，难以继续折叠。

以下是理论计算：

一张$$0.01$$mm，$$1.0000\times 10^{-5}$$米的纸

对折$$3$$次，厚$$8.0000\times 10^{-5}$$米

对折$$10$$次，厚$$1.0240\times 10^{-2}$$米

对折$$25$$次，厚$$3.3554\times 10^2$$米

对折$$30$$次，厚$$1.0737\times 10^4$$米，$$10.737$$千米

对折$$40$$次，厚$$1.0995\times 10^7$$米，$$10995$$千米

对折$$80$$次，厚$$1.2089\times 10^{19}$$米，$$1281$$万光年

对折$$100$$次，厚$$1.2676\times 10^{25}$$米，$$1.34$$亿光年

如果对折$$110$$次，就厚$$1.2981\times 10^{28}$$米，$$1370$$亿光年！而目前测得的宇宙直径，为$$920$$亿光年！

折纸$$110$$次，你就是宇宙的神！


指数增长威力巨大，你是否要试试？

最后附上计算程序源代码：

```c++
#include<iostream>
using namespace std;
int main(){
  int a;              \\折叠次数
  float b=0.00001     \\单张纸厚度（米）
  cin>>a;
  for(int i=1;i<=a;i++) b*=2;
  cout<<b;
  return 0;
}
```

It sounds easy to fold paper, right?

In 2011, about $$4$$km of toliet paper was folded $$13$$ times by teachers and 
students in St. Mark's School Of Texas, USA. The record was still $$12$$ times 9 
years ago, in 2002.

In _theory_(理论), a piece of paper can be folded _infinitely_(无限地). But in fact, if we fold the paper for many times, the stresses between each side of the paper are different, so we cannot keep folding a piece of paper forever.

Here are _theoretical calculations_(理论计算)

A piece of $$0.01$$mm, $$1.0000\times 10^{-5}$$m paper,

If we fold $$3$$ times, it will be $$8.0000\times 10^{-5}$$m;

If we fold $$10$$ times, it will be $$1.0240\times 10^{-2}$$m;

If we fold $$25$$ times, it will be $$3.3554\times 10^2$$m;

If we fold $$30$$ times, it will be $$1.0737\times 10^4$$m, that is 
$$10.737$$km;

If we fold $$40$$ times, it will be $$1.0995\times 10^7$$m, that is $$10995$$km;

If we fold $$80$$ times, it will be $$1.2089\times 10^{19}$$m, that is $$12.81$$ 
millon light years;

If we fold $$100$$ times, it will be $$1.2676\times 10^{25}$$m, that is $$1.34$$ 
hundred millon light years;

And if we fold $$110$$ times, it will be $$1.2981\times 10^{28}$$m, that is 
$$1370$$ hundred millon light years! Until now, as human’s knowledge, the length 
of space, is $$920$$ hundred millon light years!

If you fold a piece of paper for $$110$$ times, you will be the god of space.


_Exponential growth_(指数增长) has a great power, do you want to try?
