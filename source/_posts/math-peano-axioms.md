---
title: 数学归纳法的正确性
date: 2018/04/03 13:01
mathjax: true
---
数学归纳法的正确性是由 [peano 公理](https://en.wikipedia.org/wiki/Peano_axioms) 保证的
```
皮亚诺公理：

1. 1 是自然数；
2. 每一个确定的自然数 a，都有一个确定的后继数 a',a'也是自然数；
3. 对于每个自然数b、c，b = c 当且仅当 b 的后继数 = c 的后继数；
4. 1 不是任何自然数的后继数
5. 任意关于自然数的命题，如果证明了它对自然数 1 是对的，又假定它对自然数 n 为真时，可以证明它对 n' 也真，那么命题对所有自然数都真
```
正是第五条公设保证了数学归纳法的正确性。
