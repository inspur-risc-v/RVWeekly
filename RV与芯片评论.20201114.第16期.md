# RV与芯片评论.20201114.第16期


<br />本期概要

1. 噱头：初中生5天开发出一个5级流水线的RISC-V
1. MIPS两家公司宣布支持RISC-V指令集
1. 欧洲处理器计划公布路线图
1. Sipeed+平头哥：玄铁906是K210之后的下一块开发板
1. 下周即将召开 Edge AI Summit
1. Google把开源“魔爪”伸向了ASIC设计




---

<a name="cgX2z"></a>
# 重点聚焦
<a name="10379fd7"></a>
### 本周结束的会议

- 
- 
<a name="m3P7J"></a>
### 即将召开的会议

- 
- 
- 



<a name="u1qhF"></a>
### 相关周报

- [OSDT Weekly](https://github.com/hellogcc/osdt-weekly/tree/master/weekly)：
   - "[OSDT Weekly 2020-11-11 第071期 ](https://mp.weixin.qq.com/s/Eu4ANCJvUYK3WAfpvso-xQ
)(From mp.weixin.qq.com 2020.11.11"
- [泰晓咨询](http://tinylab.org/)：
   - "[泰晓资讯·11月 / 第一期 / 2020 ](http://tinylab.org/tinylab-weekly-11-1st-2020/
)(From tinylab.org 2020.11.14)"
- [PLCT开源进展](https://www.zhihu.com/column/plct-lab)：
   - 本周暂无
- ![image.png](https://cdn.nlark.com/yuque/0/2020/png/1541992/1599307696075-3f44fb1b-f362-4130-a254-b3e4fb6cebac.png#align=left&display=inline&height=24&margin=%5Bobject%20Object%5D&name=image.png&originHeight=84&originWidth=89&size=7408&status=done&style=none&width=25)[semi engineering](https://semiengineering.com/)：每周三，周五发布
   - "[UVM transaction class methods; EPROM; WPA2 vulnerabilities; NN inference on mobile GPUs. ](https://semiengineering.com/blog-review-nov-11-2/
)(From semiengineering.com 2020.11.17)"
      - UVM transaction class methods; EPROM; WPA2 vulnerabilities; NN inference on mobile GPUs.
   - "[Week In Review: Design, Low Power ](https://semiengineering.com/week-in-review-design-low-power-120/
)(From semiengineering.com 2020.11.13)"
      - Synopsys acquires Moortec; Silvaco buys Dolphin memory assets; CXL 2.0 released; Ansys results.
   - "[Week In Review: Manufacturing, Test ](https://semiengineering.com/week-in-review-manufacturing-test-122/
)(From semiengineering.com 2020.11.13)"
      - 5nm Macs; TSMC U.S. fab; 22nm; mmWave test standard. 
   - "[Week In Review: Auto, Security, Pervasive Computing ](https://semiengineering.com/week-in-review-auto-security-pervasive-computing-41/
)(From semiengineering.com 2020.11.13)"
      - Cadence DSPs certified ASIL B(D); Amazon switches to in-house chips.
- ：
- [RT-Thread](https://my.oschina.net/u/4428324)：
   - "[【20201112期AI简报】超快速3D目标检测网络来了！SFA3D! ](https://my.oschina.net/u/4428324/blog/4718382
)(From my.oschina.net 2020.11.12)"

---



<a name="nqDGS"></a>
# 技术动态

- "[国产集成开发环境——国产RISC-V生态的“强心剂” ](https://www.21ic.com/article/880487.html
)(From www.21ic.com 2020.11.14)"
   - 介绍了RT-Thread Studio
- 
- 
- 
- 
- 
- 
- 
<a name="UQCtX"></a>
### Linux动态
"[Linux 5.10-rc3 Released As A "Normal" RC3 Version ](https://www.phoronix.com/scan.php?page=news_item&px=Linux-5.10-rc3-Released
)(From www.phoronix.com 2020.11.14)"

