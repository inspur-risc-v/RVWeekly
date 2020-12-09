# RV与芯片评论.20201205.第19期


<br />本期概要

- RISC-V Summit 2020将在下周召开，有哪些看点
- 本周各公司动作频繁，Andes，AntMicro，Imperas，Esperanto，SiFive，发布了多款内核和IP
- 本周有许多值得一看的论文，主要集中在芯片安全和加密加速
- 2020最后一个月，本年度年度总结




---

<a name="cgX2z"></a>
# 一，重点聚焦


<a name="8zNLV"></a>
### RISC-V Summit 2020将在下周召开

- 
<a name="tlITa"></a>
### 第一次东亚时区RISC-V生态双周同步会将在下周四召开
<a name="fLvGn"></a>
### 相关周报

- ![image.png](https://cdn.nlark.com/yuque/0/2020/png/1541992/1599307696075-3f44fb1b-f362-4130-a254-b3e4fb6cebac.png#align=left&display=inline&height=24&margin=%5Bobject%20Object%5D&name=image.png&originHeight=84&originWidth=89&size=7408&status=done&style=none&width=25)[semi engineering](https://semiengineering.com/) Week In Review: ：
   - Blog Review："[Dec. 2 ](https://semiengineering.com/blog-review-dec-2-2/
)(_FPGA verification effectiveness; automotive sensors; formal verification._)"
   - Design, Low Power：[Xilinx buys HLS compiler; Nordic Semi gets Imagination’s Wi-Fi biz; new RISC-V cores; Synopsys Q4 revenue up 20%. ](https://semiengineering.com/week-in-review-design-low-power-123/
)
   - Manufacturing, Test：[ASE expand EMS biz; IC packaging demand; 5nm + 2.5D; R2R. ](https://semiengineering.com/week-in-review-manufacturing-test-125/
)
   - Auto, Security, Pervasive Computing：[SMIC on DOD blacklist; Intel Labs Day; Ericsson on 5G — 60% world access in 2026.](https://semiengineering.com/week-in-review-auto-security-pervasive-computing-44/
)
- [IoT News](https://staceyoniot.com/): [Dec. 4, 2020](https://staceyoniot.com/iot-news-of-the-week-for-dec-4-2020/
)
- [OSDT Weekly](https://github.com/hellogcc/osdt-weekly/tree/master/weekly)："[2020-12-02 第074期 ](https://github.com/hellogcc/osdt-weekly/blob/master/weekly/2020-12-02.md
)(From github.com 2020.12.05)"
- [泰晓咨询](http://tinylab.org/)：[12月 / 第一期 / 2020 ](http://tinylab.org/tinylab-weekly-12-1st-2020/
)
- [PLCT开源进展](https://www.zhihu.com/column/plct-lab)：[第14期·2020年12月01日](https://zhuanlan.zhihu.com/p/325728273
)
- [RT-Thread](https://my.oschina.net/u/4428324)：[【20201127期嵌入式AI周报】NanoDet 目标检测模型、移植 ncnn到 RISC-V等！](https://my.oschina.net/u/4428324/blog/4761572
)
- ：[第 136 期：利特伍德奇迹定律 ](https://www.yuque.com/ruanyf/weekly/issue-136
)
- [Top 10 Data Center Stories of the Month: November 2020](https://www.datacenterknowledge.com/uncategorized/top-10-data-center-stories-month-november-2020
)
   - Equinix 解释了为什么不与云计算提供商竞争；AWS 计划在弗吉尼亚州进行另一次扩张；FedEx 关注边缘计算等。
<a name="IqIkK"></a>
### 2020年度总结专题

- 
- RISC-V中文社区，RISC-V半年报：[上](https://www.risc-v1.com/thread-1270-1-1.html)，[下](https://www.risc-v1.com/thread-1271-1-1.html)
- [Top tech 2020: The two Jasons pick their favorite gear of the year](https://www.zdnet.com/article/jason-squareds-top-5-tech-of-2020/
)

---



<a name="nqDGS"></a>
# 二，技术动态

- 
- 
   - 利用Deeplite独特的优化软件和Andes的低功耗Andes RISC-V CPU内核，为人工智能驱动的应用提供支持。此次合作的重点是压缩和加速著名的Visual Wake Words(VWW)应用，其中一个微小的嵌入式摄像头可以检测图像中的人。Deeplite和Andes一起取得了业界领先的成果，从基于浮点的Mobilenet-v1-0.25x模型中产生了各种优化的INT8模型。
- 
- 
- 
- 
<a name="UQCtX"></a>
### Linux动态

- "[[GIT PULL] RISC-V Fixes for 5.10-rc6 ](https://www.mail-archive.com/linux-kernel@vger.kernel.org/msg2397130.html
)(From www.mail-archive.com 2020.11.28)"
- "[[PATCH v2 1/2] RISC-V: Update l2 cache DT documentation to add support for SiFive FU740 ](https://www.mail-archive.com/linux-kernel@vger.kernel.org/msg2397551.html
)(From www.mail-archive.com 2020.11.29)"
- "[RE: [PATCH v15 10/17] RISC-V: KVM: Implement stage2 page table programming ](https://www.mail-archive.com/linux-kernel@vger.kernel.org/msg2399047.html
)(From www.mail-archive.com 2020.11.30)"
- "[RE: [PATCH v15 10/17] RISC-V: KVM: Implement stage2 page table programming ](https://www.mail-archive.com/linux-kernel@vger.kernel.org/msg2399047.html
)(From www.mail-archive.com 2020.11.30)"
- "[[PATCH 5.9 124/152] RISC-V: Add missing jump label initialization ](https://www.spinics.net/lists/stable/msg430219.html
)(From www.spinics.net 2020.12.01)"
- "[Re: [PATCH v2] RISC-V: enable XIP ](https://www.spinics.net/lists/kernel/msg3759464.html
)(From www.spinics.net 2020.12.03)"
<a name="SYbmw"></a>
### QEMU动态

