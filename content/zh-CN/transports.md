# 可插拔传输

可插拔传输层
是一种洋葱路由用来伪装其传输的数据信号之特殊工具，当您的网络服务供应商或所处的网络环境会过滤阻挡通往洋葱路由网络的连接时，此工具即可发挥其功用。

## 可插拔传输的类型

目前有六种可插拔传输可用，更多机制正在开发。

obfs3

|

obfs3 makes Tor traffic look random, so that it does not look like Tor or any
other protocol. While still included by default, it is reccomended to use
obfs4 instead, as it has several security improvements over obfs3.  
  
---|---  
  
obfs4

|

obfs4 可以像 obfs3
一样让洋葱路由所发送的网络信号看起来像是随机乱数一般，并且还可以避免网络过滤监控机制利用网段扫描法找出网桥的地址，因此相较之下 obfs4
网桥更难以被网络监控过滤机制阻挡。  
  
Scramblesuit

|

ScrambleSuit 类似 obfs4，但使用了不同的网桥。  
  
FTE

|

FTE（变形加密）可将 Tor 的网络传输乔装打扮为普通网络（HTTP）数据。  
  
meek

|

这些 可插拔传输层 都可以让您在使用洋葱路由来上网时，在网络上传输的数据信号看起来就像是在浏览普通网站一样，meek-amazon
可以让您的网络信号看起来像是在访问亚马逊网络服务一样；meek-azure 则可以让您的网络信号看起来像是正在使用微软的网络云端服务一般；而 meek-
google 会让您的网络信号看起来像是在使用谷歌搜索引擎一样。  
  
Snowflake

|

Snowflake is an improvement upon Flashproxy. It sends your traffic through
WebRTC, a peer-to-peer protocol with built-in NAT punching.  
  
## 关于

© 2016 YF

© 2016 danfong

© 2016 naruto861214

© 2016 Vel

© 2016 Agustín Wu

© 2016 Chinrur Yang

© 2016 LNDDYL

© 2017 Mingye Wang (Arthur2e5)

翻译者

  * YF
  * danfong
  * naruto861214
  * Vel
  * Agustín Wu
  * Chinrur Yang
  * LNDDYL
  * Mingye Wang (Arthur2e5)

