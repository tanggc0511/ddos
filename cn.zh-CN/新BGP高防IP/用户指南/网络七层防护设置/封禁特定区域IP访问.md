# 封禁特定区域IP访问 {#task_183076 .task}

区域封禁帮助您一键阻断来自指定地区（中国大陆省份、港澳台特别行政区、大洲）的来源IP的所有访问请求。该功能目前只针对指定域名生效。

使用区域封禁功能前，请确认您的网站域名已接入增强功能套餐的新BGP高防实例。

假设example.aliyundemo.com域名的正常用户均来自中国大陆（含港澳台特别行政区），您可以为example.aliyundemo.com域名配置区域封禁，封禁来自海外地区（亚洲，欧洲，北美洲，南美洲，非洲，大洋洲，南极洲）的访问请求。

**注意事项** 

-   区域封禁针对域名级别生效，如果您需要对多个不同网站域名进行区域封禁，则需要对不同域名分别进行设置，不支持对多个域名批量配置。
-   区域封禁根据源IP的归属区域在新BGP高防中识别过滤，并不能减小进入BGP高防网络的攻击流量。

1.  登录[云盾新BGP高防管理控制台](https://yundun.console.aliyun.com/?p=ddoscoo&__consolePageCode=ddoscoo)。
2.  定位到**防护** \> **防护设置** \> **CC防护策略**。
3.  选择需要设置区域封禁的域名（以example.aliyundemo.com为例），开启区域封禁开关。![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/156896/156091141544273_zh-CN.png)


4.  在区域封禁配置页面，单击**设置**，选择封禁区域。以下图中的配置为例，配置生效后，海外流量将无法访问到example.aliyundemo.com。![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/156896/156091141544274_zh-CN.png)


5.  选择区域后，单击**确定**，配置生效。

