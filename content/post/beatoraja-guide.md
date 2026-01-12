---
title: "Beatoraja Guide"
date: 2023-04-01
draft: false
---

# Beatoraja使用教程

    我也不知道我为什么要写这个。
    最近更新：23.4.8 删除了bat版本的相关教程。

<!--more-->

## 前言

大家好，我是Scely。

这是一份Beatoraja的使用教程，我会尽量涵盖所有相关的东西。如果发现有歧义的地方或者需要补充的地方，欢迎通过[以下联系方式](https://scelym.github.io/post/me/#how-to-find-me)来提醒我补充或者更改。

本教程的宗旨是，**在不影响游戏的前提下尽量少的修改游戏本身的设置**。大部分的设置与正常游戏无关，可熟悉游戏之后自行摸索。

__对于初次配置Beatoraja进行游戏的用户，不建议跳过教程的任何一个步骤。__

__对于初次配置Beatoraja进行游戏的用户，不建议跳过教程的任何一个步骤。__

__对于初次配置Beatoraja进行游戏的用户，不建议跳过教程的任何一个步骤。__

__此教程为免费教程，如果在任何地方发现收费行为，请立即骂街。__

__此教程为免费教程，如果在任何地方发现收费行为，请立即骂街。__

__此教程为免费教程，如果在任何地方发现收费行为，请立即骂街。__

本教程有很多张图片，如果没有见到图片可以尝试关闭广告屏蔽工具。

本教程需要有一定的电脑相关知识及英语知识才可以完全理解。但是没有这些知识不会影响阅读教程。

本教程适合明确的知道自己需求的人阅读。

善用右侧导航栏快速定位到你想看的地方。

__本教程不保证游戏水平的提升。__

__如果你对自己阅读教程的水平没有信心，或者是自己的硬盘空间不足，可以联系我购买BMS硬盘，到手即玩__

## 1. 游戏前

---

### 1.1 硬件配置

Beatoraja强制需要64位系统。如果你不清楚如何查看64/32位系统的话请自行搜索“查看系统位数”。

我根据之前了解的情况，列出了推荐配置一个表格供大家参考。

~~2023年了，正常的电脑都能用好吗。~~

/ | 最低配置 | 推荐配置(720p)
---|---|---
CPU性能 | 酷睿初代以后的Intel | 酷睿4代以后的Intel/锐龙以后的AMD
显卡性能 | UHD610以上 | GTX950/RX550
内存 | 2G*2 双通道 | 4G*2 双通道
硬盘空间 | 20G可用空间 | 150G以上可用空间

以上配置仅代表可以流畅游玩Beatoraja的大部分情况，特殊情况如4K分辨率/特殊谱面不包含在内。

也就是说，目前大部分的电脑都可以流畅运行Beatoraja。极少数的配置不足玩家建议游玩需求配置更低的Lunatic Rave 2。[LR2教程](https://hakula.xyz/tutorial/lr2.html)by Hakula。

---

### 1.2 软件配置

{{< admonition tip "Tips" false >}}0.8.8版本后对java的需求变为java17，所以对教程相关部分进行改动。{{< /admonition >}}

Beatoraja需要有Java环境才可以运行。由于Jre版本内置了Java，不需要额外下载，但页面依旧提供下载方式。

[Java8 64位官方下载地址](https://www.java.com/en/download/manual.jsp) （教程内不需要）

[Beatoraja官方地址](https://mocha-repository.info/download.php) (日文)

- 点击**beatoraja-*最新版本号*-jre-win64**下载。

- 暂不提供其他镜像地址。

- 教程内不提供额外皮肤的下载方式，如有需求请进群咨询。

---

## 2. 游戏设置

{{< admonition tip "Tips" false >}}此处游戏内演示用的皮肤为Type-M，不提供下载方式。{{< /admonition >}}

- 打开Beatoraja.exe文件

没什么意外情况的话，来到了标题为 “Beatoraja *版本号* configuration” 的窗口。

![configuration界面](http://i0.hdslb.com/bfs/new_dyn/9b37d0747280149b4531bd2635ff6760550673.png)

---

### 2.1 用户名

在界面的最上面一行，Player ID后面有个输入框，输入你的名字。（也可以不输入，没什么意义）

- 有些皮肤会读取你的这个名字显示在某些界面上，比如选歌界面，或decide界面会显示一行player：xxx。
- 此选项和Internet ranking（网络相关功能）无关。

---

### 2.2 视频设置

窗口的初始选项卡是Video界面。

{{< admonition tip "Tips" false >}}视频选项与水平无关，仅为个人习惯。{{< /admonition >}}

Display Mode中有三个选项：FullScreen/Borderless/Window，分别对应全屏/无边框窗口/窗口化。

Resolution意为分辨率，我个人的设置是720p窗口化，对于大部分针对1080p所作的皮肤来说会产生不对等缩放的问题。

Vsync开关是垂直同步开关，**不建议打开**。

MAX FPS**建议**设置为500。

下面是BGA开关/miss层显示时间/BGA大小。不建议在此处调整miss层显示时间以外的设置。

{{< admonition tip "新增必须调整项目" false >}}调整输入采样率{{< /admonition >}}

- (0.8.5)之前的教程中并未注意此项目，并非新增功能。

Input选项卡中将MODE切换至7keys

下一行的Minimum input duration(ms)调至1

切换至其他你所游玩的MODE，同样检查此项是否为1

![input界面](http://i0.hdslb.com/bfs/new_dyn/9a88702536fec4f93a9c5a41fc14acc7550673.png)

---

### 2.3 导入曲包及难度表

**曲包可以在[https://bms.iidx.ca/（感谢anshi）](https://bms.iidx.ca/)下载。** 

选项卡切到Resource栏。

![resource](http://i0.hdslb.com/bfs/new_dyn/e9d073b70320fad326490c7d5f0a8475550673.png)

BMS Path为曲包目录，Table URL为难度表链接。

曲包导入方法：点击BMS path框右侧的加号，选择*.bms文件所在文件夹的上级目录，确定即可。

- 不要直接导入单曲。

- 确定[*.bms]文件都在同一个层级下。如 __['选定文件夹'/'分类'/'曲名'/'BMx文件']__。

    - BMS读取的方式是按层级，以上面的格式为例子，如果出现了一个 __['选定文件夹'/'曲名'/'BMx文件']__ 的文件，则下一级的所有文件夹都不会被读取。
    - 不要选择 __['选定文件夹'/'BMx文件']__ 的文件夹。

        - 此处BMx文件包括:BMS/BME/BML/PMS等支持格式。
        - 此条规则适用于LR2。

    - 曲目较多时会导入很久，程序体现为卡死，但实际并未卡死。

删除方法为点击目录所在行，高亮后点击右方减号。~~真的要写这句吗~~

Beatoraja的难度表链接是默认内置的，点击下方的**Load Difficulty Table**按钮即可联网下载。

如果想添加新的难度表或者段位认证，只需要把链接粘贴到上方仅有一行的输入框内，再点击右侧加号即可。

- 部分用户会提示下载失败，据统计大部分是由于运营商的DNS污染或者网络环境导致，需要用到特殊方法或者同难度表的别的链接。
- [BMS难度表集合站](https://www.ribbit.xyz/bms/tables/table_list.html)，部分国内网络可能打不开，内含部分垃圾表。
- [Zris的难度表镜像](https://zris.work/bmstable.htm)，内含使用方法。

下方的Update Song Database When Starting按钮建议打开。

---

### 2.4 皮肤设置

选项卡切到Skin栏。

![skin](http://i0.hdslb.com/bfs/new_dyn/525f99eddb53f62fd247362340227a49550673.png)

Category栏切换游戏模式，搓盘不算在key数内，也就是7+1模式为7keys。

选曲界面为Music Select，结算界面为Result。麻烦英语课的时候好好听课。

右侧Skin下拉菜单选择皮肤，选择后下面会有具体设置。

每个皮肤的设置不相同，仅对大部分皮肤都会有的设置做说明。

- (0.8.3) beatoraja同捆了Zris的modernchic中文翻译版本。

【日文】[beatoraja皮肤集合](https://mirais-station.hatenablog.com/entry/2021/01/21/180000)。需要一定的日语阅读能力，不对此博客做详细介绍

- Score Graph是柱状图，实时显示与目标分数/自己最好成绩的差距。
- Judge Detail中可以切换fast/slow显示或是偏差毫秒显示。
- Notes和Keybeam为note样式和爆炸效果。
- Line darkness为轨道分割线亮度，255时为不显示。
- Key Beam Offset为按键光柱调整，h为负时缩短光条高度。

其他界面的皮肤切换思路相同，对应名字为Select-选歌界面/Decide-点击谱面后的过渡界面/Result-结算界面。

{{< admonition tip "Tips" false >}}设置完毕后点击右上角update按钮才会更新。在游戏中对皮肤做出的更改切换场景后才会显示。{{< /admonition >}}

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

默认的界面是5keys设置，需要按键盘的右方向键切到7keys。

![按键设置](http://i0.hdslb.com/bfs/new_dyn/8a31a9b39aec7df63c684ac5447ea2b9550673.png)

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

![start](http://i0.hdslb.com/bfs/new_dyn/a6ae39373b2fc1c6aebe2f3add315229550673.png)

- 不在此对随机选项/血条选项做说明。
- 此菜单中通常会有一个Main BPM选项，建议打开。绝大多数的谱面中此选项有效。

按住select键菜单中不建议调整任何选项。

![select](http://i0.hdslb.com/bfs/new_dyn/409f7f714b075fdfdc3a259991246a0b550673.png)

- 此菜单中的选项会对游戏有较大影响，建议进阶使用。

同时按住start和select键菜单中可以调整延迟/下落速度/BGA开关/同步切换血条功能。

![start+select](http://i0.hdslb.com/bfs/new_dyn/254cb122006773d2eeba2c935c762ae0550673.png)

在此解释一下best clear功能，开了这个选项后游戏中会同步跑所有血条：Full-Combo/EX-Hard/Hard/Normal/Easy/assist-Easy。在通过的前提下优先显示最高的血条。演示皮肤中可以调整最低下到哪个血条。

- 本人并不使用IR功能，所以打开best clear会对某个网上传成绩的影响并不知情。

(0.8.4)Beatoraja更新了和LR2类似的自动调整延迟功能，此皮肤可以在start+select界面中开关此选项。如果使用的是其他皮肤，则可以在Configuration界面中的Play Option选项卡中找到“Notes Display Timing Auto Adjust”开关。

挡板和lift及判定线升高功能在此皮肤中可以通过在start+select界面中使用鼠标开关，具体调整逻辑与IIDX相同。如果使用的皮肤没有这个开关则要去Configuration界面中的Play Option选项卡找到开关并打开，此处不做讲解。

关于LN mode：

- LN mode为LR2式长条判定，无尾判，按住不需要松手。
- CN mode为有尾判。
- HCN mode为一个长条分割为很多小note，可以中间续接。
- 在含有长条的谱面中3种mode分别计分，如谱面无长条则任意切换不会受到影响。

---

### 2.8 游玩

游戏中的谱面标级并无依据可循，做谱人想写什么就写什么。所以如果想找到适合自己水平的谱面，请参照难度表游戏。

{{< admonition info warning success "Tips" false >}}无意义的寻找认同感并不会对你的水平有实际改善。{{< /admonition >}}

---

## 3. 疑难解答

Q：点击play弹出如下界面该如何处理？

![you are busted!](http://i0.hdslb.com/bfs/new_dyn/9e82c1e4c1691b97fde0c3d3f79dcc52550673.png)

A：制作方并不想让Beatoraja成为IIDX或者DJMAX等商业游戏的模拟器，一旦检测到有商业解析BMS的导入就会强制不能运行。解决办法为窗口中所说：移除含有商业解析BMS的目录并点击Rebulid BMS Database。

Q：点击谱面后游戏闪退，仅剩Configuration界面和命令提示符界面。

A：尝试使用管理员权限运行程序。

- BGA问题在beatoraja中几乎不会出现，如果确定为BGA问题则可以尝试下载K-lite视频解码包，[官方下载地址](https://www.codecguide.com/download_kl.htm)，一般来说Standard以上的包即可解决。如果还是不能解决的话可以尝试关闭BGA。

Q：选歌界面移动到某一首歌时游戏闪退。

A：我没有发生过此种情况。据了解是由于皮肤中使用了自定义字体导致，建议重新下载皮肤或者更换选歌界面解决。

Q：Load Difficulty Table时卡死。

A：联网需要一点时间，一般是1分钟左右。如果长时间卡死或者命令提示符窗口提示更新失败则为网络环境问题，需要寻找同难度表的其他链接或者科学上网方式。

{{< admonition tip "Tips" false >}}以上情况不代表所有可能会发生的情况。如果发生了不能解决的情况可以通过各种方式联系我。{{< /admonition >}}

Q：打开程序后无响应。

A：麻烦说的详细一点，谢谢。或者可以找我详细询问。

![详细一点.jpg](https://s1.ax1x.com/2023/04/08/pp7Ioi6.jpg)

---

## 5. 结语

本来是没有写这个的需求的，hakula写了LR2的引导，oraja的引导群里也好几份。

直到我看了个群里的oraja引导，信息混乱，小半个篇幅是在介绍程序的优点，很多不必要甚至误导的操作也写在里面。

写了一大堆，删了。教程中不应该出现个人情绪浓重的语言，即使是这种教程也是。

只留下一句，我的罪恶，我的生命之火。

BMS交流群：176763307

感谢各位的帮助：

    为什么这个格式首行一定要有缩进
    Ramen
    Kaguya
    Mahua
    rexcape
    Feb.

by Scely 2021.1.30 

last update 2023.04.08

2021.10.15 我退出了上面的“BMS交流群”，群内发生的事与我无关。

如果你觉得教程对你有帮助的话，可以通过爱发电向我表示支持。

[爱发电地址](https://afdian.net/@Scely)