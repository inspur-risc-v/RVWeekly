# RV与芯片评论.20201128.第18期


<br />本期概要

- 乐鑫ESP32-C3发布，使用RISC-V，集成蓝牙，wifi和RF模块，另外有其中加密算法的硬件加速单元
- 奇绩创坛路演活动本周结束，StarFive等企业参加
- Experts at the Table: 人工智能和芯片的安全问题和应对策略
- 芯华章推出基于LLVM的系统仿真架构，支持飞腾处理器 
- 本周观点：RISC-V是否准备好与ARM的竞争




---

<a name="cgX2z"></a>
# 重点聚焦


<a name="8OhqG"></a>
### Experts at the Table: 人工智能和芯片的安全问题和应对策略


<a name="u1qhF"></a>
### 相关周报

- ![image.png](https://cdn.nlark.com/yuque/0/2020/png/1541992/1599307696075-3f44fb1b-f362-4130-a254-b3e4fb6cebac.png#align=left&display=inline&height=24&margin=%5Bobject%20Object%5D&name=image.png&originHeight=84&originWidth=89&size=7408&status=done&style=none&width=25)[semi engineering](https://semiengineering.com/) Week In Review: ：
   - [Blog Review](https://semiengineering.com/blog-review-nov-25-2/)：FPGA complexity; next decade of semiconductors; CXL 2.0; adding functional safety.
   - [Design, Low Power](https://semiengineering.com/week-in-review-design-low-power-122/)：_Edge AI chip; AI development platform; LG to spin off units._
   - [Manufacturing, Test](https://semiengineering.com/week-in-review-manufacturing-test-124/)：_Fab equipment boom; Intel’s letter to Biden; 28nm; FinTech._
   - [Auto, Security, Pervasive Computing](https://semiengineering.com/week-in-review-auto-security-pervasive-computing-43/)：_Subaru, Softbank 5G automatic driving; China EV shakeup soon to come._
   - 
- [IoT News](https://staceyoniot.com/): [Nov. 27, 2020](https://staceyoniot.com/iot-news-of-the-week-for-nov-27-2020/
): 
- [OSDT Weekly](https://github.com/hellogcc/osdt-weekly/tree/master/weekly)：[2020-11-25 第073期 ](https://github.com/hellogcc/osdt-weekly/blob/master/weekly/2020-11-25.md
)(github.com)
- [泰晓咨询](http://tinylab.org/)：暂无
- [PLCT开源进展](https://www.zhihu.com/column/plct-lab)："[PLCT开源进展·第14期·2020年12月01日 ](https://zhuanlan.zhihu.com/p/325728273
)(From zhuanlan.zhihu.com 2020.12.01)"
- [RT-Thread](https://my.oschina.net/u/4428324)：暂无
- ：[第 135 期：什么行业适合创业？ ](https://www.yuque.com/ruanyf/weekly/issue-135
)(From www.yuque.com)

---



<a name="nqDGS"></a>
# 技术动态

- "[国产开源物联网操作系统RT-Thread Smart正式上线（附源代码下载地址） ](https://www.eet-china.com/kj/59008.html
)(From www.eet-china.com 2020.11.23)"
- 
- 
- 
- 
- 
- 
- 
- 
   - 老外跟进报道
<a name="UQCtX"></a>
### Linux动态

- "[RE: [PATCH 1/2] RISC-V: Update l2 cache DT documentation to add support for SiFive FU740 ](https://lkml.org/lkml/2020/11/23/205
)(From lkml.org 2020.11.23)"
- "[[PATCH v3] RISC-V: Use SBI SRST extension when available ](https://www.mail-archive.com/linux-kernel@vger.kernel.org/msg2393773.html
)(From www.mail-archive.com 2020.11.24)"
- "[Re: drivers/clocksource/timer-riscv.c:28:16: error: implicit declaration of function 'get_cycles64' ](https://www.mail-archive.com/linux-kernel@vger.kernel.org/msg2393472.html
)(From www.mail-archive.com 2020.11.24)"
- "[Re: [PATCH] RISC-V: Define get_cycles64() regardless of M-mode ](https://www.mail-archive.com/linux-kernel@vger.kernel.org/msg2394751.html
)(From www.mail-archive.com 2020.11.25)"
- "[[GIT PULL] RISC-V Fixes for 5.10-rc6 ](https://www.mail-archive.com/linux-kernel@vger.kernel.org/msg2397130.html
)(From www.mail-archive.com 2020.11.28)"
<a name="SYbmw"></a>
### QEMU动态

- "[[PATCH 0/8] Add RISC-V semihosting 0.2. Finish ARM semihosting 2.0 ](https://www.mail-archive.com/qemu-devel@nongnu.org/msg762456.html
)(From www.mail-archive.com 2020.11.25)"
- "[[Bug 1826568] Re: RISC-V Disassembler/translator instruction decoding disagreement ](https://www.mail-archive.com/qemu-devel@nongnu.org/msg762413.html
)(From www.mail-archive.com 2020.11.25)"
<a name="v2ah0"></a>
### 一周问答

