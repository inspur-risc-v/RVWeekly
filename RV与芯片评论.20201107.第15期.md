# RV与芯片评论.20201107.第15期


<br />本期概要<br />上周最大的新闻就是SiFive的板子了，以至于RV国际连发四篇新闻来讲这个。<br />这周又有许多IP商取得了成果：泰凌微+Andes，CodaSip+NeuLinker，NSITEX+CodePlay<br />但是有调查显示，Linux届依然有一半人不知道RISC-V是什么。<br />本周有两篇优秀的技术文章值得一看，一个是使用[向量指令加速AI算法的挑战](https://www.yuque.com/riscv/rvnews/eobkn3)，另一个是[RISC-V的指令集设计有没有值得改善的地方](https://www.yuque.com/riscv/rvnews/ffxa5o)。<br />此外还有大量的论文值得阅读。<br />


---



<a name="u1qhF"></a>
### 相关周报

- "[【一周】PHP composer 2.0 | .NET版本Spark 1.0 | 最快的RISC-V的商用内核 | Facebook也吃上QUIC  ](https://www.oschina.net/question/3820517_2319624
)(From www.oschina.net 2020.11.01)"
- 
- 
- 
- "[泰晓资讯 : 2020 年 10 月 第 四 期 ](https://mp.weixin.qq.com/s/wmO889sWDnIvFN5nggslcQ
)(From mp.weixin.qq.com 2020.11.07)"
- "[OSDT Weekly 2020-11-05 第070期 ](https://mp.weixin.qq.com/s/bQlOdzoIIOQPIhHym2A0NA
)(From mp.weixin.qq.com 2020.11.05)"
- "[PLCT开源进展·第12期·2020年11月01日 ](https://zhuanlan.zhihu.com/p/271624898
)(From zhuanlan.zhihu.com 2020.11.01)"




---



<a name="nqDGS"></a>
# 技术动态

- 
- <br />
<a name="NupUV"></a>
### 使用向量指令加速AI的挑战


<a name="2pZEL"></a>
### ARM工程师如何设计一个更好的RISC-V
<a name="uJMaJ"></a>
### Linux动态

- "[[PULL v2 07/19] target/riscv: Add V extension state description ](https://www.mail-archive.com/qemu-devel@nongnu.org/msg756938.html
)(From www.mail-archive.com 2020.11.03)"
- "[[PULL v2 03/19] target/riscv: Merge m/vsstatus and m/vsstatush into one uint64_t unit ](https://www.mail-archive.com/qemu-devel@nongnu.org/msg756952.html
)(From www.mail-archive.com 2020.11.03)"
- "[Re: [RFC PATCH 2/3] RISC-V: Initial DTS for Microchip ICICLE board ](https://lkml.org/lkml/2020/11/3/682
)(From lkml.org 2020.11.03)"
- "[Re: [RFC PATCH 3/3] RISC-V: Enable Microchip PolarFire ICICLE SoC ](https://www.mail-archive.com/linux-kernel@vger.kernel.org/msg2364926.html
)(From www.mail-archive.com 2020.11.03)"
- "[[PATCH] RISC-V: Use non-PGD mappings for early DTB access ](https://www.spinics.net/lists/kernel/msg3722751.html
)(From www.spinics.net 2020.11.04)"
- "[Re: [PATCH v4] riscv: Enable per-task stack canaries ](https://lkml.org/lkml/2020/11/4/394
)(From lkml.org 2020.11.04)"
- "[[PATCH v3 4/5] RISC-V: Protect all kernel sections including init early ](https://www.mail-archive.com/linux-kernel@vger.kernel.org/msg2368242.html
)(From www.mail-archive.com 2020.11.04)"
- "[[PATCH v3 0/5] Improve kernel section protections ](https://www.mail-archive.com/linux-kernel@vger.kernel.org/msg2368240.html
)(From www.mail-archive.com 2020.11.04)"
- "[Re: [PATCH AUTOSEL 4.19 28/60] riscv: Define AT_VECTOR_SIZE_ARCH for ARCH_DLINFO ](https://lkml.org/lkml/2020/11/6/9
)(From lkml.org 2020.11.05)"
- "[Re: [PATCH v4 1/9] RISC-V: Implement ptrace regs and stack API ](https://lkml.org/lkml/2020/11/5/1524
)(From lkml.org 2020.11.05)"
- "[Re: [PATCH v4 0/5] Unify NUMA implementation between ARM64 & RISC-V ](https://www.mail-archive.com/linux-kernel@vger.kernel.org/msg2369334.html
)(From www.mail-archive.com 2020.11.05)"
- "[[PATCH 08/32] riscv: Fix kernel time_init() ](https://www.spinics.net/lists/linux-spi/msg24904.html
)(From www.spinics.net 2020.11.07)"
- "[[PATCH 00/32] RISC-V Kendryte K210 support improvments ](https://www.spinics.net/lists/linux-spi/msg24896.html
)(From www.spinics.net 2020.11.07)"
- "[Re: [PATCH 19/32] riscv: Add Kendryte K210 SoC reset controller ](https://www.spinics.net/lists/linux-gpio/msg54696.html
)(From www.spinics.net 2020.11.07)"
- "[[PATCH 32/32] riscv: Update Kendryte K210 defconfig ](https://www.spinics.net/lists/linux-gpio/msg54685.html
)(From www.spinics.net 2020.11.07)"



