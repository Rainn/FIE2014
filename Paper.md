#A high performance education system in hybrid cloud


##Abstract

**以前做了什么**

In prior work, we proposed an adaptive web-based mobile education architecture that complements the instantaneity of communication and interactivity between teachers and students.

**目前面临的问题**

With the development of SaaS business as well as the evolution of smart devices and users expectation recently, this architecture is facing challenges like delay of data transmission and interaction collision that lead to the data can't be delivered to the right place instantly in hybrid cloud environment.

**本篇文章提出两点解决问题**

This paper addresses the question of how to develop a module for monitoring polydirectional communications among hybrid network and find an effective way to synchronize information between browsers in hybrid education cloud.

总结出来三种普遍的数据连接transaction in hybrid cloud: 
1 一对多  大数据量 视频。。。
2 星型 并发多
3 一对一 并发大

**细化核心技术是什么**

Specifically, we propose an improved architecture which uses both the public and private clouds. A “Node Monitoring System” is used to detect each node’s status, bandwidth, network topographic in order to  generate data buffering algorithm and transmission policy in the system. Also, and Websocket based methodology is designed to accelerate the synchronous data in mobile education environment.

**评测和结论**

The result shows that high performance and rapid data sharing can be obtained while keeping the devices in hybrid public and private cloud.
