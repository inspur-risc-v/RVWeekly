# RV与芯片评论.20201024.第13期


<br />本期概要

- [Linley秋季处理器会议](#4TVjc)，[London Open Source Meetup for RISC-V](#Uvurq)，[欧洲开源峰会](#lUaAI)
- [Linux5.10将支持RISC-V UEFI](#WzMSO)
- 芯片发布：[SiFive VIU7](#hZHeH)，[南京博流的RISC-V蓝牙和WIFI芯片](#hZHeH)，[CoreMark1.3万分的RISC-V](https://www.yuque.com/riscv/rvnews/irg5qb)




---

<a name="cgX2z"></a>
# 重点聚焦
<a name="4TVjc"></a>
### Linley秋季处理器会议2020进行中


<a name="Uvurq"></a>
### London Open Source Meetup for RISC-V结束
<a name="lUaAI"></a>
### 欧洲开源峰会将在下周举行
<br />
<a name="DdzZp"></a>
### 在线会议：2020.11.06 RISC-V on FreeBSD
Mitchell Horne 将讨论 FreeBSD 对 RISC-V CPU 架构支持的过去、现在和未来。这个一小时的会议将在太平洋标准时间上午10:00/UTC下午17:00举行，网址是：[https://live.freebsd.org/FreeBSD/freebsdfriday/](https://live.freebsd.org/FreeBSD/freebsdfriday/)。

- "[FreeBSD Fridays: Introduction to RISC-V on FreeBSD ](https://freebsdfoundation.org/news-and-events/event-calendar/freebsd-fridays-introduction-to-risc-v-on-freebsd/
)(From freebsdfoundation.org 2020.10.25)"

<br />
<a name="saKC5"></a>
### The Next OSDT (aka HelloLLVM/HelloGCC) meetup 直播回放已公开


<a name="q92Hd"></a>
### 相关周报

- "[Week In Review: Auto, Security, Pervasive Computing ](https://semiengineering.com/week-in-review-auto-security-pervasive-computing-38/
)(From semiengineering.com 2020.10.23)"
   - FLex Logix shows off inference chip; OneSpin chips in; Synopsys, IBM collaborate.
- "[Week In Review: Design, Low Power ](https://semiengineering.com/week-in-review-design-low-power-117/
)(From semiengineering.com 2020.10.23)"
   - Microchip buys HLS provider LegUp; new edge inference chip; NN accelerator IP; power electronics virtual prototyping.
- "[【20201023期AI简报】OpenCV 4.5 发布、NVIDIA开源NeMo ](https://my.oschina.net/u/4428324/blog/4687245
)(From my.oschina.net 2020.10.25)"




---



<a name="nqDGS"></a>
# 技术动态

- "[The scalable Vector race is on: 3 1/2 years after publishing the spec ARM has announced cores that include SVE. ](https://www.reddit.com/r/RISCV/comments/jgy78a/the_scalable_vector_race_is_on_3_12_years_after/
)(From www.reddit.com 2020.10.24)"



