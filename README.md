# lnmp-full-safe lnmp.org Safe Download
# 介绍
Safe Download Source for lnmp tools All Versions Install Script
安全的lnmp全版本安装服务
文件校验的md5数据来自 webarchive 具体时间线见下方表格
# 背景
### 起因
众所周知，lnmp.org为非常好用的环境部署工具，但是在2023年9月19号被监测到有投毒风险，网站的说明也从个人变成了金华市的一家公司，后续，他们相继收购了 oneinstack，也是wdcp持有者；
从个人角度，个人制作了原始链接，用于个人方便使用之前的版本。如有问题，请及时联系。
### 事件发生时间线：
| 发生时间  | 内容  | 链接  |
|  ----  | ----  |----  |
| 20230919 |安恒信息CERT发布  关于LNMP供应链投毒事件风险提示 正式发现 | https://mp.weixin.qq.com/s/OT7C1l5rjBNCawFXRIUJOQ| 
| 20230927 | oneinstack.com 的备案号 9 月 27 号变更为：浙 ICP 备 2023007596 号-4，与该公司运营的 MAC 软件网站的备案号：浙 ICP 备 2023007596 号-1 一致，该公司还同时收购了军哥的 lnmp.org 一键脚本，lnmp.org 网站下的版权信息已经变更 |  [twitter消息](https://twitter.com/landiantech/status/1709226985334214932)| 
| 20231006 | oneinstack issue有人反馈下载的数据和官方不一致，作者反馈是自己管理不善 |  https://github.com/oneinstack/oneinstack/issues/511| 
| 20231122 | oneinstack issue继续有人反馈md5不一致，截止20230224暂未有解释原因 |https://github.com/oneinstack/oneinstack/issues/517|

消息来源： 


# 安全文件服务如下
lnmp脚本支持在线下载文件安装，也支持离线安装，离线安装，会预先把所有的文件打包到一个压缩包里，使用过程中不会再联网下载安装包。
目前已验证的完整安装包的内容和数据源，请下载之后使用 md5sum 工具务必再校验一遍，具体使用方式可以自行网上查找

| Version                | File Size | MD5                              |  Source|Download Link|
|------------------------|-----------|----------------------------------| ------|-------|
| lnmp2.0-full.tar.gz(理论上此版本安全,网站下方未变更主体) |1.2GB |ada53925291dc448b70f19de8f92880c|[webarchive20230831](https://web.archive.org/web/20230831000930/https://lnmp.org/download.html)|[Link](https://github.com/jwsky/lnmp-full-safe/releases/download/publish/lnmp2.0-full.tar.gz)|
| lnmp1.9-full-v2.tar.gz（理论上v1 v2均安全，网站下方未变更主体） | 1GB|8486d50dc908dda7ada559834c0064b8|[webarchive20230831](https://web.archive.org/web/20230831000930/https://lnmp.org/download.html)|[Link](https://github.com/jwsky/lnmp-full-safe/releases/download/publish/lnmp1.9-full-v2.tar.gz)|
| lnmp1.9-full-v1.tar.gz（理论上v1 v2均安全，网站下方未变更主体） | 1GB|09020777f9ce981a01b1fdd229f6f427|[Webarchive20230430](https://web.archive.org/web/20230530002906/https://lnmp.org/download.html)|[Link](https://github.com/jwsky/lnmp-full-safe/releases/download/publish/lnmp1.9-full-v1.tar.gz)|
| lnmp1.8-full.tar.gz（较久版本，理论安全）    | 909MB     | 3027d97ff1c4d19141dc8b243f4135ec|[Webarchive20230430](https://web.archive.org/web/20230530002906/https://lnmp.org/download.html)|[Link](https://github.com/jwsky/lnmp-full-safe/releases/download/publish/lnmp1.8-full.tar.gz)|
| lnmp1.7-full.tar.gz （较久版本，理论安全）   | 870MB     | 763e66eb3d6b234019dab57a1d9c80c5|[Webarchive20230430](https://web.archive.org/web/20230530002906/https://lnmp.org/download.html)|wait|
| lnmp1.6-full.tar.gz （较久版本，理论安全）   | 677MB     | ed70f840634a74619d9a6e81c66b4843|[Webarchive20230430](https://web.archive.org/web/20230530002906/https://lnmp.org/download.html)|wait|
| lnmp1.5-full.tar.gz （较久版本，理论安全）   | 581MB     | 1ce4d7ef8c57341f8c56983bbb29ebfa|[Webarchive20230430](https://web.archive.org/web/20230530002906/https://lnmp.org/download.html)|wait|
| lnmp1.4-full.tar.gz （较久版本，理论安全）   | 406MB     | 8419aaafc137057087812ea447e7b13a|[Webarchive20230430](https://web.archive.org/web/20230530002906/https://lnmp.org/download.html)|wait|
| lnmp1.3-full.tar.gz （较久版本，理论安全）   | 478MB     | a5aa55cd177cd9b9176ad697c12e45c0|[Webarchive20230430](https://web.archive.org/web/20230530002906/https://lnmp.org/download.html)|wait|
| lnmp1.2-full.tar.gz （较久版本，理论安全）   | 312MB     | b3d3d9e40395f4eb5e525adfaabfb675 |[Webarchive20230430](https://web.archive.org/web/20230530002906/https://lnmp.org/download.html)|wait|
| lnmp1.1-full.tar.gz （较久版本，理论安全）   | 184MB     | 744d0155b8ebe4ae424578937a0cafac|[Webarchive20230430](https://web.archive.org/web/20230530002906/https://lnmp.org/download.html)|wait|
| lnmp1.0-full.tar.gz （较久版本，理论安全）   | 134MB     | e1127d65d93415c429010d6859353eea |[Webarchive20230430](https://web.archive.org/web/20230530002906/https://lnmp.org/download.html)|wait|
| lnmp0.9-full.tar.gz （较久版本，理论安全）   | 61.83MB   | 0eb79ddd5cd1df3a487f62e7943aaa9d |[Webarchive20230430](https://web.archive.org/web/20230530002906/https://lnmp.org/download.html)|wait|
| lnmp0.8-full.tar.gz  （较久版本，理论安全）  | 80.25MB   |Not Provided                                | -                          |
| lnmp0.7-full.tar.gz （较久版本，理论安全）   | 66.64MB   | Not Provided                                | -                          |
| lnmp0.6-full.tar.gz （较久版本，理论安全）   | 50.56MB   | Not Provided                                 | -                          |
| lnmp0.5-full.tar.gz （较久版本，理论安全）   | 44.19MB   | Not Provided                                | -                          |
| lnmp0.4-full.tar.gz    | 44.2MB    | Not Provided                                 | -                          |




 
