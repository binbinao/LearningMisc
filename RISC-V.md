# RISC-V - 维基百科，自由的百科全书
<table><caption><b>RISC-V</b></caption><tbody><tr><td colspan="2"><a href="chrome-extension://cjedbglnccaioiolemnfhjncicchinao/wiki/File:RISC-V-logo.svg"><img alt="RISC-V-logo.svg" src="chrome-extension://upload.wikimedia.org/wikipedia/commons/thumb/9/9a/RISC-V-logo.svg/220px-RISC-V-logo.svg.png" decoding="async" width="220" height="37" srcset="chrome-extension://upload.wikimedia.org/wikipedia/commons/thumb/9/9a/RISC-V-logo.svg/330px-RISC-V-logo.svg.png 1.5x, chrome-extension://upload.wikimedia.org/wikipedia/commons/thumb/9/9a/RISC-V-logo.svg/440px-RISC-V-logo.svg.png 2x" data-file-width="512" data-file-height="85"></a></td></tr><tr><th scope="row">推出年份</th><td>2010年<span>，​11年前</span></td></tr><tr><th scope="row">设计公司</th><td><a href="chrome-extension://cjedbglnccaioiolemnfhjncicchinao/wiki/%E5%8A%A0%E5%B7%9E%E5%A4%A7%E5%AD%B8%E6%9F%8F%E5%85%8B%E8%90%8A%E5%88%86%E6%A0%A1" title="加州大学柏克莱分校">加州大学柏克莱分校</a></td></tr><tr><th scope="row">最新架构版本</th><td>2.2</td></tr><tr><th scope="row">是否开放架构？</th><td>是</td></tr><tr><th scope="row">体系结构类型</th><td>Load-store</td></tr><tr><th scope="row">字长/寄存器资料宽度</th><td>32、64、128</td></tr><tr><th scope="row"><a href="chrome-extension://cjedbglnccaioiolemnfhjncicchinao/wiki/%E5%AD%97%E8%8A%82%E5%BA%8F" title="字节序">字节序</a></th><td>小端序</td></tr><tr><th scope="row">指令编码长度</th><td>不定长度</td></tr><tr><th scope="row">指令集架构设计策略</th><td>RISC</td></tr><tr><th scope="row">扩展指令集</th><td>M、A、F、D、Q、C、P</td></tr><tr><th scope="row"><a href="chrome-extension://cjedbglnccaioiolemnfhjncicchinao/wiki/%E5%88%86%E6%94%AF%E9%A0%90%E6%B8%AC%E5%99%A8" title="分支预测器">分支预测结构</a></th><td>比较和分支</td></tr><tr><th scope="row">通用寄存器</th><td>16、32（包括一个始终为零的寄存器）</td></tr><tr><th scope="row">浮点寄存器</th><td>32</td></tr></tbody></table>