<a name="v2ah0"></a>
### 一周问答

- "[why is it the branch type instructions have confusing format in RISC-V ISA?  ](https://stackoverflow.com/questions/64691699/why-is-it-the-branch-type-instructions-have-confusing-format-in-risc-v-isa
)(From stackoverflow.com 2020.11.07)"
- "[How to print memref value on a RISC-V backend? ](https://llvm.discourse.group/t/how-to-print-memref-value-on-a-risc-v-backend/2118
)(From llvm.discourse.group 2020.11.07)"
- "[How do I calculate the total cycle of risc-v instructions? [closed]  ](https://stackoverflow.com/questions/64705907/how-do-i-calculate-the-total-cycle-of-risc-v-instructions
)(From stackoverflow.com 2020.11.07)"
<a name="CC8oT"></a>
### 社区动态

- "[Issue: ESP32-S2 ULP RISC-V no evidence of running (IDFGH-4210) #6069 ](https://github.com/espressif/esp-idf/issues/6069
)(From github.com 2020.11.07)"
- "[Running program which has custom instruction in SPIKE simulator results error ](https://forums.sifive.com/t/running-program-which-has-custom-instruction-in-spike-simulator-results-error/4158
)(From forums.sifive.com 2020.11.07)"

<br />

---

<a name="SM5cC"></a>
# 产业风云

- "[乐鑫科技面临业绩大考:两款产品打天下 账上超七成是现金 ](https://finance.sina.com.cn/wm/2020-11-04/doc-iiznezxr9937355.shtml
)(From finance.sina.com.cn 2020.11.05)"
- "[没有杀手级应用 只有物联网+区块链构建的“杀手级”生态网络 ](https://www.big-bit.com/news/363757.html
)(From www.big-bit.com 2020.11.05)"
- "[Microchip Technology Announces Financial Results for Second Quarter of Fiscal Year 2021 ](https://www.globenewswire.com/news-release/2020/11/05/2121571/0/en/Microchip-Technology-Announces-Financial-Results-for-Second-Quarter-of-Fiscal-Year-2021.html
)(From www.globenewswire.com 2020.11.07)"
- 
- 



<a name="QPFhS"></a>
### Micro Magic的5Ghz芯片后续
<a name="PDaZK"></a>
### SiFive 的 HiFive Unmatch PC板子余热

<a name="PO7vP"></a>
### 泰凌微 + 晶心科技：TLSR9
<a name="bIkVL"></a>
### CodaSip + NeuLinker： BK5核心
<a name="xcBzC"></a>
### NSITEX + CodePlay：LLVM向量处理器
<a name="JhmZ4"></a>
### Valtrix加入RV国际


Andes AX45: 8阶超标量流水线的64Bit处理器
<a name="cGGp8"></a>
### 评论文集

- "[大卫·帕特森：汇聚世界资源促进技术创新  ](https://www.sohu.com/a/428860198_162758
)(From www.sohu.com 2020.11.02)"
> 在深圳全球创新人才论坛上，身处异国的大卫·帕特森通过虚拟影像做了演讲分享，听众强烈感受到他对RISC-V（第五代精简指令集）、对深圳、对国际合作的热忱。

