# RV与芯片评论.20201010.第11期

本期概要：

- [Linley秋季处理器会议开始注册](https://www.yuque.com/riscv/rvnews/20201011#F30Fk)
- RISC-V获得了更多的支持：[Linux UEFI](#NnNqO)，[UDE](#fcMGH), [Nokia](#dEEfF)，[瑞萨](#i2KYO)，[Maxim](#qG6pb)。
- 甚至有了更多的[本科生芯片](#MXwXc)流片
- [一周RISC-V问答](https://www.yuque.com/riscv/rvnews/20201011#a8hhr)
- [这些论文值得一看](https://www.yuque.com/riscv/rvnews/20201011#5NYql)
- [这些博文值得新人入门](https://www.yuque.com/riscv/rvnews/20201011#2xvIA)

---

<a name="cgX2z"></a>
# 重点聚焦

- 
- 
- "[如何看待 AMD 2020.10.8（当地时间）发布的 Zen3 处理器？有哪些亮点和不足？ ](https://www.zhihu.com/question/420324699
)(From www.zhihu.com 2020.10.08)"
<a name="F30Fk"></a>
### Linley秋季处理器会议开始注册
相关新闻

- 

<br />
<a name="a8hhr"></a>
### 相关周报

- "[Blog Review: Oct. 7 ](https://semiengineering.com/blog-review-oct-7-2/
)(From semiengineering.com 2020.10.07)"
- "[Product of the Week: Microchip PolarFire SoC FPGA Icicle Kit ](https://www.embedded-computing.com/latest-blogs/product-of-the-week-microchip-polarfire-soc-icicle-kit
)(From www.embedded-computing.com 2020.10.07)"
- "[Week In Review: Design, Low Power ](https://semiengineering.com/week-in-review-design-low-power-115/
)(From semiengineering.com 2020.10.10)"

---

<a name="nqDGS"></a>
# 技术动态


<a name="NnNqO"></a>
### Linux5.10将支持UEFI for RISC-V
<a name="fcMGH"></a>
### UDE增加了对RISC-V架构的支持
<a name="GS7JP"></a>
### U-BOOT动态

- "[U-Boot 2020.10 Released With Many Improvements ](https://www.phoronix.com/scan.php?page=news_item&px=U-Boot-2020.10-Released
)(From www.phoronix.com 2020.10.07)"
<a name="hpgOZ"></a>
### Linux动态

- "[Re: [PATCH] crypto: jitterentropy - bind statically into kernel ](https://www.spinics.net/lists/linux-crypto/msg50884.html
)(From www.spinics.net 2020.10.04)"
- "[[PATCH v4 5/5] riscv: Add numa support for riscv64 platform ](https://lkml.org/lkml/2020/10/5/1386
)(From lkml.org 2020.10.05)"
- "[linux-next: manual merge of the akpm-current tree with the risc-v tree ](https://www.mail-archive.com/linux-kernel@vger.kernel.org/msg2334049.html
)(From www.mail-archive.com 2020.10.06)"
- "[Re: [PATCH] riscv: Fixup bootup failure with HARDENED_USERCOPY ](https://lkml.org/lkml/2020/10/7/100
)(From lkml.org 2020.10.07)"
- "[Re: [PATCH 2/2] riscv: Fixup static_obj() fail v2 ](https://lkml.org/lkml/2020/10/7/1099
)(From lkml.org 2020.10.07)"
- "[linux-next: manual merge of the risc-v tree with the risc-v-fixes tree ](https://lkml.org/lkml/2020/10/7/976
)(From lkml.org 2020.10.08)"
- <br />
<a name="v2ah0"></a>
### 一周问答

- RISC-V中的桑格乘法指令有什么区别
   - mulhsu是符号扩展寄存器和零扩展寄存器之间的乘法。
   - mulh是两个符号扩展寄存器的乘积。
   - mulhu是两个零扩展寄存器的乘积。
   - "[In the risc-v architecture, what do the bits returned by the mulh[[s]u] operation look like? ](https://stackoverflow.com/questions/64200706/in-the-risc-v-architecture-what-do-the-bits-returned-by-the-mulhsu-operatio
)(From stackoverflow.com 2020.10.07)"
- RISC-V中ra和sp寄存器的作用
   - **Caller-saved registers** (AKA **volatile** registers, or **call-clobbered**) are used to hold temporary quantities that need not be preserved across calls.
   - **Callee-saved registers** (AKA **non-volatile** registers, or **call-preserved**) are used to hold long-lived values that should be preserved across calls.
   - "[What's the difference between caller-saved and callee-saved in RISC-V ](https://stackoverflow.com/questions/64211181/whats-the-difference-between-caller-saved-and-callee-saved-in-risc-v
)(From stackoverflow.com 2020.10.07)"
   - "[Why $ra is Caller Saved in RISC-V ](https://stackoverflow.com/questions/59693334/why-ra-is-caller-saved-in-risc-v
)(From stackoverflow.com 2020.10.07)"
   - "[What are callee and caller saved registers? ](https://stackoverflow.com/questions/9268586/what-are-callee-and-caller-saved-registers
)(From stackoverflow.com 2020.10.07)"
- 硬件接口违反了协议规则会发生什么，如何使用形式验证分析协议安全问题
   - "[Chips Listening To Gibberish ](https://semiengineering.com/chips-listening-to-gibberish/
)(From semiengineering.com 2020.10.10)"
- <br />

