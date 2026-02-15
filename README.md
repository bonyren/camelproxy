## 系统简介
“CamelProxy”是一款网络代理服务器的软件解决方案。其主要功能体现在:

- 代理共享上网
- 上网行为管理
- 内网安全防护
- 访问链路跳转

局域网内只要一台计算机可以上网，其他计算机就可以通过该计算机代理上网，减少硬件费用和上网开支；通过CamelProxy内置的帐号，访问权限，访问日志功能进行上网权限管理和上网行为审计，可以有效提升企业员工的工作效率和企业的信息安全管理水平；代理上网只会对外暴露代理服务器的地址，可以有效的防护内网内其他计算机的安全；代理服务器可以改变默认网络传输路径，主动跨越到目的资源的网络瓶颈节点。

它同时支持HTTP, Sock5等代理协议，系统具有高性能/大容量/高并发，运行稳定，部署简便，使用友好等特点。企业和组织可以使用CameProxy快速搭建出自己的代理服务器系统。

Microsoft Store下载地址：[https://apps.microsoft.com/detail/xp99jfn2s4dfgm](https://apps.microsoft.com/detail/xp99jfn2s4dfgm)

## 适用的典型场景
- 公司组织因为信息安全等原因，内部电脑平时不允许直接访问外部互联网。但某些场景通过审批，可以访问外部资源。这就需要一个能够连接互联网的电脑作为代理服务器，并安装部署本代理软件，其他电脑通过该代理服务器转发即可实现。
- 当你玩国外的网络资源，比如玩服务器在国外的游戏，由于数据要经过公共的国际网关，网速会大幅下降，不能满足需求体验。此时可以在云计算厂商（阿里云，腾讯云，华为云...）的香港机房购买云主机，然后部署本代理软件，本机电脑通过该代理访问国外资源。
- 当你的公司在国外设置分支机构，国外的工作人员需要访问服务器在国内的公司软件系统时，由于要经过国际网关，网速会卡顿。此时也可以在香港机房部署云主机和本软件，国外电脑通过代理访问国内资源。

## 系统的优势特点

### 高性能/大容量/高并发
![高性能/大容量/高并发](https://foruda.gitee.com/images/1732694247548848935/65c8465e_10482337.png "efficiency.png")
CamelProxy的网络IO转发引擎采用了Windows平台最高效的IO模型，结合C++语言高效，富有技巧的实现，使之网络IO性能速度达到同类软件中领先的水平。同时多年服务端高性能系统开发经验的应用，使之CPU，内存等资源占用率极低。在代理服务器带宽充足的条件下，从终端用户的角度来看，无法察觉访问其访问是否经过了代理服务器转发。
### 运行可靠稳定
![运行可靠稳定](https://foruda.gitee.com/images/1732694277937779633/6654643e_10482337.png "stable.png")
CamelProxy经历了严格测试，可以适应各种网络环境，做到长时间，无间断的稳定运行。同时做了很多系统的安全防护和加固，可以有效的识别和应对网络攻击。在设计阶段，我们就将软件长航时运行作为产品稳定性的一个重要的指标，设计了一套服务该指标的保障体系。在实现阶段，我们在CPU, 内存，IO等使用上，精益求精，既将系统的潜能发挥到极致，又确保系统的稳固可靠。
### 部署简单/使用友好
![部署简单/使用友好](https://foruda.gitee.com/images/1732694300550999509/8d99534c_10482337.png "friendly.png")
CamelProxy具备“一次安装，日常运行无须干预”的运作模式，它采用Windows后台服务的形式，跟随操作系统启动而自动运行。同时它的管理控制台采用Web模式呈现，既支持代理服务器本机浏览器访问，也支持远程，手机操控。可以随时随地，非常方便对代理服务器进行管理。

## 系统界面概览

![CamelProxy软件界面](https://images.gitee.com/uploads/images/2022/0301/154153_8d2b8c58_10482337.png "CamelProxy软件界面")
![CamelProxy软件界面-设置](https://images-eds-ssl.xboxlive.com/image?url=4rt9.lXDC4H_93laV1_eHM0OYfiFeMI2p9MWie0CvL99U4GA1gf6_kayTt_kBblFwHwo8BW8JXlqfnYxKPmmBXxyIKOooLGpN284TAU4S7.4CyO6FSPiG_s_BaYEuDiotV8R6zLR8GGoH2K7LoBMUgDFaMdHebmsBS.8RY3Dh.o-&format=source "CamelProxy软件界面-设置")

![CamelProxy软件界面-报警](https://images-eds-ssl.xboxlive.com/image?url=4rt9.lXDC4H_93laV1_eHM0OYfiFeMI2p9MWie0CvL99U4GA1gf6_kayTt_kBblFwHwo8BW8JXlqfnYxKPmmBXxyIKOooLGpN284TAU4S78K0tDG5wpkT.mCpBO4J5vxZDnfKIJfKbrt0BPXbkEOlVplUkN2tDTCeA4HzsrT748-&format=source "CamelProxy软件界面-报警")

![CamelProxy软件界面-日志](https://images-eds-ssl.xboxlive.com/image?url=4rt9.lXDC4H_93laV1_eHM0OYfiFeMI2p9MWie0CvL99U4GA1gf6_kayTt_kBblFwHwo8BW8JXlqfnYxKPmmBXxyIKOooLGpN284TAU4S79VuyYYOyrazKUM.jusZbsMjsh93NCaOlEBvIqN6PmyP3Hy7WQdGg1TbrkHNchSI0E-&format=source "CamelProxy软件界面-日志")

## 系统的组成

CamelProxy是一个单纯的高效代理服务器系统。

同时支持HTTP和SOCK5代理协议。提供32位和64位版本，用户可以根据自己的服务器环境来针对性的下载。安装完成后，代理引擎以Windows系统服务的方式运行，会跟随Windows系统的启动而自动运行，无需用户的干预；


## 系统环境要求

CamelProxy目前只支持Windows平台，提供32位和64位的版本，用户可以根据自己的服务器系统环境进行下载，一般目前服务器Windows系统都过渡到64位了。32位的版本可以在32位和64位操作系统都能运行，64位版本只能在64位系统运行，在64位系统安装使用64位程序会获得更高的性能表现。目前支持的主流操作系统版本如下：  
Windows Server 2003, 2008, 2012, 2016系列； Windows xp, 7, 8, 10, 11系列；

## 下载

在CamelProxy官方站点[下载中心](https://camelproxy.wsworking.com/download)下载就可以。

Microsoft Store下载地址：[https://apps.microsoft.com/detail/xp99jfn2s4dfgm](https://apps.microsoft.com/detail/xp99jfn2s4dfgm)

## 安装

安装很简单，一步步Next就可以了。

## 升级维护

CamelProxy支持自动升级，当官方有新版本发布时，用户都会得到提示，运行自动更新程序完成系统的升级。

## 配置

CamelProxy代理转发默认监听端口号是8089，如果代理服务器处的的环境启用了防火墙服务，则需要将8089加入允许TCP，UDP连接的防火墙配置规则中。

## 工作模式

*   浏览器->CamelProxy->目标站点资源  
    ![](https://camelproxy.wsworking.com/static/media/model1_release.png)
