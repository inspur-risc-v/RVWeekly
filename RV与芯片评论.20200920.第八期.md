# RV与芯片评论.20200920.第八期


<br />本周的大事件就是英伟达收购ARM的确切消息了，从国际到国内，从Intel到RISC-V，所有芯片相关领域都受到了波及。当然SiFive也借此机会频频动作，从前不久接受高通等芯片公司的融资以来，SiFive一直很活跃，这周更是借机宣传了自己的新RISC-V架构，以及想要做PC市场的决心，甚至聘任高通副总裁为CEO。


---

<a name="CUXq4"></a>
# 重点聚焦
<a name="3yqDo"></a>
### 9月15-25日，嵌入式视觉峰会正在召开中
[https://embeddedvisionsummit.com/](https://embeddedvisionsummit.com/)<br />
<a name="ni1Ap"></a>
### 2020年阿里巴巴云栖大会召开
[https://yunqi.aliyun.com/2020/](https://yunqi.aliyun.com/2020/live)
<a name="nKse6"></a>
### 2020 Inclusion外滩大会将于9月24日召开
做芯片也要时刻关注市场，这次的普惠大会由蚂蚁集团主持，有包括国际货币基金组织总裁在内的许多大佬参加。其中AIoT，计算安全，智能计算等很多议题值得关注。<br />时间：2020.09.24 - 2020.09.25<br />内容: 1场主论坛、40场分论坛<br />主要话题: 数字普惠开放、金融科技创新、全球生态共建、商业价值变革、绿色和可持续发展<br />分论坛: 开放银行金融生态、科技驱动未来保险、智能计算峰会、共享智能、区块链峰会、绿色金融新时代<br />主页: "[ 2020·INCLUSION·外滩大会  ](https://www.inclusionconf.com/
)(From www.inclusionconf.com 2020.09.16)"

<a name="rh2tr"></a>
### Chisel 挑战赛
<a name="JiaJ2"></a>
### RIOS实验室： RISC-V Online Bootcamp成功召开
<br />
<br />

<a name="Vqxbq"></a>
### 相关周报

- "[OSDT Weekly 2020-09-16 第063期  ](https://mp.weixin.qq.com/s/bffioUOhaTVXIs3PQNyfFw
)(From mp.weixin.qq.com 2020.09.16)"
- "[PLCT开源进展·第09期·2020年09月16日 ](https://zhuanlan.zhihu.com/p/248987366
)(From zhuanlan.zhihu.com 2020.09.16)"
- "[嵌入式AI简报 2020-09-17: 苹果发布A14/华为芯片封锁生效/TNN发布v0.2.0/微软AI编译器nnfusion ](https://mp.weixin.qq.com/s?__biz=MjM5NDczOTA4NQ==&mid=2447885277&idx=1&sn=f63241cb0839911028f018da5a722a18&chksm=b290453f85e7cc297ebe029dcd40937eec79fb0e630feb6237d00bafc70662c95fc82fd0329f&mpshare=1&scene=1&srcid=0917QAJghL8KAsRJsuxQASBA&sharer_sharetime=1600325072663&sharer_shareid=db4eb9d3aef59de08fb5613959d70c4a&key=60bc1c903d603065100392ead0b83d939e8307388f4e6182184568e7fca7e35bb320b72ccd776880d1d4349a4a1abcf4e9da02bf9e7ae987e528bb1e46bb90503c66e9783c82c8383dbe904facc0c39297c887dcbf0a6e3a392d4fea4d4a83f021cd5b4c1ba70ddad1f8a9031827924d6f89e6fc0f8ee1639bf48405a89d400e&ascene=1&uin=MTUxMDgzOTA4MQ%3D%3D&devicetype=Windows+10+x64&version=62090538&lang=zh_CN&exportkey=ASg4VEQogcuu9Z1DhRlM5HM%3D&pass_ticket=geWXosIabaosTnVFSJ1LjUW9eio55PPbK3TFVoMnkWdgXGWPTqmP78WpEV%2FOgy4Y&wx_header=0
)(From mp.weixin.qq.com 2020.09.17)"
- "[【20200916期AI简报】AI开源工具、5TOPS的旭日3 AIoT芯片 ](https://mp.weixin.qq.com/s?__biz=MzIwMzA2NzI1Ng==&mid=2655162815&idx=2&sn=00fee9342b089aee437e5dd668d235c7&chksm=8d632ba8ba14a2bea7166420e99b7cd51238cbc7b769a8fe85ce17e6596d76197bf9cafad6b0&mpshare=1&scene=1&srcid=0917aZ5EJM636MLeXEh97atN&sharer_sharetime=1600326099100&sharer_shareid=db4eb9d3aef59de08fb5613959d70c4a&key=5ea26212a5cd1589836d8d4a203e8914471b1d26002f5d846cbaf99e1baa9bab2a5ae68650a57ca53f73ba36904190299d9d1d10d3bc009cb7e62c51ee55e773e3cfdcc84d573cebe689d0ff13d38997c5fbe50b58da57fa5c4bbadc9153d3c294ef93f7d582bc272c710e2af2bbbcb2f179035549276c702576352169862d60&ascene=1&uin=MTUxMDgzOTA4MQ%3D%3D&devicetype=Windows+10+x64&version=62090538&lang=zh_CN&exportkey=ASzFNqFqxdu%2B187ZRTwHGJs%3D&pass_ticket=geWXosIabaosTnVFSJ1LjUW9eio55PPbK3TFVoMnkWdgXGWPTqmP78WpEV%2FOgy4Y&wx_header=0
)(From [RTThread物联网操作系统]() 2020.09.16)"
- "[Linux Graphics 周刊（第 5 期） ](https://mp.weixin.qq.com/s?__biz=MzU0MjY2MTU0NQ==&mid=2247484018&idx=1&sn=7ab0307b66569280e2c056c292d2d7ae&chksm=fb160cb4cc6185a25b24a209f7d6af3e15b34c544158990f1ea71405828fc331ac37b90167c4&mpshare=1&scene=1&srcid=0917XUho9a1P3QVMGYveef6B&sharer_sharetime=1600325224873&sharer_shareid=db4eb9d3aef59de08fb5613959d70c4a&key=2af4ca460c7df26d3524f92988e60d7c4ee719863220c5407d1fb037193f62a45dd5a74c2b960a5048cca3012f7e2c3e7ad03b1b821852b6c7abd4d7347f5a1c24b57058dd9e8b70aa72ad26c648f100a7a8f07ae4f02d318d77288d771806c3f235778ea1858d716b3bdc526c4a1f53867a1b6c669231b15789106d919d9609&ascene=1&uin=MTUxMDgzOTA4MQ%3D%3D&devicetype=Windows+10+x64&version=62090538&lang=zh_CN&exportkey=AYQDdX6pO7%2FgL5V9aOmiCPw%3D&pass_ticket=geWXosIabaosTnVFSJ1LjUW9eio55PPbK3TFVoMnkWdgXGWPTqmP78WpEV%2FOgy4Y&wx_header=0
)(From mp.weixin.qq.com 2020.09.17)"
- "[IC技术圈期刊 2020年第09期 ](https://mp.weixin.qq.com/s?__biz=MzIyMjYxNzA4NQ==&mid=2247485673&idx=1&sn=2412409406231ddf32b14c879cbaaf31&chksm=e82b847bdf5c0d6d4de538ab4fad4b5dab96846a538ab1c91984a818ef395cc633e7d08ddbe3&mpshare=1&scene=1&srcid=0920vTAIRVZzVy6wn7gd1qNu&sharer_sharetime=1600587665352&sharer_shareid=db4eb9d3aef59de08fb5613959d70c4a&key=aabb5ee173354e5d62a85b3e87964e573caf21e305e05faf5d194f3104f1874506c212f38b5eb9bf09b2ebde65da11a5706223b07916e19bd7b47025518fcc419f1dbf5c175587755c118f43befdbfdae8cf3ce26f56d2a81e68ae5e584ff1e3d4c9d91eee95b78a14624ceda1b67dff154c6073c8273636ed64038f75e1e344&ascene=1&uin=MTUxMDgzOTA4MQ%3D%3D&devicetype=Windows+10+x64&version=62090538&lang=zh_CN&exportkey=AVZFd%2FrUswfURt4B8Rtt0nA%3D&pass_ticket=VbWIHJSH%2FZtrWCipDYSr8u%2FMxEGn5scuaqTaDQkEhiIOufd8meXD%2BttLvHBaZV79&wx_header=0
)(From mp.weixin.qq.com 2020.09.20)"
- "[泰晓资讯 : 2020 年 9 月 第 二 期 ](https://mp.weixin.qq.com/s?__biz=MzA5NDQzODQ3MQ==&mid=2648182842&idx=1&sn=4a636ebf6135d84bb6e7b2ad77dec7b8&chksm=88622512bf15ac044293417ed85f7e9cd7f8080749f0bd1cc80aa498c8dcc4bf1a861f589651&mpshare=1&scene=1&srcid=09178D8UMatAbJkOxpK2Sgwm&sharer_sharetime=1600326285938&sharer_shareid=db4eb9d3aef59de08fb5613959d70c4a&key=53e823c17d388498756dd044f59327c008957ccb8030cce67699ae160310dcd4fb3e4ce43f3a994e3bc9893c03bd7657f9f2bdcff4a5cd83ffced0aca6e84fdb79be905ca6d57c3ac52abed32819f2fee93b4f5d4535b9aacf8d911f918e1379a0a26eb829d93043307d259b17e903a9bcb340d053e19640686abc444d8a83f5&ascene=1&uin=MTUxMDgzOTA4MQ%3D%3D&devicetype=Windows+10+x64&version=62090538&lang=zh_CN&exportkey=Ac4tBD%2FYbDkopHbZ1h%2BggjQ%3D&pass_ticket=VbWIHJSH%2FZtrWCipDYSr8u%2FMxEGn5scuaqTaDQkEhiIOufd8meXD%2BttLvHBaZV79&wx_header=0
)(From mp.weixin.qq.com 2020.09.20)"
- "[Most Read articles – Nvidia & ARM, Risc-V, O-RAN ](https://www.electronicsweekly.com/blogs/electro-ramblings/latest-news/read-articles-nvidia-arm-risc-v-o-ran-2020-09/
)(From www.electronicsweekly.com 2020.09.21)"
- "[Week In Review: Design, Low Power ](https://semiengineering.com/week-in-review-design-low-power-112/
)(From semiengineering.com 2020.09.21)"
- "[Week In Review: Manufacturing, Test ](https://semiengineering.com/week-in-review-manufacturing-test-114/
)(From semiengineering.com 2020.09.21)"
- "[AMD：已获得对华为供货许可证；Nvidia收购Arm，RISC-V或迎来新机会|一周科技热评 ](https://mp.weixin.qq.com/s?__biz=MjM5NjIzMDkwMQ==&mid=2651648546&idx=1&sn=c3b3e843bfc52cc8bb25b021b526240f&chksm=bd1431b88a63b8ae5a19f52894aa3c88f7e4d2e7c6086d88992714c8b34902be6c5e45464bd4&mpshare=1&scene=1&srcid=0920dPobkNqiwZKTrpk7NqCz&sharer_sharetime=1600577370743&sharer_shareid=db4eb9d3aef59de08fb5613959d70c4a&key=5ea26212a5cd158967fd7617151fd9849f78c4e2f01c091cb184e8f3748daefdf76902d90de33f86d51a3b496cf9daa73a88f0925c1879cc47f560d47343616714edbe79bb6a0335d0c4f486225a8783950bd9f4af503624857a0a2c44be4b8185e5b886f6ec49ac975690c3b49bb8d14a842d06c01dd52e8699d2807bbe090e&ascene=1&uin=MTUxMDgzOTA4MQ%3D%3D&devicetype=Windows+10+x64&version=62090538&lang=zh_CN&exportkey=AWi5BfFlRk%2B5Rgn4keHnvRw%3D&pass_ticket=VbWIHJSH%2FZtrWCipDYSr8u%2FMxEGn5scuaqTaDQkEhiIOufd8meXD%2BttLvHBaZV79&wx_header=0
)(From mp.weixin.qq.com 2020.09.22)"
- "[RT-Thread8月份社区简报，快来看看代码、软件包、社区生态更新情况！ ](https://mp.weixin.qq.com/s?__biz=MzIwMzA2NzI1Ng==&mid=2655162873&idx=1&sn=e31f30a9c1f999ad4e95a2efaf8f48df&chksm=8d632beeba14a2f8156e44177214da48b42fd0f826c058c49274fc41c0eb76e287d224e18dc5&xtrack=1&scene=90&subscene=93&sessionid=1600431763&clicktime=1600431901&enterid=1600431901&ascene=1&devicetype=Windows+10+x64&version=62090538&nettype=WIFI&abtest_cookie=AAACAA%3D%3D&lang=zh_CN&exportkey=ASaXeFir3WI0G3akS2cIXro%3D&pass_ticket=VbWIHJSH%2FZtrWCipDYSr8u%2FMxEGn5scuaqTaDQkEhiIOufd8meXD%2BttLvHBaZV79&wx_header=0&key=aabb5ee173354e5db208750a26ad9adc0756bf0dc35d0d83301a5fcfe71ee1becf2dc2e39df9a92b1c4fddcc920e53c3d9cf3adcfbdf180524f29f3c336236724c04b513855c22d7d7356f9e199f2f141e8ed594306674a41166046cd294d48bedcab9ca8147eb7e9493f34bd57a4c95c4da331cd226588aa0dca21d6eadc93b&uin=MTUxMDgzOTA4MQ%3D%3D
)(From mp.weixin.qq.com 2020.09.22)"




