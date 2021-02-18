# RV与芯片评论.20210206.第6周(总第28期)




---

<a name="7NzFL"></a>
## 重点聚焦
<a name="4Ys76"></a>
##### 2月8日，芯来在B站做了直播


<a name="tQhG8"></a>
##### RV64X开源
"[RISC—V助力开源GPU发展 ](http://news.moore.ren/industry/264655.htm
)(From news.moore.ren 2021.02.08)"
>    - RV64X项目, 开发64位通用ISA，由Pixilica的Atif Zafar，GOWIN Semiconductor的Grant Jennings和CHIPS Alliance and Western Digital的Ted Marena领导。
>    - 该小组提出了一种RV32X参考实现，该实现具有hardware texture单元、特殊功能单元、32KB L1缓存、8K uCode SRAM缓存和四个32位dsp / alu(可以处理FP32和INT32数据)。参考设计将很可能使用FPGA实现。
>    - 其图形处理器将以微代码实现标准图形流水线，但也将能够添加自定义光栅化器（样条，SubDiv表面，补丁）和自定义流水线阶段，以支持商用GPU设计不支持的功能。
>    - "[里程碑，RISC-V扩展到GPU应用 ](https://www.cnbeta.com/articles/tech/1086161.htm
)(From www.cnbeta.com 2021.02.10)"
>    - "[RV64X：开源GPU来了，这次靠谱吗？ ](https://zhuanlan.zhihu.com/p/349060389
)(From zhuanlan.zhihu.com 2021.02.18)"



<a name="VoXVb"></a>
#### 相关周报

- ![image.png](https://cdn.nlark.com/yuque/0/2020/png/1541992/1599307696075-3f44fb1b-f362-4130-a254-b3e4fb6cebac.png#align=left&display=inline&height=24&margin=%5Bobject%20Object%5D&name=image.png&originHeight=84&originWidth=89&size=7408&status=done&style=none&width=25)[semi engineering](https://semiengineering.com/) Week In Review: 
   - Blog Review：
   - Design, Low Power：
   - Manufacturing, Test：
   - Auto, Security, Pervasive Computing：
- IoT News：（[Site](https://staceyoniot.com/)）：
- OSDT Weekly：([zhihu](https://www.zhihu.com/column/c_1252285504848613376)，[Github](https://github.com/hellogcc/osdt-weekly/tree/master/weekly))：[2021-02-03 第083期](https://github.com/hellogcc/osdt-weekly/blob/master/weekly/2021-02-03.md
)
- 泰晓咨询：（[Site](http://tinylab.org/)）：
- PLCT开源进展：([Github](https://github.com/isrc-cas/PLCT-Weekly)，[zhihu](https://www.zhihu.com/column/plct-lab)）：[第18期·2021年02月01日](https://zhuanlan.zhihu.com/p/348645912
)
- RT-Thread：（[oschina](https://my.oschina.net/u/4428324)）：[【20210205期AI简报】联发科发布二代5G基带芯片发布、超强镜像优化从1.16GB到22.4MB！ ](https://my.oschina.net/u/4428324/blog/4949238
)
- 科技爱好者周刊：（[yuque](https://www.yuque.com/ruanyf/weekly)）：
- "[RISC-V双周报1月27日-2月9日 ](https://www.rvmcu.com/article-show-id-557.html
)(From www.rvmcu.com 2021.02.18)"

---



<a name="gxOhD"></a>
## 技术动态
<br />
<a name="gHqP6"></a>
#### 一周问答

- "[WCH-Link不能使用，请大师指导  ](https://bbs.21ic.com/icview-3069212-1-1.html
)(From bbs.21ic.com 2021.02.09)"
- "[不是说swd是arm专有的吗？，为何沁恒的riscv单片机可以支持？](https://whycan.com/t_5968_2.html)(From whycan.com 2021.02.09)"
>    - 沁恒官方的说法是和ARM的SWD协议不是一个东西（在datasheet里面被称为RVSWD），相当于只是借用了SWD的名字（串行调试线）而已。
>    - 另外，沁恒官方提供的调试器可以同时兼容SWD和RVSWD两种协议（需要切换工作状态），目测是在CMSIS-DAP上加了一些私有协议。

- "[大家怎么看RISC-V? ](https://www.zhihu.com/question/442373688
)(From www.zhihu.com 2021.02.18)"
- "[目前支持RISC-V的操作系统有哪些？ ](https://www.zhihu.com/question/442997301
)(From www.zhihu.com 2021.02.18)"
<a name="an5uU"></a>
#### 社区动态

- "[大家怎么看RISC-V? ](https://www.zhihu.com/question/442373688
)(From www.zhihu.com 2021.02.09)"

---

<a name="RLWsL"></a>
## 产业风云
"[5G基站芯片的新竞争 ](https://finance.sina.com.cn/stock/hkstock/hkstocknews/2021-02-02/doc-ikftssap2433677.shtml
)(From finance.sina.com.cn 2021.02.09)"
>    - 前高通(QCOM.US)首席执行官Paul Jacobs和高通前首席技术官Matt Grob加入了5G蜂窝创业公司EdgeQ，担任其顾问委员会成员
>    - EdgeQ计划通过使用和扩展开放式硬件RISC-V设计，将5G蜂窝基站的总体拥有成本(TCO)降低一半，该方法也是有效地划分传统的封闭式芯片方法与Open RAN之间的差异。
>    - "[RISC-V加持O-RAN 功耗成本可望减半 ](https://std.stheadline.com/sc/kol/article/2431/%E5%89%B5%E7%A7%91%E7%94%9F%E6%B4%BB-%E5%89%B5%E7%A7%91%E5%BB%A3%E5%A0%B4-RISC-V%E5%8A%A0%E6%8C%81O-RAN-%E5%8A%9F%E8%80%97%E6%88%90%E6%9C%AC%E5%8F%AF%E6%9C%9B%E6%B8%9B%E5%8D%8A
)(From std.stheadline.com 2021.02.09)"

