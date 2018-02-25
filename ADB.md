# ADB工具 油牌工作室|LG G5 交流群
ADB三个字母你肯定不陌生，刷Recovery、黑域冰箱空调等都有接触，你可能一脸懵逼之中就弄完了，却不知道这是个什么东西。
## 工具包
一般工具包内有两套程序 **ADB**和 **Fastboot** 

> * ADB  <br /> 
ADB全名Andorid Debug Bridge，翻译过来是安卓调试桥，顾名思义这是个调试Android的工具。在调试Android设备 ~~(你的手机)~~ 时，需要在设置里 **打开USB调试** 。 <br /> 

> * Fastboot  <br /> 
Fastboot翻译过来就是快速引导，和ADB一样在调试时要打开某个模式，Fastboot指令也只在Fastboot模式下生效。各种厂商进入Fastboot模式的方式参差不齐，一般来说 **厂商会对Fastboot模式做出不同程度的阉割和修改** ，如果你刷不进Recovery时，可以考虑一下是不是厂商的问题。 <br /> 

## ADB工具包的使用方法
应为内容过于庞大，插进来也不合适。所以我另开了一个篇章。 <br />
[ADB工具安装或使用教程](/ADB-Tool)
## 常用的指令
### ADB指令
>  `adb help` <br /> 
`ADB帮助` 查看所有可执行的指令

> `adb devices` <br /> 
`ADB设备` 查看所有被ADB程序识别的设备

 >  `adb reboot` +  `Recovery` / `Fastboot` <br /> 
 `重启` 到 `恢复模式`/ `快速引导` <br /> 
 
 > `adb sideload` + `文件地址` <br />
  `ADB SIDELOAD` 从执行端获取文件并刷入 ~~(就是在电脑上复制文件到手机里然后再在手机里刷的啦)~~
 
##### [更多的指令请点击这里](https://www.jianshu.com/p/5980c8c282ef)
### Fastboot
> `Fastboot Devices` <br /> 
`Fastboot设备` 查看所有被Fastboot程序识别的设备

> `Fastboot Earse` + `System` / `Data` /  `Userdata` / `ceche` / `更多分区` <br />
`Fastboot 清除` 对某个分区进行清除，如果是要清除除了System以外的分区可以在System后面加上 `-W` 所以完整的指令是 `Fastboot Earse System -w` <br />

> `Fastboot Flash` + `Recovery` / `System` / `Boot` / `modem` / `userdata` / `更多分区` + `文件地址` <br /> 
对某个 `分区` 刷入 `映像文件` <br /> 

> `Fatboot oem unlock` 
解Bootloader锁,此指令会应厂商定制而不同
