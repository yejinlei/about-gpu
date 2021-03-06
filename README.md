# about-gpu

## GPU显卡参数
![](data/deviceQueryDrv.PNG)

* CUDA Capability Major/Minor version number(计算能力)：2.1
  * GPU计算能力不仅仅代表计算的能力，同时它也代表硬件架构上的细微差异，本显卡属于Fermi架构SM2.1
  * Fermi架构介绍

	![](data/Fermi.PNG)
    * SM2.1内部结构，如图：

    ![](data/Fermi_SM21.PNG)
    ![](data/bandwidthTest.PNG)

    * 正式出现核的概念（core，之前都是使用sp），增加了双精度运算和完整32位整型运算的支持
    * 原子操作做了巨大改进
    * 增加了ECC内存校验
    * 多kernel函数并发执行
    * 共享存储可配置（16KB或48KB）
    * 双warp调度机制

## Nvidia产品及计算能力
- **Tesla Workstation Products**

产品|计算能力
-|-
Tesla K80|	3.7
Tesla K40|	3.5
Tesla K20|	3.5
Tesla C2075|	2.0
Tesla C2050/C2070|	2.0

- **Tesla Data Center Products**

产品|计算能力
-|-
Tesla P100|	6.0
Tesla P40|	6.1
Tesla P4|	6.1
Tesla M40|	5.2
Tesla M40|	5.2
Tesla K80|	3.7
Tesla K40|	3.5
Tesla K20|	3.5
Tesla K10|	3.0

- **Quadro Desktop Products**

产品|计算能力
-|-
Quadro P6000|	6.1
Quadro P5000|	6.1
Quadro M6000 24GB|	5.2
Quadro M6000|	5.2
Quadro K6000|	3.5
Quadro M5000|	5.2
Quadro K5200|	3.5
Quadro K5000|	3.0
Quadro M4000|	5.2
Quadro K4200|	3.0
Quadro K4000|	3.0
Quadro M2000|	5.2
Quadro K2200|	5.0
Quadro K2000|	3.0
Quadro K2000D|	3.0
Quadro K1200|	5.0
Quadro K620|	5.0
Quadro K600|	3.0
Quadro K420|	3.0
Quadro 410|	3.0
Quadro Plex 7000|	2.0

- **Quadro Mobile Products**

产品|计算能力
-|-
Quadro K6000M|	3.0
Quadro M5500M|	5.0
Quadro K5200M|	3.0
Quadro K5100M|	3.0
Quadro M5000M|	5.0
Quadro K500M|	3.0
Quadro K4200M|	3.0
Quadro K4100M|	3.0
Quadro M4000M|	5.0
Quadro K3100M|	3.0
Quadro M3000M|	5.0
Quadro K2200M|	5.0
Quadro K2100M|	3.0
Quadro M2000M|	5.0
Quadro K1100M|	3.0
Quadro M1000M|	5.0
Quadro K620M|	5.0
Quadro K610M|	3.5
Quadro M600M|	5.0
Quadro K510M|	3.5
Quadro M500M|	5.0

- **Desktop Products**

产品|计算能力
-|-
NVIDIA NVS 810|	5.0
NVIDIA NVS 510|	3.0
NVIDIA NVS 315|	2.1
NVIDIA NVS 310|	2.1

- **Mobile Products**

产品|计算能力
-|-
NVS 5400M|	2.1
NVS 5200M|	2.1
NVS 4200M|	2.1

- **GeForce Desktop Products**

