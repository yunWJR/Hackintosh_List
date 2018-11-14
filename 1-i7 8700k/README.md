# Hackintosh i78700k

availabel for 10.13.6

> 注意：10.13.6 安全更新后，使用 GT750TI 启动不了。解决办法：

1. 先切换到 HD630，主板 BIOS 切换到独显，（取掉独显，我的主板需要），显示器插到主板的显示接口。
2. 使用EFI-FOR-HD630启动，或者自己修改 config文件，进入系统，更新 webdriver。
3. 切换回原始 EFI，显卡切换回GT750TI，重启。
4. 其他 N 卡类似。

# 配置


```
i7-8700k
华擎 Z370m-pro4
GT750TI (注意：HD630核显（CPU自带）请使用EFI-FOR-HD630文件夹)
BCM94352Z（淘宝买的，当前使用）
8Gx2 2400 DDR4
ALC892声卡（主板自带）
Intel 网卡（主板自带）
建兴（LITEON）睿速系列 T10 240G

```







