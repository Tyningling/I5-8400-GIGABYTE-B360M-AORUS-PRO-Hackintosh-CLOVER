目前已知问题： 在Clover引导界面 选择 exit退出引导不会断电。 貌似旧版本也不行！ 

配置如同标题,我使用的是**BCM4322**的无线网卡，该网卡在10.14以下免驱，10.15需要加载特殊驱动。

假设您与我的网卡配置不符，

请另找别人同配置的网卡驱动搬移至kexts/Other/下，删除IO80211Family.kext即可。

我目前使用的MAC的镜像源来自[黑果小兵 19E287原版镜像](https://blog.daliansky.net/macOS-Catalina-10.15.4-19E266-Release-version-with-Clover-5107-original-image-Double-EFI-Version-UEFI-and-MBR.html)。

使用Clover引导。

更新日志：

2020.4.22 - 修复HDMI睡眠唤醒无信号。

修复BCM4322 驱动。

支持USB3.0接口，成功加载声卡驱动。

成功解决HDMI无信号输出问题。