"[30家国产AI芯片厂商调研分析报告 ](https://www.eet-china.com/news/202101251234.html
)(From www.eet-china.com 2021.02.09)"
>    - Aspencore《电子工程专辑》分析师团队对中国本土的AI芯片设计公司进行了第一手调查和网络汇编整理，从众多AI芯片设计厂商中挑选30家，从核心技术、代表产品、典型应用场景等多个维度进行了分析。这是China Fabless系列调研分析报告的一部分
>    - "[一 ](https://www.eet-china.com/news/202101251234.html
)(From www.eet-china.com 2021.02.09)"
>    - "[二 ](https://www.eet-china.com/news/202102020909.html
)(From www.eet-china.com 2021.02.09)"

"[美的“造芯”新进展！在重庆成立一家半导体公司 ](https://www.leiphone.com/news/202102/LCFskigxfN0TMVHF.html
)(From www.leiphone.com 2021.02.09)"
>    - 1月26日，美的集团和佛山市美的空调工业投资有限公司共同投资成立了一家半导体公司，并命名为美垦半导体。
>    - 美的最早于2010年成立（IPM）项目组，两年后研制出全国第一款IMS架构的IPM，并在2013年率先实现了国产自研IPM的量产。

"[格兰仕用“芯”站上“智”高点 ](https://finance.sina.com.cn/tech/2021-02-05/doc-ikftpnny4740419.shtml
)(From finance.sina.com.cn 2021.02.18)"<br />"[晶心科技AX25 RISC-V CPU核心获SK Telecom采用 ](http://www.eetrend.com/article/2021-02/100411439.html
)(From www.eetrend.com 2021.02.09)"<br />"[晶心科技宣布AndesCore™ RISC-V处理器核心获EdgeQ采用 为5G开放式无线电存取网路打造整合AI的5G晶片平台 ](https://www.21ic.com/article/887031.html
)(From www.21ic.com 2021.02.18)"<br />"[2021年十大“增长最快”IC排名预测，DRAM连续两年进入榜首 ](https://www.ednchina.com/news/6369.html
)(From www.ednchina.com 2021.02.18)"
>    - 2020年IC Insights发布了2020年版的《McClean报告》。
>    - 对IC产业的新分析和预测包括IC Insights在2020年对世界半导体贸易统计（WSTS）组织定义的33种IC产品类别中每一种的销售增长率的排名。2019年，NAND闪存和DRAM是所有IC产品类别中增长率最低的两个，但预计2020年成为两个最大的IC销售类别。现在，IC Insights的分析再次预测2021年DRAM的增长将跃居榜首。

