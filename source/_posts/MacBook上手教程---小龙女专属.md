---
title: 小龙女MacBook专属教程
date: 2021-05-10 22:08:11
cover: https://file-1256865446.cos.ap-guangzhou.myqcloud.com/img/1625711233832-t01f000fe3220d040fe.jpg
tags: 
- Mac
- 教程
- 小龙女专属
categories:
- 工具使用
- 小龙女专属
---
 
> 这篇mac系统教程是专属于小龙女而写的，目的是为了让她能快速上手，当然了，手把手教学的效果最好了:)，但是毕竟不在身边，只能言传，不能身教。以下会分为3个篇章介绍，分别为硬件篇、系统篇、软件篇，我会尽可能的详细介绍。也希望小龙女能看着文章，一步步的动手操作，这样效果更好。ok~那我们就开始吧~~

# 硬件篇


## 初识MackBook
> 苹果公司为自己的一系列电脑（包括 iMac、Mac mini、Macbook、Mac Pro 等）取的名字统称 Mac。Mac 用的专属操作系统叫 macOS（WWDC16上，OS X 正式更名为 macOS）

**总结：Mac = 苹果电脑，macOS = 苹果电脑系统**

### 常用的快捷键

在一些 Apple 自己的键盘上，通常顶行中会有特殊按键，有音量图标、显示屏亮度图标和其他功能图标。按图标键可执行相应功能，或将其与 Fn 键组合使用来用作 F1、F2、F3 或其他标准功能键。

#### 空格（space）键
这是一个神奇的按键。在Mac系统里，几乎所有文件都可以直接用空格键快速查看预览。如视频、图片、音乐、页面、文档、PDF等等。拿图片举例，只要点选文件夹里某张图片，点击空格键就打开了，再点击上下左右键可切换浏览其他图片。而不用每次都双击打开，再关闭，再双击打开另一张，再关闭……

生命诚可贵，space 大法好。

#### Command-⌘

这是另一个神奇的Mac独有的按键。通常会配合其他键完成操作。记住多数快捷组合键都需要用到它就行了。类似于Windows里的Ctrl键。

**复制粘贴**

⌘ + C 复制（拷贝）

⌘ + X 剪切

⌘ + V 粘贴

⌘ + option + V 粘贴，原复制对象不会保留，相当于「移动」
 
 **关闭退出**

⌘ + W 关闭当前的软件窗口（软件并没有真正退出进程，类似于最小化），相当于点了左上角的红色叉叉（并不会关闭应用，只是最小化）。

⌘ + Q **真正退出软件**。

⌘ + option + esc 强制退出某个软件。通常在软件无响应时使用。
 
**⌘ + Z 撤销**

在编辑文档的时候相当于 windows 下的 Ctrl+Z 键，即撤销刚才的操作。在 Mac 下则更为强大，你可以用这个快捷键撤销刚刚不小心的操作。比如你刚刚删除了一张图片，但是你马上又后悔了，你当然可以点开废纸篓，找到刚刚删除的图片，然后放回原处。更妙的方法是在删除后马上点击 ⌘+Z，这时候神奇的事情发生了，刚删除的图片又回到原来的位置！

**⌘ + A 全选**

相当于 Windows 的 ctrl+A

**⌘ + delete 删除**

即把文件移至废纸篓

**⌘ + S 保存**

不用多解释你也懂

**⌘ + N 新建**

新建你正在用的东西。比如你在用 Safari，那 ⌘+N 就是新建一个 Safari 窗口。你在用 Photoshop，⌘+N 就是新建一个 PS 文稿。

**⌘ + 空格键**

切换输入法（也可以自己设置）。

**control + 空格键**

显示或隐藏 Spotlight 搜索栏，可以快捷搜索你电脑中的任何东西。

**⌘ + tab**

切换 app的，试一下你就明白了。

有些快捷键可以到系统偏好设置里修改成你喜欢（习惯）的，比如输入法，Spotlight 等。


### Multi-Touch 触控板手势

