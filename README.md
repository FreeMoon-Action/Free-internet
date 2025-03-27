# 【肥宅快乐上网方案】 开心上网-导航页！

项目名：Free internet  
中文名：肥宅快乐上网  

> 通过GitHub搜索 `肥宅快乐上网`、`肥宅上网`、`开心上网`、`快乐上网`  
> 都能找到本项目。

----------------------------
# 前言
- 本文为私人导航页，请不要在互联网传播，别给自己和别人带来麻烦。  
- 通过GitHub搜索 `肥宅快乐上网`、`肥宅上网`、`快乐上网`、`开心上网`，都能找到本项目。
- 
- 翻墙，又名科学上网、魔法上网、高级上网、VPN上网、谷歌网络、特殊网络、代理上网、出国留学、出国、外网、起飞等等，在中国大陆是违法行为，禁止在国内交流谈论，本文仅供海外华人、留学生等参考。  
- 上网步骤：科学软件+机场节点=起飞成功！  

----

# VPN客户端 / 软件工具
> 文章分享的所有客户端，都是开源免费的，在 GitHub 可以审阅源码。  
> 同时也建议别乱用不熟悉的软件  
> 软件作恶的破坏力，取决于开发者水平上限, 和道德下限。

## 【电脑端】Windows and MacOS
- [Clash Verge Rev](https://github.com/clash-verge-rev/clash-verge-rev/releases)  现在主流的开源跨平台 clash 客户端，非常推荐！
	- `Windows` 、`MacOS`、`Linux` 系统版本均支持。
	- windows 下载使用 `_x64-setup.exe` 安装包版，不推荐便携版（点击 `Assets` 可展开，列表末尾有展开全部 show more）
	- 由于clash 内核作者和 clash for windows 作者跑路，[【跑路事件】](https://jichanggo.com/clashforwindows%e5%88%a0%e5%ba%93%e8%b7%91%e8%b7%af)， 旧版 clash 无人维护更新，现在更推荐用 `Clash Verge Rev`

- [旧版 Clash for windows 汉化包作者提供的版本](https://github.com/Z-Siqi/Clash-for-Windows_Chinese/releases) 不推荐。
	- 汉化包作者提供了删库前的版本，和打包的汉化版。（现已无人维护更新，尽快迁移至 `Clash Verge Rev`）
	- 已知的bug，clash在不退出的情况下关机，下次开机将会无法联网，解决办法是启动clash再关闭能解决，但是避免麻烦尽量关机前退出clash。  

- [v2rayN](https://github.com/2dust/v2rayN/releases) 经典老牌VPN工具，功能强大的代理客户端，支持 VMess、VLESS、Trojan、Shadowsocks 等多种协议

## 【Android 安卓客户端】  
- [FlClash](https://github.com/chen08209/FlClash/releases) （推荐）
	- FlClash 基于 ClashMeta 的开源多平台代理客户端
	- 下载 `android-arm64-v8a.apk`  , 老手机用 `v7a` 
	- 另外，FlClash 也有 Windows 和 Mac 和 Android 端，也推荐使用。

- [Clash for Android](https://github.com/Z-Siqi/Clash-for-Windows_Chinese/releases/tag/CFA)   旧版，不推荐。
	- 下载高级通用版 `premium-universal-release.apk`

### 【其他】
- 苹果手机/平板等ios系统，请参考机场给出的解决办法，一般为`ShadowRocket`，俗称小火箭，因为国内Apple ID无法下载，需要境外的ID，一般通常机场会免费提供Apple ID，请仔细阅读机场网站的教程和注意事项，或者咨询机场客服。  

## 使用教程 (简易版)

- 电脑/手机端 `Clash 系列`
	- 复制机场的订阅链接，粘贴到 `clash` 订阅里点 `下载/导入` 即可。
- 电脑端设置
	- 这两个选项可视为翻墙总开关，只开其中一个即可，或着都开，能顺利打开 谷歌/YouTube ，即翻墙成功。
		- 1，设置里打开 `TUN 模式`，即虚拟网卡上网，比较万能通用，但需管理员权限。
		- 2，或打开 `系统代理`，即电脑设置里VPN功能。
- 安卓 FlClash 设置
	- 打开 `配置`，新建，将订阅链接导入 URL 提交
	- 点 `代理`， 选择流畅的节点
	- 点 `仪表盘`，点右下角播放图标，开启 VPN 功能开关，即可。
- 其他客户端大同小异，不会的去 YouTube 搜教程。
- 
- 【最后】
	- 尽量使用 `规则` 模式，别用 `全局`，全局意思是所有网络数据都走代理翻出去，你国内的账号不想要了？有账号风控和隐私等等各种风险。
	- `规则模式`，也叫 `gfw` 模式，意思是`国外软件/网站`走代理翻墙，国内的软件/网站不翻走直连，更稳妥。

---
# 机场

> **提醒一下：上网流不流畅、卡不卡顿、网速、延迟等等的这些因素，是由机场的优劣决定的，想要良好的上网体验，请自行寻找优秀的机场。**
>   
> 免费便宜的机场都不太稳定。  所有机场，在晚上高峰时期都不稳定（别说机场了家用宽带也卡）
>   
> 有任何问题请联系机场客服
> 推荐用我的 `邀请码` 注册，很多机场主对邀请用户有折扣 或账户优先权重。


- [淘气兔](https://taoqitu.me/index.html?register=PmjukBYS)，7.8元/月100G，12元/月200G，按量付费22元100G，66元400G
	- 价格便宜，月付和按量付费都很便宜，实测稳定性不错。

- [ButBit坚果机场](https://www.nutbit.net/#/register?code=zrwBmric) ，15元/3个月50G每月，10元/月100G，15/月200G
	- 还不错，便宜好用，实测稳定性还可以。

- [云通机场](https://yuntong.one/#/?code=rI51UtfM)  不限时长，按量付费！
	- 只算流量，没有月付套餐。￥0.1-0.3/GB，1元起充，首单10元获赠5元，实测速度延迟都不错，推荐！
	- **发现节点ip经常变，对ip固定有要求的别买，要求不高的没事** 

- [OuO专线机场](https://login.ouonetwork.com/register?aff=YsDwuCds)  月付10元100G, 18/200G。（现可打85折）
	- 实测效果不错节点多延迟低，用我的邀请码 `YsDwuCds` 注册，下单优惠码填`DUANG114514`打8.5折即8.5/月

- [流量光机场](https://llgjc1.com/#/register?code=Far4jGKn)   4.9元/月150G，9.9/月300G，按量付费30/500G。
	- 实测延迟稳定还可以，便宜大碗的机场

- [XFLTD养鸡场](https://xfltd.org/#/register?code=rFmCLdkn)  7元/月150G，不限时按量付费 10元120G, 20元250G
	- （2025.2补充: 最近用的人多了速度一般般，只剩价格优势了） 

- 
- ~~飞鸟云 （按流量计费的机场，10元200G，15元400G，20元600G等，不限时，限3设备~~  不太行，一片红    
- ~~魔戒 （按流量计费的机场，1元10g，12元130g等，不限制使用时间/人数/设备）~~  不太行，一片红  


- [ ] 另外，以备不时之需，老司机们通常会准备好几个机场，防止与世界失联！   避免陷入了 `只有翻出去才能买机场，但没有机场又翻不出去` 的死循环。
- [ ] 备用机场推荐 不限时按量付费 的机场。
- [ ] 另外，非常推荐按量付费的机场，使用量不大、不下载，通常10块钱可以用半年，非常nice！  

## 其他问题
**以上内容能解决大部分问题了，如果还碰到了其他的问题，该如何解决？**  
- 大部分机场网站首页都写了很详细的教程可以参考，以及咨询机场客服、或机场TG群。  
- 99%的问题，都能在YouTube 和Google上面，可以搜索到大量的视频教程、攻略、讲解等等内容。  
- 别像个傻比一样，在百度搜索、在 头条/西瓜/抖音/B站/知乎/QQ/微信 这些地方找，还有在QQ群上面问的。求求你，别害人了，别人真的好心帮你了，会封号/喝茶/铁窗泪的。  

**最后，如果真的解决不了，请放弃这件事情。**

---
# 个人小 Tips
- 不要用 `QQ` `微信` 传输机场订阅链接、VPN安装包等等信息，100%会被标记成分！QQ微信B站有人做过测试，发链接100%会被腾讯访问。
- 不要在国内任何软件上，教别人翻墙、给别人发机场链接、发VPN软件链接，100%自动识别，飞机群已经有人中招了，直接封号，封号算轻的，缺指标了直接铁窗泪。
- 
- 若需要 `电脑` 和 `手机` 之间传安装包、订阅链接，用局域网传输工具。
	- [【LocalSend】官网](https://localsend.org/zh-CN) |  [【localsend】开源链接](https://github.com/localsend/localsend)  
	- 推荐使用 `Localsend` ，开源免费，局域网传输，纯离线运行。
		- 需要手机电脑在同一个路由器下面，才是局域网。
		- 手机电脑都装一个，方便局域网传输各种资料/文件/链接。
		- 嫌麻烦可以只装电脑端，拖文件进窗口，发送模式通过链接，手机端的浏览器扫码，或输入局域网地址，即可访问下载。

----------------------------
# 其他网站、工具：
- [科学网络测速](https://fast.com/zh/tw/)
- [ip111.cn 全方位查询您的IP地址](https://ip111.cn/)
- [IP纯净度检测Scamalytics](https://scamalytics.com/)
- [IP服务器检测](https://ipinfo.io/)
- [检查IP地址和DNS 隐蔽性和纯净度](https://whoer.net/zh)

----------------------------
## 路由器 科学上网
> 以下内容均为 2022年 左右的硬件，内容可能过时、失效，数码产品月月新，请自行寻找。  

- **入门级家用路由器，硬路由刷固件，实现科学上网**  
	- **红米AC2100路由器**（捡二手百元左右），刷OpenWrt固件或老毛子固件。这款路由器比较热门，性价比还算OK，缺点是性能一般，科学速度跑不满百兆，最高70M左右。  
    [B站刷固件教程视频](https://www.bilibili.com/video/BV1HZ4y1P7A9) ，[YouTube 刷固件+FQ教程](https://youtu.be/jBaMRhda4Dk) ，
    [OpenWrt 固件视频 YT](https://youtu.be/1OPZVrrZ9xc) - [【恩山固件帖子】](https://www.right.com.cn/forum/thread-8234820-1-1.html) - [【固件下载链接](https://sssddddff.lanzouh.com/iwWuG05fla7e)  
    推荐OpenWrt，功能强大，在YouTube搜索，有非常多各种固件、版本的中文教程。  
    - **兆能M2**，（百元左右），比较热门，CPU型号高通IPQ6000，性能还行，刷openwrt固件，过程比红米ac2100稍微繁琐一点点，相关内容：[acwifi文章推荐](https://www.acwifi.net/13962.html)，[什么值得买文章](https://post.smzdm.com/p/avxe2m44/)，[B站视频](https://www.bilibili.com/video/BV1Hr4y1B7F2/)。  
    - **360T7**，（百元左右），CPU型号MT7981，性能还行，可刷 Hanwckf H大的openwrt固件，过程比红米ac2100稍微繁琐一点点，相关内容：[acwifi文章推荐](https://www.acwifi.net/22217.html)，[B站视频](https://www.bilibili.com/video/BV18e4y1g7VL/)，[图文教程](https://qust.me/post/360t7-openwrt/)，[Hanwckf图文教程](https://cmi.hanwckf.top/p/360t7-firmware/)。  
- **网关模式**：这个方式有多种叫法，网关模式、局域网共享、旁路由、单臂路由、透明网关，叫法不同，作用类似，通过电脑或手机里的科学软件，比如clash，开启局域网端口，就可以实现这个路由器下的这个端口的设备都能科学上网，缺点是每个设备第一次连接时，需要多一步设置手动代理、填ip填端口，有点麻烦，除非，在路由器里关闭dhcp设置静态ip并指向共享网络的设备的ip，就能避免手机等设备需要改设置的问题，但是不建议使用，一般人搞不明白，能搞明白的人不需要这么繁琐的东西。并而这样做，且始终需要一台手机电脑等设备，时时刻刻分享局域网代理，这个只适合短时间内电脑给手机、平板、VR等设备，共享网络，不太适合长时间使用。[教程链接](https://youtu.be/Y6dDuL73Vxo) （或自行查找其它教程）  
- **软路由+OpenWrt** ，算是终极解决方法了，软路由做主路由拨号，普通硬路由器做AP，是目前比较主流的性价比、方便、快捷、性能强悍的解决方案。  
	- 软路由性能强大，功能丰富，拓展性强，大部分设备最低都可以局域网2.5G，科学千兆。  
	- 常见的软路由价格在200-1000左右，通常为四五百，且配置起来稍微繁琐。  
	- 软路由固件推荐使用`OpenWRT` ，或者 [iStoreOS](https://github.com/istoreos) （一个由 `OpenWRT` 简化优化之后的固件，口碑挺不错！[(youtube视频介绍)](https://www.youtube.com/watch?v=8NCydysULe8)）  
	- **常见的软路由设备型号：**  
		- ARM架构:R4S\R2S\R5S\H68K\R68s 等等，折腾难度比x86低一点点  
		- X86架构：J1900\J4125\N5105等处理器的工控机/小主机，其他更多型号和推荐，在YouTube可以找到很多相关的内容。  

----------------------------

## 出去之后 

- [【翻墙必看】为什么翻墙被发现？老手都犯的错误](https://www.youtube.com/watch?v=r5_XFK6UBGs) YouTube 视频 
- 
- [中国防火墙究竟是怎么运作的？ 科普](https://www.youtube.com/watch?v=i8Iiv9yFTdM)
- [防火墙/GFW是什么？为什么会有墙？](https://youtu.be/XKZM_AjCUr0) 电丸科技AK
- [多种翻墙方式的利弊和特点 你更适合哪一种？ 翻墙方式科普](https://youtu.be/f9ohvZyQrmY) 电丸科技AK
- [软路由指南](https://www.youtube.com/watch?v=JfSJmPFiL_s) 【从零开始】新手入门软路由指南，什么是软路由？ by 不良林  

## YouTube频道推荐：
- [李子柒](https://www.youtube.com/@cnliziqi/videos)
- [安争鸣](https://www.youtube.com/@anzhengming/videos)
- [小岛大浪吹](https://www.youtube.com/@xiaodaodalang/featured) 
- [四處觀察](https://www.youtube.com/@sichuguancha) 
- [小叔TV](https://www.youtube.com/@xiaoshu)
- [56BelowTV 零下56](https://www.youtube.com/@56BelowTV/featured)
- [跟洋妞学英语 Jacki](https://www.youtube.com/c/JackiesEnglishClass/featured)
- [老高與小茉](https://www.youtube.com/channel/UCMUnInmOkrWN4gof9KlhNmQ/featured)
- ...

---

## 浏览器插件工具推荐

- 浏览器推荐
	- [谷歌Chrome浏览器](https://www.google.com/chrome/)、国内的 [百分浏览器](https://www.centbrowser.cn/) 
	- 其它360浏览器等等的都不推荐使用，网址都会被云检测。
- 以下为浏览器插件使用推荐

- [划词翻译](https://hcfy.app/)
- [YouTube 双字幕自动翻译](https://chrome.google.com/webstore/detail/youtube-dual-subtitles/hkbdddpiemdeibjoknnofflfgbgnebcm)
- [视频倍速播放  适用于大部分网站视频](https://chrome.google.com/webstore/detail/video-speed-controller/nffaoalbilbmmfgbnbgppjihopabppdk)  
- [跨浏览器同步书签](https://chrome.google.com/webstore/detail/floccus-bookmarks-sync/fnaicdffflnofjppbagibeoednhnbjhg/related)

- [暴力猴-脚本管理器](https://chromewebstore.google.com/detail/%E6%9A%B4%E5%8A%9B%E7%8C%B4/jinjaccalgkegednnccohejagnlnfdag)  -  [油猴-脚本管理器](https://chrome.google.com/webstore/detail/tampermonkey/dhdgffkkebhmkfjojejmpbldmpobfkfo?hl=zh-CN) 
	- 油猴、暴力猴本质是一个东西
- [油猴脚本下载站](https://greasyfork.org/zh-CN/scripts) 配合搜索，可以很方便找到各种优秀的插件  
- 油猴插件推荐
    - [隐藏Google+YouTube广告（推荐）](https://greasyfork.org/zh-CN/scripts/38182-hide-youtube-google-ad)
    - [YouTube视频下载](https://greasyfork.org/zh-CN/scripts/369400-local-youtube-downloader)
    - [Github增强 下载加速](https://greasyfork.org/zh-CN/scripts/412245-github-%E5%A2%9E%E5%BC%BA-%E9%AB%98%E9%80%9F%E4%B8%8B%E8%BD%BD)
    - [bilibili 页面净化大师](https://greasyfork.org/zh-CN/scripts/479861-bilibili-%E9%A1%B5%E9%9D%A2%E5%87%80%E5%8C%96%E5%A4%A7%E5%B8%88)

## 电影、字幕、电视剧、影视

- [聚BT - 在线影视板块 - 合集导航](https://jubt.fun/cn/index.html#在线影视)
- [破解资源君的在线电影网站推荐 - 合集推荐](https://github.com/pojiezhiyuanjun/freemovie/wiki)
- [Sukebei 磁力种子+ 外](https://sukebei.nyaa.si)
- 
- [mp4电影](www.domp4.cc) 资源一般
- [迅雷电影天堂](https://www.xl720.com) 好像还行，但资源容量偏小
- 
- [字幕库2](https://zimuku.org)
- [字幕库3](https://zmk.pw/)
- [射手网[伪]](secure.assrt.net) 字幕网站

----------------

## 常用站点/推荐

- [YouTube 全球最大的视频网站](https://www.youtube.com/)
- [Telegram 电报](https://telegram.org/) 
	- 简称TG或飞机，国外常用的聊天工具, 开源软件。吊打QQ微信
	- [视频教程](https://youtu.be/zKSoN0ZHqso) / [TG电报频道搜索网](https://cn.tgstat.com/)  
- [Quora 国外版知乎, 在线问答网站](https://www.quora.com/)
- [Reddit 娱乐、兴趣、社交、论坛、新闻等交流网站](https://www.reddit.com/)
- [Discord 大型互联网社群、兴趣交流社区](https://discord.com/)
- [全球上网测速](https://fast.com/zh/tw/) 测机场速度
- [1337X 搜种子电影音乐等等](https://www.1377x.to/)
- [互联网时光机-查看某个网站，多年前的样子](https://web.archive.org/)
- [外国接码网站 - SMS-Activate （收费）](https://sms-activate.org/cn)
- 
- [APK Downloader 下载Google Play里的app，填入app链接](https://apps.evozi.com/apk-downloader/)
- [Google Play 谷歌商店官网，安卓App应用官网](https://play.google.com/store/apps) 搭配上面↑ 的APK下载网站，可以下载安卓apk应用，解决国内手机没有谷歌商店，无法下载应用的问题。  
- [APKPure应用商店,下载全球app的安卓APK](https://apkpure.com/cn/)
- [9Apps 阿里出品的国际第三方 安卓应用和游戏商店（可下载国外应用软件）](https://www.9apps.com/)
- 
- [YouGlish - 输入英语单词或句子，搜索在YouTube 视频里的发音/读音](https://youglish.com)

## 邮箱相关
- [电子邮箱推荐](https://qiangwaikan.com/best-email-provider/)
-   
- [谷歌邮箱Gmail，全球上网冲浪必备！（注册谷歌号即可）](https://mail.google.com/)
- [微软邮箱，免手机号，上网冲浪必备！](https://outlook.live.com/mail/0/)
- [Tutanota邮箱 开源、端到端加密邮箱](https://tutanota.com/)
- [一次性邮箱](https://temp-mail.org/zh)

## 老色批
- [Sukebei 磁力种子](https://sukebei.nyaa.si/)  
- https://theporndude.com/zh porn导航站
- [P站](https://cn.pornhub.com/)
- [JavDB番号影片数据库](https://javdb.com/)

----------------------------

## 这篇文章是什么？有什么用？

GitHub 笔记文章、导航页，方便收藏链接、查找检索、跨设备浏览，仅用于朋友间交流。  并收藏了现在主流的优秀的流程和工具，避免踩坑和不必要的折腾。    
请正确使用科学上网功能，查询论文资料，学习优秀的学术知识，和以及看美剧，学英语等等。  
不要观看那些傻比网站，也不要发表任何观点，请遵守国内和国外的法律，作为成年人要为自己言行负责。  
**本文禁止在国内任何社交平台、论坛转载发表，本GitHub项目谢绝Star和Fork**  

---

## 更新日志

- 2025年2月11日
	- 回头看了一下之前写的内容，有很多失效和不合理的内容，最近机场用的多了更新了几个还不错的，顺便把一些失效的链接推荐给删了，去掉一些没价值的内容。其他内容推荐你们刷 YouTube，我推荐的东西始终有局限性，尝试去搜索，可以学到不少知识。