---

<a name="vZgT2"></a>
# 技术动态
<a name="Xq4cV"></a>
### Imagination Technologies的RISC-V课程讨论
<a name="bGB0Y"></a>
### Libre-SOC使用OpenPower架构，放弃RISC-V


<a name="UFsRi"></a>
### 讨论：关于RISC-V的DMA和Cache Coherence问题
"[Cache coherence and DMA on RISC-V ](https://www.reddit.com/r/RISCV/comments/iu4z6a/cache_coherence_and_dma_on_riscv/
)(From www.reddit.com 2020.09.18)"<br />

<a name="NjHSk"></a>
### SiFive想做RISC-V PC
<a name="y1Xtl"></a>
### RISC-V CON第十讲：RISC-V Vector Programming with C Intrinsic 结束


<a name="3Fl5C"></a>
### 研讨会：UVM-based Verification of Custom Instructions with RISC-V Cores结束
<a name="rdiCv"></a>
### 设计基于RISC-V指令集架构的专用领域处理器
<a name="o1S5h"></a>
### 其他新闻

- "[芯来基础软件平台(Nuclei Software Platform)重磅升级 ](https://mp.weixin.qq.com/s?__biz=MzUxNDkyNzYxNA==&mid=2247485152&idx=1&sn=042bf3d5c6f9a3de12973b06bbd91a07&chksm=f9bf3871cec8b167c10bb92b3499c7f66a3dfa4cd99a4b4dad632d28749e023c8ca97f3cb639&mpshare=1&scene=1&srcid=0918pWJBcAClohxYwaodmHGv&sharer_sharetime=1600425483904&sharer_shareid=db4eb9d3aef59de08fb5613959d70c4a&key=aabb5ee173354e5d32673a2d489ca23ff261da48fdee0267321ff3c8be6a2107bef37bb4690ae8db0d6e4d6308e681956daf5db4269d9cd79e1b2a93b7011f7f5c77bc2681b1f47c5d311727964c0d16b56d1bfd68c92e1f61eb988cddbb11b9116715c01643b528aa3fa9438730db565fefffc42d7ccbc6f36818981ae59e1a&ascene=1&uin=MTUxMDgzOTA4MQ%3D%3D&devicetype=Windows+10+x64&version=62090538&lang=zh_CN&exportkey=ASFvypCeHtwQ7wnRDHoYXZg%3D&pass_ticket=VbWIHJSH%2FZtrWCipDYSr8u%2FMxEGn5scuaqTaDQkEhiIOufd8meXD%2BttLvHBaZV79&wx_header=0
)(From mp.weixin.qq.com 2020.09.18)"
- "[推动改变的RISC-V催化剂 ](https://mp.weixin.qq.com/s?__biz=MzU2Mjc1NDQ1MQ==&mid=2247484362&idx=1&sn=cca1efcd0164b7a0ded3e2a6b5a3367b&chksm=fc65e536cb126c20e1bb0d7ca08435e33dc1d005453d10295a4e97eafc9fb10f9f702d73ea81&mpshare=1&scene=1&srcid=0920AYIs5k9vTfOcODNLIHGu&sharer_sharetime=1600535608191&sharer_shareid=db4eb9d3aef59de08fb5613959d70c4a&key=aabb5ee173354e5d592e8d4ce12bed6cd802ef62e8e3dcad246a9e70b5571c00af06ac2f908bb127aeeb6201213eef68259cf45f00e56612da3978c0a133b805c52f3661aae8bd7833f5f25ec43f2e2c5d275d675a50875f48f4c7fd59236f9a04943683d10a00fef798f6c3889a1c8f3531d02578387073cdbe030cb0ed4ba2&ascene=1&uin=MTUxMDgzOTA4MQ%3D%3D&devicetype=Windows+10+x64&version=62090538&lang=zh_CN&exportkey=AeOCHkMx6icLA8XtRWRiCR4%3D&pass_ticket=VbWIHJSH%2FZtrWCipDYSr8u%2FMxEGn5scuaqTaDQkEhiIOufd8meXD%2BttLvHBaZV79&wx_header=0
)(From mp.weixin.qq.com 2020.09.18)"
- "[欢迎加入 OSDT Slack 和邮件列表，在微信群可能无法访问之前 ](https://mp.weixin.qq.com/s?__biz=MzIxNDUzNDEyOA==&mid=2247484829&idx=1&sn=bfac2bdfb3a80e7003030cd1ec3f9251&chksm=97a75702a0d0de1493e9fc2816b58c9941a1f5ee456f560841f65e9f87137526a87169ad0ccd&mpshare=1&scene=1&srcid=0920nRpBORWv8QQXySJ2knzO&sharer_sharetime=1600536064824&sharer_shareid=db4eb9d3aef59de08fb5613959d70c4a&key=c69caee2bdbd960c1fb425164d812f3e22ecde8258eb9192d13debecafcad53cca04626d1881430f15a7168da5988d1312ba8a953a9a17f4ecc4dfeb047b4d558f7e7ceaf86b662c3718a7eea54b9befb0e7b569a8a3ab0a0174f9543b5e7c3310ab4989dcb594c8529af2139ba0c3787da3eebda85756f882b62d6dc91d702a&ascene=1&uin=MTUxMDgzOTA4MQ%3D%3D&devicetype=Windows+10+x64&version=62090538&lang=zh_CN&exportkey=ATwk0OAuzk2sPtLX9eYp%2Bmk%3D&pass_ticket=VbWIHJSH%2FZtrWCipDYSr8u%2FMxEGn5scuaqTaDQkEhiIOufd8meXD%2BttLvHBaZV79&wx_header=0
)(From mp.weixin.qq.com 2020.09.18)"