除了快捷键以外，在拥有 Multi-Touch 触控板的 Mac 上使用 Multi-Touch 手势是另一个帮你提高效率延长生命的法宝。Mac 上的触控板跟那些 Windows 笔记本上的触摸板完全不是一个东西好么。用了这个东西才能真正体会到 Mac 系统的美妙，体会到什么是行云流水般自然顺畅。轻按、滚动、开合和轻扫，一指、两指、三指、四指。花10分钟了解这些手势，日后不只用来装逼，最重要的是可以大大提高 Mac 使用效率和方便性。

Multi-Touch 很多手势比较像 iPhone 上的操作，比如点击某东西只要轻点触控板即可，而不用完全按下（会听到声音）。比如 双指从触控板右侧边缘向左轻扫可查看通知中心，类似 iPhone 上从屏幕上方外侧向内扫。比如双指开合缩放图片和网页，跟 iPhone 上一样。

例：



# 系统篇
> 习惯了windows系统，刚开始使用macOS系统会有总总不适应的阶段，不需要担心，有我在，下面我将介绍macOS系统。

### macOS和windows有什么不同？
**软件不通用**，Windows 软件的扩展名后缀通常是.exe，macOS 是.app。很多软件会同时提供 Windows 和 Mac 版本，在 macOS 上下载 Mac 版本才能安装。

**文件系统不一样**，Mac 采用 APFS 格式，Windows 用的是 NTFS 格式。苹果格式的磁盘默认在 Windows 上不能读写，Windows NTFS 格式磁盘在 Mac 上也只能读不能写。但是可以有方法实现双平台支持，后面再说。对了，macOS 一般不需要磁盘分区。

**键盘和快捷键不完全一样**，但是大体还是相似的，请看上篇的快捷键介绍。

### 程序坞
程序坞是一个工具架，可以把常用软件放置在此处，方便后续快速打开，Windows中的任务栏也是类似的功能。

程序坞其实是可以隐藏的，你可以在通用设置中勾选「自动隐藏和显示程序坞」，使用的时候只有鼠标接近隐藏区域，才会再次出现，你就可以使用。同时程序坞也是可以调整位置的。你可以选择把程序坞放在画面的左右而不是画面的底部。

