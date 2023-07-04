# ✨ Mac OS 9.22 (on PowerBook G4)

{% hint style="warning" %}
核能预警:前方全程由手机进行记录，请自备护目镜🤭
{% endhint %}

开机，推入光盘，按下C键，就能看到Happy Mac<img src="../.gitbook/assets/huaji.png" alt="" data-size="line">

启动除了9.2之外和其他OS 9没有区别<img src="../.gitbook/assets/huaji.png" alt="" data-size="line">

![](https://wvbarchive-1310561333.cos.ap-hongkong.myqcloud.com/5505567339/f08aad8165380cd7c7eaf69aad44ad345b8281c2.jpg) ![](https://wvbarchive-1310561333.cos.ap-hongkong.myqcloud.com/5505567339/b2ebd9086b63f6245fef6d748b44ebf81b4ca308.jpg) ![](https://wvbarchive-1310561333.cos.ap-hongkong.myqcloud.com/5505567339/27fdae3c70cf3bc732b2999bdd00baa1cc112a08.jpg) ![](https://wvbarchive-1310561333.cos.ap-hongkong.myqcloud.com/5505567339/0b0f9cecab64034f9a3a9671a3c3793108551dc3.jpg)

启动之后，由于ROM版本的原因，分辨率会降至640\*480

不用担心，我们等会就能解决这个问题<img src="../.gitbook/assets/huaji.png" alt="" data-size="line">

![](https://wvbarchive-1310561333.cos.ap-hongkong.myqcloud.com/5505567339/1292b7170924ab185c42b64039fae6cd7a890b62.jpg)

由于这是Power Mac G4 QuickSilver的Software Install膜改而成，我们先要破解机型限制<img src="../.gitbook/assets/huaji.png" alt="" data-size="line">

将整个光盘的内容复制到另一个磁盘（我这里是HFS+的U盘），再将/软件安装程序/升级程序文件下的Welcome文件替换同目录下的IncompatHW，即可正常进行安装<img src="../.gitbook/assets/huaji.png" alt="" data-size="line">

![](https://wvbarchive-1310561333.cos.ap-hongkong.myqcloud.com/5505567339/4f47682542a7d9331bb8b504a14bd11372f001ae.jpg) ![](https://wvbarchive-1310561333.cos.ap-hongkong.myqcloud.com/5505567339/f6f45df23a87e9507d04a21b1c385343faf2b4af.jpg)

在格式化磁盘后，我们就可以开始安装了<img src="../.gitbook/assets/huaji.png" alt="" data-size="line">

安装程序的区别可以说是基本没有，除了中文

![](https://wvbarchive-1310561333.cos.ap-hongkong.myqcloud.com/5505567339/70ba421e95cad1c8058eac50733e6709c83d5181.jpg) ![](https://wvbarchive-1310561333.cos.ap-hongkong.myqcloud.com/5505567339/22249002918fa0ec10f3347a2a9759ee3c6ddb82.jpg) ![](https://wvbarchive-1310561333.cos.ap-hongkong.myqcloud.com/5505567339/89c917ce3bc79f3d5298b447b6a1cd11738b2945.jpg) ![](https://wvbarchive-1310561333.cos.ap-hongkong.myqcloud.com/5505567339/22249002918fa0ec10bf347a2a9759ee3c6ddb46.jpg) ![](https://wvbarchive-1310561333.cos.ap-hongkong.myqcloud.com/5505567339/01c0f00b304e251f35c0b48fab86c9177e3e5383.jpg) ![](https://wvbarchive-1310561333.cos.ap-hongkong.myqcloud.com/5505567339/3b3f6d47f21fbe094568936367600c338644ad8c.jpg) ![](https://wvbarchive-1310561333.cos.ap-hongkong.myqcloud.com/5505567339/2c75e70b19d8bc3e277356bd8e8ba61ea9d34547.jpg) ![](https://wvbarchive-1310561333.cos.ap-hongkong.myqcloud.com/5505567339/cb20d41d8701a18b7add4238922f07082938fe8d.jpg) ![](https://wvbarchive-1310561333.cos.ap-hongkong.myqcloud.com/5505567339/6d0187ff9925bc31df2751ef52df8db1ca137040.jpg)

安装过程中有两个包没装上，没关系，手动补<img src="../.gitbook/assets/huaji.png" alt="" data-size="line">

反正都是在软件安装程序里的<img src="../.gitbook/assets/huaji.png" alt="" data-size="line">

![](https://wvbarchive-1310561333.cos.ap-hongkong.myqcloud.com/5505567339/17d876dea9ec8a136cd40b97fb03918fa2ecc0f4.jpg) ![](https://wvbarchive-1310561333.cos.ap-hongkong.myqcloud.com/5505567339/36fd2c37acaf2eddff7a159e811001e938019337.jpg) ![](https://wvbarchive-1310561333.cos.ap-hongkong.myqcloud.com/5505567339/9d3036db81cb39db094b3b21dc160924aa183037.jpg) ![](https://wvbarchive-1310561333.cos.ap-hongkong.myqcloud.com/5505567339/d3e7d77fca8065384123f8649bdda144af3482f5.jpg) ![](https://wvbarchive-1310561333.cos.ap-hongkong.myqcloud.com/5505567339/65ebf2cbd1c8a78656a016796b09c93d71cf5030.jpg)

下面就是我们破解的时间了<img src="../.gitbook/assets/huaji.png" alt="" data-size="line">

首先我们要把较新的ROM（我的最低9.7.1）替换到硬盘上的系统文件夹中<img src="../.gitbook/assets/huaji.png" alt="" data-size="line">

我的ROM提取自我恢复盘恢复的OS 9英文<img src="../.gitbook/assets/huaji.png" alt="" data-size="line">

![](https://wvbarchive-1310561333.cos.ap-hongkong.myqcloud.com/5505567339/1976d5b6d0a20cf460e1a5a87a094b36adaf994d.jpg)

同时为了解决睡眠问题，我们还要把较新的ATI显卡扩展（如果是N卡那就是N扩展）丢进硬盘里<img src="../.gitbook/assets/huaji.png" alt="" data-size="line">

这个时候就可以重启了<img src="../.gitbook/assets/huaji.png" alt="" data-size="line">

![](https://wvbarchive-1310561333.cos.ap-hongkong.myqcloud.com/5505567339/49d7ba55564e9258533dc3999082d158cdbf4eb5.jpg)

重新启动，听一声悦耳的Duang，我们就会发现主题已经成了默认的灰色Quantum Foam<img src="../.gitbook/assets/huaji.png" alt="" data-size="line">

![](https://wvbarchive-1310561333.cos.ap-hongkong.myqcloud.com/5505567339/50cc3442fbf2b211d1cbc039c68065380ed78ed1.jpg) ![](https://wvbarchive-1310561333.cos.ap-hongkong.myqcloud.com/5505567339/8a7402390cd79123d0fbd003a1345982b3b780a7.jpg) ![](https://wvbarchive-1310561333.cos.ap-hongkong.myqcloud.com/5505567339/1976d5b6d0a20cf47e74bba87a094b36aeaf99d2.jpg)

启动就给我很积极地蹦出两个设置

话说苹果当年用15' 1280\*854的3:2屏幕可以说是真的很有勇气了<img src="../.gitbook/assets/huaji.png" alt="" data-size="line">

![](https://wvbarchive-1310561333.cos.ap-hongkong.myqcloud.com/5505567339/4a2505d8f2d3572c128cdbab8613632763d0c354.jpg)

终于能够成功走完一遍设置助理而不报错了<img src="../.gitbook/assets/huaji.png" alt="" data-size="line">

其实就是OOBE，也没有什么大的差别<img src="../.gitbook/assets/huaji.png" alt="" data-size="line">

![](https://wvbarchive-1310561333.cos.ap-hongkong.myqcloud.com/5505567339/92ef69f51bd5ad6e6f01239d8dcb39dbb4fd3cc6.jpg) ![](https://wvbarchive-1310561333.cos.ap-hongkong.myqcloud.com/5505567339/bb06d5109313b07e8b81167f00d7912396dd8cfa.jpg) ![](https://wvbarchive-1310561333.cos.ap-hongkong.myqcloud.com/5505567339/d1d7f0dca144ad341045c0f0dca20cf433ad85c0.jpg) ![](https://wvbarchive-1310561333.cos.ap-hongkong.myqcloud.com/5505567339/47fc4f391f30e9244f5edb4640086e061f95f7c1.jpg) ![](https://wvbarchive-1310561333.cos.ap-hongkong.myqcloud.com/5505567339/e8279a1e4134970aa186575899cad1c8a5865dc1.jpg) ![](https://wvbarchive-1310561333.cos.ap-hongkong.myqcloud.com/5505567339/92ef69f51bd5ad6e6cc2229d8dcb39dbb7fd3c87.jpg) ![](https://wvbarchive-1310561333.cos.ap-hongkong.myqcloud.com/5505567339/e8279a1e4134970aa04a565899cad1c8a6865d85.jpg) ![](https://wvbarchive-1310561333.cos.ap-hongkong.myqcloud.com/5505567339/1c9453a95edf8db1b1d93b130523dd54544e74c3.jpg) ![](https://wvbarchive-1310561333.cos.ap-hongkong.myqcloud.com/5505567339/03e20a234f4a20a450e87bb09c529822700ed0cc.jpg) ![](https://wvbarchive-1310561333.cos.ap-hongkong.myqcloud.com/5505567339/9da0314f9258d10933d8efc5dd58ccbf6d814d87.jpg)

值得一提的还有这个AirPort设置助理

由于网卡的局限性，现在有密码的WiFi这机子都不能连接，于是就出现了密码错误的这种蛇皮提示<img src="../.gitbook/assets/huaji.png" alt="" data-size="line">

![](https://wvbarchive-1310561333.cos.ap-hongkong.myqcloud.com/5505567339/1a5bc30e4bfbfbed66f5770874f0f736aec31f0a.jpg) ![](https://wvbarchive-1310561333.cos.ap-hongkong.myqcloud.com/5505567339/fccad63433fa828b2c5edc94f11f4134960a5ab9.jpg) ![](https://wvbarchive-1310561333.cos.ap-hongkong.myqcloud.com/5505567339/ca76de004a90f603ac1fdd303512b31bb151ed14.jpg) ![](https://wvbarchive-1310561333.cos.ap-hongkong.myqcloud.com/5505567339/2c75e70b19d8bc3e367447bd8e8ba61ea9d345ba.jpg) ![](https://wvbarchive-1310561333.cos.ap-hongkong.myqcloud.com/5505567339/c7b08cf91a4c510ffe6da36d6c59252dd52aa515.jpg)

值得一提的还有随光盘送的iTunes<img src="../.gitbook/assets/huaji.png" alt="" data-size="line">

这是唯一一个能在OS 9上播放正常MP3的播放器，同时作为随盘程序，我觉得还是可以看一下的<img src="../.gitbook/assets/huaji.png" alt="" data-size="line">

安装程序在光盘的应用文件夹中<img src="../.gitbook/assets/huaji.png" alt="" data-size="line">

安装程序倒没什么亮点<img src="../.gitbook/assets/huaji.png" alt="" data-size="line">

![](https://wvbarchive-1310561333.cos.ap-hongkong.myqcloud.com/5505567339/f243b7a30cf431ad8167004e4736acaf2fdd9801.jpg) ![](https://wvbarchive-1310561333.cos.ap-hongkong.myqcloud.com/5505567339/6e87ecd5b31c87014a03f1912b7f9e2f0608ff02.jpg) ![](https://wvbarchive-1310561333.cos.ap-hongkong.myqcloud.com/5505567339/bd0ec850f3deb48fe6dde2a9fc1f3a292cf57802.jpg) ![](https://wvbarchive-1310561333.cos.ap-hongkong.myqcloud.com/5505567339/50cc3442fbf2b211afcbc639c68065380ed78ed1.jpg) ![](https://wvbarchive-1310561333.cos.ap-hongkong.myqcloud.com/5505567339/678bf92e07082838eee89f63b499a9014e08f1d2.jpg)

重启打开后会有一个简单的设置<img src="../.gitbook/assets/huaji.png" alt="" data-size="line">然后就能开始BOOM了

界面很Brushed Metal，很OS X，但仍是原生OS 9应用，可见当时苹果有多嫌弃Platinum

![](https://wvbarchive-1310561333.cos.ap-hongkong.myqcloud.com/5505567339/8b1b11084b36acaf6245db8b70d98d1000e99c11.jpg) ![](https://wvbarchive-1310561333.cos.ap-hongkong.myqcloud.com/5505567339/fefd0c62f6246b6012aaff03e7f81a4c500fa212.jpg) ![](https://wvbarchive-1310561333.cos.ap-hongkong.myqcloud.com/5505567339/750e81cc7b899e51b42a77634ea7d933c9950d12.jpg) ![](https://wvbarchive-1310561333.cos.ap-hongkong.myqcloud.com/5505567339/4c0056accbef76090190d4e822dda3cc7dd99e27.jpg)

最后来一张关于本机<img src="../.gitbook/assets/huaji.png" alt="" data-size="line">

![](https://wvbarchive-1310561333.cos.ap-hongkong.myqcloud.com/5505567339/c0fe7ed9bc3eb135b076fbccaa1ea8d3fc1f440d.jpg)