- "[Linux 5.10第三个候选版本发布：开发工作一切顺畅 ](https://www.cnbeta.com/articles/tech/1050975.htm
)(From www.cnbeta.com 2020.11.14)"

Mail Archived

- "[Re: [PATCH 18/32] riscv: Add Kendryte K210 SoC clock driver ](https://www.spinics.net/lists/linux-spi/msg24937.html
)(From www.spinics.net 2020.11.07)"
- "[[PATCH 00/32] RISC-V Kendryte K210 support improvments ](https://www.spinics.net/lists/linux-spi/msg24896.html
)(From www.spinics.net 2020.11.07)"
- "[[PATCH 09/32] riscv: Fix SiFive gpio probe ](https://www.spinics.net/lists/linux-spi/msg24905.html
)(From www.spinics.net 2020.11.07)"
- "[[PATCH 08/32] riscv: Fix kernel time_init() ](https://www.spinics.net/lists/linux-spi/msg24904.html
)(From www.spinics.net 2020.11.07)"
- "[[PATCH 32/32] riscv: Update Kendryte K210 defconfig ](https://www.spinics.net/lists/linux-gpio/msg54685.html
)(From www.spinics.net 2020.11.07)"
- "[Re: [PATCH 19/32] riscv: Add Kendryte K210 SoC reset controller ](https://www.spinics.net/lists/linux-gpio/msg54696.html
)(From www.spinics.net 2020.11.07)"
- "[[PATCH] riscv: Explicitly specify the build id style in vDSO Makefile again ](https://lkml.org/lkml/2020/11/8/259
)(From lkml.org 2020.11.08)"
- "[Re: [PATCH v8 1/7] RISC-V: Move DT mapping outof fixmap ](https://lkml.org/lkml/2020/11/9/42
)(From lkml.org 2020.11.09)"
- "[linux-next: Signed-off-by missing for commit in the risc-v tree ](https://www.spinics.net/lists/linux-next/msg57402.html
)(From www.spinics.net 2020.11.09)"
- "[[PATCH v15 17/17] RISC-V: KVM: Add MAINTAINERS entry ](https://lkml.org/lkml/2020/11/9/334
)(From lkml.org 2020.11.09)"
- "[[PATCH 2/2] RISC-V: sifive_l2_cache: Update L2 cache driver to support SiFive FU740 ](https://www.mail-archive.com/linux-kernel@vger.kernel.org/msg2377368.html
)(From www.mail-archive.com 2020.11.12)"
- "[Re: [PATCH] riscv: Explicitly specify the build id style in vDSO Makefile again ](https://www.mail-archive.com/linux-kernel@vger.kernel.org/msg2378552.html
)(From www.mail-archive.com 2020.11.12)"
- "[Re: [v3] cpuidle: add riscv cpuidle driver ](https://www.mail-archive.com/linux-kernel@vger.kernel.org/msg2377958.html
)(From www.mail-archive.com 2020.11.12)"
- "[[PATCH 1/3] dt-bindings: riscv: Add DT documentation for SiFive Bus Error Unit ](https://lkml.org/lkml/2020/11/12/489
)(From lkml.org 2020.11.12)"
- "[[PATCH 1/2] RISC-V: Update l2 cache DT documentation to add support for SiFive FU740 ](https://www.mail-archive.com/linux-kernel@vger.kernel.org/msg2377369.html
)(From www.mail-archive.com 2020.11.12)"
- "[[RFC PATCH v2 4/4] RISC-V: Enable Microchip PolarFire ICICLE SoC ](https://www.mail-archive.com/linux-kernel@vger.kernel.org/msg2379659.html
)(From www.mail-archive.com 2020.11.13)"
- "[Re: [PATCH v4] riscv: Enable per-task stack canaries ](https://www.mail-archive.com/linux-kernel@vger.kernel.org/msg2379892.html
)(From www.mail-archive.com 2020.11.13)"



<a name="SYbmw"></a>
### 其他动态
KVM

