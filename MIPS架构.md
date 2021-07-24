# MIPS架构 - 维基百科，自由的百科全书
<table><caption><b>MIPS</b></caption><tbody><tr><th scope="row">推出年份</th><td>1981年<span>，​40年前</span></td></tr><tr><th scope="row">设计公司</th><td><a href="chrome-extension://cjedbglnccaioiolemnfhjncicchinao/wiki/MIPS%E7%A7%91%E6%8A%80%E5%85%AC%E5%8F%B8" title="MIPS科技公司">MIPS科技公司</a>→<a href="chrome-extension://cjedbglnccaioiolemnfhjncicchinao/wiki/Imagination_Technologies" title="Imagination Technologies">Imagination Technologies</a></td></tr><tr><th scope="row">是否开放架构？</th><td>否</td></tr><tr><th scope="row">体系结构类型</th><td>寄存器-寄存器，load-store</td></tr><tr><th scope="row">字长/寄存器资料宽度</th><td><a href="chrome-extension://cjedbglnccaioiolemnfhjncicchinao/wiki/32%E4%BD%8D%E5%85%83" title="32位">32位</a>、<a href="chrome-extension://cjedbglnccaioiolemnfhjncicchinao/wiki/64%E4%BD%8D%E5%85%83" title="64位">64位</a></td></tr><tr><th scope="row"><a href="chrome-extension://cjedbglnccaioiolemnfhjncicchinao/wiki/%E5%AD%97%E8%8A%82%E5%BA%8F" title="字节序">字节序</a></th><td>可配置大小端序</td></tr><tr><th scope="row">指令编码长度</th><td>固定长度</td></tr><tr><th scope="row">指令集架构设计策略</th><td><a href="chrome-extension://cjedbglnccaioiolemnfhjncicchinao/wiki/%E7%B2%BE%E7%AE%80%E6%8C%87%E4%BB%A4%E9%9B%86" title="精简指令集">精简指令集</a>（RISC）</td></tr><tr><th scope="row">扩展指令集</th><td><a href="chrome-extension://cjedbglnccaioiolemnfhjncicchinao/wiki/MSA" title="MSA">MSA</a>、<a href="chrome-extension://cjedbglnccaioiolemnfhjncicchinao/wiki/%E6%95%B8%E4%BD%8D%E8%A8%8A%E8%99%9F%E8%99%95%E7%90%86%E5%99%A8" title="数字信号处理器">DSP</a>、<a href="chrome-extension://cjedbglnccaioiolemnfhjncicchinao/w/index.php?title=VZ&amp;action=edit&amp;redlink=1" title="VZ（页面不存在）">VZ</a>、<a href="chrome-extension://cjedbglnccaioiolemnfhjncicchinao/w/index.php?title=MDMX&amp;action=edit&amp;redlink=1" title="MDMX（页面不存在）">MDMX</a>、<a href="chrome-extension://cjedbglnccaioiolemnfhjncicchinao/w/index.php?title=MIPS-3D&amp;action=edit&amp;redlink=1" title="MIPS-3D（页面不存在）">MIPS-3D</a></td></tr><tr><th scope="row"><a href="chrome-extension://cjedbglnccaioiolemnfhjncicchinao/wiki/%E5%88%86%E6%94%AF%E9%A0%90%E6%B8%AC%E5%99%A8" title="分支预测器">分支预测结构</a></th><td>比较和分支</td></tr><tr><th scope="row">通用寄存器</th><td>31个+1个固定为0的寄存器R0</td></tr><tr><th scope="row">浮点寄存器</th><td>32个（有一对32位寄存器组成的双精度浮点数寄存器）</td></tr></tbody></table>

