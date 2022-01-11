---
aliases: 字符串连接,集合连接
tags: 
date: 2022-01-10 17:08
progress: 基本完成
---
[[字符串]]连接：
将收尾相接得到新[[字符串]]的运算，记为$x*y或xy$。
同样，递归定义如下
$$xy=\begin{cases}
x&			y=\varepsilon \\ 
(xz)a&   y=za
\end{cases}$$
其中$a\in\sum$，且$x,y,z$都是[[字符串]]。

集合连接：
集合A和B的连接，记为A*B或AB，定义为：
$$AB=\{w|w=xy,x\in A且y\in B\}$$
