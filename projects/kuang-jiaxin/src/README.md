## 项目说明

这个项目是一个网络规划和流量分配的模拟器，包括两个主要部分：网络定义和流量分配算法。

1. 网络定义部分：
   - 使用字典数据结构来表示网络，其中节点是字典的键，相邻节点列表是对应键的值。
   - 提供了添加节点和添加连接的函数，用于动态构建网络结构。
   - 包含了网络的初始化过程，将节点和连接添加到网络中，并打印最终的网络结构。
2. 流量分配算法部分：
   - 使用 Dijkstra 算法来计算网络中两点之间的最短路径。
   - 提供了流量分配的函数，根据成本函数和OD对（Origin-Destination对）来分配流量。
   - 实现了单个OD对的流量分配过程，包括更新成本、计算最短路径、流量加载和流量合并等操作。

下面是项目中用到的一些关键概念和数据结构：

- Network: 用字典表示的网络结构，包括节点和连接信息。
- AttributeMap: 用字典表示的属性映射，例如长度和速度信息的映射。
- Path: 用列表表示的路径信息，表示网络中的一条路径。

整个项目主要用于模拟网络规划和流量分配的过程，通过定义网络结构和实现流量分配算法，可以模拟在实际交通网络中的流量分布情况，并进行一些简单的优化和规划操作。

这个项目还在进行开发中，部分函数中可能存在未实现的部分，需要进一步完善和测试。



## 小组成员

江旭坤：组织，编码

况佳欣：编码、调试

罗群羽：编码、调试

潘国璨：文档写作

王婷焮：文档写作