- "[[PATCH v15 16/17] RISC-V: KVM: Document RISC-V specific parts of KVM API ](https://www.spinics.net/lists/kvm/msg228487.html
)(From www.spinics.net 2020.11.09)"
- "[[PATCH v15 09/17] RISC-V: KVM: Implement VMID allocator ](https://www.spinics.net/lists/kvm/msg228481.html
)(From www.spinics.net 2020.11.09)"
- "[[PATCH v15 12/17] RISC-V: KVM: Add timer functionality ](https://www.spinics.net/lists/kvm/msg228489.html
)(From www.spinics.net 2020.11.09)"
- "[[PATCH v15 02/17] RISC-V: Add initial skeletal KVM support ](https://www.spinics.net/lists/kvm/msg228478.html
)(From www.spinics.net 2020.11.09)"
- "[KVM RISC-V Support ](https://lwn.net/Articles/836608/
)(From lwn.net 2020.11.14)"

QEMU

- "[[PULL 0/6] riscv-to-apply queue ](https://www.mail-archive.com/qemu-devel@nongnu.org/msg758762.html
)(From www.mail-archive.com 2020.11.09)"
- "[Re: [RFC v5 00/68] support vector extension v1.0 ](https://www.mail-archive.com/qemu-devel@nongnu.org/msg758742.html
)(From www.mail-archive.com 2020.11.09)"
- "[Re: [PATCH 4/4] riscv: Add semihosting support [v11] ](https://www.mail-archive.com/qemu-devel@nongnu.org/msg759365.html
)(From www.mail-archive.com 2020.11.11)"
<a name="v2ah0"></a>
### 一周问答

- "[RISC-V Load address not aligned to word boundary ](https://stackoverflow.com/questions/64748879/risc-v-load-address-not-aligned-to-word-boundary
)(From stackoverflow.com 2020.11.14)"
- "[How can I extract bits in Risc v assembly code ](https://stackoverflow.com/questions/64747340/how-can-i-extract-bits-in-risc-v-assembly-code
)(From stackoverflow.com 2020.11.14)"
- "[RISC-V Load address not aligned to word boundary ](https://stackoverflow.com/questions/64748879/risc-v-load-address-not-aligned-to-word-boundary
)(From stackoverflow.com 2020.11.14)"
- "[How to Build “riscv64-unknown-elf-gcc” ](https://forums.sifive.com/t/how-to-build-riscv64-unknown-elf-gcc/4192
)(From forums.sifive.com 2020.11.14)"
<a name="CC8oT"></a>
### 社区动态

- "[Best Book for Learning and Practicing RISC-V Assembly Language and Architecture. ](https://www.reddit.com/r/RISCV/comments/jqpd4r/best_book_for_learning_and_practicing_riscv/
)(From www.reddit.com 2020.11.14)"
- "[Add JIT for RISC-V #11136 ](https://github.com/eclipse/openj9/issues/11136
) in Gitub/[eclipse](https://github.com/eclipse)/[openj9](https://github.com/eclipse/openj9)  (From github.com 2020.11.10)" 
- "[Newbie question: Do you think RISC-V has the potential of reviving the high-performance workstation market that thrived in the 1990s? ](https://www.reddit.com/r/RISCV/comments/jrgvx8/newbie_question_do_you_think_riscv_has_the/
)(From www.reddit.com 2020.11.14)"
   - ARM自己的内核可能比RISC-V领先五年，其SiFive U84（已宣布但尚未在芯片中使用）和阿里巴巴XT910（显然已在阿里巴巴的云中使用，但尚未出售）都在ARM A72级别左右。但是ARM宣布了A78并交付了A76。
   - 在接下来的12个月左右的时间里，RISC-V供应商将推出带有RISC-V Vector扩展的CPU，它将很好地运行GPGPU代码-在许多方面都与GPU一样好（给定具有足够功能的矢量单元处理元素），并且在需要串行和并行代码之间频繁交互的任何事物上都比GPU更好。
   - 在2019年12月的RISC-V峰会上，现有GPU制造商Think Silicon展示了他们的GPU架构（在FPGA中），其中指令集更改为RISC-V，外加六条自定义指令，只花了一个月。
