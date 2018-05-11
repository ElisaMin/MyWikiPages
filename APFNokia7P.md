# 前言
#### Android P Beta只适合尝鲜使用，如果你想日常使用那你一定是疯了！
[首先你得熟练的使用adb指令](/ADB-Tool) <br />
支持的型号为TA-10`46`/`55` <br />
# 开始
## 获取更新包
 进入诺基亚开发者页面，注册/登入一个诺基亚账号或者使用Facebook、Google帐户登录
 <br />
 输入手机的IMEI-选择运营商、国家-register。
 > 运营商：进入设置>关于手机>状态> SIM卡状态>网络 

 > IMEI码则是在状态-IMEI信息里，两个的话填写IMEI 1即可 
 <br />
 
 
 
![注册界面](http://imgsrc.baidu.com/forum/pic/item/2e99304e251f95ca8e193201c5177f3e66095228.jpg) <br />

---

添加完成后会有一个绿色的`Validation OK`如图所示
 <br />
 
 ![添加完成](http://imgsrc.baidu.com/forum/w%3D580/sign=d96d3c4b70d98d1076d40c39113eb807/707915ce36d3d53941b0a5743687e950342ab008.jpg)
 <br />

点击`Install Manually` 后向下滚动勾选I Read……点击 `Download`
 <br />
 ![下载]( http://imgsrc.baidu.com/forum/pic/item/60a0c895d143ad4b503dd4778e025aafa50f068d.jpg)
 <br />
 ## 恢复出厂设置
（恢复出厂设置） 启用USB调试并使用adb工具执行 `adb reboot recovery` 如果没用的话音量+键和电源键按十秒再松开（？）然后选Recovery mode，在Rec下清除所有的用户数据（Wipe All User Data）
 <br />
![重启](http://imgsrc.baidu.com/forum/w%3D580/sign=d133f932c5ea15ce41eee00186013a25/ec68b2fb43166d229d4282234a2309f79152d2e0.jpg)
 <br />
 ## 刷入
 在Rec里面按住电源+音量加键一次你会发现新大陆，选择“Apply update from ADB”
 <br />
在电脑上输入`adb sideload `把下载好的文件拖进执行窗口（Sideload后面加空格）然后回车执行。 
<br />
![sideload](http://imgsrc.baidu.com/forum/w%3D580/sign=a2b3da7306d162d985ee621421dea950/3311b9014a90f603d33608f03512b31bb151ed13.jpg)
 <br />
 ## 好好享受Android P的快乐吧！
这个时候你可以去喝杯茶什么的，安装完成后在手机选择`Reboot system now`重启后就是Android P了！
# 回滚
 刷回正式版最新固件就行了
 <br />
 <br />
 <br />
 <br />
