# 拓补排序
有向无环图 DAG
- 每个顶点仅出现一次
- 如果存在一条从顶点 A 到 顶点 B 的路径，那么 A 出现在顶点 B 的前面

如何拓补排序呢
- 找出入度为 0 的顶点
- 将入度为 0 的顶点值去除，作为拓补排序后序列表的元素，再把入度减一
- 找到新的入度为 0 的顶点


# 来个题目吧

