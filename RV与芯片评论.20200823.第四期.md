# RV与芯片评论.20200823.第四期

本期概述：

1. 好多好多的会议：这周刚开完了一个（[Hotchips](#CzTP6)），下周马上开另一个([ISPASS2020](#qvNhc))，然后还有一个（[RISC-V Global Forum](#IjH6s)）开始注册，我们才刚刚整理了两个会议的内容（[CRVS2020 & CCF DAC](#pHDRB)），结果PLCT又要开[技术交流会](#pZbQK)。
1. SiFive瞄准芯片定制和IP业务成立[OpenFive](#Xm8SE)，把自己的[RVVintrinsic加到了rv工具链](#0QJ9x)里，与交换机公司[Innovium](#Xm8SE)达成合作，最后[StarFive也成为RV国际的高级会员](#pXwQF)。
1. RV界也越来越受资本和国家的重视，例如[印度想把RV当作国芯对待](#q0X4D)，[各路公司也陆续加入RV的怀](#3GTHa)抱，就是不知道[老黄要是真的买了ARM](#slItq)，英伟达在RV上做的这么多投入准备怎么办。




---

<a name="Lk9UQ"></a>
# 会议动态
<a name="CzTP6"></a>
### Hotchips32
本周刚开完，主题是大。不仅有晶圆级2.6万亿的AI芯片Cerebras的二代WSE，还有Benini搞得大动作，4096核的RV架构。另外平头哥也在会议上宣传了一波玄铁910<br />详情请见：

- "[史上最大芯片新一代产品出炉！晶体管数达2.6万亿个 ](https://www.sensorexpert.com.cn/article/14863.html
)(From www.sensorexpert.com.cn 2020.08.21)"
- [平头哥：玄铁910支持V0.7扩展，coremark跑出7.1分](#Xcck7)
- [瑞士理工：4096核心的RISC-V架构](#qcWlC)



<a name="IjH6s"></a>
### RISC-V Global Forum
8月19号开始注册，会议在 9月3日下午3点开始<br />如果不是会员单位，可以申请Scholarship Program ( [https://www.surveymonkey.com/r/RISCVScholarship](https://www.surveymonkey.com/r/RISCVScholarship) )<br />
<br />

<a name="qvNhc"></a>
### ISPASS-2020：2020 IEEE International Symposium on Performance Analysis of Systems and Software
会议时间：August 23-26, 2020 注册已于本周五截止<br />[https://www.ispass.org/ispass2020/](https://www.ispass.org/ispass2020/)<br />23号8点会有 Secure RISC-V Architecture Design的Work Shop，会有这些主题<br />   Secure cores and multicores<br />   ISA extensions for Security<br />   Software and hardware obfuscation Techniques<br />   Secure, efficient, and lightweight hardware implementations<br />   Hardware security solutions for machine learning<br />   Secure design for emerging applications: IoT, robotics, wearable computing, etc.<br />   Architectural designs and hardware security solutions for HPC, Data Centers and cloud computing<br />   Hardware virtualization and isolation for security<br />   Hardware-Software co-design solutions for graph analytics<br />   Post-quantum cryptosystem designs<br />   Software and core authentication<br />   Secure execution environment<br />   Secure root of trust bios<br />   Memory subsystem organization to secure data accesses<br />   Network-on-Chip (NoC) security feature to process and compute isolation.<br />
<br />

<a name="pHDRB"></a>
### CRVS2020 & CCF DAC
我们整理了两个会议中关于的RV的主要报告，，主要包括以下内容：

- DMR：一款RISC-V架构的乱序超标量通用处理器核
- 面向100G网络应用的RISC-V CPU设计
- RV16 An Ultra-Low-Cost Embedded RISC-V Processor Core
- NutShell-本科生设计的可运行Linux的RISC-V芯片
- 面向RISC-V的关键系统软件及生态
- 开源处理器敏捷软硬件协同验证基础平台实现
- RISC-V Enclave的发展与机遇
- 基于RISC-V的SoC FPGA芯片互联架构方案
- 支持一致性缓存的Spike仿真器
- RISC-V Vector 及定制指令 gem5 实践
- 芯来科技产品介绍



<a name="mNrwf"></a>
### ![image.png](https://cdn.nlark.com/yuque/0/2020/png/1541992/1598622521888-3b7019bf-22ee-4f77-9e3e-ad0e32e63442.png#align=left&display=inline&height=24&margin=%5Bobject%20Object%5D&name=image.png&originHeight=38&originWidth=148&size=4015&status=done&style=none&width=93)[COSCUP 開源人年會](https://www.youtube.com/channel/UCU8s-nDqbsKnitUNaVJ2Xvg)2020的视频也出来了
"[Experience on porting HIGHMEM and KASAN to RISC-V Linux ](https://coscup.org/2020/zh-TW/agenda/WDZBBJ
)(From coscup.org 2020.08.02)"

- YouTube：[https://www.youtube.com/watch?v=2Fqwr9B9Kq8&feature=emb_title](https://www.youtube.com/watch?v=2Fqwr9B9Kq8&feature=emb_title)


<br />"[FOSS it all the way : FPGA tool, RISC-V and Linux ](https://coscup.org/2020/zh-TW/agenda/V3CLXW
)(From coscup.org 2020.08.02"

- YouTube：[https://www.youtube.com/watch?v=AtVHkxvkclQ](https://www.youtube.com/watch?v=AtVHkxvkclQ)



"[Past, Present and Future of RISC-V Open Source ISA -- Andes' Perspective ](https://coscup.org/2020/zh-TW/agenda/3JCDGS
)(From coscup.org 2020.08.28)"

- YouTube：[https://www.youtube.com/watch?v=65q8nlkoIZA](https://www.youtube.com/watch?v=65q8nlkoIZA)



<a name="pZbQK"></a>
### ![](https://cdn.nlark.com/yuque/0/2020/jpeg/1541992/1596870782099-fb1b8215-7e9e-4f4c-8352-3277b732b5a7.jpeg#align=left&display=inline&height=24&margin=%5Bobject%20Object%5D&originHeight=284&originWidth=428&size=0&status=done&style=none&width=36)PCLT：CIRCT/FIRRTL/MLIR 技术交流会

- "[CIRCT/FIRRTL/MLIR 技术交流会，本周日上午十点开始  ](https://mp.weixin.qq.com/s/hTjZ7AqqFJZuOMLPRFynSg
)(From mp.weixin.qq.com 2020.08.21)"




---

<a name="n7ucD"></a>
# 技术动态
<a name="0QJ9x"></a>
### ![image.png](https://cdn.nlark.com/yuque/0/2020/png/1541992/1597396138436-1b77090f-6e3c-4a09-a67c-af81f1da7d38.png#align=left&display=inline&height=27&margin=%5Bobject%20Object%5D&name=image.png&originHeight=289&originWidth=305&size=46486&status=done&style=none&width=28)SiFive 把自己的RVV intrinsic开源并集成到了riscv-gun-toolchain里

<br />


<a name="Xcck7"></a>
### ![image.png](https://cdn.nlark.com/yuque/0/2020/png/1541992/1596877896147-cb2a2928-e379-45d3-8120-c5914c80187a.png#align=left&display=inline&height=24&margin=%5Bobject%20Object%5D&name=image.png&originHeight=40&originWidth=44&size=2204&status=done&style=none&width=26)平头哥：玄铁910支持V0.7扩展，coremark跑出7.1分

<br />

<a name="qcWlC"></a>
### ![](https://cdn.nlark.com/yuque/0/2020/svg/1541992/1598087411825-decfaf09-052a-494f-b1eb-e8edd580adaa.svg#align=left&display=inline&height=24&margin=%5Bobject%20Object%5D&originHeight=85&originWidth=300&size=0&status=done&style=none&width=85)瑞士理工：4096核心的RISC-V架构




---

<a name="EdT9z"></a>
# 市场新闻
<a name="m8YdW"></a>
### ![image.png](https://cdn.nlark.com/yuque/0/2020/png/1541992/1597396138436-1b77090f-6e3c-4a09-a67c-af81f1da7d38.png#align=left&display=inline&height=27&margin=%5Bobject%20Object%5D&name=image.png&originHeight=289&originWidth=305&size=46486&status=done&style=none&width=28)OpenFive: SiFive有成为一家IP巨头的打算？
<a name="Xm8SE"></a>
### ![image.png](https://cdn.nlark.com/yuque/0/2020/png/1541992/1597396138436-1b77090f-6e3c-4a09-a67c-af81f1da7d38.png#align=left&display=inline&height=27&margin=%5Bobject%20Object%5D&name=image.png&originHeight=289&originWidth=305&size=46486&status=done&style=none&width=28)Innovation使用SiFive内核作为边缘数据中心交换机处理器
"[SiFive and Innovium Announce Collaboration to Accelerate Innovation in Data Center Networking ](https://www.sifive.com/press/sifive-and-innovium-announce-collaboration-to-accelerate
)(From www.sifive.com 2020.08.18)"

<a name="3GTHa"></a>
### ![](https://cdn.nlark.com/yuque/0/2020/jpeg/1541992/1596870782099-fb1b8215-7e9e-4f4c-8352-3277b732b5a7.jpeg#align=left&display=inline&height=24&margin=%5Bobject%20Object%5D&originHeight=284&originWidth=428&size=0&status=done&style=none&width=36)Imagination向RIOS实验室开放GPU IP技术 
相关新闻

- "[助力RISC-V生态发展，Imagination向RIOS实验室开放GPU IP技术 ](https://www.eet-china.com/news/202008191101.html
)(From www.eet-china.com 2020.08.19)"
- "[RIOS实验室与Imagination Technologies建立战略伙伴关系，共同助力RISC-V生态发展  ](https://mp.weixin.qq.com/s/jt50ahw2oizmucfoc-uFeA
)(From mp.weixin.qq.com 2020.08.19)"



<a name="TO0IX"></a>
### ![](https://cdn.nlark.com/yuque/0/2020/jpeg/1541992/1596870782099-fb1b8215-7e9e-4f4c-8352-3277b732b5a7.jpeg#align=left&display=inline&height=24&margin=%5Bobject%20Object%5D&originHeight=284&originWidth=428&size=0&status=done&style=none&width=36)芯原上市，市值740亿
2018年，芯原股份牵头成立中国RISC-V产业联盟（CRVIC），作为首任理事长单位，公司投资过芯来智融，芯原的戴伟民博士也是RISC-V领域的旗帜性人物。<br />相关新闻：

- "[芯片界的药明康德  ](https://mp.weixin.qq.com/s/vuh3nhaCuJ0miyes4sLNXA
)(From mp.weixin.qq.com 2020.08.19)"
- "[芯原股份科创板上市大涨，市值超740亿  ](https://mp.weixin.qq.com/s/Bnu_PL9f7cw_oYsFSGnGfg
)(From mp.weixin.qq.com 2020.08.21)"

<br />
<a name="slItq"></a>
### 市场小评：ARM在左，RISC-V在右，NVIDIA买了ARM会对RISC-V造成什么影响？
这个收购案的牵扯有不少，关心贸易战的，要担心买了ARM会不会继续对国内使用ARM架构的企业造成影响；关心ARM的，会担心ARM失去中立性，以至于苹果这样的公司会对ARM架构产生担忧。不过我没见到有太多关心RISC-V的，但这一点上也是有问题的，就是老黄在RV上投入了不少经精力，包括存控芯片都有替换成RV的方案，买了ARM看起来会和RV有所重叠，以至于有人猜疑老黄会不会吸干ARM再拥抱RV。不过最后这些都白猜了：老黄没打算买。<br />也许这就是RV比ARM好的地方，不会因为一家公司的动荡，对整个生态造成冲击。<br />相关阅读：

- "[英伟达的执着与Arm的摇摆  ](https://mp.weixin.qq.com/s/VrFXGQ-Dz8HYLWXmMxGV4w
)(From mp.weixin.qq.com 2020.08.21)"
- "[Arm前景动荡，RISC-V能否承此重任？  ](https://mp.weixin.qq.com/s/lREnpkGwWdXMEAhS29albA
)(From mp.weixin.qq.com 2020.08.21)"
- "[英伟达有望成首家市值5千亿美元半导体厂商  ](https://mp.weixin.qq.com/s/5TtXxED2rdiARJczv_MmBA
)(From mp.weixin.qq.com 2020.08.21)"
- "[黄仁勋：英伟达是Arm长期合作伙伴，但尚未提出收购计划 ](https://mp.weixin.qq.com/s/bjiZohAFUZXkVAoiFXAtBw)(From mp.weixin.qq.com 2020.08.22)"

