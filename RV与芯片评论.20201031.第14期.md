# RV与芯片评论.20201031.第14期


<br />本期概要

- Linux5.10发布，GUN Degubber10.1支持RISC-V GUN
- RISC-V Summit议程发布，欧洲开源峰会本周结束，开放核心峰会下周举行
- SIFive的RISC-V PC发布，64bit PolarBerry最小核心板，OpenHWGroup大部64bit的CVA6核心
- Imagination因为国际关系开始调整公司战略
- 博客推荐：CPU系统级验证，理解RISC-V中的跳转指令
- 一周论文推荐：ETH为5G RNN的RISC-V扩展指令集




---

<a name="cgX2z"></a>
# 重点聚焦


<a name="qQM4M"></a>
### 国产开源架构芯片大赛暨创新论坛
> 2020年10月30日09:30-12:00
> 由中关村科学城源码开源芯片创新中心主办，北京微芯区块链与边缘计算研究院、芯来科技（北京）有限公司承办，中国RISC-V产业联盟与中国开放指令生态(RISC-V)联盟协办。
> 

> 国产开源架构芯片大赛发布，助力aRISC-V应用生态普及
> 中国科学院RISC-V开源主线规划及“一生一芯”集成电路教学创新
> 清华大学“天格计划”介绍：本科生团队基于实验卫星实现双中子星并合所产生的伽马射线暴探测
> 基于RISC-V的开源芯片最新技术进展及RISC-V产教结合生态


<br />"[报名 | 国产开源架构芯片大赛暨创新论坛 ](https://mp.weixin.qq.com/s?__biz=MzU1Mzk1OTE2MA==&mid=2247484018&idx=1&sn=45037f349eb9d602b4753e6819bd6df9&scene=21#wechat_redirect
)(From mp.weixin.qq.com 2020.10.29)"<br />
<br />

<a name="ouGii"></a>
### RISC-V Summit议程发布


<a name="sNlAT"></a>
### 欧洲开源峰会结束
<a name="u1qhF"></a>
### 相关周报

- "[OSDT Weekly 2020-10-28 第069期 ](https://mp.weixin.qq.com/s/LWUoGsuvjr9QJeb4EusaMQ
)(From mp.weixin.qq.com 2020.10.29)"
- "[Connected Car News: GMC, Toyota AI, Volvo, Opus IVS, TomTom, FEV, HERE, what3words, Tyrata, SmartSens, Hyundai, Nexteer, OneSpin & ADASKY ](https://www.autoconnectedcar.com/2020/10/connected-car-news-gmc-toyota-ai-volvo-opus-ivs-tomtom-fev-here-what3words-tyrata-smartsens-hyundai-nexteer-onespin-adasky/
)(From www.autoconnectedcar.com 2020.10.25)"
- "[SD Times news digest: DataKitchen’s DataOps Transformation Advisory Service, Netlify team overview, and Rackspace’s new IoT solutions ](https://sdtimes.com/softwaredev/sd-times-news-digest-datakitchens-dataops-transformation-advisory-service-netlify-team-overbiew-and-rackspaces-new-iot-solutions/
)(From sdtimes.com 2020.10.26)"
- "[ELEXCON2021电子展精彩内容发布！即刻跟进您不可错过的行业热点 ](https://my.oschina.net/u/4419179/blog/4692383
)(From my.oschina.net 2020.10.28)"
- "[【Rust日报】2020-10-28 RustSBI项目已进入RISC-V SBI标准 ](https://rustcc.cn/article?id=47ccf4e1-61d3-4130-a5c6-aa523dd08612
)(From rustcc.cn 2020.10.28)"
- "[Top articles in October on eeNews Europe ](https://www.eenewseurope.com/news/top-articles-october-eenews-europe
)(From www.eenewseurope.com 2020.10.30)"
- "[Week In Review: Design, Low Power ](https://semiengineering.com/week-in-review-design-low-power-118/
)(From semiengineering.com 2020.10.30)"

---



<a name="nqDGS"></a>
# 技术动态

- "[Ashling宣布RiscFree支持Arm和RISC-V的同时调试 ](https://finance.sina.com.cn/tech/2020-10-28/doc-iiznezxr8477643.shtml
)(From finance.sina.com.cn 2020.10.28)"
- "[关于开源这件事，openEuler到底做得怎么样了？ ](https://www.donews.com/article/detail/4877/25553.html
)(From www.donews.com 2020.10.28)"

