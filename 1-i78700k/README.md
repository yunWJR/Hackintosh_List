# Hackintosh-i78700k-efi
i78700k-efi for Hackintosh
> `Now available for 10.12.6、10.13.1`

# 1. 主机配置
* i7-8700k
* 华擎 Z370m-pro4
* HD630核显（CPU自带）
* BCM94352Z（淘宝买的，当前使用）
* 8Gx2 2400 DDR4
* ALC892声卡（主板自带）
* Intel 网卡（主板自带）
* 建兴（LITEON）睿速系列 T10 240G

# 2. BIOS设置
* Vt-d 关闭
* IOAPIC 24-119 Entries 关闭
* USB XHCI Handoff 打开
* 安全启动模式 关闭

# 3. Clover信息
clover：r4452
## 正常功能：
* CPU 变频正常
* BCM94352Z 正常
* 声卡-realtekALC.kext驱动
* USB正常

## 待解决：
* 双屏输出

# 更新记录
2018-05-08
1、change SMBIOS to iMac18.1 for fix HD630 in 10.13.4
2、update clove
3、update kext

2018-02.08
初始版本