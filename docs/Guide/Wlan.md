# WLAN 无线网络连接

!!! Tip
    **主要介绍 Windows 7、Windows 10 自带无线设置**

## Windows 7 无线连接

- 首先按下图点开无线网络列表，选择 **GRG-Intranet** 或 **GRG-Intranet-5G**，点击连接

![](/imgs/wlan/lbiao.jpg)

- WiFi：GRG-Intranet，免密。点击连接即可。连接以后会自动弹出 http://10.1.253.2 网络认证界面，用户名：OA账号名，密码：域密码

![](/imgs/wlan/mima.jpg)

若网络连接如下图所示，即能正常连上公司 Wlan 无线网络。

![](/imgs/wlan/ok.jpg)

## Windows 10 无线连接

- 首先按下图点开无线网络列表，选择 GRG-Intranet/GRG-visitor，点击连接。

![](/imgs/wlan/win10.png)

- IE浏览器访问 [http://10.1.7.228:8080/am/portal/serviceId/SN190917612774/ac/H3C/ssid/GRG-Intranet](http://10.1.7.228:8080/am/portal/serviceId/SN190917612774/ac/H3C/ssid/GRG-Intranet) 进行网络认证,认证通过即可访问外网。

![](/imgs/wlan/rz.png)

- 若连接 WiFi：GRG-visitor，需要手机微信扫描一下二维码获取 WiFi 密码。

![](/imgs/wlan/WiFi.png)

- 手机获取的WiFi密码如下图。GRG-visitor 密码一天一改，第二天访问时先忘记前一天的密码.

![](/imgs/wlan/mima.png)

- 电脑上输入获取的WiFi密码即可连接 GRG-visitor 网络


## 园区内连接无线网络注意事项
连接无线网络搜索到 WiFi 时会有 GRG-Intranet 和 GRG-Intranet2
解决办法：

- Windows 10 的设置，点击WLAN，点击右边的管理已知网络

![](/imgs/wlan/wjmm.png)

- 进入后找到GRG-Intranet和GRG-Intranet2，点击忘记，然后再尝试连接GRG-Intranet（注意升级后GRG-Intranet连接为免密码连接）。

![](/imgs/wlan/wj.png)

- 若使用 grgit.com 或者 qq.com 等其他 http 不能重定向认证页面，使用以下链接尝试打开认证页面：
[http://10.1.7.228:8080/am/portal/serviceId/SN190917612774/ac/H3C/ssid/GRG-Intranet](http://10.1.7.228:8080/am/portal/serviceId/SN190917612774/ac/H3C/ssid/GRG-Intranet)

- 不能弹出认证页面或者手动输入认证页面地址后不能弹出认证页面的，
请检查DNS是否为自动获取，若不是，请改为自动获取。

- 若已认证后，还是不能正常上网，请检查 DNS 是否为自动获取，若不是，请改为自动获取。

## 温馨提示
1. 员工的上网账号是唯一的，不能同时在两台以上的设备登录。
