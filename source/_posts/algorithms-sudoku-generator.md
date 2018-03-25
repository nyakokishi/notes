---
title: 最少提示数数独生成器
date: 2018/03/25 23:07
tags: ['Algorithms']
---
目前生成有唯一解的数独最少需要的提示数为17，但是否仅需16个提示数就能生成有唯一解的数独？看到有篇论文对此进行实验，先是借由遗传算法(Genetic Algorithm)生成最少17个提示数的数独盘面，再对17个提示数的数独盘面删去一个提示数，以此来证明是否存在最少提示数为16且具有唯一解的数独盘面。结果比较遗憾，并没有找到这样的解。相关论文：[Research on Minimum Sudoku Generator](https://core.ac.uk/display/13401839)、[現今最少提示數之數獨盤面產生器研究](http://www.airitilibrary.com/Publication/alDetailedMesh1?DocID=U0021-0712200716113542)