- "[[PATCH] target/riscv: Fix the bug of HLVX/HLV/HSV ](https://www.mail-archive.com/qemu-devel@nongnu.org/msg763018.html
)(From www.mail-archive.com 2020.11.29)"
- "[[PATCH 1/1] target-riscv: support QMP dump-guest-memory ](https://www.mail-archive.com/qemu-devel@nongnu.org/msg763287.html
)(From www.mail-archive.com 2020.11.30)"
- "[[PATCH 1/1] target-riscv: support QMP dump-guest-memory ](https://www.mail-archive.com/qemu-devel@nongnu.org/msg763287.html
)(From www.mail-archive.com 2020.11.30)"
<a name="xV2Cs"></a>
### KVM动态

- "[[PATCH RFC 2/3] RISC-V: KVM: Support dynamic time frequency from userspace ](https://www.spinics.net/lists/kvm/msg229935.html
)(From www.spinics.net 2020.12.03)"
- "[[PATCH RFC 1/3] RISC-V: KVM: Change the method of calculating cycles to nanoseconds ](https://www.spinics.net/lists/kvm/msg229934.html
)(From www.spinics.net 2020.12.03)"
<a name="v2ah0"></a>
### 一周问答

- "[Whisper simulator for RISC-V: C++ Program either gets caught in infinite loop or get aborted  ](https://stackoverflow.com/questions/65085354/whisper-simulator-for-risc-v-c-program-either-gets-caught-in-infinite-loop-or
)(From stackoverflow.com 2020.12.05)"
- "[What are the step-by-step instructions to get Spike RISC-V simulator setup for Freedom Studio? ](https://forums.sifive.com/t/what-are-the-step-by-step-instructions-to-get-spike-risc-v-simulator-setup-for-freedom-studio/4273
)(From forums.sifive.com 2020.12.07)"
<a name="CC8oT"></a>
### 社区动态

- "[从技术的角度来看，RISC-V 能对芯片发展、科技自主起到哪些作用？ ](https://www.zhihu.com/question/425542531
)(From www.zhihu.com 2020.12.05)"
- 包云岗回应知乎问题：从技术的角度来看，RISC-V 能对芯片发展、科技自主起到哪些作用？
   - [从技术的角度来看，RISC-V 能对芯片发展、科技自主起到哪些作用？ - 知乎](https://www.zhihu.com/question/425542531/answer/1607862976)
- "[Decode for sm4 and aes32 instructions, rs1==rd #65 ](https://github.com/riscv/riscv-crypto/issues/65
)(From github.com 2020.12.07)"

---

<a name="SM5cC"></a>
# 三，产业风云

- 
- 
- "[深度解密IMG B系列GPU：多核架构、图像压缩技术、RISC-V技术等 ](https://www.eda365.com/thread-469628-1-1.html
)(From www.eda365.com 2020.11.27)"
   - Imagination对外正式宣布推出全新的IMG B系列（IMG B-Series）图形处理器（GPU），这是其第一个包含新多核架构的GPU IP系列，也是首次采用RISC-V，可提供最高的性能密度（peRFormance per mm?），峰值算力可达6TFLOPS(每秒万亿次浮点运算)的计算能力，AI算力可达24TOPS，同时提供了多种全新配置，可以针对给定的性能目标实现更低的功耗和高达35％的带宽降低。
- 
   - AndesCore™ 45系列IP是顺序8级双发RISC-V处理器，并配备了可选的DSP（RISC-V P-扩展）单元、单精度或双精度浮点运算单元和MMU（内存管理单元），同时支持基于Linux的应用。其高性能的单核成员，包括32位的A45/D45/N45和64位的AX45/NX45
- 
- 
   - 使用EEMBC基准，我们每瓦的CoreMarks达到了55000个。M1芯片用EEMBC的说法大概相当于10000个CoreMarks，除以8个核心和15W的总功率，那就是每瓦不到100个CoreMarks。" 继续与Arm做比较，他补充道："EEMBC基准下最快的Arm处理器是Cortex-A9(四核)，数据为22343 CoreMarks。除以四核，每核5W，则每瓦的CoreMarks为1112个
- 
- 
- 
- 
<a name="PO7vP"></a>
### 评论文集

- "[RISC-V：准备好与Arm竞争了吗？ ](http://news.moore.ren/industry/258871.htm
)(From news.moore.ren 2020.11.29)"
- "[RISC-V蓬勃发展，机遇与挑战并存 ](http://m.chinaaet.com/article/3000125584
)(From m.chinaaet.com 2020.12.05)"
- "[RISC-V架构火爆，中国厂商疯狂涌入，它真是中国芯的机会？  ](https://www.sohu.com/a/435257420_436214
)(From www.sohu.com 2020.11.30)"
- 
- 
- 
- "[如何评价乐鑫推出的RISC-V 内核 ESP32-C3芯片，是否是Wi-Fi MCU领域新的里程碑？ ](https://www.zhihu.com/question/432178022
)(From www.zhihu.com 2020.12.07)"
   - [2020.11.20 乐鑫ESP32-C3发布 · 语雀](https://www.yuque.com/riscv/rvnews/olvw6q)

---



<a name="tAplU"></a>
# 四，其他动态


<a name="tO9Sj"></a>
### 项目推荐

- 
   - KCP53000是个64位RISC-V核心
<a name="xNWor"></a>
### 视频推荐

- "[MIT 6.004 L14: Implementing RISC-V Processor in Hardware ](https://www.youtube.com/watch?v=c23MThWhXMw
)(From www.youtube.com 2019.10.24)"
> MIT 6.004 Computation Structures course
> Lecture 14: Implementing RISC-V Processor in Hardware

- "[RISC-V Project: Driving GPIO Pins ](https://www.youtube.com/watch?v=pe6KbwCQuSM&feature=emb_title
)(From www.youtube.com 2020.12.05)"
> 在没有操作系统的情况下控制150 MHz RISC-V开发板的引脚是开发硬件的重要一步。 在这段视频中，我们将探讨一种使用SiFive FE310-G002开发套件和SiFive的Freedom Metal库来实现这一目标的方法。 这里有相当多的代码，所以请看例子前的链接，你可以复制。