---

<a name="5NYql"></a>
# 一周论文


<a name="Suqxd"></a>
### Building a Modern TRNG: An Entropy Source Interface for RISC-V
Markku-Juhani O. Saarinen and G. Richard Newell and Ben Marshall<br />"[Building a Modern TRNG: An Entropy Source Interface for RISC-V ](https://eprint.iacr.org/2020/866
)(From eprint.iacr.org 2020.10.10)"
> 目前提出的RISC-V真随机数生成器(TRNG)架构打破了以往ISA TRNG的做法，将熵源(ES)组件从密码学PRNG中分离出来，成为一个独立的接口，并在其使用轮询。我们描述了这个接口，它在密码学中的使用，并为它的各个方面提供了额外的讨论、背景和理由。这种设计参考了早期主流ISA的经验教训、最近引入的SP 800-90B和FIPS 140-3熵审计要求、AIS 31和Common Criteria、当前和新兴的加密需求（如后量子密码学）以及支持各种RISC-V实现和应用的目标。许多架构的选择是对安全微控制器、Linux内核和密码学库中的随机数发生器进行定量观察的结果。我们进一步将该架构与一些当代的随机数发生器进行比较，并描述了一个简约的TRNG参考实现，它与RISC-V AES指令一起使用熵源。



<a name="d583ea92"></a>
### **[PDF]** [An Embedded **RISC**-**V **Core with Fast Modular Multiplication](http://scholar.google.com/scholar_url?url=https://arxiv.org/pdf/2009.14685&hl=en&sa=X&d=3214310686435327347&ei=WF17X5rfA4yTyQS-4JHICQ&scisig=AAGBfm3OpllrzrVxHKgoCtjkGWVyZMzyvw&nossl=1&oi=scholaralrt&hist=AQxAsJ0AAAAJ:4202114184661953008:AAGBfm3D0OY4figMd-K5msYCl6aFfjtabQ&html=)
ÖF Irmak, A Yurdakul - arXiv preprint arXiv:2009.14685, 2020
> 物联网中最大的问题之一是隐私和安全。加密和认证需要大的功率预算，而电池操作的物联网终端节点并不具备这种能力。专为特定加密操作设计的硬件加速器几乎不提供未来更新的灵活性。自定义指令解决方案的面积更小，为新方法的实现提供了更大的灵活性。自定义指令的一个缺点是，处理器必须等待操作完成。最终，设备对实时事件的响应时间会变长。在这项工作中，我们提出了一种具有扩展的模块化乘法自定义指令的处理器，当在Partial Execution模式下使用时，通常情况下，任何大小的模块化乘法都会阻挡处理器两个周期。我们的概念验证CPU采用了RISC-V的嵌入式和压缩扩展。我们的设计在椭圆曲线密码学领域的最新密码算法上进行了基准测试。我们的128位模块化乘法的CPU在ASIC上的工作频率为136MHz，在FPGA上的工作频率为81MHz。它在软件实现上实现了13倍的速度，同时将整体功耗降低了95/%，比我们的基本架构平均面积开销减少了41/%。