<a name="WzMSO"></a>
### RISC-V的UEFI被Linux5.10初步支持
<a name="ihUzY"></a>
### 剑桥大学Talk：关于ARMv8和RISC-V的relaxed memory（21年1月29）
主讲：[Christopher Pulte, University of Cambridge](https://talks.cam.ac.uk/user/show/44065)<br />url：[https://talks.cam.ac.uk/talk/index/153283](https://talks.cam.ac.uk/talk/index/153283)<br />

<a name="kfWuR"></a>
### terminus：一个用 Rust 编写的 RISC-V 指令集模拟器
<br />
<a name="gucjq"></a>
### FYI 方舟编译器即将添加 RISC-V Backend 
消息：PLCT吴伟老师
> -- 节选自邮件列表 --
> [hellogcc-maple] [Minutes]OpenArkCompiler Conference 2020-10-23
> author: binaryfz
> 社区动态传递...
> 孵化器...
> 2. 后端：下一步支持RISC-V...
> Fred Chow Open64前端介绍<br />
> 已在码云开源，请参考：[https://gitee.com/open64ark/open64](https://gitee.com/open64ark/open64)

<br />
<a name="3bDT0"></a>
### BlueSpec：推出新版RISC-V Explorer，可以跟踪开源RISC-V内核变更


<a name="i6Bnu"></a>
### SiFive：白皮书：对关键任务应用的确定性处理方案
<a name="7W2QA"></a>
### <br />
<a name="en51B"></a>
### 演讲：A Plan 9 C Compiler for RV32GC and RV64GC
<br />
<a name="WK8U1"></a>
### 广播访谈Drew Fustini: 关于在RISC-V上构建Linux系统
<br />
<a name="YjMSB"></a>
### 高性能计算：HPC和Snow系统
<a name="vIDWa"></a>
### Linux动态

- "[[PATCH v4] riscv: Enable per-task stack canaries ](https://lkml.org/lkml/2020/10/18/71
)(From lkml.org 2020.10.18)"
- "[[GIT PULL] RISC-V Patches for the 5.10 Merge Window, Part 1 ](https://lkml.org/lkml/2020/10/19/735
)(From lkml.org 2020.10.19)"
- "[Re: [GIT PULL] RISC-V Patches for the 5.10 Merge Window, Part 1 ](https://www.mail-archive.com/linux-kernel@vger.kernel.org/msg2347120.html
)(From www.mail-archive.com 2020.10.19)"
- "[Re: [PATCH 4/5] RISC-V: Protect .init.text & .init.data ](https://lkml.org/lkml/2020/10/21/774
)(From lkml.org 2020.10.21)"
- "[Re: [PATCH 4/5] RISC-V: Protect .init.text & .init.data ](https://lkml.org/lkml/2020/10/21/774
)(From lkml.org 2020.10.21)"
- "[Re: [PATCH v2 2/2] Add RISC-V support content to the EBBR specification ](https://www.mail-archive.com/boot-architecture@lists.linaro.org/msg01545.html
)(From www.mail-archive.com 2020.10.21)"
- "[Re: [PATCH v4 5/5] riscv: Add numa support for riscv64 platform ](https://www.spinics.net/lists/arm-kernel/msg847715.html
)(From www.spinics.net 2020.10.22)"
- "[[GIT PULL] RISC-V Patches for the 5.10 Merge Window, Part 2 ](https://lkml.org/lkml/2020/10/24/7
)(From lkml.org 2020.10.23)"

<br />
<a name="SYbmw"></a>
### QEMU动态

- "[[PATCH] riscv: Add semihosting support [v8] ](https://www.mail-archive.com/qemu-devel@nongnu.org/msg753690.html
)(From www.mail-archive.com 2020.10.23)"
- "[[PATCH v1 00/16] RISC-V: Start to remove xlen preprocess ](https://www.mail-archive.com/qemu-devel@nongnu.org/msg753566.html
)(From www.mail-archive.com 2020.10.23)"
- "[[PATCH] riscv: Add semihosting support [v8] ](https://www.mail-archive.com/qemu-devel@nongnu.org/msg753690.html
)(From www.mail-archive.com 2020.10.23)"
- "[[PATCH v1 00/16] RISC-V: Start to remove xlen preprocess ](https://www.mail-archive.com/qemu-devel@nongnu.org/msg753566.html
)(From www.mail-archive.com 2020.10.23)"
- "[[PATCH V3 0/6] Support RISC-V migration ](https://www.mail-archive.com/qemu-devel@nongnu.org/msg753315.html
)(From www.mail-archive.com 2020.10.30)"




<a name="atISg"></a>
### <br />

---

<a name="SM5cC"></a>
# 产业风云

- 
- "[中芯国际原高管出任跃昉科技CEO，格兰仕梁惠强不再兼任 ](http://pc.nfapp.southcn.com/2329/4191424.html
)(From pc.nfapp.southcn.com 2020.10.22)"
   - "[前中芯国际执行副总裁汤天申博士已加盟广东跃昉科技有限公司(简称“跃昉科技”)，并出任CEO ](https://finance.sina.com.cn/tech/2020-10-23/doc-iiznctkc7258829.shtml
)(From finance.sina.com.cn 2020.10.22)"
- "[Maxim Integrated’s Network Accelerator Chip Enables IoT Artificial Intelligence in Battery Devices ](https://www.eletimes.com/maxim-integrateds-network-accelerator-chip-enables-iot-artificial-intelligence-in-battery-devices
)(From www.eletimes.com 2020.10.22)"
   - MAX78000后续报道
   - MAX78000将能耗和延迟降低了100多倍，在物联网边缘实现复杂的嵌入式推理决策。