<a name="us08D"></a>
#### 评论文集

- "[RISC-V芯片的出货量怎么都10亿了？ ](https://mp.ofweek.com/ee/a756714870137
)(From mp.ofweek.com 2021.02.09)"
- "[国产EDA/IP的开源和生态——从ICCAD 2020年会看中国半导体产业发展趋势 ](https://www.eet-china.com/news/210211.html
)(From www.eet-china.com 2021.02.18)".
>    - EDA和IP处于半导体产业链的最前端，也是技术和价值含量最高的环节，EDA和IP的发展水平代表着一个国家在半导体领域的“软实力”。 而开源模式和生态发展将是本土EDA/IP供应商把握机遇，快速发展的有效途径。


---



<a name="CVPaP"></a>
## 其他动态


<a name="xfDo7"></a>
#### 博文推荐

- [宋宝华](https://blog.csdn.net/21cnbao)："[RISC-V架构系列之1：指令集和特权模式 ](https://blog.csdn.net/21cnbao/article/details/113449603
)(From blog.csdn.net 2021.02.08)"
- "[Risc-V 内核 ](https://blog.csdn.net/zhuimeng_ruili/article/details/113487904
)(From blog.csdn.net 2021.02.08)"
- "[【RISC-V MCU CH32V103测评】PWM调节LED灯 ](http://bbs.eeworld.com.cn/thread-1156180-1-1.html
)(From bbs.eeworld.com.cn 2021.02.09)"
- "[【RISC-V MCU CH32V103测评】 ---前进的维子---写U盘文件 ](http://bbs.eeworld.com.cn/thread-1156217-1-1.html
)(From bbs.eeworld.com.cn 2021.02.09)"
- "[【RISC-V MCU CH32V103测评】+ 读取DH11 ](http://bbs.eeworld.com.cn/thread-1156184-1-1.html
)(From bbs.eeworld.com.cn 2021.02.09)"
- "[【RISC-V MCU CH32V103测评】- 3：USART - 为什么试了三个串口工具都不行？ ](http://bbs.eeworld.com.cn/thread-1156176-1-1.html
)(From bbs.eeworld.com.cn 2021.02.09)"
- "[【RISC-V MCU CH32V103测评】四、看一下温度+对RISC-V的看法 ](http://bbs.eeworld.com.cn/thread-1156226-1-1.html
)(From bbs.eeworld.com.cn 2021.02.09)"
- "[【RISC-V MCU CH32V103测评】SPI的测试  ](http://bbs.eeworld.com.cn/thread-1156664-1-1.html
)(From bbs.eeworld.com.cn 2021.02.18)"
- "[使用 Rust 创建一个模拟器 ](https://rustcc.cn/article?id=192ba514-12d0-4966-a42c-7806e7f2f990
)(From rustcc.cn 2021.02.09)"
- [老萧](https://www.zhihu.com/people/xiao-bang-95)："[RISC-V 的下个十年（上） ](https://zhuanlan.zhihu.com/p/347400101
)，[（下）](https://zhuanlan.zhihu.com/p/349397331
)
>    - 和大家分享由 Krste Asanović 教授在2020年的 RISC-V 峰会上的一篇演讲。Krste Asanović 教授（一下简称 Krste）是著名的计算机架构科学家，现担任美国加州伯克利大学的教授和 RISC-V 基金会董事会主席。
>    - 第一个部分主要对计算机体系结构做了回顾和展望，并预测了在该领域未来十年可能会出现的新的机遇与挑战；第二部分主要讨论了 RISC-V 会以怎样的策略，来应对这些机遇和挑战，也是整个演讲中最精彩的部分。