<br />[https://arxiv.org/abs/2009.14685](https://arxiv.org/abs/2009.14685)<br />

<a name="c4b99427"></a>
### **[PDF]** [Bypassing Isolated Execution on **RISC**-**V **with Fault Injection](http://scholar.google.com/scholar_url?url=https://eprint.iacr.org/2020/1193.pdf&hl=en&sa=X&d=1608813345069362277&ei=WF17X5rfA4yTyQS-4JHICQ&scisig=AAGBfm3_U7Xh1kCJaebZFXzIK-O7TKOuXg&nossl=1&oi=scholaralrt&hist=AQxAsJ0AAAAJ:4202114184661953008:AAGBfm3D0OY4figMd-K5msYCl6aFfjtabQ&html=)
S Nashimoto, D Suzuki, R Ueno, N Homma<br />**RISC**-**V **is equipped with physical memory protection (PMP) to prevent malicious<br />software from accessing protected memory regions. One of the main objectives of<br />PMP is to provide a trusted execution environment (TEE) that isolates secure and …<br />

<a name="fjh98"></a>
### Enabling Virtual Memory Research on RISC-V with a Configurable TLB Hierarchy for the Rocket Chip Generator
Authors:[Nikolaos Charalampos Papadopoulos](https://arxiv.org/search/cs?searchtype=author&query=Papadopoulos%2C+N+C), [Vasileios Karakostas](https://arxiv.org/search/cs?searchtype=author&query=Karakostas%2C+V), [Konstantinos Nikas](https://arxiv.org/search/cs?searchtype=author&query=Nikas%2C+K), [Nectarios Koziris](https://arxiv.org/search/cs?searchtype=author&query=Koziris%2C+N), [Dionisios N. Pnevmatikatos](https://arxiv.org/search/cs?searchtype=author&query=Pnevmatikatos%2C+D+N)<br />[Download PDF](https://arxiv.org/pdf/2009.07723)
> Rocket Chip Generator使用一系列参数化的处理器组件来生产基于RISC-V的SoC。它是一个强大的工具，可以生产从微小的嵌入式处理器到复杂的多核系统的各种处理器设计。在本文中，我们扩展了Rocket Chip Generator的内存管理单元的功能，特别是TLB层次结构。TLB在性能方面是必不可少的，因为它们减轻了频繁的Page Table Walks的开销，但由于其大小和/或关联性，可能会损害处理器的关键路径。在最初的Rocket Chip实现中，L1指令/数据TLB是完全关联的，共享的L2 TLB是直接映射的。我们解除了这些限制，设计并实现了可配置的、集关联性的 L1 和 L2 TLB 模板，可以创建从直接映射到完全关联的任何组织，以实现所需的性能和资源利用比例，尤其是对于较大的 TLB。我们评估了不同的TLB配置，并在Xilinx ZCU102 FPGA上使用SPEC2006套件的基准来展示我们设计的性能、面积和频率结果。



<a name="ETSa6"></a>
### [Developing TEI-aware Ultra Low Power SoC Platforms for IoT Endnodes](http://scholar.google.com/scholar_url?url=https://ieeexplore.ieee.org/abstract/document/9208740/&hl=en&sa=X&d=2855658135084893421&ei=V117X6C9O6nCywSO6p6QAQ&scisig=AAGBfm0mSj1ox2qOeR9rBQrSau4ZAWfTUg&nossl=1&oi=scholaralrt&hist=AQxAsJ0AAAAJ:3812021249043908228:AAGBfm19OZ2uvk2g_ev6ffIC03BRSiTYQw&html=)
K Han, S Lee, KI Oh, Y Bae, H Jang, JJ Lee, W Lee… - IEEE Internet of Things …, 2020<br />… of that, taking into account that the highly complex, time-consuming and<br />labor-intensive development process of these ULP SoCs may hinder their<br />widespread use for IoT endnodes, this paper presents a new EDA tool to …<br />

<a name="kV02l"></a>
### [MEG: A RISCV-based System Emulation Infrastructure for Near-data Processing Using FPGAs and High-bandwidth Memory](http://scholar.google.com/scholar_url?url=https://dl.acm.org/doi/abs/10.1145/3409114&hl=en&sa=X&d=1909495027458171596&ei=V117X6C9O6nCywSO6p6QAQ&scisig=AAGBfm1Tn5xJIoAc0rfeUl2dOM5l8bpPOw&nossl=1&oi=scholaralrt&hist=AQxAsJ0AAAAJ:3812021249043908228:AAGBfm19OZ2uvk2g_ev6ffIC03BRSiTYQw&html=)
J Zhang, Y Zha, N Beckwith, B Liu, J Li - ACM Transactions on Reconfigurable …, 2020<br />… evaluation in a realistic computing environment. In this article, we propose MEG, an<br />open source, configurable, cycle-exact, and **RISC**-**V**-based full-system emulation<br />infrastructure using FPGA and HBM. MEG provides a highly mod …<br />

<a name="XgRAK"></a>
### [VP Float: First Class Treatment for Variable Precision Floating Point Arithmetic](http://scholar.google.com/scholar_url?url=https://dl.acm.org/doi/abs/10.1145/3410463.3414660&hl=en&sa=X&d=9693421360714600166&ei=V117X6C9O6nCywSO6p6QAQ&scisig=AAGBfm2yliHvSX82DB4H5w8MuH3bThPztQ&nossl=1&oi=scholaralrt&hist=AQxAsJ0AAAAJ:3812021249043908228:AAGBfm19OZ2uvk2g_ev6ffIC03BRSiTYQw&html=)
T Jost, Y Durand, C Fabre, A Cohen, F Pétrot - Proceedings of the ACM International …, 2020<br />… To evaluate the portability of our approach, we also demonstrate our LLVM<br />implementation targeting a coprocessor for a **RISC**-**V** Rocket core accelerating<br />FP arithmetic in the UNUM format [1]. Unfortunately we hit hardware bugs ….<br />

<a name="c223b6ee"></a>
### [PyH2: Using PyMTL3 to Create Productive and Open-Source Hardware Testing Methodologies](http://scholar.google.com/scholar_url?url=https://ieeexplore.ieee.org/abstract/document/9195875/&hl=en&sa=X&d=7136320638085969066&ei=V117X6C9O6nCywSO6p6QAQ&scisig=AAGBfm1hWD-HE0DwNpod6k2_imA76fK7Vw&nossl=1&oi=scholaralrt&hist=AQxAsJ0AAAAJ:3812021249043908228:AAGBfm19OZ2uvk2g_ev6ffIC03BRSiTYQw&html=)
S Jiang, Y Ou, P Pan, K Cheng, Y Zhang, C Batten - IEEE Design & Test, 2020<br />… instances to facilitate debugging. Third, performing random testing can be dif- ficult<br />in important hardware domains. There has been a major surge in open-source<br />**RISC**-**V** pro- cessor implementations. However, due to limited …<br />
<br />

<a name="Xn8IB"></a>
### [Recursive Threshold Logic-A Bioinspired Reconfigurable Dynamic Logic System with Crossbar Arrays](http://scholar.google.com/scholar_url?url=https://ieeexplore.ieee.org/abstract/document/9209063/&hl=en&sa=X&d=8419054157064418301&ei=V117X6C9O6nCywSO6p6QAQ&scisig=AAGBfm0qI5MxgDiRNEBOCkvzK7nPtAPy8w&nossl=1&oi=scholaralrt&hist=AQxAsJ0AAAAJ:3812021249043908228:AAGBfm19OZ2uvk2g_ev6ffIC03BRSiTYQw&html=)
AP James, O Krestinskaya, A Maan - IEEE Transactions on Biomedical Circuits and …, 2020<br />Page 1. 1932-4545 (c) 2020 IEEE. Personal use is permitted, but republication/<br />redistribution requires IEEE permission. See [http://www.ieee.org/](http://www.ieee.org/)<br />publications_standards/publications/rights/index.html for more information. This …<br />
<br />

<a name="akssJ"></a>
### [A Vector-Length Agnostic Compiler for the Connex-S Accelerator with Scratchpad Memory](http://scholar.google.com/scholar_url?url=https://dl.acm.org/doi/abs/10.1145/3406536&hl=en&sa=X&d=7017426561678846765&ei=V117X6C9O6nCywSO6p6QAQ&scisig=AAGBfm36HgSjb_4MbRqPaWMK-PkVhvENNg&nossl=1&oi=scholaralrt&hist=AQxAsJ0AAAAJ:3812021249043908228:AAGBfm19OZ2uvk2g_ev6ffIC03BRSiTYQw&html=)
AE Şuşu - ACM Transactions on Embedded Computing Systems …, 2020<br />… like incw, nor stack regions. Note that Connex-S has an instruction similar to index,<br />which we call ldix. Similarly, the **RISC**-**V** ISA [46, 99] has vector-length agnostic<br />extensions [11, 98]. The vector ISA can dynamically change …<br />
<br />

<a name="o0Hyy"></a>
### **[PDF]** [Implementing Low-Diameter On-Chip Networks for Manycore Processors Using a Tiled Physical Design Methodology](http://scholar.google.com/scholar_url?url=https://www.csl.cornell.edu/~cbatten/pdfs/ou-tiled-ocns-nocs2020.pdf&hl=en&sa=X&d=17570995882618572357&ei=7wh-X_DnCIyNy9YPzcub0Ag&scisig=AAGBfm1IhEMMcCgeeYuICvn0-Z3GrXpPMw&nossl=1&oi=scholaralrt&hist=AQxAsJ0AAAAJ:3812021249043908228:AAGBfm19OZ2uvk2g_ev6ffIC03BRSiTYQw&html=)
Y Ou, S Agwa, C Batten<br />… In this section, we explore tradeoffs across different topolo- gies using analytical modeling<br />before presenting more realis- tic layout-level results in Section IV. To choose an appropri-<br />ate core area, we implemented a **RISC**-**V** RV32IMAF in-order Page 3 …<br />

<a name="7HOpX"></a>
### [Efficient and Secure Implementation of Secret-Key and Post-Quantum Public-Key Cryptography with Applications in Internet of Things, Cloud Computing, and …](http://scholar.google.com/scholar_url?url=http://search.proquest.com/openview/741ef444e428fdc85bdf6b28f44ff99d/1%3Fpq-origsite%3Dgscholar%26cbl%3D18750%26diss%3Dy&hl=en&sa=X&d=3567251840506651241&ei=7wh-X_DnCIyNy9YPzcub0Ag&scisig=AAGBfm0efL5jcQ_8f2ntr45m5qJVnySwIg&nossl=1&oi=scholaralrt&hist=AQxAsJ0AAAAJ:3812021249043908228:AAGBfm19OZ2uvk2g_ev6ffIC03BRSiTYQw&html=)
F Farahmand - 2020<br />Page 1. EFFICIENT AND SECURE IMPLEMENTATION OF SECRET-KEY AND<br />POST-QUANTUM PUBLIC-KEY CRYPTOGRAPHY WITH APPLICATIONS IN INTERNET<br />OF THINGS, CLOUD COMPUTING, AND HARDWARE SECURITY by …<br />

<a name="nJZ5g"></a>
### [METHOD FOR EXECUTING A BINARY CODE OF A FUNCTION SECURED BY A MICROPROCESSOR](http://scholar.google.com/scholar_url?url=https://www.freepatentsonline.com/y2020/0302067.html&hl=en&sa=X&d=14422807461235364388&ei=7wh-X_DnCIyNy9YPzcub0Ag&scisig=AAGBfm09wcIWg4SKI2yjzXdRLovJNLQObA&nossl=1&oi=scholaralrt&hist=AQxAsJ0AAAAJ:3812021249043908228:AAGBfm19OZ2uvk2g_ev6ffIC03BRSiTYQw&html=)
O Savry - US Patent App. 16/823,419, 2020<br />… An unconditional branch instruction is for example the instruction “JAL” in the “**RISC** **V**”<br />instruction set … For example, a conditional branch instruction is a “BRANCH” in the<br />“**RISC**-**V**” instruction set. The branch instruction can be a call to a function …<br />
<br />

<a name="6Z4Oi"></a>
### [Return-Oriented Programming on **RISC**-**V**](http://scholar.google.com/scholar_url?url=https://dl.acm.org/doi/abs/10.1145/3320269.3384738&hl=en&sa=X&d=6480481209185609306&ei=ULKAX6rzC6nCywSO6p6QAQ&scisig=AAGBfm2lCK2iMQOhIHhHH-Z19X6tJ_JDEw&nossl=1&oi=scholaralrt&hist=AQxAsJ0AAAAJ:3812021249043908228:AAGBfm19OZ2uvk2g_ev6ffIC03BRSiTYQw&html=)
GA Jaloyan, K Markantonakis, RN Akram, D Robin… - Proceedings of the 15th …, 2020
> 本文首次分析了RISC-V上面向返回式编程（ROP）的可行性，RISC-V是一种针对嵌入式系统的新指令集架构。我们展示了一类新的小工具的存在，使用了几个线性代码序列和跳转（LCSAJ），目前基于Galileo的ROP小工具搜索工具没有发现。我们认为，这一类小工具在RISC-V上足够丰富，可以发动复杂的ROP攻击，绕过传统的缓解措施，如DEP、ASLR、堆栈金丝雀、G-Free和一些基于编译器的后向边缘CFI，通过跳过任何由编译器插入的保护间接跳转指令。我们提供了这种小工具的例子，以及一个概念验证的ROP链，使用C代码注入来利用两个标准Linux操作系统上的特权升级攻击。此外，我们还讨论了防止此类攻击所需的一些缓解措施，并提供了一种新的ROP小工具查找算法，以处理这类新的小工具。



<a name="PfrGJ"></a>
### [ATGP_RISC-V: Automation of Test Generator using Pluggy for **RISC**-**V **Architecture](http://scholar.google.com/scholar_url?url=https://ieeexplore.ieee.org/abstract/document/9214255/&hl=en&sa=X&d=6568639514342683787&ei=ULKAX6rzC6nCywSO6p6QAQ&scisig=AAGBfm00JD-KoIVt89v8TLiq4E3puzt4-A&nossl=1&oi=scholaralrt&hist=AQxAsJ0AAAAJ:3812021249043908228:AAGBfm19OZ2uvk2g_ev6ffIC03BRSiTYQw&html=)
B Madhavan, A Kamerish, R Manimegalai - 2020 Third International Conference on …, 2020
> 缩减指令集计算(RISC)架构是一种自由开放的指令集架构(ISA)，它通过开放的标准合作，实现了处理器创新的新时代。它直接挑战了几个成熟的处理器系列，如intel x-86、Motorola 68k处理器。为了繁荣RISC-V生态系统，核心供应商需要一个独立的验证解决方案，以确保他们的设计符合ISA规范。由于RISC-V设计的可选功能、实施灵活性和客户扩展的规定，RISC-V设计的验证变得具有挑战性。因此，彻底的验证对于成功地与成熟的处理器系列竞争是至关重要的。自动化是减少处理器验证时间的关键。本文提供了一种开发自动化工具ATGP_RISC-V的方法，该工具使用相同的参数来运行所有指令生成器。这有助于以高效的方式验证处理器，减少手动比较测试结果所需的时间。


<br />

<a name="a0ebe538"></a>
### [Hardware enforced fine grained data labeling on **RISC**-**V **using RUST](http://scholar.google.com/scholar_url?url=https://repository.tudelft.nl/islandora/object/uuid:e7a8b0bc-04f8-4ea8-ad9c-d45d30d2bc74&hl=en&sa=X&d=13003866789232991550&ei=ULKAX6rzC6nCywSO6p6QAQ&scisig=AAGBfm1I_6-A-HLPUy11qdNOOURyljsnmw&nossl=1&oi=scholaralrt&hist=AQxAsJ0AAAAJ:3812021249043908228:AAGBfm19OZ2uvk2g_ev6ffIC03BRSiTYQw&html=)
X van Rijnsoever - 2020
> 许多不同变体的软件bug都有可能将敏感数据泄露给攻击者。实现安全域的分离机制可以防止错误或恶意代码将敏感数据从一个安全域泄露到另一个安全域。该工作提出了一种基于在标记内存中用标签标记安全域的分离机制，在字级粒度上，称为颜色标签.利用基于RISC-V架构的标记架构，颜色标签为单个内存字、缓存线、寄存器和外设分配颜色（表示安全域）。使用一套简单的硬件强制策略，确保数据保护。控制流的完整性在表示代码和有效跳转地址的附加标签位的帮助下得以保持。在Rust编译器中实现了软件支持。编译器增强了宏，以支持通过源级注释的着色概念。在编译过程中会报告标签的不正确使用。外部工具用于生成标签信息，并生成包含变量着色、特殊函数使用和构造信息的安全报告。使用外部工具可以使编译器的更改保持在最小的范围内，从而减轻了维护负担，也降低了对编译器的信任度。该报告可用于安全审计.该概念是在指令集架构模拟器上实现的。工具链的修改和概念本身已经在这个模拟器上进行了测试。测试表明，在几种常见的攻击模式下，该概念可以防止跨安全域信息泄露。由于在可执行代码中执行额外指令而产生的开销取决于实际代码。对典型的目标应用OpenVPN-NL的测试显示，最常调用的函数的指令数增加了不到5%.通过设计或重新设计专门用于颜色标签的软件，这种开销有可能进一步降低。进一步的测试，特别是在实际的硬件实现上，是值得推荐的。然而，硬件性能成本估计可以忽略不计。面积要求很高：在RISC-V软核中实现这一概念需要两倍的外部内存容量，FPGA资源利用估计需要增加14%的ALM和74%的内部内存块。



<a name="gIyv6"></a>
### **[PDF]** [Information Leakage Analysis using Accelerated Fault Injection Emulation of a **RISC**-**V **Microprocessor](http://scholar.google.com/scholar_url?url=http://ece-research.unm.edu/jimp/pubs/GOMAC2020_FINAL.pdf&hl=en&sa=X&d=8167299110200665332&ei=ULKAX6rzC6nCywSO6p6QAQ&scisig=AAGBfm36inQxNQmsvnqUINKGxRInsdU7xw&nossl=1&oi=scholaralrt&hist=AQxAsJ0AAAAJ:3812021249043908228:AAGBfm19OZ2uvk2g_ev6ffIC03BRSiTYQw&html=)
TJ Mannos, J Plusquelic, B Dziki, FGG Meade<br />This paper investigates information security issues that result from the occurrence of<br />faults within a **RISC**-**V **microprocessor. Faults are emulated using a specialized fault<br />injection circuit which is inserted in series along paths within the synthesized netlist …<br />
<br />

<a name="YBxjx"></a>
### **PDF]** [NCPU: An Embedded Neural CPU Architecture on Resource-Constrained Low Power Devices for Real-time End-to-End Performance](http://scholar.google.com/scholar_url?url=http://nu-vlsi.eecs.northwestern.edu/Neural_CPU_MICRO2020.pdf&hl=en&sa=X&d=14411464447445462589&ei=ULKAX6rzC6nCywSO6p6QAQ&scisig=AAGBfm1PPa1OJmd4GLd0eEojzqhlffiySw&nossl=1&oi=scholaralrt&hist=AQxAsJ0AAAAJ:3812021249043908228:AAGBfm19OZ2uvk2g_ev6ffIC03BRSiTYQw&html=)
T Jia, Y Ju, R Joseph, J Gu<br />… The proposed architecture is built on a binary neural network accelerator<br />with the capability of emulating an in-order **RISC**-**V** CPU pipeline. The<br />NCPU supports flexible programmability of **RISC**-**V** and maintains data …<br />

<a name="xWDOF"></a>
### **[PDF]** [A Hardware in the Loop Benchmark Suite to Evaluate NIST LWC Ciphers on Microcontrollers](http://scholar.google.com/scholar_url?url=https://www.researchgate.net/profile/Sebastian_Renner4/publication/344450004_A_Hardware_in_the_Loop_Benchmark_Suite_to_Evaluate_NIST_LWC_Ciphers_on_Microcontrollers/links/5f76e0dd92851c14bca7b33f/A-Hardware-in-the-Loop-Benchmark-Suite-to-Evaluate-NIST-LWC-Ciphers-on-Microcontrollers.pdf&hl=en&sa=X&d=15945709724010735643&ei=ULKAX6rzC6nCywSO6p6QAQ&scisig=AAGBfm2vcN6yUnjzDOgDsV5oUvAFJd3IIQ&nossl=1&oi=scholaralrt&hist=AQxAsJ0AAAAJ:3812021249043908228:AAGBfm19OZ2uvk2g_ev6ffIC03BRSiTYQw&html=)
S Renner, E Pozzobon, J Mottok<br />… The focus of this paper should rather lay on the framework design and testing methodology<br />than on the current results, especially for reference code. Keywords: Lightweight<br />Cryptography · Benchmarking · Embedded Sys- tems · **RISC**-**V** 1 Introduction …<br />
<br />

<a name="WgFRh"></a>
### [Detailed review on embedded MMU and their performance analysis on test benches](http://scholar.google.com/scholar_url?url=https://ieeexplore.ieee.org/abstract/document/9212265/&hl=en&sa=X&d=15091078577605444781&ei=ULKAX6rzC6nCywSO6p6QAQ&scisig=AAGBfm0x6akp0fqo-w9h5IsxpvjQBCYbVQ&nossl=1&oi=scholaralrt&hist=AQxAsJ0AAAAJ:3812021249043908228:AAGBfm19OZ2uvk2g_ev6ffIC03BRSiTYQw&html=)
D Behera, UR Jena - … Conference on Computational Intelligence for Smart …, 2020<br />… support multi-process. Nowadays, with the complexities of the proposed<br />MMU-implanted NoC (MMNoC) program, a model stage is being provided including<br />the MMNoC and the double **RISC**-**V** processors. The model stage …<br />
<br />

<a name="M5tfH"></a>
### [CoDaRR: Continuous Data Space Randomization against Data-Only Attacks](http://scholar.google.com/scholar_url?url=https://dl.acm.org/doi/abs/10.1145/3320269.3384757&hl=en&sa=X&d=3703343383485838554&ei=ULKAX6rzC6nCywSO6p6QAQ&scisig=AAGBfm1_kotOIJ-9aCm5xTtwuGwTx-oGYA&nossl=1&oi=scholaralrt&hist=AQxAsJ0AAAAJ:3812021249043908228:AAGBfm19OZ2uvk2g_ev6ffIC03BRSiTYQw&html=)
P Rajasekaran, S Crane, D Gens, Y Na, S Volckaert… - Proceedings of the 15th …, 2020<br />Page 1. CoDaRR : Continuous Data Space Randomization against<br />Data-Only Attacks Prabhu Rajasekaran [rajasekp@uci.edu](mailto:rajasekp@uci.edu) University of<br />California, Irvine Stephen Crane [sjc@immunant.com](mailto:sjc@immunant.com) Immunant, Inc. David …<br />
<br />
<br />


---

<a name="SM5cC"></a>
# 产业风云


<a name="qG6pb"></a>
### MAX78000：ARM主核+RISC-V协处理器的IoT AI推理设备


<a name="dEEfF"></a>
### Nokia的5G芯片或会使用RISC-V架构
<a name="MXwXc"></a>
### 世界各地本科生RISC-V涌起

- "[东京大学版「一生一芯」：自制CPU、C编译器，还成功运行了类Unix系统 ](https://finance.sina.com.cn/tech/2020-10-08/doc-iivhuipp8489972.shtml
)(From finance.sina.com.cn 2020.10.08)"
- "[一个印度本科生的RISC-V项目，感觉不输我们！ ](https://www.sohu.com/a/423219199_458015
)(From www.sohu.com 2020.10.10)"



<a name="2xvIA"></a>
### RV国际CTO的访谈节目


<a name="QiDUd"></a>
### 晶心股票大涨，预计2025年全球有624亿RISC-V核心
"[《半導體》RISC-V爆發力可期 晶心科剽悍 ](https://www.chinatimes.com/realtimenews/20201005001468-260410?chdtv
)(From www.chinatimes.com 2020.10.07)"

