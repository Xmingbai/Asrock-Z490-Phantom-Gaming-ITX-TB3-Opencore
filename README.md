# 编辑更新中
==========================================================================
#  Asrock-Z490-Phantom-Gaming-ITX-TB3 opencore0.6.5 hackintosh Catalina 10.15.x & big sur 11.1
==========================================================================

# 1.基本硬件配置清单 及截图

CPU：i9-10850K（可以支持所有十代）

主板：ASROCK Z490 Phantom Gaming-ITX/TB3

SSD：SN750 500G

Wi-Fi：intel AX200 更换为 BCM94352Z （更换步骤参考B站视频操作）

内存；十铨火神DDR4 3000  16gx2

![](https://github.com/Xmingbai/Asrock-Z490-Phantom-Gaming-ITX-TB3-Opencore/blob/main/%E5%85%B3%E4%BA%8E%E6%9C%AC%E6%9C%BA.png)


## 2.macOS 基本功能

CPU正常睿频

核显双硬解正常

核显支持3个4K60HZ显示器，TYPE-C、DP、HDMI 

若使用独显5500、5600、5700 配置文件自带显卡性能优化，请在device中手动启用

音频输出正常（alcid=1）

支持2.5有线网卡

蓝牙、WiFi正常  支持隔空、接力、随航

睡眠、休眠、唤醒正常，支持USB、蓝牙唤醒

TYPE-C雷电 支持视频输出、雷电硬盘 且支持热插拔，外接显卡扩展坞可识别但显卡无法驱动


未修正的地方 ：缺少雷劈信息

![](https://github.com/Xmingbai/asrock-Z490M-itx-hackintosh/blob/main/%E5%85%B3%E4%BA%8E%E6%9C%AC%E6%9C%BA.png)

![](https://github.com/Xmingbai/asrock-Z490M-itx-hackintosh/blob/main/CPU%20geekbench.png)

![](https://github.com/Xmingbai/asrock-Z490M-itx-hackintosh/blob/main/IGPU%20DP%25HDMI.png)

![](https://github.com/Xmingbai/Asrock-Z490-Phantom-Gaming-ITX-TB3-Opencore/blob/main/%E5%8F%8C%E6%98%BE%E5%8D%A1.png)






# 3. OC 0.6.5 更新说明

☆ OC0.6.5 支持Catalina 10.15.x 和Big Sur 11.1 支持OTA升级，支持直装

☆ 升级kext驱动到最新正式版本

☆ 更换OC主题包



![](https://github.com/Xmingbai/hackintosh-opencore--UI-theme/blob/main/TipsBackground.png)

如何切换到背景无提示的纯净方式呢？

EFI/OC/Resources/Image/NoTipsBackground.icns文件改名为Background.icns即可（先改名同名文件）

![](https://github.com/Xmingbai/hackintosh-opencore--UI-theme/blob/main/NoTipsBackground.png)



# 若有其他问题请加Q群：1125705781，备注小明或者B站，也欢迎关注B站：小明和他的女朋友


此份操作指南 同步 发布于B站专栏，方便国内访问  

https://www.bilibili.com/read/cv8721205 




# 3.bios 设置参考指南   

https://www.bilibili.com/read/cv7393476

雷电3 bios设置参考截图



另 四大主板厂商华擎、华硕、维修、技嘉 针对性 详细截图 黑苹果bios设置 参考B站专栏

https://space.bilibili.com/591453294/article


# 4.OC0.6.4 引导使用指南 

## 4.1 基本驱动及对应版本

Lilu.kext----------------------------1.5.1

VirtualSMC.kext--------------------1.2.0 

WhateverGreen.kex----------------1.4.6

AppleALC.kext---------------------1.5.6

LucyRTL8125Ethernet.kext---------1.0.0



## 4.2 OC配置文件config.plist如何使用




## 4.3 USB端口定制了15个端口，见USBports截图

![](https://github.com/Xmingbai/Asrock-Z490-Phantom-Gaming-ITX-TB3-Opencore/blob/main/%E4%B8%BB%E6%9D%BFUSB%E5%90%8E%E7%BD%AE%E5%88%86%E5%B8%83.png)

![](https://github.com/Xmingbai/Asrock-Z490-Phantom-Gaming-ITX-TB3-Opencore/blob/main/%E4%B8%BB%E6%9D%BF%E5%89%8D%E7%BD%AE.png)

3个USB支持10G速率



## 4.4 如何使用2.5G有线网卡
 
 联网设置：系统偏好设置—-网络—以太网—高级——硬件—配置有自动改为手动，速率手工设置为1000 全双工（或100，取决于网线链接路由器的端口速率），见图


![](https://github.com/Xmingbai/asrock-Z490M-itx-hackintosh/blob/main/2.5G%E7%BD%91%E5%8D%A1%E8%AE%BE%E7%BD%AE.png)

# 若有其他问题请加Q群：1125705781，备注小明或者B站

# 也欢迎关注B站：小明和他的女朋友

https://space.bilibili.com/591453294?spm_id_from=333.788.b_765f7570696e666f.2
