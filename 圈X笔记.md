# 圈 X / Quantumult X 备忘录

## 1️⃣大佬主页

排名不分先后（仅作自己收藏用）

- [Orz-3](https://raw.githubusercontent.com/Orz-3/QuantumultX/master/Orz-3.conf)
- [KOP-XIAO](https://raw.githubusercontent.com/KOP-XIAO/QuantumultX/master/QuantumultX_Profiles.conf)
- [DivineEngine 神机](https://raw.githubusercontent.com/DivineEngine/Profiles/master/Quantumult/Outbound.conf)
- [NobyDa野比](https://github.com/NobyDa)
- [erdongchanyo 耳东橙](https://github.com/erdongchanyo/Rules/blob/main/Quantumult%20X/README.md) (教程清晰)
- [Cuttlefish 墨鱼](https://github.com/ddgksf2013/Cuttlefish)
- [limbopro 毒奶](https://raw.githubusercontent.com/limbopro/Profiles4limbo/main/full.conf)
- [Tartarus2014 烧烤哥](https://raw.githubusercontent.com/Tartarus2014/QuantumultX-Script/main/QuanX.conf)
- [zwf234 奇心科技](https://raw.githubusercontent.com/zwf234/rules/master/QuantumultX/qixin.conf)
- [w37fh 北纬37度的大飛](https://raw.githubusercontent.com/w37fhy/QuantumultX/master/QuantumultX_diy.conf)
- [blackmatrix7](https://github.com/blackmatrix7/ios_rule_script)（去广告很好用）
- [ id77](https://github.com/id77/QuantumultX)
- [zqzess](https://github.com/zqzess/rule_for_quantumultX/tree/master/QuantumultX) (有简洁版配置)

## 2️⃣懒人配置

```
https://raw.githubusercontent.com/erdongchanyo/Rules/main/Quantumult X/LazyConf/QuantumultX_EDC-Lazy.conf
```

- [Cuttlefish 墨鱼](https://raw.githubusercontent.com/ddgksf2013/Cuttlefish/master/Profile/QuantumultX.conf)  特别多好用的规则

```
https://raw.githubusercontent.com/ddgksf2013/Cuttlefish/master/Profile/QuantumultX.conf
```

- [zqzess](https://github.com/zqzess/rule_for_quantumultX/tree/master/QuantumultX) 简洁版配置

```
https://raw.githubusercontent.com/zqzess/rule_for_quantumultX/master/QuantumultX/zqzess_lite.conf
```

## 3️⃣分流

#### 规则分流(可能有用-备忘)

- **blackmatrix7**
  
  ```
  https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/QuantumultX/Advertising/Advertising.list
  ```
- **NobyDa**
  
  ```
  https://raw.githubusercontent.com/NobyDa/ND-AD/master/QuantumultX/AD_Block.txt
  
  https://raw.githubusercontent.com/NobyDa/ND-AD/master/QuantumultX/AD_Block_Plus.txt
  ```

## 4️⃣复写

- [奇心合集](https://raw.githubusercontent.com/zwf234/rules/master/QuantumultX/qxrules.conf)
- [墨鱼](https://raw.githubusercontent.com/ddgksf2013/Cuttlefish/master/Profile/QuantumultX.conf)
- 🍅番茄小说去广告
  
  ```
  https://raw.githubusercontent.com/zqzess/rule_for_quantumultX/master/QuantumultX/rewrite/FanQieNovel.qxrewrite
  ```

## 5️⃣脚本

- **墨鱼脚本**
  
  ```
  https://github.com/ddgksf2013/Cuttlefish/raw/master/Jd/Task/jd_task.json
  ```
- **奇心脚本合集**
  
  ```
  https://raw.githubusercontent.com/zwf234/rules/master/QuantumultX/qixin.json
  ```

## 6️⃣VIP解锁

- **id77**
  
  ```
  https://raw.githubusercontent.com/id77/QuantumultX/master/rewrite/vip.conf
  ```
- 墨鱼
  
  ```
  https://raw.githubusercontent.com/ddgksf2013/Cuttlefish/master/Rewrite/UnlockApp.conf
  ```
- **哔哩哔哩番剧开启1080P+ （by NobyDa）**
  
  ```
  #hostname=api.bilibili.com, app.bilibili.com
  
  ^https:\/\/ap(p|i)\.bilibili\.com\/((pgc\/player\/api\/playurl)|(x\/v2\/account\/myinfo\?)|(x\/v2\/account/mine\?)) url script-response-body https://raw.githubusercontent.com/zqzess/rule_for_quantumultX/master/js/backup/bilifj.js
  ```
  
  ```
  https:\/\/ap(p|i)\.bilibili\.com\/((pgc\/player\/api\/playurl)|(x\/v2\/account\/myinfo\?)|(x\/v2\/account/mine\?)) url script-response-body BiliHD.js
  ```
- **BiliBili 解锁1080P高码率+4K画质 (番劇和影視除外) @ddgksf2013**
  
  ```
  #hostname=api.bilibili.com
  
  ^https?:\/\/app\.bilibili\.com\/x\/v2\/account\/myinfo\? url script-response-body https://raw.githubusercontent.com/ddgksf2013/Cuttlefish/master/Script/bilibili_diy.js
  ```
- **#全能扫描王**
  
  ```
  hostname = *.intsig.net
  
  ^https:\/\/(api|api-cs)\.intsig\.net\/purchase\/cs\/query_property\? url script-response-body https://raw.githubusercontent.com/id77/QuantumultX/master/Script/camscanner.js
  ```

## 7️⃣其他

### #常用图标

- [Orz-3](https://github.com/Orz-3)/**[mini](https://github.com/Orz-3/mini)**
  
  🔘彩色版本
  
  ```
  https://raw.githubusercontent.com/Orz-3/mini/master/Color/name.png
  ```
  
  🔘透明版本
  
  ```
  https://raw.githubusercontent.com/Orz-3/mini/master/Alpha/name.png
  ```
- [Orz-3](https://github.com/Orz-3)/**[face](https://github.com/Orz-3/face)**
  
  ```
  https://raw.githubusercontent.com/Orz-3/face/master/name.png
  ```
- Koolson
  
  ```
  img-url=https://raw.githubusercontent.com/Koolson/Qure/master/IconSet/Netease_Music.png
  
  img-url=https://raw.githubusercontent.comKoolson/Qure/master/IconSet/Telegram.png
  
  img-url=https://raw.githubusercontent.com/Koolson/Qure/master/IconSet/WeChat.png
  
  img-url=https://raw.githubusercontent.com/Koolson/Qure/master/IconSet/YouTube.png
  ```


