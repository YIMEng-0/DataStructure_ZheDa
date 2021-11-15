# cmake_minimum_required(VERSION <specify CMake version here>)
project(C__Code)

set(CMAKE_CXX_STANDARD 14)

add_executable(C__Code
        上课Demo/1.计时实例.c
        上课Demo/10.堆的操作.cpp
        上课Demo/11.堆的两种建立方式.cpp
        上课Demo/12.哈夫曼树.cpp
        上课Demo/13.并查集的表示.cpp
        上课Demo/14.排序算法的实现.cpp
        上课Demo/15.图的邻接矩阵实现.c
        上课Demo/16.图的邻接表实现.c
        上课Demo/17.图的迷宫遍历.cpp
        上课Demo/18.无权图的最短路径问题.cpp
        上课Demo/19.Dijkstra.cpp
        上课Demo/2.数组存储的线性表.c
        上课Demo/20.Floyd.cpp
        上课Demo/21.Prim.cpp
        上课Demo/22.Kruskal.cpp
        上课Demo/23.散列表数组实现.cpp
        上课Demo/24.散列表链表实现.cpp
        上课Demo/25.KMP算法.cpp
        上课Demo/3.链表存储的线性表.c
        上课Demo/4.栈的顺序存储实现.c
        上课Demo/5.栈的链表存储实现.c
        上课Demo/6.循环队列的顺序存储实现.c
        上课Demo/7.队列的链式存储实现.c
        上课Demo/8.树的链表存储实现.cpp
        上课Demo/9.二叉搜索树的操作.cpp
        编程作业/1.最大子列和问题.cpp
        编程作业/10.是否为同一棵搜索树.cpp
        "编程作业/11.Tree Traversals Again.cpp"
        "编程作业/12.Root of AVL Tree.cpp"
        "编程作业/13.Complete Binary Search Tree.cpp"
        编程作业/14.二叉搜索树的操作集.cpp
        编程作业/15.堆中的路径.cpp
        "编程作业/16.File Transfer.cpp"
        "编程作业/17.Huffman Codes.cpp"
        编程作业/18.列出连通集.cpp
        "编程作业/19.Saving James Bond - Easy Version.cpp"
        "编程作业/2.Maximum Subsequence Sum.cpp"
        编程作业/20.六度空间.cpp
        编程作业/21.哈利·波特的考试.cpp
        "编程作业/22.Saving James Bond - Hard Version.cpp"
        编程作业/23.旅游规划.cpp
        编程作业/24.公路村村通.cpp
        "编程作业/25.How Long Does It Take.cpp"
        编程作业/26.关键活动.cpp
        编程作业/27.排序.cpp
        "编程作业/28.Insert or Merge.cpp"
        "编程作业/29.Insertion or Heap Sort.cpp"
        编程作业/3.二分查找.cpp
        编程作业/30.统计工龄.cpp
        "编程作业/31.PAT Judge.cpp"
        "编程作业/32.Sort with Swap(0, i).cpp"
        编程作业/33.电话聊天狂人.cpp
        编程作业/34.Hashing.cpp
        编程作业/35.QQ帐户的申请与登陆.cpp
        "编程作业/36.Hashing - Hard Version.cpp"
        "编程作业/37.KMP 串的模式匹配.cpp"
        编程作业/4.两个有序链表序列的合并.cpp
        编程作业/5.一元多项式的乘法与加法运算.cpp
        "编程作业/6.Reversing Linked List.cpp"
        "编程作业/7.Pop Sequence.cpp"
        编程作业/8.树的同构.cpp
        "编程作业/9.List Leaves.cpp")