- "[HiFive FE310-G002 JTAG on Board HiFive1 Rev B ](https://forums.sifive.com/t/hifive-fe310-g002-jtag-on-board-hifive1-rev-b/4187
)(From forums.sifive.com 2020.11.14)"
- "[YA RISC-V port thread ](https://bbs.archlinux.org/viewtopic.php?id=260639
)(From bbs.archlinux.org 2020.11.14)"
- "[Starting with prototyping a risc-v SBC - looking for resources ](https://www.reddit.com/r/openhardware/comments/jso5oo/starting_with_prototyping_a_riscv_sbc_looking_for/
)(From www.reddit.com 2020.11.14)"
- 

---

<a name="SM5cC"></a>
# 产业风云

- "[2020闪存峰会：西部数据介绍数据中心与车载工业级NVMe SSD新品 ](https://www.cnbeta.com/articles/tech/1052507.htm
)(From www.cnbeta.com 2020.11.14)"
- "[紫光展锐：基于展锐6纳米5G芯片的手机将于明年量产 ](https://finance.sina.com.cn/tech/2020-11-11/doc-iiznezxs1307071.shtml
)(From finance.sina.com.cn 2020.11.14)"
   - 黄宇宁认为，5G给RISC-V带来了新机会。“现在5G可能会带来一个新的更大的市场，就是当传统的MCU加上5G的应用。5G低延时高可靠的特性特别适合工业的场景，所以就存在一种新的可能：工业的控制器和基础连接的功能连在一起，一种新形态的工业控制器。”
- "[全国产MCU研发设计公司「爱普特」完成超亿元A轮融资， 青桐资本担任财务 ](https://www.admin5.com/article/20201112/975209.shtml
)(From www.admin5.com 2020.11.14)"
   - 爱普特率先使用了自主可控的RISC-V架构内核设计了多系列的全国产MCU
- "[核芯互联：10倍速度实现“中国芯”替代，未来将冲击科创板  ](https://www.sohu.com/a/431524795_100269432
)(From www.sohu.com 2020.11.14)"
   - 核芯互联在模拟和数字领域都采用敏捷设计方法，将芯片设计周期缩短至3个月以内，研发速度提升10倍。这也是核芯互联在短短两年时间内研发出20多款芯片的重要原因。
- "[MindSpore: 作为一个开源社区，开放是核心 ](https://www.sohu.com/a/431645023_114877
)(From www.sohu.com 2020.11.14)"
   - MindSpore是华为在今年3月28日开源的一个全场景AI计算框架。如今，七个多月过去，MindSpore在国内开发者群体中发挥着越来越大的影响力。黄之鹏认为，MindSpore社区的优势主要有三点：一是开放治理；二是强调合作；三是开发者第一。
- 
- 
- 
- 
- 
- 
- 
- "[[Ars] Amazon moves AI off Nvidia to it's own silicon ](https://www.overclock.net/threads/ars-amazon-moves-ai-off-nvidia-to-its-own-silicon.1774641/
)(From www.overclock.net 2020.11.13)"
<a name="PO7vP"></a>
### 评论文集

- "[破解“中国开源拿来主义”的几点分析 | 包云岗 ](https://zhuanlan.zhihu.com/p/284049407
)(From zhuanlan.zhihu.com 2020.11.10)"
- "[开放性与碎片化，RISC-V能否撼动处理器架构的格局？ ](https://www.eda365.com/article-172070-1.html
)(From www.eda365.com 2020.11.14)"
- "[为什么说2019是RISC-V进入主流市场的元年？ ](https://www.zclxy.com/1749.html
)(From www.zclxy.com 2020.11.14)"
- 

---



<a name="tAplU"></a>
# 其他动态


<a name="tO9Sj"></a>
### 视频推荐

