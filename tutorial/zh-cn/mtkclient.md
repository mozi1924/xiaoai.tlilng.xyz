# mtkclient刷机，备份，解锁教程

## 本教程由[mozi1924](http://www.coolapk.com/u/8793429)编写

------------------------------

># 提前准备

要刷的设备

数据线

mtkclient软件(推荐mtkclient2.0工具里面有)

usbdk驱动

---------

1.首先安装usbdk,前往usbdk[官方仓库](https://github.com/daynix/UsbDk/releases)下载

如果连不上可以在网站主页的驱动文件夹下载

下载时你会看到这两个版本：

<img decoding="usbdk" src="../d/.picture/usbdk.png" width=300px>

选择合适你电脑的版本，如果你的电脑处理器是32位就选x86，64位就选x64

下载后安装重启即可
> # 1.连接

打开软件

将数据线接到电脑上

> 连接音箱：

>小屏设备

按住顶部三键并插入数据线即可，如下图：

<img decoding="lx04threebutton" src="../d/.picture/lx04threebutton.png" width="50%">

> 大屏设备

大屏设备因功率大，有独立电源，所以隐藏了micro-usb,扣开底部胶垫你会看到micro-usb接口，如图：

<img decoding="microusb" src="../d/.picture/microusb.png" width="500px">

插入数据线，随后按住三按键，连接电源

连接成功后软件界面如图：

<img decoding="mtkclient" src="../d/.picture/mtkclient.png" width="500px">

----

> # 2.刷机
进入写分区，如图：

<img decoding="write" src="http://disk.tlilng.xyz/d/guest/.picture/write.png" width="500px">

点击从目录选择，选择解压后的备份包，然后点击写分区，等跑完进度条就可以断电重启了

> # 2.备份

进入读分区，点击选择所有分区，然后点击旁边的读分区，选择一个目录保存，等跑完条即可

> # 3.解锁

进入flash工具页面，如图：

<img decoding="mtkclientflashtool" src="../d/.picture/mtkclientflashtool.png" width="500px">

点击下面的解锁bootloader等跑完进度条即可(一般是瞬间完成)