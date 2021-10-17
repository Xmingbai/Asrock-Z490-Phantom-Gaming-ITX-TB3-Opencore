
==========================================================================
#  Asrock-Z490-Phantom-Gaming-ITX-TB3 opencore0.7.4 hackintosh Catalina 10.15.x & big sur 11.x

更新至OC0.7.4
更新kexts
5500/5600/5700/6800/6900系列显卡添加启动参数agdpmod=pikera



==========================================================================
#  Asrock-Z490-Phantom-Gaming-ITX-TB3 opencore0.6.8 hackintosh Catalina 10.15.x & big sur 11.x

OC及kexts常规性更新

==========================================================================
==========================================================================
#  Asrock-Z490-Phantom-Gaming-ITX-TB3 opencore0.6.6 hackintosh Catalina 10.15.x & big sur 11.2 &11.3
==========================================================================

操作说明文档同步于B站专栏： https://www.bilibili.com/read/cv9360709?share_medium=iphone&share_plat=ios&share_source=QQ&share_tag=s_i&timestamp=1611116372&unique_k=avREvp

若有其他问题请加Q群：1125705781，备注小明或者B站

也欢迎关注B站：小明和他的女朋友

https://space.bilibili.com/591453294?spm_id_from=333.788.b_765f7570696e666f.2


# 1.基本硬件配置清单 及截图

CPU：i9-10850K（可以支持所有十代）

主板：ASROCK Z490 Phantom Gaming-ITX/TB3

SSD：SN750 500G

Wi-Fi：intel AX200 更换为 BCM94352Z （更换步骤参考B站视频操作）

内存；十铨火神DDR4 3000  16gx2

显卡：一块NVIDIA K4200 和 一块 AMD RX5500XT 作为测试