- "[ Linux on RISC-V with Open Hardware - Drew Fustini, BeagleBoard.org Foundation ](https://www.youtube.com/watch?v=PNcX3MCAIjo&feature=emb_title
)(From www.youtube.com 2020.11.29)"
- "[Ask the Expert Session with Calista Redmond, CEO of RISC V International ](https://www.youtube.com/watch?v=Aqiobrlou9s&feature=emb_title
)(From www.youtube.com 2020.11.29)"
- "[【5G小课堂】- 5G为什么需要eCPRI接口? ](https://www.bilibili.com/s/video/BV1eD4y1X7JV
)(From www.bilibili.com 2020.12.05)"

<br />
<a name="aF1Xk"></a>
### 资源推荐：RISC-V精选文献收集
[https://ascslab.org/conferences/secriscv/materials/papers/paper_1.pdf](https://ascslab.org/conferences/secriscv/materials/papers/paper_1.pdf) - ?.pdf
<a name="qOiMZ"></a>
### 博文推荐

- "[RISC-V常见指令 ](https://blog.csdn.net/qq_43245691/article/details/110260112
)(From blog.csdn.net 2020.11.28)"
- "[基于高云系列FPGA的RISC-V软核 ](https://mbb.eet-china.com/forum/topic/84303_1_1.html
)(From mbb.eet-china.com 2020.12.05)"
- 
- "[[RISC-V MCU 应用开发] 【RISC-V MCU CH32V103测评】+SPIFLASH和RTC测试 ](https://bbs.21ic.com/icview-3051566-1-1.html
)(From bbs.21ic.com 2020.12.05)"
- "[RISCV ISS Spike 介绍 ](https://blog.csdn.net/cs824980820/article/details/110389068
)(From blog.csdn.net 2020.12.05)"
- "[[RISC-V MCU 应用开发] 【RISC-V MCU CH32V103测评】+SPI读写FLASH测试 ](https://bbs.21ic.com/icview-3051506-1-1.html
)(From bbs.21ic.com 2020.12.05)"
- "[[RISC-V MCU 应用开发] 【RISC-V MCU CH32V103测评】10：FATFS移植Demo ](https://bbs.21ic.com/icview-3051984-1-1.html
)(From bbs.21ic.com 2020.12.05)"
- "[[RISC-V MCU 应用开发] [RISC-V MCU CH32V103测评]+开箱搭建开发环境之跑马灯跑起来 ](https://bbs.21ic.com/icview-3049494-1-1.html
)(From bbs.21ic.com 2020.12.05)"
- "[开源RISCV简单虚拟原型/模拟器：RISC-V-TLM ](https://blog.csdn.net/qq_35990574/article/details/110492282
)(From blog.csdn.net 2020.12.05)"
- "[IceStick Tutorial ](https://github.com/BrunoLevy/learn-fpga/blob/master/FemtoRV/TUTORIALS/IceStick.md
)(From github.com 2020.12.07)"
- "[[RISC-V MCU 应用开发] 【RISC-V MCU CH32V103测评】+ 安装开发环境建立第一个工程 ](https://bbs.21ic.com/icview-3053544-1-1.html
)(From bbs.21ic.com 2020.12.08)"

---

<a name="5NYql"></a>
# 五，一周论文
<br />
<a name="IUIRI"></a>
## 处理器设计


<a name="sdYoM"></a>
### [An Academic **RISC**-**V **Silicon Implementation Based on Open-Source Components](https://ieeexplore.ieee.org/abstract/document/9268664/)
J Abella, C Bulla, G Cabo, FJ Cazorla, A Cristal… - 2020 XXXV Conference on …, 2020
> 本文介绍的设计称为preDRAC，是由BSC、CIC-IPN、IMB-CNM（中船重工）和UPC联合开发的能够启动Linux的RISC-V通用处理器。preDRAC处理器是第一个由西班牙或墨西哥学术机构设计和制造的RISC-V处理器，将是未来这些机构联合开发的RISC-V设计的基础。本文总结了设计任务，先是针对FPGA，后是针对SoC，从高架构层面的描述到RTL，再经过逻辑综合和物理设计，为其在CMOS 65nm技术下的最终带出做好布局准备。

<a name="V0GnC"></a>
### [**RISC**-**V **processors design: a methodology for cores development](https://ieeexplore.ieee.org/abstract/document/9268639/)
A Barriga - 2020 XXXV Conference on Design of Circuits and …, 2020
> 本篇通讯介绍了一种便于实现基于RISC-V的ISA的处理器的设计方法。作为所提出的方法的应用实例，描述了具有不同结构和特点的三个处理器的设计。

<a name="QMSIQ"></a>
## 芯片安全
<a name="E9D4s"></a>
### [RIMI: Instruction-level Memory Isolation for Embedded Systems on RISC-V](https://ieeexplore.ieee.org/abstract/document/9256494/)
H Kim, J Lee, D Pratama, AM Awaludin, H Kim, D Kwon - 2020 IEEE/ACM …, 2020<br />设计了一个扩展指令集，专门用于内存隔离
> 随着物联网的出现，嵌入式系统已经被广泛应用于各个领域。与此同时，这些系统的安全性也成为许多人关注的问题。然而，高端系统已经具备的安全功能，由于其对成本和功耗的负面影响，在低端嵌入式系统中并没有提供。因此，为了在低开销的情况下提高安全性，已经进行了许多研究来实现这些系统的内存隔离方法。然而，现有的这种方法的技术在扩展性或性能方面存在问题。为了缓解这些问题，我们提出了RIMI，一种新的指令扩展，以在嵌入式系统中提供内存隔离。由于RIMI中的指令，我们可以实现指令级的内存隔离，其中访问权限被绑定到每个内存和控制传输指令。我们在RISC-V架构上实现了RIMI原型，它是一个著名的开源指令集架构（ISA）。我们的评估结果表明，现有的安全解决方案，即影子堆栈和进程内隔离，可以通过RIMI有效地实现。