- 
- "[淄博洛克网络科技有限公司下属子公司成为Risc-V战略合作伙伴 ](https://www.chinaz.com/2020/1023/1198944.shtml
)(From www.chinaz.com 2020.10.25)"
   - RockBrain USB服务器产品
   - 2020年10月，海南泰岳物联科技有限公司正式加入RISC-V组织，成为RISC-V战略合作伙伴成员之一。
- "[直播预告 | 全球首门基于RISC-V的官方课程来袭，与IMG共探下一代芯片人才培养 ](http://imgtec.eetrend.com/content/2020/100055510.html
)(From imgtec.eetrend.com 2020.10.25)"
   - 2020年10月29日（星期四） 20:00
   - 报名链接：[https://sourl.cn/gv8qEA](https://sourl.cn/gv8qEA)
<a name="nM5ic"></a>
### 产业评论


- "[openEuler平台能否借社区生态补强国内开源最后一块短板?  ](https://www.sohu.com/a/426576154_134438
)(From www.sohu.com 2020.10.21)"
- "[小米的T字生态：它的下一个十年应该看什么？ ](https://finance.sina.com.cn/tech/csj/2020-10-23/doc-iiznezxr7590400.shtml
)(From finance.sina.com.cn 2020.10.23)"
- "[RISC-V的驱动力解析 ](https://www.eefocus.com/mcu-dsp/474950
)(From www.eefocus.com 2020.10.25)"
- "[Nvidia-Arm Deal a Boon for RISC-V?  ](https://www.enterpriseai.news/2020/10/23/nvidia-arm-deal-a-boon-for-risc-v/
)(From www.enterpriseai.news 2020.10.25)"

<br />
<a name="lJVln"></a>
### SiFive：推出VIU7核心，支持V1.0扩展


<a name="hZHeH"></a>
### 博流智能科技：RISC-V蓝牙5.0和Wifi芯片


<a name="lJ0Go"></a>
### OneSpin：成为德国Scale4Edge项目合作伙伴


<a name="nIUrS"></a>
### 威奇半导体推出业界首款千万级IOPS高性能存储加速芯片及系统

- "[威奇半导体推出业界首款千万级IOPS高性能存储加速芯片及系统 ](http://finance.eastmoney.com/a/202010221672652136.html
)(From finance.eastmoney.com 2020.10.22)"
>     专注存储领域的半导体创新企业威奇半导体(WeChiSemi，以下简称“威奇”)今日宣布推出业界首款千万级IOPS“云麾-WSA10M”存储协处理卡、“磐鼎-XL”高性能分布式整机存储系统和“磐鼎-HC”高性能超融合架构系统。
>   “云麾-WSA10M”存储协处理卡基于威奇自主创新研发的千万级IOPS高性能存储加速ASIC芯片“云麾”，其业界首创的“DPU+SPU”设计集成智能化的数据处理单元(DPU)和存储处理单元(SPU)， 从硬件层面保证协处理卡有能力充分卸载分布式存储系统与数据相关的计算、应用及存储相关网络协议。特性上，“云麾”ASIC芯片采用自主研发的RISC-V技术，全面支持PCIe Gen4和Gen5接口规范，内嵌双网络接口支持 25/50/100/200GbE网络。网络接口支持全套存储网络协议，如RoCE v2、TCP-IP和NVMe over Fabric。 “云麾-WSA10M”存储协处理卡是威奇针对大规模数据中心以及云计算相关的中国及全球市场推出的协处理器产品，该产品可以帮助客户迅速构建私有的高性能分布式存储阵列，让客户在存储系统上获得前所未有的整体拥有成本。

<a name="YP9vl"></a>
### OPEN AI + 芯来科技: 基于RISC-V无门槛构建和部署AI推理
> OPEN AI LAB 基于芯来科技的NMSIS-NN计算库，成功开发了语音关键字识别的Demo，该语言Demo以 音频 文件作为输入，基于KWS关键字识别模型推理出正确的结果。

"[OPEN AI 携芯来科技扩大RISC-V软件生态 ](http://news.moore.ren/industry/250511.htm
)(From news.moore.ren 2020.10.22)"
<a name="hQcyT"></a>
### SiPearl将要开发Arm HPC芯片
使用ARM专门为HPC开发的Neoverse V1芯片

- "[SiPearl Develops Arm HPC Chip ](https://www.linleygroup.com/newsletters/newsletter_detail.php?num=6227&year=2020&tag=3
)(From www.linleygroup.com 2020.10.21)"

