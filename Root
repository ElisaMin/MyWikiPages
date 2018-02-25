# Root科普
Root翻译:根、祖先、起源。
## 超级用户
超级用户是指操作系统上拥有 `最高权限的用户 `，不同的操作系统也有不同的叫法。
> * 在Windows的超级用户叫`Administrators` 也就是 `超级管理员` 
> * 在Unix和Linux超级用户叫 `Root` 。 <br />

不管什么名字，共有特征 `最高权限` 。
## SU
SU是Switch User（切换用户）的简写，在Linux或Unix执行 `SU` 指令可以切换到超级用户（Root）从而获取最高权限。
## Android的Root
Android的内核来源于Linux，不例外的也是需要执行 `SU` 指令切换到Root（超级用户）才能使用最高权限。出自安全考虑大多数的厂商都会阉割掉 `SU` 指令，并且有的厂商会吞掉自行添加的SU程序以保证系统文件不被更改。所谓的Root软件和Root补丁都是将 `SU可执行文件`添加到Android系统里（/System/xbin）。
# Android获取Root权限的方法
## Root软件
主要是通过漏洞的方式添加SU可执行文件，似乎自从Android L（5.0/5.1）以后成功率就逼近0%，现在基本死光了。
## Recovery刷入补丁
Android M（6.0）以后用得最多同时成功率逼近1000‰的方法，用的最多的补丁品牌有以下两位。
### SuperSU
又名超级授权，历史悠久的神器，几乎无人能敌。可惜最近被国内某公司收购了，原作者也退出了对SuperSU的开发，2.80版本的SuperSU权限管理App一下多了十几二十个权限。2.79是最后一个干净的版本，更推荐使用Magisk。
### Magisk（强力推荐）
又称马脸、脸谱，Magisk本身是模块框架，在13版本之后加入了MagiskSU 。 **你可以不用Magisk的模块但SU绝对必须得用**  。现在很多第三方ROM都自带Magisk，最重要的还是  **Magisk能隐藏Root权限和Xposed！** （Magisk和Xposed不是一回事也不能互相代替但是可以互相存在） <br />
<br />
**油牌工作室 |LG G5 交流群** 
###### 本文章如有侵权 请你憋着 如有错误请指正