---

<a name="GuFye"></a>
# 一周论文

<br />

<a name="WUS9r"></a>
### [A RISC-V ISA Compatible Processor IP](http://scholar.google.com/scholar_url?url=https://ieeexplore.ieee.org/abstract/document/9190558/&hl=en&sa=X&d=6508579246501927337&scisig=AAGBfm35T_z8a0ld645qV9Uznjr5yQq4qw&nossl=1&oi=scholaralrt&hist=AQxAsJ0AAAAJ:4202114184661953008:AAGBfm3D0OY4figMd-K5msYCl6aFfjtabQ&html=)
A Birari, P Birla, K Varghese, A Bharadwaj - … Symposium on VLSI Design and Test …, 2020 <br />A processor is the core component of an electronic system. In this work, we present a high-performance general-purpose processor system, based on open source **RISC**-<br />**V **instruction set architecture. Our processor has a 32-bit 5-stage pipeline core with …<br />

<a name="uqaCq"></a>
### [A Compiler Comparison in the **RISC**-**V **Ecosystem](http://scholar.google.com/scholar_url?url=https://ieeexplore.ieee.org/abstract/document/9191411/&hl=en&sa=X&d=14353337475249734167&scisig=AAGBfm12WEtCfBdxzPIJrM_3gpTVPkMvMA&nossl=1&oi=scholaralrt&hist=AQxAsJ0AAAAJ:4202114184661953008:AAGBfm3D0OY4figMd-K5msYCl6aFfjtabQ&html=)
M Poorhosseini, W Nebel, K Grüttner - 2020 International Conference on Omni-layer … <br />The GNU Compiler Collection (GCC) is the traditional compiler for most embedded systems, since it supports many different instruction set architectures (ISA) in its back-<br />end. GCC has also been the first compiler that supported the **RISC**-**V **ISA. Since a …<br />
<a name="43VTF"></a>
### **[PDF]** [Research on Formal Verification Method of **RISC**-**V **Microcontroller](http://scholar.google.com/scholar_url?url=https://pdf.hanspub.org/CSA20200600000_69315461.pdf&hl=en&sa=X&d=7299378005923615251&scisig=AAGBfm1H4rhBSfgd1JpvkZyL25LAiUsliA&nossl=1&oi=scholaralrt&hist=AQxAsJ0AAAAJ:4202114184661953008:AAGBfm3D0OY4figMd-K5msYCl6aFfjtabQ&html=)
Y Pan, Z Cheng<br />Embedded microcontrollers are widely deployed within power IoT system. It's vital to guarantee functional correctness of the embedded microcontroller, which acts as core component in self-developed IoT ground communication node of transmission …<br />

