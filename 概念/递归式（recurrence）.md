---
aliases: 递归式
tags: 
date: 2021-12-23 13:41
progress: 基本完成
---

递归式就是一个等式或者不等式，它通过更小的输入上的函数值来描述一个函数。

例子:
$$T(n)=\begin{cases}
\Theta(1)& 			\text{若n=1}\\
2T(\frac n2)+\Theta(n)&	\text{若n>1}
\end{cases}$$
