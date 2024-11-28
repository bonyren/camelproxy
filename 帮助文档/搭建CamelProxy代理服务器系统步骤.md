### 1.选择服务器环境

如果CamelProxy代理服务器部署在内网，一台能访问Internet，安装了Windows操作系统的计算机都可以。

如果CamelProxy代理服务器部署在云端，比如阿里云，腾讯云等，则推荐操作系统Windows 2003 server以上，64位版本，硬件为1核CPU, 2G内存，2M外网带宽以上配置。

### 2.下载安装

访问CamelProxy下载中心下载针对版本，部署服务器为64位操作系统请优先下载64位版本，32位操作系统则必须下载32位版本。

下载成功后，双击执行安装程序。
### 3.防火墙/安全组配置

CamelProxy默认"8089"为代理转发端口。 如果部署在内网，则内网防火墙要允许通过TCP/UDP 8089端口访问CamelProxy。

如果部署在云端，则安全组策略要允许“公网入方向”TCP/UDP 8089端口访问。

### 4.CamelProxy系统配置

双击桌面CamelPorxy控制台快捷图标
继续创建代理用户帐号，默认为了安全，CamelProxy不允许匿名访问，所以需要首先创建代理用户帐号。
![输入图片说明](https://images.gitee.com/uploads/images/2022/0301/153812_be9c85a2_10482337.png "camelproxyui_realtime.png")