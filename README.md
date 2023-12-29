# Quantumult_X-pro
- [Quantumult小白基础教程请自学](https://github.com/erdongchanyo/Rules/tree/main/Quantumult%20X)；
- 本文重点介绍关于Quantumultx的自建策略，包括分流、重写等资源。内容简单，只需要按步骤跟做；
## 分流规则：
### 步骤：点击小风车→分流（规则资源）→右上角标志（填加分流资源）
<img width="665" alt="iShot_2023-12-25_17 32 14" src="https://github.com/yidianhongxin/Quantumult_X-DRL/assets/11401362/f2161ba2-e632-4c91-88c7-c657dc7297ff">
<img width="445" alt="image" src="https://github.com/yidianhongxin/Quantumult_X-DRL/assets/11401362/1277b892-26fa-43f1-9b08-cd0f32c40949">

### 以下为具体分流规则（点击链接，复制网址）：
- [AI网站的分流策略](https://raw.githubusercontent.com/yidianhongxin/Quantumult_X-DRL/main/AI_qx.list)：ChatGPT、Claude、Copilot、Bard等主流AI网站分流规则；
- [国区网站分流](https://raw.githubusercontent.com/yidianhongxin/Quantumult_X-DRL/main/CN_Direct.list)：国内常用网站分流规则，不断更新中……
- [外区网站分流](https://raw.githubusercontent.com/yidianhongxin/Quantumult_X-DRL/main/Global.list)：推特、微软、电报、google等分流规则；
- [国外流媒体](https://raw.githubusercontent.com/yidianhongxin/Quantumult_X-DRL/main/StreamingMedia.list)：youtube、tiktok等规则；
- [国内IP直连](https://github.com/yidianhongxin/Quantumult_X-DRL/blob/main/GEOIP%20(CN).list)：汇总了一些可判定为国内IP的地址进行直连；
- [毒奶去广告](https://github.com/yidianhongxin/Quantumult_X-DRL/blob/main/Adblock4limbo.list)：毒奶去广告的备份库（避免作者删库的备份）；
- [苹果🍎网址分流](https://github.com/yidianhongxin/Quantumult_X-DRL/blob/main/GEOIP%20(CN).list))：判定为苹果网址来源的分流集合；
- [禁止iphone升级](https://github.com/yidianhongxin/Quantumult_X-DRL/blob/main/BlockiOSUpdate.list)：禁止iphone手机升级；
## 节点策略设置：
由于分流规则中会引用到对应的策略，所以创建名称必须和以下策略名称一一对应，才能无缝运行；创建策略的方法如下：
### 自定义策略→填加新策略
- 类型选择：Url-latency-benchmark（该类型为自动选择最优节点）；
- 策略名：按以下策略名一一对应创建，如：🤖 AI -美英；
- 图标：图标可自定义，也可按我提供的对应图标；
- 需匹配的资源标签-正则：.*
- 需匹配的节点标签-正则：United States|美国|United Kingdom|英国（释义：每个人的机场节点不同，这个意思是选机场里含有美国和英国的节点，如果节点没有这些可更换其它开头的节点）
#### 举例：“🤖 AI -美英”策略的设置
![WechatIMG507](<img src="https://github.com/yidianhongxin/Quantumult_X-DRL/assets/11401362/a4d2da6f-2f0f-4042-acc1-b1dcc82208ec"style="width:50%; ">)

### 以下是分流规则名称和“需匹配的节点标签”
- 🎵 TikTok：美国|United States
- 🇺🇸 漂亮专用：美国|United States
- 🛫 🔥超速通过：香港|Hong Kong
- bard-欧、英、瑞士：United Kingdom|German|French|英国|瑞士|德国
- 🤖 AI -美英：United States|United Kingdom
- 🐟 Final：香港|Australia

