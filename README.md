<div align="center">
<h3 align="center"><h1>爱快去广告规则</h1><h2>基于爱快DNS反向代理实现的去广告规则</h2>

<br>
<img src="https://img.shields.io/github/stars/houoop/ikuai-dns-adblock-rules?style=flat-square&color=yellow">
<img src="https://img.shields.io/github/forks/houoop/ikuai-dns-adblock-rules?color=orange&style=flat-square">
<img src="https://img.shields.io/github/issues/houoop/ikuai-dns-adblock-rules?color=green&style=flat-square">
<br>
<img alt="GitHub last commit" src="https://img.shields.io/github/last-commit/houoop/ikuai-dns-adblock-rules?style=flat-square">
<img alt="GitHub commit activity" src="https://img.shields.io/github/commit-activity/w/houoop/ikuai-dns-adblock-rules?style=flat-square">  
<img alt="GitHub commit activity" src="https://data.jsdelivr.com/v1/package/gh/houoop/ikuai-dns-adblock-rules/badge?style=flat-square">  
<br>

<br>
  

</div>                           
                                                                        
<!--br-->
## 项目说明

**一直以来爱快软路由由于具有人性化的WEB UI、强大的分流功能，以及可以免费在大量的低配置x86机器使用具有大量的受众，但是由于中国相关政策的原因，爱快厂商无法在系统中直接提供像openwrt里那样方便的去广告功能，本项目通过程序将网络中相关去广告规则转换为可以直接导入爱快系统中使用的文本**


### 📃 转换规则列表


|   规则名称   | 📎 爱快规则链接 |🚀 国内加速 | 原项目地址 | 备注
|     :----:  | :----:       | :----: | :----: | :----:
| Anti-AD规则  | [Github RAW](https://raw.githubusercontents.com/houoop/ikuai-dns-adblock-rules/main/anti-ad-for-ikuai.txt)   |[jsDelivr加速](https://fastly.jsdelivr.net/gh/houoop/ikuai-dns-adblock-rules@main/anti-ad-for-ikuai.txt)| [GITHUB REPO](https://github.com/privacy-protection-tools/anti-AD) |通用规则-条目60000+（推荐）（[有立场争议](https://github.com/Mosney/anti-anti-AD))
| AdRules规则  | [Github RAW](https://raw.githubusercontents.com/houoop/ikuai-dns-adblock-rules/main/adrules-for-ikuai.txt)   |[jsDelivr加速](https://fastly.jsdelivr.net/gh/houoop/ikuai-dns-adblock-rules@main/adrules-for-ikuai.txt)| [GITHUB REPO](https://github.com/Cats-Team/AdRules) |通用规则-条目60000+（推荐）
| 大圣净化规则  | [Github RAW](https://raw.githubusercontents.com/houoop/ikuai-dns-adblock-rules/main/ad-wars.txt)   |[jsDelivr加速](https://fastly.jsdelivr.net/gh/houoop/ikuai-dns-adblock-rules@main/ad-wars.txt)| [GITHUB REPO](https://github.com/jdlingyu/ad-wars) |适用于移动端-条目1000+
| SmartTV Block规则  | [Github RAW](https://raw.githubusercontents.com/houoop/ikuai-dns-adblock-rules/main/smarttv-block.txt)   |[jsDelivr加速](https://fastly.jsdelivr.net/gh/houoop/ikuai-dns-adblock-rules@main/smarttv-block.txt)| [GITHUB REPO](https://github.com/Perflyst/PiHoleBlocklist) |适用于智能电视-条目200+



#### 使用说明：
- **经测试导入上万条规则到爱快系统中不影响系统运行速度**

- **欲使用爱快DNS反向代理来去除广告需要在DHCP中设置爱快的地址为DNS服务器，并在DNS设置中开启DNS加速** -

- **也可以在DNS设置中开启强制客户端DNS代理，此时爱快将接管所有客户端的DNS解析，无论客户端设置任何DNS服务器** -

- **下载你想要的规则文本到本地，在DNS设置中导入txt文本规则到系统中即可** -
![](./iShot_2022-09-29_16.54.19.png)
## 🚛 自动更新规则

TODO

希望大家可以提交 Issue 或者 Request 来帮助我完善规则 🔍 我审核之后会加入到规则，如果规则有误杀我会尽快处理



## 访问量
![](http://profile-counter.glitch.me/houoop/count.svg)


## Star数

[![Stargazers over time](https://starchart.cc/houoop/ikuai-dns-adblock-rules.svg)](https://starchart.cc/houoop/ikuai-dns-adblock-rules)

