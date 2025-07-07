


# 最小生成树

**最小生成树**（英语：Minimum spanning tree，简称**MST**）是**最小权重生成树**（英语：Minimum weight spanning tree）的简称，是一个[连通](https://zh.wikipedia.org/wiki/%E8%BF%9E%E9%80%9A%E5%9B%BE "连通图")[加权无向图](https://zh.wikipedia.org/wiki/%E5%9B%BE_(%E6%95%B0%E5%AD%A6) "图 (数学)")中一棵权值最小的[生成树](https://zh.wikipedia.org/wiki/%E7%94%9F%E6%88%90%E6%A0%91 "生成树")。

##  最小生成树求法
### 普利姆（Prim）算法
1).输入：一个加权连通图，其中顶点集合为V，边集合为E；

2).初始化：Vnew = {x}，其中x为集合V中的任一节点（起始点），Enew = {},为空；

3).重复下列操作，直到Vnew = V：

a.在集合E中选取权值最小的边<u, v>，其中u为集合Vnew中的元素，而v不在Vnew集合当中，并且v∈V（如果存在有多条满足前述条件即具有相同权值的边，则可任意选取其中之一）；

b.将v加入集合Vnew中，将<u, v>边加入集合Enew中；

4).输出：使用集合Vnew和Enew来描述所得到的最小生成树。

**prim时间复杂度**

这里记顶点数v，边数e

邻接矩阵:O(v2) 邻接表:O(elog2v)
<!--stackedit_data:
eyJoaXN0b3J5IjpbLTU3NTczNzA5OF19
-->