- "[ 7:53 / 18:59 OPEN SOURCE PROCESSOR - RISC V could be revolutionary ](https://www.youtube.com/watch?v=WI1dDxQPsY4&feature=emb_title
)(From www.youtube.com 2020.11.14)"
- "[FreeBSD Fridays: Introduction to RISC-V on FreeBSD ](https://linuxreviews.org/FreeBSD_Fridays:_Introduction_to_RISC-V_on_FreeBSD
)(From linuxreviews.org 2020.11.14)"
<a name="roTiH"></a>
### 博文推荐

- "[GSoC项目 Optimize OpenCV for RISC-V ](https://zhuanlan.zhihu.com/p/291207654?utm_source=wechat_session&utm_medium=social&s_r=0
)(From zhuanlan.zhihu.com 2020.11.13)"
   - 为Wide Uniersal Intrinsics实现近期非常火热的RISC-V指令集及其"V"(向量)扩展（RVV）的支持，从而使OpenCV在RISC-V平台上也能获得向量加速。
- "[QEMU模拟器下编译运行基于RISCV指令集的linux操作系统 ](https://blog.csdn.net/weixin_39688262/article/details/109543688
)(From blog.csdn.net 2020.11.14)"
- "[【Java on RISC-V】交叉编译OpenJDK11(zero VM) ](https://zhuanlan.zhihu.com/p/291064772
)(From zhuanlan.zhihu.com 2020.11.14)"
- "[qemu 运行 riscv 内核失败记录 ](https://blog.csdn.net/Longyu_wlz/article/details/109150134
)(From blog.csdn.net 2020.11.14)"
- "[RSIC-V——指令集spec阅读笔记——向量扩展0.9 ](https://blog.csdn.net/qq_39815222/article/details/109570539
)(From blog.csdn.net 2020.11.14)"
- "[[MCU应用开发] 【RISC-V MCU CH32V103测评】Part3：王小琪之下载程序的三种方法 ](https://bbs.21ic.com/icview-3045380-1-1.html
)(From bbs.21ic.com 2020.11.14)"
- "[关于 CPU 你需要了解的 ](https://my.oschina.net/u/4732490/blog/4710404
)(From my.oschina.net 2020.11.14)"
- "[[RISCV]为RISC-V移植FreeRTOS -- 目录结构 ](https://blog.csdn.net/wangyijieonline/article/details/109677855
)(From blog.csdn.net 2020.11.14)"
- "[MODE-CSR相关 ](https://blog.csdn.net/m0_52050582/article/details/109672677
)(From blog.csdn.net 2020.11.14)"
- 
- "[ARM架构的STM32F103和RISC-V架构的CH32V103对比 ](https://blog.csdn.net/wsq_666/article/details/109686718
)(From blog.csdn.net 2020.11.14)"
- "[Mini ITX Linux RISC-V开发板 ](https://sff.design/16815.html
)(From sff.design 2020.11.14)"
- "[Nuclei Studio 对 GD32VF103 Debug 设置 ](https://blog.csdn.net/qq_43588817/article/details/109694006
)(From blog.csdn.net 2020.11.19)"

---

<a name="5NYql"></a>
# 一周论文
<br />
<a name="uOKKb"></a>
### [A Minimal RISC-V Vector Processor for Embedded Systems](https://ieeexplore.ieee.org/abstract/document/9232940)
M Johns, TJ Kazmierski - 2020 Forum for Specification and Design Languages …, 2020<br />This paper presents the first RISC-V vector processor design aimed at<br />microcontrollers that uses the new RISC-V 'V'extension for vectors, part of the open-<br />source RISC-V instruction set architecture (ISA). Being aimed at small embedded …<br />

<a name="NHEqe"></a>
### [Following the Pebble Trail: Extending Return-Oriented Programming to **RISC**-**V**](https://dl.acm.org/doi/abs/10.1145/3411495.3421366)
BP Deac, A Colesa - Proceedings of the 2020 ACM SIGSAC Conference on …, 2020<br />It is widely known that return-oriented programming (ROP) attack can be mounted on<br />x86, ARM and SPARC architectures. However, it remained an open question if ROP<br />was possible on **RISC**-**V**, a new and promising free and open instruction set …<br />

