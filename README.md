
# 一.Java基础
## 基础
- 面向对象的特征：继承、封装和多态
- final, finally, finalize 的区别
- int 和 Integer 有什么区别，Integer的值缓存范围
- Exception、Error、运行时异常与一般异常有何异同
- 包装类，装箱和拆箱
- char和double的字节，以及在内存的分布是怎样；
- 请写出5种常见到的runtime exception
- 重载和重写的区别
- String、StringBuilder、StringBuffer
- 抽象类和接口有什么区别
- 说说反射的用途及实现,反射的作用与实现原理；
- 说说自定义注解的场景及实现
- equals 与 == 的区别
- String中hashcode是怎么实现的；
- hashCode和equals方法的区别与联系
- toString()方法什么情况下需要重写；
- 什么是Java序列化和反序列化，如何实现Java序列化？或者请解释Serializable 接口的作用
- Object类中常见的方法，为什么wait  notify会放在Object里边？
- Java的平台无关性如何体现出来的
- JDK和JRE的区别
- Java 8有哪些新特性
- Java 8流式迭代的好处？
- JDBC 流程
- MVC 设计思想
- 浅拷贝和深拷贝的区别；
- 软引用和弱引用的使用场景（软引用可以实现缓存，弱引用可以用来在回调函数中防止内存泄露）；
- String s="abc"和String s=new String("abc")区别；
- Java中的回调机制；
- 判断对象相等时，什么情况下只需要重写 equals()，什么情况下需要重写 equals(),hashcode()？
- 序列化和反序列化底层如何实现的（ObjectOutputStream 、ObjectInputStream、 readObject  writeObject）；
- 如何调试多线程的程序；
- JDK中哪些实现了单例模式？
- float f = 1.4f;double d = 1.4d; 与 float f = 1.5f;double d = 1.5d; 是否为true，内存是怎样的；
- split的源码，split("a|b|c");得出多少个数组；
- Java的多态怎么实现;
## 设计模式
- 你项目中有使用哪些设计模式
- 说说常用开源框架中设计模式使用分析
- 说说你对设计原则的理解
- 23种设计模式的设计理念
- 设计模式之间的异同，例如策略模式与状态模式的区别
- 设计模式之间的结合，例如策略模式+简单工厂模式的实践
- 设计模式的性能，例如单例模式哪种性能更好。
- 模板方法模式；
- 发布/订阅使用场景；
- 开闭原则，解析工厂方法模式，建造者模式，区别。手撸出来。
## 集合
- List 和 Set 区别
- List 和 Map 区别
- Arraylist与LinkedList默认空间是多少；
- ArrayList和LinkList的删除一个元素的时间复杂度；（ArrayList是O(N)，LinkList是O(1)）；
- Arraylist 与 LinkedList 区别
- Arraylist与LinkedList各自的优势
- ArrayList 与 Vector 区别
- 说一下TreeMap的实现原理？红黑树的性质？红黑树遍历方式有哪些？如果key冲突如何解决？setColor()方法在什么时候用？什么时候会进行旋转和颜色转换？
- HashMap 和 Hashtable 的区别
- HashSet 和 HashMap 区别
- HashMap 和 ConcurrentHashMap 的区别
- HashMap 的工作原理及代码实现，什么时候用到红黑树
- HashMap在什么时候时间复杂度是O（1），什么时候是O（n），什么时候又是O（logn）；
- 谈谈HashMap，哈希表解决hash冲突的方法；
- 怎么解决Hash冲突；（开放地址法、链地址法、再哈希法、建立公共溢出区等
- 多线程情况下HashMap死循环的问题
- HashMap出现Hash DOS攻击的问题
- 手写简单的HashMap
- 看过那些Java集合类的源码
- ConcurrentHashMap 的工作原理及代码实现，如何统计所有的元素个数
- Set内存放的元素为什么不可以重复，内部是如何保证和实现的？
- Set和hashCode以及equals方法的联系
- 为什么要重写hashcode()和equals()以及他们之间的区别与关系；
- Object的hashcode()是怎么计算的？
- 若hashcode方法永远返回1或者一个常量会产生什么结果？
- HashSet方法里面的hashcode存在哪，如果重写equals不重写hashcode会怎么样？
- Java Collections和Arrays的sort方法默认的排序方法是什么；
## 线程
- AtomicInteger底层实现原理；
- 写出一个必然会产生死锁的伪代码；
- CopyOnWriteArrayList是什么；
- 创建线程的方式及实现
- 线程和进程的概念、并行和并发的概念
- sleep() 、join（）、yield（）有什么区别
- 进程间通信的方式
- 说说 CountDownLatch、CyclicBarrier 原理
- 说说 CountDownLatch 与 CyclicBarrier 区别
- 说说 Semaphore 原理
- 说说 Exchanger 原理
- ThreadLocal 原理分析，ThreadLocal为什么会出现OOM，出现的深层次原理
- 讲讲线程池的实现原理
- 线程池的实现？四种线程池？重要参数及原理？任务拒接策略有哪几种？
- 线程池的几种方式
- 线程的生命周期，状态是如何转移的
- Java线程池的几个参数的意义和实现机制；
- Java线程池使用无界任务队列和有界任务队列的优劣对比；
- 线程状态以及API怎么操作会发生这种转换；
- 一个线程连着调用start两次会出现什么情况？（由于状态只有就绪、阻塞、执行，状态是无法由执行转化为执行的，所以会报不合法的状态！）
- wait方法能不能被重写？（wait是final类型的，不可以被重写，不仅如此，notify和notifyall都是final类型的），wait能不能被中断；
- 常用的避免死锁方法；
- 有三个线程T1 T2 T3，如何保证他们按顺序执行；
- 三个线程循环输出ABCABCABC....
- Java中有哪些同步方案（重量级锁、显式锁、并发容器、并发同步器、CAS、volatile、AQS等）
- 线程池，如何根据CPU的核数来设计线程大小，如果是计算机密集型的呢，如果是IO密集型的呢？
- 线程池内的线程如果全部忙，提交⼀个新的任务，会发⽣什么？队列全部塞满了之后，还是忙，再提交会发⽣什么？
- ExecutorService你一般是怎么⽤的？是每个Service放一个还是个项目放一个？有什么好处？
- 多线程是解决什么问题的？线程池解决什么问题？
- 线程池，如何设计的，里面的参数有多少种，里面的工作队列和线程队列是怎样的结构，如果给你，怎样设计线程池？
- 两个线程设计题。记得一个是：t1,t2,t3，让t1，t2执行完才执行t3，原生实现。

