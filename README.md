# B460M-MORTAR-WIFI-Hackintosh-OCEFI
自用迫击炮B460m的完美OC黑果EFI，有两个版本，硬件跟我差不多的照理通用

USB 所有USB已完美定制 有问题的话自己根据自己的主机定制

**Opencore版本：1.0.4**
MacOS版本15.5  

[下载链接](https://github.com/JasmineYong/B460M-MORTAR-WIFI-Hackintosh-OCEFI/releases) 

| 硬件 | 型号 |
| ------------- | ------------- |
|CPU|i3-10100(Comet Lake)|
|主板|B460M-MORTAR-WIFI|
|核显|UHD Graphics 630|
|独显|没有独显未屏蔽|
|硬盘|ZHITAI TiPlus5000 512GB|
|主板声卡|USB音响 ALC1200|
|主板有线网卡|Realtek RTL8125|
|主板无线网卡|AX200|
|主板蓝牙|英特尔(R) 无线 Bluetooth(R)|

**已定制显示器HDMI接口**  
**无法显示的话 请修改DeviceProperties**
| 删除 | 重新添加Key | Data Type | Value |
| ------------- | ------------- | ------------- | ------------- |
|framebuffer-con0-alldata|framebuffer-patch-enable|Data|01000000
|framebuffer-con0-enable|framebuffer-stolenmem|Data|00003001
|framebuffer-patch-enable|

**BIOS设置**  
一键黑苹果模式 SETTINGS-高级-D.T.M-允许  
或者手动设置：  
快速开机：禁止  
安全启动：禁止  
PCIE设备唤醒：允许  
USB设备从S3/S4/55唤醒：允许  
PS/2鼠标从S3/S4/55唤醒：允许  
PS/2键盘从S3/S4/55唤醒：任意键  
集成显卡多显示器：允许  
CFG锁定：禁止  

![image](https://github.com/JasmineYong/B460M-MORTAR-WIFI-Hackintosh-OCEFI/blob/main/1007a088f99274438179f83dcd50f13f.png)
![image](https://github.com/JasmineYong/B460M-MORTAR-WIFI-Hackintosh-OCEFI/blob/main/4974ae1e10ca320192d1ec013affa989.png)
![image](https://github.com/JasmineYong/B460M-MORTAR-WIFI-Hackintosh-OCEFI/blob/main/90cef088961cff3dec1ab1b92955fd4c.png)