![](https://file-1256865446.cos.ap-guangzhou.myqcloud.com/img/1625712131478.png)

### 状态栏

我们刚刚已经说了屏幕的下半部分，这回我们再来说说屏幕的上半部分。也就是状态栏。
![](https://file-1256865446.cos.ap-guangzhou.myqcloud.com/img/1625712213239.png)

状态栏的左边部分基本上就是「你现在窗口软件」的「菜单栏」。各种软件的基本设置都是在这里选择。这里最需要说明的是，很多软件的基础设置都可以在这里点开对应软件名字下面「偏好设置」中设定。之所以强调是因为很多软件的教程可能会提到告诉你「偏好设置」里选择，比如最为常见的就是语言，那么这个时候你就可以来到这里查找。

状态栏的右边一方面是一些基本的信息展示，比如时间信息，网络信息，电量信息、搜索按钮、以及一些软件的状态等等。它的主要目的是帮助你快速使用那些不需要打开界面就可以进行操作的应用。

### 高效利用屏幕
这里介绍系统级别的分屏。在 Mac 电脑中如果你想要同时使用两个软件是可以进行分屏的。而且分屏的方式也是非常简单，只要我们使用鼠标直接点击长按软件左上角的全屏按钮就可以。

然后这个时候画面的一侧就会出现其他需要分屏软件的选择，直接可以进行选择即可。

分屏有什么好处呢，首先肯定是最大化使用屏幕。相当于是屏幕上可以打开多个界面，比如你可以在写文章的同时，看综艺节目等等。


### 苹果全家桶生态配合

购买了mac电脑的最重要的隐藏优势，如果有其他苹果产品，可以进行生态的配合。

**airdrop**

airdrop（隔空投送）本质上是苹果多设备之间可以通过蓝牙进行传输，速度非常快，而且不依赖于网络，这个功能也是我在Mac上最常用的功能之一。自从有了airdrop，就再也不需要通过微信传输图片或者视频了，而且传输的都是原文件，没有压缩。 

**iCloud**

iCloud也是一款跨设备的云端应用， 你在手机上拍的照片，只要在Mac用同一个Apple ID登陆，就可以直接在「照片」中查看手机上拍的照片。同样你Mac上的文件存储到iCloud之后，也可以在手机或者平板上打开。

**跨设备复制粘贴**

只有是苹果设备并且使用的同一个appId并且都打开了蓝牙，那么你就可以在某台设备上复制的文字或者图片，直接在另外一台设备上粘贴。比如我下班路上用iPhone查看了一个比较有意思的网页，回到家后我想用Mac打开，就只需要在iPhone上复制地址，然后在Mac上粘贴即可。再比如，别人发给你的邮箱账号和密码，你想在Mac上登录，直接在iPhone复制即可，这个功能太友好了。

**接力功能**

通过“接力”功能，您可以在一台设备上（Mac、iPhone、iPad 或 Apple Watch）开始一项任务，然后在另一台设备上继续该任务，而不丢失任务进程。例如，您可以在 iPhone 上浏览网页，然后在 Mac 的 Safari 浏览器中从您离开的位置继续浏览。您可以配合多款 Apple App 使用“接力”功能，例如，“日历”、“通讯录”、Pages 文稿或 Safari 浏览器。部分第三方 App 也可配合“接力”功能使用。
![](https://file-1256865446.cos.ap-guangzhou.myqcloud.com/img/1625712808570.png)

若要使用“接力”，您的设备必须满足“连续互通”系统要求。它们还必须在“系统偏好设置”（在 Mac 上）和“设置”（在 iOS 和 iPadOS 设备上）中打开 Wi-Fi、蓝牙和“接力”。您必须在所有设备上使用同一个 Apple ID 登录。

【提示】**“接力”开启后，您可以使用“通用剪贴板”跨设备拷贝和粘贴文本、图像、照片以及视频。您还可以在 Mac 电脑之间拷贝文件。**

**打开或关闭接力**

1. 在您的 Mac 上：选取苹果菜单 >“系统偏好设置”，点按“通用”，然后选择“允许在这台 Mac 和 iCloud 设备之间使用接力”（位于“最近使用的项目”下方）。若要将其关闭，请取消选择该选项。
2. 在 iPad、iPhone 或 iPod touch 上：前往“设置”>“通用”>“接力”，然后轻点以打开“接力”。若要将其关闭，请轻点该选项。

3. 在 Apple Watch 上：在 iPhone 上的“Watch” App 中，前往“我的手表”>“通用”，然后轻点以打开“启用接力”。若要将其关闭，请轻点该选项。

# 软件篇

> 由于Mac上的软件基本上都是收费的软件，光买软件的费用就是一个很大的支出，那我们只能使用PJ软件了。
推荐网址：https://www.macwk.com/

## 软件怎么下
MacOS中的App Store应用软件并没有ios的丰富，所以可以通过其他网址上下载，下载的安装包都是以.dmg为后缀名，可以在访达-下载文件夹中查找。
双击安装包即可安装，如下图，按住左侧图标拖动到右侧applications中。听到“咚”的一声，就安装完毕了。大概2秒左右。然后可关闭下图窗口。 超级简单方便，是不是？
![](https://file-1256865446.cos.ap-guangzhou.myqcloud.com/img/1625723728875.png)



## 下载以后如何安装？
如果你是从 Mac 的 App Store 中直接下载的软件，就如 iPhone 一样，可以直接通过自己的账号密码进行下载。不过如果是从网络上下载的软件，一般来说 Mac 都会问一下：

在你点击「打开」以后，就会正常安装。但你可能会碰到说应用不让打开的情况，并告诉你这是不信任的开发者。这是因为对于 Mac 来说，应用分三个类别，即从应用商店下载、从网络上下载但是包含 Apple 官方认证签名的、从网络上下载没有包含 Apple 官方签名认证（可能意味着风险）。

如果是第三种，你打开的时候可能就会被阻止。不用担心，如果你确定这个软件没有任何问题，可以在 **「设置 - 安全性与隐私」** 中看到你刚才要打开的应用，直接点击「仍要打开」即可。

## 如何卸载软件？
到finder，应用程序中卸载（右键-移到废纸篓） 是不是比windows简单？
![](https://file-1256865446.cos.ap-guangzhou.myqcloud.com/img/1625723673323.png)

## 软件推荐

### 办公类：

#### Microsoft office 2019 
微软的office 软件，不需要解释
下载地址：https://www.macwk.com/soft/office

#### WPS  
  金山旗下的office软件，windows上广告比较多， macOS上简洁干净，除了一些功能需要会员之外，还是不错的。
 下载地址：https://mac.wps.cn/

 #### XMind
Xmind 2021 是一款风靡全球的思维导图和头脑风暴软件，也是当前体验最好，功能最强大的mac思维导图软件，融合艺术与创造力，让思维清晰可见。XMind 2021 新增演说模式可自动生成转场动画和布局，一键即可展示你的思维导图。从头脑风暴到思维展示，在 XMind 中即可完成工作流闭环。告别繁琐，尽享高效。

下载地址： https://www.macwk.com/soft/xmind

### 系统类：

#### CleanMyMac X
一款清理工具，类似于360， 不过在macOS上CleanMyMac X界面简洁，功能强大。非常值得下载~
**直观的状态中心**
![](https://file-1256865446.cos.ap-guangzhou.myqcloud.com/img/1625717601052.png)
**一键智能清理**
![](https://file-1256865446.cos.ap-guangzhou.myqcloud.com/img/1625717617036.png)
**快速卸载**
![](https://file-1256865446.cos.ap-guangzhou.myqcloud.com/img/1625717672702.png)
下载地址：https://www.macwk.com/soft/cleanmymac-x

#### BetterZip 
BetterZip 5 for Mac 是一款MacOS平台上强大的压缩解压软件，BetterZip mac 破解版支持大部分压缩格式（ZIP，SIT，TAR，GZip，BZip2，RAR，7-Zip，CPIO，ARJ，LZH / LHA，JAR，WAR，CAB，ISO，CHM，RPM，DEB，NSIS，BIN，HQX等）、支持压缩包加密，而且不用解压即可预览文件，同时还具有窗口式的查看界面，解压部分文件等功能，总而言之，功能相当强大。

下载地址：https://www.macwk.com/soft/betterzip

#### Snipaste 

Snipaste for Mac 是一款很好用的支持贴图的屏幕截图工具。这是一款历时3年开发的截图工具，在win平台上面已经很稳定了，功能非常强大，支持自动检测界面元素区域，贴图，像素级的鼠标移动控制、截图范围控制，取色器 ，历史记录回放等功能，同时也支持多屏可以安装试一下。 最好用的是他的贴图功能。

下载地址：https://www.macwk.com/soft/snipaste

#### Paste

Paste for Mac是Mac平台上一款专业的剪切板记录增强工具，它能够为您储存您在设备上复制您的所有内容，并将其储存在Paste Mac的历史记录中。是您日常生活工作中必不可少的一款软件

**新的复制和粘贴方法**
无论复制的是什么格式，Paste都会自动保留您复制的所有内容，以便您可以快速访问复制过的内容。
![](https://file-1256865446.cos.ap-guangzhou.myqcloud.com/img/1625718622208.png)

**提高您的工作效率**
![](https://file-1256865446.cos.ap-guangzhou.myqcloud.com/img/1625718572596.png)

下载地址：https://www.macwk.com/soft/paste

#### Bartender
Bartender 4 中文版是一款Mac上的菜单栏应用图标管理工具，Bartender 4 是迄今为止最大的更新，专门针对 macOS Big Sur 创建。随着更多令人兴奋的新功能的加入，能够帮助我们删除或者隐藏 macOS 11 Big Sur 系统菜单栏图标的图标，它能够创建一个二级的菜单栏，让我们把不需要直接显示的菜单栏的应用图标放在这个二级菜单栏中，或者直接隐藏，对于崇尚简洁的Mac用户来说，这是一款非常好用的软件！ 当我们安装的应用越来越多时，菜单栏的图标也越来越多， 通过这个软件我们可以选择隐藏某些软件达到简洁的效果。

**菜单栏布局**
通过新的布局屏幕，您可以更全面，更强大地控制菜单栏项目。您可以隐藏它们，可以轻松访问它们，将最重要的项目设置为始终可见，并为工作流程定义项目的确切顺序。即使在macOS重新启动后，也会按需保留您的设置。
![](https://file-1256865446.cos.ap-guangzhou.myqcloud.com/img/1625718812691.png)

![](https://file-1256865446.cos.ap-guangzhou.myqcloud.com/img/1625718851284.png)

#### One Switch 
One Switch 是一款mac平台上面的快速开启或关闭系统功能的工具。比如一键隐藏mac桌面图标、一键切换mac深色外观（暗黑模式）、一键关闭Mac休眠、一键开启mac屏幕保护、一键连接AirPods等、一键显示mac隐藏文件、一键打开mac原彩显示等等功能，您还可以自定义其它功能！

**一键隐藏桌面图标**
![](https://file-1256865446.cos.ap-guangzhou.myqcloud.com/img/1625718937161.png)

下载地址：https://www.macwk.com/soft/one-switch

### 音影类

#### IINA（看视频必备）

IINA 是一款采用现代设计和流线型功能的在线mac视频播放器，可以观看视频，管理播放列表，处理媒体内容或为电影加载字幕提等等。IINA mac可以加载本地文件或提供视频URL，IINA mac可以使用所有流行的媒体格式。而且您可以快速更改界面主题，调整默认行为和用户界面，决定是否要自动加载字幕，配置新的键绑定等。这是一款 Github 开源应用，感谢开发者们的辛苦付出。

#### MarginNote （看文献必备）

MarginNote 3 mac 是一款专为mac用户设计的电子阅读神器，配有强大的阅读器以及多种学习实用工具，能够让学习者更加方便的阅读，将不同的知识贯通连接，达到过目不忘的境界。MarginNote 在你阅读时重要字段提供标注、也可以让你用思维导图的方式更好的将你所学所读所想组织起来，清晰易懂，外加标签以及使用学习卡提高记忆力。适用于学生、老师、科研人士以及更多热爱学习的人，致力于提高学习阅读能力热爱学习的你绝对不要错过。

**思维导图模式**
![](https://file-1256865446.cos.ap-guangzhou.myqcloud.com/img/1625719514933.png)

**复习模式**
![](https://file-1256865446.cos.ap-guangzhou.myqcloud.com/img/1625719540046.png)

下载地址： 目前没有破解版，我已经购买了，需要联系我即可。


### 浏览器篇

#### Chrome 谷歌浏览器 （科研狗必备配合翻墙使用）

Chrome是一款强大的浏览器，由于国内的环境，导致很多人不愿意使用，都在使用垃圾的国内浏览器，导致一堆垃圾广告和弹窗。

#### 浏览器插件
chrome的插件是最大的特色之一，使用插件会使工作效率提升，下面我会介绍我经常使用的插件。
插件商城：https://chrome.google.com/webstore/category/extensions
#####  Adblock Plus   免费的广告拦截器
可以帮你拦截各种流浪的广告，必装！！！
下载地址：https://chrome.google.com/webstore/detail/adblock-plus-free-ad-bloc/cfhdojbkjhnklbpkdaibdccddilifddb

点击添加至Chrome即可
![](https://file-1256865446.cos.ap-guangzhou.myqcloud.com/img/1625724555246.png)

##### OneTab 一键管理浏览器标签
浏览器打开了过多的标签页，会占用大量的内存。 使用这个插件即可帮你减少内存的使用，并将标签页转换成列表。
比如我经常会打开大量的标签页。
![](https://file-1256865446.cos.ap-guangzhou.myqcloud.com/img/1625724881595.png)
点击这个图标，即可转换成列表，方便下次查看， 点击某个网站查看或者恢复全部
![](https://file-1256865446.cos.ap-guangzhou.myqcloud.com/img/1625724979818.png)
![](https://file-1256865446.cos.ap-guangzhou.myqcloud.com/img/1625725034530.png)


#### 网址推荐
##### 科研类
https://site.sciping.com/  经常使用的科研学术性导航网址，非常齐全推荐收藏~

https://scholar.google.com.hk/?hl=zh-CN  谷歌学术文献查询

##### 翻译网站
https://www.deepl.com/translator       Deepl 专业词汇翻译比较准确

https://translate.google.cn/  谷歌翻译

https://fanyi.youdao.com/  有道翻译

http://zhiyunwenxian.cn/  国内的知云文献翻译，使用一般吧。


##### 办公素材
- 优品ppt，各种免费的ppt模板   https://www.ypppt.com/
- 1ppt  ppt素材    http://www.1ppt.com/
- ppter吧   ppt素材下载        https://www.ppter8.com/
- 多搜   无版权图片素材      http://duososo.com/

#### 资源搜索类
- 万网搜：点击上方可以切换各种搜索网站 https://www.wanwangsou.com/       

#### 影视类
国内：
- 555电影    https://www.o8tv.com/
- 奈菲影视  需要关闭广告屏蔽器  https://www.nfmovies.com/ 
- 独播库 国内影视在线观看    https://e.duboku.fun/
- 
  
国外：
- 91美剧  还不错，看了好多年了  https://91mjw.com/
- 奈飞星，主打国外影视剧，速度不错，画质很清晰 	https://nfxhd.com/
- 简影 高颜值高质量极速追剧站  https://tv.syrme.top/
- 4K鸭 奈飞蓝光资源站 https://yanetflix.com/
  
  
### 翻墙篇
由于国内的网络环境，需要查看国外的文献资料，需要翻墙。过多的描述就不说了，敏感话题。



#### ClahsX 翻墙软件 

下载地址：https://github.com/yichengchen/clashX/releases/download/1.65.0/ClashX.dmg
ps：网址进不去联系我。

首次使用 ClashX 时，macOS 会提醒你此应用来自未知开发者，请允许打开此应用。
ClashX 首次运行会提示是否安装帮助程序（Helper）。此帮助程序用于设置系统代理，否则每次你通过 ClashX 变更系统系统状态（打开或关闭）时都需要输入密码，请点击 “Install”，之后 macOS 会提示输入用户密码。

![](https://file-1256865446.cos.ap-guangzhou.myqcloud.com/img/1625720618491.png)

启动 ClashX，点击状态栏中的 ClashX 图标，依次选择「配置」、「托管配置」、「管理」，在弹出的界面点击添加订阅。

![](https://file-1256865446.cos.ap-guangzhou.myqcloud.com/img/1625720637365.png)

![](https://file-1256865446.cos.ap-guangzhou.myqcloud.com/img/1625720679448.png)

地址联系我：
![](https://file-1256865446.cos.ap-guangzhou.myqcloud.com/img/1625720714125.png)
若干秒后将在软件里看到刚刚添加的配置文件。
![](https://file-1256865446.cos.ap-guangzhou.myqcloud.com/img/1625720756221.png)

点击 ClashX 状态栏图标，将「出站模式」选为「规则判断」，在「Proxy」或「Gloabal」策略组中可以选择自己喜欢的线路，然后点击「设置为系统代理」即可开始使用。

「Proxy」或「Gloabal」策略组是用于访问国际互联网的默认策略，一般情况下，所有国际网络的访问都通过该策略组中选择的节点进行连接。
![](https://file-1256865446.cos.ap-guangzhou.myqcloud.com/img/1625720776501.png)
![](https://file-1256865446.cos.ap-guangzhou.myqcloud.com/img/1625720793587.png)
![](https://file-1256865446.cos.ap-guangzhou.myqcloud.com/img/1625720808441.png)


设置完成后， 访问https://www.google.com  正常访问，恭喜你翻墙成功。 外面的世界固然精彩，可不能贪杯噢~~