<br />
<a name="q0X4D"></a>
### ![](https://cdn.nlark.com/yuque/0/2020/jpeg/1541992/1596870782099-fb1b8215-7e9e-4f4c-8352-3277b732b5a7.jpeg#align=left&display=inline&height=24&margin=%5Bobject%20Object%5D&originHeight=284&originWidth=428&size=0&status=done&style=none&width=36)印度大力发展RISC-V，谋求半导体崛起
"[印度大力发展RISC-V，谋求半导体崛起  ](https://mp.weixin.qq.com/s/MnECqm9jgJylRXgBgKFJQg
)(From mp.weixin.qq.com 2020.05.16)"<br />[India selects RISC-V for semiconductor self-sufficiency contest: Use these homegrown cores to build kit](https://www.theregister.com/2020/08/19/india_microprocessor_challenge_risc_v/) - [www.theregister.com](http://www.theregister.com)<br />


---

<a name="KQySS"></a>
# 其他
<a name="sY7gB"></a>
## RV国际
<a name="o19kd"></a>
### ![](https://cdn.nlark.com/yuque/0/2020/jpeg/1541992/1596870782099-fb1b8215-7e9e-4f4c-8352-3277b732b5a7.jpeg#align=left&display=inline&height=24&margin=%5Bobject%20Object%5D&originHeight=284&originWidth=428&size=0&status=done&style=none&width=36)RISC-V Training Partner Program
首批四家提供培训的单位中有大陆的 PLCT Lab 来提供中文的培训内容。<br />RISC-V Training Partners are focusing on RISC-V training in a professional setting. RISC-V International provides this Training Partner Program in order to extend the breadth and reach of RISC-V knowledge (disruptive technology), provide opportunities for a broader audience to teach and learn, and engage the community to achieve expertise in the critical areas needed for a healthy ecosystem while we share the message and benefits of open collaboration.<br />消息来源：PLCT Lab<br />相关新闻：