<a name="jMU15"></a>
### **[PDF]** [**RISC**-**V **Processor Core Customization and Verification for m-NLP Applications](http://scholar.google.com/scholar_url?url=https://www.duo.uio.no/bitstream/handle/10852/79111/23/thesis_rp.pdf&hl=en&sa=X&d=5188298181059552728&scisig=AAGBfm1bLDMVWu1NpE_5xoMCQfVvcbrXZQ&nossl=1&oi=scholaralrt&hist=AQxAsJ0AAAAJ:4202114184661953008:AAGBfm3D0OY4figMd-K5msYCl6aFfjtabQ&html=)
RAT Pedersen - 2020<br />This work experimented with using a custom instruction set extension for computing electron density from sensor data received from a multi-needle langmuir probe (m- NLP). Custom instructions were designed and implemented on a **RISC**-**V **processor …<br />

<a name="Chhry"></a>
### [HECTOR-V: A Heterogeneous CPU Architecture for a Secure **RISC**-**V **Execution Environment](http://scholar.google.com/scholar_url?url=https://arxiv.org/pdf/2009.05262&hl=en&sa=X&d=2216907089040315775&scisig=AAGBfm0fFjSHaLAhtqCcONSbzBYauZa3Jg&nossl=1&oi=scholaralrt&hist=AQxAsJ0AAAAJ:3812021249043908228:AAGBfm19OZ2uvk2g_ev6ffIC03BRSiTYQw&html=)
P Nasahl, R Schilling, M Werner, S Mangard - arXiv preprint arXiv:2009.05262, 2020 <br />To ensure secure and trustworthy execution of applications, vendors frequently embed trusted execution environments into their systems. Here, applications are protected from adversaries, including a malicious operating system. TEEs are usually …<br />