<br />
<a name="Su3w8"></a>
### CloudBEAR的BM-310MCU详解
<br />
<a name="g6LL4"></a>
### 包永刚：芯来科技大学计划，一周上手RISC-V
<br />

- "[一周就能从Arm开发切换到RISC-V！ 5年内RISC-V的AIoT设备将触手可及 ](https://www.leiphone.com/news/202010/4JdVWIvASjNEgNLB.html
)(From www.leiphone.com 2020.10.21)"
- "[一周就能从Arm开发切换到RISC-V！ 5年内RISC-V的AIoT设备将触手可及 ](https://www.leiphone.com/news/202010/4JdVWIvASjNEgNLB.html
)(From www.leiphone.com 2020.10.25)"



<a name="Ps6dG"></a>
### IAR Embedded Workbench for RISC-V功能安全版获得IEC和ISO认证


<a name="gpHHl"></a>
### CodaSip：在法国设立设计中心


<a name="kd40P"></a>
### Prodigy通用处理器


<a name="Xo2wH"></a>
### SmartDV将携设计和验证IP组合参加2020年虚拟三星SAFE论坛


<a name="k7UFI"></a>
###  Microchip: 收购LegUp HLS



---

<a name="5NYql"></a>
# 一周论文


<a name="V4sax"></a>
### [An Open-Source **RISC**-**V **Evaluation Platform](http://scholar.google.com/scholar_url?url=https://link.springer.com/chapter/10.1007/978-3-030-54828-5_3&hl=en&sa=X&d=5200425097481302515&ei=QdiNX7X6OP2Jy9YPkd2mkA0&scisig=AAGBfm1JrWNpiOrPHx0FDV7BVJRR9ZtAsA&nossl=1&oi=scholaralrt&hist=AQxAsJ0AAAAJ:3812021249043908228:AAGBfm19OZ2uvk2g_ev6ffIC03BRSiTYQw&html=)
V Herdt, D Große, R Drechsler - Enhanced Virtual Prototyping
> 本章介绍了一个在SystemC TLM（事务级建模）中实现的开源RISC-V虚拟原型（VP），目标是扩展RISC-V生态系统。VP提供了一个32/64位的RISC-V内核，并提供了一套基本的外设，支持多核仿真。此外，VP还提供了SW调试（通过Eclipse IDE）和覆盖率测量功能，并支持FreeRTOS、Zephyr和Linux操作系统。VP被设计为可扩展和可配置的平台（作为一个例子，我们提供了一个与SiFive的RISC-V HiFive1板相匹配的配置），具有通用的总线系统，并采用符合标准的SystemC实现。后一点非常重要，因为它允许利用上述系统级用例所需的基于SystemC的前沿建模技术。最后，与RTL相比，VP允许更快的仿真速度，同时比现有的ISSs更精确。此外，VP集成了一个高效的核心时序模型，以实现基于RISC-V系统的快速和准确的性能评估。时序模型通过一组定义良好的接口连接到核心，这些接口将功能和非功能方面解耦，并使时序模型易于重新配置。



<a name="sNprz"></a>
### **[PDF]** [WebRISC-V: A **RISC**-**V **Educational Simulator featuring RV64IM, Pipeline and Web-Based UI](http://scholar.google.com/scholar_url?url=https://www3.diism.unisi.it/~giorgi/papers/Mariotti20-acaces.pdf&hl=en&sa=X&d=128514506147546075&ei=QdiNX7X6OP2Jy9YPkd2mkA0&scisig=AAGBfm2ShC4fLYMkIqps82dCrmCRNmo3ug&nossl=1&oi=scholaralrt&hist=AQxAsJ0AAAAJ:3812021249043908228:AAGBfm19OZ2uvk2g_ev6ffIC03BRSiTYQw&html=)
G Mariotti, R Giorgi
> WebRISC-V是一个基于网络的面向教育的RISC-V流水线仿真环境，旨在帮助学生学习和减轻教师的教学经验。该模拟器允许在一个五级流水线上执行RISC-V用户提供的源代码，使其很容易跟踪指令流，同时显示寄存器、内存和流水线元素的内部状态数据。在这里，我们将介绍WebRISC-V以及为什么它是有用的教学工具，介绍它的最新功能更新，并简要地将模拟器与其他可用的RISC-V教育工具进行比较。



