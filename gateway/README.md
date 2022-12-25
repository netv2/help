# Switch 游戏机


> [!TIP] <!-- [!NOTE] [!TIP] [!WARNING] [!ATTENTION]-->
> 使用网关模式，可以达到类似路由器的效果，让整个网关下的所有设备都能够使用节点网络
前提是设备在他同一个WIFI网络下。
> 不止于Switch，类似Xbox，PS4等，也可以使用本方法尝试连接。

- 以下举例4个平台的软件设置方法，其他软件也大同小异

<!-- tabs:start -->

#### **Clash for Windows**

- 打开允许局域网连接。记住端口为7890

<div align=center>
     <img src="gateway/images/w1.png" width = 100% />
</div>

- 查询路由分配给你电脑本机的IP地址

<div align=center>
     <img src="gateway/images/w2.png" width = 60% />
</div>

- 那么就知道了本台机器的服务器地址是192.168.0.135端口7890

#### **Clash for Android**

- 首先打开软件点击设置，覆写。设置HTTP端口例如设置为1234，设置允许来自局域网的连接为已启用

<div align=center>
     <img src="gateway/images/a1.png" width = 60% />
</div>

- 查询路由分配给你手机本机的IP地址

<div align=center>
     <img src="gateway/images/a2.png" width = 60% />
</div>

- 这样就知道了服务器地址为192.168.1.115端口1234

#### **Clash X**

打开允许局域网连接。HTTP端口为7890

<div align=center>
     <img src="gateway/images/x1.png" width = 50% />
</div>

- 设置，网络

<div align=center>
     <img src="gateway/images/x2.png" width = 90% />
</div>

- 这样就知道了服务器地址为192.168.0.106端口7890

#### **Shadowrocket**

- 打开shadowrocket，点击设置，代理，代理共享

<div align=center>
     <img src="gateway/images/s1.png" width = 60% />
</div>

- 打开启用共享，就知道了服务器地址为192.168.1.122端口为1082

<!-- tabs:end -->

> [!TIP] <!-- [!NOTE] [!TIP] [!WARNING] [!ATTENTION]-->
> 提示：switch游戏机等设备需要和上述的电脑手机在同一个WIFI网络下才行。


打开Switch或者其他需要联网的设备，找到WIFI，点击进入详情，找到HTTP/HTTPS代理，选择手动，然后将上述的服务器地址和端口填入，连接WIFI后就可以了

> [!ATTENTION] <!-- [!NOTE] [!TIP] [!WARNING] [!ATTENTION]-->
> 注意：如果设备WIFI设置里没有此项，那就无能为力了。

<div align=center>
     <img src="gateway/images/switch1.png" width = 100% />
</div>