<a name="Cza3O"></a>
### **[PDF]** [Dynamic Frequency Scaling as a countermeasure against simple power analysis attack in **RISC**-**V **processors](https://ascslab.org/conferences/secriscv/materials/presentations/presentation_paper_04.pdf)
BA Dao, AT Le, TT Hoang, A Tsukamoto, K Suzaki…
> 动态频率缩放(DFS)是一种在硬件模块工作时动态改变其时钟频率的相关技术。本文演示了将DFS技术集成到一个开源的RISC-V处理器中，并将其作为一种简单、经济的对抗简单功率分析攻击的措施。将该集成处理器在Sakura-X FPGA板[1]中实现实验。实验结果表明，DFS模块可以掩盖测量功率痕迹中的敏感信息，而处理器的硬件资源要求几乎没有变化。索引号-DFS，RISC-V处理器，SPA，SCA 一、引言 嵌入式系统正变得越来越流行，尤其是对安全性有要求的应用。在这些系统中，由于软件成熟、实用，通用处理器被广泛使用。然而，通用处理器极易受到侧信道攻击，即利用从热量、声音、时间、电磁辐射或功耗中泄露的信息来检索加密操作中使用的秘密密钥[2]。最有效的侧信道攻击是功率分析攻击。它们包括简单功率分析(SPA)攻击、微分功率分析(DPA)攻击[3]和相关功率分析(CPA)攻击[4]。实际上，SPA涉及到对处理器执行加密功能时的功率痕迹进行视觉观察。它允许攻击者收集有关加密算法的类型和时间的基本信息[5]。根据这些信息，攻击者可以决定部署更复杂和强大的攻击，如DPA或CPA，以破坏整个系统的安全。

<a name="wv4gz"></a>
### **[PDF]** [Examination of applicability of **RISC**-**V **security specifications to low-end processors](https://ascslab.org/conferences/secriscv/materials/papers/paper_06.pdf)
F Arakawa, A Tsukamoto, K Suzaki, M Ikeda<br />专门分析了PMP安全单元，认为内存保护的面积太大，需要做些什么
> 我们评估了RISC-V上安全扩展的面积开销，RISC-V是通用处理器的开放指令集架构。近来，安全支持的重要性越来越高，特别是在物联网时代，大规模系统的安全性会因为系统终端设备中的低端处理器的脆弱性而受到影响。然而，即使牺牲性能，也要减少低端处理器的面积和功率。评估结果显示，物理内存保护(PMP)功能的面积与内存管理单元其他部分的面积相当，这极大地影响了低端处理器的面积。此外，当启用虚拟内存时，PMP面积会增加。在PMP=16的情况下，Mid RV32 Rocket瓦片的PMP面积开销达到了33.3%之多。

<a name="oChsV"></a>
### **[PDF]** [Verifying **RISC**-**V **Physical Memory Protection](https://ascslab.org/conferences/secriscv/materials/papers/paper_19.pdf)
K Cheang, C Rasmussen, D Lee, DW Kohlbrenner…<br />表示不需要额外寄存器，修改一下PMP就能运行TEE
> 我们正式验证了RISCV中物理内存保护(PMP)的开源硬件实现，PMP是安全关键系统中用于内存隔离的标准功能，如Keystone可信执行环境。PMP提供了每个硬件线程机器模式控制寄存器，指定了物理内存区域的访问权限。我们首先基于RISC-V ISA手册形式化了PMP规则的功能属性。然后，我们使用LIME工具来翻译一个开源实现的PMP硬件模块写在Chisel到Uclid5形式化验证语言。我们在Uclid5中对形式规范进行编码，并验证硬件的功能正确性。这是验证Keystone框架的初步努力，其中可信计算基础(TCB)依靠PMP提供完整性和确证性等安全保证。

<a name="LkcwI"></a>
### **[PDF]** [Protecting Processors from Software Exploitation Cyberattacks: **RISC**-**V **Sets the Stage for a Streamlined CoreGuard® Integration](https://ascslab.org/conferences/secriscv/materials/papers/paper_21.pdf)
S Milburn
> Dover Microsystems 的 CoreGuard® 是唯一适用于嵌入式系统的解决方案，可防止软件漏洞被利用，并使处理器免受基于网络的整类攻击。它通过将安全性直接硬接线到硅片中，提供物理保护层，防止攻击者接管处理器的能力。CoreGuard技术以IP块的形式提供，为处理器和SoC设计者提供了使用、修改或扩展RISC-V处理器的多种选择。正确 "的选择基于许多因素，如PPA（功率、性能和面积）限制以及设计者对处理器实现的灵活性。本文介绍了将CoreGuard IP与RISC-V主机处理器集成的选择。虽然CoreGuard技术是架构不可知的，但RISC-V架构的开放性和特权模型为最适应和最简化的集成方法提供了完美的舞台。

<a name="PSW93"></a>
### **[PDF]** [Enclave Computing on **RISC**-**V**: A Brighter Future for Security?](https://ascslab.org/conferences/secriscv/materials/papers/paper_16.pdf)
G Dessouky, AR Sadeghi, E Stapf
> 商品操作系统庞大的攻击面促使学术界和工业界开发新型安全架构，在所谓的飞地中为敏感应用提供强有力的保护，这些飞地只需要信任硬件和最小的软件组件。然而，工业界提出的飞地架构往往缺乏重要的功能，如安全的I/O，并且假设的威胁模型遗漏了重要的攻击类别，如微架构攻击。因此，学术界最近的工作提出了一系列新的飞地架构，这些飞地架构具有鲜明的特征和更全面的威胁模型，其中许多是在开放的RISC-V架构上开发的。本文简要介绍了学术界提出的基于RISC-V架构的飞地架构，讨论了它们的特点、局限性以及我们目前研究中所应对的开放性挑战。