<br />
<a name="vWTYw"></a>
### RISC-V 5.10发布
<a name="DCC7j"></a>
### RustSBI v0.0.2发布
<a name="UQCtX"></a>
### <br />
<a name="EN4Pb"></a>
### GNU Debugger 10.1发布，支持RISC-V GNU/Linux

<br />

<a name="tGhVe"></a>
### Truechip：新增包括TileLink在内的多个RISC-V IP验证
<br />
<a name="S7B0n"></a>
### RISC-V解析器
<br />
<a name="T7WyA"></a>
### MEEP: 欧洲MEEP项目为RISC-V生态系统建设开源数字图书馆
<br />
<a name="7qzJH"></a>
### Linux动态

- "[Linux Kernel 5.10合并窗口期已关闭 诸多改进和新功能一览 ](https://www.cnbeta.com/articles/tech/1045099.htm
)(From www.cnbeta.com 2020.10.25)"
- "[[PATCH 4/4] arch, mm: make kernel_page_present() always available ](https://lkml.org/lkml/2020/10/25/51
)(From lkml.org 2020.10.25)"
- "[linux-next: manual merge of the risc-v tree with Linus' tree ](https://lkml.org/lkml/2020/10/25/208
)(From lkml.org 2020.10.26)"
- "[Re: [PATCH 1/3] irqchip/irq-sifive-plic: Fixup wrong size of xxx_PER_HART and reg base ](https://www.spinics.net/lists/kernel/msg3707407.html
)(From www.spinics.net 2020.10.25)"
- "[[PATCH AUTOSEL 5.9 071/147] riscv: Define AT_VECTOR_SIZE_ARCH for ARCH_DLINFO ](https://www.mail-archive.com/linux-kernel@vger.kernel.org/msg2353701.html
)(From www.mail-archive.com 2020.10.26)"
- "[[PATCH v2 4/6] RISC-V: Align the .init.text section ](https://lkml.org/lkml/2020/10/26/1263
)(From lkml.org 2020.10.26)"
- "[[PATCH AUTOSEL 5.8 063/132] riscv: Define AT_VECTOR_SIZE_ARCH for ARCH_DLINFO ](https://lkml.org/lkml/2020/10/26/1694
)(From lkml.org 2020.10.26)"
- "[[PATCH AUTOSEL 5.8 063/132] riscv: Define AT_VECTOR_SIZE_ARCH for ARCH_DLINFO ](https://www.spinics.net/lists/stable/msg420579.html
)(From www.spinics.net 2020.10.26)"
- "[[Kernel-packages] [Bug 1894613] Re: risc-v 5.8 kernel oops on ftrace tests ](https://www.mail-archive.com/kernel-packages@lists.launchpad.net/msg425541.html
)(From www.mail-archive.com 2020.10.28)"
- "[	Re: [RFC PATCH 2/3] RISC-V: Initial DTS for Microchip ICICLE board ](https://lkml.org/lkml/2020/10/30/1206
)(From lkml.org 2020.10.30)"



<a name="SYbmw"></a>
### QEMU动态

- "[Re: [PATCH] riscv: Add semihosting support [v8] ](https://www.mail-archive.com/qemu-devel@nongnu.org/msg753718.html
)(From www.mail-archive.com 2020.10.23)"
- "[Re: [PATCH] riscv: Add semihosting support [v8] ](https://www.mail-archive.com/search?l=qemu-devel@nongnu.org&q=subject:%22Re%5C%3A+%5C%5BPATCH%5C%5D+riscv%5C%3A+Add+semihosting+support+%5C%5Bv8%5C%5D%22&o=newest&f=1
)(From www.mail-archive.com 2020.10.26)"
- "[[PATCH v7 5/7] arch, mm: wire up memfd_secret system call were relevant ](https://www.mail-archive.com/linux-kernel@vger.kernel.org/msg2352051.html
)(From www.mail-archive.com 2020.10.26)"
- "[Re: [PATCH 0/4] Add RISC-V semihosting support ](https://www.mail-archive.com/qemu-devel@nongnu.org/msg755375.html
)(From www.mail-archive.com 2020.10.28)"
- "[[PULL 00/18] riscv-to-apply queue ](https://www.mail-archive.com/qemu-devel@nongnu.org/msg755568.html
)(From www.mail-archive.com 2020.10.29)"