<a name="MiUfU"></a>
### [Evaluation of Open-Source Linear Algebra Libraries targeting ARM and **RISC**-**V **Architectures](http://scholar.google.com/scholar_url?url=https://ieeexplore.ieee.org/abstract/document/9222916/&hl=en&sa=X&d=938626021721150408&ei=QdiNX7X6OP2Jy9YPkd2mkA0&scisig=AAGBfm1VnM4oPLXqtdvuEYixp824XOc3cw&nossl=1&oi=scholaralrt&hist=AQxAsJ0AAAAJ:3812021249043908228:AAGBfm19OZ2uvk2g_ev6ffIC03BRSiTYQw&html=)
C Fibich, S Tauner, P Rössler, M Horauer - 2020 15th Conference on Computer …, 2020
> Basic Linear Algebra Subprograms （BLAS）已经成为提供线性代数功能的库的事实上的标准接口。物联网(IoT)节点的强大设备的出现，使得现有的BLAS实现可以在这些系统中重用。这就需要对这些库在嵌入式处理器上的特性进行辨别评估。这项工作对广泛的未经修改的开源BLAS库的性能和内存消耗进行了基准测试和讨论。与相关（但部分已经过时）的出版物相比，这项评估涵盖了最大的一组开源BLAS库，也考虑了内存消耗，并特别关注于支持Linux的嵌入式平台（一个基于ARM的SoC，包含一个SIMD加速器和基于新兴RISC-V架构的首批商业嵌入式系统之一）。结果表明，特别是对于矩阵运算和较大的问题规模，优化的BLAS实现与纯C实现相比，可以获得显著的性能提升。此外，在我们选择的测试中，ARM平台的性能优于RISC-V化身。



<a name="BTKAZ"></a>
### **[PDF]** [A Simulator and Compiler Framework for Agile Hardware-Software Co-design Evaluation and Exploration](http://scholar.google.com/scholar_url?url=https://users.soe.ucsc.edu/~tsorensen/files/iccad20.pdf&hl=en&sa=X&d=12488021065776058888&ei=QdiNX7X6OP2Jy9YPkd2mkA0&scisig=AAGBfm1G1LrqKoOD7nB2lq-z_eaBnO4idQ&nossl=1&oi=scholaralrt&hist=AQxAsJ0AAAAJ:3812021249043908228:AAGBfm19OZ2uvk2g_ev6ffIC03BRSiTYQw&html=)
T Sorensen, A Manocha, E Tureci, M Orenes-Vera…
> 随着摩尔定律的放缓和Dennard Scaling的结束，架构师们越来越多地转向异构并行和软硬件协同设计。这些趋势对基于仿真的性能评估提出了新的挑战，而仿真是早期阶段架构探索的核心。仿真器必须是轻量级的，以支持通用内核和专用处理单元的异构组合。它们还必须支持软硬件协同设计的敏捷探索，即编程模型、编译器、ISA和专用硬件的变化。为了应对这些挑战，我们描述了我们的编译器和模拟器对。DEC++和MosaicSim。它们共同为异构系统提供了一个轻量级、模块化的仿真器，提供了专门为硬件-软件协同设计探索而设计的准确性和敏捷性。这个模拟器和相应的编译器是作为DECADES项目的一部分开发的，这是一个设计和带出一个新的异构架构的多团队努力。我们将介绍两个重要数据科学应用中的案例研究，在这些案例中，DEC++和MosaicSim为新兴的全栈系统实现了直接的设计空间探索。


<br />
<br />
<br />

<a name="4uJgM"></a>
### **[PDF]** [**RISC**-**V **Cryptographic Extension Proposals Volume I: Scalar & Entropy Source Instructions](http://scholar.google.com/scholar_url?url=https://lists.riscv.org/g/tech-crypto-ext/attachment/318/0/riscv-crypto-spec-v0.7.0-scalar.pdf&hl=en&sa=X&d=4360932347904339354&ei=UISQX_z7AoqVmgHnyLKgDg&scisig=AAGBfm1-rcs4I-trg0q3h7AHZ5Je1JTytQ&nossl=1&oi=scholaralrt&hist=AQxAsJ0AAAAJ:3812021249043908228:AAGBfm19OZ2uvk2g_ev6ffIC03BRSiTYQw&html=)
A Zeh, A Glew, B Spinney, B Marshall, D Page…<br />This document describes the proposed scalar cryptography extension for **RISC**-**V**. All<br />instructions proposed here use the general purpose X registers, and obey the 2-read-<br />1-write register access constraint. These instructions are designed to be lightweight …<br />

