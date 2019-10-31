# 第x章 DAM课程笔记模版

## x.0 使用工具
1. 用Markdown格式；
2. 用网易云笔记进行编辑；
3. 可用云笔记或者github进行团队协作。

## x.1 段落
请模仿本模版，用“h1”至“h6”逐层分章节，便于统一。

## x.2 文字
段落中要能够对于相关知识点概念清楚，有叙述，有表达，独立成段，避免单纯从课件复制条条杠杠。


## x.3 公式
公式使用latex表达方式，在markdown中嵌入。

```math
E=m c^2

A =
\begin{bmatrix}
a & b \\
c & d
\end{bmatrix}
```

## x.4 表格
单纯的数据表格，采用Markdown中的标准格式。

header 1 | header 2
---|---
row 1 col 1 | row 1 col 2
row 2 col 1 | row 2 col 2

流程图方面，网易云笔记提供了很好的模版工具，大家可以在撰写过程中学习。如下所示。


```
graph LR
A-->B 
B-->C
C-->B
B-->D
```

或者如下图更为复杂的例子。


```
sequenceDiagram
A->>B: How are you?
B->>A: Great!
```


## x.5 示意图
在一篇优秀的课堂笔记中，必然是图文并茂的。因此示意图部分很重要。建议采用的统一方式，通过互联网资源引入，插入图像。

![image](http://www.cad.zju.edu.cn/home/zhx/papers/ExplicitSI.png)