<a name="xR9Zr"></a>
### [Functional and Formal Verification on submodules of a Vector Processing Unit based on **RISC**-**V **V-extension](https://webthesis.biblio.polito.it/16044/)
VL Guglielmi - 2020<br />This thesis was developed while working at Barcelona Supercomputing Center, a<br />research center specialized in High Performance Computing and investigation in<br />many fields, such as cloud computing, bioinformatics, material science and more …<br />

<a name="hpdB1"></a>
### [A Vector Processing Unit implementation for **RISC**-**V **Vector Extension: Functional Verification and Assertions on submodules.](https://webthesis.biblio.polito.it/16009/)
L Valente - 2020<br />Power dissipation and Energy consumption of digital circuits has emerged as an<br />important design parameter in the evaluation of microelectronic circuits. This has led<br />electronic architects to value Parallel Architectures that allow to perform many …<br />

<a name="vVDzm"></a>
### **[PDF]** [Implementing the Load Slice Core on a **RISC**-**V **based microarchitecture](https://www.diva-portal.org/smash/get/diva2:1497145/FULLTEXT01.pdf)
A Dalbom, T Svensson - 2020<br />As cores have become better at exposing Instruction-Level Parallelism (ILP), they<br />have become bigger, more complex, and consumes more power. These cores are<br />approaching the Power-and Memory-wall quickly. A new microarchitecture proposed …<br />

<a name="2VVz6"></a>
### **[PDF]** [A Vector Processing Unit implementation for **RISC**-**V **Vector Extension: Functional Verification and Assertions on submodules](https://webthesis.biblio.polito.it/16009/1/tesi.pdf)
L Lavagno, N Sonmez, L Valente<br />Power dissipation and Energy consumption of digital circuits have emerged as<br />important design parameters in the evaluation of microelectronic circuits. This has<br />led electronic architects to value Parallel Architectures that allow to perform many …<br />

<a name="dcQG0"></a>
### [Following the Pebble Trail: Extending Return-Oriented Programming to **RISC**-**V**](https://dl.acm.org/doi/abs/10.1145/3411495.3421366)
BP Deac, A Colesa - Proceedings of the 2020 ACM SIGSAC Conference on …, 2020<br />It is widely known that return-oriented programming (ROP) attack can be mounted on<br />x86, ARM and SPARC architectures. However, it remained an open question if ROP<br />was possible on **RISC**-**V**, a new and promising free and open instruction set …<br />

<a name="eTLqR"></a>
### [A Vector Processing Unit implementation for **RISC**-**V **Vector Extension: Functional Verification and Assertions on submodules.](https://webthesis.biblio.polito.it/16009/)
L Valente - 2020<br />Power dissipation and Energy consumption of digital circuits has emerged as an<br />important design parameter in the evaluation of microelectronic circuits. This has led<br />electronic architects to value Parallel Architectures that allow to perform many …<br />

<a name="9FR6j"></a>
### **[PDF]** [Implementing the Load Slice Core on a **RISC**-**V **based microarchitecture](https://www.diva-portal.org/smash/get/diva2:1497145/FULLTEXT01.pdf)
A Dalbom, T Svensson - 2020<br />As cores have become better at exposing Instruction-Level Parallelism (ILP), they<br />have become bigger, more complex, and consumes more power. These cores are<br />approaching the Power-and Memory-wall quickly. A new microarchitecture proposed …<br />

<a name="Nrnbz"></a>
### **[PDF]** [A Vector Processing Unit implementation for **RISC**-**V **Vector Extension: Functional Verification and Assertions on submodules](https://webthesis.biblio.polito.it/16009/1/tesi.pdf)
L Lavagno, N Sonmez, L Valente<br />Power dissipation and Energy consumption of digital circuits have emerged as<br />important design parameters in the evaluation of microelectronic circuits. This has<br />led electronic architects to value Parallel Architectures that allow to perform many …<br />

