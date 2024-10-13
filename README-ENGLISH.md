# Lnmp Safe Download - lnmp-full-safe lnmp.org Safe Download
中文   |  English 
# Introduction
Safe Download Source for lnmp tools All Versions Install Script  
A secure service for downloading all versions of lnmp installation scripts. This content is a snapshot collection of historical versions from lnmp.org.  
File source: Historical files from Tianyi Cloud (with timestamps from the time of upload) [Link](https://cloud.189.cn/web/share?code=mmMF32NbEZv2)  
File verification MD5 data: From webarchive, the specific timeline is listed in the table below.

# Background
### Cause
It is well-known that lnmp.org is a very useful environment deployment tool, but on September 19, 2023, it was detected that there was a poisoning risk. The website's description also changed from an individual to a company in Jinhua City. Later, they successively acquired Oneinstack, which is also owned by wdcp.  
From a personal perspective, the official website may be "safe" now, but historical versions are safer. Therefore, this original link collection was created for personal convenience in using previous historical versions. This is only for personal convenience, with no profit involved. If there are any issues, please get in touch.  

### Event Timeline:
| Date  | Content  | Link  |
|  ----  | ----  |----  |
| 20230919 |Anheng Information CERT issued a risk alert about LNMP supply chain poisoning | https://mp.weixin.qq.com/s/OT7C1l5rjBNCawFXRIUJOQ| 
| 20230927 | On September 27, the filing number of oneinstack.com was changed to: Zhejiang ICP Bei 2023007596 No. -4, consistent with the filing number of the company's Mac software site: Zhejiang ICP Bei 2023007596 No. -1. The company also acquired the one-click script from lnmp.org. The copyright information on lnmp.org has already been changed. |  [Twitter Message](https://twitter.com/landiantech/status/1709226985334214932)| 
| 20231006 | Someone reported on the oneinstack issue that the downloaded data was inconsistent with the official version, and the author replied that it was due to their mismanagement |  https://github.com/oneinstack/oneinstack/issues/511| 
| 20231122 | The oneinstack issue continues with reports of MD5 mismatches, and no explanation has been provided as of February 24, 2023 |https://github.com/oneinstack/oneinstack/issues/517|

Source: 

# Secure File Services as follows:
LNMP scripts support online file downloads for installation and offline installation. For offline installation, all files will be pre-packaged into a compressed file, and no further downloads will be required during usage.  
The currently validated complete installation packages and data sources are listed below. After downloading, please be sure to verify using the md5sum tool. You can search for specific usage methods online.  
For installation instructions, refer to the official website: https://lnmp.org/install.html  
Thanks to lnmp.club  
PS: Due to the large size of MySQL/MariaDB binary packages, the full version does not include binaries. For offline installation, use the compilation installation method or download the binaries manually to the src directory of the installation package.  
You are also welcome to use the modified version by a senior expert (not verified by me): https://github.com/moeYuiYui/lnmp  

| Version                | File Size | MD5                              |  Source|Download Link|
|------------------------|-----------|----------------------------------| ------|-------|
| lnmp2.0-full.tar.gz (Theoretically safe, subject not changed at the bottom of the website) |1.2GB |ada53925291dc448b70f19de8f92880c Verification method: After downloading, run the command (Linux/Mac) md5sum lnmp2.0-full.tar.gz |[webarchive20230831](https://web.archive.org/web/20230831000930/https://lnmp.org/download.html)|[Link](https://github.com/jwsky/lnmp-full-safe/releases/download/publish/lnmp2.0-full.tar.gz)|
| lnmp1.9-full-v2.tar.gz (Theoretically v1 and v2 are both safe, subject not changed at the bottom of the website) | 1GB|8486d50dc908dda7ada559834c0064b8 Verification method: After downloading, run the command (Linux/Mac) md5sum lnmp1.9-full-v2.tar.gz|[webarchive20230831](https://web.archive.org/web/20230831000930/https://lnmp.org/download.html)|[Link](https://github.com/jwsky/lnmp-full-safe/releases/download/publish/lnmp1.9-full-v2.tar.gz)|
| lnmp1.9-full-v1.tar.gz (Theoretically v1 and v2 are both safe, subject not changed at the bottom of the website) | 1GB|09020777f9ce981a01b1fdd229f6f427 Verification method: After downloading, run the command (Linux/Mac) md5sum lnmp1.9-full-v1.tar.gz|[Webarchive20230430](https://web.archive.org/web/20230530002906/https://lnmp.org/download.html)|[Link](https://github.com/jwsky/lnmp-full-safe/releases/download/publish/lnmp1.9-full-v1.tar.gz)|
| lnmp1.8-full.tar.gz (Older version, theoretically safe) | 909MB |3027d97ff1c4d19141dc8b243f4135ec Verification method: After downloading, run the command (Linux/Mac) md5sum lnmp1.8-full.tar.gz|[Webarchive20230430](https://web.archive.org/web/20230530002906/https://lnmp.org/download.html)|[Link](https://github.com/jwsky/lnmp-full-safe/releases/download/publish/lnmp1.8-full.tar.gz)|
| lnmp1.7-full.tar.gz (Older version, theoretically safe) | 870MB |763e66eb3d6b234019dab57a1d9c80c5|[Webarchive20230430](https://web.archive.org/web/20230530002906/https://lnmp.org/download.html)|Not recommended to use|
| lnmp1.6-full.tar.gz (Older version, theoretically safe) | 677MB |ed70f840634a74619d9a6e81c66b4843|[Webarchive20230430](https://web.archive.org/web/20230530002906/https://lnmp.org/download.html)|Not recommended to use|
| lnmp1.5-full.tar.gz (Older version, theoretically safe) | 581MB |1ce4d7ef8c57341f8c56983bbb29ebfa|[Webarchive20230430](https://web.archive.org/web/20230530002906/https://lnmp.org/download.html)|Not recommended to use|
| lnmp1.4-full.tar.gz (Older version, theoretically safe) | 406MB |8419aaafc137057087812ea447e7b13a|[Webarchive20230430](https://web.archive.org/web/20230530002906/https://lnmp.org/download.html)|Not recommended to use|
| lnmp1.3-full.tar.gz (Older version, theoretically safe) | 478MB |a5aa55cd177cd9b9176ad697c12e45c0|[Webarchive20230430](https://web.archive.org/web/20230530002906/https://lnmp.org/download.html)|Not recommended to use|
| lnmp1.2-full.tar.gz (Older version, theoretically safe) | 312MB |b3d3d9e40395f4eb5e525adfaabfb675 |[Webarchive20230430](https://web.archive.org/web/20230530002906/https://lnmp.org/download.html)|Not recommended to use|
| lnmp1.1-full.tar.gz (Older version, theoretically safe) | 184MB |744d0155b8ebe4ae424578937a0cafac|[Webarchive20230430](https://web.archive.org/web/20230530002906/https://lnmp.org/download.html)|Not recommended to use|
| lnmp1.0-full.tar.gz (Older version, theoretically safe) | 134MB |e1127d65d93415c429010d6859353eea |[Webarchive20230430](https://web.archive.org/web/20230530002906/https://lnmp.org/download.html)|Not recommended to use|
| lnmp0.9-full.tar.gz (Older version, theoretically safe) | 61.83MB |0eb79ddd5cd1df3a487f62e7943aaa9d |[Webarchive20230430](https://web.archive.org/web/20230530002906/https://lnmp.org/download.html)|Not recommended to use|
| lnmp0.8-full.tar.gz (Older version, theoretically safe) | 80.25MB |Not Provided | - |
| lnmp0.7-full.tar.gz (Older version, theoretically safe) | 66.64MB | Not Provided | - |
| lnmp0.6-full.tar.gz (Older version, theoretically safe) | 50.56MB | Not Provided | - |
| lnmp0.5-full.tar.gz (Older version, theoretically safe) | 44.19MB | Not Provided | - |
| lnmp0.4-full.tar.gz | 44.2MB | Not Provided | - |