- "[Why there is 5 in RISC-V? ](https://www.reddit.com/r/RISCV/comments/jxxiug/why_there_is_5_in_riscv/
)(From www.reddit.com 2020.11.21)"
> The name RISC-V was chosen to represent the fifth major RISC ISA design from UC Berkeley (RISC-I [23], RISC-II [15], SOAR [32], and SPUR [18] were the first four). We also pun on the Volume I: RISC-V User-Level ISA V2.2 use of the Roman numeral “V” to signify “variations” and “vectors”, as support for a range of architecture research, including various data-parallel accelerators, is an explicit goal of the ISA design.

- "[RISC-V: PMP vs MultiZone ](https://stackoverflow.com/questions/64946852/risc-v-pmp-vs-multizone
)(From stackoverflow.com 2020.11.23)"
- "[光刻机不让买，5G不让卖，那RISC-V就不会被卡脖子吗？ ](https://club.6parkbbs.com/military/index.php?app=forum&act=threadview&tid=16099116
)(From club.6parkbbs.com 2020.11.23)"
- "[RISC-V架构能否有效挑战ARM和英特尔？ ](https://www.wukong.com/answer/6837056753784324360/
)(From www.wukong.com 2020.11.23)"
- 你认为AMD会迁移到RISC-V架构吗
   - "[Do you think AMD will switch to the RISC V architecture in the near future rather than paying Intel to use x86? I'm thinking the days of x86 are numbered. ](https://boards.4channel.org/g/thread/78818189/do-you-think-amd-will-switch-to-the-risc-v
)(From boards.4channel.org 2020.11.27)"
- "[How do I write NOT Operation for the Risc-V (Assembly Language)?  ](https://stackoverflow.com/questions/65006052/how-do-i-write-not-operation-for-the-risc-v-assembly-language
)(From stackoverflow.com 2020.11.26)"

<br />
<a name="CC8oT"></a>
### 社区动态

- "[gollvm: missing headers, Clang's issues and broken libffi on Fedora 33 (64bit RISC-V) #42804 ](https://github.com/golang/go/issues/42804
)(From github.com 2020.11.24)"
- "[Bug 251403 - lang/gcc10 seems to not allow building for RISC-V ](https://bugs.freebsd.org/bugzilla/show_bug.cgi?id=251403
)(From bugs.freebsd.org 2020.11.26)"
- "[SiFive now has MiniITX RISC-V being released soon. ](https://linustechtips.com/topic/1274067-sifive-now-has-miniitx-risc-v-being-released-soon
)(From linustechtips.com 2020.11.27"
- "[Question regarding compilation of source files ](https://github.com/NikosDelijohn/RISCV-32I/issues/6
)(From github.com 2020.11.27)"

<br />

---

<a name="SM5cC"></a>
# 产业风云

- "[奇绩创坛陆奇：今年录取创业公司 87% 属前沿技术驱动型，含芯片、传感器、脑机、生物科技 ](https://finance.sina.com.cn/tech/2020-11-22/doc-iiznctke2723928.shtml
)(From finance.sina.com.cn 2020.11.22)".
   - 11月21日至22日，奇绩创坛2020年路演日（Demo Day）活动在北京开展。奇绩创坛自2018年起已持续举办了两届
   - 奇绩创坛前身是YC中国，由陆奇博士（前百度总裁兼COO、微软执行副总裁、雅虎执行副总裁）于2018年创立，主要专注于早期技术驱动型项目的投资、加速和创业者社区建设。
   - 奇绩创坛创始人兼 CEO 陆奇介绍说，今年总共录取了 30 家创业公司，其中 87% 前沿技术驱动型企业，包括芯片、传感器、脑机、生物科技，创始人平均年龄 33 岁，最小的 19 岁。