<a name="i2KYO"></a>
### 瑞萨布局RISC-V后续


<a name="obiXx"></a>
### 印度全国产CPU后续：认为Domain Specification是趋势

- "[There's a new microprocessor in town. And this one Made in India — at IIT Madras ](https://www.edexlive.com/happening/2020/oct/04/theres-a-new-microprocessor-in-town-and-this-one-made-inindiaat-iit-madras-14913.html
)(From www.edexlive.com 2020.10.04)"
- 国内网友评论："[转：100% 印度造RISC-V SoC成功流片！180纳米，工艺落后但完全自主 ](https://www.txrjy.com/thread-1148696-1-1.html
)(From www.txrjy.com 2020.10.06)"

<br />
<a name="VqK8x"></a>
### N+A追踪专题

- "[ARM pledges to erect 'firewalls' against Nvidia meddling ](https://www.zdnet.com/article/arm-pledges-to-erect-firewalls-against-nvidia-meddling/
)(From www.zdnet.com 2020.10.07)"
- "[英特尔，高通，特斯拉反对ARM与Nvidia合并 ](https://www.fudzilla.com/news/pc-hardware/51663-intel-qualcomm-tesla-against-arm-nvidia-merger
)(From www.fudzilla.com 2020.10.08)"
- "[Arm高管：被英伟达收购后将继续保留“防火墙”以保护客户信息 ](https://finance.sina.com.cn/tech/2020-10-08/doc-iivhuipp8467786.shtml
)(From finance.sina.com.cn 2020.10.08)"
- "[Arm's Inaugural DevSummit Starts With Big Developer Announcements And Updates ](https://www.forbes.com/sites/patrickmoorhead/2020/10/08/arms-inaugural-devsummit-starts-with-big-developer-announcements-and-updates/#6c7de9a5153c
)(From www.forbes.com 2020.10.09)"
- ![](https://cdn.nlark.com/yuque/0/2020/jpeg/1541992/1602317903842-2387ed35-e142-46a7-89ee-ca5224fd19fa.jpeg#align=left&display=inline&height=24&margin=%5Bobject%20Object%5D&originHeight=199&originWidth=199&size=0&status=done&style=none&width=24)"[Arm再下保证书，防火墙是否能打消客户顾虑？ ](https://www.sohu.com/a/423372204_486088
)(From www.sohu.com 2020.10.10)"