"[自制CPU系列（二）：木心处理器需求设计 ](https://zhuanlan.zhihu.com/p/345379213
)(From zhuanlan.zhihu.com 2021.02.18)"

---

<a name="MyRXD"></a>
## 一周论文<br />
<a name="KyvIx"></a>
### 架构改进
<a name="8YiKc"></a>
#### [Architectural Supports for Block Ciphers in a RISC CPU Core by Instruction Overloading](https://www.computer.org/csdl/journal/tc/5555/01/09319522/1qiRRDsOtHi)
P Choi, W Kong, JH Kim, MK Lee, DK Kim - IEEE Transactions on Computers, 2021
> 我们提出了一种新颖的计算机架构概念，即指令重载，以支持块密码。我们不是增加新的指令，而是只扩展一些现有指令的执行。所提出的方法允许中央处理单元核心根据数据的地址，对同一指令执行不同的操作，类似于面向对象语言中的运算符重载。我们首先提出了AES算法的扩展，然后我们用两个支持多块密码和硬件掩码的进一步扩展来证明其增强的适用性。AES的第一个扩展也适用于基于添加/AND-旋转-XOR的块密码，如SIMON。在这个扩展核心上，AES和SIMON的加密速度，至少提高了一倍，而且受内存延迟的影响也大大降低。此外，AES加密代码所需的内存仅为之前软件实现的18%。第二种扩展可以进一步支持在GF(2&lt;sup&gt;8&lt;/sup&gt;)上定义的各种块密码，SM4加密速度至少提高了182%。第三种扩展提供了抗相关权力分析(CPA)，面积开销为66.6%，但几乎没有速度开销，而典型的抗CPA AES软件实现至少需要数百倍的执行时间。

<a name="XEh4U"></a>
#### [SIMDify: Framework for SIMD-Processing with RISC-V Scalar Instruction Set](https://dl.acm.org/doi/abs/10.1145/3437378.3444364)
MA Sarkisla, A Yurdakul - 2021 Australasian Computer Science Week …, 2021
> 在这项工作中，我们提出了一个并行编程框架SIMDify，它可以生成单指令-多数据（SIMD）处理器，在不使用SIMD指令的情况下实现SIMD处理。SIMDify将一个为标量RISC-V ISA编译的应用机代码进行仿真，确定SIMD处理区域。然后，SIMDify配置并生成特定应用的SIMD处理器，在SIMD数据路径上并发执行标量RISC-V指令。SIMD处理器由一个主站和多个从站处理元件（PE）组成。从机专注于SIMD级任务，而主机则负责中央控制。所提出的架构是第一个用HLS设计的具有SIMD功能的RISC-V处理器，并且能够以比现有的SISD RISC-V HLS内核更快的时钟频率工作。SIMDify使用户从使用定制指令的僵化编程模型中解脱出来，提供了一个灵活的解决方案。该处理器是在Vivado High Level Synthesis 19.2中设计和测试的。它在Zynq Zedboard FPGA上工作频率为78 MHz。主站PE使用5%，每个从站使用3.5%的FPGA资源。测试结果表明，使用9个从机时执行时间可提高8.5倍，使用29个从机时可提高19倍。



<a name="Tq2mL"></a>
#### [DExIE-An IoT-Class Hardware Monitor for Real-Time Fine-Grained Control-Flow Integrity](https://dl.acm.org/doi/abs/10.1145/3441110.3441146)
C Spang, Y Lavan, M Hartmann, F Meisel, A Koch - Workshop on Design and …, 2021
> 动态执行完整性引擎（Dynamic Execution Integrity Engine，DExIE）是一个轻量级的硬件监控器，可以灵活地连接到许多物联网类处理器流水线上。它能保证及时捕捉功能间和功能内的非法控制流，防止任何非法指令触及内存。将DExIE附加到内核上对性能的影响取决于具体的流水线结构。在一些特别合适的情况下，用DExIE扩展处理器不会有性能上的损失。DExIE具有实时性，因为它只引起极少的、然后完全可以预测的管道停顿。它通常比基于软件的监控更快，而且通常比单独的防护处理器更小。我们不仅介绍了硬件架构，还介绍了自动编程流程，并讨论了用于细粒度控制流信息的紧凑适应性存储格式。