<a name="GsRrw"></a>
### [he gem5 Simulator: Version 20.0+: A new era for the open-source computer architecture simulator](http://scholar.google.com/scholar_url?url=https://par.nsf.gov/biblio/10191846&hl=en&sa=X&d=9124447756415638500&scisig=AAGBfm0SoaR9E7tg9P7IVXYgeclwhq6APQ&nossl=1&oi=scholaralrt&hist=AQxAsJ0AAAAJ:3812021249043908228:AAGBfm19OZ2uvk2g_ev6ffIC03BRSiTYQw&html=)
J Lowe-Power, A Mutaal - ArXivorg, 2020<br />
<br />

<a name="8Mola"></a>
### **[PDF]** [Circuitly: A visual and constructive framework for teaching digital circuits](http://scholar.google.com/scholar_url?url=https://www.ic.unicamp.br/~reltech/PFG/2020/PFG-20-04.pdf&hl=en&sa=X&d=5761896235558619607&scisig=AAGBfm04q3gq60C61FNHG6a3fKvZs7SUYA&nossl=1&oi=scholaralrt&hist=AQxAsJ0AAAAJ:3812021249043908228:AAGBfm19OZ2uvk2g_ev6ffIC03BRSiTYQw&html=)
L Castro, R Azevedo, R Técnico-IC-PFG… - 2020<br />… 6 Future work 6.1 Build a **RISC**-**V** processor using Circuitly As discussed along<br />the article, this work was inspired by Schocken and Nisan's “From Nand to Tetris”<br />constructive teaching approach. We intend to create a similar …<br />