## 锁机制
- 用过并发包下边的哪些类；
- 说说线程安全问题，什么是线程安全，如何保证线程安全
- 重入锁的概念，重入锁为什么可以防止死锁
- 产生死锁的四个条件（互斥、请求与保持、不剥夺、循环等待）
- 如何检查死锁（通过jConsole检查死锁，jstack）
- volatile 实现原理（禁止指令重排、刷新内存）
- synchronize 实现原理（对象监视器）
- synchronized 与 lock 的区别
- synchronized与ReentraLock哪个是公平锁；
- AQS原理，ReentranLock源码，设计原理，整体过程。
- - AQS同步队列
- sync原理详细，sync内抛异常会怎样，死锁吗？还是释放掉？怎么排查死锁？死锁会怎样？有没有什么更好的替代方案？
- CAS无锁的概念、乐观锁和悲观锁
- 常见的原子操作类
- 什么是ABA问题，出现ABA问题JDK是如何解决的
- 乐观锁的业务场景及实现方式
- 乐观锁的业务场景及实现方式
- Java 8并法包下常见的并发类
- 把所有认识熟用的JUC( java.util.concurrent(简称JUC)包)下的类写出来，讲下使用，然后讲下原生的线程操作;
- 偏向锁、轻量级锁、重量级锁、自旋锁的概念
- 多个线程同时读写，读线程的数量远远⼤于写线程，你认为应该如何解决并发的问题？你会选择加什么样的锁？
- synchronized关键字锁住的是什么东西？在字节码中是怎么表示的？在内存中的对象上表现为什么？
- wait/notify/notifyAll⽅法需不需要被包含在synchronized块中？这是为什么？
- 乐观悲观锁的设计，如何保证原子性，解决的问题；


