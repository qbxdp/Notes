### 给你一张知识地图，计算机组成原理应该怎么学

**学习地图：** /img/knowledge-map.img

#### 四大部分

##### 计算机的基本组成

- 运算器，控制器，存储器，输入输出设备这五大基本组件。
- 计算机的两个核心指标：性能和功耗。

#####  计算机的指令和计算

- 指令部分：搞明白，一行行的 C，Java，PHP 程序，是怎么在计算机里面跑起来的。指令由控制器来控制的。
- 计算部分，从二进制和编码开始，理解数据在计算机里面的表示。以及怎么从数字电路层面，实现加法，乘法这些基本的运算功能。靠的就是运算器【Arithmetic Logic Unit】。其中有个特别重要的概念就是 **浮点数【Floating Point**。

##### 处理器设计

- CPU 时钟。
- 数据通路。

##### 存储器和 I/O 设备

- 存储器原理。从上到下的 CPU 高速缓存，内存 ， SSD 硬盘和机械硬盘的工作原理。以及他们之间的性能差异。

#### 补充阅读资料

##### 入门书籍

- 《计算机是怎样跑起来的》
- 《程序是怎样跑起来的》
- 硬件层面的基础实现，可以看看 Coursera 上的北京大学免费公开课 《Computer Organization》。

##### 深入学习书籍

- 《计算机组成与设计：硬件/软件接口》
- 《深入理解计算机系统》, 被称为 CSAPP 的经典教材，B站和油管上都有。
- 《计算机组成：结构化方法》来自操作系统大神塔能鲍姆(Andrew S. Tanenbaum), 适合作为一个辅助的参考书来使用。
- 《计算机体系结构：量化研究方法》，如果你对计算机体系结构有兴趣的话。

#### 课外阅读

对于资深程序员来说，来自 Redhat 的 **What Every Programmer Should Know About Memory** 是写出高性能程序不可不读的经典材料。而 LMAX 开源的 Disruptor，则是通过实际应用程序，来理解计算机组成原理中各个知识点的最好范例。

《编码：隐匿在计算机软硬件背后的语言》和 《程序员的自我修养：连接，封装和库》是理解计算机硬件和操作系统层面代码执行的优秀阅读材料。

---

#### 总结延伸

最有效的办法，**不是段时间冲刺，而是有节奏地坚持。要和专栏的发布节奏同步推进，做好思考其，并且多在流言区和其他朋友一起交流。**