[![](chrome-extension://upload.wikimedia.org/wikipedia/commons/thumb/7/7a/Yunsup_Lee_holding_RISC_V_prototype_chip.jpg/220px-Yunsup_Lee_holding_RISC_V_prototype_chip.jpg)](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/wiki/File:Yunsup_Lee_holding_RISC_V_prototype_chip.jpg)

**RISC-V**（发音为“risk-five”）是一个基于[精简指令集](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/wiki/%E7%B2%BE%E7%AE%80%E6%8C%87%E4%BB%A4%E9%9B%86 "精简指令集")（RISC）原则的[开源](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/wiki/%E5%BC%80%E6%BA%90%E6%A0%87%E5%87%86 "开源标准")[指令集架构](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/wiki/%E6%8C%87%E4%BB%A4%E9%9B%86%E6%9E%B6%E6%A7%8B "指令集架构")（ISA），简易解释为[开源软件](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/wiki/%E5%BC%80%E6%BA%90%E8%BD%AF%E4%BB%B6 "开源软件")运动相对应的一种“开源硬件”。该项目2010年始于[加州大学柏克莱分校](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/wiki/%E5%8A%A0%E5%B7%9E%E5%A4%A7%E5%AD%B8%E6%9F%8F%E5%85%8B%E8%90%8A%E5%88%86%E6%A0%A1 "加州大学柏克莱分校")，但许多贡献者是该大学以外的志愿者和行业工作者。

与大多数指令集相比，RISC-V指令集可以自由地用于任何目的，允许任何人[设计](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/wiki/%E9%9B%86%E6%88%90%E7%94%B5%E8%B7%AF%E8%AE%BE%E8%AE%A1 "集成电路设计")、制造和销售RISC-V[芯片](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/wiki/%E9%9B%86%E6%88%90%E7%94%B5%E8%B7%AF "集成电路")和[软件](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/wiki/%E8%BD%AF%E4%BB%B6 "软件")而不必支付给任何公司专利费。虽然这不是第一个开源指令集[\[1\]](#cite_note-1)，但它具有重要意义，因为其设计使其适用于现代计算设备（如仓库规模[云计算机](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/wiki/%E9%9B%B2%E7%AB%AF%E9%81%8B%E7%AE%97 "云计算")、高端[移动电话](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/wiki/%E7%A7%BB%E5%8A%A8%E7%94%B5%E8%AF%9D "移动电话")和微小[嵌入式系统](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/wiki/%E5%B5%8C%E5%85%A5%E5%BC%8F%E7%B3%BB%E7%BB%9F "嵌入式系统")）。设计者考虑到了这些用途中的性能与功率效率。该指令集还具有众多支持的软件，这解决了新指令集通常的弱点。[\[2\]](#cite_note-si2019-2)

RISC-V指令集的设计考虑了小型、快速、低功耗的现实情况来实做，但并没有对特定的[微架构](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/wiki/%E5%BE%AE%E6%9E%B6%E6%A7%8B "微架构")做过度的设计。[\[3\]](#cite_note-sodor-3)[\[4\]](#cite_note-boom-4)截至2017年5月RISC-V已经确立了版本2.22的用户空间的指令集(userspace ISA)，而特权指令集(privileged ISA)也处在草案版本1.10。

意义\[[编辑](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/w/index.php?title=RISC-V&action=edit&section=1 "编辑章节：意义")\]
------------------------------------------------------------------------------------------------------------------------

RISC-V的作者们旨在提供数种可以在[BSD许可证](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/wiki/BSD%E8%AE%B8%E5%8F%AF%E8%AF%81 "BSD许可证")之下自由使用的CPU设计。该许可证允许像是RISC-V芯片设计等派生作品可以像RISC-V本身一样是公开且自由发行，也可以是闭源或者是专有财产。

相比而言，[ARM控股](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/wiki/%E5%AE%89%E8%AC%80%E6%8E%A7%E8%82%A1 "安谋控股")和[MIPS科技](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/wiki/%E7%BE%8E%E6%99%AE%E6%80%9D%E7%A7%91%E6%8A%80 "美普思科技")等商业芯片供应商会对使用其[专利](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/wiki/%E4%B8%93%E5%88%A9 "专利")者收取高额的许可费用。[\[5\]](#cite_note-5)他们也要求在接收其描述设计优点的文件和指令集前，还需要签署保密协议。许多设计优点为完全专有，从来不会披露给客户。这种保密制度阻碍了公共教育用途和安全审核，以及开发公共、低成本的[自由及开放源代码软件](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/wiki/%E8%87%AA%E7%94%B1%E5%8F%8A%E5%BC%80%E6%94%BE%E6%BA%90%E4%BB%A3%E7%A0%81%E8%BD%AF%E4%BB%B6 "自由及开放源代码软件")[编译器](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/wiki/%E7%B7%A8%E8%AD%AF%E5%99%A8 "编译器")和[操作系统](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/wiki/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F "操作系统")。[\[来源请求\]](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/wiki/Wikipedia:%E5%88%97%E6%98%8E%E6%9D%A5%E6%BA%90 "Wikipedia:列明来源")

开发一个CPU需要多种专业的设计知识，包括电子逻辑、编译器和操作系统。这种资源在专业工程团队之外很难见到。所以现代且高质量的通用计算机指令集近年来除了学术环境以外并没有在任何地方被广泛使用，甚至没有被阐述。正因如此，许多RISC-V贡献者将此视为整个社区付出的成果，而这也是RISC-V有很多任务程上的应用的一项原因。

RISC-V的作者们还有大量研究和用户经验来验证他们在硅片和仿真中的设计。RISC-V指令集是从一系列的学术计算机设计项目直接发展而来的。它一开始的目的有一部分是为了帮助这些项目。

历史\[[编辑](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/w/index.php?title=RISC-V&action=edit&section=2 "编辑章节：历史")\]
------------------------------------------------------------------------------------------------------------------------

### 前身\[[编辑](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/w/index.php?title=RISC-V&action=edit&section=3 "编辑章节：前身")\]

RISC的历史可追溯到1980年左右。[\[6\]](#cite_note-riscstart-6)在此之前，人们觉得简单的计算机可能会有用，但是没有很多人去阐述其设计原则。这种简单而有效的计算机一直都是学术界的兴趣。

学术界的学者们为了出版第一版的《计算机体系结构：定量方法》（_Computer Architecture: A Quantitative Approach_）[ISBN 978-1558600690](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/wiki/Special:%E7%BD%91%E7%BB%9C%E4%B9%A6%E6%BA%90/9781558600690) ，所以于1990年订立了RISC指令集DLX。David Patterson是其中一位作者，后来协助RISC-V的开发。但是DLX只用于教育用途，学术界和业余爱好者使用[FPGA（现场可编程门数组）](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/wiki/%E7%8E%B0%E5%9C%BA%E5%8F%AF%E7%BC%96%E7%A8%8B%E9%80%BB%E8%BE%91%E9%97%A8%E9%98%B5%E5%88%97 "现场可编程逻辑门阵列")来实做它，但并没有获取商业运用。版本2及更早版本的ARM CPU具有公共域指令集，并且仍有GCC的支持，而GCC是一个受欢迎且免费的软件编译器。该ISA有三个开源内核，但尚未制造。

OpenRISC是一款基于DLX的开源ISA，并且具有相关的RISC设计。它完全支持GCC并且有实做在Linux上。但是它很少有商业上的实做，直到2018年下半年SiFive公司10月推出一系列全新 CPU设计图产品线应用涵盖 [5G](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/wiki/5G "5G")、网通、存储、[增强现实](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/wiki/%E6%93%B4%E5%A2%9E%E5%AF%A6%E5%A2%83 "增强现实")（AR）、[虚拟现实](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/wiki/%E8%99%9B%E6%93%AC%E5%AF%A6%E5%A2%83 "虚拟现实")（VR）等，其 E系列与 U系列的 CPU方案已经威胁到ARM(安谋)公司的收费产品并且拥有后者缺乏的64位架构产品。[\[7\]](#cite_note-7)。

[ARM](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/wiki/ARM "ARM")公司受到威胁后上线了一个网站riscv-basics.com，列举了对RISC-V的批判，包括：成本、生态系统、碎片化风险、安全性问题、设计验证。但最终迫于业界舆论恶评，ARM关闭了该网站。[\[2\]](#cite_note-si2019-2)

### 基金会\[[编辑](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/w/index.php?title=RISC-V&action=edit&section=4 "编辑章节：基金会")\]

加州柏克莱分校的Krste Asanović教授，发现开放源代码的电脑系统有很多用途。在2010年他决定用三个月的时间来开发并发表一个开放源代码的电脑系统。这个项目是用来帮助包括学术以及工业的用户。柏克莱分校的[大卫·帕特森](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/wiki/%E5%A4%A7%E8%A1%9B%C2%B7%E5%B8%95%E7%89%B9%E6%A3%AE_(%E5%AD%B8%E8%80%85) "大卫·帕特森 (学者)")教授也参加了这个项目。帕特森也是原来伯克利分校RISC的设计者，RISC-V只是他众多RISC [CPU](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/wiki/CPU "CPU")研究项目的一个．RISC-V项目早期一些经费来自[DARPA](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/wiki/DARPA "DARPA")。

有参与支持RISC-V基金会的公司以及机构包括了[超微半导体](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/wiki/%E8%B6%85%E5%BE%AE%E5%8D%8A%E5%AF%BC%E4%BD%93 "超微半导体")，[晶心科技](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/wiki/%E6%99%B6%E5%BF%83%E7%A7%91%E6%8A%80 "晶心科技")，[英国航太系统](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/wiki/%E8%8B%B1%E5%9B%BD%E8%88%AA%E5%A4%AA%E7%B3%BB%E7%BB%9F "英国航太系统")，加州大学伯克利分校，[BLuespec](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/w/index.php?title=BLuespec&action=edit&redlink=1 "BLuespec（页面不存在）")，Cortus，[Google](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/wiki/Google "Google")，GreenWaves Technology，[慧与科技](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/wiki/%E6%85%A7%E8%88%87%E7%A7%91%E6%8A%80 "慧与科技")，[华为](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/wiki/%E8%8F%AF%E7%82%BA "华为")，[IBM](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/wiki/IBM "IBM")，Imperas Software，[中国科学院](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/wiki/%E4%B8%AD%E5%9B%BD%E7%A7%91%E5%AD%A6%E9%99%A2 "中国科学院")，北京清华大学，[印度理工学院](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/wiki/%E5%8D%B0%E5%BA%A6%E7%90%86%E5%B7%A5%E5%AD%B8%E9%99%A2 "印度理工学院")，莱迪思半导体，迈伦科技，美高森美，[美光科技](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/wiki/%E7%BE%8E%E5%85%89%E7%A7%91%E6%8A%80 "美光科技")，[英伟达](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/wiki/%E8%BC%9D%E9%81%94 "英伟达")，[恩智浦半导体](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/wiki/%E6%81%A9%E6%99%BA%E6%B5%A6%E5%8D%8A%E5%AF%BC%E4%BD%93 "恩智浦半导体")，[甲骨文公司](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/wiki/%E7%94%B2%E9%AA%A8%E6%96%87%E5%85%AC%E5%8F%B8 "甲骨文公司")，[高通](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/wiki/%E9%AB%98%E9%80%9A "高通")，[Rambus Cryptography Research](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/w/index.php?title=Rambus_Cryptography_Research&action=edit&redlink=1 "Rambus Cryptography Research（页面不存在）")，[西部数据](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/wiki/%E5%A8%81%E9%A8%B0%E9%9B%BB%E5%AD%90 "西部数据")，[SiFive](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/w/index.php?title=SiFive&action=edit&redlink=1 "SiFive（页面不存在）")，[阿里巴巴集团](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/wiki/%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E9%9B%86%E5%9B%A2 "阿里巴巴集团")，[红帽公司](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/wiki/%E7%B4%85%E5%B8%BD%E5%85%AC%E5%8F%B8 "红帽公司")，[成为资本](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/w/index.php?title=%E6%88%90%E4%B8%BA%E8%B5%84%E6%9C%AC&action=edit&redlink=1 "成为资本（页面不存在）")[\[8\]](#cite_note-8)。。

2019年6月，图灵奖得主、RISC-V基金会创始人之一[大卫·帕特森（David Patterson）](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/wiki/%E5%A4%A7%E8%A1%9B%C2%B7%E5%B8%95%E7%89%B9%E6%A3%AE_(%E5%AD%B8%E8%80%85) "大卫·帕特森 (学者)")在瑞士宣布，将依托清华-伯克利深圳学院（TBSI），在内部建设RISC-V国际开源实验室（RISC-V International Open Source Laboratory），又称大卫帕特森RIOS图灵实验室。北京[清华大学](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/wiki/%E6%B8%85%E5%8D%8E%E5%A4%A7%E5%AD%A6 "清华大学")称实验室将瞄准世界CPU产业战略发展新方向和[粤港澳大湾区](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/wiki/%E7%B2%A4%E6%B8%AF%E6%BE%B3%E5%A4%A7%E6%B9%BE%E5%8C%BA "粤港澳大湾区")产业创新需求，[\[2\]](#cite_note-si2019-2)聚焦于开源指令集CPU研究，建设以[深圳](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/wiki/%E6%B7%B1%E5%9C%B3 "深圳")为根节点的RISC-V全球创新网络和以技术成果转移为主要使命的非营利组织，全面提升RISC-V生态系至最先进可商用水平。预判届时将面对国际大厂法律层面发起挑战问题上，伯克利加州大学和清华大学的[法学院](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/wiki/%E6%B3%95%E5%AD%A6%E9%99%A2 "法学院")将与之创建联系。[\[2\]](#cite_note-si2019-2)

### 奖项\[[编辑](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/w/index.php?title=RISC-V&action=edit&section=5 "编辑章节：奖项")\]

*   2017：[The Linley Group's Analyst's Choice Award for Best Technology](http://linleygroup.com/press_detail.php?The-Linley-Group-Announces-Winners-of-Annual-Analysts-Choice-Awards-85)（[页面存档备份](chrome-extension://web.archive.org/web/20170824134910/http://linleygroup.com/press_detail.php?The-Linley-Group-Announces-Winners-of-Annual-Analysts-Choice-Awards-85)，存于[互联网档案馆](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/wiki/%E4%BA%92%E8%81%94%E7%BD%91%E6%A1%A3%E6%A1%88%E9%A6%86 "互联网档案馆")）（对其指令集）

[![](chrome-extension://upload.wikimedia.org/wikipedia/commons/thumb/8/8e/IGLOO2-Pre-Programmed-RISC-V-Development-Board.jpg/220px-IGLOO2-Pre-Programmed-RISC-V-Development-Board.jpg)](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/wiki/File:IGLOO2-Pre-Programmed-RISC-V-Development-Board.jpg)

激励要求\[[编辑](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/w/index.php?title=RISC-V&action=edit&section=6 "编辑章节：激励要求")\]
----------------------------------------------------------------------------------------------------------------------------

RISC设计者们认为指令集因为位于硬件和软件之间，所以是电脑主要的沟通桥梁，因此如果有一个设计良好的指令集是开源而且可以被任何人使用的，就可以让更多的资源能够重复利用，而大大的减少软件的成本。而这样的指令集也会增加硬件供应商市场的竞争力，因为硬件供应商们可以挪用更多资源来进行设计，减少处理软件支持的事务。[\[9\]](#cite_note-isasbefree-9)

设计者声称在指令集设计领域里，新的设计准则渐渐变得罕见，而近四十年中，大多数成功的设计变得越来越相似。至于那些失败的指令集，大多数是因为他们的赞助商赚不了钱，而不是因为其指令集在技术上有多差。所以，一个在成熟的设计准则之下开发且设计良好的开源指令集想必能吸引许多供应商长期的支持。[\[9\]](#cite_note-isasbefree-9)

许多先前的开源指令集架构使用[GNU通用公共许可协议](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/wiki/GNU%E9%80%9A%E7%94%A8%E5%85%AC%E5%85%B1%E8%AE%B8%E5%8F%AF%E8%AF%81 "GNU通用公共许可证")来鼓励用户们允许他们的实现方法被其他人复制或是使用。

设计者们表示，RISC-V指令集是给实际上的电脑使用的，它不像其他学术上的指令集设计，只有为了比较好阐述理念而做优化。而RISC-V指令集有一些功能是可以增加电脑速度又可以减少成本和电源使用。这些特色包含，[Load/store架构](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/wiki/Load/store%E6%9E%B6%E6%A7%8B "Load/store架构")，在CPU里面的比特表示方法来简化[MUX（数据多任务器）](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/wiki/MUX "MUX")，以标准为基础来简化的浮点数，架构中立的设计和把[MSB(Most significant bit)](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/wiki/%E6%9C%80%E9%AB%98%E6%9C%89%E6%95%88%E4%BD%8D "最高有效位")放到固定位置来加速[Sign extension](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/w/index.php?title=Sign_extension&action=edit&redlink=1)。而sign-extension常常就是[静态时序分析](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/wiki/%E9%9D%99%E6%80%81%E6%97%B6%E5%BA%8F%E5%88%86%E6%9E%90 "静态时序分析")里面的关键路径（Critical timing path）[\[10\]](#cite_note-isa-10)。

RISC-V 指令集是设计来给各式各样的用途使用的，而它支持三个不同的[字组](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/wiki/%E5%AD%97_(%E8%AE%A1%E7%AE%97%E6%9C%BA) "字 (计算机)")大小，分别是32位、64位、128位以及与这三种字组大小有关的各式各样的指令子集。而这些指令子集的定义会按照那三个字组大小来做些微的改动。透过这些指令子集的向量处理器与数据中心等级的机柜式平行电脑/[平行运算](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/wiki/%E5%B9%B3%E8%A1%8C%E9%81%8B%E7%AE%97 "平行运算")来帮助[嵌入式系统](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/wiki/%E5%B5%8C%E5%85%A5%E5%BC%8F%E7%B3%BB%E7%BB%9F "嵌入式系统")、[个人电脑](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/wiki/%E5%80%8B%E4%BA%BA%E9%9B%BB%E8%85%A6 "个人电脑")和[超级电脑](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/wiki/%E8%B6%85%E7%B4%9A%E9%9B%BB%E8%85%A6 "超级电脑")。

该指令集采取不固定的编码长度而且还可以再扩展，因此在未来，还可以一直加入更多比特的编码方式。该指令集有特别留空间给128位的延伸版本，因为60年的产业界经验显示在指令集设计领域里，最无法撤销的错误就是缺少存储器寻址空间。截至2016年，128位的指令集仍然刻意地维持在没有定义的状态，这是因为到现在为止，人们很少有实际上操作这么大存储器的系统的经验。[\[10\]](#cite_note-isa-10)

然而，RISC-V也可以拿来做学术上的使用。它拥有简化的整数指令子集允许学生拿来做基本的练习，而整数指令子集就是一个简单的指令集架构（ISA）让软件可以控制研究上的机器。而不定长度的指令集架构也允许扩展来满足研究或是学生练习上的需求。[\[10\]](#cite_note-isa-10)分割出来的特权指令集可以支持在不重新设计编译器的情况下，进行操作系统方面的研究。[\[11\]](#cite_note-isapriv-11)RISC-V的开放的知识产权允许相关的设计被发布、使用和修改。[\[10\]](#cite_note-isa-10)

软件\[[编辑](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/w/index.php?title=RISC-V&action=edit&section=7 "编辑章节：软件")\]
------------------------------------------------------------------------------------------------------------------------

一个新的CPU[指令集](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/wiki/%E6%8C%87%E4%BB%A4%E9%9B%86 "指令集")通常的问题是缺少CPU的硬件设计跟软件的支持。在RISC-V的网站有一个user mode指令集的规格，还有１个用来支持[操作系统](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/wiki/%E4%BD%9C%E6%A5%AD%E7%B3%BB%E7%B5%B1 "操作系统")模式的优先指令集的初步规格。

市面上已经有好几个使用RISC-V开源架构的CPU设计可以供参考，包括64-bit Berkeley Out of Order Machine (BOOM)[\[12\]](#cite_note-boom-github-12)、64-bit Rocket[\[13\]](#cite_note-rocket-chip-github-13)、柏克莱设计的五个32-bit Sodor CPU[\[3\]](#cite_note-sodor-3)、Clifford Wolf 的 picorv32、Syntacore 的 scr1、苏黎世联邦理工学院／波隆纳大学的 PULPino (Riscy and Zero-Riscy)[\[14\]](#cite_note-pulpino-14)，以及很多其他的设计。使用三层指令分段的 Sodor CPU 是一个适合[嵌入式](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/wiki/%E5%B5%8C%E5%85%A5%E5%BC%8F "嵌入式")设计的小型CPU。Rocket可能适用在小型低功耗的[个人电脑](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/wiki/%E5%80%8B%E4%BA%BA%E9%9B%BB%E8%85%A6 "个人电脑")或其他个人设备。BOOM 使用了大部分Rocket的架构，但是功能更加强大，适合个人电脑、服务器或超级电脑。picorv 跟 scr1 都是使用Verilog 设计的 32位 MCU 等级的 RV32IMC。PULPino的核心使用了一个适合微控制器的简单的 RV32IMC ISA架构(Zero-Riscy)，以及另外１个更强大的DSP版本 RV32IMFC ISA 可以支持一些嵌入式信号处理的特别DSP 指令集．

设计软件包括了１个设计编译器 Chisel，它可把设计编译成[Verilog](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/wiki/Verilog "Verilog")代码. 网站上还有测试用的参考资料可以用来验证设计的正确性。

RISC-V目前提供的软件有 [GNU Compiler Collection](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/wiki/GNU_Compiler_Collection "GNU Compiler Collection") (GCC) toolchain (具有调试器 GDB)、一套 [LLVM](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/wiki/LLVM "LLVM") toolchain、[OVPsim](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/w/index.php?title=OVPsim&action=edit&redlink=1 "OVPsim（页面不存在）")模拟器（以及RISC-V快速处理器模式的软件参考库）、Spike 模拟器，以及一套在[QEMU](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/wiki/QEMU "QEMU")上运行的模拟器。

操作系统的支持包括 [Linux](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/wiki/Linux "Linux") 核心、[FreeBSD](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/wiki/FreeBSD "FreeBSD"), 以及 [NetBSD](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/wiki/NetBSD "NetBSD")，但是监督模式的指令在2016年11月10日还没有标准化[\[11\]](#cite_note-isapriv-11)，所以这方面的支持还不是正式的。有一个早期的 RISC-V 的FreeBSD 操作系统已经在2016年2月上传到开放源代码社区，而且包含在 FreeBSD 11.0[\[15\]](#cite_note-freebsdriscv-15)[\[16\]](#cite_note-freebsdriscv-committed-16) 。[Debian](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/wiki/Debian "Debian")[\[17\]](#cite_note-riscv-debian-port-17)跟[Fedora](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/wiki/Fedora "Fedora")[\[18\]](#cite_note-riscv-fedora-port-18)的版本也有人在移植，并且在逐渐稳定中。已经有人做了１个 [U-Boot](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/w/index.php?title=U-Boot&action=edit&redlink=1 "U-Boot（页面不存在）") 的移植版本。[\[19\]](#cite_note-19)UEFI Spec v2.7 定义了RISC-V UFEI 的规格，而且[惠普](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/wiki/%E6%83%A0%E6%99%AE "惠普")公司的工程师已经做好一个 TianoCore的移植版本，并且将会上传到开放源代码社区。已经有人做好了一个 [L4 microkernel family](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/wiki/L4%E5%BE%AE%E5%86%85%E6%A0%B8%E7%B3%BB%E5%88%97 "L4微内核系列") 的移植[\[20\]](#cite_note-riscv-sel4-port-20)。还有一个在网页上用[JavaScript](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/wiki/JavaScript "JavaScript")写的 RISC-V Linux 系统模拟器[\[21\]](#cite_note-riscv-angel-jsport-21)。

设计\[[编辑](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/w/index.php?title=RISC-V&action=edit&section=8 "编辑章节：设计")\]
------------------------------------------------------------------------------------------------------------------------

### 指令子集\[[编辑](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/w/index.php?title=RISC-V&action=edit&section=9 "编辑章节：指令子集")\]

RISC-V 指令使用模块化的设计, 包括几个可以互相替换的基本指令集,　以及额外可以选择的扩展指令集. 所有基本跟扩展的指令集都是由科技产业，　研究机构跟学术界合作开发的. 基本指令集规范了指令跟他们的编码，控制流程，寄存器数目（以及它们的长度），存储器跟寻址方式，逻辑（整数）运算以及其他. 只要有软件以及一个通用的编译器的支持，只用基本指令集就可以用来制作一个简单的通用型的电脑．

标准的扩展指令集可以搭配所有的基本指令集，以及其他扩展指令集，而不会冲突　

很多RISC-V 电脑可能使用精简扩展指令集来降低电力消耗，程序的大小以及存储器的使用. 未来也有项目支持 [hypervisor](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/wiki/Hypervisor "Hypervisor")s, [virtualization](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/wiki/Virtualization "Virtualization")

[\[11\]](#cite_note-isapriv-11) 只要再加上一个监督指令集(S)的扩展，以及以下 RVGC　指令集，我们就有足够的指令可以支持一个 [Unix](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/wiki/Unix "Unix")\-style [操作系统](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/wiki/%E4%BD%9C%E6%A5%AD%E7%B3%BB%E7%B5%B1 "操作系统").

| 指令集名称 | 描述 | 版本 | 状态[\[a\]](#cite_note-frozen-22) |
| --- | --- | --- | --- |
| 基本指令集 |
| RV32I | 基本整数指令集, 32位 | 2.0 | 冻结 |
| RV32E | 基本整数指令集(嵌入式系统), 32位, 16 寄存器 | 1.9 | 开放 |
| RV64I | 基本整数指令集, 64位 | 2.0 | 冻结 |
| RV128I | 基本整数指令集, 128位 | 1.7 | 开放 |
| 标准扩展指令集 |
| M | 整数乘除法标准扩展 | 2.0 | 冻结 |
| A | 不可中断指令(Atomic)标准扩展 | 2.0 | 冻结 |
| F | 单精确度浮点运算标准扩展 | 2.0 | 冻结 |
| D | 双倍精确度浮点运算标准扩展 | 2.0 | 冻结 |
| G | 所有以上的扩展指令集以及基本指令集的总和的简称 | 不适用 | 不适用 |
| Q | 四倍精确度浮点运算标准扩展 | 2.0 | 冻结 |
| L | 十进制浮点运算标准扩展 | 0.0 | 开放 |
| C | 压缩指令标准扩展 　　　 | 2.0 | 冻结 |
| B | 位操作标准扩展 | 0.93 | 开放 |
| J | 动态指令翻译标准扩展 | 0.0 | 开放 |
| T | 顺序存储器访问标准扩展 | 0.0 | 开放 |
| P | 单指令多资料流（SIMD）运算标准扩展 | 0.1 | 开放 |
| V | 向量运算标准扩展 | 0.10 | 开放 |
| N | 用户中断标准扩展 | 1.1 | 开放 |

1.  **[^](#cite_ref-frozen_22-0 "跳转")** 冻结状态代表着他们已经有最终版本的指令集而且在正式发布前只会对原先的内容做澄清

为了让大家容易分辨各种不同的指令组合，所以我们订了一些专有名词． 在RISC-V，我们先指明用哪种基本指令集，然后是寄存器的宽度跟其他变化 e.g., RV64I or RV32E. 然后用上表的字母（以及表列的顺序）表示用了哪种扩展指令. 基本指令集，扩展整数或浮点运算，多CPU系统使用的同步指令扩展，标准扩展指令MAFD被认为是大部分的一般运算都需要的，所以我们给它们一个字母的简称G．

嵌入式系统使用的一个小的 32位电脑可能用 RV32EC. 而大型的64位电脑可以用 RV64GC; RV64IMAFDC.的简称．

也有人提议了一个另外的命名方式，用 Zxxx 表示标准扩展，而 Yxxx 表示非标准扩展(厂商自定义).这些都还在讨论中．

### 寄存器集\[[编辑](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/w/index.php?title=RISC-V&action=edit&section=10 "编辑章节：寄存器集")\]

RISC-V 有 32 个整数寄存器 (在嵌入式版本则是 16 个)。当浮点延伸集被实现的时候，还有 32 个浮点寄存器。除了“存储器访问指令”之外，一般指令“只能”寻址寄存器 (注：无法访问存储器）。

如同有些 RISC 指令集（MIPS, SPARC, DEC Alpha），其中一个寄存器为“零寄存器”（zero register，注：其值永远为零），剩下的寄存器为通用寄存器。在 RISC 当中，第一个整数寄存器是零寄存器。存储数值到零寄存器是没有作用的。使用零寄存器可以让指令集设计更简单。比方说，把“寄存器 X 复制到寄存器 Y” (MOV Y, X)，可以使用“将寄存器 X 与 0 相加后，复制到寄存器 Y” (ADD Y, X, r0) 实现。

RISC-V 有提供“控制寄存器”及“状态寄存器”，但是 user-mode 程序只能访问用来“量测性能”及“浮点管理”的部分。

RISC-V 并没有指令可以存储和恢复（save and restore。注：通常用于 context-switch，中断处理，或是函数调用）多个寄存器。这些设计在 RISC-V 当中，被认为是不必要的，过于复杂的，可能过慢的设计。

### 存储器访问\[[编辑](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/w/index.php?title=RISC-V&action=edit&section=11 "编辑章节：存储器访问")\]

就像许多的 RISC 一样， RISC-V 只有 load 与 store 指令可以访问存储器。

存储器的寻址单位是 8-bit 的 byte，以 little-endian 存放在存储器。Load 与 Store 支持的资料长度从 8-bit 到电脑的 word 大小。访问并不需要对齐到 word 的大小，不过如果有对齐的话，可以增加性能。这项功能可以减小代码大小，而且透过软件的模拟，还可以简化硬件的设计（会触发一个“对齐失败”的中断。

Load 和 Store 指令可以直接使用代码中的常量，在堆栈中的本地变量，或是数据结构中的内容。寻址的方式是使用基底寄存器与 12-bit 的 signed 相对地址 (+- 2KB)。如果基底寄存器是 0，则资料或是常量可以在低地址，或是高地址（负的相对地址，导致绕回到高的存储器地址。比方说 ROM 的存储器地址）。

那么，RISC-V 怎么管理 CPU 与 thread 之间的共享存储器呢？在单一的 thread 当中，运行顺序永远是遵照原本的编译顺序。不过在不同的 thread 以及在 I/O 设备之间，RISC-V 不保证访问的顺序 --- 除非有像 FENCE 这样的指令出现。

FENCE 保证在其之前的运行结果，一定会被其后的 thread 或 I/O 设备看到。FENCE 有 8-bit 可以分别指定 memory read/write 与 I/O read/write 的各种组合顺序。透过这些组合，FENCE 可以保证存储器与 memory-mapped I/O 之间的运行顺序。比方说：其中一个组合是可以在不影响 I/O 运算的情况下，只保证存储器的读取和写入顺序。也就是说，如果 I/O 运算可以和存储器同时运行的话，FENCE 不会强迫他们之间要互相等待。单一 CPU 上面跑单一 thread 的情况下，可以把 FENCE 视作 NOP 指令。

如同许多的 RISC 指令集一样，RISC-V 并没有可以“写入多个寄存器”的寻址模式。比方说：不支持 auto-incrementing（像是 \*ptr++ 就无法使用一个指令完成，而必须拆解成“一个 load 指令”及“一个 addi 指令”。）

和其他类似成功的电脑一样，RISC-V 也是 little-endian。这稍稍降低了复杂度与成本，因为所有大小的读取，都遵循一样的顺序（注：例如 64-bit 与 128-bit 的读取，都是从最小的 word 开始读进来，只要一直 shift 就可以了）。举例来说，RISC-V 的指令集都是从最低的那个 byte 开始解码（注：opcode）。RISC-V 的规格书保留了实现 big-endian 的可能性。

有些 RISC CPUs（例如：MIPS, PowerPC, DLX, and Berkeley's RISC-I）在 Load/Save 指令当中使用 16-bit 位移。使用 load upper word 指令来设置最高的 16-bit。这让最高的 16-bit 资料可以很容易被设置，而不需要位移指令。然而，大部分使用 load upper word 的时机都是为了要加载一个常量（比如：地址）。RISC-V 则是使用类似 SPARC 12-bit 与 20-bit 的设计。而 RISC-V 所采用的 12-bit 设计，可以让指令更小。也就是说，这使得 32-bit 的 load/store 指令，就算需要在 32 个寄存器（需要 5-bit 寻址）当中选两个来用（一共 10-bit），还是有足够的 bit 数目来支持 RISC-V 的可变长度指令编码 (variable-length instruction coding)。

注：请参考 32-bit 的 I-type 指令格式，就会发现这个 12-bit 位移比 16-bit 来得优异的地方。这使得 32-bit 的空间当中，扣掉 12-bit 的常量值，以及最低的两个 bit 为 11（表示这是一个 32-bit 长的指令），再扣掉两个 5-bit 的寄存器地址，还有将近 8-bit 的空间可以留给 opcode 及 func3 。如果是使用 16-bit immediate 的话，会使得空间不够放下两个 5-bit 的寄存器地址。举例来说，SLLI Rd, Rs, immediate (Shift Left Logical Immediate) 将会被迫拆解成两个指令来完成：LDR Ri, immediate; SLLI Rd, Rs, Ri 。

### 立即数\[[编辑](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/w/index.php?title=RISC-V&action=edit&section=12 "编辑章节：立即数")\]

RISC-V 读取 32-bit 常量与地址是透过设置 upper 20-bit 的指令达到的。LUI 指令 (Load Upper Immediate) 把（指令中的）20-bit 读取到寄存器的 31~12 bits 当中。另一个 AUIPC 指令，也是一样读取 upper 20-bit，同时又加上 PC (Program Counter) 之后，存放到某个基底寄存器。这个指令让 PIC 程序（Position-Independent Code）能够支持“相对于代码位置的 32-bit 地址”。这个基底寄存器可以再搭配 12-bit 位移，使用在 Load 与 Store 指令当中（注：访问本地的 static 变量?)。如果需要的话，也可以使用 addi 指令，将 lower 12-bit 的常量加到一个寄存器中（注：这样就完成一个完整的 32-bit 常量读取）。在 64-bit 架构下，LUI 与 AUIPC 运行的结果会被比特扩展至 64-bit (sign-extent)。

有些高速的 CPU 会把一些指令“融合”成一个指令。比如说：上述的 LUI 与 AUIPC 就很适合和 Load/Save 指令一起融合。

### 函数调用、跳跃和分支\[[编辑](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/w/index.php?title=RISC-V&action=edit&section=13 "编辑章节：函数调用、跳跃和分支")\]

RISC-V 的函数调用 JAL (Jump and Link) 把回传地址放在一个寄存器当中。由于它省下了一次访问推叠存储器，所以在许多的设计当中是比较快速的。JAL 有一个 20-bit signed 位移。这个位移会被乘上 2 之后，加到 PC 当中。如果没有对齐到 32-bit 地址，CPU 会触发一个例外。

RISC-V 的 JALR (Jump and Link Register) 指令和 JAL 很像，但是他是把一个 12-bit 的相对位移，和某一个寄存器相加。（而 JAL 是用 20-bit 相加）

JALR 的指令格式有点像使用寄存器的 load/store 指令。搭配另一个设置高 20-bit 的基底寄存器，可以组成一个 32-bit 的地址（可以是绝对地址，例如 LUI; 或是相对于 PC 的地址，例如 AUIPC）。（使用零寄存器当基底寄存器，则是可以跳到 0 +- 2KB 的绝对地址）

透过使用零寄存器，底下两种无条件跳跃（其他组语中的 JUMP 或 JMP）：“20-bit PC 相对地址”以及“寄存器为底的 12-bit”，分别使用 JAL 与 JALR 两个指令来实现。在这个情况下，因为目的地寄存器是零存器，所以回传地址会被丢弃。

如同许多的 RISC 系统，在一个函数调用当中，RISC-V 编译器必须使用多个指令将寄存器一个一个地存到堆栈当中，然后在函数结束的时候，一个一个地将寄存器自堆栈中还原。RISC-V 没有“存储多个”或是“还原多个”寄存器的指令。因为这些指令被认为会让 CPU 变得复杂，而且可能更慢\[51\]。 然而 RISC-V 的这种设计，会增加程序大小。而设计者原本是希望透过一种特别的 routine 来减小程序（注：可以参考 [这份文件](https://content.riscv.org/wp-content/uploads/2016/06/riscv-spec-v2.1.pdf)（[页面存档备份](chrome-extension://web.archive.org/web/20190218015815/https://content.riscv.org/wp-content/uploads/2016/06/riscv-spec-v2.1.pdf)，存于[互联网档案馆](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/wiki/%E4%BA%92%E8%81%94%E7%BD%91%E6%A1%A3%E6%A1%88%E9%A6%86 "互联网档案馆")） 的 1.7 Optimizing Register Save/Restore Code Size）。

RISC-V 没有旗标寄存器（注：原文是 conditional code register，就是指传统的旗标寄存器 flag register，用以存放计算结果，给接下来的指令使用，例如：进位旗标 carry flag）。设计者相信旗标寄存器会让 CPU 设计更加复杂，因为它必须强迫了指令们在不同的运行阶段之间的交互作用。这样的设计，会使得高精度计算变得更复杂，有些数值计算需要更多的能量。

相反地，RISC-V 直接比较两个寄存器，操作数包括：相等，不相等，小于，无号数小于，大于，无号数大于。十个“比较跳跃”操作数，可以透过翻转顺序的方式，可以只用上述六个操作数实现出来。举例来说：“如果大于时跳跃”可以用“小于或等于时跳跃”来实现。

这六个比较跳跃有 12-bit 的有号位移，可以跳到 PC+-4KB 的范围内。

RISC-V 要求 CPU 实现“默认分支预测” (default branch prediction)。如果是往回跳跃 (例如： do {...} while (expr) 中的 expr 判断式），CPU 要预测跳跃会发生，也就是预测 expr “会”成立。如果是向前跳跃（例如：if (expr) {...} else {...} 中的 else 部分），CPU 预测这个跳跃会发生，也就是预测 expr “不会”成立。CPU 判断往回或向前的方法，是看指令中相对地址的最高比特，也就是有号数的部分 (signed bit)：如果是 1，表示是负数，要往回跳跃。如果是 0，表示是正数，要向前跳跃。当然，复杂的 CPU 实现也可以加入更多的分支预测。

RISC-V 手册也建议软件（如：编译器）利用默认分支预测的特性，来避免分支造成 pipeline 被停滞。方法就是利用上一段提到的 signed bit 来让“暗示” CPU 这个分支会不会发生。所以，就是算是简单又便宜的 CPU ，也可以透过编译器来优化性能。如果有需要，编译器也可以透过统计等方式来优化性能。

所以，为了避免不必要的分支预测电路（以及不必要的 pipeline 停滞），无条件跳跃不要用“比较分支”来实现。

RISC-V 并不支持“条件运行”指令（condition execution，注：当某个条件成立的时候，才运行该指令）。设计者宣称没有这种设计的 CPU 比较容易设计，而且编译器在进行优化的时候，也比较不容易假设错误。设计者宣称高速又不照顺序运行的 CPU 反正都会同时运行正反两种结果，之后再丢弃其中一个。他们也宣称，即使在简单的 CPU 当中，条件运行其实是比较没有价值的，不如跳跃预测来的有用。不使用条件运行的代码会比较大，但是他们宣称压缩指令集在大部分的情况下，可以解决这样的问题。

许多的 RISC 设计都有“分支延迟槽”（branch delay slot），用来充份使用跳跃指令的下一个存储器地址，这可以略略增加整体的 CPU 性能。RSIV-V 并不支持这个功能，因为他会让多时序，超标量，以及 long pipeline 变得很复杂。而动态分支预测其实已经做得很好，可以不需要这个功能了。

### 算术和逻辑集\[[编辑](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/w/index.php?title=RISC-V&action=edit&section=14 "编辑章节：算术和逻辑集")\]

RISC-V 把数学运算指令归类到一个很小的 I 子集当中，包括：加法，减法，位移，位操作，及比较跳跃。这些可以使用软件的方式去模拟其他大部分的 RISC-V 指令（atomic 运算是值得一提的例外）。RISC-V 目前没有“数开头有几个零”以及一些用来加速软件浮点运算的位操作。

整数乘法子集（M 子集）包括：有号数与无号数的乘法与除法。

浮点子集包括单精度运算，以及类似于整数的“比较跳跃”。它需要额外的 32 个浮点寄存器，这些是与整数寄存器分开的。双精度浮点子集一般假设浮点寄存器是 64 比特，而且会与 F 子集一起协作。RISC-V 亦有定义四精度 128-bit 浮点指令。没有支持硬件浮点指令的 CPU，依旧可以使用软件的浮点程序库。

RISC-V 在遇到运算错误的时候，并不会发出例外，包括：overflow, underflow, subnormal 及 divide by zero。相反的，整数运算和浮点运算都会产生合理的默认数值，然后设置状态比特。Divide-by-zero 可以用一个跳跃指令来处理。这些状态比特可以也可以被操作系统或是定期的中断检查到。

### 原子内存操作\[[编辑](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/w/index.php?title=RISC-V&action=edit&section=15 "编辑章节：原子内存操作")\]

RISC-V 支持多个 CPU 与 thread。其标准存储器同步模式是“释放一致”原则。也就是说，读取和写入顺序可以重排，但是有些读取可以被设置成“获取”运算，会在其后的访问之前被运行，有些写入可以被当作“释放”运算，必须在其之前的访问的后面运行。

基本指令当中包含了最少的支持，使用 fence 指令来保证存储器访问顺序。尽管这很简单（fence r/rw 提供“获取”，fence rw/w 提供“释放”），组合起来还是可以很有效率。

RISC-V处理器\[[编辑](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/w/index.php?title=RISC-V&action=edit&section=16 "编辑章节：RISC-V处理器")\]
---------------------------------------------------------------------------------------------------------------------------------------

### 商业实现\[[编辑](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/w/index.php?title=RISC-V&action=edit&section=17 "编辑章节：商业实现")\]

[阿里巴巴](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/wiki/%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E9%9B%86%E5%9B%A2 "阿里巴巴集团")旗下半导体公司平头哥发布了它的首款 RISC-V 处理器玄铁 910（XuanTie910），名字取自[金庸](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/wiki/%E9%87%91%E5%BA%B8 "金庸")小说《[神雕侠侣](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/wiki/%E7%A5%9E%E9%9B%95%E4%BE%A0%E4%BE%A3 "神雕侠侣")》。阿里巴巴称它是目前性能最强的 RISC-V 处理器，支持16核，主频 2.5GHz，单核性能达到 7.1 Coremark/MHz。阿里巴巴称其性能突破源自两大创新：一是它采用3发射8执行的复杂乱序执行架构，是业界首个实现每周期 2 条内存访问的 RISC-V 处理器；二是它基于 RISC-V 扩展了 50 余条指令，系统性增强了 RISC-V 的计算、存储和多核等方面能力。[\[22\]](#cite_note-23)

### 开源实现\[[编辑](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/w/index.php?title=RISC-V&action=edit&section=18 "编辑章节：开源实现")\]

[中国科学院](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/wiki/%E4%B8%AD%E5%9C%8B%E7%A7%91%E5%AD%B8%E9%99%A2 "中国科学院")计算所在2020年发布“香山”高性能RISC-V处理器开源项目，香山以Chisel[硬件描述语言](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/wiki/%E7%A1%AC%E4%BB%B6%E6%8F%8F%E8%BF%B0%E8%AF%AD%E8%A8%80 "硬件描述语言")开发。[\[23\]](#cite_note-24) [\[24\]](#cite_note-25) 第一版“雁栖湖架构”使用[台积电](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/wiki/%E5%8F%B0%E7%A9%8D%E9%9B%BB "台积电")的28nm制程，工作频率为1.3GHz。[\[25\]](#cite_note-26)

参见\[[编辑](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/w/index.php?title=RISC-V&action=edit&section=19 "编辑章节：参见")\]
-------------------------------------------------------------------------------------------------------------------------

*   [精简指令集](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/wiki/%E7%B2%BE%E7%AE%80%E6%8C%87%E4%BB%A4%E9%9B%86 "精简指令集") (RISC)
*   [OpenRISC](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/w/index.php?title=OpenRISC&action=edit&redlink=1 "OpenRISC（页面不存在）")，以[GNU General Public License](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/wiki/GNU%E9%80%9A%E7%94%A8%E5%85%AC%E5%85%B1%E8%AE%B8%E5%8F%AF%E8%AF%81 "GNU通用公共许可证")授权
*   [OVPsim](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/w/index.php?title=OVPsim&action=edit&redlink=1 "OVPsim（页面不存在）")，RISC-V处理器指令子集、内核和系统的指令精确模拟器。免费为非商业用途提供。
*   [ARM架构](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/wiki/ARM%E6%9E%B6%E6%A7%8B "ARM架构")
*   [开源运算硬件列表](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/w/index.php?title=%E5%BC%80%E6%BA%90%E8%BF%90%E7%AE%97%E7%A1%AC%E4%BB%B6%E5%88%97%E8%A1%A8&action=edit&redlink=1)

参考资料\[[编辑](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/w/index.php?title=RISC-V&action=edit&section=20 "编辑章节：参考资料")\]
-----------------------------------------------------------------------------------------------------------------------------

1.  **[^](#cite_ref-1 "跳转")** RISC-V讀卡器：開放式架構地圖集第1期 1st. Strawberry Canyon. [ISBN 978-0999249109](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/wiki/Special:%E7%BD%91%E7%BB%9C%E4%B9%A6%E6%BA%90/978-0999249109 "Special:网络书源/978-0999249109").)
2.  ^ [跳转至： **2.0**](#cite_ref-si2019_2-0) [**2.1**](#cite_ref-si2019_2-1) [**2.2**](#cite_ref-si2019_2-2) [**2.3**](#cite_ref-si2019_2-3) [新浪-图灵奖得主加入清华，牵头推动芯片开源](https://t.cj.sina.com.cn/articles/view/5703921756/153faf05c01900gt8p)
3.  ^ [跳转至： **3.0**](#cite_ref-sodor_3-0) [**3.1**](#cite_ref-sodor_3-1) Celio, Christopher. [ucb-bar/riscv-sodor](https://github.com/ucb-bar/riscv-sodor). Regents of the University of California. \[12 February 2015\]. （原始内容[存档](https://web.archive.org/web/20180611023547/https://github.com/ucb-bar/riscv-sodor)于2018-06-11）.
4.  **[^](#cite_ref-boom_4-0 "跳转")** Celio, Christopher. [CS 152 Laboratory Exercise 3](https://web.archive.org/web/20160623234620/http://www-inst.eecs.berkeley.edu/~cs152/sp14/handouts/lab3.pdf) (PDF). Regents of the University of California. \[12 February 2015\]. （[原始内容](http://www-inst.eecs.berkeley.edu/~cs152/sp14/handouts/lab3.pdf) (PDF)存档于2016-06-23）.
5.  **[^](#cite_ref-5 "跳转")** [詳細了解ARM許可芯片的方法：第1部分](https://web.archive.org/web/20170824175657/https://semiaccurate.com/2013/08/07/a-long-look-at-how-arm-licenses-chips/). SemiAccurate. 2013 \[2017-08-28\]. （[原始内容](http://semiaccurate.com/2013/08/07/a-long-look-at-how-arm-licenses-chips)存档于2017-08-24）.
6.  **[^](#cite_ref-riscstart_6-0 "跳转")** [精簡指令集計算機的案例](http://dl.acm.org/citation.cfm?id=641917). ACM SIGARCH计算机体系结构新闻. 1980年10月, **8** (6): 25. [doi:10.1145/641914.641917](https://dx.doi.org/10.1145%2F641914.641917).
7.  **[^](#cite_ref-7 "跳转")** [RSIC-V開源CPU殺出](https://technews.tw/2018/11/16/sifive-7-series-cpu-ip-vs-arm/). \[2019-06-15\]. （原始内容[存档](https://web.archive.org/web/20181121041858/http://technews.tw/2018/11/16/sifive-7-series-cpu-ip-vs-arm/)于2018-11-21）.
8.  **[^](#cite_ref-8 "跳转")** [https://riscv.org/members/](https://riscv.org/members/). \[2021-05-01\]. （原始内容[存档](https://web.archive.org/web/20210426212215/https://riscv.org/members/)于2021-04-26）.
9.  ^ [跳转至： **9.0**](#cite_ref-isasbefree_9-0) [**9.1**](#cite_ref-isasbefree_9-1) Krste Asanović, David A. Patterson. [Instruction Sets Should Be Free: The Case For RISC-V](https://www2.eecs.berkeley.edu/Pubs/TechRpts/2014/EECS-2014-146.pdf) (PDF). U.C. Berkeley Technical Reports. \[2018-10-31\]. （原始内容[存档](https://web.archive.org/web/20190423083613/https://www2.eecs.berkeley.edu/Pubs/TechRpts/2014/EECS-2014-146.pdf) (PDF)于2019-04-23）.
10.  ^ [跳转至： **10.0**](#cite_ref-isa_10-0) [**10.1**](#cite_ref-isa_10-1) [**10.2**](#cite_ref-isa_10-2) [**10.3**](#cite_ref-isa_10-3) Waterman, Andrew; Asanović, Krste. [The RISC-V Instruction Set Manual, Volume I: Base User-Level ISA version 2.2](https://riscv.org/specifications/). University of California, Berkeley. \[25 May 2017\]. EECS-2016-118. （原始内容[存档](https://web.archive.org/web/20170828103102/https://riscv.org/specifications/)于2017-08-28）.
11.  ^ [跳转至： **11.0**](#cite_ref-isapriv_11-0) [**11.1**](#cite_ref-isapriv_11-1) [**11.2**](#cite_ref-isapriv_11-2) Waterman, Andrew; Lee, Yunsup; Avizienas, Rimas; Patterson, David; Asanovic, Krste. [Draft Privileged ISA Specification 1.9](https://web.archive.org/web/20180826095957/https://riscv.org/specifications/privileged-isa/). RISC-V. RISC-V Foundation. \[30 August 2016\]. （[原始内容](https://riscv.org/specifications/privileged-isa/)存档于2018-08-26）.
12.  **[^](#cite_ref-boom-github_12-0 "跳转")** Celio, Christopher. [riscv-boom](https://github.com/ucb-bar/riscv-boom/). GitHub. Regents of the University of California. \[11 November 2016\].
13.  **[^](#cite_ref-rocket-chip-github_13-0 "跳转")** Asanovic, Krste; 等. [rocket-chip](https://github.com/ucb-bar/rocket-chip). GitHub. The RISC-V Foundation. \[11 November 2016\].
14.  **[^](#cite_ref-pulpino_14-0 "跳转")** Traber, Andreas; 等. [PULP:Parallel Ultra Low Power](https://www.pulp-platform.org/). ETH Zurich, University of Bologna. \[5 August 2016\].
15.  **[^](#cite_ref-freebsdriscv_15-0 "跳转")** [FreeBSD Wiki: RISC-V](https://wiki.freebsd.org/riscv).
16.  **[^](#cite_ref-freebsdriscv-committed_16-0 "跳转")** [FreeBSD Foundation: Initial FreeBSD RISC-V Architecture Port Committed](https://freebsdfoundation.blogspot.be/2016/02/initial-freebsd-risc-v-architecture.html).
17.  **[^](#cite_ref-riscv-debian-port_17-0 "跳转")** Montezelo, Manuel. [Debian GNU/Linux port for RISC-V 64](https://groups.google.com/a/groups.riscv.org/forum/#!msg/sw-dev/u4VcUtB9r94/4HiFYBhXAAAJ). Google Groups. Google. \[19 July 2018\]. （原始内容[存档](https://web.archive.org/web/20181112180034/https://groups.google.com/a/groups.riscv.org/forum/#!msg/sw-dev/u4VcUtB9r94/4HiFYBhXAAAJ)于2018-11-12）.
18.  **[^](#cite_ref-riscv-fedora-port_18-0 "跳转")** [Architectures/RISC-V](https://fedoraproject.org/wiki/Architectures/RISC-V). Fedora WIKI. Red Hat. \[26 September 2016\]. （原始内容[存档](https://web.archive.org/web/20210124044605/https://fedoraproject.org/wiki/Architectures/RISC-V)于2021-01-24）.
19.  **[^](#cite_ref-19 "跳转")** Begari, Padmarao. [U-Boot port on RISC-V 32-bit is available](https://groups.google.com/a/groups.riscv.org/forum/#!topic/sw-dev/j63wzz2ylY8). Google Groups. Microsemi. \[15 February 2017\]. （原始内容[存档](https://web.archive.org/web/20181112180034/https://groups.google.com/a/groups.riscv.org/forum/#!topic/sw-dev/j63wzz2ylY8)于2018-11-12）.
20.  **[^](#cite_ref-riscv-sel4-port_20-0 "跳转")** Almatary, Hesham. [RISC-V, seL4](https://docs.sel4.systems/Hardware/RISCV.html). seL4 Documentation. CSIRO. \[13 July 2018\].
21.  **[^](#cite_ref-riscv-angel-jsport_21-0 "跳转")** [riscv-angel](https://web.archive.org/web/20181111215351/https://riscv.org/software-tools/riscv-angel/). The RISC-V Foundation. \[2018-11-11\]. （[原始内容](https://riscv.org/software-tools/riscv-angel/)存档于2018-11-11）.
22.  **[^](#cite_ref-23 "跳转")** [阿里巴巴发布首款 RISC-V 处理器](https://www.solidot.org/story?sid=61487). 科技行者. \[2019-07-25\]. （原始内容[存档](https://web.archive.org/web/20190725102020/https://www.solidot.org/story?sid=61487)于2019-07-25）.
23.  **[^](#cite_ref-24 "跳转")** [香山开源项目](https://github.com/OpenXiangShan/XiangShan)
24.  **[^](#cite_ref-25 "跳转")** [Chinese chip designers hope to topple Arm's Cortex-A76 with XiangShan RISC-V design](https://www.theregister.com/2021/07/06/xiangshan_risc_v/)
25.  **[^](#cite_ref-26 "跳转")** [香山：开源高性能RISC-V处理器](https://raw.githubusercontent.com/OpenXiangShan/XiangShan-doc/main/slides/20210622-RVWC-%E9%A6%99%E5%B1%B1%E5%BC%80%E6%BA%90%E9%AB%98%E6%80%A7%E8%83%BDRISC-V%E5%A4%84%E7%90%86%E5%99%A8.pdf)

拓展阅读\[[编辑](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/w/index.php?title=RISC-V&action=edit&section=21 "编辑章节：拓展阅读")\]
-----------------------------------------------------------------------------------------------------------------------------

*   [The RISC-V Instruction Set Manual](http://www.eecs.berkeley.edu/Pubs/TechRpts/2016/EECS-2016-118.pdf)（[页面存档备份](chrome-extension://web.archive.org/web/20171021160947/http://www.eecs.berkeley.edu/Pubs/TechRpts/2016/EECS-2016-118.pdf)，存于[互联网档案馆](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/wiki/%E4%BA%92%E8%81%94%E7%BD%91%E6%A1%A3%E6%A1%88%E9%A6%86 "互联网档案馆")）
*   [Instruction Sets Should Be Free: The Case For RISC-V](http://www.eecs.berkeley.edu/Pubs/TechRpts/2014/EECS-2014-146.html)（[页面存档备份](chrome-extension://web.archive.org/web/20160304045606/http://www.eecs.berkeley.edu/Pubs/TechRpts/2014/EECS-2014-146.html)，存于[互联网档案馆](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/wiki/%E4%BA%92%E8%81%94%E7%BD%91%E6%A1%A3%E6%A1%88%E9%A6%86 "互联网档案馆")） Whitepaper by Krste Asanović and [David A. Patterson](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/wiki/%E5%A4%A7%E8%A1%9B%C2%B7%E5%B8%95%E7%89%B9%E6%A3%AE_(%E5%AD%B8%E8%80%85) "大卫·帕特森 (学者)")
*   [The RISC-V Instruction Set](http://www.hotchips.org/wp-content/uploads/hc_archives/hc25/HC25-posters/HC25.26.p70-RISC-V-Warterman-UCB.pdf)（[页面存档备份](chrome-extension://web.archive.org/web/20170506031542/http://www.hotchips.org/wp-content/uploads/hc_archives/hc25/HC25-posters/HC25.26.p70-RISC-V-Warterman-UCB.pdf)，存于[互联网档案馆](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/wiki/%E4%BA%92%E8%81%94%E7%BD%91%E6%A1%A3%E6%A1%88%E9%A6%86 "互联网档案馆")） HotChips 25 (2013)
*   [The RISC-V Software Ecosystem](http://riscv.org/wp-content/uploads/2015/02/riscv-software-toolchain-tutorial-hpca2015.pdf)（[页面存档备份](chrome-extension://web.archive.org/web/20160331183131/http://riscv.org/wp-content/uploads/2015/02/riscv-software-toolchain-tutorial-hpca2015.pdf)，存于[互联网档案馆](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/wiki/%E4%BA%92%E8%81%94%E7%BD%91%E6%A1%A3%E6%A1%88%E9%A6%86 "互联网档案馆")） HPCA 2015, Tutorial
*   [Rocket Chip](http://riscv.org/wp-content/uploads/2015/02/riscv-rocket-chip-generator-tutorial-hpca2015.pdf)（[页面存档备份](chrome-extension://web.archive.org/web/20160331183104/http://riscv.org/wp-content/uploads/2015/02/riscv-rocket-chip-generator-tutorial-hpca2015.pdf)，存于[互联网档案馆](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/wiki/%E4%BA%92%E8%81%94%E7%BD%91%E6%A1%A3%E6%A1%88%E9%A6%86 "互联网档案馆")） HPCA 2015, Tutorial
*   [The RISC-V Compressed Instruction Set Manual Version 1.9 (draft)](https://riscv.org/wp-content/uploads/2015/11/riscv-compressed-spec-v1.9.pdf)（[页面存档备份](chrome-extension://web.archive.org/web/20161108041353/https://riscv.org/wp-content/uploads/2015/11/riscv-compressed-spec-v1.9.pdf)，存于[互联网档案馆](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/wiki/%E4%BA%92%E8%81%94%E7%BD%91%E6%A1%A3%E6%A1%88%E9%A6%86 "互联网档案馆")）

外部链接\[[编辑](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/w/index.php?title=RISC-V&action=edit&section=22 "编辑章节：外部链接")\]
-----------------------------------------------------------------------------------------------------------------------------

*   [官方网站](https://riscv.org/) [![在维基数据上编辑此内容](chrome-extension://upload.wikimedia.org/wikipedia/commons/thumb/8/8a/OOjs_UI_icon_edit-ltr-progressive.svg/10px-OOjs_UI_icon_edit-ltr-progressive.svg.png)](https://www.wikidata.org/wiki/Q17637401#P856 "在维基数据上编辑此内容")
*   [GitHub](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/wiki/GitHub "GitHub")上的[UCB's site for RISC-V](https://github.com/ucb-bar)
*   [RISC-V: An Open Standard for SoCs. The case for an open ISA](https://web.archive.org/web/20170824093026/http://www.eetimes.com/author.asp?doc_id=1323406). EETimes. 8 July 2014 \[2017-08-28\]. （[原始内容](http://www.eetimes.com/author.asp?doc_id=1323406)存档于2017-08-24）.
*   [Pulpino](https://web.archive.org/web/20170824094526/http://www.pulp-platform.org/): A developed, open-source system-on-chip based on RISC-V, 4 August 2016
*   Hruska, Joel. [RISC rides again: New RISC-V architecture hopes to battle ARM and x86 by being totally open source](https://web.archive.org/web/20170824093721/http://www.extremetech.com/computing/188405-risc-rides-again-new-risc-v-architecture-hopes-to-battle-arm-and-x86-by-being-totally-open-source). ExtremeTech. 21 August 2014 \[2017-08-28\]. （[原始内容](http://www.extremetech.com/computing/188405-risc-rides-again-new-risc-v-architecture-hopes-to-battle-arm-and-x86-by-being-totally-open-source)存档于2017-08-24）.
*   [Analyzing the RISC-V Instruction Set Architecture](https://web.archive.org/web/20170804193133/http://www.adapteva.com/andreas-blog/analyzing-the-risc-v-instruction-set-architecture/). [Adapteva](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/w/index.php?title=Adapteva&action=edit&redlink=1 "Adapteva（页面不存在）"). 11 August 2014 \[2017-08-28\]. （[原始内容](http://www.adapteva.com/andreas-blog/analyzing-the-risc-v-instruction-set-architecture/)存档于2017-08-04）.
*   [YouTube上的RISC-V频道](https://www.youtube.com/channel/UC5gLmcFuvdGbajs4VL-WU3g)
*   [search: RISC-V since 2013](https://scholar.google.com.au/scholar?q=%22RISC-V%22&btnG=&hl=en&as_sdt=0%2C5&as_ylo=2013). Google Scholar.\[[失效链接](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/wiki/Wikipedia:%E5%A4%B1%E6%95%88%E9%93%BE%E6%8E%A5 "Wikipedia:失效链接")\]

| \[[显示](#)\]
*   [查](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/wiki/Template:RISC_architectures "Template:RISC architectures")
*   [论](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/wiki/Template_talk:RISC_architectures "Template talk:RISC architectures")
*   [编](https://zh.wikipedia.org/w/index.php?title=Template:RISC_architectures&action=edit)

[精简指令集](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/wiki/%E7%B2%BE%E7%AE%80%E6%8C%87%E4%BB%A4%E9%9B%86%E8%AE%A1%E7%AE%97%E6%9C%BA "精简指令集计算机")



 |
| --- |

| \[[显示](#)\]
*   [查](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/wiki/Template:Microcontrollers "Template:Microcontrollers")
*   [论](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/wiki/Template_talk:Microcontrollers "Template talk:Microcontrollers")
*   [编](https://zh.wikipedia.org/w/index.php?title=Template:Microcontrollers&action=edit)

[单片机](chrome-extension://cjedbglnccaioiolemnfhjncicchinao/wiki/%E5%8D%95%E7%89%87%E6%9C%BA "单片机")



 |
| --- |


[Source](https://zh.wikipedia.org/wiki/RISC-V)