- [https://riscv.org/exchange/training-partner-program](https://riscv.org/exchange/training-partner-program)/
- [https://riscv.org/exchange/train](https://riscv.org/exchange/train)
- "[RISC-V Training Partners Bring professional learning to the worldwide community! ](https://riscv.org/2020/08/risc-v-training-partners-bring-professional-learning-to-the-worldwide-community/
)(From riscv.org 2020.0817)"



<a name="pXwQF"></a>
### ![image.png](https://cdn.nlark.com/yuque/0/2020/png/1541992/1596875681420-60eb79ae-38b1-49f6-9c68-8fbbedd35ca2.png#align=left&display=inline&height=24&margin=%5Bobject%20Object%5D&name=image.png&originHeight=74&originWidth=73&size=10748&status=done&style=none&width=24)![](https://cdn.nlark.com/yuque/0/2020/jpeg/1541992/1596870782099-fb1b8215-7e9e-4f4c-8352-3277b732b5a7.jpeg#align=left&display=inline&height=24&margin=%5Bobject%20Object%5D&originHeight=284&originWidth=428&size=0&status=done&style=none&width=36)StarFive: 成为RV国际高级会员
"[赛昉科技加入RISC-V International Association高级会员，开启生态合作新纪元  ](https://mp.weixin.qq.com/s/XT5Vy9MIF21ctFoQaXjBQw
)(From mp.weixin.qq.com 2020.08.21)"