<br />
<a name="v2ah0"></a>
### 一周问答

- "[lw vs addi in assembly? [closed] ](https://stackoverflow.com/questions/64564371/lw-vs-addi-in-assembly
)(From stackoverflow.com 2020.10.27)"
- "[Do you think it might be useful to spend some time to recover toolchain from source?  ](https://github.com/pine64/bl_iot_sdk/issues/13
)(From github.com 2020.10.31)"
   - 有人在github上提了issue
- "[Assembly how to properly Read data into register [closed] ](https://stackoverflow.com/questions/64586865/assembly-how-to-properly-read-data-into-register
)(From stackoverflow.com 2020.10.30)"
<a name="CC8oT"></a>
### 社区动态

- "[大咖问答17期：胡振波带你玩转RISC-V架构及嵌入式设计 ](https://www.cirmall.com/bbs/thread-170867-1-1.html
)(From www.cirmall.com 2020.10.13)"
   - 胡振波老师参加电路城论坛第十七期大咖问答（10月13日-10月25日），为大家解答RISC-V相关方面的各种问题




---

<a name="SM5cC"></a>
# 产业风云

- "[芯来科技RISC-V处理器IP 荣获2020年“中国芯”新锐产品 ](https://mp.weixin.qq.com/s?__biz=MzUxNDkyNzYxNA==&mid=2247485202&idx=1&sn=2505b3445cba0cc4ba61584d0480af17&chksm=f9bf3983cec8b0953c0351f6ff56ed22dd532c4c3ec6c9d1a9e29dbcfd387bf89b9c1fdfc049&mpshare=1&scene=1&srcid=1028Bb5ivUYrCzMPJSnECzP4&sharer_sharetime=1603868758097&sharer_shareid=c9a17b92d9e10beff73b35c4264d6f51#rd
)(From mp.weixin.qq.com 2020.10.28)"
- "[Nvdia收购Arm，将大力推进RISC-V的进展 ](http://news.eeworld.com.cn/manufacture/ic514463.html
)(From news.eeworld.com.cn 2020.10.27)"
- "[Ashling宣布RiscFree支持Arm和RISC-V的同时调试 ](http://news.eeworld.com.cn/manufacture/ic514459.html
)(From news.eeworld.com.cn 2020.10.27)"
- "[格兰仕家电出口量逆势增长近20% 开源芯片平台持续扩大 ](https://finance.sina.com.cn/chanjing/gsnews/2020-10-28/doc-iiznezxr8452605.shtml
)(From finance.sina.com.cn 2020.10.28)"
- "[AMD to Acquire Xilinx, Creating the Industry’s High Performance Computing Leader ](https://www.amd.com/en/press-releases/2020-10-27-amd-to-acquire-xilinx-creating-the-industry-s-high-performance-computing
)(From www.amd.com 2020.10.31)"
   - [https://news.ycombinator.com/item?id=24906151](https://news.ycombinator.com/item?id=24906151)
- "[零跑发布凌芯01智能驾驶芯片 最早或于明年底启动IPO  ](https://www.sohu.com/a/428204411_115362
)(From www.sohu.com 2020.10.31)"
   - 凌芯01采用了阿里旗下平头哥半导体公司的玄铁C860 32位CPU。
- 
- 



<a name="z3vL9"></a>
### BL602
BL602在上周发布后，引起很多关注。<br />甚至举办了坚果挑战赛，现在仍能报名

<a name="WJLah"></a>
### IAR: 为RISC-V指令提供安全认证
<br />
<a name="axU5a"></a>
### SiFive的FU740 PC板发布
<a name="B6xH6"></a>
### PolarBerry：64bit RIAC-V最小核心板


<a name="GdGTk"></a>
### OpenHWGroup：CVA6：64bit RISC-V
<a name="EraOz"></a>
### Codeplay：参与日本NSITEXE和KMC项目


<a name="9qCGF"></a>
### Imagination: 国际局势变化让他们的战略开始动摇


<a name="T9ijf"></a>
### 其它产业