<a name="lyytw"></a>
### EDA专题

- "[SmartDV推出SmartConf Testbench Generator ](https://www.design-reuse.com/news/48773/smartdv-smartconf-testbench-generator.html
)(From www.design-reuse.com 2020.10.06)"

<br />
<a name="EDWdP"></a>
### AMD YES

- "[如何看待媒体称AMD正就收购半导体制造商Xilinx展开深入谈判，会对行业产生什么影响？ ](https://www.zhihu.com/question/424777837
)(From www.zhihu.com 2020.10.10)"

<br />
<a name="0fFYu"></a>
### RISC-V产业评论

- "[开放性与碎片化，RISC-V能否撼动处理器架构的格局？ ](https://www.sohu.com/a/423162017_467791
)(From www.sohu.com 2020.10.10)"
- ![](https://cdn.nlark.com/yuque/0/2020/png/1541992/1602317880980-8e6888f3-12e2-43a0-a429-ae70c6f254c1.png#align=left&display=inline&height=24&margin=%5Bobject%20Object%5D&originHeight=456&originWidth=456&size=0&status=done&style=none&width=24)"[点评 | 芯片公司的崛起与爆发需要多年的锤炼；RISC-V短期内推广难度不小  ](https://www.sohu.com/a/423421188_166680
)(From www.sohu.com 2020.10.10)"

