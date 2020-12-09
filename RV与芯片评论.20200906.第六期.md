# RV与芯片评论.20200906.第六期


<br />本周开了一个好大的会[RISC-V Global Forum 2020](https://www.yuque.com/riscv/rvnews/20200906#JOQIQ)，然而上周的还没整理完呢。<br />这周看到不少关于LPC2020的讨论，比如[平头哥又露了一把脸](https://www.yuque.com/riscv/rvnews/20200906#Wmf5j)，比如[Arnd Bermann对2030年cpu的大胆预言](https://www.yuque.com/riscv/rvnews/drauau)，说起来还有外国网友认为[未来的开源CPU只能靠中国了](https://www.yuque.com/riscv/rvnews/20200906#yqhXi)。但是这个情况下，RISC-V倒是面临了IC验证的问题，这周各方大佬都有在讨论，为此我专门列了个[专题](https://www.yuque.com/riscv/rvnews/20200906#zaGi9)。另外本周比较热点的就是[Imagination的网课了](https://www.yuque.com/riscv/rvnews/20200906#0yxjS)。但总的来说，RISC-V是富有朝气的。<br />


---

<a name="zaGi9"></a>
# 重点聚焦
<a name="JOQIQ"></a>
### ![image.png](https://cdn.nlark.com/yuque/0/2020/png/1541992/1597454185685-6bf1e301-2210-4181-98de-f14be9d37dea.png#align=left&display=inline&height=24&margin=%5Bobject%20Object%5D&name=image.png&originHeight=340&originWidth=339&size=12802&status=done&style=none&width=24)RISC-V Global Forum 2020
本周3号， RISC-V全球论坛开了十多个小时，有趣的东西不少，但是没来得及整理。小标题整理在这里：

"[Some RISC-V high performance implementations presented at RISC-V Global Forum by European Processor Initiative, NSITEXE, OpenBLAS, and SemiDynamics ](http://primeurmagazine.com/weekly/AE-PR-10-20-38.html
)(From primeurmagazine.com 2020.09.14)"
<a name="E5hMG"></a>
### RISC-V Online Bootcamp将于9月18日举行
David Patterson和Mark Himelstein会在线上参会<br />"[RISC-V Online Bootcamp  ](https://mp.weixin.qq.com/s/aTEohnXbnjK2j6d2lNJmHg
)(From mp.weixin.qq.com 2020.08.31)"<br />关于：

<a name="D1ZaI"></a>
### 相关周报
PLCT: "[PLCT开源进展·第08期·2020年09月01日 ](https://zhuanlan.zhihu.com/p/212382464
)(From [软件所PLCT实验室](https://www.zhihu.com/column/plct-lab) zhuanlan.zhihu.com 2020.09.01)"<br />![image.png](https://cdn.nlark.com/yuque/0/2020/png/1541992/1599307696075-3f44fb1b-f362-4130-a254-b3e4fb6cebac.png#align=left&display=inline&height=24&margin=%5Bobject%20Object%5D&name=image.png&originHeight=84&originWidth=89&size=7408&status=done&style=none&width=25)"[Week In Review: Design, Low Power ](https://semiengineering.com/week-in-review-design-low-power-110/
)(From semiengineering.com 2020.09.04)"


---

<a name="yiUtc"></a>
# 技术动态


<a name="AfKEh"></a>
### ![](https://cdn.nlark.com/yuque/0/2020/png/1541992/1599121661338-36aa0d46-82bc-4118-9028-b9fb86b0b69b.png#align=left&display=inline&height=24&margin=%5Bobject%20Object%5D&originHeight=224&originWidth=566&size=0&status=done&style=none&width=61)研讨会：RISC-V & SoC Architecture Exploration for AI & ML Many-core Compute Arrays

<br />第十讲9月17开始<br />"[RISC-V CON 第十讲报名中：RISC-V Vector Programming with C Intrinsic  ](https://mp.weixin.qq.com/s/oBoDy4chVMc0ir_NlWeKwQ
)(From mp.weixin.qq.com 2020.09.03)"

<a name="rGqGZ"></a>
### MounRiver Studio: 面向RISC-V的MCU IDE

<br />