<a name="mWOvy"></a>
### **[PDF]** [Memory-Latency-Accuracy Trade-offs for Continual Learning on a **RISC**-**V **Extreme-Edge Node](http://scholar.google.com/scholar_url?url=https://arxiv.org/pdf/2007.13631&hl=en&sa=X&d=4536370493006595496&scisig=AAGBfm12MQhoG-st_txkpGa5j8ps8BsNSA&nossl=1&oi=scholaralrt&hist=AQxAsJ0AAAAJ:4202114184661953008:AAGBfm3D0OY4figMd-K5msYCl6aFfjtabQ&html=)
L Ravaglia, M Rusci, A Capotondi, F Conti, L Pellegrini… - arXiv preprint arXiv …, 2020 AI-powered edge devices currently lack the ability to adapt their embedded inference models to the ever-changing environment. To tackle this issue, Continual Learning<br />(CL) strategies aim at incrementally improving the decision capabilities based on …<br />

<a name="tGWKB"></a>
### [REHAD: Using Low-Frequency Reconfigurable Hardware for Cache Side-Channel Attacks Detection](http://scholar.google.com/scholar_url?url=https://conferences.computer.org/eurosp/pdfs/EuroSPW2020-7k9FlVRX4z43j4uE2SeXU0/859700a703/859700a703.pdf&hl=en&sa=X&d=15304609960097734496&scisig=AAGBfm23QlDayN0CeTsZwsMeq1kWR2hJMA&nossl=1&oi=scholaralrt&hist=AQxAsJ0AAAAJ:3812021249043908228:AAGBfm19OZ2uvk2g_ev6ffIC03BRSiTYQw&html=)
Y Mao, V Migliore, V Nicomette<br />… REHAD has been integrated into the ORCA softcore **RISC**- **V** on a FPGA and two common cache side-channel attacks have been successfully detected. Index Terms—Reconfigurable architectures, intrusion detec- tion …<br />
<br />