## JVM
- GC分哪两种，Minor GC 和Full GC有什么区别？什么时候会触发Full GC？分别采用什么算法？
- Minor GC与Full GC分别在什么时候发生？什么时候触发Full GC;
- Full GC次数太多了，如何优化；
- GC收集器有哪些？CMS收集器与G1收集器的特点。
- Java在什么时候会出现内存泄漏；
- Java中的大对象如何进行存储；
- 讲下JVM的大页模式，JVM内存模型;
- JVM里的有几种classloader，为什么会有多种？
- rt.jar被什么类加载器加载，什么时间加载；
- 自己写的类被什么加载，什么时间加载；
- 什么是双亲委派机制？介绍一些运作过程，双亲委派模型的好处；
- 什么情况下我们需要破坏双亲委派模型；
- 常见的JVM调优方法有哪些？可以具体到调整哪个参数，调成什么值？
- JVM虚拟机内存划分、类加载器、垃圾收集算法、垃圾收集器、class文件结构是如何解析的；
- 自己写的两个不同的类是被同一个类加载器加载的吗？为什么？
- 为什么新生代内存需要有两个Survivor区？
- 类加载的五个过程：加载、验证、准备、解析、初始化；
- G1停顿吗，CMS回收步骤，CMS为什么会停顿，停顿时间；
- CMS垃圾回收过程；
- JVM运行时内存区域划分
- 栈主要存的数据是什么，堆呢？
- 堆分为哪几块，比如说新生代老生代，那么新生代又分为什么？
- 内存溢出OOM和堆栈溢出SOE的示例及原因、如何排查与解决
- 如何判断对象是否可以回收或存活
- 常见的GC回收算法及其含义
- 常见的JVM性能监控和故障处理工具类：jps、jstat、jmap、jinfo、jconsole等
- JVM如何设置参数
- JVM性能调优
- 类加载器、双亲委派模型、一个类的生命周期、类是如何加载到JVM中的
- 类加载的过程：加载、验证、准备、解析、初始化
- 什么情况下会触发类加载；
- 强引用、软引用、弱引用、虚引用
- Java内存模型JMM
- JMM里边的原子性、可见性、有序性是如何体现出来的，JMM中内存屏障是什么意思，
- 引用计数法与GC Root可达性分析法区别；
- 为什么JVM调优经常会将-Xms和-Xmx参数设置成一样；
- 直接内存如何管理的；
- 如果你的项目出现了内存泄露，如何排查的，怎么监控这个问题呢；
- 标记清除和标记整理的区别和优缺点，为何标记整理会发生stop the world；
- 对象内存布局，然后讲下对象的死亡过程？
- 对象头，详细讲下；
- 你有遇到过临界区问题吗？有遇到过吗？你在项目遇到这个问题是怎样解决的？


## 设计模式

- 常见的设计模式

- 设计模式的的六大原则及其含义

- 常见的单例模式以及各种实现方式的优缺点，哪一种最好，手写常见的单利模式

- 设计模式在实际场景中的应用

- Spring中用到了哪些设计模式

- MyBatis中用到了哪些设计模式

- 你项目中有使用哪些设计模式

- 说说常用开源框架中设计模式使用分析

- 动态代理很重要！！！

## 数据结构

- 树（二叉查找树、平衡二叉树、红黑树、B树、B+树）

- 深度有限算法、广度优先算法

- 克鲁斯卡尔算法、普林母算法、迪克拉斯算法

- 什么是一致性Hash及其原理、Hash环问题

- 常见的排序算法和查找算法：快排、折半查找、堆排序等
- KMP算法（一种改进的字符串匹配算法）；
- 反转链表手撸;
- 页面置换算法呢？多少种？有最优的置换算法吗？
- 快排，给一串数组，把具体每次patition写下，最终结果也写45, 32, 41, 35, 38, 20, 50;
- 一个整数status, 判断第K个比特位是否为比特1;
- 把递归实现的快排改成非递归，你知道非递归有什么好处吗;
- 举例使用分治思想的算法;
- TopN的大数据量题；
- 红黑树的实现原理和应用场景；
## 网络/IO基础
- HTTP、TCP、UDP的区别和联系；
- TCP和UDP各自的优势，知道哪些使用UDP协议的成功案例；
- TCP和UDP各用了底层什么协议；
- 单个UDP报文最大容量；
- 单个TCP报文最大容量；
- TCP报头格式、UDP报头格式；
- Server遭遇SYN Flood应当怎么处理；
- 数据链路层是做什么的?
- 数据链路层的流量控制？
- 网络模型的分层、IP和Mac地址在那个层、TCP和HTTP分别在那个层；
- TCP滑动窗口；
- TCP为什么可靠；
- TCP三次握手，为什么不是三次，为什么不是四次；
- TCP三次握手数据丢失了怎么办？那如果后面又找到了呢
- TCP的同传，拆包与组装包是什么意思；
- TCP的拥塞控制、流量控制详细说明？
- BIO、NIO、AIO的概念
- NIO是什么？适用于何种场景？
- 什么是长连接和短连接
- 讲下请求头细节？
- Http1.0和2.0相比有什么区别，可参考《Http 2.0》