![](https://github.com/Xmingbai/Asrock-Z490-Phantom-Gaming-ITX-TB3-Opencore/blob/main/big%20sur%2011.2.jpg)

![](https://github.com/Xmingbai/Asrock-Z490-Phantom-Gaming-ITX-TB3-Opencore/blob/main/%E5%85%B3%E4%BA%8E%E6%9C%AC%E6%9C%BA.png)

## 2.macOS实现的功能

CPU正常睿频

核显双硬解正常

核显支持3个4K60HZ显示器，TYPE-C、DP、HDMI 

若使用独显5500、5600、5700 配置文件自带显卡性能优化，请在device中手动启用

音频输出正常（alcid=1）,支持开机启动音，支持显示器音频

支持2.5G有线网卡

蓝牙、WiFi正常  支持隔空、接力、随航

睡眠、休眠、唤醒正常，支持USB、蓝牙唤醒

TYPE-C雷电 支持视频输出、雷电硬盘 且支持热插拔，外接显卡扩展坞可识别但外接显卡无法驱动


未修正的地方 ：缺少雷劈信息

![](https://github.com/Xmingbai/Asrock-Z490-Phantom-Gaming-ITX-TB3-Opencore/blob/main/PCI.png)

![](https://github.com/Xmingbai/Asrock-Z490-Phantom-Gaming-ITX-TB3-Opencore/blob/main/R20.png)

![](https://github.com/Xmingbai/Asrock-Z490-Phantom-Gaming-ITX-TB3-Opencore/blob/main/geekbench.png)

![](https://github.com/Xmingbai/Asrock-Z490-Phantom-Gaming-ITX-TB3-Opencore/blob/main/%E9%9B%B7%E7%94%B5%E5%A4%96%E6%8E%A5%E6%98%BE%E5%8D%A1RX5500XT.png)

Windows 方面

![](https://github.com/Xmingbai/Asrock-Z490-Phantom-Gaming-ITX-TB3-Opencore/blob/main/Windows%20%E5%A4%96%E6%8E%A5%E9%9B%B7%E7%94%B5%E7%A1%AC%E7%9B%98%E7%9B%92.JPG)

![](https://github.com/Xmingbai/Asrock-Z490-Phantom-Gaming-ITX-TB3-Opencore/blob/main/Windows%20%E5%A4%96%E6%8E%A5%E9%9B%B7%E7%94%B5%E7%A1%AC%E7%9B%98%E7%9B%92.JPG)


# 3.OC 0.6.6 更新说明

☆ 升级kext驱动到最新正式版本

☆ 音频输出 增加了核显（DP或者HDMI）显示器音频输出

☆ device properties 内包含RX55000xt\5600&5700优化信息，需要手工启用（去掉前置#就行）

☆ 更换OC主题包（支持OC UI 随意切换有三个背景选择，改名为Background.icns即可）

☆ 正常直升11.2 （支持11.3 beta x）


# OC 0.6.5 更新说明

☆ OC0.6.5 支持Catalina 10.15.x 和Big Sur 11.1 支持OTA升级，支持直装

☆ 升级kext驱动到最新正式版本

☆ 更换OC主题包

☆ config.plist 添加了5500、5600&5700 显卡仿冒优化参数


![](https://github.com/Xmingbai/hackintosh-opencore--UI-theme/blob/main/TipsBackground.png)

如何切换到背景无提示的纯净方式呢？

EFI/OC/Resources/Image/NoTipsBackground.icns文件改名为Background.icns即可（先改名同名文件）

![](https://github.com/Xmingbai/hackintosh-opencore--UI-theme/blob/main/NoTipsBackground.png)


# 若有其他问题请加Q群：1125705781，备注小明或者B站，也欢迎关注B站：小明和他的女朋友

此份操作指南 同步 发布于B站专栏，方便国内访问  

https://www.bilibili.com/read/cv8721205 


# 4.bios 设置参考指南   

https://www.bilibili.com/read/cv7393476

雷电3 bios设置参考截图

![](https://github.com/Xmingbai/Asrock-Z490-Phantom-Gaming-ITX-TB3-Opencore/blob/main/TB3-BIOS.BMP)

另 四大主板厂商华擎、华硕、微星、技嘉 针对性 详细截图 黑苹果bios设置 参考B站专栏

https://space.bilibili.com/591453294/article


# 5.OC0.6.5 引导使用指南 

## 5.1 基本驱动及对应版本

Lilu.kext----------------------------1.5.1

VirtualSMC.kext--------------------1.2.0 

WhateverGreen.kex----------------1.4.6

AppleALC.kext---------------------1.5.6

LucyRTL8125Ethernet.kext---------1.0.0

## 5.2 OC配置文件config.plist如何使用

A.请变更三码食用，i9 cpu采用imac20.2，i9以下级别采用iMac20.1

B.device property 中已有5500、5600&5700 显卡仿冒优化参数，去掉显卡路径前面#符号即可启用

C.启动参数中 agdpmod=pikera 一般仅使用5500&5600&5700显卡时保留，使用其他显卡请删除该参数

![](https://github.com/Xmingbai/Asrock-Z490-Phantom-Gaming-ITX-TB3-Opencore/blob/main/%E6%98%BE%E5%8D%A1%20device.png)

![](https://github.com/Xmingbai/Asrock-Z490-Phantom-Gaming-ITX-TB3-Opencore/blob/main/kext.png)

## 5.3 USB端口定制了15个端口，见USBports截图

![](https://github.com/Xmingbai/Asrock-Z490-Phantom-Gaming-ITX-TB3-Opencore/blob/main/%E4%B8%BB%E6%9D%BFUSB%E5%90%8E%E7%BD%AE%E5%88%86%E5%B8%83.png)

![](https://github.com/Xmingbai/Asrock-Z490-Phantom-Gaming-ITX-TB3-Opencore/blob/main/%E4%B8%BB%E6%9D%BF%E5%89%8D%E7%BD%AE.png)

3个USB支持10G速率

默认是前置只有一个TYPE-C的USB端口定制

![](https://github.com/Xmingbai/Asrock-Z490-Phantom-Gaming-ITX-TB3-Opencore/blob/main/USBports.png)

还保留了前置有2个USB3.0的USB端口定制，有需要的可以启用 USBPorts_2USB3.0.kext

## 5.4如何使用2.5G有线网卡
 
 联网设置：系统偏好设置—-网络—以太网—高级——硬件—配置有自动改为手动，速率手工设置为1000 全双工（或100，取决于网线链接路由器的端口速率），见图

![](https://github.com/Xmingbai/asrock-Z490M-itx-hackintosh/blob/main/2.5G%E7%BD%91%E5%8D%A1%E8%AE%BE%E7%BD%AE.png)

# 若有其他问题请加Q群：1125705781，备注小明或者B站

# 也欢迎关注B站：小明和他的女朋友  或者 

https://space.bilibili.com/591453294?spm_id_from=333.788.b_765f7570696e666f.2