- "[New Neoverse Platforms Take on the Cloud, HPC, and the Edge ](https://www.electronicdesign.com/technologies/embedded-revolution/article/21143244/electronic-design-new-neoverse-platforms-take-on-the-cloud-hpc-and-the-edge
)(From www.electronicdesign.com 2020.10.30)"

Zeus和Perseus，又称Neoverse V1和Neoverse N2，分别集成了针对关键任务环境进行优化的核心。<br />N1架构应用在亚马逊的Graviton处理器中，该处理器在一些AWS装置中使用。<br />![](https://cdn.nlark.com/yuque/0/2020/png/1541992/1604050550145-6e61ed7f-e66e-4668-b236-236c933e8a57.png#align=left&display=inline&height=225&margin=%5Bobject%20Object%5D&originHeight=433&originWidth=770&size=0&status=done&style=none&width=400)<br />

- "[Micromax“ in”系列将于11月3日发布 ](https://www.gsmarena.com/micromax_in_series_launch_date-news-45939.php
)(From www.gsmarena.com 2020.10.30)"

印度手机制造商Micromax想要凭借in系列手机重返印度手机市场，并宣传不要买中国手机。新闻没啥，就是评论炸了。<br />[https://www.gsmarena.com/newscomm-45939.php](https://www.gsmarena.com/newscomm-45939.php)<br />
<br />

- "[OpenHPC Progress Report – v2.0, More Recipes, Cloud and Arm Support, Says Schulz ](https://www.hpcwire.com/2020/10/26/openhpc-progress-report-v2-0-more-recipes-cloud-and-arm-support-says-schulz/
)(From www.hpcwire.com 2020.10.30)"

OpenHPC于2015年底启动，2016年过渡到Linux基金会项目。目标是 "提供开源HPC软件组件和最佳实践的参考集合，降低部署、推进和使用现代HPC方法和工具的障碍"，虽然英特尔是早期的推动者让人担心，但依然极受欢迎。此后，OpenHPC坚持走开源道路（同时仍享受英特尔的支持）。<br />本月OpenHPC发布了针对新的Linux操作系统发行版的2.0版本，并加入了对云和Arm的新支持。<br />
<br />
<br />

<a name="PO7vP"></a>
### 评论文集

- "[“硅谷教父”：技术推动世界繁荣  ](https://www.sohu.com/a/427460487_114986
)(From www.sohu.com 2020.10.26)"
- "[玩家布局，为什么家电厂商转型IoT迫在眉睫? ](https://iot.ofweek.com/2020-10/ART-132216-8500-30466185.html
)(From iot.ofweek.com 2020.10.26)".
- "[Why Universities Want RISC-V ](https://www.eejournal.com/article/why-universities-want-risc-v/
)(From www.eejournal.com 2020.10.27)"
- "[US-China Chip Wars To Force Beijing To Adopt 'Warp Speed' Steps In Global Tech Divergence - Futurist ](https://sputniknews.com/analysis/202010271080889545-us-china-chip-wars-to-force-beijing-to-adopt-warp-speed-steps-in-global-tech-divergence---futurist/
)(From sputniknews.com 2020.10.27)"
- "[迎接一个新的半导体时代？写在AMD(AMD.US)收购Xilinx(XLNX.US)之后 ](https://finance.sina.com.cn/stock/hkstock/hkstocknews/2020-10-28/doc-iiznctkc8126772.shtml
)(From finance.sina.com.cn 2020.10.28)"
- "[LeapFive首席技术官江朝晖：RISC-V与区块链结合将为数据生产者、传播者带来价值 ](https://news.huoxing24.com/20201028144447851674.html
)(From news.huoxing24.com 2020.10.28)"
- "[RISC-V is trying to launch an open-hardware revolution ](https://www.engadget.com/risc-v-upscaled-120000950.html
)(From www.engadget.com 2020.10.30)"

<br />
<a name="jZbXK"></a>
### 工作机会

- "[Set up Couchbase in RISC-V eco-system (via QEMU) ](https://www.upwork.com/job/Set-Couchbase-RISC-eco-system-via-QEMU_~01d786389e2eade14c/
)(From www.upwork.com 2020.10.31)"




---



<a name="tAplU"></a>
# 其他动态
<a name="3KLeb"></a>
### 使用GD32VF103TB做的带Type-C的，电烙铁


<a name="tO9Sj"></a>
### 视频推荐