<a name="Btm36"></a>
### [A Systematic Review on an Embedded Web Server Architecture](http://scholar.google.com/scholar_url?url=https://link.springer.com/chapter/10.1007/978-981-15-7234-0_49&hl=en&sa=X&d=918119733200455436&ei=UISQX_z7AoqVmgHnyLKgDg&scisig=AAGBfm2AUcD0tB-kuP9mTk2jKnsYJZzTyg&nossl=1&oi=scholaralrt&hist=AQxAsJ0AAAAJ:3812021249043908228:AAGBfm19OZ2uvk2g_ev6ffIC03BRSiTYQw&html=)
SK Panday, RVV Krishna, D Nandan - Proceedings of International Conference on Recent …<br />… Many architecture techniques are used to manufacture the processor, some<br />are mention below as Based on ARM, AVR, MicroBlaze, MS-51, MIPS,<br />**RISC**-**V**, SPARC, X86, and many more others and where MicroBlaze …<br />

<a name="kVoqy"></a>
### [VGM-Bench: FPU Benchmark Suite for Computer Vision, Computer Graphics and Machine Learning Applications](http://scholar.google.com/scholar_url?url=http://books.google.com/books%3Fhl%3Den%26lr%3Dlang_en%26id%3DLCsDEAAAQBAJ%26oi%3Dfnd%26pg%3DPA322%26dq%3Drisc-v%26ots%3Dnl3kO9uv1u%26sig%3DMUj9YKayFOzS8J0QOr1VM3FLeHg&hl=en&sa=X&d=16222967558493495724&ei=UISQX_z7AoqVmgHnyLKgDg&scisig=AAGBfm2r5kyjBrwN4AhVZd6NNl__7hYFdA&nossl=1&oi=scholaralrt&hist=AQxAsJ0AAAAJ:3812021249043908228:AAGBfm19OZ2uvk2g_ev6ffIC03BRSiTYQw&html=)
D Zoni - … Systems: Architectures, Modeling, and Simulation: 20th …<br />… The complete benchsuite, together with a detailed description of each application is<br />available as open source at [1]. To show in practice the value of this benchmark suite,<br />results are collected on a **RISC**-**V** System-on-Chip platform meant for IoT …<br />

<a name="GgZYK"></a>
### **[PDF]** [Elasticlave: An Efficient Memory Model for Enclaves](http://scholar.google.com/scholar_url?url=https://arxiv.org/pdf/2010.08440&hl=en&sa=X&d=6322590158357713864&ei=7SyTX67hE4-NywTcxYqYBA&scisig=AAGBfm0F4Jfp8Zhva2bgL-maBSzT9Ut18g&nossl=1&oi=scholaralrt&hist=AQxAsJ0AAAAJ:3812021249043908228:AAGBfm19OZ2uvk2g_ev6ffIC03BRSiTYQw&html=)
Z Yu, S Shinde, TE Carlson, P Saxena - arXiv preprint arXiv:2010.08440, 2020<br />… We prototype ELASTICLAVE design on an RTL-designed cycle-level **RISC**-**V** core and<br />observe 1 to 2 or- ders of magnitude performance improvements over the spatial model<br />implemented with the same processor configuration. ELASTICLAVE has a small TCB …<br />

<a name="OUHgT"></a>
### **[PDF]** [On licenses for [Open] Hardware](http://scholar.google.com/scholar_url?url=https://arxiv.org/pdf/2010.09039&hl=en&sa=X&d=11866328149901913750&ei=7SyTX67hE4-NywTcxYqYBA&scisig=AAGBfm3s8zte_EkNIILsxVHr3kd5ySMopA&nossl=1&oi=scholaralrt&hist=AQxAsJ0AAAAJ:3812021249043908228:AAGBfm19OZ2uvk2g_ev6ffIC03BRSiTYQw&html=)
M Montón, X Salazar - arXiv preprint arXiv:2010.09039, 2020<br />… are of current interest. We have been mainly motivated by the growing influence<br />of the open **RISC**-**V** ISA, but trying to address a wider hardware point of view. Index<br />Terms—Licenses, open-hardware I. INTRODUCTION Thanks …<br />

