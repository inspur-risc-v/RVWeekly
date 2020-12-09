# RV与芯片评论.20201121.第17期


<br />本期概要

- Edge AI Summit结束
- Mythic发布模拟矩阵处理器，直接在闪存中计算矩阵
- 乐鑫发布ESP32-C3
- BBC联合SiFive联合发布神秘博士主题少儿编程套件
- 资本风云：嘉楠科技大涨，晶心科技直接涨停
- RV51: 在8051上运行RV31I程序
- 印度学者谈中国半导体


<br />


---

<a name="cgX2z"></a>
# 重点聚焦


<a name="0eQ7M"></a>
### AI边缘峰会

<br />

<a name="u1qhF"></a>
### 相关周报

- ![image.png](https://cdn.nlark.com/yuque/0/2020/png/1541992/1599307696075-3f44fb1b-f362-4130-a254-b3e4fb6cebac.png#align=left&display=inline&height=24&margin=%5Bobject%20Object%5D&name=image.png&originHeight=84&originWidth=89&size=7408&status=done&style=none&width=25)[semi engineering](https://semiengineering.com/) Week In Review: ：
   - Blog Review："[Blog Review: Nov. 18 ](https://semiengineering.com/blog-review-nov-18-2/
)(From semiengineering.com 2020.11.21)"
      - Mobile holograms; auto ECU consolidation; NAND flash; IoT software security.
   - Design, Low Power："[Week In Review: Design, Low Power ](https://semiengineering.com/week-in-review-design-low-power-121/
)(From semiengineering.com 2020.11.21)"
      - Synopsys buys optical measurement company; PSS 2.0 draft; Arm-based supercomputer tops list.
   - Manufacturing, Test："[Week In Review: Manufacturing, Test ](https://semiengineering.com/week-in-review-manufacturing-test-123/
)(From semiengineering.com 2020.11.21)"
      - PDF buys Cimetrix; maskless litho; OSAT ranking; TSMC fab.
   - Auto, Security, Pervasive Computing："[Week In Review: Auto, Security, Pervasive Computing ](https://semiengineering.com/week-in-review-auto-security-pervasive-computing-42/
)(From semiengineering.com 2020.11.21)"
      - Pervasive computing in IC manufacturing; Synopsys security; Arm’s IoT commitment.
- ："[（第 134 期）：未来的游戏业比现在大100倍 ](https://www.yuque.com/ruanyf/weekly/issue-134
)(From www.yuque.com 2020.11.21)"
- "[Top 5 Data Center Stories of the Week: November 20, 2020 ](https://www.datacenterknowledge.com/uncategorized/top-5-data-center-stories-week-november-20-2020
)(From www.datacenterknowledge.com 2020.11.20)"
- [OSDT Weekly](https://github.com/hellogcc/osdt-weekly/tree/master/weekly)：
   - "[OSDT Weekly 2020-11-18 第072期 ](https://github.com/hellogcc/osdt-weekly/blob/master/weekly/2020-11-18.md
)(From github.com 2020.11.21)"
- [泰晓咨询](http://tinylab.org/)：
   - "[泰晓资讯·11月 / 第二期 / 2020 ](http://tinylab.org/tinylab-weekly-11-2nd-2020/
)(From tinylab.org 2020.11.21)"
- [PLCT开源进展](https://www.zhihu.com/column/plct-lab)：
   - "[PLCT开源进展·第13期·2020年11月16日 ](https://zhuanlan.zhihu.com/p/297749144
)(From zhuanlan.zhihu.com 2020.11.17)"
- [RT-Thread](https://my.oschina.net/u/4428324)：
   - "[【20201120期嵌入式AI周报】 M1808 AI 核心板搭载5G模、嵌入式视觉应用开发详解！ ](https://my.oschina.net/u/4428324/blog/4749911
)(From my.oschina.net 2020.11.27)"
   - "[RT-Thread10月社区简报 ](https://my.oschina.net/u/4428324/blog/4749929
)(From my.oschina.net 2020.11.27)"
- "[IC技术圈期刊 2020年第11期 ](https://mp.weixin.qq.com/s/2nn8uZfYEpqaCJiE_9XXlQ
)(From mp.weixin.qq.com 2020.11.21)"

---



<a name="nqDGS"></a>
# 技术动态

