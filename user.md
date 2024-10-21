# 软件准备
## 安装mmWaveStudio
下载软件：[mmWaveStudio](https://www.ti.com.cn/tool/cn/MMWAVE-STUDIO#downloads).
> MMWAVE-STUDIO — 用于第 1 代部件 (xWR1243、xWR1443、xWR1642、xWR1843、xWR6843、xWR6443) 的 mmWave Studio GUI 工具

下载后默认安装即可，也可更改存储地址
## 安装R2015a runtime
这是安装环境，下载地址：[matlab-runtime](https://ww2.mathworks.cn/products/compiler/matlab-runtime.html)
> R2015aSP1 (8.5.1) 1 32bit

下载后默认安装即可
<!---
# 安装Microsoft Visual C++ 2013
用于c++编写，下载地址：[Microsoft Visual C++](https://support.microsoft.com/en-us/topic/update-for-visual-c-2013-and-visual-c-redistributable-package-5b2ac5ab-4139-8acc-08e2-9578ec9b2cf1)
> English - United States    https://download.microsoft.com/download/0/5/6/056DCDA9-D667-4E27-8001-8A0C6971D6B1/vcredist_x64.exe
-->
## CCS驱动
下载[CCS驱动](https://www.ti.com.cn/tool/cn/download/CCSTUDIO-THEIA)
> CCSTheia1.2.0.00007_win64.zip  — 745285 K
## 电脑IP调整
win10操作：网络和 Internet 设置->找到高级网络设置->更多网络适配器选项->以太网->属性->Internet 协议版本 4 (TCP/IPv4)，将地址修改为：
>IP地址：192.168.33.30  
>子网掩码：255.255.255.0
# 设备调试
## 硬件组装
将雷达与DCA1000连接，如图所示：  
<div align=center><img src="https://github.com/heavenbo/DCA1000/blob/main/photo/AWR1843_DCA1000.jpg" width="400px"></img></div>
## 模式调整
AWR1843BOOST中S2开关调整为SPI模式，雷达板上的拨码调为011（SOP2为高位）  
<div align=center><img src="https://github.com/heavenbo/DCA1000/blob/main/photo/AWR184.png" width="400px"></img></div>

将DCA1000上数据位数拨为16位  
<div align=center><img src="https://github.com/heavenbo/DCA1000/blob/main/photo/DCA1000.png" width="400px"></img></div>
## 查看端口
将DCA1000连接电源，将两个usb口、网线连接电脑，进入设备管理器，查看串口，如图所示即算连接成功  
<div align=center><img src="https://github.com/heavenbo/DCA1000/blob/main/photo/port.png" width="400px"></img></div>
将端口波特率设为115200
## 连接电脑
打开软件，出现软件出现以下界面，按顺序操作  
<div align=center><img src="https://github.com/heavenbo/DCA1000/blob/main/photo/gui.png" width="800px"></img></div>
## 软件界面操作