[![](chrome-extension://upload.wikimedia.org/wikipedia/commons/thumb/e/ea/MIPS_Architecture_%28Pipelined%29.svg/300px-MIPS_Architecture_%28Pipelined%29.svg.png)](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/wiki/File:MIPS_Architecture_(Pipelined).svg)

流水线式 MIPS，展示了五个阶段（指令获取、指令解码、执行、内存访问和写回）。

**MIPS**（**M**icroprocessor without **I**nterlocked **P**ipeline **S**tages），是一种采取[精简指令集](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/wiki/%E7%B2%BE%E7%AE%80%E6%8C%87%E4%BB%A4%E9%9B%86 "精简指令集")（RISC）的[指令集架构](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/wiki/%E6%8C%87%E4%BB%A4%E9%9B%86%E6%9E%B6%E6%A7%8B "指令集架构")（ISA），1981年出现，由 [MIPS 公司](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/wiki/MIPS%E7%A7%91%E6%8A%80%E5%85%AC%E5%8F%B8)开发并授权，广泛被使用在许多电子产品、网络设备、个人娱乐设备与商业设备上。最早的MIPS架构是 32 比特，最新的版本已经变成 64 比特。商业市场主要竞争对手为[ARM](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/wiki/ARM "ARM")与[RISC-V](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/wiki/RISC-V "RISC-V")。

MIPS 架构有多个版本。其中包括 MIPS I、II、III、IV，以及 MIPS V，它们各自各自是 MIPS32/64（分别是 [32 位](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/wiki/32%E4%BD%8D%E5%85%83 "32位")、[64 位](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/wiki/64%E4%BD%8D%E5%85%83 "64位")的实现）发布的五个版本。早期的 MIPS 架构只有 32 位的版本，而其 64 位的版本随后才被开发。截至 2017 年 4 月，MIPS32/64 的当前版本是 MIPS32/64 Release 6[\[1\]](#cite_note-1)[\[2\]](#cite_note-2) 。MIPS32/64 与 MIPS I–V 的主要区别在于它除了用户态架构外，还定义了特权内核模式系统控制协处理器。

MIPS 架构有几个可选的拓展。比如 MIPS-3D，它是一个专用于常见 3D 计算任务的[浮点](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/wiki/%E6%B5%AE%E7%82%B9 "浮点") [SIMD](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/wiki/%E5%8D%95%E6%8C%87%E4%BB%A4%E6%B5%81%E5%A4%9A%E6%95%B0%E6%8D%AE%E6%B5%81 "单指令流多数据流") 指令集的简单集合[\[3\]](#cite_note-3)；MDMX（MaDMaX）是一个应用更加广泛的整数 SIMD 指令集，它使用了 64 位浮点数寄存器；MIPS16e 则为提供了指令流压缩的功能，这可以减小程序的体积[\[4\]](#cite_note-4)；MIPS MT 则提供了[多线程](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/wiki/%E5%A4%9A%E7%BA%BF%E7%A8%8B "多线程")的能力。[\[5\]](#cite_note-5)

在一些大学和技术学校中[计算机架构](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/wiki/%E8%AE%A1%E7%AE%97%E6%9C%BA%E6%9E%B6%E6%9E%84 "计算机架构")的课程上，学生们通常会学习 MIPS 架构。这个架构极大地影响了后来的精简指令集架构（如 [DEC Alpha](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/wiki/DEC_Alpha "DEC Alpha")）。

发展历史\[[编辑](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/w/index.php?title=MIPS%E6%9E%B6%E6%A7%8B&action=edit&section=1 "编辑章节：发展历史")\]
--------------------------------------------------------------------------------------------------------------------------------------------

*   在1981年，[斯坦福大学](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/wiki/%E6%96%AF%E5%9D%A6%E7%A6%8F%E5%A4%A7%E5%AD%A6 "斯坦福大学")教授[约翰·轩尼诗](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/wiki/%E7%B4%84%E7%BF%B0%C2%B7%E8%BB%92%E5%B0%BC%E8%A9%A9 "约翰·轩尼诗")领导他的团队，实现出第一个MIPS架构的[处理器](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/wiki/%E8%99%95%E7%90%86%E5%99%A8 "处理器")。他们原始的概令是透过[指令流水线](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/wiki/%E6%8C%87%E4%BB%A4%E7%AE%A1%E7%B7%9A%E5%8C%96 "指令流水线")来增加CPU运算的速度。
*   1984年，[约翰·轩尼诗](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/wiki/%E7%B4%84%E7%BF%B0%C2%B7%E8%BB%92%E5%B0%BC%E8%A9%A9 "约翰·轩尼诗")教授离开斯坦福大学，创立[MIPS科技公司](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/wiki/MIPS%E7%A7%91%E6%8A%80%E5%85%AC%E5%8F%B8 "MIPS科技公司")。于1985年，设计出R2000芯片，1988年，将其改进为R3000芯片。
*   2018年6月—美国硅谷新创AI芯片公司[Wave Computing](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/w/index.php?title=Wave_Computing&action=edit&redlink=1 "Wave Computing（页面不存在）")宣布完成收购MIPS公司股权，MIPS公司维持独立运作，并预计开源MIPS架构。[\[6\]](#cite_note-6)。
*   2021年3月，Wave Computing宣布停止开发MIPS架构，并且加入RISC-V基金会，未来处理器将基于RISC-V架构设计[\[7\]](#cite_note-7)[\[8\]](#cite_note-8)。

MIPS I\[[编辑](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/w/index.php?title=MIPS%E6%9E%B6%E6%A7%8B&action=edit&section=2 "编辑章节：MIPS I")\]
------------------------------------------------------------------------------------------------------------------------------------------------

### 特性\[[编辑](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/w/index.php?title=MIPS%E6%9E%B6%E6%A7%8B&action=edit&section=3 "编辑章节：特性")\]

<table role="presentation"><tbody><tr><td><a href="chrome-extension://cjedbglnccaioiolemnfhjncicchinao/wiki/File:Wiki_letter_w_cropped.svg"><img alt="[icon]" src="chrome-extension://upload.wikimedia.org/wikipedia/commons/thumb/1/1c/Wiki_letter_w_cropped.svg/20px-Wiki_letter_w_cropped.svg.png" decoding="async" width="20" height="14" srcset="chrome-extension://upload.wikimedia.org/wikipedia/commons/thumb/1/1c/Wiki_letter_w_cropped.svg/30px-Wiki_letter_w_cropped.svg.png 1.5x, chrome-extension://upload.wikimedia.org/wikipedia/commons/thumb/1/1c/Wiki_letter_w_cropped.svg/40px-Wiki_letter_w_cropped.svg.png 2x" data-file-width="44" data-file-height="31"></a></td><td><span>此章节需要<a href="https://zh.wikipedia.org/w/index.php?title=MIPS%E6%9E%B6%E6%A7%8B&amp;action=edit"><b>扩充</b></a>。 <small><i>(<span>2019年12月1日</span>)</i></small></span></td></tr></tbody></table>

#### 延迟槽\[[编辑](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/w/index.php?title=MIPS%E6%9E%B6%E6%A7%8B&action=edit&section=4 "编辑章节：延迟槽")\]

为了减少各种指令后流水线的阻塞，MIPS I引入了延迟槽机制，在分支与加载指令后都有一条指令的延迟槽。分支指令延迟槽中的内容会先于分支指令被提交。而加载指令的延迟槽中则不允许使用刚刚加载的数据。一般情况下延迟槽的安排会由汇编器完成，但在一些情况下程序员仍然需要关注他的存在。对于实在无法安排指令的延迟槽可以直接填入"NOP"。

### 操作数\[[编辑](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/w/index.php?title=MIPS%E6%9E%B6%E6%A7%8B&action=edit&section=5 "编辑章节：操作数")\]

MIPS包括32个寄存器和2^30个存储器字，详见下表[\[9\]](#cite_note-9)：

<table><caption>MIPS操作数</caption><tbody><tr><th>名字</th><th>举例</th><th>注释</th></tr><tr><td>32个寄存器</td><td>$s0 ~ $s7，$t0 ~ $t9，$zero，$a0 ~ $a3，$v0 ~ $v1，$gp，$fp，$sp，$ra，$at</td><td>寄存器用于数据的快速访问。在MIPS中，只能对存放在寄存器中的数执行算术操作，寄存器$zero恒为0，寄存器$at被汇编器保留，用于处理大的常数。</td></tr><tr><td>2^30个存储字</td><td>Memory[0]，Memory[4]，...，Memory[4294967292]</td><td>存储器只能通过数据传输指令访问。MIPS使用字节编址，所以连续的字地址相差4。存储器用于保存数据结构、数组和溢出的寄存器</td></tr></tbody></table>

### 指令格式\[[编辑](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/w/index.php?title=MIPS%E6%9E%B6%E6%A7%8B&action=edit&section=6 "编辑章节：指令格式")\]

在MIPS架构中，指令被分为三种类型：R型、I型和J型。三种类型的指令的最高6位均为6位的opcode码。从25位往下，

*   R型指令用连续三个5位二进制码来表示三个寄存器的地址，然后用一个5位二进制码来表示[移位](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/wiki/%E7%A7%BB%E4%BD%8D%E5%AF%84%E5%AD%98%E5%99%A8 "移位寄存器")的位数（如果未使用移位操作，则全为0），最后为6位的function码（它与opcode码共同决定R型指令的具体操作方式）；
*   I型指令则用连续两个5位二进制码来表示两个寄存器的地址，然后是一个16位二进制码来表示的一个立即数二进制码；
*   J型指令用26位二进制码来表示跳转目标的指令地址（实际的指令地址应为32位，其中最低两位为00，）。[\[10\]](#cite_note-uidaho-10)[\[11\]](#cite_note-11)

三种类型的指令图示如下：

| 类型 | [位](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/wiki/%E4%BD%8D%E5%85%83 "比特") |
| --- | --- |
| 31 | 30 | 29 | 28 | 27 | 26 | 25 | 24 | 23 | 22 | 21 | 20 | 19 | 18 | 17 | 16 | 15 | 14 | 13 | 12 | 11 | 10 | 9 | 8 | 7 | 6 | 5 | 4 | 3 | 2 | 1 | 0 |
| R | opcode (6) | rs (5) | rt (5) | rd (5) | shamt (5) | funct (6) |
| I | opcode (6) | rs (5) | rt (5) | immediate (16) |
| J | opcode (6) | address (26) |

### 指令\[[编辑](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/w/index.php?title=MIPS%E6%9E%B6%E6%A7%8B&action=edit&section=7 "编辑章节：指令")\]

#### 访存指令\[[编辑](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/w/index.php?title=MIPS%E6%9E%B6%E6%A7%8B&action=edit&section=8 "编辑章节：访存指令")\]

MIPS I 具有访存8-bit字节，16-bit半字，32-bit字的能力， 并且只支持“基地址+偏移”一种[寻址模式](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/wiki/%E5%AF%BB%E5%9D%80%E6%A8%A1%E5%BC%8F "寻址模式")。 由于MIPS I是一种32位架构，少于32-bit的加载指令在目标寄存器中都会对高位进行符号扩展或全零扩展到32-bit。带有 "无符号" 后缀的指令会被进行全零扩展，其他的指令会进行符号扩展。 加载指令会从一个通用寄存器中获取基地址 (rs) 并将从操作地址读取的结果写入一个通用寄存器 (rt). 存储指令则会从一个通用寄存器获取基地址(rs)，将另一个通用寄存器(rt)中的内容写入相应操作地址。所有的访存指令都会将基地址加上指令中的有符号16-bit立即数immediate偏移以获得最终操作地址。 MIPS I要求所有的访存指令与操作单位对齐，也就是目标地址必须是所访问数据字节数的整数倍。为了支持高效的非对其访存，MIPS提供了带左/右后缀的访存指令。所有的加载指令后面带有一个延迟槽，延迟槽内的指令不得使用刚刚加载的指令。

| 指令功能 | 助记符 | 格式 | 格式 |
| --- | --- | --- | --- |
| 加载字节 | LB | I | 3210 | rs | rt | offset |
| 加载半字 | LH | I | 3310 | rs | rt | offset |
| 加载字左 | LWL | I | 3410 | rs | rt | offset |
| 加载字 | LW | I | 3510 | rs | rt | offset |
| 加载无符号字 | LBU | I | 3610 | rs | rt | offset |
| 加载无符号半字 | LHU | I | 3710 | rs | rt | offset |
| 加载字右 | LWR | I | 3810 | rs | rt | offset |
| 存储字节 | SB | I | 4010 | rs | rt | offset |
| 存储半字 | SH | I | 4110 | rs | rt | offset |
| 存储字左 | SWL | I | 4210 | rs | rt | offset |
| 存储字 | SW | I | 4310 | rs | rt | offset |
| 存储字右 | SWR | I | 4610 | rs | rt | offset |

相关条目\[[编辑](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/w/index.php?title=MIPS%E6%9E%B6%E6%A7%8B&action=edit&section=9 "编辑章节：相关条目")\]
--------------------------------------------------------------------------------------------------------------------------------------------

[MIPS架构处理器](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/wiki/MIPS%E6%9E%B6%E6%9E%84%E5%A4%84%E7%90%86%E5%99%A8 "MIPS架构处理器")  
[流水线](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/wiki/%E7%AE%A1%E7%B7%9A "流水线")

参考文献\[[编辑](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/w/index.php?title=MIPS%E6%9E%B6%E6%A7%8B&action=edit&section=10 "编辑章节：参考文献")\]
---------------------------------------------------------------------------------------------------------------------------------------------

1.  **[^](#cite_ref-1 "跳转")** [MIPS32 Architecture](https://www.mips.com/products/architectures/mips32-3/). MIPS. \[March 20, 2020\]. （原始内容[存档](https://web.archive.org/web/20200321031349/https://www.mips.com/products/architectures/mips32-3/)于2020-03-21）.
2.  **[^](#cite_ref-2 "跳转")** [MIPS64 Architecture](https://www.mips.com/products/architectures/mips64/). MIPS. \[March 20, 2020\]. （原始内容[存档](https://web.archive.org/web/20200202235833/https://www.mips.com/products/architectures/mips64/)于2020-02-02）.
3.  **[^](#cite_ref-3 "跳转")** [MIPS-3D ASE](http://www.imgtec.com/mips/mips-3d-ase.asp). [Imagination Technologies](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/wiki/Imagination_Technologies "Imagination Technologies"). \[January 4, 2014\]. （原始内容[存档](https://web.archive.org/web/20140103091950/http://www.imgtec.com/mips/mips-3d-ase.asp)于2014-01-03）.
4.  **[^](#cite_ref-4 "跳转")** [MIPS16e](https://www.mips.com/products/architectures/ase/ase16e/). MIPS. \[March 20, 2020\]. （原始内容[存档](https://web.archive.org/web/20210116053233/https://www.mips.com/products/architectures/ase/ase16e/)于2021-01-16）.
5.  **[^](#cite_ref-5 "跳转")** [MIPS Multithreading](https://www.mips.com/products/architectures/ase/multi-threading/). MIPS. \[March 20, 2020\]. （原始内容[存档](https://web.archive.org/web/20201026011525/https://www.mips.com/products/architectures/ase/multi-threading/)于2020-10-26）.
6.  **[^](#cite_ref-6 "跳转")** [存档副本](https://www.eettaiwan.com/20200424nt01-wave-computing-set-to-file-chapter-11-with-mips-the-likely-winner/). \[2020-07-29\]. （原始内容[存档](https://web.archive.org/web/20200729034403/https://www.eettaiwan.com/20200424nt01-wave-computing-set-to-file-chapter-11-with-mips-the-likely-winner/)于2020-07-29）.
7.  **[^](#cite_ref-7 "跳转")** [MIPS becomes RISC-V](https://www.eejournal.com/article/wait-what-mips-becomes-risc-v/) March 8, 2021. Retrieved March 11, 2021.
8.  **[^](#cite_ref-8 "跳转")** [Wave Computing and MIPS emerge from chapter 11 bankruptcy](https://www.prnewswire.com/news-releases/wave-computing-and-mips-emerge-from-chapter-11-bankruptcy-301237051.html) March 1, 2021. Retrieved March 11, 2021.
9.  **[^](#cite_ref-9 "跳转")** David A, Patterson. 计算机组成与设计：硬件、软件接口（原书第4版）. 机械工业出版社.
10.  **[^](#cite_ref-uidaho_10-0 "跳转")** [MIPS R3000 Instruction Set Summary](https://web.archive.org/web/20180628185213/http://www.mrc.uidaho.edu/mrc/people/jff/digital/MIPSir.html). \[2013-08-21\]. （[原始内容](http://www.mrc.uidaho.edu/mrc/people/jff/digital/MIPSir.html)存档于2018-06-28）.
11.  **[^](#cite_ref-11 "跳转")** [MIPS Instruction Reference](http://www.xs4all.nl/~vhouten/mipsel/r3000-isa.html). \[2013-08-21\]. （原始内容[存档](https://web.archive.org/web/20101205171903/http://www.xs4all.nl/~vhouten/mipsel/r3000-isa.html)于2010-12-05）.

外部链接\[[编辑](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/w/index.php?title=MIPS%E6%9E%B6%E6%A7%8B&action=edit&section=11 "编辑章节：外部链接")\]
---------------------------------------------------------------------------------------------------------------------------------------------

*   [MIPS 架构](http://www.mips.com/products/architectures/) （[页面存档备份](chrome-extension://web.archive.org/web/20200926113910/http://www.mips.com/products/architectures/)，存于[互联网档案馆](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/wiki/%E4%BA%92%E8%81%94%E7%BD%91%E6%A1%A3%E6%A1%88%E9%A6%86 "互联网档案馆")）
*   [计算机组织：MIPS 指令集 (一) 寄存器说明](https://isite.tw/2015/03/17/13075) （[页面存档备份](chrome-extension://web.archive.org/web/20201020024023/https://isite.tw/2015/03/17/13075)，存于[互联网档案馆](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/wiki/%E4%BA%92%E8%81%94%E7%BD%91%E6%A1%A3%E6%A1%88%E9%A6%86 "互联网档案馆")）

| \[[显示](#)\]
*   [查](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/wiki/Template:RISC_architectures "Template:RISC architectures")
*   [论](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/wiki/Template_talk:RISC_architectures "Template talk:RISC architectures")
*   [编](https://zh.wikipedia.org/w/index.php?title=Template:RISC_architectures&action=edit)

[精简指令集](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/wiki/%E7%B2%BE%E7%AE%80%E6%8C%87%E4%BB%A4%E9%9B%86%E8%AE%A1%E7%AE%97%E6%9C%BA "精简指令集计算机")



 |
| --- |

| \[[显示](#)\]
*   [查](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/wiki/Template:MIPS%E8%8A%AF%E7%89%87 "Template:MIPS芯片")
*   [论](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/w/index.php?title=Template_talk:MIPS%E8%8A%AF%E7%89%87&action=edit&redlink=1 "Template talk:MIPS芯片（页面不存在）")
*   [编](https://zh.wikipedia.org/w/index.php?title=Template:MIPS%E8%8A%AF%E7%89%87&action=edit)

MIPS芯片

 |
| --- |

| \[[显示](#)\]
*   [查](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/wiki/Template:%E5%A4%84%E7%90%86%E5%99%A8%E6%8A%80%E6%9C%AF "Template:处理器技术")
*   [论](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/w/index.php?title=Template_talk:%E5%A4%84%E7%90%86%E5%99%A8%E6%8A%80%E6%9C%AF&action=edit&redlink=1 "Template talk:处理器技术（页面不存在）")
*   [编](https://zh.wikipedia.org/w/index.php?title=Template:%E5%A4%84%E7%90%86%E5%99%A8%E6%8A%80%E6%9C%AF&action=edit)

[处理器技术](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/wiki/%E5%A4%84%E7%90%86%E5%99%A8_(%E8%AE%A1%E7%AE%97) "处理器 (计算)")



 |
| --- |


[Source](https://zh.wikipedia.org/wiki/MIPS%E6%9E%B6%E6%A7%8B)