---

<a name="yMVIb"></a>
# 产业动态


<a name="Se4a4"></a>
### N+A: 英伟达收购ARM, 对RISC-V造成的系列影响
<a name="Kw9bm"></a>
### RISC-V PC?
随着NVIDIA收购ARM和SiFive想要做个PC级芯片的新闻，人们也开始讨论RISC-V PC是什么样子的<br />
<br />大多数人认为，能跑Linux的RISCV板子顶多是个树莓派<br />"[If you say you want a RISC-V board that runs Linux, what do you mean? ](https://www.reddit.com/r/RISCV/comments/irwumi/if_you_say_you_want_a_riscv_board_that_runs_linux/
)(From www.reddit.com 2020.09.20)"<br />
<br />这里的调查，大多数人认为RISC-V PC的主频应该不低于1GHz<br />"[On a RISC-V Linux board, what is the minimum CPU speed to be useful to you? ](https://www.reddit.com/r/RISCV/comments/is8m2z/on_a_riscv_linux_board_what_is_the_minimum_cpu/
)(From www.reddit.com 2020.09.20)"

大多数人愿意给能运行Linux的RISC-V开发板花费100美元<br />"[How much would you be willing to pay in the next 12 months for a RISC-V Linux board? ](https://www.reddit.com/r/RISCV/comments/is8srx/how_much_would_you_be_willing_to_pay_in_the_next/
)(From www.reddit.com 2020.09.20)"<br />

<a name="xqv6k"></a>
### Sifive：感到机会来了
<a name="XYkyr"></a>
### SiFive：聘任原高通副总裁Patrick Little为CEO

<br />

<a name="jq63H"></a>
### 中科院招标RISC-V物理设计服务

<br />

<a name="6AIVb"></a>
### GigaDevice：提供ARM和RISC-V的MCU
ARM是GD32E5系列，使用ARM M33核心<br />RISC-V是GD32VF103系列，32bit的<br />"[GigaDevice Offers MCUs based on both RISC-V, Arm ](https://www.embedded-computing.com/home-page/gigadevice-offers-mcus-based-on-both-risc-v-arm
)(From www.embedded-computing.com 2020.09.15)"<br />"[兆易创新：GD32 MCU出货持续攀升，全面布局光通信市场 ](https://www.esmchina.com/news/7013.html
)(From www.esmchina.com 2020.09.21)"<br />

<a name="nKGjv"></a>
### Graham Lee：苹果将最终采用RISC-V


<a name="xqJsv"></a>
### PolarFire：Microchip的RISC-V SOC FPGA套件

<br />


---

<a name="fYhjB"></a>
# 其他动态


<a name="H5059"></a>
### 开发板：Precursor，长得像个手机的RV开发套件
据称软件所吴老师被CrowdSupply以出口管制理由取消订单了，想购买的同学可以去找他交流下。
<a name="4keqM"></a>
### 文章评论

