
## 简单介绍

**pure-netsniff-ng**是一个纯净版的netsniff-ng。其对[原库](https://github.com/netsniff-ng/netsniff-ng)进行了删减和修改，仅保留了最基本的netsniff-ng**零拷贝抓包**等功能。

主要修改如下：

1. 保留了基本的pcap抓包和回放功能。
2. 删除了trafgen、mausezahn、ifpps、curvetun等模块
3. 修改了configure文件
4. 其他修改


## 安装步骤
1. `./configure`
2. `make`
3. `make install`

具体的可`./configure --help`或`make help`查询相应的帮助信息
安装时出现的依赖问题请参考**INSTALL**
