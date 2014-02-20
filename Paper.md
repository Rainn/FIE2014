#Interactive Educational System with high performance in hybrid cloud 


##Abstract

**以前做了什么**

In prior work, we proposed an adaptive web-based mobile education architecture that complements the instantaneity of communication and interactivity of users to meet the needs of improving communication between teachers and students in the coming education revolution.

**目前面临的问题**

With the development of SaaS business as well as the evolution of smart devices and incremental of user's expectation recently, this architecture is facing challenges like delay of data transmission and interaction collision that lead to sometimes the data can't be delivered to the right place instantly in hybrid cloud environment. We abstracted the hybrid network topography from real education circumstance to figure out that there are massive coursewares, such as real-time video stream, flash based experimental content, give too much pressure to the browsers in star type network and there are many concurrence transmission and complex paths in mesh type network.

总结出来三种普遍的数据连接transaction in hybrid cloud: 
1 一对多  大数据量 视频。。。
2 星型 并发多
3 一对一 并发大

**本篇文章提出两点解决问题**

This paper addresses the question of how to develop a module for monitoring polydirectional communications among hybrid network and find an effective way to synchronize information between browsers in hybrid education cloud.

**细化核心技术是什么**

Specifically, we propose an improved architecture which uses both the public and private clouds characteristics. A “Node Monitoring System” is used to detect each node’s specification, bandwidth, network topography in order to  generate data buffering algorithm and transmission policy in the system. Also, Websocket based methodology is designed to accelerate the response speed of synchronous data in mobile education environment.

**评测和结论**

The result shows that high performance and rapid data sharing can be obtained while keeping the devices in hybrid public and private cloud under current situation. We present this architecture to further simplify similar web application development in hybrid cloud by using add-on components for other use cases such as interactive conferencing system or play games. It will also extend beyond web to native applications and reduces the barrier between web and non-web applications for more needs in our future research.

不只在教育领域，在需要交互的领域，比如教育。。。

Keywords: remote education; cloud education; hybrid cloud; web-based system; mobile education; SaaS;