<a name="HUXAj"></a>
## 科普，博文和课程推荐
<a name="8S0fG"></a>
### ![](https://cdn.nlark.com/yuque/0/2020/jpeg/1541992/1596870782099-fb1b8215-7e9e-4f4c-8352-3277b732b5a7.jpeg#align=left&display=inline&height=24&margin=%5Bobject%20Object%5D&originHeight=284&originWidth=428&size=0&status=done&style=none&width=36)IC思维实验室：对RISC-V specification和implementation中的一些问题及思考（三）
"[对RISC-V specification和implementation中的一些问题及思考（三）  ](https://mp.weixin.qq.com/s/wUeQc4EfG8qaiv70CJ_p9w
)

<a name="AU16t"></a>
### ![image.png](https://cdn.nlark.com/yuque/0/2020/png/1541992/1598879296979-bd0fefe0-a5a6-451e-bf4d-cb1d0bc5e60f.png#align=left&display=inline&height=24&margin=%5Bobject%20Object%5D&name=image.png&originHeight=61&originWidth=62&size=966&status=done&style=none&width=24)使用Openocd烧录RISC-V
"[RISCV Openocd 烧录过程 ](https://zhuanlan.zhihu.com/p/192353607
)(From zhuanlan.zhihu.com 2020.08.31)"
<a name="D7xHm"></a>
### ![image.png](https://cdn.nlark.com/yuque/0/2020/png/1541992/1598622498648-da50e43d-1add-41c9-98d6-ac1bdb694ad2.png#align=left&display=inline&height=24&margin=%5Bobject%20Object%5D&name=image.png&originHeight=24&originWidth=31&size=486&status=done&style=none&width=31)Port luajit to RISC-V Motivation, first steps and perspectives
[http://mirroronet.pl/pub/mirrors/video.fosdem.org/2020/K.3.401/riscv_luajit.webm](http://mirroronet.pl/pub/mirrors/video.fosdem.org/2020/K.3.401/riscv_luajit.webm)<br />

<a name="krknR"></a>
### ![image.png](https://cdn.nlark.com/yuque/0/2020/png/1541992/1598622499848-bf8f482b-210a-48d9-b58b-25c077095867.png#align=left&display=inline&height=24&margin=%5Bobject%20Object%5D&name=image.png&originHeight=24&originWidth=31&size=486&status=done&style=none&width=31)Tool setup to learn RISC-V instructions(Module C, Part 1)
"[Tool setup to learn RISC-V instructions(Module C, Part 1) ](https://www.youtube.com/watch?v=qa-kaMXBCHA
)<br />(From www.youtube.com 2020.08.28)"
<a name="g38XS"></a>
## 事件日历

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
<br />本文来自
<a name="zKP0r"></a>
#### [RISC-V和芯片动态简报](https://www.yuque.com/riscv/rvnews)
已关注

- <br />
