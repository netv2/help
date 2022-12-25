
<div align=center>
     <img src="linux/clashl/images/logo.webp" width = 100 />
</div>

> 电脑系统应为Ubuntu 18(GUI图形系统)及以上

> [!TIP] <!-- [!NOTE] [!TIP] [!WARNING] [!ATTENTION]-->
> 先自行尝试安装使用，如果实在操作不了，请求助客服

### 软件下载

> [下载地址1](http://110.42.178.197:5244/d/Cross%20Firewalls/CLASH/Clash.for.Windows-0.20.10-x64-linux.tar.gz.zip?sign=V5NfUbuQA1acfcjqq9_9B3tuWyBsaTx07tLIAw572mY=:0)
>
> [下载地址2](https://airnet.lanzoue.com/iiPzu0ifu6rc)

> [!WARNING] <!-- [!NOTE] [!TIP] [!WARNING] [!ATTENTION]-->
> 注意：本篇文档是未汉化前制作的，请自行对应操作步骤。

### 解压软件

<div align=center>
     <img src="linux/clashl/images/linux1.png" width = 100% />
</div>

### 启动软件

- 进入文件夹后，鼠标右键空白处，点击在终端打开

<div align=center>
     <img src="linux/clashl/images/linux2.png" width = 100% />
</div>

- 在终端中输入./cfw启动软件,电脑右上角状态栏呼出界面

<div align=center>
     <img src="linux/clashl/images/linux3.png" width = 100% />
</div>

### 导入订阅

- 回到官网：[【打开官网】](https://acc.netv2.top/)登录后点击复制订阅

<div align=center>
     <img src="linux/clashl/images/linux4.png" width = 100% />
</div>

- 返回到软件内，点击proflies[配置]，在最上方的粘贴好订阅，最后点击 download [下载]

<div align=center>
     <img src="linux/clashl/images/linux5.png" width = 100% />
</div>

- 成功后新的配置文件会显示，选中后它[选中后会有绿色标记]。

<div align=center>
     <img src="linux/clashl/images/linux6.png" width = 100% />
</div>

### 启动

- 1点击proxies[代理]，2展开节点，3选择Rule[规则]模式，4测试连通性，5选择一个节点

<div align=center>
     <img src="linux/clashl/images/linux7.png" width = 100% />
</div>

- 选择General [常规] 菜单，[start with linux] 启动系统代理

<div align=center>
     <img src="linux/clashl/images/linux8.png" width = 100% />
</div>








<!-- panels:start -->
<!-- div:title-panel -->

- 最后：1、打开设置，2网络，3网络代理，4手动，5，按照图片添加以下参数

<div align=center>
     <img src="linux/clashl/images/linux9.png" width = 100% />
</div>


<!-- div:left-panel -->

HTTP/HTTPS：
```
127.0.0.1
```

<!-- div:right-panel -->

端口：
```
7890
```

<!-- panels:end -->

忽略主机：

```
localhost;127.*;10.*;172.16.*;172.17.*;172.18.*;172.19.*;172.20.*;172.21.*;172.22.*;172.23.*;172.24.*;172.25.*;172.26.*;172.27.*;172.28.*;172.29.*;172.30.*;172.31.*;192.168.*
```