<a name="ZtOsA"></a>
### **[PDF]** [Scalable Open-Source System-on-Chip Design](http://scholar.google.com/scholar_url?url=http://www.cs.columbia.edu/~luca/research/carloni_VLSISOC20.pdf&hl=en&sa=X&d=2516651678675518570&ei=7SyTX67hE4-NywTcxYqYBA&scisig=AAGBfm3xg0tYsg8-Sxl4z_fAS8MOVqOKrw&nossl=1&oi=scholaralrt&hist=AQxAsJ0AAAAJ:3812021249043908228:AAGBfm19OZ2uvk2g_ev6ffIC03BRSiTYQw&html=)
LP Carloni<br />… Index Terms—system-on-chip (SoC), open-source hardware (OSH), heterogeneous<br />computing, system-level design, **RISC**-**V** … The momentum of OSH has been building in<br />recent years [18], [19], thanks particularly to the popularity of the **RISC**-**V** project [20] …<br />
<br />

<a name="RXfGC"></a>
### **[PDF]** [Specification and verification in the field: Applying formal methods to BPF just-in-time compilers in the Linux kernel](http://scholar.google.com/scholar_url?url=https://unsat.cs.washington.edu/papers/nelson-jitterbug.pdf&hl=en&sa=X&d=1980033617522820009&ei=7SyTX67hE4-NywTcxYqYBA&scisig=AAGBfm09VSdet-bCOCtXhGyn6koQKnTPQQ&nossl=1&oi=scholaralrt&hist=AQxAsJ0AAAAJ:3812021249043908228:AAGBfm19OZ2uvk2g_ev6ffIC03BRSiTYQw&html=)
L Nelson, J Van Geffen, E Torlak, X Wang<br />… Using Jitterbug, we have designed, implemented, and verified a new BPF<br />JIT for 32-bit **RISC**-**V**, found and fixed 16 previously unknown bugs in five<br />other deployed JITs, and developed new JIT optimizations; all of these …<br />

<a name="ewAvd"></a>
### **[PDF]** [PIE: A Dynamic TCB for Remote Systems with a Platform Isolation Environment](http://scholar.google.com/scholar_url?url=https://arxiv.org/pdf/2010.10416&hl=en&sa=X&d=1717896703994516307&ei=7SyTX67hE4-NywTcxYqYBA&scisig=AAGBfm0HFXcTXDtjHsF6gT-h9kZdRZXVCQ&nossl=1&oi=scholaralrt&hist=AQxAsJ0AAAAJ:3812021249043908228:AAGBfm19OZ2uvk2g_ev6ffIC03BRSiTYQw&html=)
M Schneider, A Dhar, I Puddu, K Kostiainen, S Capkun - arXiv preprint arXiv …, 2020<br />… in connected peripherals. Finally, we present a prototype based on **RISC**-**V's** Keystone<br />to show that such systems are feasible with only around 350 lines added to the software<br />TCB. I. INTRODUCTION Trusted execution environments …<br />

<a name="fI4uk"></a>
### **[PDF]** [Virtual Secure Platform: A Five-Stage Pipeline Processor over TFHE](http://scholar.google.com/scholar_url?url=https://arxiv.org/pdf/2010.09410&hl=en&sa=X&d=13309290604200388643&ei=7SyTX67hE4-NywTcxYqYBA&scisig=AAGBfm3hiwRCiee8n_d9WDADldM5qzz8Yw&nossl=1&oi=scholaralrt&hist=AQxAsJ0AAAAJ:3812021249043908228:AAGBfm19OZ2uvk2g_ev6ffIC03BRSiTYQw&html=)
K Matsuoka, R Banno, N Matsumoto, T Sato, S Bian - arXiv preprint arXiv:2010.09410, 2020<br />Page 1. Virtual Secure Platform: A Five-Stage Pipeline Processor over TFHE Kotaro<br />Matsuoka ∗ , Ryotaro Banno†, Naoki Matsumoto†, Takashi Sato‡, Song Bian‡ ∗<br />Undergraduate School of Electrical and Electronic Engineering …<br />
<br />


---


<br />

<a name="tAplU"></a>
# 其他动态


<a name="lxmHe"></a>
### RV科普