<a name="n14oq"></a>
### **[PDF]** [Real-time Thread Isolation and Trusted Execution on Embedded **RISC**-**V**](https://ascslab.org/conferences/secriscv/materials/papers/paper_15.pdf)
S Lindemer, G Midéus, S Raza
> 物联网模式导致对具有硬件强化可信执行环境(TEE)的低功耗单核嵌入式设备的需求越来越大。这一领域的卓越解决方案是Arm TrustZone，它提供了四种CPU执行状态，每种状态都有自己的内存和指令权限。2019年，物理内存保护（PMP）指令在RISC-V ISA中被ratiﬁed，它提供了类似于Arm MPU的增强功能，但无法创建类似TrustZone的TEE框架。在本文中，我们讨论了PMP规范中的一个限制，它排除了在RISC-V上设计这样一个TEE框架，而不需要借助非标准的硬件修改。我们提出了一个简单的修改PMP规范，这将解决这个限制，而无需增加额外的寄存器。我们讨论了我们正在进行的早期工作，实现这种硬件扩展的原型，并将其与Zephyr实时操作系统（RTOS）集成。

<a name="dyLlt"></a>
### **[PDF]** [Subversion-Resilient Enhanced Privacy ID](https://eprint.iacr.org/2020/1450.pdf)
A Faonio, D Fiore, L Nizzardo, C Soriente
> 安全硬件平台的匿名认证利用量身定制的组签名方案，并假设硬件是可信的。然而，人们对硬件组件和嵌入式系统的可信度越来越关注。例如，一个被颠覆的硬件可能会利用其签名来提取识别信息甚至签名密钥。



<a name="apAb8"></a>
### [Microarchitectural Isolation Guarantees Through Execution Based Signatures](https://ieeexplore.ieee.org/abstract/document/9268660/)
S Briongos, P Malagón, JM Moya, T Eisenbarth - … on Design of Circuits and Integrated …, 2020
> 可信执行环境(TEE)旨在为某些计算提供完整性和保密性保证，而不考虑系统其他部分的状态。也就是说，即使操作系统或管理程序受到损害，它们也能保护受信任的应用程序（TA）。TEE与操作系统并行运行，并利用一组硬件和软件组件来创建这样一个隔离的环境。然而，这种隔离可以通过利用微架构侧通道来打破。多核处理器的共享组件的状态取决于实际执行的进程，因此，一些信息会从一个进程泄露给同一处理器中运行的任何其他进程。这种泄漏完全打破了TEE所承诺的保密性保证。完全避免泄漏的唯一方法是避免资源的共享，但这几乎是不可能实现的，否则处理器的性能就会大大降低。假设有可能存在泄漏，而攻击者只能从可观察到的微架构状态中获取信息，我们提出对硬件资源进行监控，以检测攻击引起的微架构状态变化。为此，我们实现了一个硬件模块，在运行时将每个飞地预先存储的微架构执行签名，与实际的执行痕迹进行比较，当检测到有明显变化时，就会触发报警。

<a name="bKM8l"></a>
### The design of scalar AES Instruction Set Extensions for RISC-V
> 安全、高效地执行AES是大多数计算平台的基本要求。专门的指令集扩展(ISE)通常是为此目的而包含的。RISC-V是一个（相对）新的ISA，缺乏这样一个标准化的ISE。我们调查了最先进的工业和学术界的AES ISE，实现并评估了五种不同的ISE，其中一种是新颖的。我们为32位和64位基础架构推荐了单独的ISE，与基于使用T表的纯软件实现相比，AES-128块加密的硬件成本分别提高了4倍和10倍，硬件成本为1.1K和8.2K门。我们还探讨了如何利用所提出的RISC-V标准位操作扩展来高效实现AES-GCM。我们的工作支持正在进行的RISC-V密码学扩展标准化进程。

<a name="yGH6k"></a>
### [Power and Performance optimized Domino Comparator in 7nm FinFET for TLBs](https://ieeexplore.ieee.org/abstract/document/9270064/)
T Masina, K Rahul, S Yachareni - 2020 4th International Conference on Electronics …, 2020
> 翻译旁观缓冲器(TLB)用于将微处理器中的虚拟地址转换为物理地址。翻译旁观缓冲器(TLB)利用基于多米诺的高速地址比较器，更快地产生感测地址错位。多米诺逻辑电路在设计中用于实现更高的速度，但容易产生PVT变化。在先进的FinFET节点中，较高的金属电阻和电容限制了性能和功耗的降低。本文介绍了7nm技术中多米诺骨牌地址比较器的优化，以克服速度和功耗的限制。本研究采用的银行技术基于多米诺节点电容比较了多米诺比较器的性能和可靠性。所提出的技术显著提高了128位和64位地址比较器的功耗和性能。

<a name="5f3mA"></a>
## 加密加速
<a name="k64e0"></a>
### [Efficient Hardware/Software Co-Design for Post-Quantum Crypto Algorithm SIKE on ARM and **RISC**-**V **based Microcontrollers](https://ieeexplore.ieee.org/abstract/document/9256463/)
DB Roy, T Fritzmann, G Sigl - 2020 IEEE/ACM International Conference On …, 2020<br />这里提到SIKE抗量子算法，设计了一个加速器集成到RISC-V和ARM平台，表示他们是第一个应用到RISC-V上的SIKE设计。RISC-V的加速比是ARM的两倍快
> 由于量子计算机发展的最新进展，后量子密码学已经成为一个非常有吸引力的研究课题。在现有的不同的后量子公钥算法中，超星异源密钥封装(Supersingular Isogeny Key-Encapsulation，SIKE)由于其资源密集型算子，但具有密钥尺寸小的特点，因此提出了独特的设计挑战。SIKE的现有实现要么关注FPGA平台上的专用加速器，要么关注ARM上的汇编优化软件实现。完全的FPGA实现虽然具有低延迟和高性能，但存在面积占用大、灵活性低的缺点。另一方面，与FPGA实现相比，纯软件实现的性能较低。本文提出了SIKE的硬件/软件协同设计方法，将基于冗余数的有限场加速器集成到基于ARM和RISC-V的两个微控制器平台上。结果表明，我们在ARM Cortex-A9上的实现与在ARM32和ARM64上的独立软件实现相比，增强了场加速器，在时钟周期方面提供了显著的加速。此外，为了展示如何减轻处理器和加速器之间的通信开销，我们将有限场加速器直接集成到RISC-V处理器的内核中。据我们所知，这是第一个应用硬件/软件协同设计方法在ARM和RISC-V平台上实现SIKE的设计。我们提出的设计需要65500 K时钟周期才能在ARM Cortex-A9处理器上执行SIKEp434。在RISC-V上，我们提出的设计只需要36900K的时钟周期。