- Https的基本概念
- Https的过程;
- Https和Http有什么区别；
- Http 为什么是无状态的；
- 两个不同ip地址的计算机之间如何通信；
- 地址解析协议ARP；
- OSI七层模型，每层都说下自己的理解和知道的，说的越多越好；
- OSI七层模型分别对应着五层模型的哪一部分；
- 三次握手和四次挥手、为什么挥手需要四次
- Get和Post，讲下区别，要我模拟出抓包来。
- 详细讲下Cookie和Session，Token，OAuth2.0协议;
- 从游览器中输入URL到页面加载的发生了什么？可参考《从输入URL到页面加载发生了什么》![http://mp.weixin.qq.com/s?__biz=MzI1NDQ3MjQxNA==&mid=2247483724&idx=1&sn=e58dd30d124971c795584e8673d6cc71&chksm=e9c5f8fddeb271ebebbb6c350ed1abc252f1f26b4f35c4ce36e10bde9659a37520feabed2290&scene=21#wechat_redirect]

- 拆包和粘包的问题，如何解决，如果我们的包没有固定长度的话，我们的应用程序应该如何解决；
- DHCP如何实现分配IP的； 发现阶段（DHCP客户端在网络中广播发送DHCP DISCOVER请求报文，发现DHCP服务器，请求IP地址租约）、提供阶段（DHCP服务器通过DHCP OFFER报文向DHCP客户端提供IP地址预分配）、选择阶段（DHCP客户端通过DHCP REQUEST报文确认选择第一个DHCP服务器为它提供IP地址自动分配服务）和确认阶段（被选择的DHCP服务器通过DHCP ACK报文把在DHCP OFFER报文中准备的IP地址租约给对应DHCP客户端）。
- 再聊下Http的Http basic authentication;
# 二.操作系统
- Linux静态链接和动态链接；

- 什么是IO多路复用模型（select、poll、epoll）；

- Linux中的grep管道用处？Linux的常用命令？

- 操作系统中虚拟地址、逻辑地址、线性地址、物理地址的概念及区别；
- 为什么要内存对齐；
- 为什么会有大端小端，htol这一类函数的作用；
- 内存的页面置换算法；

- 内存的页面置换算法；

- 进程调度算法，操作系统是如何调度进程的；

- 父子进程、孤儿进程、僵死进程等概念；

- fork进程时的操作；

- kill用法，某个进程杀不掉的原因（僵死进程；进入内核态，忽略kill信号）；

- 系统管理命令（如查看内存使用、网络情况）；

- find命令、awk使用；

- Linux下排查某个死循环的线程；
- top显示出来的系统信息都是什么含义；（重要！）
- Linux地址空间，怎么样进行寻址的；
- Linux如何查找目录或者文件的；
- Linux下可以在/proc目录下可以查看CPU的核心数等；cat /proc/下边会有很多系统内核信息可供显示；
- 说一下栈的内存是怎么分配的；
- 说一下栈帧的内存是怎么分配的；
- Linux各个目录有了解过吗？/etc、/bin、/dev、/lib、/sbin这些常见的目录主要作用是什么？
- Linux下排查某个死循环的线程；
- 进程的内存分布；
- 如何查找一个进程打开所有的文件；
- 说一下查看使用的协议及其对应的端口；
- 为什么会有内核态，保护模式你知道吗?
- 文件是怎么在磁盘上存储的？
- 有了进程为何还要线程呢，不同进程和线程他们之间有什么不同。（进程是资源管理的最小单位，线程是程序执行的最小单位。在操作系统设计上，从进程演化出线程，最主要的目的就是更好的支持SMP以及减小（进程/线程）上下文切换开销。）
- 文件系统，进程管理和调度，内存管理机制、虚地址保护模式；
- InnoDB聚集索引B+树叶子节点和磁盘什么顺序相同;
# 三.数据存储和消息队列

## 数据库
- MySQL 索引使用的注意事项
- DDL、DML、DCL分别指什么
- explain命令
- left join，right join，inner join
- 数据库事物ACID（原子性、一致性、隔离性、持久性）
- 事物的隔离级别（读未提交、读以提交、可重复读、可序列化读）
- 脏读、幻读、不可重复读
- 数据库的几大范式,数据库的三大范式；
- 数据库常见的命令
- 说说分库与分表设计，http://mp.weixin.qq.com/s?__biz=MzI1NDQ3MjQxNA==&mid=2247483931&idx=1&sn=6eda41aa81c1243422a603205d2fad22&chksm=e9c5fbaadeb272bc92537803c14a6f55e1170b1a3b8f60160f66417800c0ace960dfe192717a&scene=21#wechat_redirect
- 分库与分表带来的分布式困境与应对之策（如何解决分布式下的分库分表，全局表？）
- 说说 SQL 优化之道
- MySQL遇到的死锁问题、如何排查与解决
- 存储引擎的 InnoDB与MyISAM区别，优缺点，使用场景
- 说说反模式设计
- 存储引擎的 InnoDB与MyISAM区别，优缺点，使用场景
- 数据库索引的原理
- 索引类别（B+树索引、全文索引、哈希索引）、索引的原理
- 什么是自适应哈希索引（AHI）
- 为什么要用 B+tree作为MySQL索引的数据结构
- SQL优化思路，联合索引与底层树结构的映像关系，索引结构（B+、B-），为什么用这样的结构；
- 聚集索引与非聚集索引的区别
- 遇到过索引失效的情况没，什么时候可能会出现，如何解决
- limit 20000 加载很慢怎么解决
- 如何选择合适的分布式主键方案
- 选择合适的数据存储方案
- 常见的几种分布式ID的设计方案
- 常见的数据库优化方案，在你的项目中数据库如何进行优化的
- 数据库索引，什么是全文索引，全文索引中的倒排索引是什么原理；
- 数据库最佳左前缀原则是什么？
- 什么是组合索引，组合索引什么时候会失效；
- 悲观锁和乐观锁的原理和应用场景；
- 左连接、右连接、内连接、外连接、交叉连接、笛卡儿积等
- 一般情况下数据库宕机了如何进行恢复（什么是Write Ahead Log机制，什么是Double Write机制，什么是Check Point）；
- 什么是redo日志、什么是undo日志；
- 数据库中的隔离性是怎样实现的；原子性、一致性、持久性又是如何实现的；
- 关系型数据库和非关系型数据库区别；
- MySQL并发情况下怎么解决（通过事务、隔离级别、锁）；
- MySQL中的MVCC机制是什么意思，根据具体场景，MVCC是否有问题；
- MySQL数据库的隔离级别，以及如何解决幻读；
- InnoDB的插入缓冲和两次写的概率和意义；
- 如果建了⼀个单列索引，查询的时候查出2列，会⽤到这个单列索引吗？（会用到）
- 如果建了⼀个包含多个列的索引，查询的时候只⽤了第⼀列，能不能⽤上这个索引？查三列呢？
- 接上题，如果where条件后⾯带有⼀个 i + 5 < 100 会使⽤到这个索引吗？
- like %aaa%会使⽤索引吗? like aaa%呢?
- drop、truncate、delete的区别？
- 平时你们是怎么监控数据库的? 慢SQL是怎么排查的？（慢查询日志）
- 你们数据库是否⽀持emoji表情，如果不⽀持，如何操作?选择什么编码方式？如果支持一个表情占几个字节?(utf8mb4)；
- 如果查询很慢，你会想到的第⼀个⽅式是什么？（数据库索引）
- 你目前为止遇到的最大数据量是多少？知道100万时候怎么设计吗？1000万呢？过几十亿呢？
- MySQL有多少个参数可调，除了最大连接数。全部列出来，一个个分析。
- 数据库什么情况下索引会失效;
- 锁机制介绍：行锁、表锁、排他锁、共享锁；
- 事务介绍，分布式事物的理解，常见的解决方案有哪些，什么事两阶段提交、三阶段提交；
- MySQL记录binlog的方式主要包括三种模式？每种模式的优缺点是什么？
- SQL的整个解析、执行过程原理、SQL行转列；


## Redis
- Redis 有哪些数据类型,http://mp.weixin.qq.com/s?__biz=MzI1NDQ3MjQxNA==&mid=2247483987&idx=1&sn=5c5e4cd5bc73a7e6f84e5d6adfab0935&chksm=e9c5fbe2deb272f4b5b75bd2ac92bb27950452623ec83c0e1add7e30c773160421fab1571680&scene=21#wechat_redirect
- Redis 内部结构
- 聊聊 Redis 使用场景
- Redis 如何实现持久化,http://mp.weixin.qq.com/s?__biz=MzI1NDQ3MjQxNA==&mid=2247483992&idx=1&sn=8f554bc490c4db1a78a30144f873e911&chksm=e9c5fbe9deb272fff47483c241e6d2a7aae99dc8f6fe9fee31f2dd214d0cf81b33d51f7a7dbe&scene=21#wechat_redirect
- Redis 集群方案与实现
- Redis 为什么是单线程的？
- 缓存雪崩、缓存穿透、缓存预热、缓存更新、缓存降级
- 使用缓存的合理性问题
- Redis常见的回收策略
- Redis中zSet跳跃表问题；
- Redis的set的应用场合？
- Redis高级特性了解吗？
- Redis的pipeline有什么用处？
- Redis集群宕机如何处理，怎么样进行数据的迁移；
- Redis主节点宕机了怎么办，还有没有同步的数据怎么办;
- Redis原子操作怎么用比较好；
- Redis分布式锁操作的原子性，Redis内部是如何实现的？
- Redis过期策略是怎么实现的呢？
- Redis插槽的分配（key的有效部分使用CRC16算法计算出哈希值，再将哈希值对16384取余，得到插槽值）;
- Redis主从是怎么选取的（一种是主动切换，另一种是使用sentinel自动方式）;
- Redis复制的过程;
- Redis队列应用场景；
- Redis渐进式rehash过程？
- Redis如何使用Redis实现分布式锁？
- Redis跳跃表的问题；

## ElasticSearch
- 倒排索引
- 聊聊 ElasticSearch 使用场景

## 消息队列
- 消息队列的使用场景
- 消息队列使用的场景介绍和作用（应用耦合、异步消息、流量削锋等）；
- 消息的重发补偿解决思路
- 如何解决消息队列丢失消息和重复消费问题；

- 消息的幂等性解决思路

- 消息的堆积解决思路

- 自己如何实现消息队列

- 如何保证消息的有序性
- 异步队列怎么实现；



# 四.开源框架和容器
## Spring

- Servlet的生命周期
- Servlet如何保证单例模式,可不可以编程多例的哪？

- 转发与重定向的区别
- Spring中@Autowired和@Resource注解的区别？
- BeanFactory 和 ApplicationContext 有什么区别
- 如果一个接⼝有2个不同的实现, 那么怎么来Autowire一个指定的实现？(可以使用Qualifier注解限定要注入的Bean，也可以使用Qualifier和Autowire注解指定要获取的bean，也可以使用Resource注解的name属性指定要获取的Bean)
- Spring框架中需要引用哪些jar包，以及这些jar包的用途；
- Spring Boot没有放到web容器⾥为什么能跑HTTP服务？
- Spring中循环注入是什么意思，可不可以解决，如何解决；
- Spring Bean 的生命周期
- Spring声明一个 bean 如何对其进行个性化定制；

- Spring IOC 如何实现
- Spring IoC涉及到的设计模式；（工厂模式、单利模式。。）

- Spring中Bean的作用域，默认的是哪一个

- 说说 Spring AOP、Spring AOP 实现原理

- 动态代理（CGLib 与 JDK）、优缺点、性能对比、如何选择

- Spring 事务实现方式、事务的传播机制、默认的事务类别

- Spring 事务底层原理

- Spring框架如何实现事务的；

- Spring事务失效（事务嵌套），JDK动态代理给Spring事务埋下的坑，可参考《JDK动态代理给Spring事务埋下的坑！》
- Spring的声明式事务 @Transaction注解⼀般写在什么位置? 抛出了异常会⾃动回滚吗？有没有办法控制不触发回滚?
- 如何自定义注解实现功能

- Spring MVC 运行流程

- Spring MVC 启动流程
- HTTP 请求的 GET 与 POST 方式的区别

- Spring 的单例实现原理

- Spring 框架中用到了哪些设计模式

- Spring 其他产品（Srping Boot、Spring Cloud、Spring Secuirity、Spring Data、Spring AMQP 等）
- Spring Could的常见组件有哪些？

- 有没有用到Spring Boot，Spring Boot的认识、原理
- 一个Controller调用两个Service，这两Service又都分别调用两个Dao，问其中用到了几个数据库连接池的连接？


## Mybatis
- MyBatis有什么优势；
- MyBatis的原理
- MyBatis如何做事务管理；

## Tomcat
- Tomcat的基础架构（Server、Service、Connector、Container）

- Tomcat如何加载Servlet的

- Pipeline-Valve机制
- 你项目的并发是多少？怎么解决高并发问题？单机情况下Tomcat的并发大概是多少，MySQL的并发大致是多少？
- 如何优化Tomcat，常见的优化方式有哪些；
- Tomcat本身的参数你⼀般会怎么调整？
- Tomcat缓存，聊下缓存的整体理解，知道多少种缓存；


## Netty
- 为什么选择 Netty

- 说说业务中，Netty 的使用场景

- 原生的 NIO 在 JDK 1.7 版本存在 epoll bug

- 什么是TCP 粘包/拆包

- TCP粘包/拆包的解决办法

- Netty 线程模型

- 说说 Netty 的零拷贝

- Netty 内部执行流程

- Netty 重连实现

## Dubbo
- 什么是Dubbo
- 什么是RPC、如何实现RPC、RPC 的实现原理，http://mp.weixin.qq.com/s?__biz=MzI1NDQ3MjQxNA==&mid=2247483900&idx=1&sn=c5ca198a66a701f81c2ab118fe7a734a&chksm=e9c5f84ddeb2715bc574e467cd6537ef81f223453e0989ffd136976b48dcc2d961a75be596de&scene=21#wechat_redirect
- Dubbo中的SPI是什么概念
- Dubbo的基本原理、执行流程
- 你怎么理解 RPC 框架
- 说说 RPC 的实现原理
- 说说 Dubbo 的实现原理
- Dubbo的基本原理，RPC，支持哪些通信方式，服务的调用过程；
- Dubbo如果有一个服务挂掉了怎么办；
- Dubbo请求流程以及原理；
- Dubbo完整的一次调用链路介绍；
- Dubbo支持几种负载均衡策略？
- Dubbo Provider服务提供者要控制执行并发请求上限，具体怎么做？
- Dubbo启动的时候支持几种配置方式？

# 五.分布式
## Nginx
- 正向代理、反向代理；
- 请解释什么是C10K问题或者知道什么是C10K问题吗？

- Nginx简介，可参考《Nginx简介》

- 正向代理和反向代理.

- Nginx几种常见的负载均衡策略

- Nginx服务器上的Master和Worker进程分别是什么

- 使用“反向代理服务器”的优点是什么?
- Nginx的Master和Worker，Nginx是如何处理请求的；
- 常见的Nginx负载均衡策略；已有两台Nginx服务器了，倘若这时候再增加一台服务器，采用什么负载均衡算法比较好？

## 分布式其他
- 谈谈业务中使用分布式的场景
- session 与 cookie 区别
- Session 分布式方案
- session 分布式处理
- 分布式锁的应用场景、分布式锁的产生原因、基本概念
- 分布是锁的常见解决方案
- 分布式事务的常见解决方案
- 集群与负载均衡的算法与实现
- 什么是C10K问题；
- 高并发情况下怎么办；
- 分布式事务，操作两个表不在一个库，如何保证一致性。
- 如何保证分布式缓存的一致性(分布式缓存一致性hash算法?)？
- 分布式系统中，每台机器如何产生一个唯一的随机值；
- 系统的量级、pv、uv等；
- 什么是Hash一致性算法？分布式缓存的一致性，服务器如何扩容（哈希环）；
- 什么是客户端负载均衡策略、什么是服务器端负载均衡策略；
- 扫描二维码登录的过程解析；
- 如何设计一个生成唯一UUID的算法？
- 实现一个负载均衡的算法，服务器资源分配为70%、20%、10%；
# 六.微服务篇
- 前后端分离是如何做的?
- 微服务哪些框架
- 你怎么理解 RESTful
- 说说如何设计一个良好的 API
- 如何理解 RESTful API 的幂等性
- 如何保证接口的幂等性
- 如何防止表单重复提交（Token令牌环等方式）；
- 分布式理论，什么是CAP理论，什么是Base理论，什么是Paxos理论；
- 说一下你对微服务的理解，与SOA的区别；
- 分布式协议的选举算法；
- 怎么考虑数据一致性问题,
- 说说最终一致性的实现方案
- 领域驱动有了解吗？什么是领域驱动模型？充血模型、贫血模型
- JWT有了解吗，什么是JWT,http://mp.weixin.qq.com/s?__biz=MzI1NDQ3MjQxNA==&mid=2247485183&idx=1&sn=05dac824dbb534710dd99d6c895fbaf5&chksm=e9c5ff4edeb27658173c8b06ad6d1241d3b7822c734ddf6ac064d40e63cb0cb0a0c90804b9c7&scene=21#wechat_redirect
- 你怎么看待微服务,微服务的优缺点，http://mp.weixin.qq.com/s?__biz=MzI1NDQ3MjQxNA==&mid=2247485005&idx=1&sn=78a1d286c6a15a81ea5dcf6634a70b54&chksm=e9c5fffcdeb276ea3c766a6e5954685db0e89bea8ff0f47c9a3ff2c0c02991f791a5160287c4&scene=21#wechat_redirect

- 微服务与 SOA 的区别

- 如何拆分服务、水平分割、垂直分割

- 微服务如何进行数据库管理,（Flyway 数据库脚本管理工具）

- 如何应对微服务的链式调用异常

- 对于快速追踪与定位问题

- 如何保证微服务的安全、认证
- 熟悉maven是吧？我们来聊下Maven的源码原理，Maven冲突的时候，怎么选择依赖包，我们怎么查，我们遇到两个不一样的版本，我们应该如何去选择，为什么？
## 安全问题
- 什么是XSS攻击，XSS攻击的一般表现形式有哪些？如何防止XSS攻击；
- 如何防范常见的Web攻击，有哪些Web攻击
- 如何方式SQL注入

- 服务端通信安全攻防

- HTTPS原理剖析、降级攻击、HTTP与HTTPS的对比

- 安全要素与 STRIDE 威胁
- 授权与认证

- 基于角色的访问控制

- 基于数据的访问控制


## 性能优化
- 性能指标有哪些

- 如何发现性能瓶颈

- 性能调优的常见手段

- 说说你在项目中如何进行性能调优
- 你是否遇到过 CPU 100% ，如何排查与解决
- CPU高？什么情况CPU高？解决什么问题？
- 你是否遇到过 内存 OOM ，如何排查与解决
- Java内存抖动严重，优化的思路

# 七.工程篇
## 需求分析
- 你如何对需求原型进行理解和拆分

- 说说你对功能性需求的理解

- 说说你对非功能性需求的理解

- 你针对产品提出哪些交互和改进意见

- 你如何理解用户痛点

## 设计能力
- 说说你在项目中使用过的 UML 图

- 你如何考虑组件化

- 你如何考虑服务化
- 你如何考虑组件化、服务化、系统拆分
- 秒杀场景如何设计
- 秒杀系统设计，超卖怎么搞;
- 你如何进行领域建模

- 你如何划分领域边界

- 说说你项目中的领域建模

- 说说概要设计
- 有一个url白名单，需要使用正则表达式进行过滤，但是url量级很大，大概亿级，那么如何优化正则表达式？如何优化亿级的url匹配呢？
- 给定a、b两个文件，各存放50亿个url，每个url各占64字节，内存限制是4G，让你找出a、b文件共同的url？
- 海量日志数据，提取出某日访问百度次数最多的那个IP；
- 你们的图片时怎么存储的，对应在数据库中时如何保存图片的信息的？
- 假如成都没有一座消防站，现在问你要建立几座消防站，每个消防站要配多少名消防官兵，多少辆消防车，请你拿出一个方案；
- 基于数组实现一个循环阻塞队列；
- 常见的ipv4地址的展现形式如“168.0.0.1”，请实现ip地址和int类型的相互转换。（使用位移的方式）
- 现网某个服务部署在多台Liunx服务器上，其中一台突然出现CPU 100%的情况，而其他服务器正常，请列举可能导致这种情况发生的原因？如果您遇到这样的情况，应如何定位？内存？CPU？发布？debug？请求量？
- 一个文本文件，大约有一万行，每行一个词，要求统计出其中最频繁出现的前10个词，请给出思想，给出时间复杂度分析。
- 让你设计一个cache如何设计；
- 比如我有个电商平台，做每日订单的异常检测，服务端代码应该写；
https://blog.csdn.net/v_july_v/article/details/6279498
https://blog.csdn.net/v_july_v/article/details/7382693


- 有几台机器存储着几亿淘宝搜索日志，你只有一台2g的电脑，怎么选出搜索热度最高的十个搜索关键词;

- 如何设计算法压缩一段URL;

- 有一个页面能同时展示两个广告，现在有五个广告，设计算法使五个广告展示概率为1:2:3:4:5；

- 有25匹马，五个赛道，用最少比赛次数将25匹马排序；



## 业务工程

- 说说你的开发流程、如何进行自动化部署的

- 你和团队是如何沟通的

- 你如何进行代码评审

- 说说你对技术与业务的理解

- 说说你在项目中经常遇到的 Exception

- 说说你在项目中遇到感觉最难Bug，怎么解决的

- 说说你在项目中遇到印象最深困难，怎么解决的

- 介绍一下工作中的一个你认为最有价值的项目，以及在这个过程中的角色、解决的问题、
- 你觉得你们项目还有哪些不足的地方

- 说说你对敏捷开发的实践

- 说说你对开发运维的实践


## 软实力
- 说说你的亮点

- 说说你最近在看什么书、什么博客、在研究什么新技术、再看那些开源项目的源代码

- 说说你觉得最有意义的技术书籍

- 工作之余做什么事情、平时是如何学习的，怎样提升自己的能力

- 说说个人发展方向方面的思考

- 说说你认为的服务端开发工程师应该具备哪些能力

- 说说你认为的架构师是什么样的，架构师主要做什么

- 说说你所理解的技术专家
- 如何看待加班的问题
- 看过哪些源代码？然后会根据你说的源码问一些细节的问题？（这里主要考察面试者是否对技术有钻研的精神，还是只停留在表面，还是背了几道面经，这个对于很多有强迫症的面试官，如果你连源码都没看过，基本上是会pass掉的，比如我也是这样的！）
- 项目中遇到了哪些比较有挑战性的问题，是如何解决的；（这个很有争议，一方面是你连一个复杂的问题都解决不了，要你过来干什么，还有就是，我的能力牛逼啊，但是公司没有业务场景让我展示啊！这个就看你遇到的面试官了，祝你好运！）


## 逻辑思维题

有两根粗细均匀的香（烧香拜佛的香），每一根烧完都花一个小时，怎么样能够得到15min？

假定你有8个撞球，其中有1个球比其他的球稍重,如果只能利用天平来断定哪一个球重,要找到较重的球,要称几次?（2次）；

实验室里有1000个一模一样的瓶子，但是其中的一瓶有毒。可以用实验室的小白鼠来测试哪一瓶是毒药。如果小白鼠喝掉毒药的话，会在一个星期的时候死去，其他瓶子里的药水没有任何副作用。请问最少用多少只小白鼠可以在一个星期以内查出哪瓶是毒药；（答案是10只）

假设有一个池塘，里面有无穷多的水。现有2个空水壶，容积分别为5升和6升。问题是如何只用这2个水壶从池塘里取得3升的水；