- "[RISC-V® Innovation Unleashed Webinar Series | #1 - Introduction to the PolarFire® SoC Icicle Kit ](https://vimeo.com/472713230
)(From vimeo.com 2020.10.31)"
   - 您是否刚拿到 Icicle 开发工具包，并准备好了解它的功能？在本网络研讨会中，您将学习如何开箱启动Linux®操作系统，并在套件上运行Web服务器以监控电力使用情况。您还将了解如何对 eNVM™ 进行编程，以便在启动时运行裸机应用程序，并将套件恢复到出厂映像以再次启动 Linux。
- "[Search Videos SharePlay Video Shields UP #5 - RISC V Enclaves: A Clean Slate Approach to Linux Security ](https://www.digikey.fr/en/videos/m/microchip/shields-up-5--risc-v-enclaves-a-clean-slate-approach-to-linux-security
)(From www.digikey.fr 2020.10.31)"
   - MultiZone™演示展示了如何确保混合关键性系统的确定性行为，把Linux和Real-Time跑在单个PolarFire SoC设备上。
<a name="be1P2"></a>
### 博文推荐: CPU系统级验证——指令集验证——force-riscv代码结构分析
> force-risc是由OpenHW开发的一款针对RISCV的指令集测试激励生成器，目前支持RV64的I、M、A、Zicsr、F、D、C、V（0.9版本）指令生成，且支持M/U/S三种工作模式，且支持动态虚拟内存管理动态，全页异常控制，存储子系统验证等特征，支持可配置状态转换，指令集模拟器互动，测试激励python脚本生成等功能。

"[CPU系统级验证——指令集验证——force-riscv代码结构分析 ](https://blog.csdn.net/qq_39815222/article/details/109280068
)(From blog.csdn.net 2020.10.26)"

<a name="lOeXC"></a>
### 博文推荐：理解RISC-V中的SETJMP/LONGJMP
<br />

---

<a name="2TkaG"></a>
# 一周论文
<br />
<a name="1emvK"></a>
### Extending the RISC-V ISA for Efficient RNN-based 5G Radio Resource Management