- "[赛昉科技亮相奇绩创坛路演日 共推国内RISC-V开源生态 ](http://www.semiinsights.com/s/bdt/15/41075.shtml
)(From www.semiinsights.com 2020.11.23)"
   - 相关新闻："[RISC-V芯片涌现新机会？中国公司正涌入这一阵营 ](https://mbb.eet-china.com/forum/topic/84126_1_1.html
)(From mbb.eet-china.com 2020.11.24)"
- 芯华章推出基于LLVM的系统仿真架构，支持飞腾处理器
   - "[国产EDA终于支持国产计算架构 飞腾服务器已经验证 ](https://finance.sina.com.cn/tech/2020-11-26/doc-iiznctke3446356.shtml
)(From finance.sina.com.cn 2020.11.27)"
   - "[提升芯片设计研发效率！芯华章宣布推出全新验证技术及产品 ](http://www.cet.com.cn/wzsy/cyzx/2714937.shtml
)(From www.cet.com.cn 2020.11.27)"
   - "[芯华章发布全新仿真技术：全面支持x86/Arm/RISC-V/MIPS/GPGPU/NPU等架构 ](http://www.icsmart.cn/41437/
)(From www.icsmart.cn 2020.11.27)"
- "[群联、慧荣、FADU等厂商陆续推出企业级NVMe SSD新主控 ](https://finance.sina.com.cn/tech/2020-11-26/doc-iiznezxs3765377.shtml
)(From finance.sina.com.cn 2020.11.27)"
   - 慧荣（Silicon Motion）的 SM8266 主控
   - 群联（Phison）的 FX 系列
   - 采用了 FC4121 主控的 FADU Delta SSD，是率先采用 RISC-V 处理器内核架构的新主控
      - 上一代 FC3081“Annapurna”主控采用的是 SiFive 的 S51 内核。
- "[汇聚新能源汽车半导体技术和产业专家的“中国国际汽车电子高峰论坛”成功在上海举行 ](https://www.ednchina.com/news/6022.html
)(From www.ednchina.com 2020.11.27)"
- 
- "[深度解密IMG B系列GPU：多核架构、图像压缩技术、RISC-V技术等 ](https://www.eda365.com/thread-469628-1-1.html
)(From www.eda365.com 2020.12.05)"
- 
<a name="PO7vP"></a>
### 评论文集

- "[RISC-V为什么会成为热点? ](https://blog.csdn.net/DP29syM41zyGndVF/article/details/110101828
)(From blog.csdn.net 2020.11.24)"
- "[半导体IP行业深度报告：核心、机遇、格局、国产突破 ](https://finance.sina.com.cn/stock/stockzmt/2020-11-26/doc-iiznezxs3864927.shtml
)(From finance.sina.com.cn 2020.11.27)"
- "[国内芯片企业纷纷入局，如今RISC-V生态建设进展几何？ ](https://www.rvmcu.com/article-show-id-522.html
)(From www.rvmcu.com 2020.11.27)"
- 
- 
- "[RISC-V蓬勃发展，机遇与挑战并存 ](http://m.chinaaet.com/article/3000125584
)(From m.chinaaet.com 2020.12.05)"

---



<a name="tAplU"></a>
# 其他动态


<a name="KDCRS"></a>
### 项目推荐