- "[华为方舟编译器新发布对 RISC-V 后端的支持 ](https://m.ithome.com/html/520787.htm
)(From m.ithome.com 2020.11.20)"        
   - 方舟编译器可以在RISC-V的QEMU模拟器以及真实硬件设备上成功运行CPU2017的C程序
   - 代码链接地址：[https://gitee.com/openarkcompiler-incubator/mapleall](https://gitee.com/openarkcompiler-incubator/mapleall)
- 
- 
- 
- 
- 
- 
- 
- 
- 
- 
- 


<br />

<a name="UQCtX"></a>
### Linux动态

- "[Bug#960837: opendht: Need -latomic on at least RISC-V architecture ](https://www.mail-archive.com/debian-bugs-dist@lists.debian.org/msg1773760.html
)(From www.mail-archive.com 2020.11.14)"
- "[Re: [PATCH 08/32] riscv: Fix kernel time_init() ](https://www.spinics.net/lists/linux-clk/msg53152.html
)(From www.spinics.net 2020.11.16)"
- "[[PATCH] RISC-V: fix barrier() use in ](https://www.mail-archive.com/linux-kernel@vger.kernel.org/msg2382393.html
)(From www.mail-archive.com 2020.11.16)"
- "[RE: [PATCH v15 10/17] RISC-V: KVM: Implement stage2 page table programming ](https://www.spinics.net/lists/kvm/msg228864.html
)(From www.spinics.net 2020.11.16)"
- "[[PATCH bpf-next 0/3] RISC-V selftest/bpf fixes ](https://www.spinics.net/lists/bpf/msg30215.html
)(From www.spinics.net 2020.11.17)"
- "[Re: [PATCH 1/2] RISC-V: Update l2 cache DT documentation to add support for SiFive FU740  ](https://lkml.org/lkml/2020/11/21/90
)(From lkml.org 2020.11.21)"
<a name="SYbmw"></a>
### 其他动态

- "[Re: [PATCH bpf-next v2 0/3] RISC-V selftest/bpf fixes ](https://www.spinics.net/lists/netdev/msg701720.html
)(From www.spinics.net 2020.11.21)"
- "[[Bug 1820686] Re: risc-v: 'c.unimp' instruction decoded as 'c.addi4spn fp, 0' ](https://www.mail-archive.com/qemu-devel@nongnu.org/msg761699.html
)(From www.mail-archive.com 2020.11.21)"
<a name="v2ah0"></a>
### 一周问答

- "[[求助] 【硕士毕业选题】基于 Risc-v的微处理器实现 or ADPLL两个方向?  ](http://bbs.eetop.cn/thread-887655-1-1.html
)(From bbs.eetop.cn 2020.11.16)"
- "[[μTVM] Deployment on GAP8 RISC-V platform ](https://discuss.tvm.apache.org/t/tvm-deployment-on-gap8-risc-v-platform/8475
)(From discuss.tvm.apache.org 2020.11.21)"
<a name="CC8oT"></a>
### 社区动态

- "["Unknown Error" while decompiling RISC-V binary #2466 ](https://github.com/NationalSecurityAgency/ghidra/issues/2466
)(From [NationalSecurityAgency](https://github.com/NationalSecurityAgency)/[ghidra](https://github.com/NationalSecurityAgency/ghidra) in github.com 2020.11.19)" 
- "[riscv: qemu needs SDK update to test memory protection #30012 ](https://github.com/zephyrproject-rtos/zephyr/issues/30012
)(From [zephyrproject-rtos](https://github.com/zephyrproject-rtos)/[zephyr](https://github.com/zephyrproject-rtos/zephyr) github.com 2020.11.19)"
- "[QEMU performance for U54-mc ](https://forums.sifive.com/t/qemu-performance-for-u54-mc/4210
)(From forums.sifive.com 2020.11.19)"
- "[RISC-V 能够发展起来吗，想看开源体系对抗苹果的闭源体系 ](https://www.v2ex.com/t/726805
)(From www.v2ex.com 2020.11.19)"

---

<a name="SM5cC"></a>
# 产业风云

- "[仅售83元，树莓派「最强敌手」要来了！背后竟是阿里平头哥 ](https://zhuanlan.zhihu.com/p/296391391
)(From zhuanlan.zhihu.com 2020.11.16)"
- "[晶心科衝RISC-V 盤中奔漲停 ](https://money.udn.com/money/story/5612/5018716
)(From money.udn.com 2020.11.16)"
   - 晶心科第3季仍处于亏损状态，每股净损0.69元，累计前三季每股净损1.99元，不过第4季有机会赚钱，10月业绩来到历史次高水准，累计前10月合并营收为3.79亿元，年减8.2％，明年力拼转为获利局面。