<a name="6xGIl"></a>
### ![image.png](https://cdn.nlark.com/yuque/0/2020/png/1541992/1599967305643-0cd6feb3-a325-4ff3-9ae4-b1c0b5dd5770.png#align=left&display=inline&height=24&margin=%5Bobject%20Object%5D&name=image.png&originHeight=73&originWidth=112&size=12390&status=done&style=none&width=37)沁恒微电子推出CH32V103开发板
<a name="tZgRA"></a>
# 技术动态：验证和EDA专项
<a name="I7i2N"></a>
### ![image.png](https://cdn.nlark.com/yuque/0/2020/png/1541992/1597454185685-6bf1e301-2210-4181-98de-f14be9d37dea.png#align=left&display=inline&height=24&margin=%5Bobject%20Object%5D&name=image.png&originHeight=340&originWidth=339&size=12802&status=done&style=none&width=24)RV国际博客：OpenHW 在RISC-V验证平台中做的工作
简单介绍了OpenHW的CORE-V verification test bench 及其UVM验证环境的搭建和结构<br />
<br />"[OpenHW open source CORE-V processor IP: a RISC-V story that leads with verification ](https://riscv.org/2020/08/openhw-open-source-core-v-processor-ip-a-risc-v-story-that-leads-with-verification/
)(By [Kevin McDermott](https://riscv.org/author/kevinm/)，From riscv.org 2020.08.31)"<br />

<a name="ODTS7"></a>
### 开源硬件需要开源验证方法吗?
CPU的验证必须是充分的且彻底的，本文主要讲了开源EDA工具的发展困难<br />

<a name="aMlwT"></a>
### CPU验证工作中挑战


<a name="vOtcm"></a>
### Synopsys: HAPS®-80作为高性能软件开发和系统验证平台


<a name="o0lqb"></a>
### 包云岗& DeepTech: 历时5年打造开源芯片生态的一块拼图——SERVE平台
同时本科生造芯依然在持续发酵<br />"[5位本科生回应4个月“造芯”毕业质疑，这届后浪有多牛？ ](https://ee.ofweek.com/2020-09/ART-8320315-8120-30456826.html
)(From ee.ofweek.com 2020.09.05)"<br />"[5名本科生四个月造出芯片竟然是真的！  ](https://www.sohu.com/a/416728957_239259
)(From www.sohu.com 2020.09.05)"


---

<a name="TuxuW"></a>
# 一周论文
<a name="egsxX"></a>
### Building a Modern TRNG: An Entropy Source Interface for RISC-V
"[Building a Modern TRNG: An Entropy Source Interface for RISC-V ](https://www.semanticscholar.org/paper/Building-a-Modern-TRNG%3A-An-Entropy-Source-Interface-Saarinen-Newell/2ea013981a186ee518dde588d7913b62be0a743a
)(From www.semanticscholar.org 2020.09.05)"<br />

<a name="0Abj2"></a>
### ![image.png](https://cdn.nlark.com/yuque/0/2020/png/1541992/1596875184550-25106f3b-2ab2-4656-aac4-7452ab8134da.png#align=left&display=inline&height=24&margin=%5Bobject%20Object%5D&name=image.png&originHeight=340&originWidth=364&size=121128&status=done&style=none&width=26)Raven: A 28nm RISC-V vector processor with integrated switched-capacitor DC-DC converters and adaptive clocking
"[Raven: A 28nm RISC-V vector processor with integrated switched-capacitor DC-DC converters and adaptive clocking ](https://ieeexplore.ieee.org/document/7477469
)(From ieeexplore.ieee.org 2020.09.05)"

<a name="DQMyu"></a>
### Investigation of the RISC-V
为什么处理器指令集架构真的很重要？为什么选择RISC-V，为什么比其他更好？RISC-V为世界各地的开发人员带来了哪些机遇，它有哪些类似物？<br />Proceedings of ISP RAS, 2020, Volume 32, Issue 2, Pages 81–98 (Mi tisp500)<br />"[Investigation of the RISC-V ](http://www.mathnet.ru/php/archive.phtml?wshow=paper&jrnid=tisp&paperid=500&option_lang=eng
)(From www.mathnet.ru 2020.09.05)"

<a name="HapyY"></a>
### ![image.png](https://cdn.nlark.com/yuque/0/2020/png/1541992/1596875184550-25106f3b-2ab2-4656-aac4-7452ab8134da.png#align=left&display=inline&height=24&margin=%5Bobject%20Object%5D&name=image.png&originHeight=340&originWidth=364&size=121128&status=done&style=none&width=26)Architecture, Chip, and Package Codesign Flow for Interposer-Based 2.5-D Chiplet Integration Enabling Heterogeneous IP Reuse
"[Architecture, Chip, and Package Codesign Flow for Interposer-Based 2.5-D Chiplet Integration Enabling Heterogeneous IP Reuse ](https://ieeexplore.ieee.org/abstract/document/9174651
)(From ieeexplore.ieee.org 2020.09.05)"