- ![image.png](https://cdn.nlark.com/yuque/0/2020/png/1541992/1606460019144-6c0e1d0d-387b-4783-b2b8-50d7f20a0a71.png#align=left&display=inline&height=24&margin=%5Bobject%20Object%5D&name=image.png&originHeight=56&originWidth=55&size=1108&status=done&style=none&width=24)[ar-pavel](https://github.com/ar-pavel)/[RISC-V-Simulator](https://github.com/ar-pavel/RISC-V-Simulator)
   - 使用C++写的RISC-V模拟器，基本实现了RV32I指令
- ![image.png](https://cdn.nlark.com/yuque/0/2020/png/1541992/1606460019144-6c0e1d0d-387b-4783-b2b8-50d7f20a0a71.png#align=left&display=inline&height=24&margin=%5Bobject%20Object%5D&name=image.png&originHeight=56&originWidth=55&size=1108&status=done&style=none&width=24)[edilcn](https://github.com/edilcn)/[fpga-riscv32-minimal](https://github.com/edilcn/fpga-riscv32-minimal)：
   - EEL 510389 – Digital Systems and Reconfigurable Devices 的课程作业，该项目实现了一个十余个控制指令。适合初学者借鉴。
- 
   - KCP53000是个64位RISC-V核心
<a name="EwqDy"></a>
### 博文推荐

- "[Cross compiling Golang for RISC-V with cgo ](https://blog.davidburela.com/2020/11/21/cross-compiling-golang-for-risc-v/
)(From blog.davidburela.com 2020.11.23)"
- "[Spike+OpenOCD调试RISCV汇编指令环境搭建 ](https://zhuanlan.zhihu.com/p/301577545
)(From zhuanlan.zhihu.com 2020.11.22)"
- 
- 
- "[5.4 RISC-V寄存器 ](https://zhuanlan.zhihu.com/p/295439950
)(From zhuanlan.zhihu.com 2020.11.15)"
- "[[RISC-V MCU 应用开发] 【原创】 【RISC-V MCU CH32V103测评】U盘文件列表功能的验证 ](https://bbs.21ic.com/icview-3049836-1-1.html
)(From bbs.21ic.com 2020.11.25)"
- "[[RISC-V MCU 应用开发] 【RISC-V MCU CH32V103测评】+FATFS移植及目录显示 ](https://bbs.21ic.com/icview-3050142-1-1.html
)(From bbs.21ic.com 2020.11.26)"
- 
- 
- "[构建riscv上运行的linux系统 ](https://segmentfault.com/a/1190000038317909
)(From segmentfault.com 2020.12.05)"
- "[RISC-V常见指令 ](https://blog.csdn.net/qq_43245691/article/details/110260112
)(From blog.csdn.net 2020.12.05)"
- "[基于高云系列FPGA的RISC-V软核 ](https://mbb.eet-china.com/forum/topic/84303_1_1.html
)(From mbb.eet-china.com 2020.12.05)"
- 

---

<a name="5NYql"></a>
# 一周论文<br />
<a name="9HFnz"></a>
### [Unifying Timer and Interrupt Management for an ARM-**RISC**-**V**-Heterogeneous Multi-Core](https://ieeexplore.ieee.org/abstract/document/9255193/)
M Eckert, J Haase, B Klauer - IECON 2020 The 46th Annual Conference of the IEEE …, 2020
> 定时器和中断管理基础设施对于执行先发制人操作系统的计算机系统来说是必不可少的。这一点对单核系统和多核系统都适用。当涉及到可支持操作系统的ISA异构多核系统（系统包括不同ISA的内核，这些内核都能执行操作系统）时，不同系统ISA的不同定时器和中断基础设施仍然适用。但是，如果在ISA异构性的基础上增加了可重构性，也就是说组成（各个核的数量）是运行时可适应的，则需要重新考虑定时器和中断管理基础设施。本文推导了一种统一的定时器和中断管理方案，适用于由ARM和RISC-V内核组成的可执行Linux的运行时适应性强、可支持操作系统的ISA异构多核系统。通过分析/研究RISC-V和ARM系统的定时器和中断管理方案来实现。最后本文将说明RISC-V的定时器和中断管理设备也适合管理基于ARM系统的定时器和中断。

