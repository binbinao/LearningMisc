# 讯息传递界面 - 维基百科，自由的百科全书

> 讯息传递界面（英语：Message Passing Interface，缩写MPI）是一个平行计算的应用程序接口（API），常在超级电脑、电脑丛集等非共享内存环境程序设计。

**讯息传递界面**（英语：Message Passing Interface，缩写MPI）是一个[平行计算](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/wiki/%E5%B9%B3%E8%A1%8C%E8%A8%88%E7%AE%97 "平行计算")的[应用程序接口](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/wiki/%E5%BA%94%E7%94%A8%E7%A8%8B%E5%BA%8F%E6%8E%A5%E5%8F%A3 "应用程序接口")（API），常在[超级电脑](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/wiki/%E8%B6%85%E7%B4%9A%E9%9B%BB%E8%85%A6 "超级电脑")、[电脑丛集](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/wiki/%E9%9B%BB%E8%85%A6%E5%8F%A2%E9%9B%86 "电脑丛集")等非共享内存环境程序设计。

历史\[[编辑](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/w/index.php?title=%E8%A8%8A%E6%81%AF%E5%82%B3%E9%81%9E%E4%BB%8B%E9%9D%A2&action=edit&section=1 "编辑章节：历史")\]
------------------------------------------------------------------------------------------------------------------------------------------------------------------------

建立信息传递接口的努力始于1991夏天一小群研究员在奥地利的一个度假山庄开始的讨论。那次讨论之后，于1992年4月29-30号于[维吉尼亚州](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/wiki/%E7%B6%AD%E5%90%89%E5%B0%BC%E4%BA%9E%E5%B7%9E "维吉尼亚州")[威廉斯堡](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/wiki/%E5%A8%81%E5%BB%89%E6%96%AF%E5%A0%A1_(%E5%BC%97%E5%90%89%E5%B0%BC%E4%BA%9A%E5%B7%9E))召开了一次关于分布式内存环境下的信息传递标准设置研讨会。在这次研讨会上讨论了对标准信息传递接口至关重要的一些基本特征，并建立了一个继续标准化此过程的工作组。[杰克·东加拉](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/w/index.php?title=%E5%82%91%E5%85%8B%C2%B7%E6%9D%B1%E5%8A%A0%E6%8B%89&action=edit&redlink=1), Rolf Hempel, [托尼·黑](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/w/index.php?title=%E6%89%98%E5%B0%BC%C2%B7%E9%BB%91&action=edit&redlink=1), and David W. Walker于1992年11月提出了一些初始草稿提议，后被称为MPI1。在1992年11月，一个MPI的工作组会议在[明尼阿波利斯](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/wiki/%E6%98%8E%E5%B0%BC%E4%BA%9E%E6%B3%A2%E5%88%A9%E6%96%AF "明尼阿波利斯")召开，他们决定了为此标准化过程建立一个更正式的标注。MPI工作组在1993年的头九个月每6个星期见面一次。MPI标准草稿在93年11月的超级计算机会议上提出。在经过一阵子的公众论议后，MPI修改了一些部分，并于1994年6月发布了MPI1.0版本。这些会议和邮件共同建立了MPI论坛，此论坛后来开放至所有高性能计算的成员。

MPI包含了80个人40个组织的共同努力，他们主要都在美国和欧洲。主要的时下电脑供应商也涉入MPI，还有大学的研究员，政府公务员和产业界。

MPI标准定义了核心函式库的语法和语义，这个函式库可以被Fortran和C调用构成可移植的信息传递程序。MPI提供了适应各种并行硬件商的基础集，他们都被有效的实现。这导致了是硬件商可以基于这一系列底层标准来建立高层次的惯例，从而为分布式内存交互系统提供他们的并行机。MPI提供了一个简单易用的可移植接口，足够强大到程序员可以用它在高级机器上进行进行高性能信息传递操作。

在建立“真正”的MPI标准过程中，研究员们整合了几个系统最有用的特征到MPI中，而不是用一个系统来适应标准。其特征为IBM，Intel, nCUBE, PVM, Express, P4 and PARMACS等系统所用。