- 
   - 上周我们谈到了这个EDA厂商的优秀操作，本周更新了一些网友评论和相关新闻
- "[西部数据扩展闪存产品组合，助力ZB时代以数据为中心的存储架构不断发展  ](https://www.sohu.com/a/432581678_104421
)(From www.sohu.com 2020.11.18)"
   - 西部数据公司在2020 美国闪存峰会（Flash Memory Summit）上首发三款全新解决方案
   - 西部数据在本次峰会上会就NVMe、NVMe-oF™、分区命名空间（ZNS）、分区存储、RISC-V、计算存储等主题发表演讲
- 2020.11.16 Maxim的 MAX 78000 AI 加速芯片获得了 the Best Sensors 2020 Award，AI组最佳创意奖
   - [https://www.fierceelectronics.com/sensors/maxim-wins-best-sensors-2020-award-for-max-78000-accelerator-chip](https://www.fierceelectronics.com/sensors/maxim-wins-best-sensors-2020-award-for-max-78000-accelerator-chip)
- "[区块链第一股嘉楠科技的AI芯片生意 ](https://tech.sina.com.cn/roll/2020-11-19/doc-iiznezxs2666201.shtml
)(From tech.sina.com.cn 2020.11.19)"
   - “相较于发达国家，我国的开源基础核心技术仍然缺失，产品市场份额仍然不高，产业价值链仍然以中低端为主，生态关键环节仍存在挑战。”近日，在开源软件供应链2020峰会上，中国科学院软件研究所（以下简称软件所）所长赵琛如是说。
   - [https://canaan-creative.com/1024.html](https://canaan-creative.com/1024.html)
   - 外网报道："[Canaan Inc. to Report Third Quarter 2020 Financial Results on November 30, 2020 ](https://finance.yahoo.com/news/canaan-inc-report-third-quarter-110000960.html
)(From finance.yahoo.com 2020.11.21)"
- "[兆易创新：MCU涨价叠加ARM架构爆发，利好不断助推业绩提升 ](http://biz.jrj.com.cn/2020/11/19000031317359.shtml
)(From biz.jrj.com.cn 2020.11.19)"
- "[边缘智能计算框架Tengine成功打通RISC-V芯片架构的AI部署与推理AI模型量化，或撼动AI推理格局 ](https://blog.csdn.net/weixin_43476455/article/details/109840291
)(From blog.csdn.net 2020.11.20)"
- "[嘉楠科技的第二个芯片战场 ](https://mp.weixin.qq.com/s/AA6SSOJhj5WVe4o_a2GNvA
)(From mp.weixin.qq.com 2020.11.19)"
   - 端侧AI芯片是新战场
   - 新架构是下一个目标
- "[乐鑫发布低成本 Wi-Fi + Bluetooth LE 5.0 combo 芯片 ESP32-C3 ](https://mp.weixin.qq.com/s/0jSYGe7iq5rundNMqqIOlQ
)(From mp.weixin.qq.com 2020.11.20)"
   - 乐鑫推出全新低成本 IoT 芯片 ESP32-C3，成本对标 ESP8266，可 pin to pin 兼容 ESP8266 模组；继承 ESP32 成熟软件架构，搭载 RISC-V 处理器。
   - 



<a name="PO7vP"></a>
### 评论文集

- 
- "[张楠赓：下一个十年 是“后移动互联网时代” ](https://finance.sina.com.cn/hy/hyjz/2020-11-16/doc-iiznctke1715072.shtml
)(From finance.sina.com.cn 2020.11.16)"
   - 第二十二届中国国际高新技术成果交易会，嘉楠科技董事长兼首席执行官张楠赓出席并演讲
   - 现在的数据增长是指数型的，为了真正解决这个问题，还是要去做一些真正革新性的计算架构
