## CamelProxy代理服务器测试环境

*   地点：腾讯云位于广州的机房服务器
*   配置：2核CPU, 4G内存，4M固定外网带宽，windows 2008 R2 64位操作系统
*   版本：CamelProxy 64位 1.0.3

## 性能测试工具用例

用apache的工具ab, 模拟10个并发客户端，每个客户端请求10次，访问http://www.sohu.com/的主页面。

## 性能测试结果

得到如下截图数据，“用户直连访问” PK “用户通过CamelProxy代理转发”  
[![](https://camelproxy.wsworking.com/static/media/test_report.png)](/static/media/test_report.png)

通过对比“Percentage of the requests served within a certain time(ms)”，我们可以发现：通过CamelProxy代理访问和直接访问，访问响应速度损失非常小。