---

<a name="tAplU"></a>
# 其他动态


<a name="1Jjlp"></a>
### 开发板推荐
"[Banana Pi BPI-EAI80 Cortex-M4F板嵌入AI加速器，WiFi模块 ](https://www.cnx-software.com/2020/10/09/16-banana-pi-bpi-eai80-cortex-m4f-board-embeds-ai-accelerator-wifi-module/
)(From www.cnx-software.com 2020.10.10)"

<a name="KCgFm"></a>
### 博文推荐：RISC-V入门系列

- "[OS 和 trap: RISC-V 视角 ](https://zhuanlan.zhihu.com/p/150571417
)(From zhuanlan.zhihu.com 2020.06.24)"
- "[RISC-V And C Toolchains: Get Start ](https://zhuanlan.zhihu.com/p/118749234
)(From zhuanlan.zhihu.com 2020.10.01)"
- "[RISC-V 入门 Part2: ABI && Calling Convention ](https://zhuanlan.zhihu.com/p/261294574
)(From zhuanlan.zhihu.com 2020.10.03)"
- "[RISC-V 入门 Part3: 指令格式 ](https://zhuanlan.zhihu.com/p/261705919
)(From zhuanlan.zhihu.com 2020.10.04)"
- "[RISC-V 入门 Part4: 编译、链接、加载 ](https://zhuanlan.zhihu.com/p/261823959
)(From zhuanlan.zhihu.com 2020.10.05)"

