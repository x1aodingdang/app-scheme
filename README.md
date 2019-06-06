# app-scheme
记录关于app的一些协议


【如何查看 app 的 URL Schemes ?】
这个取决于这个APP有没有设置URL Scheme，如果没有设置, 肯定找不到。
步骤如下：
1.在电脑上使用iTunes下载那个app
2.下载完后，在itunes里点击这个app，选择->Show in Finder，看见的是一个.ipa文件
3.将文件名的后缀 .ipa 改成 .zip 然后解压
4.打开解压后的文件，找到Payload文件夹并打开，里面只有一个文件
5.右击这个文件，选择-->显示包内容
6.这时候会有很多文件，包括图片什么的，在这个文件夹中搜索，找到info.plist文件并打开
7.在plist文件中搜索CFBundleURLSchemes，会找到URL Schemes.(可能会存在多个URL Scheme，因为这里包括当前app的URL Scheme和要跳转到app的URL Scheme，可以根据URL identifier区分)

【常用APP的Url Scheme 前缀】

QQ mqq://
微信是 weixin://
网易新闻 newsapp://
淘宝 taobao://
点评 dianping:// dianping://search
微博 sinaweibo://
weico微博 weico://
支付宝 alipay://
豆瓣fm： doubanradio://
微盘 sinavdisk://
网易公开课 ntesopen://
美团 i*******://
人人 renren://
我查查 wcc://
1号店 wccbyihaodian://
有道词典 yddictproapp://
知乎 zhihu://
优酷 youku://
ZAKER zakeripad://
mdict mdict://
京东hd openApp.jdiPad://
易迅 icson://；yixunipad://
wunderlist wunderlist://
支付宝 alipay://
查找朋友 grenada://；findmyfriends://；fmf1://
查找iphone fmip1://
触宝拨号：dialer://
蜂窝网络：prefs:root=MOBILE_DATA_SETTINGS_ID
WIFI：prefs:root=WIFI（WIFI这几个字母一定要大写）
定位服务：prefs:root=LOCATION_SERVICES
备忘录：mobilenotes://
高德地图：iosamap://
今日头条 snssdk141://
挖财记账 wacai://
QQ音乐 :QQmusic://
猎豹浏览器:sinaweibosso.422729959://
UC浏览器:ucbrowser://
支付宝:alipay://
优酷:youku://
节奏大师:节奏大师tencentrm://
刀塔传奇:刀塔传奇teiron2273://
天天动听:ttpod://
淘宝taobao://
名片全能王camcard://
支付宝alipay://
豆瓣fm：doubanradio://
微盘 sinavdisk://
网易公开课ntesopen://
我查查 wcc://
1号店wccbyihaodian://
有道词典yddictproapp://
知乎zhihu://
墨客 com.moke.moke-1://
名片全能王 camcard://
扫描全能王 camscanner://
12306订票助手 trainassist://
金山词霸 com.kingsoft.powerword.6://
节奏大师 tencentrm://
凤凰新闻 comIfeng3GifengNews://
高铁管家 gtgj://
飞信 fetion://
豆瓣FM doubanradio://
大智慧 dzhiphone://
布卡漫画 buka://
爱奇艺PPS ppstream://
哔哩哔哩动画 bilibili://
56视频 com.56Video://
365日历 rili365://
58同城 wbmain://
遇见 iaround://
陌陌 momochat://
旺旺卖家版 wangwangseller://
有道词典 yddict://
掌阅iReader iReader://
艺龙旅行 elongIPhone://
迅雷+迅雷云播 thunder://
熊猫公交 wb1405365637://
携程无线 CtripWireless://
无线苏州 SuZhouTV://
唯品会 vipshop://
微视 weishiiosscheme://
微拍 wpweipai://
旺信 wangxin://
网易公开课 ntesopen://
网易将军令 netease-mkey://
万年历 youloft.419805549://
土豆视频 tudou://
同花顺 amihexin://
天涯社区 tianya://
天气通Pro sinaweatherpro://
天气通 sinaweather://
墨迹天气 rm434209233MojiWeather://
腾讯新闻 qqnews://
腾讯微云 weiyun://
腾讯地图 sosomap://
淘宝旅行 taobaotravel://
人人 renrenios://
蜻蜓FM qtfmp://
浦发银行 wx1cb534bb13ba3dbd://
招商银行 cmbmobilebank://
支付宝 alipay://
建设银行 wx2654d9155d70a468://
工商银行 com.icbc.iphoneclient://
酷我音乐 com.kuwo.kwmusic.kwmusicForKwsing://
酷狗音乐 kugouURL://
京东 openApp.jdMobile://
QQ音乐 qqmusic://
QQ斗地主 tencent382://
QQ浏览器 mttbrowser://
QQ安全中心 qmtoken://
QQ国际版 mqqiapi://
PPTV pptv://
爱奇艺视频 qiyi-iphone://
暴风影音 com.baofeng.play://
保卫萝卜2 wb2217954495://
保卫萝卜 wb1308702128://
百度云 baiduyun://
百度音乐 baidumusic://
百度视频 baiduvideoiphone:// 或 bdviphapp://
百度糯米 bainuo://
百度魔图 photowonder://
百度魔拍 wondercamera://
百度地图 baidumap://
百度导航 bdNavi://
百度视频hd BaiduVideoiPad://；baiduvideoipadapp://
百度相册hd BaiDuCloudAlbumHD://
百度浏览器hd bdbrowser://
百度文库hd bdwenku://
搜狗输入法 com.sogou.sogouinput://
搜狐视频 sohuvideo-iphone:// 或 sohuvideo://
搜狐新闻 sohunews://
随手记 FDMoney://
腾讯企业邮箱 qqbizmailDistribute2://
腾讯手机管家 mqqsecure://
腾讯视频 tenvideo:// 或 tenvideo2:// 或 tenvideo3://
腾讯微博 TencentWeibo://
天猫 tmall://
天天星连萌 tencent100689806://
天天爱消除 tencent100689805://
天天酷跑 tencent100692648://
天天飞车 tencent100695850://
天天动听 ttpod://
威锋网 com.weiphone.forum://
新浪微博 weibo:// 或 sinaweibo://
网易邮箱 neteasemail://
百度输入法 BaiduIMShop://
C浏览器 ucbrowser://
一个one clover-one://
当当hd dangdanghd://；ddhd://
大众点评hd dianpinghd://
多看阅读 duokan-reader://
艺龙旅行hd elongiPad://
圈点hd skitch://
印象笔记hd enx://
电话 mobilephone://
备忘录 mobilenotes://
设置 prefs:root=SETTING
定位服务 prefs:root=LOCATION_SERVICES
E-Mail MESSAGE://
popAgraph popagraphtumblr://
dropbox db-auth://；dbapi-1://；dbapi-2://；dbapi-3://
goodreader ghttp://；ghttps://；grhttp://；grhttps://；giwhttp://；giwhttps://；gropen://；com.goodreader.sendtogr://
ifttt ifttt://
名片全能王hd camcard://；CamCardHDOpenAPI://
拉手团购hd LaShouGroupHDPay://
美团hd i*******://evermemo evermemo://
网易云课堂 wangyiyunketang://
网易公开课 ntesopen://
订票助手2 trainassistfree://
pcalc lite pcalc://
爱奇艺视频 QIYIHD-iPad://
三国kill sgk://
扇贝新闻 shanbaynews://
扇贝单词 shanbay://
扇贝单词hd shanbaywordshd://
skype skype://
搜狐视频hd sohu-SViPad://；sohuvideohd://
teamviewer:teamviewer8://
格志 griddiary://；sumi-interactive://
淘宝hd taobao://；itaobao://；taobaohd://
天猫 tmall://
腾讯视频hd tenvideohd://；tenvideo2://
qq通讯录 tencentappqqpim://
同步推正版HD tbtui://；tuihd://
航旅纵横pro umetrippro://mathpad myscriptmathpad://
雅虎天气！ yweather://
一号店 ipadstore://
优酷hd youkuhd://
知乎 zhihu://
欧陆词典pro eudic://
拓词 towordsp://
TuneIn Radio tunein:// 或 tuneinpro://
OfficeSuite mobisystemsofficesuite://
WPS Office KingsoftOfficeApp://
Line line://1Password onepassword://
Clear(著名的Todo应用) clearapp://
Chrome谷歌浏览器 googlechrome://
Calendars 5 calendars://
PDF Expert 5 pdfexpert5presence://
Documents 5 rdocs://
nPlayer nplayer-http://
GPlayer gplayer://
AVPlayer HD AVPlayerHD://
AVPlayer AVPlayer://
Ace Player aceplayer://


【系统的Url Scheme 】
电池电量 Prefs:root=BATTERY_USAGE
通用设置 Prefs:root=General
存储空间 Prefs:root=General&path=STORAGE_ICLOUD_USAGE/DEVICE_STORAGE
蜂窝数据 Prefs:root=MOBILE_DATA_SETTINGS_ID
Wi-Fi 设置 Prefs:root=WIFI
蓝牙设置 Prefs:root=Bluetooth
定位设置 Prefs:root=Privacy&path=LOCATION
辅助功能 Prefs:root=General&path=ACCESSIBILITY
关于手机 Prefs:root=General&path=About
键盘设置 Prefs:root=General&path=Keyboard
显示设置 Prefs:root=DISPLAY
声音设置 Prefs:root=Sounds
App Store 设置 Prefs:root=STORE
墙纸设置 Prefs:root=Wallpaper
打开电话 Mobilephone://
世界时钟 Clock-worldclock://
闹钟 Clock-alarm://
秒表 Clock-stopwatch://
倒计时 Clock-timer://
打开相册 Photos://

