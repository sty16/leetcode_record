### AC自动机

Trie树上的KMP算法

定义fail指针，如果一个编号为j的Trie节点指向编号为i的节点，则root节点到i节点的字符串是root节点到j节点的一个后缀。

+ 每一个点j的Fail指针指向点的深度一定是比j小的。
+ 第一层节点的fail指针为root。
+ 实现时采用队列，采用父节点的fail指针更新子节点的fail指针，