<a name="rz7qs"></a>
### 计算加速
<a name="AbhnE"></a>
#### [A Design of 16TOPS Efficient GEMM Module in Deep Learning Accelerator](https://ieeexplore.ieee.org/abstract/document/9332090/)
G Lu, D Xu, N Wang, X Zhang, D Zhen, H Lei, Y Bai… - 2020 IEEE International …, 2020
> 提出了一个高效的GEMM（泛矩阵乘法）模块作为DLA（深度学习加速器）的关键计算单元。该核心位于一个系统中，该系统由RISC-V处理器组成，用于标量运算和指令分配，PE（Processing Engine）用于矢量运算和张量运算。本文主要介绍张量运算模块GEMM，通过创新的数据预处理和内存布局，提供高度并行的处理能力。为了给各种神经网络提供足够的灵活性，GEMM还支持RISC-V处理器调度的多条指令。同时，分层指令队列保证了扩展性。当采用台积电12nm技术实现时，所提出的设计在1GHz下实现了16条TOPS INT8。



<a name="MxSCm"></a>
#### **[PDF]** [Hardware–Software Co-Design for Decimal Multiplication](https://www.mdpi.com/2073-431X/10/2/17/pdf)
M Shintani, M Inoue - Computers, 2021
> 对于非常大规模的应用来说，使用软件的十进制算术速度很慢。另一方面，当采用硬件时，需要额外的面积开销。一个平衡的策略可以克服这两个问题。我们提出的方法符合IEEE 754-2008标准，适用于十进制浮点算术以及软件和硬件的组合。在我们的方法中，软件与一些面积有效的十进制组件（硬件）被用来设计乘法过程。在基于RISC-V的集成协同设计评估框架中分析发现，所提出的方法为小数乘法解提供了几个帕累托点。与全软件方案相比，总执行过程加快了1.43×～2.37×。此外，与面积有效的全硬件方案相比，所需硬件减少了7-97%。

<a name="M1oQX"></a>
### 仿真验证，EDA
<a name="2UGu1"></a>
#### **[PDF]** [An Effective Methodology for Integrating Concolic Testing with SystemC-based Virtual Prototypes](http://www.informatik.uni-bremen.de/agra/doc/konf/DATE-2021_Concolic_Testing_with_SystemC_based_VPs.pdf)
S Tempel, V Herdt, R Drechsler
> 在本文中，我们提出了一种有效的方法论，用于整合协和测试（CT）和基于SystemC的虚拟原型（VP），以验证嵌入式SW二进制文件。我们的方法论包括三个步骤。1)将CT支持与VP的指令集模拟器(ISS)集成在一起，2)利用标准TLM-2.0扩展机制，与通用TLM事务一起传输协和值，3)为基于SystemC的外设提供轻量级的协和覆盖，使外设能够得到非侵入式的CT支持，从而大大减少CT集成的工作量。我们使用RIOT操作系统进行的RISC-V实验证明了我们方法的有效性。



<a name="MLElz"></a>
#### [Real silicon using open source eda](https://ieeexplore.ieee.org/abstract/document/9336682/)
RT Edwards, M Shalan, M Kassem - IEEE Design & Test, 2021
> 与更广泛的软件世界不同，电子设计自动化(EDA)的开源环境是零散的，需要花费大量的精力和各种学科的知识来组装一个工作流程。这使得大多数的开源工具都处于孤立的状态，有时在实际应用中几乎没有用武之地。在这篇文章中，我们介绍了商业定义的系统级芯片（SoC）微控制器的例子，从概念到芯片验证都是使用开源EDA工具和方法设计的。我们探讨了创建商业质量的芯片所面临的挑战和所需的解决方案，以及如何实现首次芯片成功。