信息传递模式非常之吸引人，皆因它的广泛可移植性，以及能被用于分布式内存/共享内存的多核处理器，工作站网络，和这些架构的组合。信息传递模式可用于多重设定，独立于网络速度和内存架构。

概述\[[编辑](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/w/index.php?title=%E8%A8%8A%E6%81%AF%E5%82%B3%E9%81%9E%E4%BB%8B%E9%9D%A2&action=edit&section=2 "编辑章节：概述")\]
------------------------------------------------------------------------------------------------------------------------------------------------------------------------

MPI是一个跨语言的通讯协议，用于编写并行计算机。支持点对点和广播。MPI是一个信息传递应用程序接口，包括协议和和语义说明，他们指明其如何在各种实现中发挥其特性。MPI的目标是高性能，大规模性，和可移植性。MPI在今天仍为高性能计算的主要模型。

主要的MPI-1模型不包括共享内存概念，MPI-2只有有限的分布共享内存概念。 但是MPI程序经常在共享内存的机器上运行。在MPI模型周边设计程序比在NUMA架构下设计要好因为MPI鼓励内存本地化。

尽管MPI属于OSI参考模型的第五层或者更高，他的实现可能通过传输层的sockets和Transmission Control Protocol (TCP)覆盖大部分的层。大部分的MPI实现由一些指定惯例集（API）组成，可由C,C++,Fortran,或者有此类库的语言比如C#, Java or Python直接调用。MPI优于老式信息传递库是因为他的可移植性和速度。

特色\[[编辑](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/w/index.php?title=%E8%A8%8A%E6%81%AF%E5%82%B3%E9%81%9E%E4%BB%8B%E9%9D%A2&action=edit&section=3 "编辑章节：特色")\]
------------------------------------------------------------------------------------------------------------------------------------------------------------------------

大多数讯息传递界面的实现为[函式库](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/wiki/%E5%87%BD%E5%BC%8F%E5%BA%AB "函式库")，亦不需要[编译器](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/wiki/%E7%B7%A8%E8%AD%AF%E5%99%A8 "编译器")支持。

例子\[[编辑](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/w/index.php?title=%E8%A8%8A%E6%81%AF%E5%82%B3%E9%81%9E%E4%BB%8B%E9%9D%A2&action=edit&section=4 "编辑章节：例子")\]
------------------------------------------------------------------------------------------------------------------------------------------------------------------------

由多[行程](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/wiki/%E8%A1%8C%E7%A8%8B "行程")来执行Hello World：

#include <stdio.h>
#include <mpi.h>

int main(int argc, char \*argv\[\])
{
 char processor\_name\[MPI\_MAX\_PROCESSOR\_NAME\];
 int len;

 MPI\_Init(&argc, &argv);

 MPI\_Get\_processor\_name(processor\_name, &len);
 printf("Hello World from %s\\n", processor\_name);

 MPI\_Finalize();
 
 return 0;
}

执行结果：

% mpicc hello.c

% cat nodefile
node1
node2

% mpirun -np 1 -hostfile nodefile a.out（由1節點來執行）
Hello World from node1

% mpirun -np 2 -hostfile nodefile a.out（由2節點來執行）
Hello World from node1
Hello World from node2

实现\[[编辑](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/w/index.php?title=%E8%A8%8A%E6%81%AF%E5%82%B3%E9%81%9E%E4%BB%8B%E9%9D%A2&action=edit&section=5 "编辑章节：实现")\]
------------------------------------------------------------------------------------------------------------------------------------------------------------------------

