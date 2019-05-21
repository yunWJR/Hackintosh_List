# Hackintosh List - 我的黑苹果 EFI

# 0-kext 文件夹

最新kext 集合

更新时间：2019.05.08



下载地址：

- Clover [最新下载地址](https://sourceforge.net/projects/cloverefiboot/)

- [LiLu](https://github.com/acidanthera/Lilu/releases)

- LiLu [常用插件](https://github.com/acidanthera/Lilu/blob/master/KnownPlugins.md)

- [RehabMan](https://bitbucket.org/RehabMan/)



# 1-i7 8700k 文件夹

availabel for 10.14.5

## 配置信息

```
i7-8700k
华擎 Z370m-pro4
蓝宝石 RX470D (注意：HD630核显（CPU自带）请使用EFI-FOR-HD630文件夹)
BCM94352Z（淘宝买的，当前使用）
8Gx2 2400 DDR4
ALC892声卡（主板自带）
Intel 网卡（主板自带）
建兴（LITEON）睿速系列 T10 240G

```


10.14.5 USB 解除限制补丁

```
Comment: USB port limit patch #1 10.14.x modify by DalianSky(credit ydeng)
Name: com.apple.iokit.IOUSBHostFamily
Find: 83FB0F0F
Replace: 83FB3F0F
MatchOS: 10.14.x

Comment: USB port limit patch #2 10.14.x modify by DalianSky(credit PMHeart)
Name: com.apple.iokit.IOUSBHostFamily
Find: 83E30FD3
Replace: 83E33FD3
MatchOS: 10.14.x

Comment: USB Port limit patch #3 10.14.x modify by DalianSky(credits PMheart)
Name: com.apple.driver.usb.AppleUSBXHCI
Find: 83FB0F0F
Replace: 83FB3F0F
MatchOS: 10.14,10.14.1,10.14.2,10.14.3

Comment: USB Port limit patch #4 10.14.x modify by DalianSky(credits PMheart)
Name: com.apple.driver.usb.AppleUSBXHCI
Find: 83FF0F0F
Replace: 83FF3F0F
MatchOS: 10.14.x
```


> 注意：10.13.6 安全更新后，使用 GT750TI 启动不了。解决办法：

1. 先切换到 HD630，主板 BIOS 切换到独显，（取掉独显，我的主板需要），显示器插到主板的显示接口。
2. 使用EFI-FOR-HD630启动，或者自己修改 config文件，进入系统，更新 webdriver。
3. 切换回原始 EFI，显卡切换回GT750TI，重启。
4. 其他 N 卡类似。



# 2-i5 4590 -文件夹

availabel for 10.13.6



## 配置信息

```
i5-4590 
华硕 b85m 
HD4600核显（CPU自带）
8G 1600 DDR3
声卡（主板自带）
Intel 网卡（主板自带）
```





# 3-deskmini

[链接](https://github.com/yunWJR/Hackintosh-deskmini-efi)



## 配置信息

```
主机: deskmini 
CPU: i5-7500 或 i7-7700
网卡：Intel I219V千兆网卡（主板自带）
网卡：BCM94352Z（淘宝买的，当前使用）

```

# 4-lenovo-y700

[链接](https://github.com/yunWJR/Hackintosh-y700-efi)



## 配置信息

```
机型：lenovo-y700（I5 6300Hq）
网卡：BCM94352Z
```








