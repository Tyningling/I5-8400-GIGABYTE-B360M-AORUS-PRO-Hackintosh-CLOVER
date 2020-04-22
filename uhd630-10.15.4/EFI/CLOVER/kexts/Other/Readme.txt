ReadMe
此文件夹为Mac驱动加载提供支持，由 风陵 整理于2020.4.22。

AppleALC 声卡驱动
HibernationFixup 修复HDMI睡眠唤醒无信号
------------------
IntelMausi 有线网卡
IntelMausiEthernet 另一个有线网卡
详见：http://bbs.pcbeta.com/forum.php?mod=viewthread&tid=1817247
-------------------
IO80211Family BCM4322 无线网卡驱动
Lilu 驱动扩展支持
USBInjectAll USB3.0支持驱动
-------------------
VirtualSMC SMC设备伪造驱动 依赖Lilu 下面是它的扩展： 
SMCSuperIO SMC扩展-风扇信息读取
SMCProcessor SMC扩展-为Penryn CPU或以上提供温度传感器支持
SMCLightSensor SMC扩展 光线传感器 如同上条
SMCBatteryManager SMC扩展 -电池传感器
详见：http://bbs.pcbeta.com/viewthread-1840978-1-1.html
-------------------
WhateverGreen 显卡驱动 依赖于Lilu 版本号 1.3.9