- "[倪光南：中国在开源芯片方向上有可能取得突破 可规避限制政策 ](https://www.cnbeta.com/articles/tech/1048801.htm
)(From www.cnbeta.com 2020.11.03)"
> 11月3日，在湖南长沙举行的2020年世界计算机大会上，中国工程院院士倪光南表示，中国在开源芯片方向上有可能取得突破，并规避美国可能采取的限制政策。

- "[Arm and NVIDIA – The unthinkable pt. II. ](https://radiofreemobile.com/2020/11/06/arm-and-nvidia-the-unthinkable-pt-ii/
)(From radiofreemobile.com 2020.11.06)"
- "[Open-Source RISC-V ISA Offers More ](https://www.designnews.com/design-software/open-source-risc-v-isa-offers-more
)(From www.designnews.com 2020.11.07)"
- "[AI Compilers and the Race to the Bottom ](https://www.embedded-computing.com/articles/ai-compilers-and-the-race-to-the-bottom
)(From www.embedded-computing.com 2020.11.07)"
- 
<a name="ZLzjf"></a>
### 其他产业

- "[Huawei is building a new chip factory to circumvent US ban ](https://www.gsmarena.com/huawei_is_building_a_new_chip_factory_that_wont_use_us_technology-news-46072.php
)(From www.gsmarena.com 2020.11.02)"
- "[光电子芯片技术的原理和优势是什么？如何取代传统的 I/O 形式？ ](https://www.eet-china.com/kj/1604629823.html
)(From www.eet-china.com 2020.11.07)"
> 初创公司Ayar Labs结合光学和电子学技术，研制出了速度更快、效率更高的新型光电子芯片，与传统电信号传输方案相比，它的优势和原理是什么呢？这种光学小芯片和多波长激光器不仅产生更少的热量、信号传输的延时更低，且不易受到温度、磁场、噪声变化等情况的影响。Ayar Labs 的技术攻关方向，就是要取代传统的 I/O 形式。


---



<a name="tAplU"></a>
# 其他动态


<a name="96Tpz"></a>
### 调查显示Linux届有一半人不知道RISC-V
<a name="tO9Sj"></a>
### 课件推荐：RISC-V和向量指令
"[RISC-V and Vector Computing ](https://www.coursehero.com/file/71817705/Lecture-26-Vector-Computing-updatepdf/
)(From www.coursehero.com 2020.11.07)"
<a name="bTjLG"></a>
### 开源开发板：RED-V RedBoard
> RED-V RedBoard 是 SparkFun 出品的开源开发板，主控芯片是基于 RISC-V 架构的 SoC SiFive FE310。FE310 是全球第一款基于 RISC-V 架构的 32 位商用 SoC，采用了 180nm 的工艺，最大工作频率可以到 320MHz，性能大致相当于 Arm Cortex-M3。

"[【RED-V】基于 RISC-V 架构的开源开发板 ](https://blog.csdn.net/lu_embedded/article/details/109484394
)(From blog.csdn.net 2020.11.07)"

<a name="5nmT5"></a>
### 开发板：DT-BL10
<a name="zWhAs"></a>
### 博文推荐


- "[RISC-V Datapath Part4: Pipeline ](https://zhuanlan.zhihu.com/p/267576239
)(From zhuanlan.zhihu.com 2020.10.22)"
- "[ESP32跟RISC-V成功“联姻” HiFive1 Rev B与HiFive1区别 ](http://bigdata.ctocio.com.cn/bigdata/2020/1104/45907.html
)(From bigdata.ctocio.com.cn 2020.11.07)"
- "[RISC-V邮件列表阅读笔记（20201025--20201107） ](https://zhuanlan.zhihu.com/p/272539934
)(From zhuanlan.zhihu.com 2020.11.07)"
- "[RISC-V 特权指令集入门 ](https://juejin.im/post/6891962672892837901
)(From juejin.im 2020.11.07)"
- "[QEMU RISC-V virt 平台分析 ](https://juejin.im/post/6891922292075397127
)(From juejin.im 2020.11.07)"
- "[[MCU应用开发] 【RISC-V MCU CH32V103测评】RTC电子时钟 ](https://bbs.21ic.com/icview-3044346-1-1.html
)(From bbs.21ic.com 2020.11.07)"
- "[Real-Time Operating System (RTOS): A Simple Guide ](https://all3dp.com/2/rtos-real-time-operating-system-os-examples/
)(From all3dp.com 2020.11.07)"
- OpenJ9构建测试及OpenJDK移植进展简介（RISC-V） 张定立 - 20201107 - PLCT实验室
   - [https://www.bilibili.com/video/BV1ka411c7Us](https://www.bilibili.com/video/BV1ka411c7Us)
- "[在蜂鸟FPGA评估板上运行MLIR GEMM ](https://zhuanlan.zhihu.com/p/272179056?utm_source=wechat_session&utm_medium=social&utm_oi=643718314095022080&utm_content=group3_article&utm_campaign=shareopn
)(From zhuanlan.zhihu.com 2020.11.07)"