- "[抓住软件供应链 构建开源新生态 ](http://news.sciencenet.cn/htmlnews/2020/11/448779.shtm
)(From news.sciencenet.cn 2020.11.18)"
- "[中国芯片产业如何缩短与国外技术的差距 ](https://ee.ofweek.com/2020-11/ART-8500-2801-30470201.html
)(From ee.ofweek.com 2020.11.20)"
- "[x86与ARM的王者对决，RISC-V能否迎来自己的春天 ](http://www.semiinsights.com/s/electronic_components/23/41026.shtml
)(From www.semiinsights.com 2020.11.20)"
- "[RISC-V 有望在两年内走向数据中心？ ](https://www.chainnews.com/articles/170080052248.htm
)(From www.chainnews.com 2020.11.20)"
- "["华为方舟编译器新发布对 RISC-V 后端的支持 (From m.ithome.com 2020.11.21)" ]()(From  2020.11.21)"




---



<a name="tAplU"></a>
# 其他动态


<a name="ywwj0"></a>
### RKen：基于SiFive的HiFive PC开发板和RISC-V的嵌入式系统内核
<a name="kBCn8"></a>
### 项目推荐

- [cyrozap](https://github.com/cyrozap)/[rv51](https://github.com/cyrozap/rv51)：能在8051上运行RV32I程序的仿真器
- [jjyr](https://github.com/jjyr)/[jonesforth_riscv](https://github.com/jjyr/jonesforth_riscv)：在RISC-V上部署Jones Forth
   - Forth是一门编程语言：基于堆栈的程序设计语言Forth
   - jonesforth：是Jones给forth语言写的一个编译器，也是一个教程：[http://rwmj.wordpress.com/2010/08/07/jonesforth-git-repository/](http://rwmj.wordpress.com/2010/08/07/jonesforth-git-repository/)
   - 这个github项目将支持joneforth在risc-v上运行
- [maker-in-china](https://github.com/maker-in-china)/[learning-riscv](https://github.com/maker-in-china/learning-riscv)：从头实现一个RISCV core， 用于自己学习RISCV CPU和FPGA 知识
   - 这位朋友开了个头就放弃了，挂在这里鼓励一下
   - "[learning-RISCV-01 建立初始开发环境 ](https://makerinchina.cn/learning-riscv-01-%e5%bb%ba%e7%ab%8b%e5%88%9d%e5%a7%8b%e5%bc%80%e5%8f%91%e7%8e%af%e5%a2%83/
)(From makerinchina.cn 2020.09.25)"
- "[SAVVY-V, an open source RISC-V board ](https://blog.adafruit.com/2020/11/17/savvy-v-an-open-source-risc-v-board-riscv-opensource-crowdsupply-riscv_savvy/
)(From blog.adafruit.com 2020.11.21)"
<a name="HYzWV"></a>
## 博文推荐

- "[[RISCV]为RISC-V移植FreeRTOS系列之二 -- main.c和FreeRTOSConfig.h ](https://codeleading.com/article/96854946323/
)(From codeleading.com 2020.11.19)"
- "[[RISCV]为RISC-V移植FreeRTOS系列之四 -- 中断与trap handler ](https://blog.csdn.net/wangyijieonline/article/details/109726839
)(From blog.csdn.net 2020.11.16)"
- "[RISC-V上跑RT-Thread——Funpack第二期精彩分享之一 ](https://mp.weixin.qq.com/s/4O8p7ZB_h1jxPUJ8x24nNA
)(From mp.weixin.qq.com 2020.11.17)"
- "[[MCU应用开发] 【RISC-V MCU CH32V103测评】Part3：跑酷类小游戏Demo ](https://bbs.21ic.com/icview-3047188-1-1.html
)(From bbs.21ic.com 2020.11.16)"
- "[5.2 RISC-V vs x86 ](https://zhuanlan.zhihu.com/p/295438346
)(From zhuanlan.zhihu.com 2020.11.19)"
- "[risc-v相关的网站和资源汇总 ](https://my.oschina.net/u/2963604/blog/4725245
)(From my.oschina.net 2020.11.19)"
- "[RISC-V IDE(RISCV IDE) MounRiver Stuido_V1.30代码烧录功能详解 ](https://blog.csdn.net/qq_36353650/article/details/109805309
)(From blog.csdn.net 2020.11.19)"
- "[【RISC-V MCU CH32V103测评】+自制MP3播放器 ](https://bbs.21ic.com/icview-3048364-1-1.html
)(From bbs.21ic.com 2020.11.21)"
- "[【RISC-V MCU CH32V103测评】彩色OLED屏显示驱动 ](https://bbs.21ic.com/icview-3049082-1-1.html
)(From bbs.21ic.com 2020.11.20)"
- "[第一个 RISC-V 上的“Android 最小系统” ](https://zhuanlan.zhihu.com/p/302870095
)(From zhuanlan.zhihu.com 2020.11.20)"
   - 在 RISC-V 的 QEMU 上启动一个 Android 的 “最小系统”