<a name="sTAdr"></a>
### **[PDF]** [Indirection Stream Semantic Register Architecture for Efficient Sparse-Dense Linear Algebra](https://arxiv.org/pdf/2011.08070)
P Scheffler, F Zaruba, F Schuiki, T Hoefler, L Benini - arXiv preprint arXiv:2011.08070, 2020<br />… CSR and CSF require indirect memory lookups. In this work, we enhance a<br />memory-streaming **RISC**-**V** ISA extension to accelerate sparse-dense products<br />through streaming indirection. We present efficient dot, matrix-vector …
<a name="qiSWd"></a>
### [A Dual Lockstep Processor System-on-a-Chip for Fast Error Recovery in Safety-Critical Applications](https://ieeexplore.ieee.org/abstract/document/9255188/)
MT Sim, Y Zhuang - IECON 2020 The 46th Annual Conference of the IEEE …, 2020
> 在锁步系统中，如果没有适当的错误检测或写保护电路，由单点和共模故障引起的错误可能会导致灾难性的死亡。在本文中，我们设计并实现了一个双锁步处理器，使用一个双流水线组件，以交错的方式分别执行两个虚拟内核。这种方法可以克服共模故障（CMF）。此外，通过在二级流水线中运行相同的代码，我们的系统可以检测单点故障（SPOF）。我们的技术很容易保持两个虚拟内核之间的同步，并省略了绑定典型双核锁步处理器的其他结构。这减少了裸片尺寸，并在错误变得不可恢复之前提供早期错误检测。我们通过在微架构中加入锁步功能，并采用细粒度的多任务处理来提高系统的故障安全能力，从而实现我们的目标。最后，我们使用RISC-V 32IM ISA测试台、Dhrystones和Coremark基准以及ModelSim对我们的锁步处理器进行了验证。我们的结果显示了100%的卡顿故障自检覆盖率和完整的错误控制。由于我们的框架是细粒度的多任务操作，我们实现了两个锁步处理器而不是一个，从而节省了硬件成本。

<a name="QncqM"></a>
### **[PDF]** [AXES: Approximation Manager for Emerging Memory Architectures](https://arxiv.org/pdf/2011.08353)
B Maity, B Donyanavard, A Surhonne, A Rahmani… - arXiv preprint arXiv …, 2020
> 存储器近似技术通常在范围上受到限制，只针对存储器层次结构中的个别层次。现有的全内存层次结构的近似技术在设计时确定了最佳的设计方案，但前提是有目标和应用。这种策略是僵化的：它们不能适应未知的工作负载，必须为不同的内存配置和技术重新设计。我们提出AXES：第一个自我优化的运行时管理器，用于在内存层次结构的所有级别上协调可近似的旋钮。AXES在整个运行时持续更新和优化其近似管理策略，以适应不同的工作负载。AXES优化了近似内存配置，以最大限度地降低功耗，同时又不影响应用程序开发人员所规定的质量阈值。AXES可以(1)在运行时学习策略以管理可变的应用服务质量(QoS)约束，(2)在这些约束中自动优化目标指标，(3)协调相互依赖的旋钮和子系统的运行时决策。我们展示了AXES在RISC-V Linux平台上有效地提供功能1-3的能力，并在片上高速缓存和主内存中提供近似的内存段。我们展示了AXES能够在没有任何设计时间开销的情况下，在内存子系统中节省高达37%的能量。我们展示了AXES能够在<5%的额外能量下减少75%的QoS违反。

<a name="9ncbY"></a>
### **[PDF]** [Trends in computing technologies and markets: The HEPiX TechWatch WG](https://www.epj-conferences.org/articles/epjconf/pdf/2020/21/epjconf_chep2020_07056.pdf)
A Sciaba, H Meinhard, G Cancio, M Gasthuber… - EPJ Web of Conferences, 2020
> 在认真规划和优化大科学项目（如欧洲核子研究中心的大型强子对撞机等）下一个数据采集期的资源需求的推动下，各站点开始了一项共同的活动，即HEPiX技术观察工作组，其任务是跟踪数据中心所关注的技术和市场的演变。讲座将概述一般市场和半导体市场、服务器市场、CPU和加速器、存储器、存储和网络；将强调不确定因素和风险的重要领域。

<a name="vPwX8"></a>
### [Problems Of Security For The Implementation Of The Internet Of Things](https://www.elibrary.ru/item.asp?id=44182458)
A Fomina, Y Antokhina, E Semenova - … of Social and Behavioural Sciences EpSBS, 2020
> IoT的部署和安全问题是紧密相连的。在这个领域，至少有两个层面的问题和难题。第一个层面是政府和国际组织的责任。它解决的问题是规范物联网中的活动，为商业创造最有利的条件，确保属于各种市场参与者的存储和传输数据的安全。安全问题不仅包括识别各种漏洞，还包括打击网络犯罪和敌国。第二个层次涵盖了与开发必要的设备、设备、网络、其架构和相关软件有关的广泛问题。此外，物联网的功耗和远程物联网设备的功率问题、检测非法访问企图的算法和手段的开发以及反击等问题都非常重要。在提供通信和大幅提高通信质量方面，物联网技术的发展与5G技术，特别是mmWave的发展密切相关。文章的特点和优势包括对上述所有问题进行全面的回顾。这样的方法不仅有助于更深入地、从各方面考虑物联网发展和部署的情况。同时也为评估物联网、通信技术、连接性和安全性的发展前景提供了机会。


