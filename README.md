## 面向近似应用的固态硬盘数据布局方案的设计及实现

基于近似存储的闪存系统有望消除存储系统的能耗高、I/O瓶颈等难题，其发展进步将带来计算机体系结构以及系统软件层的革新。本课题探索基于近似存储的闪存系统中面临的现状问题：直接在闪存存储系统中应用现有近似存储技术时，没有充分考虑闪存系统中闪存芯片固有工艺偏差、干扰现象导致数据访问性能低下等现象。本课题提出在近似数据布局方案中解决闪存系统中不可避免的闪存工艺偏差现象，通过合理分配近似数据和精确数据到不同的闪存芯片位置，平衡闪存存储系统的工艺偏差，提升闪存系统的性能。