---

<a name="5NYql"></a>
# 一周论文
<a name="wUeSb"></a>
### [Risk-5: Controlled Approximations for **RISC**-**V**](https://ieeexplore.ieee.org/abstract/document/9211571/)
I Felzmann, J Fabrício Filho, L Wanner - … Transactions on Computer-Aided Design of …, 2020<br />Approximate Computing offers enhanced energy efficiency by exploring quality<br />relaxation on applications. Application-agnostic hardware-level techniques can<br />provide high benefits under certain scenarios, but their integration on a general …
<a name="Vd2Oa"></a>
### **[PDF]** [Design and Development of an Efficient Branch Predictor for an In-order **RISC**-**V **Processor](https://essuir.sumdu.edu.ua/bitstream/123456789/80515/1/Arul_Rathi_jnep_5_2020.pdf)
C Arul Rathi, G Rajakumar, T Ananth Kumar… - 2020<br />Conditional branches are a serious issue in the pipelined processor. The branch<br />direction and branch target address are determined and calculated by the processor<br />after several cycles of the instruction decode, which results in the pipeline stall …
<a name="BLcyz"></a>
### **[PDF]** [On-Board Satellite Telemetry Forecasting with RNN on **RISC**-**V **Based Multicore Processor](https://www.researchgate.net/profile/Marco_Ottavi/publication/344829368_On-Board_Satellite_Telemetry_Forecasting_with_RNN_on_RISC-V_Based_Multicore_Processor/links/5f9a5e80a6fdccfd7b87fb1d/On-Board-Satellite-Telemetry-Forecasting-with-RNN-on-RISC-V-Based-Multicore-Processor.pdf)
D Cappellone, S Di Mascio, G Furano, A Menicucci…<br />The aim of this paper is to assess the feasibility and on-board hardware performance<br />requirements for on-board telemetry forecasting by implementing a Recurrent Neural<br />Network (RNN) on low-cost multicore **RISC**-**V **microprocessor. Gravity field and …<br />