<a name="IfwUB"></a>
### ![image.png](https://cdn.nlark.com/yuque/0/2020/png/1541992/1596875184550-25106f3b-2ab2-4656-aac4-7452ab8134da.png#align=left&display=inline&height=24&margin=%5Bobject%20Object%5D&name=image.png&originHeight=340&originWidth=364&size=121128&status=done&style=none&width=26)A Cryo-CMOS Digital Cell Library for Quantum Computing Applications
做了个低温COMS库，用RSIC-V做实验在4.2开尔文下运行。<br />"[A Cryo-CMOS Digital Cell Library for Quantum Computing Applications ](https://ieeexplore.ieee.org/abstract/document/9170592
)(From ieeexplore.ieee.org 2020.09.05)"

---

<a name="O3dNl"></a>
# 行业动态
<br />
<a name="wzoSG"></a>
### SiFive: 为巴塞罗那超算中心开发加速器


<a name="MYRAw"></a>
### ![image.jpeg](https://cdn.nlark.com/yuque/0/2020/jpeg/1541992/1599309097776-1ca2f789-f2fc-4f80-b419-06576f0b30bf.jpeg#align=left&display=inline&height=24&margin=%5Bobject%20Object%5D&name=image.jpeg&originHeight=159&originWidth=317&size=6141&status=done&style=none&width=48)行业观察: 芯片巨头Arm阵地战
贸易战 + 实体名单 + ARM中国事件 + RISC-V + 英伟达, 混合影响下ARM的纠结和RISC-V的机遇.<br />"[芯片巨头Arm阵地战 ](https://finance.sina.com.cn/roll/2020-09-05/doc-iivhvpwy4969120.shtml
)(By 万佳丽 From 中国经营报 finance.sina.com.cn 2020.09.05)"<br />最近ARM又被英伟达买，又被RISC-V背刺，还又出新处理器的，很有话题度<br />"[Home>Arm Arm Announces Cortex-R82: First 64-bit Real Time Processor ](https://www.anandtech.com/show/16056/arm-announces-cortexr82-first-64bit-real-time-processor
)(From www.anandtech.com 2020.09.03)"

<a name="Wmf5j"></a>
### ![image.png](https://cdn.nlark.com/yuque/0/2020/png/1541992/1596877896147-cb2a2928-e379-45d3-8120-c5914c80187a.png#align=left&display=inline&height=24&margin=%5Bobject%20Object%5D&name=image.png&originHeight=40&originWidth=44&size=2204&status=done&style=none&width=26)玄铁910依然受到关注
"[Alibaba Xuantie 910: a new 16-core server RISC-V processor ](https://tekdeeps.com/alibaba-xuantie-910-a-new-16-core-server-risc-v-processor/
)(From tekdeeps.com 2020.08.31)"<br />"[ALIBABA SPEAKS MORE ON IT’S XT910 RISC-V CORE CLAIMED TO BE FASTER THAN AN ARM CORTEX-A73](https://www.electronics-lab.com/alibaba-speaks-more-on-its-xt910-risc-v-core-claimed-to-be-faster-than-an-arm-cortex-a73/)(From www.electronics-lab.com 2020.09.02)"<br />尤其是平头哥在LPC2020上又露了一次脸： <br />
<br />

<a name="gdEUf"></a>
### 树莓派vsPicoRio依然在继续
[https://marijuanapy.com/raspi-competitor-with-risc-v-rios-picorio-in-development/](https://marijuanapy.com/raspi-competitor-with-risc-v-rios-picorio-in-development/)<br />"[PicoRio Linux RISC-V SBC is an Open Source Alternative to Raspberry Pi Board ](https://www.cnx-software.com/2020/09/04/picorio-linux-risc-v-sbc-is-an-open-source-alternative-to-raspberry-pi-board/
)(From www.cnx-software.com 2020.09.04)"<br />"[PicoRio dev board PC with a RISC-V chip will be a low-cost, open source Raspberry Pi alternative ](https://liliputing.com/2020/09/picorio-dev-board-pc-with-a-risc-v-chip-will-be-a-low-cost-open-source-raspberry-pi-alternative.html
)(From liliputing.com 2020.09.04)"

<a name="yqhXi"></a>
### ![](https://cdn.nlark.com/yuque/0/2020/svg/1541992/1599303640390-1a9d7916-fb30-4e64-9598-03c69c4f85b2.svg#align=left&display=inline&height=24&margin=%5Bobject%20Object%5D&originHeight=45&originWidth=205&size=0&status=done&style=none&width=109)有网友让Purism用RISC-V生产笔记本电脑，引发的一系列讨论


<a name="4cA96"></a>
### 资本动态：半导体企业一个月融资12亿
"[8月融资额或超12亿元 多家企业今年已获两轮融资  ](https://www.sohu.com/a/416668274_166680
)(From www.sohu.com 2020.09.13)"