产品|计算能力
-|-
NVIDIA TITAN X|	6.1
GeForce GTX 1080|	6.1
GeForce GTX 1070|	6.1
GeForce GTX 1060|	6.1
GeForce GTX TITAN X|	5.2
GeForce GTX TITAN Z|	3.5
GeForce GTX TITAN Black|	3.5
GeForce GTX TITAN|	3.5
GeForce GTX 980 Ti|	5.2
GeForce GTX 980|	5.2
GeForce GTX 970|	5.2
GeForce GTX 960|	5.2
GeForce GTX 950|	5.2
GeForce GTX 780 Ti|	3.5
GeForce GTX 780|	3.5
GeForce GTX 770|	3.0
GeForce GTX 760|	3.0
GeForce GTX 750 Ti|	5.0
GeForce GTX 750|	5.0
GeForce GTX 690|	3.0
GeForce GTX 680|	3.0
GeForce GTX 670|	3.0
GeForce GTX 660 Ti|	3.0
GeForce GTX 660|	3.0
GeForce GTX 650 Ti BOOST|	3.0
GeForce GTX 650 Ti|	3.0
GeForce GTX 650|	3.0
GeForce GTX 560 Ti|	2.1
GeForce GTX 550 Ti|	2.1
GeForce GTX 460|	2.1
GeForce GTS 450|	2.1
GeForce GTS 450*|	2.1
GeForce GTX 590|	2.0
GeForce GTX 580|	2.0
GeForce GTX 570|	2.0
GeForce GTX 480|	2.0
GeForce GTX 470|	2.0
GeForce GTX 465|	2.0
GeForce GT 740|	3.0
GeForce GT 730|	3.5
GeForce GT 730 DDR3,128bit|	2.1
GeForce GT 720|	3.5
GeForce GT 705*|	3.5
GeForce GT 640 (GDDR5)|	3.5
GeForce GT 640 (GDDR3)|	2.1
GeForce GT 630|	2.1
GeForce GT 620|	2.1
GeForce GT 610|	2.1
GeForce GT 520|	2.1
GeForce GT 440|	2.1
GeForce GT 440*|	2.1
GeForce GT 430|	2.1
GeForce GT 430*|	2.1

- **GeForce Notebook Products**

产品|计算能力
-|-
GeForce GTX 1080|	6.1
GeForce GTX 1070|	6.1
GeForce GTX 1060|	6.1
GeForce GTX 980|	5.2
GeForce GTX 980M|	5.2
GeForce GTX 970M|	5.2
GeForce GTX 965M|	5.2
GeForce GTX 960M|	5.0
GeForce GTX 950M|	5.0
GeForce 940M|	5.0
GeForce 930M|	5.0
GeForce 920M|	3.5
GeForce 910M|	5.2
GeForce GTX 880M|	3.0
GeForce GTX 870M|	3.0
GeForce GTX 860M|	3.0/5.0(**)
GeForce GTX 850M|	5.0
GeForce 840M|	5.0
GeForce 830M|	5.0
GeForce 820M|	2.1
GeForce 800M|	2.1
GeForce GTX 780M|	3.0
GeForce GTX 770M|	3.0
GeForce GTX 765M|	3.0
GeForce GTX 760M|	3.0
GeForce GTX 680MX|	3.0
GeForce GTX 680M|	3.0
GeForce GTX 675MX|	3.0
GeForce GTX 675M|	2.1
GeForce GTX 670MX|	3.0
GeForce GTX 670M|	2.1
GeForce GTX 660M|	3.0
GeForce GT 750M|	3.0
GeForce GT 650M|	3.0
GeForce GT 745M|	3.0
GeForce GT 645M|	3.0
GeForce GT 740M|	3.0
GeForce GT 730M|	3.0
GeForce GT 640M|	3.0
GeForce GT 640M LE|	3.0
GeForce GT 735M|	3.0
GeForce GT 635M|	2.1
GeForce GT 730M|	3.0
GeForce GT 630M|	2.1
GeForce GT 625M|	2.1
GeForce GT 720M|	2.1
GeForce GT 620M|	2.1
GeForce 710M|	2.1
GeForce 705M|	2.1
GeForce 610M|	2.1
GeForce GTX 580M|	2.1
GeForce GTX 570M|	2.1
GeForce GTX 560M|	2.1
GeForce GT 555M|	2.1
GeForce GT 550M|	2.1
GeForce GT 540M|	2.1
GeForce GT 525M|	2.1
GeForce GT 520MX|	2.1
GeForce GT 520M|	2.1
GeForce GTX 485M|	2.1
GeForce GTX 470M|	2.1
GeForce GTX 460M|	2.1
GeForce GT 445M|	2.1
GeForce GT 435M|	2.1
GeForce GT 420M|	2.1
GeForce GT 415M|	2.1
GeForce GTX 480M|	2.0
GeForce 710M|	2.1
GeForce 410M|	2.1

- **Tegra Mobile & Jetson Products**

产品|计算能力
-|-
Jetson TX1|	5.3
Jetson TK1|	3.2
Tegra X1|	5.3
Tegra K1|	3.2