<a name="cgHJ3"></a>
### [Towards Designing a Secure **RISC**-**V **System-on-Chip: ITUS](https://link.springer.com/article/10.1007/s41635-020-00108-8)
VBY Kumar, S Deb, N Gupta, S Bhasin, J Haj-Yahya… - Journal of Hardware and …, 2020<br />A rising tide of exploits, in the recent years, following a steady discovery of the many<br />vulnerabilities pervasive in modern computing systems has led to a growing number<br />of studies in designing systems-on-chip (SoCs) with security as a first-class …<br />

<a name="hsT7e"></a>
### **[HTML]** [A **RISC**-**V **Simulator and Benchmark Suite for Designing and Evaluating Vector Architectures](https://dl.acm.org/doi/fullHtml/10.1145/3422667)
C Ramírez, CA Hernández, O Palomar, O Unsal… - ACM Transactions on …, 2020<br />Vector architectures lack tools for research. Consider the gem5 simulator, which is<br />possibly the leading platform for computer-system architecture research.<br />Unfortunately, gem5 does not have an available distribution that includes a flexible …<br />

<a name="ZjEH0"></a>
### [Design and Implementation of a 32-bit ISA **RISC**-**V **Processor Core using Virtex-7 and Virtex-UltraScale](https://ieeexplore.ieee.org/abstract/document/9250850/)
A Singh, N Franklin, N Gaur, P Bhulania - 2020 IEEE 5th International Conference on …, 2020<br />In this paper, a 32-bit Datapath with **RISC**-**V **instruction set architecture based on<br />RV32I CPU instruction set has been designed. Furthermore, through analysis of<br />function and theory of **RISC**-**V **CPU instruction set, the processor has been optimized …<br />

<a name="kyA3A"></a>
### [A **RISC**-**V **Processor Design for Transparent Tracing](https://www.mdpi.com/2079-9292/9/11/1873)
I Gamino del Río, A Martínez Hellín, Ó R Polo… - Electronics, 2020<br />Code instrumentation enables the observability of an embedded software system<br />during its execution. A usage example of code instrumentation is the estimation of<br />“worst-case execution time” using hybrid analysis. This analysis combines static …
<a name="PJFz0"></a>
### [Towards Quality-Driven Approximate Software Generation for Accurate Hardware: Work-in-Progress](https://ieeexplore.ieee.org/abstract/document/9243814/)
J Castro-Godínez, M Shafique, J Henkel - 2020 International Conference on …, 2020<br />… We present results of automated approximate software generated with AxSWGen and<br />executed on a **RISC**-**V** processor (SiFive HiFive1 board), achieving up to 50% energy<br />reduction for a 5% image degradation for an approximate Gaussian filter …<br />

<a name="Yw6o8"></a>
### [Hardware support for managed languages: an old idea whose time has finally come?(keynote)](https://dl.acm.org/doi/abs/10.1145/3426182.3431580)
M Maas - Proceedings of the 17th International Conference on …, 2020<br />… efficiently than a CPU. I will also talk about current work within the open-source<br />**RISC**-**V** project on developing standard extensions for managed-language support<br />in the context of the free and open **RISC**-**V** ISA. Finally, I will …<br />

<a name="lWjsj"></a>
### [Hardware support for a novel variable precision floating point format in a scientific computing environment.](https://webthesis.biblio.polito.it/16057/)
R Alidori - 2020<br />… and execution latency. Besides the SoA, three additional formats are proposed in<br />this work: Custom Posit, Not Contiguous Posit and Modified Posit. This work is<br />implemented in a **RISC**-**V** environment. This architecture supports …<br />

