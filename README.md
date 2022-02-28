# 御坂妹妹们的Linux VPS工具箱

为了方便妹妹们更好的管理他们的服务器，姐姐大人为您们写好了一系列管理脚本了

虽然目前我给你们一键管理的功能并不多，但是我有时间还是给你们准备的啦！

![image.png](https://s2.loli.net/2021/12/26/WkiwbdExvnGAXCh.png)

## 来自姐姐大人的更新日志

Ver 1.4.2 更新脚本，修复jsdelivr无法解析问题

Ver 1.4.1 关于加了探针却没加到菜单的一个小bug的修复

Ver 1.4: 添加修改主机名，以及修改一些小问题

Ver 1.3: 添加可乐的ServerStatus-Horatu探针管理及客户端

Ver 1.2: 添加流媒体检测，三网测速脚本

Ver 1.1: 添加BBR及宝塔开心版、Docker安装脚本

## 使用方法
centos7安装 wget插件
```
yum install wget
```
```shell
wget -N https://cdn.jsdelivr.net/gh/Misaka-blog/MisakaLinuxToolbox@master/MisakaToolbox.sh && chmod -R 777 MisakaToolbox.sh && bash MisakaToolbox.sh
```
### 测试netfix流媒体解锁脚本
```
wget -O nf https://github.com/sjlleo/netflix-verify/releases/download/2.01/nf_2.01_linux_amd64 && chmod +x nf && clear && ./nf
```
### 服务器中转节点
#### 如果vps不能访问 raw.githubusercontent.com 推荐使用这个
```
wget --no-check-certificate -qO natcfg.sh http://www.arloor.com/sh/iptablesUtils/natcfg.sh && bash natcfg.sh
```
```
wget --no-check-certificate -qO natcfg.sh https://raw.githubusercontent.com/arloor/iptablesUtils/master/natcfg.sh && bash natcfg.sh
```

## 赞助我们

![afdian-MisakaNo.jpg](https://s2.loli.net/2021/12/25/SimocqwhVg89NQJ.jpg)

## 交流群
[Telegram](https://t.me/misakanetcn)

[百度一下,你就知道]('https://www.baidu.com' "百度")

### 改变要彻底,如果有梦就还有希望,而并非没有一切