---

<a name="5NYql"></a>
# 一周论文


<a name="IxYla"></a>
### [Fault resilience analysis of a **RISC**-**V **microprocessor design through a dedicated UVM environment](https://ieeexplore.ieee.org/abstract/document/9250871/)
M Barbirotta, A Mastrandrea, F Menichelli, F Vigli… - 2020 IEEE International …, 2020<br />Fault tolerance is a key requirement in several application domains of embedded<br />processors cores. In a wide variety of applications, however, a full protection against<br />faults occurring in any bit of the core may be oversized, and it has been …<br />**
<a name="FHTwU"></a>
### **[PDF]** [Sustainable Computing: Informatics and Systems](https://www.researchgate.net/profile/William_Fornaciari/publication/345724095_Automatic_identification_and_hardware_implementation_of_a_resource-constrained_power_model_for_embedded_systems/links/5fac01ad299bf18c5b6513e0/Automatic-identification-and-hardware-implementation-of-a-resource-constrained-power-model-for-embedded-systems.pdf)
[PDF] [Sustainable Computing: Informatics and Systems](https://www.researchgate.net/profile/William_Fornaciari/publication/345721677_An_FPU_design_template_to_optimize_the_accuracy-efficiency-area_trade-off/links/5fac01d64585150781080f0d/An-FPU-design-template-to-optimize-the-accuracy-efficiency-area-trade-off.pdf) D Zoni, A Galimberti, W Fornaciari<br />L Cremona, W Fornaciari, D Zoni<br />… target computing platforms. Our methodology has been validated against 8<br />accelerators generated through a High-Level-Synthesis flow and by considering a<br />more complex **RISC**-**V** embedded computing platform. Depending on …
<a name="F55Ea"></a>
### **[PDF]** [33rd IEEE International Symposium on Defect and Fault Tolerance in VLSI and Nanotechnology Systems (DFT 2020) Technical Program October 19-21, 2020](https://ieeexplore.ieee.org/iel7/9250742/9250725/09250759.pdf)
L Benini, C Bolchini, L Cassano, A Miele, M Biasielli… - 2020<br />… 15.50-16.40: Session #7 - AI in space ❖ (L) On board satellite telemetry forecasting<br />with RNN on **RISC**-**V** based multi core processor Danilo Cappellone, Gianluca Furano,<br />Stefano Di Mascio, Alessandra Menicucci and Marco Ottavi …
<a name="o9iTq"></a>
### [A Pipelined Multi-Level Fault Injector for Deep Neural Networks](https://ieeexplore.ieee.org/abstract/document/9250866/)
A Ruospo, A Balaara, A Bosio, E Sanchez - … on Defect and Fault Tolerance in VLSI …, 2020<br />… The Deep Neural Network running on [14] is a CNN used for image classifica- tion. The<br />CNN application code is written in C and exploits the PULP-NN open-source library [15],<br />a multicore computing library allowing inferences on **RISC**-**V** Based PULP Cluster …<br />

<a name="YP4om"></a>
### [SHA2 and SHA-3 accelerator design in a 7nm technology within the European Processor Initiative](https://www.sciencedirect.com/science/article/pii/S0141933120305986)
P Nannipieri, M Bertolucci, L Baldanzi, L Crocetti… - Microprocessors and …, 2020<br />… Entirely European processor Intellectual Proprieties (IPs) relays on an ARM64<br />processor unit array, beside heterogeneous tile for embedded FPGA,<br />**RISC**-**V** 64 co-processors, Massively Parallel Processor Array (MPPA) …<br />

<a name="vyWoV"></a>
### [AI in space: applications examples and challenges](https://ieeexplore.ieee.org/abstract/document/9250908/)
G Furano, A Tavoularis, M Rovatti - 2020 IEEE International Symposium on Defect …, 2020<br />… Even the most computational intensive AI models (eg deep learning) have now versions<br />that allow trained models to be run on smartphones (“on the edge”). Index Terms—Deep<br />Neural Networks, **RISC**-**V**, Space Systems, Artificial Intelligence …
<a name="XnG51"></a>
### **

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

