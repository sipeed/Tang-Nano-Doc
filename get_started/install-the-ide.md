# Download

Go to the official website http://www.gowinsemi.com.cn/faq.aspx, you can see the software list below, select the version of the system suitable for the computer to download

<img src="../../assets/gowin_down.png" style="zoom: 50%;" />

# Installation

**Windows users:**

Double-click the downloaded exe installation file, select the installation language, installation location, click the next step to complete the installation.

Be sure to install the driver that prompts you to install when you complete the installation.

<img src="../../assets/gowin_install.png" style="zoom: 80%;" />

Check the installation driver and click Finish, the driver will be installed.

**Linux User:**

TODO

# License

Gao Yunyun source software requires a license to use, the current software license is provided free of charge, you can apply in [official website] (http://www.gowinsemi.com.cn/faq_view.aspx)

However, the way to apply on the official website is cumbersome. In order to facilitate development, you can use Gaoyun software through the sipeed license server.

There are currently two ways to license

**First: License server networking with sipeed (recommended)**

After downloading the software, the software will prompt you for a licence. Fill in the server address `50.116.30.241` in the pop-up box, IDE port: 10559

![](../../assets/lic_remote_1.png)

The activation of synopsys advanced functions requires adding the environment variable `LM_LICENSE_FILE=27020@50.116.30.241` to the system.

Windows User presses win+r on the keyboard, enter `cmd` in the pop-up window, click OK to pop up the black command line window, enter the following command

```
Setx LM_LICENSE_FILE 27020@50.116.30.241
```

Windows can be added in addition to the command line. You can also add it by right-clicking Computer->Properties->Environment Variables and then adding it as shown below.

<img src="../../assets/lic_remote_2.png" style="zoom: 60%;" />

**Linux** users need to add in `~/.bashrc`

```
Export LM_LICENSE_FILE 27020@50.116.30.241
```

After entering the IDE, click on `Synplify Pro` in Tools.

<img src="../../assets/lic_remote_3.png" style="zoom:67%;" />

Then the interface will pop up as shown below. At this time, you need to wait for a short time. After the license is initialized, you can use it.

<img src="../../assets/lic_remote_4.png" style="zoom:35%;" />

**Second: use a stand-alone license (need to modify the mac)**

TODO

# Instructions

Refer to the official documentation [Gowin Cloud Source Software User Guide] (http://cdn.gowinsemi.com.cn/SUG100-1.8_Gowin%E4%BA%91%E6%BA%90%E8%BD%AF%E4%BB%B6%E7%94%A8%E6%88%B7%E6%8C%87%E5%8D%97.pdf) , Chapter 5 Cloud Source Software Usage

# Reference document

+ [GoWin Software Introduction and Installation](http://cdn.gowinsemi.com.cn/%E9%AB%98%E4%BA%91%E8%BD%AF%E4%BB%B6%E7%AE%80%E4%BB%8B%E5%92%8C%E5%AE%89%E8%A3%85.pdf)

