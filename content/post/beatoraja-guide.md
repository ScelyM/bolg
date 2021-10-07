---
title: "Beatoraja Guide"
date: 2021-07-19
draft: false
---

# Beatoraja使用教程

    我也不知道我为什么要写这个。

<!--more-->

## 前言

大家好，我是Scely。

这是一份Beatoraja的使用教程，我会尽量涵盖所有相关的东西。如果发现有歧义的地方或者需要补充的地方，欢迎通过[以下联系方式](https://scelym.github.io/post/me/#how-to-find-me)来提醒我补充或者更改。

本教程的宗旨是，在不影响游戏的前提下尽量少的修改游戏本身的设置。大部分的设置与正常游戏无关，这些功能可熟悉游戏之后自行摸索。

__此教程为免费教程，如果在任何地方发现收费行为，请立即骂街。__

__此教程为免费教程，如果在任何地方发现收费行为，请立即骂街。__

__此教程为免费教程，如果在任何地方发现收费行为，请立即骂街。__


本教程有很多张图片，如果没有见到图片可以尝试关闭广告屏蔽工具。

本教程需要有一定的电脑相关知识及英语知识才可以完全理解。但是没有这些知识不会影响阅读教程。

本教程适合明确的知道自己需求的人阅读。

善用右侧导航栏快速定位到你想看的地方。

__本教程不保证游戏水平的提升。__

## 1. 游戏前

---

### 1.1 硬件配置

Beatoraja强制需要64位系统。如果你不清楚如何查看64/32位系统的话请自行搜索“查看系统位数”。

我根据之前了解的情况，列出了推荐配置一个表格供大家参考。

~~2021年了，正常的电脑都能用好吗。~~

/ | 最低配置 | 推荐配置(720p)
---|---|---
CPU性能 | 酷睿初代以后的Intel | 酷睿4代以后的Intel/锐龙以后的AMD
显卡性能 | UHD610以上 | GTX950/RX550
内存 | 2G*2 双通道 | 4G*2 双通道
硬盘空间 | 20G可用空间 | 150G以上可用空间

以上配置仅代表可以流畅游玩Beatoraja以及**考虑到噪音**的大部分情况，特殊情况如4K分辨率/特殊谱面不包含在内。

也就是说，目前大部分的电脑都可以流畅运行Beatoraja。极少数的配置不足玩家建议游玩需求配置更低的Lunatic Rave 2。[LR2教程](https://hakula.xyz/tutorial/lr2.html)by Hakula。

---

### 1.2 软件配置

Beatoraja需要有Java8以上环境才可以运行。

[Java8 64位官方下载地址](https://www.java.com/en/download/manual.jsp)

[Beatoraja官方地址](https://mocha-repository.info/download.php) (日文)

- (0.8.1)Beatoraja下载页面中有个 __-jre-win64__ 版本，这个版本可以免去安装Java的过程，缺点是没有命令提示符窗口用来查看状态。在接下来的篇幅中简称exe版。
- 通常版在接下来的篇幅中简称bat版。

[国内镜像地址](https://bms.cosmiccat.top/bms/BMS%20Player/) (感谢anshi和Hakula！)

- (0.8.1)文件夹内两个压缩包对应官方地址内两个包。

---

## 2. 游戏设置

{{< admonition tip "Tips" false >}}此处两个版本会出现很小的分歧点。不用担心，不是每个版本都会有对应的exe版本。{{< /admonition >}}

- exe版打开Beatoraja.exe文件

- bat版打开Beatoraja-config.bat文件，首先弹出的是命令提示符窗口，这个窗口会自动跑一些指令，稍等片刻。

    - 可能会出现的情况1：窗口闪了一下，消失了。解决办法：卸载已安装的32位Java，去上面Java下载页面中下载 __Windows Offline (64-bit)__ 文件
    - 情况2：窗口卡了很久没有反应。解决方法：查看命令提示符窗口的标题栏中是否在前面有 __“选择”__ 两字，如果有的话鼠标点击窗口并回车即可。

没什么意外情况的话，来到了标题为 “Beatoraja *版本号* configuration” 的窗口。

![configuration界面](https://ftp.bmp.ovh/imgs/2021/01/a17e0a4d67e7779a.png)

---

### 2.1 用户名

在界面的最上面一行，Player ID后面有个输入框，输入你的名字。

- 有些皮肤会读取你的这个名字显示在某些界面上，比如选歌界面。
- 此选项和Internet ranking无关。

---

### 2.2 视频设置

窗口的初始选项卡是Video界面。

{{< admonition tip "Tips" false >}}视频选项与水平无关，仅为个人习惯。{{< /admonition >}}

Display Mode中有三个选项：FullScreen/Borderless/Window，分别对应全屏/无边框窗口/窗口化。

Resolution意为分辨率，**建议**保持1280*720不变。

Vsync开关是垂直同步开关，对于音乐游戏来说不建议打开，仅在游戏界面画面撕裂严重的情况下建议打开。

MAX FPS设置为500。

下面是BGA开关/miss层显示时间/BGA大小。不建议调整。

---

### 2.3 导入曲包及难度表

**曲包可以在[https://bms.cosmiccat.top/](https://bms.cosmiccat.top/)下载。** 推荐下载“Satellite+通常难易度+发狂难易度”曲包，注意更新日期。

选项卡切到Resource栏。

![resource](https://ftp.bmp.ovh/imgs/2021/02/65c14c68d8515640.png)

BMS Path为曲包目录，Table URL为难度表链接。

曲包导入方法：点击BMS path框右侧的加号，选择*.bms文件所在文件夹的上级目录，确定即可。

- 不要直接导入单曲。

- 确定[*.bms]文件都在同一个层级下。如 __['选定文件夹'/'分类'/'曲名'/'BMx文件']__。

    - BMS读取的方式是按层级，以上面的格式为例子，如果出现了一个 __['选定文件夹'/'曲名'/'BMx文件']__ 的文件，则下一级的所有文件夹都不会被读取。

        - 此处BMx文件包括:BMS/BME/BML/PMS等支持格式。
        - 此条规则适用于LR2。

    - bat版可以通过命令提示符的窗口来确认进度。

        - 警告信息和你会玩到的大部分谱面无关，不用在意，可以通过文件夹名字判断导入程度。

删除方法为点击目录所在行，高亮后点击右方减号。~~真的要写这句吗~~

Beatoraja的难度表链接是默认内置的，点击下方的**Load Difficulty Table**按钮即可联网下载。

如果想添加新的难度表或者段位认证，只需要把链接粘贴到上方仅有一行的输入框内，再点击右侧加号即可。

- 部分用户会提示下载失败，据统计大部分是由于运营商的DNS污染或者网络环境导致，需要用到特殊方法或者同难度表的别的链接。
- [Zris的难度表镜像](http://zris.work/bmstable.htm)，内含使用方法。

下方的Update Song Database When Starting按钮建议打开。

---

### 2.4 皮肤设置

选项卡切到Skin栏。

![skin](https://ftp.bmp.ovh/imgs/2021/02/48509713b7cc00f4.png)

Category栏切换游戏模式，搓盘不算在key数内，也就是7+1模式为7keys。

右侧Skin下拉菜单选择皮肤，选择后下面会有具体设置。

每个皮肤的设置不相同，仅对大部分皮肤都会有的设置做说明。

- (0.8.3) beatoraja同捆了Zris的modernchic中文翻译版本。

{{< admonition tip "Tips" false >}}【日文】[beatoraja皮肤集合](https://mirais-station.hatenablog.com/entry/2021/01/21/180000)。需要一定阅读能力，不对此博客做详细介绍{{< /admonition >}}

- Score Graph是柱状图，实时显示与目标分数/自己最好成绩的差距。
- Judge Timing中打开Fast/Slow显示。
- Notes和Keybeam为note样式和爆炸效果。
- Line亮度为轨道分割线亮度，在LITONE5皮肤设置中这条没有英文翻译。

其他界面的皮肤切换思路相同，对应名字为Select-选歌界面/Decide-点击谱面后的过渡界面/Result-结算界面。

{{< admonition info warning success "Tips" false >}}设置完毕后点击右上角update按钮才会更新。在游戏中对皮肤做出的更改切换场景后才会显示。{{< /admonition >}}

---

### 2.5 其他设置

Other选项卡中Enable automatic download of BMS by IPFS按钮关闭。

- IPFS服务在程序中可以理解成一个在线下歌的服务，但是由于服务器及国内网络环境原因约等于没有。Resource中的IPFS链接可以保留，万一以后能用了呢。

Import LR2 Score功能可以导入LR2的存分文件，不用重新刷以前刷过的大灯了。

IR选项卡可以连接Internet Ranking。一般来说有两个网可以连：Mocha和MinIR。

- 选择IR后右侧链接可以注册账户，需要邮箱。
- 可以同时向两个IR发送分数。
- 其余功能自行选择，看不懂的单词可以查字典。

至此，可以点击Play开始游戏了。

---

### 2.6 按键设置

按play进入游戏后，确保输入法关闭的情况下点击主键盘6键(不要使用小键盘)，进入按键设置界面。

默认的界面是5keys设置，需要按键盘的方向键右切到7keys。

![按键设置](https://ftp.bmp.ovh/imgs/2021/01/cf47aea314596fb8.png)

设置方法为回车高亮对应光标后点击对应按键。

- 1-7键对应的是从左到右按键区7个键。
- F-Scr和R-Scr代表正反向搓盘，程序只判别输入信号而不是真正的方向。
- start和select键一定要设置，涉及很多刚才没有调整的选项。

一般来说键盘游玩的按键设置如下：

左皿|1|2|3|4|5|6|7|右皿
---|---|---|---|---|---|---|---|---
A|S|D|F| [Space] | J|K|L|;
[左shift] |A|S|D| [Space] |K|L|;| [右shift]
Q|W|E|R| [Space] |I|O|P|[
[左shift] |Z|X|C|[Space]|M|,|.|/
Q|W|E|F|[Space]|J|I|O|;
A|S|D|F|J|[Space]|K|L|;

很多考虑舒适度的玩家会在此基础上略做修改，比如提升一行至qweriop行或者降低一行或者错行游戏。

由于看不懂我说的是什么意思的人太多我决定多写几种。

{{< admonition tip "Tips" false >}}不在此教程中对游戏键位做推荐，适合别人的不一定适合自己。{{< /admonition >}}

设置完毕后ESC返回选歌界面。

---

### 2.7 速度/挡板/血条等设置

在刚才的按键设置界面设置了start/select键这时候就要用了。

按住start键菜单中可以调整目标分数/随机选项/血条选项。

![start](https://ftp.bmp.ovh/imgs/2021/02/1bc996ccaa4e17e4.png)

- 不在此对随机选项/血条选项做说明。
- 此菜单中通常会有一个Main BPM选项，建议打开。绝大多数的谱面中此选项有效。

按住select键菜单中不建议调整任何选项。

![select](https://ftp.bmp.ovh/imgs/2021/02/59034188b21df59d.png)

- 此菜单中的选项会对游戏有较大影响，建议进阶使用。

同时按住start和select键菜单中可以调整延迟/下落速度/BGA开关/同步切换血条功能。

![start+select](https://ftp.bmp.ovh/imgs/2021/02/0e122ec7327468f5.png)

在此额外对best clear功能做一个解释，开了这个选项后游戏中会同步跑所有血条：EX-Hard/Hard/Normal/Easy/assist-Easy。在通过的前提下优先显示最高的血条。

- Mocha IR在开了此选项后如果Hard未能通过则直接切换到Easy。

挡板在LITONE5内要打开谱面之后在载入时间双击start调整。有些皮肤的start菜单会有Sudden+设置，打开后也在载入时间内调整。调整逻辑和IIDX街机一致。

lift即判定线升高在大部分皮肤中仅能在configuration中的play option选项卡中选择，由于大多数人并不会使用这个功能所以不做解释。

关于LN mode：

- LN mode为LR2式长条判定，无尾判，按住不需要松手。
- CN mode为有尾判。
- HCN mode为一个长条分割为很多小note，可以中间续接。
- 在含有长条的谱面中3种mode分别计分，如谱面无长条则任意切换不会受到影响。

---

### 2.8 游玩

游戏中的谱面标级并无依据可循，做谱人想写什么就写什么。所以请参照难度表游戏。

{{< admonition info warning success "Tips" false >}}无意义的寻找认同感并不会对你的水平有实际改善。{{< /admonition >}}

---

## 3. 疑难解答

Q：双击bat文件，cmd窗口闪退该如何处理？

A：检查本机安装的Java版本。近期出现了不止一位的安装了Java15并忘记的用户，通过检查卸载Java8以外版本即可解决。另一种解决办法是挂载javafx包，不在此做解答。

Q：点击play弹出如下界面该如何处理？

![you are busted!](https://ftp.bmp.ovh/imgs/2021/01/bf114ce93778956d.png)

A：制作方并不想让Beatoraja成为IIDX或者DJMAX等商业游戏的模拟器，一旦检测到有商业解析BMS的导入就会强制不能运行。解决办法为窗口中所说：移除含有商业解析BMS的目录并点击Rebulid BMS Database。

Q：点击谱面后游戏闪退，仅剩Configuration界面和命令提示符界面。

A：查看CMD窗口中信息，如果有“音源读取失败”字样则尝试使用管理员权限运行程序。

- BGA问题在beatoraja中几乎不会出现，如果确定为BGA问题则可以尝试下载K-lite视频解码包，[官方下载地址](https://www.codecguide.com/download_kl.htm)，一般来说Standard以上的包即可解决。如果还是不能解决的话可以尝试关闭BGA。

Q：选歌界面移动到某一首歌时游戏闪退。

A：我没有发生过此种情况。据了解是由于皮肤中使用了自定义字体导致，建议重新下载皮肤或者更换选歌界面解决。

Q：Load Difficulty Table时卡死。

A：联网需要一点时间，一般是1分钟左右。如果长时间卡死或者命令提示符窗口提示更新失败则为网络环境问题，需要寻找同难度表的其他链接或者科学上网方式。

{{< admonition tip "Tips" false >}}以上情况不代表所有可能会发生的情况。如果发生了不能解决的情况可以通过各种方式联系我。{{< /admonition >}}

Q：打开程序后无响应。

A：麻烦说的详细一点，谢谢。或者可以找我详细询问。

---

## 5. 结语

本来是没有写这个的需求的，hakula写了LR2的引导，oraja的引导群里也好几份。

直到我看了个群里的oraja引导，信息混乱，小半个篇幅是在介绍程序的优点，很多不必要甚至误导的操作也写在里面。

写了一大堆，删了。教程中不应该出现个人情绪浓重的语言，即使是这种教程也是。

只留下一句，我的罪恶，我的生命之火。

感谢各位的帮助：

    为什么这个格式首行一定要有缩进
    Ramen
    Kaguya
    Mahua
    BMS群的各位（群号176763307）

by Scely 2021.1.30 update 2021.10.07

如果你觉得教程对你有帮助的话，可以通过以下二维码向我表示支持。仅支持支付宝。

![支付宝](https://ftp.bmp.ovh/imgs/2021/07/3983d6766e6158f6.jpg)