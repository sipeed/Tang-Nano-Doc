# 下载

进入官网 http://www.gowinsemi.com.cn/faq.aspx ，可以看到如下图的软件列表，选择适合电脑的系统的版本进行下载

![](../../assets/gowin_down.png)

# 安装

**Windows** 用户：

双击下载好的 exe 安装文件，选择安装语言、安装位置，鼠标点击下一步就可以完成安装了

完成安装时提示安装的驱动请务必安装

![](../../assets/gowin_install.png)

勾选安装驱动后点击完成后，就会进行驱动的安装

**Linux** 用户：

TODO

# license

高云云源软件需要 license 才能使用，目前软件的 license 是免费提供的，可以在[官网进行申请](http://www.gowinsemi.com.cn/faq_view.aspx)

不过在官网申请的方式比较麻烦，为了方便开发，可以通过 sipeed 的 licence 服务器使用高云软件

现目前有两种方式进行 license

**第一种：使用 sipeed 的 licence 服务器联网激活(推荐)**

下载好软件打开后，软件会提示需要 licence，在弹出框中填入服务器地址 `50.116.30.241` 即可，IDE端口：10559

![](../../assets/lic_remote_1.png)

synopsys 高级功能的激活需要在系统中添加环境变量 `LM_LICENSE_FILE=27020@50.116.30.241`

**Windows** 用户在键盘上按 win+r 键，在弹出的运行窗口输入 `cmd`，点击确定后会弹出黑色命令行窗口，在里面输入下面命令

```
setx LM_LICENSE_FILE 27020@50.116.30.241
```

Windows 除了命令行的方式添加，也可以通过 右键电脑->属性->环境变量 ，然后如下图进行添加

![](../../assets/lic_remote_2.png)

**Linux** 用户需要在 `~/.bashrc` 中添加

```
export LM_LICENSE_FILE 27020@50.116.30.241
```

进入 IDE 后，点击 Tools 中的 `Synplify Pro`

![](../../assets/lic_remote_3.png)

随后会弹出界面如下图，这时需要等待一小会，等 licence 初始化完毕就可以使用

![](../../assets/lic_remote_4.png)

**第二种：使用单机版 licence(需要修改mac)**

TODO

# 参考文档

+ [高云软件简介和安装](http://cdn.gowinsemi.com.cn/%E9%AB%98%E4%BA%91%E8%BD%AF%E4%BB%B6%E7%AE%80%E4%BB%8B%E5%92%8C%E5%AE%89%E8%A3%85.pdf)