<a name="d25668e7"></a>
### **[PDF]** [Design and Integration of a Debug Unit for Heterogeneous System-on-Chip Architectures](https://webthesis.biblio.polito.it/16008/1/tesi.pdf)
G Tombesi - 2020<br />… integration challenges in heterogeneous systems. In most of the cases, the instruction<br />set architecture (ISA) of the **RISC**-**V**1 project is leveraged for the processor cores of<br />the proposed platforms. Among the existing implementations …<br />

<a name="9d4d82e0"></a>
### **[PDF]** [SMALL BUT MIGHTY: EMERGING MARKET TRENDS ON THE CUTTING EDGE OF CHANGE](https://www.franklintempleton.lu/content-ftthinks/common-pdf/small-but-mighty-emerging-market-trends-on-the-cutting-edge-of-change/small-but-mighty-emerging-market-trends-on-the-cutting-edge-of-change-a.pdf)
F Templeton<br />… The first biometric wearable containing an “edge AI chip” ie,<br />microprocessors embedded with machine-learning algorithms, was based<br />on open-source **RISC**-**V** chip architecture, launched by scientists at the …<br />

<a name="766cbbf5"></a>
### [Fault Classification and Vulnerability Analysis of Microprocessors](https://repository.tudelft.nl/islandora/object/uuid:4c85a1ba-2721-4563-bb13-31d506d9c906)
P Talluri - 2020<br />… Its main steps comprises design instrumentation, simulation based fault injection and<br />automatic fault classification. **RISC**-**V** is chosen as the target architecture due to its open<br />source nature and its increasing adoption by academia and industry …<br />

<a name="07561319"></a>
### **[PDF]** [Benchmarking micro-core architectures for detecting disasters at the edge](https://arxiv.org/pdf/2011.04983)
M Jamieson, N Brown - arXiv preprint arXiv:2011.04983, 2020<br />… When choosing an IoT architecture, whether it be a physical chip or<br />soft-core, it is important that the choice made is a good one, however with<br />over 40 implementations of the **RISC**-**V** architecture alone, the ability to …<br />

<a name="3c98a0ca"></a>
### **[PDF]** [Automated fault injection in Verilog hardware designs](https://project-archive.inf.ed.ac.uk/ug4/20201672/ug4_proj.pdf)
JK Szewczyk<br />… The tool also worked correctly on larger designs: an Intel 8051‑compatible<br />core and a **RISC**‑**V** processor used in labs for the CArD course. Page 3.<br />Contents … 3 • Generating correct Verilog with fault injection for a **RISC**‑**V** code …<br />

<a name="6c216384"></a>
### [Progress-aware Dynamic Slack Exploitation in Mixed-critical Systems: Work-in-Progress](https://ieeexplore.ieee.org/abstract/document/9244032/)
A Kritikakou, S Skalistis - 2020 International Conference on Embedded Software …, 2020<br />… In this preliminary experimental set-up, we consider the PULP **RISC**-**V**<br />processor of GAP8 platform [10] as our platform model … [10] E. Flamand,<br />D. Rossi, F. Conti, I. Loi, A. Pullini, F. Rotenberg, and L. Benini, “Gap-8: A …<br />

<a name="d334dae8"></a>
### **[PDF]** [Open-Source EDA: If We Build It, Who Will Come?](https://vlsicad.ucsd.edu/Publications/Conferences/378/c378.pdf)
AB Kahng<br />… Following are some preliminary thoughts.5 Open-source EDA is part of a movement. The<br />open hardware community will use OpenROAD. A vi- brant open-source hardware<br />ecosystem sparked by **RISC**-**V** has grown rapidly in recent years [32], [34], [45] …<br />

<a name="oPPQW"></a>
### [Performance and power consumption analysis of Arm Scalable Vector Extension](https://link.springer.com/article/10.1007/s11227-020-03495-5)
T Odajima, Y Kodama, M Sato - The Journal of Supercomputing, 2020<br />… Therefore, we employ gem5, which is a general-purpose processor simulator, used<br />to evaluate SVE architecture. Additionally, gem5 supports several kinds of processors<br />such as Alpha, Arm, SPARC, x86, **RISC**-**V**, and GPU …<br />


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