---

<a name="h5NKy"></a>
# 其他
<a name="edX6V"></a>
### 开发板：HiFive1 Rev B
"[HiFive1 Rev B开发板和RISC-V介绍  ](https://mp.weixin.qq.com/s/lXKq_ijfY9X_al5Xk5-3WQ
)(From mp.weixin.qq.com 2020.09.04)"
<a name="8tWKZ"></a>
### 开发板：PolarFire SoC Icicle Kit：带双核RV64的FPGA开发板
"[PolarFire SoC Icicle Kit – Low Cost, Low Power FPGA Development Board with Quad Core 64-bit RISC-V Microprocessor Subsystem ](https://circuitdigest.com/news/polarfire-soc-icicle-kit-low-cost-low-power-fpga-development-board-with-quad-core-64-bit-risc-v-microprocessor-subsystem
)(From circuitdigest.com 2020.09.04)"

<a name="rJd9B"></a>
### 开发板：Seeed Studio Sipeed Longan Nano：超级小
![](https://cdn.nlark.com/yuque/0/2020/jpeg/1541992/1599307452512-1e70cf93-dc54-4172-85af-871ecab3b663.jpeg#align=left&display=inline&height=113&margin=%5Bobject%20Object%5D&originHeight=400&originWidth=400&size=0&status=done&style=none&width=113)<br />"[Seeed Studio Sipeed Longan Nano - RISC-V GD32VF103CBT6 Development Board ](https://www.ubuy.mu/en/catalog/product/view/id/19617703/s/dp-seeed-studio-sipeed-maixduino-for-risc-v-ai-iot
)(From www.ubuy.mu 2020.09.05)"

<a name="0yxjS"></a>
### Imagination新课程：RVfpga：理解计算机体系结构


<a name="WRxUt"></a>
### 评论文章：RISC-V, 中国，晶圆厂和新基建
作者任务RV只能对IOT和定制加速领域有影响，而在高速，高性能，大数据方面不会有影响。另外芯片制造业和EDA两个方面显得愈加重要。<br />"[RISC-V, China, Nightingales ](https://interconnected.blog/riscv-china-nightingales/
)(By [Kevin Xu](https://interconnected.blog/author/kevin/)，From interconnected.blog 2020.07.02)"

<a name="8zuLO"></a>
### 广播访谈：RISC-V CTO on Open Source Chips and Use Cases
听Mark Himelstein讲RISC-V的故事<br />"[RISC-V CTO on Open Source Chips and Use Cases ](https://orionx.net/2020/08/risc-v-cto-on-open-source-chips-and-use-cases/
)(From orionx.net 2020.09.05)"
<a name="cvNNj"></a>
### 博文：将GDB接入仿真的蜂鸟E203系统需要几步？ 
"[将GDB接入仿真的蜂鸟E203系统需要几步？  ](https://mp.weixin.qq.com/s/YYCH-6O5QESVZ3u35zVYJA
)(From EECSer  [IC思维实验室]() 2020.08.31)"<br />相关文章

- "[浅谈RISC-V的DEBUG系统及其仿真  ](https://mp.weixin.qq.com/s?__biz=MzI3MjkzNzEwMg==&mid=2247483663&idx=1&sn=8d21640a0d1d304678b123c18639869d&chksm=eb2bb8eedc5c31f855806af4aeab8bbee33d76d49b37929970e9ebaee19f3cf87e88f3b7b336&scene=21#wechat_redirect
)(From EECSer  [IC思维实验室]() 2020.04.13)"
- "[简评几款开源RISC-V处理器  ](https://mp.weixin.qq.com/s?__biz=MzI3MjkzNzEwMg==&mid=2247483695&idx=1&sn=0562cd2c775bb987a28a92dd3213ac9b&chksm=eb2bb8cedc5c31d823ff64da52b86e86b1788230a43189f024f6b587f76999249ab54ab53a5c&scene=21#wechat_redirect
)(From EECSer  [IC思维实验室]() 2020.04.22)"