<br />
<a name="Nxr0W"></a>
### 博文推荐

- "[RISC-V SV39 内存管理 ](https://zhuanlan.zhihu.com/p/263372436
)(From zhuanlan.zhihu.com 2020.10.09)"
- "[制作一个针对 RISC-V 的 LLVM/Clang 编译器 ](https://zhuanlan.zhihu.com/p/263550372
)(From zhuanlan.zhihu.com 2020.10.10)"
- "[关于C#：RISC-V组装-堆栈布局-函数调用 ](https://www.codenong.com/34182330/
)(From www.codenong.com 2020.10.10)"
- "[Memory Access In AI Systems ](https://semiengineering.com/memory-access-in-ai-systems/
)(From semiengineering.com 2020.10.10)"
- "[【JDK源码阅读】后端编译与优化 ](https://zhuanlan.zhihu.com/p/264129498
)(From zhuanlan.zhihu.com 2020.10.10)"




---


<br />RISC-V与芯片评论编辑部 - RISC-V和芯片动态周报<br />每周六发布<br />欢迎批评，指正，评论和加入<br />
<br />关于本刊: 

- [消息来源](https://www.yuque.com/riscv/rvnews/overview#vHVQ5)




| 微信公众号<br />![image.png](https://cdn.nlark.com/yuque/0/2020/png/1541992/1602320139392-1297e86a-ac06-4d76-a000-ad4307cd488c.png#align=left&display=inline&height=187&margin=%5Bobject%20Object%5D&name=image.png&originHeight=440&originWidth=465&size=225442&status=done&style=none&width=198) | Gitee

[https://gitee.com/inspur-risc-v/RVWeekly](https://gitee.com/inspur-risc-v/RVWeekly) | Github

[https://github.com/inspur-risc-v/RVWeekly](https://github.com/inspur-risc-v/RVWeekly) | 语雀

[https://www.yuque.com/riscv/rvnews](https://www.yuque.com/riscv/rvnews) |
| --- | --- | --- | --- |


<br />

