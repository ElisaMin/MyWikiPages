# APN
APN指一种网络接入技术，是通过手机上网时必须配置的一个参数，它决定了手机通过哪种接入方式来访问网络。[百度百科>>>](https://baike.baidu.com/item/apn/96667) <br />
以下均来自Moto Z Play Verizon固件
## 联通
**以下标题只是名字，并不是什么这正的3G2G接入点，坐和放宽不用在意3G2G没有4G接入点什么的。**
### 2G手机上网
> 接入点名称: `uniwap` <br />
> 代理: `10.0.0.172`<br />
> 端口: `80`<br />
> 接入点名称类型: `default` <br />
 
### 2G连接互联网
> 接入点名称: `uninet` <br />
> 接入点名称类型: `default` <br />
 
### 2G联通彩信
> 接入点名称: `uniwap`<br />
> MMSC: `http://mmsc.myuni.com.cn` <br />
> 彩信代理: `10.0.0.172`<br />
> 彩信端口: `80` <br />

### 3G手机上网
> 接入点名称: `3gwap`<br />
> 代理: `10.0.0.172`<br />
> 端口: `80`<br />
> 接入点名称类型:`default,supl` <br />
 
### 3G连接互联网
> 接入点名称: `3gnet` <br />
> 接入点名称类型: `default,supl` <br />
 
### 3G联通彩信
> 接入点名称: `3gwap` <br />
> MMSC: `http://mmsc.myuni.com.cn` <br />
> 彩信代理: `10.0.0.172`<br />
> 彩信端口: `80` <br />

### IMS
> 接入点名称: `ims`<br />
> 接入点名称类型: `ims` <br />

## 电信
~~好像没有联通那么多~~
### 中国电信(IMS)
> 接入点名称: `ims`<br />
> 接入点名称类型: `ims` <br />
> MNC: `03` <br />

### 中国电信互联网
> 接入点名称: `ctnet`<br />
> 接入点名称类型: `default,supl,fota` <br />
> 用户名: `ctnet@mycdma.cn`<br />
> 密码: `vnet.mobi` <br />
> MNC: `03` <br />

### 中国电信彩信
> 接入点名称: `ctwap` <br />
> 接入点名称类型: `mms`<br />
> 用户名: `ctnet@mycdma.cn`<br />
> 密码: `vnet.mobi` <br />
> MMSC: `http://mmsc.vnet.mobi`<br />
> 彩信代理: `10.0.0.200`<br />
> 彩信端口: `80` <br />
> MNC: `03` <br />

## 移动
待收录
## 用APN解决DNS劫持
[来自酷安动态≫≫](https://www.coolapk.com/feed/5303864)