<br />

<a name="GLzL5"></a>
### **[PDF]** [Fast packet classification on FPGA using **RISC**-**V **and binary search acceleration](https://dspace.lib.ntua.gr/xmlui/bitstream/handle/123456789/51950/my_ntua_thesis_final.pdf%3Fsequence%3D1)
P Arsinoi - 2020
> 通信技术对性能的要求推动着人们对先进网络处理器的研究，这些处理器能够通过特定应用的电路来处理巨大速率的传入数据包，然而，并没有牺牲所有传统CPU的灵活性。同时，加州大学伯克利分校开发的开源ISA处理器RISC-V的出现，正在颠覆工业界和学术界，它将计算机架构开放给更广泛的研究群体，让更多的研究人员可以探索架构和实现问题。结合上述情况，目前的工作考虑在RISC-V处理器旁边放置专用的VHDL加速器，通过定制的HW/SW协同处理来适应网络功能。我们在研究中使用HyperSplit算法进行性能测量，处理最常见、最具挑战性的网络任务，即包分类。我们在RISC-V ISA的指令子集RV64IAC中扩展了一条新的指令，该指令对应于HyperSplit二元搜索树操作。对于我们的硬件设计，我们使用火箭芯片生成器，创建了一个包括一个RV64IAC RISC-V核和核心加速器通信能力的配置。我们创建了一个VHDL HyperSplit搜索硬件加速器，我们使用RoCC接口将其连接到主火箭芯片RISC-V核。 
> 为了进行快速原型设计和设计探索，我们在Xilinx Ultrascale xcku060 FPGA上实现了HyperSplit算法的二进制搜索。我们的VHDL加速器消耗5K LUT、2K DFF、0 DSP和570 RAMB(占FPGA的53%)，用于存储高达381K节点的数据结构。通过调整我们的流水线。 
> 我们实现了P=5个流水线级的fclk= 227MHz。我们的RISC-V利用了15K LUT、7K DFF、0 DSP和5 RAMB，工作在143MHz。 
> 加入我们新的加速器，该设计加速了包分类任务，实现了比单独使用RISC-V快113倍的分类速度，维持高达25.4M包/秒的吞吐量（例如，支持8.1Gbps流量的路由器）。

<a name="Bac3f"></a>
## 扩展指令
<a name="5P7Bg"></a>
### **[PDF]** [RVCoreP-32IC: A high-performance **RISC**-**V **soft processor with an efficient fetch unit supporting the compressed instructions](https://arxiv.org/pdf/2011.11246)
T Kanamori, H Miyazaki, K Kise - arXiv preprint arXiv:2011.11246, 2020
> 在本文中，我们提出了一种高性能的RISCV软处理器，它的取数单元支持FPGA上的压缩指令目标。RISC-V中的压缩指令扩展可以减少约25%的程序大小。但它需要一个复杂的逻辑的指令获取单元，并有一个signiﬁcant影响性能。



<a name="B2gdk"></a>
### 
<a name="FZ2Fd"></a>
### **[PDF]** [XpulpNN: Enabling Energy Efficient and Flexible Inference of Quantized Neural Network on **RISC**-**V **based IoT End Nodes](https://arxiv.org/pdf/2011.14325)
A Garofalo, G Tagliavini, F Conti, L Benini, D Rossi - arXiv preprint arXiv:2011.14325, 2020
> 强量化的ﬁxed点算术现在被认为是在有限内存的低功耗物联网终端节点上部署卷积神经网络(CNN)的一个成熟的解决方案。由于最先进的嵌入式微控制器(MCU)的指令集架构(ISA)缺乏对低位宽ﬁed点指令的支持，这种趋势具有挑战性，而这些指令集架构主要基于封闭式ISA，如ARM Thumb2和相关的Helium扩展。新兴的开源ISA（如RISC-V）为解决这一挑战提供了一个可行的方法。本文介绍了RISC-V ISA的轻量级扩展，以提高微控制器级内核上大量量化神经网络（QNN）推理的效率。通过扩展ISA的nibble(4位)和crumb(2位)SIMD指令，我们能够在QNN计算的关键内核上显示出与更高精度整数计算近乎线性的速度。此外，我们还为SIMD点积和运算提出了一种定制的执行范式，该范式包括融合点积和负载运算，与标准执行方案相比，其MAC/周期峰值提高了1.64×。为了进一步提升效率，我们将RISC-V扩展核集成在一个8个处理器的并行集群中，与单核架构相比有近乎线性的改进。为了评估所提出的扩展，我们在GF22FDX技术中完全实现了处理器集群。与仅支持8位SIMD指令的基线处理集群相比，当考虑4位和2位数据操作数时，实现拟议扩展的并行集群上的QNN卷积内核运行速度分别提高了6×和8×。所提出的解决方案的峰值为2.22 TOPs/s/W，实现了与专用DNN推理加速器相当的效率水平，比基于ARM Cortex-M的最先进微控制器系统（如低端STM32L4 MCU和高端STM32H7 MCU）高出三个数量级。

<a name="P3XJd"></a>
### 

<a name="Xuo0K"></a>
## 工具链和EDA
<a name="7w3FQ"></a>
### **[PDF]** [Effective simulation and debugging for a high-level hardware language using software compilers](https://pit-claudel.fr/clement/papers/cuttlesim-ASPLOS21.pdf)
C Pit-Claudel, T Bourgeat, S Lau, A Chlipala
> 基于规则的硬件设计语言(RHDLs)承诺通过提供方便的抽象来提高开发人员的工作效率。先进的编译器技术使这些抽象的成本保持在较低水平，生成的电路具有优良的面积和时序特性。

