# Mac OS X Public Beta

这是苹果首个向公众发布的OS X，定价$29.95（乔帮主还真会坑钱），旨在给开发者和极客们看看全新的系统长什么样<img src="../.gitbook/assets/yinxian.png" alt="" data-size="line">

这是苹果首次向公众发布Aqua DE和Darwin内核，所以名义上这才是OS X的首个发行版本<img src="../.gitbook/assets/huaji.png" alt="" data-size="line">

![](https://wvbarchive-1310561333.cos.ap-hongkong.myqcloud.com/5505567339/eb90644e78f0f7368b635bc20155b319e9c4134c.jpg)

我使用事先备好的脚本启动QEMU<img src="../.gitbook/assets/huaji.png" alt="" data-size="line">

![](https://wvbarchive-1310561333.cos.ap-hongkong.myqcloud.com/5505567339/43bb1ff1f736afc35c9128a6b819ebc4b545124c.jpg) ![](https://wvbarchive-1310561333.cos.ap-hongkong.myqcloud.com/5505567339/38049037afc379312cf591eae0c4b74541a9114c.jpg)

鬼畜的Happy Mac......

![](https://wvbarchive-1310561333.cos.ap-hongkong.myqcloud.com/5505567339/b7c2c8c279310a5594b9c937bc4543a98026104c.jpg)

可见这里还是有一些OS 9的痕迹的<img src="../.gitbook/assets/huaji.png" alt="" data-size="line">

![](https://wvbarchive-1310561333.cos.ap-hongkong.myqcloud.com/5505567339/ef371e300a55b319c36495b648a98226cdfc174c.jpg)

苹果菜单中置......这应该是Public Beta最大的一个特点<img src="../.gitbook/assets/huaji.png" alt="" data-size="line">

![](https://wvbarchive-1310561333.cos.ap-hongkong.myqcloud.com/5505567339/c6ec517bdab44aed15b4a827b81c8701a38bfb74.jpg) ![](https://wvbarchive-1310561333.cos.ap-hongkong.myqcloud.com/5505567339/768ebdb54aed2e73b71390ef8c01a18b85d6fa74.jpg) ![](https://wvbarchive-1310561333.cos.ap-hongkong.myqcloud.com/5505567339/9a402dec2e738bd48edba4f2aa8b87d6257ff974.jpg) ![](https://wvbarchive-1310561333.cos.ap-hongkong.myqcloud.com/5505567339/0a1949728bd4b31cb9c682788cd6277f9c2ff874.jpg) ![](https://wvbarchive-1310561333.cos.ap-hongkong.myqcloud.com/5505567339/6e87ecd5b31c87019e4ca4252c7f9e2f0508ff74.jpg) ![](https://wvbarchive-1310561333.cos.ap-hongkong.myqcloud.com/5505567339/cb20d41d8701a18bc711048c952f07082a38fe74.jpg) ![](https://wvbarchive-1310561333.cos.ap-hongkong.myqcloud.com/5505567339/f3e8e000a18b87d666b8bddc0c0828381d30fd74.jpg) ![](https://wvbarchive-1310561333.cos.ap-hongkong.myqcloud.com/5505567339/c7f5c68a87d6277fdce824fb23381f30eb24fc74.jpg)

安装程序的思路还是一样的，但是漂亮多了<img src="../.gitbook/assets/huaji.png" alt="" data-size="line">

![](https://wvbarchive-1310561333.cos.ap-hongkong.myqcloud.com/5505567339/e17fe0d7277f9e2f44cf0bcb1430e924ba99f374.jpg)

pppppp......panic?!!!!!

![](https://wvbarchive-1310561333.cos.ap-hongkong.myqcloud.com/5505567339/dedb600928381f30ad389d6aa2014c086c06f0c1.jpg)

仔细看了下，Macintosh Garden上还有个ReadMe，里面提到了这货居然有个时间炸弹......

如果要改时间的话，需要一个已经存在的OS X才可以调时间<img src="../.gitbook/assets/pen.png" alt="" data-size="line">

<figure><img src="https://wvbarchive-1310561333.cos.ap-hongkong.myqcloud.com/5505567339/dea568b20f2442a7d6f6e066da43ad4bd3130269.jpg" alt=""><figcaption></figcaption></figure>

所以我将实体机时间调了，不知道行不行<img src="../.gitbook/assets/huaji.png" alt="" data-size="line">

![](https://wvbarchive-1310561333.cos.ap-hongkong.myqcloud.com/5505567339/edc03e83b2b7d0a299ee1b5ec0ef760949369ac7.jpg)

成功！<img src="../.gitbook/assets/huaji.png" alt="" data-size="line">

![](https://wvbarchive-1310561333.cos.ap-hongkong.myqcloud.com/5505567339/91fdd4df9c82d15800db47728b0a19d8be3e4289.jpg)

完结撒花，拔盘开机<img src="../.gitbook/assets/huaji.png" alt="" data-size="line">

![](https://wvbarchive-1310561333.cos.ap-hongkong.myqcloud.com/5505567339/191a5a6c55fbb2fb1a8241d1444a20a44423dcb9.jpg) ![](https://wvbarchive-1310561333.cos.ap-hongkong.myqcloud.com/5505567339/7d9932fab2fb431637b663b92ba446230bf7d3b9.jpg) ![](https://wvbarchive-1310561333.cos.ap-hongkong.myqcloud.com/5505567339/150fd5fa43166d2214de0c574d2309f79252d2b9.jpg)

这一切都很鬼畜啊......我有点方，就如同我第一次看到Vista三点一样😂

***

事实上前几次的问题都是因为BIOS时间，使用`-rtc`参数就可以更改BIOS时间拆掉炸弹<img src="../.gitbook/assets/huaji.png" alt="" data-size="line">

所以最终命令如下<img src="../.gitbook/assets/huaji.png" alt="" data-size="line">

![](https://wvbarchive-1310561333.cos.ap-hongkong.myqcloud.com/5505567339/9596e234e5dde711f715068babefce1b9f1661f9.jpg)

{% code title="qemu.command" overflow="wrap" lineNumbers="true" fullWidth="false" %}
```bash
#!/bin/bash
cd "$(dirname "$0")"

./qemu-system-ppc -boot c -rtc base=2000-12-01,clock=vm -M mac99 -cpu G4 -m 1024 -prom-env "vga-ndrv?=true" -hda ./6G_10.5.img -cdrom /Volumes/Macintosh\ HDD/MacOSXPublicBeta.iso
```
{% endcode %}

不过我实在不理解的是，为什么苹果要给一个居然要付费的Beta设炸弹......

![](https://wvbarchive-1310561333.cos.ap-hongkong.myqcloud.com/5505567339/b6d00c610c338744cd8968015d0fd9f9d62aa070.jpg)

Happy Mac超级鬼畜<img src="../.gitbook/assets/huaji.png" alt="" data-size="line">👎

![](https://wvbarchive-1310561333.cos.ap-hongkong.myqcloud.com/5505567339/2b946b328744ebf83d3d2342d5f9d72a6159a770.jpg) ![](https://wvbarchive-1310561333.cos.ap-hongkong.myqcloud.com/5505567339/4cc7e045ebf81a4c797eabb4db2a6059242da670.jpg)

事实上，这个苹果标根本就是个装饰<img src="../.gitbook/assets/yinxian.png" alt="" data-size="line">

![](https://wvbarchive-1310561333.cos.ap-hongkong.myqcloud.com/5505567339/c7b08cf91a4c510ff088a5676c59252dd52aa570.jpg) ![](https://wvbarchive-1310561333.cos.ap-hongkong.myqcloud.com/5505567339/ab0c7d4d510fd9f9fd5b1214292dd42a2934a470.jpg) ![](https://wvbarchive-1310561333.cos.ap-hongkong.myqcloud.com/5505567339/5ab8360ed9f9d72a4b285760d82a2834359bbb70.jpg) ![](https://wvbarchive-1310561333.cos.ap-hongkong.myqcloud.com/5505567339/11fbbef8d72a6059095ca6672434349b023bba70.jpg) ![](https://wvbarchive-1310561333.cos.ap-hongkong.myqcloud.com/5505567339/990db02b6059252df95b5a79389b033b5ab5b970.jpg) ![](https://wvbarchive-1310561333.cos.ap-hongkong.myqcloud.com/5505567339/97de0758252dd42a064546d60f3b5bb5c8eab870.jpg) ![](https://wvbarchive-1310561333.cos.ap-hongkong.myqcloud.com/5505567339/20ad422cd42a28341bea717657b5c9ea14cebf70.jpg)

安装程序一直到10.2都没变过<img src="../.gitbook/assets/yinxian.png" alt="" data-size="line">到10.3和10.4只换了个背景图<img src="../.gitbook/assets/huaji.png" alt="" data-size="line">

![](https://wvbarchive-1310561333.cos.ap-hongkong.myqcloud.com/5505567339/745c39de8db1cb1333027a6ed154564e93584b5d.jpg) ![](https://wvbarchive-1310561333.cos.ap-hongkong.myqcloud.com/5505567339/f3efd750f8198618de16a8f946ed2e738ad4e674.jpg) ![](https://wvbarchive-1310561333.cos.ap-hongkong.myqcloud.com/5505567339/e3381bd88d1001e96e595372b40e7bec55e7975f.jpg)

可以发现此处进度条下的字体仍然是OS 9默认样式

![](https://wvbarchive-1310561333.cos.ap-hongkong.myqcloud.com/5505567339/b32ad38e8c5494ee8088486421f5e0fe98257e1e.jpg) ![](https://wvbarchive-1310561333.cos.ap-hongkong.myqcloud.com/5505567339/411d5e00213fb80e218126aa3ad12f2eb8389474.jpg)

事实上，这个Assistant的样式基本就是Classic Mac OS的Assistant加上Aqua设计而已<img src="../.gitbook/assets/yinxian.png" alt="" data-size="line">

![](https://wvbarchive-1310561333.cos.ap-hongkong.myqcloud.com/5505567339/0a649102738da977da4ac156bc51f8198718e358.jpg) ![](https://wvbarchive-1310561333.cos.ap-hongkong.myqcloud.com/5505567339/ec5b49dca3cc7cd9d87d73a43501213fb90e9174.jpg) ![](https://wvbarchive-1310561333.cos.ap-hongkong.myqcloud.com/5505567339/792fd1fc5266d016b07cd9559b2bd40734fa355f.jpg) ![](https://wvbarchive-1310561333.cos.ap-hongkong.myqcloud.com/5505567339/ca76de004a90f60392d5db3a3512b31bb151ed58.jpg)

这里的Email其实可以跳过，并且在后面的版本中被砍掉了

![](https://wvbarchive-1310561333.cos.ap-hongkong.myqcloud.com/5505567339/d53eb6c9a786c917e8531544c53d70cf3ac75774.jpg) ![](https://wvbarchive-1310561333.cos.ap-hongkong.myqcloud.com/5505567339/bb19cc65034f78f02683dc8e75310a55b2191c3c.jpg) ![](https://wvbarchive-1310561333.cos.ap-hongkong.myqcloud.com/5505567339/eb90644e78f0f7367d760a7c0655b319eac4133c.jpg)

![](https://wvbarchive-1310561333.cos.ap-hongkong.myqcloud.com/5505567339/f9f52d91f603738d610fb55fbf1bb051f919ec78.jpg)

又一zz设计：OOBE完后重启

![](https://wvbarchive-1310561333.cos.ap-hongkong.myqcloud.com/5505567339/0a649102738da977f06a3f56bc51f8198718e378.jpg)

这里仍然是浓浓的BSD味道，参见我的[Rhapsody教程](../rhapsody.md)<img src="../.gitbook/assets/huaji.png" alt="" data-size="line">

![](https://wvbarchive-1310561333.cos.ap-hongkong.myqcloud.com/5505567339/b6f7148ca977391279633c1cf4198618377ae278.jpg)

这里可以看到有好多应用仍然没有开发完全，包括设置<img src="../.gitbook/assets/yinxian.png" alt="" data-size="line">

![](https://wvbarchive-1310561333.cos.ap-hongkong.myqcloud.com/5505567339/3379ce763912b31b7b2974548a18367adbb4e178.jpg)

并且Public Beta是真的没有苹果菜单，后来苹果菜单的内容现在在Finder中<img src="../.gitbook/assets/pen.png" alt="" data-size="line">

![](https://wvbarchive-1310561333.cos.ap-hongkong.myqcloud.com/5505567339/e9835e13b31bb05134610a553a7adab44bede078.jpg)

此时Finder的名字还没有出现在顶栏上，所以关于页面也还是Mac标<img src="../.gitbook/assets/huaji.png" alt="" data-size="line">

![](https://wvbarchive-1310561333.cos.ap-hongkong.myqcloud.com/5505567339/79e6d41ab051f8194b60ba37d6b44aed2f73e778.jpg) ![](https://wvbarchive-1310561333.cos.ap-hongkong.myqcloud.com/5505567339/f3efd750f8198618f80256f946ed2e738ad4e678.jpg)

可以看到其实整个系统都Aqua化了，这点倒是要好评<img src="../.gitbook/assets/huaji.png" alt="" data-size="line">

![](https://wvbarchive-1310561333.cos.ap-hongkong.myqcloud.com/5505567339/f0a59f188618367a15ccc6a022738bd4b21ce578.jpg)

Classic此时还是一个单独的应用<img src="../.gitbook/assets/huaji.png" alt="" data-size="line">

![](https://wvbarchive-1310561333.cos.ap-hongkong.myqcloud.com/5505567339/b8ede119367adab49a95a23e87d4b31c8601e478.jpg)

神奇的GrabBag，在后来的版本就消失了这个目录了，这些应用也都被移出来了

![](https://wvbarchive-1310561333.cos.ap-hongkong.myqcloud.com/5505567339/c6ec517bdab44aedff0b0799bf1c8701a08bfb78.jpg)

Key Caps仍然Carbon化差评<img src="../.gitbook/assets/yinxian.png" alt="" data-size="line">

![](https://wvbarchive-1310561333.cos.ap-hongkong.myqcloud.com/5505567339/4fd025a6d933c8957a872006dd1373f0800200c3.jpg)

此时iTunes还没有被预装（

![](https://wvbarchive-1310561333.cos.ap-hongkong.myqcloud.com/5505567339/0253be32c895d143018f5c5e7ff0820258af07c3.jpg)

这里仍然是拨号连接，浓浓的时代感啊<img src="../.gitbook/assets/huaji.png" alt="" data-size="line">

![](https://wvbarchive-1310561333.cos.ap-hongkong.myqcloud.com/5505567339/99c7af94d143ad4b7cd7febd8e025aafa60f06c3.jpg)

例行推销QuickTime Pro（

![](https://wvbarchive-1310561333.cos.ap-hongkong.myqcloud.com/5505567339/8861b642ad4bd113dd340f4f56afa40f49fb05c3.jpg)

Brushed Metal吼评<img src="../.gitbook/assets/huaji.png" alt="" data-size="line">

![](https://wvbarchive-1310561333.cos.ap-hongkong.myqcloud.com/5505567339/91b7ca4ad11373f02dc6d7e2a80f4bfbf9ed04c3.jpg)

如果尝试打开设置的话，就会提示错误<img src="../.gitbook/assets/pen.png" alt="" data-size="line">

![](https://wvbarchive-1310561333.cos.ap-hongkong.myqcloud.com/5505567339/edbfb61273f08202ea6b294247fbfbeda9641bc3.jpg) ![](https://wvbarchive-1310561333.cos.ap-hongkong.myqcloud.com/5505567339/91e714f182025aaf15cbc6b6f7edab64014f1ac3.jpg) ![](https://wvbarchive-1310561333.cos.ap-hongkong.myqcloud.com/5505567339/3304e5035aafa40ff93f76a0a764034f7af019c3.jpg)

此时的IE同样也是Beta，图标差评<img src="../.gitbook/assets/pen.png" alt="" data-size="line">

![](https://wvbarchive-1310561333.cos.ap-hongkong.myqcloud.com/5505567339/c2f63daea40f4bfb482926290f4f78f0f53618c3.jpg) ![](https://wvbarchive-1310561333.cos.ap-hongkong.myqcloud.com/5505567339/1a5bc30e4bfbfbed1fa08e0274f0f736adc31fc3.jpg)

不知道苹果是怎么想的，把关机设在注销的旁边，还得通过注销进入<img src="../.gitbook/assets/pen.png" alt="" data-size="line">

Public Beta，完<img src="../.gitbook/assets/huaji.png" alt="" data-size="line">🌹