*   Open MPI－ 是[自由软件](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/wiki/%E8%87%AA%E7%94%B1%E8%BB%9F%E4%BB%B6 "自由软件")和[开放源码](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/wiki/%E9%96%8B%E6%94%BE%E6%BA%90%E7%A2%BC "开放源码")实现。[\[1\]](#cite_note-1) [走鹃](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/wiki/%E8%B5%B0%E9%B5%91_(%E8%B6%85%E7%B4%9A%E9%9B%BB%E8%85%A6) "走鹃 (超级电脑)")（2008年6月-2009年11月[TOP500](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/wiki/TOP500 "TOP500")第一快的超级电脑）[\[2\]](#cite_note-2)及[京](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/wiki/%E4%BA%AC_(%E8%B6%85%E7%BA%A7%E7%94%B5%E8%84%91) "京 (超级电脑)")（2011年6月至今第一快的超级电脑）也使用Open MPI。[\[3\]](#cite_note-3) [\[4\]](#cite_note-4)
*   Intel MPI－[Intel](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/wiki/Intel "Intel")基于开放源码的MPICH2与MVAPICH2研发成的MPI。[\[5\]](#cite_note-5)
*   Platform MPI－Platform公司收购Scali MPI及HP MPI，研发成Platform MPI。[\[6\]](#cite_note-6)

参考文献\[[编辑](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/w/index.php?title=%E8%A8%8A%E6%81%AF%E5%82%B3%E9%81%9E%E4%BB%8B%E9%9D%A2&action=edit&section=6 "编辑章节：参考文献")\]
----------------------------------------------------------------------------------------------------------------------------------------------------------------------------

外部链接\[[编辑](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/w/index.php?title=%E8%A8%8A%E6%81%AF%E5%82%B3%E9%81%9E%E4%BB%8B%E9%9D%A2&action=edit&section=7 "编辑章节：外部链接")\]
----------------------------------------------------------------------------------------------------------------------------------------------------------------------------

*   （英文）[讯息传递界面](http://www.mpi-forum.org/) （[页面存档备份](chrome-extension://web.archive.org/web/20210505021518/http://www.mpi-forum.org/)，存于[互联网档案馆](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/wiki/%E4%BA%92%E8%81%94%E7%BD%91%E6%A1%A3%E6%A1%88%E9%A6%86 "互联网档案馆")）
*   （英文）[Open MPI内部结构](https://web.archive.org/web/20120520011000/http://www.aosabook.org/en/openmpi.html)（The Architecture of Open Source Applications, Volume II - [ISBN 9781105571817](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/wiki/Special:%E7%BD%91%E7%BB%9C%E4%B9%A6%E6%BA%90/9781105571817)）

| \[[隐藏](#)\]
*   [查](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/wiki/Template:%E5%B9%B6%E8%A1%8C%E8%AE%A1%E7%AE%97 "Template:并行计算")
*   [论](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/w/index.php?title=Template_talk:%E5%B9%B6%E8%A1%8C%E8%AE%A1%E7%AE%97&action=edit&redlink=1 "Template talk:并行计算（页面不存在）")
*   [编](https://zh.wikipedia.org/w/index.php?title=Template:%E5%B9%B6%E8%A1%8C%E8%AE%A1%E7%AE%97&action=edit)

[并行计算](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/wiki/%E5%B9%B6%E8%A1%8C%E8%AE%A1%E7%AE%97 "并行计算")



 |
| --- |

| 概论 | 

*   [分布式计算](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/wiki/%E5%88%86%E5%B8%83%E5%BC%8F%E8%AE%A1%E7%AE%97 "分布式计算")
*   [并行计算](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/wiki/%E5%B9%B6%E8%A1%8C%E8%AE%A1%E7%AE%97 "并行计算")
*   [大规模并行处理机](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/wiki/%E5%A4%A7%E8%A7%84%E6%A8%A1%E5%B9%B6%E8%A1%8C%E5%A4%84%E7%90%86%E6%9C%BA "大规模并行处理机")
*   [云端运算](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/wiki/%E9%9B%B2%E7%AB%AF%E9%81%8B%E7%AE%97 "云端运算")
*   [高性能计算](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/wiki/%E8%B6%85%E7%BA%A7%E8%AE%A1%E7%AE%97%E6%9C%BA "超级计算机")
*   [多元处理](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/wiki/%E5%A4%9A%E5%85%83%E8%99%95%E7%90%86 "多元处理")
*   [大规模多核心处理器](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/w/index.php?title=%E5%A4%A7%E8%A6%8F%E6%A8%A1%E5%A4%9A%E6%A0%B8%E5%BF%83%E8%99%95%E7%90%86%E5%99%A8&action=edit&redlink=1)
*   [GPGPU](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/wiki/%E5%9B%BE%E5%BD%A2%E5%A4%84%E7%90%86%E5%99%A8%E9%80%9A%E7%94%A8%E8%AE%A1%E7%AE%97 "图形处理器通用计算")
*   [计算机网络](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/wiki/%E8%AE%A1%E7%AE%97%E6%9C%BA%E7%BD%91%E7%BB%9C "计算机网络")
*   [Systolic array](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/w/index.php?title=Systolic_array&action=edit&redlink=1)



 |

| 层级 | 

*   [位元](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/wiki/%E4%BD%8D%E5%85%83%E5%B1%A4%E7%B4%9A%E5%B9%B3%E8%A1%8C "位元层级平行")
*   [指令](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/wiki/%E6%8C%87%E4%BB%A4%E5%B1%A4%E7%B4%9A%E5%B9%B3%E8%A1%8C "指令层级平行")
*   [线程](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/wiki/%E4%BB%BB%E5%8A%A1%E5%B9%B6%E8%A1%8C "任务并行")
*   [任务](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/wiki/%E4%BB%BB%E5%8A%A1%E5%B9%B6%E8%A1%8C "任务并行")
*   [数据](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/wiki/%E8%B3%87%E6%96%99%E5%B9%B3%E8%A1%8C "资料平行")
*   [内存](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/wiki/%E8%A8%98%E6%86%B6%E9%AB%94%E5%B1%A4%E7%B4%9A%E5%B9%B3%E8%A1%8C "内存层级平行")
*   [循环](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/w/index.php?title=Loop-level_parallelism&action=edit&redlink=1)
*   [流水线](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/wiki/%E6%B5%81%E6%B0%B4%E7%BA%BF_(%E8%AE%A1%E7%AE%97%E6%9C%BA) "流水线 (计算机)")



 |

| [多线程](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/wiki/%E5%A4%9A%E7%BA%BF%E7%A8%8B "多线程") | 

*   [时间](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/w/index.php?title=Temporal_multithreading&action=edit&redlink=1)
*   [同时多线程](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/wiki/%E5%90%8C%E6%97%B6%E5%A4%9A%E7%BA%BF%E7%A8%8B "同时多线程")（SMT）
*   [投机](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/w/index.php?title=Speculative_multithreading&action=edit&redlink=1)（SpMT）
*   [抢占式](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/wiki/%E6%8A%A2%E5%8D%A0%E5%BC%8F%E5%A4%9A%E4%BB%BB%E5%8A%A1%E5%A4%84%E7%90%86 "抢占式多任务处理")
*   [协作](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/wiki/%E5%A4%9A%E4%BB%BB%E5%8A%A1%E5%A4%84%E7%90%86 "多任务处理")
*   [集群多线程](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/wiki/AMD_Bulldozer "AMD Bulldozer")（CMT）
*   [硬件侦测](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/wiki/%E7%A1%AC%E4%BB%B6%E4%BE%A6%E6%B5%8B "硬件侦测")



 |

| 理论 | 

*   [PRAM模型](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/wiki/PRAM%E6%A8%A1%E5%9E%8B "PRAM模型")
*   [并行算法分析](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/w/index.php?title=%E5%B9%B6%E8%A1%8C%E7%AE%97%E6%B3%95%E5%88%86%E6%9E%90&action=edit&redlink=1)
*   [阿姆达尔定律](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/wiki/%E9%98%BF%E5%A7%86%E8%BE%BE%E5%B0%94%E5%AE%9A%E5%BE%8B "阿姆达尔定律")
*   [Gustafson's law](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/w/index.php?title=Gustafson%27s_law&action=edit&redlink=1)
*   [Cost efficiency](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/w/index.php?title=Cost_efficiency&action=edit&redlink=1)
*   [Karp–Flatt metric](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/w/index.php?title=Karp%E2%80%93Flatt_metric&action=edit&redlink=1)
*   [减速](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/w/index.php?title=Parallel_slowdown&action=edit&redlink=1)
*   [加速比](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/wiki/%E5%8A%A0%E9%80%9F%E6%AF%94 "加速比")



 |

| 元素 | 

*   [行程](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/wiki/%E8%A1%8C%E7%A8%8B "行程")
*   [线程](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/wiki/%E7%BA%BF%E7%A8%8B "线程")
*   [纤程](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/wiki/%E7%BA%96%E7%A8%8B "纤程")
*   [指令窗口](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/w/index.php?title=%E6%8C%87%E4%BB%A4%E7%AA%97%E5%8F%A3&action=edit&redlink=1)



 |

| 协调 | 

*   [多元处理](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/wiki/%E5%A4%9A%E5%85%83%E8%99%95%E7%90%86 "多元处理")
*   [内存一致性](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/w/index.php?title=%E5%86%85%E5%AD%98%E4%B8%80%E8%87%B4%E6%80%A7&action=edit&redlink=1)
*   [快取一致性](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/wiki/%E5%BF%AB%E5%8F%96%E4%B8%80%E8%87%B4%E6%80%A7 "快取一致性")
*   [高速缓存失效](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/w/index.php?title=%E9%AB%98%E9%80%9F%E7%BC%93%E5%AD%98%E5%A4%B1%E6%95%88&action=edit&redlink=1)
*   [屏障](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/wiki/%E5%90%8C%E6%AD%A5%E5%B1%8F%E9%9A%9C "同步屏障")
*   [同步](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/wiki/%E5%90%8C%E6%AD%A5_(%E8%AE%A1%E7%AE%97%E6%9C%BA%E7%A7%91%E5%AD%A6) "同步 (计算机科学)")
*   [应用程序检查点](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/w/index.php?title=%E5%BA%94%E7%94%A8%E7%A8%8B%E5%BA%8F%E6%A3%80%E6%9F%A5%E7%82%B9&action=edit&redlink=1)



 |

| [编程](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/wiki/%E7%A8%8B%E5%BA%8F%E8%AE%BE%E8%AE%A1 "程序设计") | 

*   [串流处理](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/wiki/%E4%B8%B2%E6%B5%81%E8%99%95%E7%90%86 "串流处理")
*   [数据流处理](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/w/index.php?title=%E6%95%B0%E6%8D%AE%E6%B5%81%E5%A4%84%E7%90%86&action=edit&redlink=1)
*   [模型](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/wiki/%E5%B9%B6%E8%A1%8C%E7%BC%96%E7%A8%8B%E6%A8%A1%E5%9E%8B "并行编程模型")
    *   [隐式并行](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/w/index.php?title=%E9%9A%90%E5%BC%8F%E5%B9%B6%E8%A1%8C&action=edit&redlink=1)
    *   [显式并行](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/w/index.php?title=%E6%98%BE%E5%BC%8F%E5%B9%B6%E8%A1%8C&action=edit&redlink=1)
    *   [并发性](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/wiki/%E5%B9%B6%E5%8F%91%E6%80%A7 "并发性")
*   [非阻塞算法](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/w/index.php?title=%E9%9D%9E%E9%98%BB%E5%A1%9E%E7%AE%97%E6%B3%95&action=edit&redlink=1)



 |

| [硬件](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/wiki/%E7%A1%AC%E4%BB%B6 "硬件") | 

*   [费林分类法](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/wiki/%E8%B2%BB%E6%9E%97%E5%88%86%E9%A1%9E%E6%B3%95 "费林分类法")
    *   [单指令流单数据流](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/wiki/%E5%96%AE%E6%8C%87%E4%BB%A4%E6%B5%81%E5%96%AE%E6%95%B8%E6%93%9A%E6%B5%81 "单指令流单数据流")
    *   [单指令流多数据流](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/wiki/%E5%8D%95%E6%8C%87%E4%BB%A4%E6%B5%81%E5%A4%9A%E6%95%B0%E6%8D%AE%E6%B5%81 "单指令流多数据流")
    *   [单指令多线程](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/w/index.php?title=%E5%8D%95%E6%8C%87%E4%BB%A4%E5%A4%9A%E7%BA%BF%E7%A8%8B&action=edit&redlink=1)（SIMT）
    *   [多指令流单数据流](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/wiki/%E5%A4%9A%E6%8C%87%E4%BB%A4%E6%B5%81%E5%96%AE%E6%95%B8%E6%93%9A%E6%B5%81 "多指令流单数据流")
    *   [多指令流多数据流](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/wiki/%E5%A4%9A%E6%8C%87%E4%BB%A4%E6%B5%81%E5%A4%9A%E6%95%B0%E6%8D%AE%E6%B5%81 "多指令流多数据流")
*   [数据流架构](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/w/index.php?title=%E6%95%B0%E6%8D%AE%E6%B5%81%E6%9E%B6%E6%9E%84&action=edit&redlink=1)
*   [指令管线化](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/wiki/%E6%8C%87%E4%BB%A4%E7%AE%A1%E7%B7%9A%E5%8C%96 "指令管线化")
*   [超标量](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/wiki/%E8%B6%85%E7%B4%94%E9%87%8F "超标量")
*   [并行向量处理机](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/wiki/%E5%B9%B6%E8%A1%8C%E5%90%91%E9%87%8F%E5%A4%84%E7%90%86%E6%9C%BA "并行向量处理机")
*   [多处理器](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/wiki/%E5%A4%9A%E5%85%83%E8%99%95%E7%90%86 "多元处理")
    *   [对称](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/wiki/%E5%AF%B9%E7%A7%B0%E5%A4%9A%E5%A4%84%E7%90%86 "对称多处理")
    *   [非对称](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/wiki/%E9%9D%9E%E5%B0%8D%E7%A8%B1%E5%A4%9A%E8%99%95%E7%90%86 "非对称多处理")
*   [内存](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/w/index.php?title=%E5%8D%8A%E5%AF%BC%E4%BD%93%E5%AD%98%E5%82%A8%E5%99%A8&action=edit&redlink=1)
    *   [共享](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/wiki/%E5%85%B1%E4%BA%AB%E5%86%85%E5%AD%98 "共享内存")
    *   [分布式内存](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/w/index.php?title=%E5%88%86%E5%B8%83%E5%BC%8F%E5%86%85%E5%AD%98&action=edit&redlink=1)
    *   [分布式共享](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/wiki/%E5%88%86%E5%B8%83%E5%BC%8F%E5%85%B1%E4%BA%AB%E5%AD%98%E5%82%A8%E5%A4%84%E7%90%86%E6%9C%BA "分布式共享存储处理机")
    *   [UMA](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/wiki/%E5%9D%87%E5%8C%80%E8%AE%BF%E5%AD%98%E6%A8%A1%E5%9E%8B "均匀访存模型")
    *   [NUMA](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/wiki/%E9%9D%9E%E5%9D%87%E5%8C%80%E8%AE%BF%E5%AD%98%E6%A8%A1%E5%9E%8B "非均匀访存模型")
    *   [COMA](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/w/index.php?title=%E4%BB%85%E7%BC%93%E5%AD%98%E5%86%85%E5%AD%98%E6%9E%B6%E6%9E%84&action=edit&redlink=1)
*   [大规模并行处理机](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/wiki/%E5%A4%A7%E8%A7%84%E6%A8%A1%E5%B9%B6%E8%A1%8C%E5%A4%84%E7%90%86%E6%9C%BA "大规模并行处理机")
*   [计算机集群](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/wiki/%E8%AE%A1%E7%AE%97%E6%9C%BA%E9%9B%86%E7%BE%A4 "计算机集群")
*   [网格计算](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/wiki/%E7%BD%91%E6%A0%BC%E8%AE%A1%E7%AE%97 "网格计算")



 |

| [API](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/wiki/%E5%BA%94%E7%94%A8%E7%A8%8B%E5%BA%8F%E6%8E%A5%E5%8F%A3 "应用程序接口") | 

*   [Ateji PX](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/w/index.php?title=Ateji_PX&action=edit&redlink=1)
*   [Boost.Thread](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/wiki/Boost_C%2B%2B_Libraries "Boost C++ Libraries")
*   [Charm++](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/w/index.php?title=Charm%2B%2B&action=edit&redlink=1)
*   [Cilk](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/wiki/Cilk "Cilk")
*   [Coarray Fortran](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/w/index.php?title=Coarray_Fortran&action=edit&redlink=1)
*   [CUDA](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/wiki/CUDA "CUDA")
*   [Dryad](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/w/index.php?title=Dryad_(programming)&action=edit&redlink=1)
*   [C++ AMP](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/wiki/C%2B%2B_AMP "C++ AMP")
*   [Global Arrays](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/w/index.php?title=Global_Arrays&action=edit&redlink=1)
*   MPI
*   [OpenMP](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/wiki/OpenMP "OpenMP")
*   [OpenCL](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/wiki/OpenCL "OpenCL")
*   [HMPP开放标准](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/wiki/HMPP%E5%BC%80%E6%94%BE%E6%A0%87%E5%87%86 "HMPP开放标准")
*   [OpenACC](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/wiki/OpenACC "OpenACC")
*   [TPL](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/w/index.php?title=%E4%BB%BB%E5%8A%A1%E5%B9%B6%E8%A1%8C%E5%BA%93&action=edit&redlink=1)
*   [PLINQ](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/w/index.php?title=Parallel_Extensions&action=edit&redlink=1)
*   [并行虚拟机](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/w/index.php?title=%E5%B9%B6%E8%A1%8C%E8%99%9A%E6%8B%9F%E6%9C%BA&action=edit&redlink=1)（PVM）
*   [POSIX线程](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/wiki/POSIX%E7%BA%BF%E7%A8%8B "POSIX线程")
*   [RaftLib](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/w/index.php?title=RaftLib&action=edit&redlink=1)
*   [UPC](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/wiki/Unified_Parallel_C "Unified Parallel C")
*   [TBB](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/w/index.php?title=Threading_Building_Blocks&action=edit&redlink=1)



 |

| 问题 | 

*   [软件闭锁](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/w/index.php?title=%E8%BD%AF%E4%BB%B6%E9%97%AD%E9%94%81&action=edit&redlink=1)
*   [可扩展性](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/wiki/%E5%8F%AF%E6%89%A9%E5%B1%95%E6%80%A7 "可扩展性")
*   [竞争危害](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/wiki/%E7%AB%B6%E7%88%AD%E5%8D%B1%E5%AE%B3 "竞争危害")
*   [死锁](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/wiki/%E6%AD%BB%E9%94%81 "死锁")
*   [活锁](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/wiki/%E6%AD%BB%E9%94%81 "死锁")
*   [饥饿](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/w/index.php?title=%E9%A5%A5%E9%A5%BF_(%E8%AE%A1%E7%AE%97%E6%9C%BA%E7%A7%91%E5%AD%A6)&action=edit&redlink=1)
*   [确定性算法](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/wiki/%E7%A1%AE%E5%AE%9A%E6%80%A7%E7%AE%97%E6%B3%95 "确定性算法")
*   [并行变慢](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/w/index.php?title=%E5%B9%B6%E8%A1%8C%E5%8F%98%E6%85%A2&action=edit&redlink=1)



 |

| 

*   ![分类](chrome-extension://upload.wikimedia.org/wikipedia/commons/thumb/9/96/Symbol_category_class.svg/16px-Symbol_category_class.svg.png "分类") [分类：并行计算](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/wiki/Category:%E5%B9%B6%E8%A1%8C%E8%AE%A1%E7%AE%97 "Category:并行计算")
*   ![](chrome-extension://upload.wikimedia.org/wikipedia/commons/thumb/4/4a/Commons-logo.svg/12px-Commons-logo.svg.png) [维基共享资源](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/wiki/%E7%B6%AD%E5%9F%BA%E5%85%B1%E4%BA%AB%E8%B3%87%E6%BA%90 "维基共享资源")上有关[讯息传递界面](https://commons.wikimedia.org/wiki/Category:%E5%B9%B6%E8%A1%8C%E8%AE%A1%E7%AE%97?uselang=zh-cn)的多媒体资源



 |


[Source](https://zh.wikipedia.org/wiki/%E8%A8%8A%E6%81%AF%E5%82%B3%E9%81%9E%E4%BB%8B%E9%9D%A2)