<a name="aYq9x"></a>
### [DEMAC: A Modular Platform for HW-SW Co-Design](https://conferences.computer.org/scwpub/pdfs/IPDRM2020-3jMNia0OMaspWzJWzIl5zk/106400a025/106400a025.pdf)
DAR Perdomo, R Kabrick, JMM Diaz, S Raskar, D Fox… - Fourth Annual Workshop on …, 2020
> 在高性能计算机上运行应用程序的科学家们希望这些系统能够有效和可靠地提供高吞吐量，同时保持灵活性、可编程性和节能性。程序通常由编码语言翻译而来，通过编译器确定这些系统的操作。HPC机器根据其架构特点表现出不同的特征和行为：它们可以有加速器，也可以是具有非统一内存访问的计算单元的集合。

<a name="KFcjs"></a>
### [Your Agile Open Source HW Stinks (Because It Is Not a System)](https://ieeexplore.ieee.org/abstract/document/9256743/)
MB Taylor - 2020 IEEE/ACM International Conference On …, 2020
> 硬件设计的激动人心的时代正在到来。在RISC-V ISA和最近的DARPA POSH/IDEA计划的带动下，大量的开源硬件项目正在进行。学术界越来越多地在网上发布他们的代码。许多敏捷的开源HW项目设想的是一个假想的用户，但实际上可能并不存在。为了获得真正的用户，我们必须务实地了解我们的HW将进入什么样的系统，并关注这些系统特有的路障。

<a name="8EuNl"></a>
### [Conference Report From The 57th Design Automation Conference](https://ieeexplore.ieee.org/abstract/document/9271841/)
Z Li - IEEE Design & Test, 2020
> 第57届设计自动化大会(DAC)是其57年历史上的第一次虚拟DAC。原计划于2020年7月19日至7月23日在Moscone West会议中心举行，但由于COVID-19的原因，DAC执委会和赞助商ACM/IEEE共同决定采用虚拟的方式。DAC 2020于7月21日-7月24日虚拟举办，并将虚拟内容延长一周，供注册参会人员使用。能够担任第一届虚拟DAC的主席，我感到非常荣幸。



<a name="WT1HK"></a>
### 

<a name="fc8xP"></a>
## 应用
<a name="5gXsj"></a>
### **[PDF]** [Design and implementation of graphical interface of vehicle display and control system based on SylixOS](https://iopscience.iop.org/article/10.1088/1742-6596/1678/1/012024/pdf)
J Zhang, X Yang, X Dong, X Tian - Journal of Physics: Conference Series, 2020
> 为了满足目前车辆显示控制系统的设计要求，同时考虑到目前软硬件平台的自主可控要求，本文提出了一套国产化的解决方案。选用隆鑫2K1000作为主控芯片，基于SylixOS自主实时操作系统完成了车辆显示控制系统的接口设计和开发。本文阐述了开源图形库Qt的开发过程，并针对开发过程中遇到的屏幕闪烁问题提出了解决方案。

<a name="ElowH"></a>
### [Building OpenLANE: A 130nm OpenROAD-based Tapeout-Proven Flow](https://ieeexplore.ieee.org/abstract/document/9256623/)
M Shalan, T Edwards - 2020 IEEE/ACM International Conference On …, 2020
> 构建一个完全开源的系统级芯片(SoC)意味着使用开源工具、开源代工工艺设计套件(PDK)和开源IP库，包括标准单元库和模拟块。这种努力涉及到许多挑战和众多实体之间的合作。在本演讲中，我们将介绍StriVe，这是一个小型的开源SoC，采用基于开源EDA工具的流程设计，并以代工工艺为目标，使用开源PDK和IP库，从概念到芯片验证。通过设计StriVe，我们的目的是要证明，任何对使用开源EDA工具和流程来生成定制ASIC设计的怀疑都是错误的。

<a name="KlCAb"></a>
### **[PDF]** [An Application of Mask Detector For Prevent Covid-19 in Public Services Area](https://iopscience.iop.org/article/10.1088/1742-6596/1641/1/012063/pdf)
AS Rafika, HLHS Warnar, MA Saputra - Journal of Physics: Conference Series, 2020
> 冠状病毒病(COVID-19)已进入印尼，使政府实施大规模的社会限制，以减少冠状病毒的传播。由于冠状病毒阳性患者的增加，政府不断呼吁并要求印尼人使用口罩。无论是健康的人或那些谁是病人。这个呼吁是符合世界卫生组织（WHO）的建议，防止COVID19的传播。因此，有必要开发用于实时监控公共服务区未使用口罩的人的工具。我们开发的面具检测的应用程序，使用相机，作为照片和视频输入的功能，并连接到Speed Maix Bit微处理器处理数据，并将其显示在LCD上。我们的目的是解决关于没有使用口罩或没有立即使用口罩的人的问题，以尽量减少COVID-19的传播。我们的最终实验表明，该应用程序高度检测的人在公共区域使用口罩或没有。本研究對於防範COVID-19的口罩偵測器的構思、設計系統與規則的應用有很大的貢獻。

<a name="60rsM"></a>
### [Developing an AI IoT application with open software on a **RISC**-**V **SoC](https://ieeexplore.ieee.org/abstract/document/9268645/)
E Torres-Sánchez, J Alastruey-Benedé… - 2020 XXXV Conference on …, 2020
> RISC-V是一种新兴的架构，在低功耗物联网应用中的优势正在不断增强。架构扩展的稳定和基于RISC-V的SOC（如Kendryte K210）开始商业化，这就提出了一个问题，即这种开放标准是否会促进特定市场的应用开发.在本文中，我们评估了与Sipeed MAIX Go开发板相关的开发环境、工具链、调试过程，以及Kendryte K210的独立SDK和Micropython端口。此外，还研究了内置卷积神经网络加速器的训练管道，并支持Tiny YOLO v2。为了对以上各方面进行深入评估，我们开发了两个基于人工智能的低成本、低功耗的物联网边缘应用。第一个是能够识别房子里的动静，并自主识别是人造成的还是房子里的宠物造成的，比如说狗或者猫。在目前COVID-19大流行的背景下，第二个应用能够标注行人是否戴了面罩，以平均13FPS的速度进行实时物体识别。纵观整个过程，我们可以得出这样的结论：尽管硬件潜力巨大，性能/成本比也很出色，但面向开发者的文档很少，开发环境处于低成熟度，调试过程有时也不存在。