<a name="KSBKA"></a>
### [A Dual-Core **RISC**-**V **Vector Processor With On-Chip Fine-Grain Power Management in 28-nm FD-SOI](https://ieeexplore.ieee.org/document/9241430/)
JC Wright, C Schmidt, B Keller, DP Dabbelt, J Kwak… - IEEE Transactions on Very …, 2020<br />This work demonstrates a dual-core **RISC**-**V **system-on-chip (SoC) with integrated<br />fine-grain power management. The 28-nm fully depleted silicon-on-insulator (FD-<br />SOI) SoC integrates switched-capacitor voltage converters and 4 Gb/s off-chip serial …
<a name="yrap6"></a>
### [Design Flow for Active Interposer-Based 2.5 D ICs and Study of **RISC**-**V **Architecture with Secure NoC](https://ieeexplore.ieee.org/abstract/document/9235512/)
H Park, J Kim, VCK Chekuri, MA Dolatsara, M Nabeel… - IEEE Transactions on …, 2020<br />Interposer-based 2.5 D integrated circuits (ICs) enable the chip-level reuse of hard<br />intellectual properties (IPs), also known as chiplets. Such system-level integration<br />shortens the design cycle considerably for large-scale and heterogeneous chips …
<a name="xDIhB"></a>
### **[PDF]** [RV-Across: An Associative Processing Simulator](http://wscad.sbc.org.br/2020/artigos/trilha-principal/s03p02-209266-1.pdf)
J Silveira, I Felzmann, JF Filho, L Wanner<br />… Emerging big data applications can be significantly sped-up by Associative<br />Processing, but validation and evaluation are key challenges. We present<br />RV- Across, a **RISC**-**V** Associative Processing Simulator for testing …
<a name="DjHFA"></a>
### [A Minimal **RISC**-**V **Vector Processor for Embedded Systems](https://ieeexplore.ieee.org/abstract/document/9232940/)
M Johns, TJ Kazmierski - 2020 Forum for Specification and Design Languages …, 2020<br />This paper presents the first **RISC**-**V **vector processor design aimed at<br />microcontrollers that uses the new **RISC**-**V **'V'extension for vectors, part of the open-<br />source **RISC**-**V **instruction set architecture (ISA). Being aimed at small embedded …
<a name="WZ89q"></a>
### **[PDF]** [RVCoreP-32IM: An effective architecture to implement mul/div instructions for five stage **RISC**-**V **soft processors](https://arxiv.org/pdf/2010.16171)
MA Islam, H Miyazaki, K Kise - arXiv preprint arXiv:2010.16171, 2020<br />**RISC**-**V**, an open instruction set architecture, is getting the attention of soft processor<br />developers. Implementing only a basic 32-bit integer instruction set of **RISC**-**V**, which<br />is defined as RV32I, might be satisfactory for embedded systems. However …
<a name="LcD3X"></a>
### [Deep Learning on Low Power Embedded Devices Using **RISC**-**V **Cores with an Extended Instruction Set](https://dk.um.si/IzpisGradiva.php%3Fid%3D77360)
J Vreča - 2020<br />This thesis explores the possibility of running neural networks on microcontrollers<br />and how to optimize their performance using instruction set extensions.<br />Microcontrollers are seen as too weak to run neural networks. We challenge this …
<a name="3NL4r"></a>
### [RVCoreP-32IM: An effective architecture to implement mul/div instructions for five stage **RISC**-**V **soft processors](https://ui.adsabs.harvard.edu/abs/2020arXiv201016171A/abstract)
M Ashraful Islam, H Miyazaki, K Kise - arXiv e-prints, 2020<br />**RISC**-**V**, an open instruction set architecture, is getting the attention of soft processor<br />developers. Implementing only a basic 32-bit integer instruction set of **RISC**-**V**, which<br />is defined as RV32I, might be satisfactory for embedded systems. However …<br />

<a name="OHyLF"></a>
### [Memory array data structure for posit operations](https://patents.google.com/patent/US20200301605A1/en)
VS Ramesh - US Patent App. 16/358,971, 2020<br />US20200301605A1 - Memory array data structure for posit operations - Google<br />Patents. Memory array data structure for posit operations. Download PDF Info.<br />Publication number US20200301605A1. US20200301605A1 US16 … 
<a name="6luYD"></a>
### [ABCFI: Fast and Lightweight Fine-Grained Hardware-Assisted Control-Flow Integrity](https://ieeexplore.ieee.org/abstract/document/9211437/)
J Li, L Chen, G Shi, K Chen, D Meng - IEEE Transactions on Computer-Aided Design …, 2020<br />… ASLR. V. IMPLEMENTATION We implemented ABCFI in two stages to evaluate it:<br />to eval- uate the hardware overhead, we implement ABCFI on Rocket Core [39] (an<br />opensource in-order CPU based on **RISC**-**V** ISA). To evaluate …
<a name="gcnPb"></a>
### **[HTML]** [Silicon photonics for telecom and data-com applications](http://www.oejournal.org/J/OEA/Article/Details/A201030000006)
K Asakawa, Y Sugimoto, S Nakamura - Opto-Electronic Advances, 2020<br />… thermal tuning. IEEE J Solid-State Circuits 51, 893–907 (2016). 57. Lee Y, Waterman<br />A, Avizienis R, Cook H, Sun C et al. A 45nm 1.3GHz 16.7 double-precision<br />GFLOPS/W **RISC**-**V** processor with vector accelerators. In ESSCIRC …
<a name="2aYx9"></a>
### [FINDER: Find Efficient Parallel Instructions for ASIPs to Improve Performance of Large Applications](https://ieeexplore.ieee.org/abstract/document/9211431/)
V Gnanasambandapillai, J Peddersen, R Ragel… - IEEE Transactions on …, 2020<br />Page 1. IEEE TRANSACTIONS ON COMPUTER-AIDED DESIGN OF INTEGRATED<br />CIRCUITS AND SYSTEMS, VOL. 39, NO. 11, NOVEMBER 2020 3577 FINDER: Find<br />Efficient Parallel Instructions for ASIPs to Improve Performance of Large Applications …<br />
<br />