- 
- 
- "[Difference Between RISC and CISC ](https://www.javatpoint.com/risc-vs-cisc
)(From www.javatpoint.com 2020.10.21)"
- "[RISC-V is the future of computing | Chris Lattner and Lex Fridman ](https://www.youtube.com/watch?feature=youtu.be&v=lXdx0X2WHfY&app=desktop
)(From www.youtube.com 2020.10.23)"
<a name="tO9Sj"></a>
### 网站推荐：opnecores
[https://opencores.org/](https://opencores.org/)<br />汇集并对比了各种开源核心

<a name="018hY"></a>
### 新书推荐：[Enhanced Virtual Prototyping: Featuring **RISC**-**V **Case Studies](http://scholar.google.com/scholar_url?url=http://books.google.com/books%3Fhl%3Den%26lr%3Dlang_en%26id%3DMC0DEAAAQBAJ%26oi%3Dfnd%26pg%3DPP6%26dq%3Drisc-v%26ots%3DxSF0KuBkq5%26sig%3DN15gsGiUABYy4ogdO23NdUTbuf8&hl=en&sa=X&d=13447516927021837977&ei=UISQX_z7AoqVmgHnyLKgDg&scisig=AAGBfm0dov3JsJD17-cw_h3NGxesSc-8DQ&nossl=1&oi=scholaralrt&hist=AQxAsJ0AAAAJ:3812021249043908228:AAGBfm19OZ2uvk2g_ev6ffIC03BRSiTYQw&html=)
V Herdt - 2020<br />本书介绍了一套全面的技术，这些技术增强了现代基于虚拟样机（VP）的设计流程的所有关键方面。作者强调了自动形式化验证方法，以及为基于SystemC的VP和相关软件(SW)量身定做的高级覆盖指导分析和测试技术。覆盖范围还包括处理功能和非功能方面的VP建模技术，还描述了硬件和VP级别之间的对应分析，以利用不同抽象级别的信息。所有的方法都得到了详细的讨论，并进行了广泛的评估，使用一些实验来证明它们在增强基于VP的设计流程方面的有效性。此外，本书特别关注现代RISC-V ISA，其中有几个案例研究，涵盖了建模以及VP和SW验证方面。
> Virtual Prototypes (VPs) play a very important role to cope with the rising complexity
> in the design flow of embedded devices. A VP is essentially an executable abstract
> model of the entire Hardware (HW) platform and pre-dominantly created in SystemC …

目录<br />1 Introduction<br />2 Preliminaries<br />3 An OpenSource RISCV Evaluation Platform<br />4 Formal Verification of SystemCBased Designs using Symbolic Simulation<br />5 CoverageGuided Testing for Scalable VirtualPrototype Verification<br />6 Verification of Embedded Software Binaries using VirtualPrototypes<br />7 Validation of FirmwareBased Power Management using Virtual Prototypes<br />8 RegisterTransfer Level Correspondence Analysis<br />9 Conclusions<br />
<br />在线地址

- [Spring](https://www.springer.com/cn/book/9783030548278?utm_campaign=3_pier05_buy_print&utm_content=en_08082017&utm_medium=referral&utm_source=google_books#otherversion=9783030548285)




<a name="6oSTR"></a>
### RISC和CISC的区别


<a name="KxZpO"></a>
### ![image.png](https://cdn.nlark.com/yuque/0/2020/png/1541992/1603287293464-fda35c75-1b86-4aff-9140-03fc89d1866c.png#align=left&display=inline&height=24&margin=%5Bobject%20Object%5D&name=image.png&originHeight=52&originWidth=52&size=1036&status=done&style=none&width=24)博文推荐：RISC-V Datapath: Part2
"[RISC-V Datapath: Part2 ](https://zhuanlan.zhihu.com/p/266505382
)(From zhuanlan.zhihu.com 2020.10.17)"

<a name="LdxsI"></a>
### tinyriscv 简介：FPGA上的RISC-V开源项目
项目开源地址：[https://gitee.com/liangkangnan/tinyriscv](https://gitee.com/liangkangnan/tinyriscv)<br />文档地址：[https://liangkangnan.gitee.io/2020/04/29/从零开始写RISC-V处理器/](https://liangkangnan.gitee.io/2020/04/29/从零开始写RISC-V处理器/)

- "[分享一个在fpga上面跑的riscv的开源项目tingriscv  ](https://www.firebbs.cn/thread-30687-1-1.html
)(From www.firebbs.cn 2020.10.20)"



<a name="LtInv"></a>
### 博文推荐：eSecure IP
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

