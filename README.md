# nodesCatch
节点检查、测速和过滤工具
# 使用说明
使用软件则表示遵守软件的使用协议

软件视频演示：https://youtu.be/aSR6OuqtFdU

视频补充：

1. 一键自动测速的参数可以在测速的时候随时修改
2. 确保电脑安装了.net framework4.6及以上，否则软件无法运行
3. 测速期间不可以对节点列表进行删除、添加、排序等操作，否则会报错
4. 手动取消测速后需要等当前线程执行完成停止后再操作
5. 遇到无法解决的奇怪问题可以打开任务管理器结束clash.exe进程

基于v2rayN二次开发和基于Clash内核的一键全自动测速软件
本软件主要是从节点池中快速筛选出可用的节点，支持直接添加节点池的节点列表或者订阅链接
支持测速的协议：Shadowsocks、ShadowsocksR、Vmess、Trojan、socks5、http、https

本来想直接用Xray内核，但是Xray不支持SSR，由于目前还有很多SSR节点分享，所以换成了Clash内核
暂不支持Vless，因为Clash内核不支持Vless，而且节点池也没有Vless的节点分享

导入节点的方法：
订阅地址、节点池地址、右键粘贴（yaml格式、订阅格式、URL格式）

导出节点的方法：
右键复制URL、右键复制订阅内容

软件不会自动保存配置信息，请注意手动点击按钮保存配置信息

软件包内的Clash是64位，如果是32位的系统请前往github下载32位版本的Clash

## 转载自[不良林的频道](https://www.youtube.com/channel/UCbCCUH8S3yhlm7__rhxR2QQ)