<a name="Di7aZ"></a>
### [Automatic identification and hardware implementation of a resource-constrained power model for embedded systems](https://www.sciencedirect.com/science/article/pii/S2210537920301918)
L Cremona, W Fornaciari, D Zoni - Sustainable Computing: Informatics and Systems, 2020<br />… For the evaluation of this work we analyzed both HLS generated hardware<br />accelerators and a hand-made designed **RISC**-**V** processor, showing that<br />our methodology is effective against any type of target hardware, even in …
<a name="vIPmc"></a>
### [Protecting Enclaves from Intra-Core Side-Channel Attacks through Physical Isolation](https://dl.acm.org/doi/abs/10.1145/3411505.3418437)
M van der Maas, SW Moore - Proceedings of the 2nd Workshop on Cyber-Security …, 2020<br />… 2019. The **RISC**-**V** Instruction Set Manual, Volume II: Privileged Architecture,<br />v1. 11 … The Internet Society, Reston, VA, USA, 15. [https://www.ndss-symposium](https://www.ndss-symposium/).<br />org/ndss-paper/timber-v-tag-isolated-memory-bringing-fine-grained-enclaves …
<a name="cBl6p"></a>
### **[PDF]** [CURE: A Security Architecture with CUstomizable and Resilient Enclaves](https://arxiv.org/pdf/2010.15866)
R Bahmani, F Brasser, G Dessouky, P Jauernig… - arXiv preprint arXiv …, 2020<br />… CURE requires minimal hardware changes while significantly improving<br />the state of the art of hardware- assisted security architectures. We<br />implemented CURE on a **RISC**-**V**-based SoC and thoroughly evaluated …
<a name="dfmN7"></a>
### **[PDF]** [A Fast Learning-Driven Signoff Power Optimization Framework](http://www.gtcad.gatech.edu/www/papers/lu-iccad20.pdf)
YC Lu, S Nath, SSK Pentapati, SK Lim<br />… Experimental results on 14 in- dustrial designs, including a **RISC**-**V**-based<br />multi-core system and the renowned ISPD-2012 benchmarks, demonstrate<br />that our frame- work achieves up to 14X runtime improvement with similar …
<a name="1yDmO"></a>
### [NoC Symbiosis:(Special Session Paper)](https://ieeexplore.ieee.org/abstract/document/9241584/)
D Petrisko, C Zhao, S Davidson, P Gao - … 14th IEEE/ACM International Symposium on …, 2020<br />… NOC SYMBIOSIS IN THE WILD We first encountered NoC Symbiosis in<br />BlackParrot (BP): a tiled, cache-coherent, Linux-capable **RISC**-**V** multicore<br />in- troduced in [3]. BlackParrot implements the **RISC**-**V** 64-bit RV64G ISA …
<a name="G6Mn4"></a>
### [Switched-Capacitor Boost-Buck Ladder Converters With Extended Voltage Range in Standard CMOS](https://ieeexplore.ieee.org/abstract/document/9219169/)
J Liu, S Gregori - IEEE Transactions on Circuits and Systems I: Regular …, 2020<br />Page 1. This article has been accepted for inclusion in a future issue of this journal.<br />Content is final as presented, with the exception of pagination. IEEE TRANSACTIONS<br />ON CIRCUITS AND SYSTEMS–I: REGULAR PAPERS 1 …

---


<br />RISC-V与芯片评论编辑部 - RISC-V和芯片动态周报<br />每周六发布<br />欢迎批评，指正，评论和加入<br />
<br />关于本刊: 

- 非特殊注明，本刊消息均来自于网络，如有版权问题，我们会立刻处理。
- [本刊部分消息来源](https://www.yuque.com/riscv/rvnews/overview#vHVQ5)




| 微信公众号<br />![image.png](https://cdn.nlark.com/yuque/0/2020/png/1541992/1602320139392-1297e86a-ac06-4d76-a000-ad4307cd488c.png#align=left&display=inline&height=187&margin=%5Bobject%20Object%5D&name=image.png&originHeight=440&originWidth=465&size=225442&status=done&style=none&width=198) | Gitee

[https://gitee.com/inspur-risc-v/RVWeekly](https://gitee.com/inspur-risc-v/RVWeekly) | Github

[https://github.com/inspur-risc-v/RVWeekly](https://github.com/inspur-risc-v/RVWeekly) | 语雀

[https://www.yuque.com/riscv/rvnews](https://www.yuque.com/riscv/rvnews) |
| --- | --- | --- | --- |