<br />**
<a name="uxUrA"></a>
### **[PDF]** [An Experimental Study of Building Blocks of Lattice-Based NIST Post-Quantum Cryptographic Algorithms](https://www.mdpi.com/2079-9292/9/11/1953/pdf)
M Imran, ZU Abideen, S Pagliarini - Electronics, 2020
> 目前部署的公钥加密算法的安全性预计容易受到量子计算机的攻击。因此，社区存在着开发后量子密码学（PQC）算法的努力，最著名的是NIST PQC标准化竞赛。在这项工作中，我们研究了基于网格的候选算法在硬件中实现时的表现。为了达到这个目的，我们评估了12种基于网格的算法，以确定它们的基本构件。我们假设这些算法将在特定应用集成电路(ASIC)平台上实现，目标技术为65纳米。为了估计每个算法的特性，我们评估了以下特性：内存需求，乘法器的使用，以及散列函数的使用。此外，对于这些构件，我们已经收集了所有研究算法的面积和功率参数，利用商业内存编译器和标准单元。我们的结果揭示了每个构件对整个密码系统的相对重要性的有趣见解，这可以用来指导ASIC设计者在选择算法时，或决定在哪里集中优化努力，使最终设计尊重要求和设计约束。



<a name="eLWOV"></a>
### **[PDF]** [Progressive Automated Formal Verification of Memory Consistency in Parallel Processors](ftp://ftp.cs.princeton.edu/techreports/2020/007.pdf)
YA Manerkar
> 近年来，由于摩尔定律和Dennard缩放的结束，晶体管级的限制导致单线程硬件性能停滞不前。取而代之的是，今天的设计通过异构并行来提高性能：在一个芯片上使用多个不同的处理元素，其中许多元素专门用于运行特定的工作负载。这种架构中的处理元件通常通过向共享内存加载和存储来相互通信和同步。内存一致性模型(MCMs)指定了这种负载和存储的排序规则。因此，MCM验证对并行系统的正确性至关重要，但众所周知，验证很难进行，需要检查大量的场景。使用形式化方法进行验证可以在数学证明的基础上提供强有力的正确性保证，是MCM验证的绝佳t。本论文对自动化形式化硬件MCM验证做出了一些贡献，使这种技术更接近于能够处理现实世界的架构。首先，我的RTLCheck工作实现了设计顺序的形式化模型与RTL处理器实现的自动链接。这种联系有助于将设计时形式化验证的正确性保证推到带状芯片上。这种联系可以作为一种针对RTL验证微结构模型合理性的方法。其次，我的RealityCheck工作通过利用硬件设计的结构模块化实现了硬件设计的可扩展的自动化形式化MCM验证。它还有利于设计处理器的各个团队对设计顺序进行模块化规范。第三，我的PipeProof工作实现了自动化的全程序硬件MCM验证。一个处理器必须尊重其所有可能程序的MCM，而PipeProof使设计人员能够自动证明这样的结果。本论文还提出了Progressive Automated Formal Verication，一种新型的通用验证方式 
> 嗷。渐进式验证强调在系统开发的多个点上使用自动形式化验证，从早期设计开始，以及各种验证方法之间的相互联系。渐进式验证有多种好处，包括更早的发现bug，减少验证开销，缩短开发时间。PipeProof、RealityCheck和RTLCheck的结合，实现了MCM特性在并行处理器中的渐进式验证，为未来渐进式验证的发展提供了参考。



<a name="Tkd4P"></a>
### [Programming Reconfigurable Heterogeneous Computing Clusters Using MPI With Transpilation](https://conferences.computer.org/scwpub/pdfs/H2RC2020-1FtHQgCvDatO1bzdGXxUTT/235400a001/235400a001.pdf)
B Ringlein, F Abel, A Ditter, B Weiss, C Hagleitner…
> 随着摩尔定律的放缓和Dennard缩放的停止，计算硬件的能量效率转化为计算能力。因此，高性能计算(HPC)系统倾向于越来越依赖于加速器，如现场可编程门阵列(FPGA)，以促进高要求的工作负载，如大数据应用或深度神经元网络。这些FPGA是可重构的，有时不再是与CPU相连的总线，而是作为独立节点直接连接到数据中心网络结构。这种CPU和FPGA的混合导致了可重构异构HPC(ReH2PC)集群的产生，尽管过去有很多建议，但目前还没有成熟的编程模型。