- [https://ieeexplore.ieee.org/document/9218496](https://ieeexplore.ieee.org/document/9218496)
- 作者：ETH: [Renzo Andri](https://ieeexplore.ieee.org/author/37085874340); [Tomas Henriksson](https://ieeexplore.ieee.org/author/37088527338); [Luca Benini](https://ieeexplore.ieee.org/author/37274443600)
> 5G移动通信中的无线电资源管理是一个具有挑战性的问题，对于这个问题，循环神经网络（RNN）已经显示出了可喜的结果。因此，加速计算密集型的RNN推理是至关重要的。可编程的解决方案对于有效的5G-RRM应对快速发展的RNN变化景观是可取的。在本文中，我们通过调整微控制器级开源RISC-V内核的指令集和微架构来研究RNN推理加速。我们将HW扩展与软件优化结合起来，在各种RRM任务中使用的广泛RNN上实现了15×和10×w.r.t.基线核的吞吐量和能效的整体提升。1


<br />

<a name="bErdN"></a>
### HECTOR-V: A Heterogeneous CPU Architecture for a Secure RISC-V Execution Environment
"[HECTOR-V: A Heterogeneous CPU Architecture for a Secure RISC-V Execution Environment ](https://arxiv.org/abs/2009.05262
)(From arxiv.org 2020.10.30)"
> 为了确保应用程序的安全和可信执行，厂商经常将可信执行环境嵌入其系统中。在这里，应用程序受到保护，免受包括恶意操作系统在内的对手的攻击。TEE通常通过将保护机制直接集成到处理器中或使用专用的外部安全元件来构建。然而，这两种方法都只能覆盖一个狭窄的威胁模型，导致有限的安全保证。应用处理器中的圈地通常在安全域和非安全域之间提供弱隔离，特别是在考虑侧通道攻击时。虽然安全元素确实提供了强隔离，但与应用处理器的缓慢通信接口暴露在对手面前，限制了使用案例。独立于所使用的实现方法，TEEs通常缺乏与外部外设建立安全通信的可能性，而且大多数在TEEs内部执行的操作系统没有提供最先进的防御策略，使得它们容易受到各种攻击。我们认为，在主应用处理器上实现的TEE是不安全的，特别是在考虑侧通道攻击时。我们演示了如何利用异构架构来实现安全的TEE设计。我们直接将处理器嵌入到我们的架构中，以提供安全域和非安全域之间的强隔离。TEE和REE的紧密耦合使得HECTOR-V能够提供建立安全通信通道的机制。我们进一步引入RISC-V安全协处理器，这是一个为TEE量身定做的安全加固处理器。为了保证TEE内部执行的应用安全，RVSCP提供控制流的完整性，严格限制I/O访问某些执行状态，并直接在硬件中提供操作系统服务。

<a name="EDKFu"></a>
### [Energy-Efficient Time Series Analysis Using Transprecision Computing](http://scholar.google.com/scholar_url?url=https://ieeexplore.ieee.org/abstract/document/9235029/&hl=en&sa=X&d=11417998940602614002&ei=CBuXX4vbFcS9yQTZ0LeIDA&scisig=AAGBfm3PR-ZNirOZhaTWgRdrKydf3tdPpw&nossl=1&oi=scholaralrt&hist=AQxAsJ0AAAAJ:3812021249043908228:AAGBfm19OZ2uvk2g_ev6ffIC03BRSiTYQw&html=)
I Fernandez, R Quislant, E Gutierrez, O Plata - 2020 IEEE 32nd International …, 2020<br />… This FPU is intended to be integrated on embedded devices as part of **RISC**-**V** processors,<br />FPGAs or ASICs to perform energy-efficient time series analysis. To this end, we propose<br />an accuracy metric to compare the results with the double precision matrix profile …<br />

<a name="UygLV"></a>
### **[PDF]** [COCO: Co-Design and Co-Verification of Masked Software Implementations on CPUs](http://scholar.google.com/scholar_url?url=https://eprint.iacr.org/2020/1294.pdf&hl=en&sa=X&d=10564044561797955140&ei=CBuXX4vbFcS9yQTZ0LeIDA&scisig=AAGBfm29t0LoMB588UWvdmKFAUEk5nPyAQ&nossl=1&oi=scholaralrt&hist=AQxAsJ0AAAAJ:3812021249043908228:AAGBfm19OZ2uvk2g_ev6ffIC03BRSiTYQw&html=)
B Gigerl, V Hadzic, R Primas, S Mangard, R Bloem<br />… concrete CPU. Using COCO, we analyze the popular 32-bit **RISC**-**V** IBEX core, identify<br />all design aspects that violate the security of our tested masked software<br />implementations and perform corrections, mostly in hardware. The …<br />

<a name="0HeUo"></a>
### [An End-to-End Approach for Multi-Fault Attack Vulnerability Assessment](http://scholar.google.com/scholar_url?url=https://ieeexplore.ieee.org/abstract/document/9237302/&hl=en&sa=X&d=6215762934178558553&ei=CBuXX4vbFcS9yQTZ0LeIDA&scisig=AAGBfm2FIW80_KeDZrh2j38oCUb8Wz6OiQ&nossl=1&oi=scholaralrt&hist=AQxAsJ0AAAAJ:3812021249043908228:AAGBfm19OZ2uvk2g_ev6ffIC03BRSiTYQw&html=)
V Werner, L Maingault, ML Potet - 2020 Workshop on Fault Detection and Tolerance …, 2020<br />Page 1. An End-to-End Approach for Multi-Fault Attack Vulnerability Assessment Vincent<br />Werner ∗† , Laurent Maingault ∗ , Marie-Laure Potet † ∗ Univ. Grenoble Alpes, CEA,<br />LETI, DSYS, CESTI, F-38000 Grenoble, [first.last@cea.fr](mailto:first.last@cea.fr) † Univ …<br />

<a name="iMLF9"></a>
### **[PDF]** [PANIC: A High-Performance Programmable NIC for Multi-tenant Networks](http://scholar.google.com/scholar_url?url=http://wisr.cs.wisc.edu/papers/osdi20-panic.pdf&hl=en&sa=X&d=9264397289969390602&ei=CBuXX4vbFcS9yQTZ0LeIDA&scisig=AAGBfm1yaWASEh0N5MdLhdyiBgwVHV4t-Q&nossl=1&oi=scholaralrt&hist=AQxAsJ0AAAAJ:3812021249043908228:AAGBfm19OZ2uvk2g_ev6ffIC03BRSiTYQw&html=)
J Lin, K Patel, BE Stephens, A Sivaraman, A Akella<br />… using an Alpha Data ADM-PCIE-9V3 Programmable NIC [12] to evaluate<br />the behavior of different hardware IP cores that could be used as on-NIC<br />accelerators, and the Rocket Chip Generator [14] to perform cycle-accurate …<br />

<a name="uA1Cm"></a>
### **[PDF]** [Multilevel Simulation Methodology for FMECA Study Applied to a Complex Cyber-Physical System](http://scholar.google.com/scholar_url?url=https://www.mdpi.com/2079-9292/9/10/1736/pdf&hl=en&sa=X&d=1225134161975883812&ei=CBuXX4vbFcS9yQTZ0LeIDA&scisig=AAGBfm1Ke9CWRpOc9ASP3wDTK67HXkZBWg&nossl=1&oi=scholaralrt&hist=AQxAsJ0AAAAJ:3812021249043908228:AAGBfm19OZ2uvk2g_ev6ffIC03BRSiTYQw&html=)
D Piumatti, J Sini, S Borlo, M Sonza Reorda, R Bojoi… - Electronics, 2020<br />Complex systems are composed of numerous interconnected subsystems,<br />each designed to perform specific functions. The different subsystems use many<br />technological items that work together, as for the case of cyber-physical systems …<br />

<a name="2e303ea0"></a>
### **[PDF]** [The nanoPU: Redesigning the CPU-Network Interface to Minimize RPC Tail Latency](http://scholar.google.com/scholar_url?url=https://arxiv.org/pdf/2010.12114&hl=en&sa=X&d=7310373728838262988&ei=iz2cX8OgM5HeyQTX3IyoDg&scisig=AAGBfm2kcrDcBw4IoQ_m5P7egu3wS3AnUw&nossl=1&oi=scholaralrt&hist=AQxAsJ0AAAAJ:3812021249043908228:AAGBfm19OZ2uvk2g_ev6ffIC03BRSiTYQw&html=)
S Ibanez, A Mallery, S Arslan, T Jepsen, M Shahbaz… - arXiv preprint arXiv …, 2020<br />… Our prototype nanoPU is based on a modified **RISC**-**V** CPU; we evaluate its<br />performance using cycle-accurate simulations of 324 cores on AWS FPGAs, including<br />real applications (MICA and chain replication). 1. Introduction …<br />
<br />

<a name="tz2xP"></a>
### [Real-Time Event Handling and Preemptive Hardware RTOS Scheduling on a Custom CPU Implementation](http://scholar.google.com/scholar_url?url=https://ieeexplore.ieee.org/abstract/document/9240083/&hl=en&sa=X&d=6873535474240876173&ei=iz2cX8OgM5HeyQTX3IyoDg&scisig=AAGBfm3CwJZRlRg95JBG0MqZEd1h4Qs3GQ&nossl=1&oi=scholaralrt&hist=AQxAsJ0AAAAJ:3812021249043908228:AAGBfm19OZ2uvk2g_ev6ffIC03BRSiTYQw&html=)
I Zagan, VG Găitan - Canadian Journal of Electrical and Computer …, 2020<br />… 2018, doi: 10.3390/ electronics7090205. [5] A. Kurth, P. Vogel, A. Capotondi,<br />A. Marongiu, and L. Benini, “HERO: Heterogeneous embedded research<br />platform for exploring **RISC**-**V** manycore accelerators on FPGA,” in Proc … Archit …<br />

<a name="N375e"></a>
### **[PDF]** [Performance Analysis of Scientific Computing Workloads on Trusted Execution Environments](http://scholar.google.com/scholar_url?url=https://arxiv.org/pdf/2010.13216&hl=en&sa=X&d=5997965912334546374&ei=iz2cX8OgM5HeyQTX3IyoDg&scisig=AAGBfm3UOdK4DS9Xdnsw4fB1naKTBugvqA&nossl=1&oi=scholaralrt&hist=AQxAsJ0AAAAJ:3812021249043908228:AAGBfm19OZ2uvk2g_ev6ffIC03BRSiTYQw&html=)
A Akram, A Giannakou, V Akella, J Lowe-Power… - arXiv preprint arXiv …, 2020<br />… Examples include Intel's SGX (Software Guard Extension) [2], ARM's<br />TrustZone [3], AMD's SEV (Secure Encrypted Virtualization) [4], and emerging<br />research platforms like **RISC**-**V's** Keystone [5]. In this paper, we investigate …<br />
<br />

<a name="fznWz"></a>
### [HOST-TRUSTED MODULE IN DATA STORAGE DEVICE](http://scholar.google.com/scholar_url?url=https://www.freepatentsonline.com/y2020/0310661.html&hl=en&sa=X&d=17614042107891346000&ei=iz2cX8OgM5HeyQTX3IyoDg&scisig=AAGBfm0RNpM6imaBWITcibFviDtcf1SHgg&nossl=1&oi=scholaralrt&hist=AQxAsJ0AAAAJ:3812021249043908228:AAGBfm19OZ2uvk2g_ev6ffIC03BRSiTYQw&html=)
S Benisty, A Marcu, JG Hahn - US Patent App. 16/368,092, 2020<br />… In some implementations, host-trusted module 114 can include a Reduced Instruction<br />Set Computer (RISC), such as a **RISC**-**V** processor or an Advanced RISC Machines<br />(ARM) processor, or a type of open source processor …
<a name="tayvd"></a>
### **[PDF]** [High-Throughput Elliptic Curve Cryptography using AVX2 Vector Instructions](http://scholar.google.com/scholar_url?url=https://sac2020.ca/files/preproceedings/27-HighThroughput.pdf&hl=en&sa=X&d=184042540208374571&ei=iz2cX8OgM5HeyQTX3IyoDg&scisig=AAGBfm3beNboNpZ5akRLuNFYhJYq4sQo7Q&nossl=1&oi=scholaralrt&hist=AQxAsJ0AAAAJ:3812021249043908228:AAGBfm19OZ2uvk2g_ev6ffIC03BRSiTYQw&html=)
H Cheng, J Großschädl, J Tian, PB Rønne, PYA Ryan<br />… Consequently, the bitlength of SIMD registers increased from 64 to 512<br />over a period of just 20 years, and one can expect further extensions in<br />the future. For example, as recently reported in [10], the **RISC**-**V** architecture …<br />

<a name="54b37108"></a>
### **[PDF]** [ExPAN (N) D: Exploring Posits for Efficient Artificial Neural Network Design in FPGA-based Systems](http://scholar.google.com/scholar_url?url=https://arxiv.org/pdf/2010.12869&hl=en&sa=X&d=4448180349030422635&ei=iz2cX8OgM5HeyQTX3IyoDg&scisig=AAGBfm39ycwAX0R9gGPFtEni6vH_2aJBUA&nossl=1&oi=scholaralrt&hist=AQxAsJ0AAAAJ:3812021249043908228:AAGBfm19OZ2uvk2g_ev6ffIC03BRSiTYQw&html=)
S Nambi, S Ullah, A Lohana, SS Sahoo, F Merchant… - arXiv preprint arXiv …, 2020<br />… It proposes improvements in Posit data extrac- tion methodology and<br />a pipelined architecture for Posit (N=32, ES=6). Posit arithmetic has also<br />been integrated into Clarinet [21] which is a **RISC**-**V** ISA based processor …<br />

<a name="9b2287b3"></a>
### **[PDF]** [hXDP: Efficient Software Packet Processing on FPGA NICs](http://scholar.google.com/scholar_url?url=https://arxiv.org/pdf/2010.14145&hl=en&sa=X&d=5049123661949070559&ei=iz2cX8OgM5HeyQTX3IyoDg&scisig=AAGBfm32x7f2KiYNTeqG5Gc62Ef0zTs7QQ&nossl=1&oi=scholaralrt&hist=AQxAsJ0AAAAJ:3812021249043908228:AAGBfm19OZ2uvk2g_ev6ffIC03BRSiTYQw&html=)
MS Brunella, G Belocchi, M Bonola, S Pontarelli… - arXiv preprint arXiv …, 2020<br />… statements. 3Intel Xeon E5-1630v3, Linux kernel v.5.6.4. soft-core designs, such as<br />those based on **RISC**-**V** [22, 25]. 2.4 hXDP Overview hXDP addresses the outlined<br />challenge by taking a software- hardware co-design approach …<br />


---


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