- "[RISC-V: WHY THE ISA BATTLES AREN’T OVER YET ](https://hackaday.com/2019/11/12/risc-v-why-the-isa-battles-arent-over-yet/
)(By [Maya Posch](https://hackaday.com/author/mayaposch/) From hackaday.com 2019.12.12)"
- "[重要性堪比光刻机/EDA，IP核国产化现处于什么水平？ ](https://www.ednchina.com/news/202009161810.html
)(From www.ednchina.com 2020.09.21)"
- "[涉足芯片制造，触及核心架构，详解小米120亿“芯投资”版图 ](https://36kr.com/p/887163362896389
)(From 36kr.com 2020.09.21)"
- "[“新基建”需要什么样的创新国产IC？ ](https://www.eet-china.com/news/202009200107.html
)(From www.eet-china.com 2020.09.21)"



<a name="SF40x"></a>
### 问答时间
为什么RISC-V的PC递增是4而不是1或者2?

- "[Why Program Counter in RISC V should be added by 4 instead of adding 0 or 2 ](https://stackoverflow.com/questions/63904609/why-program-counter-in-risc-v-should-be-added-by-4-instead-of-adding-0-or-2
)(From stackoverflow.com 2020.09.21)"

这是个陷阱题：RISC-V的一次跳转要花多长时间?

- "[Risc-V: What is the timing of a conditional branch to the next instruction?  ](https://stackoverflow.com/questions/63964936/risc-v-what-is-the-timing-of-a-conditional-branch-to-the-next-instruction
)(From stackoverflow.com 2020.09.21)"



<a name="AKv19"></a>
### 博文推荐
<a name="mJ0mi"></a>
#### 用一段C代码编译的指令代码，来阐明RISC-V架构的简洁
非常适合初学者了解RISC-V指令<br />"[用一段C代码编译的指令代码，来阐明RISC-V架构的简洁 ](https://zhuanlan.zhihu.com/p/237357630
)(From zhuanlan.zhihu.com 2020.09.21)"
<a name="x7omW"></a>
#### <br />
<a name="jZayK"></a>
### 赛事新闻

- "[深入科创高地集纳“创芯”人才 “创业之芯”大赛武汉、南京、无锡、深圳等分站赛举行 ](https://t.cj.sina.com.cn/articles/view/1734252941/675e998d02000ygzb?from=tech
)(From t.cj.sina.com.cn 2020.09.14)"
- "[中关村软件园“创新之源”大赛启幕 ](http://it.people.com.cn/n1/2020/0916/c1009-31862982.html
)(From it.people.com.cn 2020.09.21)"
<a name="l7KCH"></a>
### 专栏推荐：Java on RISC-V 
让RISC-V生态可以用上工业级的Java应用，目前有三篇文章<br />"[Java on RISC-V ](https://zhuanlan.zhihu.com/c_1287750038518161408
)(From zhuanlan.zhihu.com 2020.09.21)"

- "[【Java on RISC-V】OpenJDK对于RISC-V的支持现状以及路线图 ](https://zhuanlan.zhihu.com/p/234721637
)(From zhuanlan.zhihu.com 2020.09.11)"
- "[【Java on RISC-V】Maxine-VM对于RISC-V的支持进展调研与搭建测试 ](https://zhuanlan.zhihu.com/p/234736963
)(From zhuanlan.zhihu.com 2020.09.11)"
- "[【Java on RISC-V】OpenJ9对于RISC-V的支持进展调研与搭建测试 ](https://zhuanlan.zhihu.com/p/245365529
)(From zhuanlan.zhihu.com 2020.09.15)"


<br />


---

RISC-V与芯片评论编辑部 - RISC-V和芯片动态周报<br />每周六发布<br />欢迎批评，指正，评论和加入<br />
<br />关于本刊: 

- [消息来源](https://www.yuque.com/riscv/rvnews/overview#vHVQ5)




| 微信公众号<br />![image.png](https://cdn.nlark.com/yuque/0/2020/png/1541992/1602320139392-1297e86a-ac06-4d76-a000-ad4307cd488c.png#align=left&display=inline&height=187&margin=%5Bobject%20Object%5D&name=image.png&originHeight=440&originWidth=465&size=225442&status=done&style=none&width=198) | Gitee

[https://gitee.com/inspur-risc-v/RVWeekly](https://gitee.com/inspur-risc-v/RVWeekly) | Github

[https://github.com/inspur-risc-v/RVWeekly](https://github.com/inspur-risc-v/RVWeekly) | 语雀

[https://www.yuque.com/riscv/rvnews](https://www.yuque.com/riscv/rvnews) |
| --- | --- | --- | --- |