<a name="542ED"></a>
### **[PDF]** [Proving Confidentiality and Its Preservation Under Compilation for Mixed-Sensitivity Concurrent Programs](http://unsworks.unsw.edu.au/fapi/datastream/unsworks:73144/SOURCE02?view=true)
R Sison - 2020<br />Page 1. Proving Confidentiality and Its Preservation Under Compilation for<br />Mixed-Sensitivity Concurrent Programs Robert Sison Submitted in fulfilment of the<br />requirements for the degree of Doctor of Philosophy School of Computer …<br />

<a name="MLvWp"></a>
## 一周专利

<br />

<a name="X6IM4"></a>
### [Bit sting operations using a computing tile](https://patents.google.com/patent/US20200341761A1/en)
VS Ramesh - US Patent App. 16/397,084, 2020<br />US20200341761A1 - Bit sting operations using a computing tile - Google Patents. Bit<br />sting operations using a computing tile. Download PDF Info. Publication number<br />US20200341761A1. US20200341761A1 US16/397,084 US201916397084A …
<a name="tFsay"></a>
### [Fast storage class memory using write once memory coding](https://patents.google.com/patent/US20200341685A1/en)
E Sharon, A Navon, A Bazarsky, I Alrod - US Patent App. 16/397,993, 2020<br />US20200341685A1 - Fast storage class memory using write once memory coding - Google<br />Patents. Fast storage class memory using write once memory coding. Download PDF Info.<br />Publication number US20200341685A1. US20200341685A1 …
<a name="CDdmm"></a>
### [Method for the execution of a binary code of a secure function by a microprocessor](https://patents.google.com/patent/US20200349294A1/en)
O Savry - US Patent App. 16/866,619, 2020<br />… An unconditional branch instruction is for example the instruction “JAL”<br />in the set of instructions “**RISC** **V**”. The branch instruction may also be**
<a name="dqxif"></a>
### [Methods and systems for efficient cryptographic third-party authentication of asset transfers using trusted computing](https://patents.google.com/patent/US20200351089A1/en)
CT Wentz - US Patent App. 16/861,599, 2020<br />US20200351089A1 - Methods and systems for efficient cryptographic third-party<br />authentication of asset transfers using trusted computing - Google Patents. Methods<br />and systems for efficient cryptographic third-party authentication …
<a name="xIVhr"></a>
### [Methods and systems for utilizing hardware-secured receptacle devices](https://patents.google.com/patent/US20200351098A1/en)
CT Wentz - US Patent App. 16/861,767, 2020<br />US20200351098A1 - Methods and systems for utilizing hardware-secured receptacle<br />devices - Google Patents. Methods and systems for utilizing hardware-secured<br />receptacle devices. Download PDF Info. Publication number …<br />
<br />
<br />
<br />


---

RISC-V与芯片评论编辑部 - RISC-V和芯片动态周报<br />每周六发布<br />欢迎批评，指正，评论和加入<br />
<br />关于本刊: 

- 非特殊注明，本刊消息均来自于网络，如有版权问题，我们会立刻处理。
- [本刊部分消息来源](https://www.yuque.com/riscv/rvnews/overview#vHVQ5)




| 微信公众号<br />![image.png](https://cdn.nlark.com/yuque/0/2020/png/1541992/1602320139392-1297e86a-ac06-4d76-a000-ad4307cd488c.png#align=left&display=inline&height=187&margin=%5Bobject%20Object%5D&name=image.png&originHeight=440&originWidth=465&size=225442&status=done&style=none&width=198) | Gitee

[https://gitee.com/inspur-risc-v/RVWeekly](https://gitee.com/inspur-risc-v/RVWeekly) | Github

[https://github.com/inspur-risc-v/RVWeekly](https://github.com/inspur-risc-v/RVWeekly) | 语雀

[https://www.yuque.com/riscv/rvnews](https://www.yuque.com/riscv/rvnews) |
| --- | --- | --- | --- |


<br />
<br />
<br />
<br />