<a name="pFdq6"></a>
### **[PDF]** [Sim2Real Transfer for Deep Reinforcement Learning with Stochastic State Transition Delays](https://assets.amazon.science/1f/8c/983e48114baaab0ae5f03e2fd4d5/sim2real-transfer-for-deep-reinforcement-learning-with-stochastic-state-transition-delays.pdf)
SS Sandha, L Garcia, B Balaji, FM Anwar, M Srivastava
> 深度强化学习(RL)已被证明对各种机器人应用是有用的。为了解决训练过程中的样本有效性和安全性，通常在模拟器中训练深度RL策略，然后部署到现实世界，这个过程称为Sim2Real转移。对于机器人应用来说，部署的异构性和运行时计算的随机性导致传感器采样率的时序特性变化，以及从感知到执行的端到端延迟。之前的工作已经使用域随机化技术来实现策略在具有不同状态转换延迟的域间的成功转移。我们表明，采样率和策略执行时间的变化会导致Deep RL策略性能的下降，而域随机化不足以克服这一限制。我们提出了Time-in-State RL (TSRL)方法，该方法在训练时将延迟和采样率作为额外的代理观测值，以提高Deep RL策略的鲁棒性。我们在模拟和使用1/18比例的汽车的真实机器人上展示了TSRL在HalfCheetah、Ant和汽车机器人上的有效性。

<a name="ukgcf"></a>
## 工艺
<a name="bh6bq"></a>
### [RTL-to-GDS Design Tools for Monolithic 3D ICs](https://ieeexplore.ieee.org/abstract/document/9256662/)
J Kim, G Murali, P Vanna-Iampikul, E Lee, D Kim… - 2020 IEEE/ACM …, 2020
> 在本文中，我们提出了用碳纳米管场效应晶体管和电阻存储器构建的单片3D集成电路（M3D）的RTL-to-GDS设计流程。我们的工具流程是基于商业化的2D工具和智能方法来扩展它们来进行M3D设计和仿真。我们提供了一个后路线优化流程，充分利用底层M3D工艺设计套件（PDK）的潜力进行功率、性能和面积（PPA）优化。我们还对M3D设计进行红外跌落和热分析，以提高可靠性。为了提高M3D设计的可测试性，我们开发了以设计促测试(DFT)的方法，并将低开销的内置自测试模块集成到我们的设计中，用于测试层间孔(ILV)以及各层的逻辑电路。我们的基准设计是RISC-V Rocketcore，这是一个开源处理器。我们的实验表明，在等效性能下，M3D设计比2D设计节省了8.1%的功耗、19.6%的线长和55.7%的面积。此外，我们的IR-drop和热分析表明，我们的M3D设计具有可接受的功率和热完整性。



<a name="EhvV1"></a>
### [Machine Learning Based Hardware Trojan Detection Using Electromagnetic Emanation](https://link.springer.com/chapter/10.1007%2F978-3-030-61078-4_1)
P Lejoly - … Security: 22nd International Conference, ICICS 2020 …
> 现代系统级芯片(SoC)的复杂性和外包趋势，使得硬件木马(HT)成为SoC安全的现实威胁。在最先进的技术中，已经提出了许多技术来检测HT的插入。基于侧通道的方法作为一种很好的方法出现在HT检测中。他們可以提取任何差異的功耗，電磁（EM）發射，延遲傳播，等引起的HT插入/修改在真正的設計。因此，它们可以应用于检测HT，即使它没有被激活。然而，这些方法是在AES协处理器等过于简单的设计原型上进行评估的。此外，这些方法所使用的分析方法受到一些统计指标的限制，如EM痕迹的直接比较或T检验系数。在本文中，我们提出了两种基于机器学习算法的新检测方法。第一種方法是在原始的 EM 軌跡上應用有監督的機器學習 (ML) 演算法來進行 HT 的分類和檢測，它提供了接近 90% 的檢測率。该方法的检测率接近90%，假阴性小于5%。第二种方法，我们提出了一种基于离群/新奇算法的方法。此方法结合基于T-test的信号处理技术，与最先进的技术相比，提供了更好的性能，检测率接近100%，假阳性小于1%。我们已经在一个复杂的目标设计上评估了我们方法的性能。RISC-V通用处理器。插入了RISC-V处理器相应大小为0.53%、0.27%和0.1%的三个HT进行实验。实验结果表明，插入的HT虽然是最小化的，但可以用我们的新方法来检测。



<a name="6XM2k"></a>
### [Twenty Years of Near/Sub-Threshold Design Trends and Enablement](https://ieeexplore.ieee.org/abstract/document/9273082/)
K Singh, JP de Gyvez - IEEE Transactions on Circuits and Systems II: Express …, 2020
> 本教程论文调查了过去20年的近/亚阈值数字集成电路设计。大多数的芯片已经被高度表征为电压缩减到近/亚阈值，并且已经报道了一个显著的定制设计工作，以实现可靠的操作。在本教程中，我们讨论了工艺变化的挑战，并讨论了多年来用于最小化这种影响的电路和方法。我们讨论了标准单元库设计的优势，并提供了一种涉及更多的修剪方法来提高性能和鲁棒性。最后，我们讨论了通常被忽略的近/亚阈值电路的功率传输技术的发展。我们激励使用电压堆叠作为一种新的近/亚阈值的功率交付技术。本文根据我们的经验，提供了设计工作在近/亚阈值区域的芯片的基本使能方法。



<a name="TTOGD"></a>
## 一周专利
<a name="nXUKo"></a>
### 专利：[Securing conditional speculative instruction execution](https://patents.google.com/patent/US20200356374A1/en)
SJ Wallach - US Patent App. 16/942,591, 2020
> 在处理器中执行的方法，包括：在处理器中接收处理中的分支指令；由处理器确定分支指令后的指令地址为推测执行的候选地址，该地址包括对象标识和偏移量；由处理器根据地址的对象标识确定是否对分支指令后的指令进行推测执行。


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

