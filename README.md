# tl-wr740n-v5
添加机型：
tl-wr740n-v5
（for https://github.com/coolsnowwolf/lede）

grep -irl wr710n ./*

1.【修改文件】

/target/linux/ath79/image/generic-tp-link.mk

2.【新增文件】

/target/linux/ath79/dts/ar9331_tplink_tl-wr740n-v5.dts

=================================================================

【原厂参数】

型号：TL-WR740N v5.0  MO:111196

1、cpu：AR9331-AL1A

2、内存16MB：8M*16bit ddr类型 winbond  W9412G6JH-5 【已硬改为64MB，型号：HY5DU121622DTP-D43】

3、闪存：16Mbit/8=2MB sop-8 【已硬改为16MB，型号：MX25L12835FM2I-10G】

4、网口：W L L L L，100Mbps

5、WiFi：2.4ghz 150M 单天线


软件版本：  

4.17.5 Build 110115 Rel.54888n

硬件版本：     

WR740N 5.0 00000000