<a name="rhGUc"></a>
#### [Read your Circuit: Leveraging Word Embedding to Guide Logic Optimization](https://dl.acm.org/doi/abs/10.1145/3394885.3431560)
WL Neto, MT Moreira, L Amaru, C Yu, PE Gaillardon - … of the 26th Asia and South …, 2021
> 为了解决所涉及的复杂性，电子设计自动化(EDA)工具被分解成定义明确的步骤，每个步骤在不同的抽象层次上运行。较高的抽象层次缩短了流程运行时间，同时牺牲了与物理电路实现的相关性。弥合逻辑合成工具和物理设计(PnR)工具之间的这种差距是提高结果质量(QoR)的关键，同时可能缩短上市时间。为了解决这个问题，在这项工作中，我们将逻辑路径形式化为句子，门是一袋字。因此，我们展示了如何利用词嵌入来表示通用路径，并预测给定路径是否可能是关键的后PnR。我们介绍了我们的方法的有效性，对于我们的测试案例，准确率超过90%。最后，我们进一步介绍了一种智能和非侵入式的流程，使用这些信息来指导优化。与标准流程相比，我们的流程呈现出高达15.53%的面积延迟积（ADP）和18.56%的功率延迟积（PDP）。



<a name="DrKyK"></a>
### 产业研究
<a name="jNfpB"></a>
#### [ASIP for 5G and Beyond: Opportunities and Vision](https://ieeexplore.ieee.org/abstract/document/9319703/)
S Shahabuddin, A Mämmelä, M Juntti, O Silvén - … on Circuits and Systems II: Express …, 2021
> 本教程讨论特定应用指令集处理器(ASIP)及其在第五代(5G)及以后5G网络中的潜力。ASIP是一类定制化的处理器，通常是为单一或一小套应用而设计的，融合了软件实现的灵活性和基于寄存器传输级（RTL）设计的效率。在本文中，我们介绍了通信系统ASIP的优势、方法、工具集和最先进的ASIP的总结。此外，我们还确定了5G及5G以上系统的关键特征，其中灵活性是一个关键要求，因此，ASIPs可以发挥关键作用。



<a name="l6VV9"></a>
### 一周专利
<a name="EogpG"></a>
#### **[PDF]** [Bit string lookup data structure](https://patentimages.storage.googleapis.com/5e/3b/95/660d002915f9f8/US20210011715A1.pdf)
VS Ramesh - US Patent App. 16/506,453, 2021<br />US20210011715A1 - Bit string lookup data structure - Google Patents. Bit string lookup<br />
<br />


---

RISC-V与芯片评论编辑部 - RISC-V和芯片动态周报<br />每周六发布<br />欢迎批评，指正，评论和加入<br />
<br />关于本刊: 

- 非特殊注明，本刊消息均来自于网络，如有版权问题，我们会立刻处理。
- [本刊部分消息来源](https://www.yuque.com/riscv/rvnews/overview#vHVQ5)




| 语雀 | 微信公众号 | Gitee | Github | Inspur |
| :---: | :---: | :---: | :---: | --- |
| <br />[RISC-V和芯片动态简报](https://www.yuque.com/riscv/rvnews)<br />[riscv  rvnews](https://www.yuque.com/riscv/rvnews) | 高效服务器和存储技术国家重点实验室<br />![image.png](https://cdn.nlark.com/yuque/0/2020/png/1541992/1608207453103-7b2eb8ee-1087-4e91-b124-0f9d394ef0bb.png#align=left&display=inline&height=139&margin=%5Bobject%20Object%5D&name=image.png&originHeight=139&originWidth=138&size=34726&status=done&style=none&width=138) | [inspur-risc-v  RVWeekly](https://gitee.com/inspur-risc-v/RVWeekly) | [inspur-risc-v  RVWeekly](https://github.com/inspur-risc-v/RVWeekly) | [riscv  RVWeekly](http://open.inspur.com/riscv/RVWeekly) |


<br />

