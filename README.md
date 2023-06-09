# ddns-scripts_aliyun

#### 原版本百分号编码存在一些问题，会导致多出一些'0'字符。
#### 本版本替换为 [starsunyzl/ddns-scripts-alibabacloud](https://github.com/starsunyzl/ddns-scripts-alibabacloud/blob/main/usr/lib/ddns/update_alibabacloud_com.sh) 中的百分号编码实现，经测试可正常运行。

-----------------------------------------------------
适用于 OpenWRT/LEDE 自带DDNS客户端的阿里云更新脚本

依赖: ddns-scripts wget openssl-util

建议安装: luci-app-ddns


安装后在DDNS服务提供商一栏多出一个 aliyun.com。

详情见恩山论坛介绍帖 [适用于OpenWRT/LEDE自带DDNS功能的阿里云脚本，完美嵌入](http://www.right.com.cn/forum/thread-267501-1-1.html)
