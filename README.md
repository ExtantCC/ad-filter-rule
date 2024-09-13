## AbBlock List

广告过滤规则整合，使用 [fordes123/ad-filters-subscriber v2](https://github.com/fordes123/ad-filters-subscriber/tree/v2)
构建。定期合并上游规则，去除重复以及包含无效域名的项目

| 文件              | 适用                          |        github        |         ghproxy          |         jsdelivr          |
|-----------------|:----------------------------|:--------------------:|:------------------------:|:-------------------------:|
| `easylist.txt`  | AdGuard、AdBlock 等主流去广告扩展和程序 | [link][easylist-raw] | [link][easylist-ghproxy] | [link][easylist-jsdelivr] |
| `dns.txt`       | AdGuard Home 等基于DNS的过滤工具    |   [link][dns-raw]    |   [link][dns-ghproxy]    |   [link][dns-jsdelivr]    |
| `dnsmasq.conf`  | dnsmasq 及其衍生版本              | [link][dnsmasq-raw]  | [link][dnsmasq-ghproxy]  | [link][dnsmasq-jsdelivr]  |
| `clash.yaml`    | clash 及其衍生版本                |  [link][clash-raw]   |  [link][clash-ghproxy]   |  [link][clash-jsdelivr]   |
| `smartdns.conf` | smartdns                    | [link][smartdns-raw] | [link][smartdns-ghproxy] | [link][smartdns-jsdelivr] |
| `hosts`         | 几乎所有操作系统原生支持                |  [link][hosts-raw]   |  [link][hosts-ghproxy]   |  [link][hosts-jsdelivr]   |
| `private.txt`   | 本仓库维护的私有规则，以 easylist 形式提供  | [link][private-raw]  | [link][private-ghproxy]  | [link][private-jsdelivr]  |

[easylist-raw]: https://raw.githubusercontent.com/xndeye/adblock_list/beta/rule/easylist.txt

[easylist-ghproxy]: https://ghproxy.net/https://raw.githubusercontent.com/xndeye/adblock_list/beta/rule/easylist.txt

[easylist-jsdelivr]: https://gcore.jsdelivr.net/gh/xndeye/adblock_list@beta/rule/easylist.txt

[dns-raw]: https://raw.githubusercontent.com/xndeye/adblock_list/beta/rule/dns.txt

[dns-ghproxy]: https://ghproxy.net/https://raw.githubusercontent.com/xndeye/adblock_list/beta/rule/dns.txt

[dns-jsdelivr]: https://gcore.jsdelivr.net/gh/xndeye/adblock_list@beta/rule/dns.txt

[dnsmasq-raw]: https://raw.githubusercontent.com/xndeye/adblock_list/beta/rule/dnsmasq.conf

[dnsmasq-ghproxy]: https://ghproxy.net/https://raw.githubusercontent.com/xndeye/adblock_list/beta/rule/dnsmasq.conf

[dnsmasq-jsdelivr]: https://gcore.jsdelivr.net/gh/xndeye/adblock_list@beta/rule/dnsmasq.conf

[clash-raw]: https://raw.githubusercontent.com/xndeye/adblock_list/beta/rule/clash.yaml

[clash-ghproxy]: https://ghproxy.net/https://raw.githubusercontent.com/xndeye/adblock_list/beta/rule/clash.yaml

[clash-jsdelivr]: https://gcore.jsdelivr.net/gh/xndeye/adblock_list@beta/rule/clash.yaml

[smartdns-raw]: https://raw.githubusercontent.com/xndeye/adblock_list/beta/rule/smartdns.conf

[smartdns-ghproxy]: https://ghproxy.net/https://raw.githubusercontent.com/xndeye/adblock_list/beta/rule/smartdns.conf

[smartdns-jsdelivr]: https://gcore.jsdelivr.net/gh/xndeye/adblock_list@beta/rule/smartdns.conf

[hosts-raw]: https://raw.githubusercontent.com/xndeye/adblock_list/beta/rule/hosts

[hosts-ghproxy]: https://ghproxy.net/https://raw.githubusercontent.com/xndeye/adblock_list/beta/rule/hosts

[hosts-jsdelivr]: https://gcore.jsdelivr.net/gh/xndeye/adblock_list@beta/rule/hosts

[private-raw]: https://raw.githubusercontent.com/xndeye/adblock_list/beta/rule/private.txt

[private-ghproxy]: https://ghproxy.net/https://raw.githubusercontent.com/xndeye/adblock_list/beta/rule/private.txt

[private-jsdelivr]: https://gcore.jsdelivr.net/gh/xndeye/adblock_list@beta/rule/private.txt

<details>
<summary>点击查看上游规则</summary>
<ul>
    <li><a href="https://raw.githubusercontent.com/AdguardTeam/FiltersRegistry/master/filters/filter_2_Base/filter.txt">AdGuard 基础过滤器</a></li>
    <li><a href="https://raw.githubusercontent.com/AdguardTeam/FiltersRegistry/master/filters/filter_11_Mobile/filter.txt">AdGuard 移动广告过滤器</a></li>
    <li><a href="https://adguard.com/kb/zh-CN/general/ad-filtering/adguard-filters/">AdGuard 防跟踪保护过滤器</a></li>
    <li><a href="https://raw.githubusercontent.com/AdguardTeam/FiltersRegistry/master/filters/filter_17_TrackParam/filter.txt">AdGuard URL跟踪过滤器</a></li>
    <li><a href="https://raw.githubusercontent.com/AdguardTeam/FiltersRegistry/master/filters/filter_14_Annoyances/filter.txt">AdGuard 恼人广告过滤器</a></li>
    <li><a href="https://raw.githubusercontent.com/AdguardTeam/FiltersRegistry/master/filters/filter_10_Useful/filter.txt">AdGuard 解除搜索广告和自我推销过滤器</a></li>
    <li><a href="https://raw.githubusercontent.com/AdguardTeam/FiltersRegistry/master/filters/filter_224_Chinese/filter.txt">AdGuard 中文过滤器</a></li>
    <li><a href="https://github.com/jdlingyu/ad-wars">ad-wars</a></li>
    <li><a href="https://github.com/TG-Twilight/AWAvenue-Adblock-Rule">AWAvenue-Adblock-Rule</a></li>
    <li><a href="https://raw.githubusercontent.com/Noyllopa/NoAppDownload/master/NoAppDownload.txt">NoAppDownload</a></li>
    <li><a href="https://github.com/Cats-Team/AdRules">Cats-Team/AdRules AdBlock List Lite</a></li>
    <li><a href="https://github.com/badmojr/1Hosts">1Hosts (Lite)</a></li>
    <li><a href="https://github.com/hagezi/dns-blocklists">hagezi/dns-blocklists normal</a></li>
    <li><a href="https://github.com/xndeye/web-ad-rule">xndeye/web-ad-rule</a></li>
</ul>
</details>



使用anti-AD能够屏蔽广告域名，能屏蔽电视盒子广告，屏蔽app内置广告，同时屏蔽了一些日志收集、大数据统计等涉及个人隐私信息的站点，能够保护个人隐私不被偷偷上传。

| 文件                       | raw                                                          | 官网地址                                                   | 适用于                                                       |
| -------------------------- | ------------------------------------------------------------ | ---------------------------------------------------------- | ------------------------------------------------------------ |
| `adblock-for-dnsmasq.conf` | [link](https://raw.githubusercontent.com/privacy-protection-tools/anti-AD/master/adblock-for-dnsmasq.conf) | [官网地址🚀](https://anti-ad.net/anti-ad-for-dnsmasq.conf)  | dnsmasq及衍生版本                                            |
| `anti-ad-easylist.txt`     | [link](https://raw.githubusercontent.com/privacy-protection-tools/anti-AD/master/anti-ad-easylist.txt) | [官网地址🚀](https://anti-ad.net/easylist.txt)              | AdGuardHome（DNS过滤）                                       |
| `anti-ad-adguard.txt`      | [link](https://raw.githubusercontent.com/privacy-protection-tools/anti-AD/master/anti-ad-adguard.txt) | [官网地址🚀](https://anti-ad.net/adguard.txt)               | AdGuard（匹配整个URL的域名部分）                             |
| `anti-ad-domains.txt`      | [link](https://raw.githubusercontent.com/privacy-protection-tools/anti-AD/master/anti-ad-domains.txt) | [官网地址🚀](https://anti-ad.net/domains.txt)               | Pi-Hole或其他工具（[白名单](https://raw.githubusercontent.com/privacy-protection-tools/dead-horse/master/anti-ad-white-list.txt)） |
| `anti-ad-surge.txt`        | [link](https://raw.githubusercontent.com/privacy-protection-tools/anti-AD/master/anti-ad-surge.txt) | [官网地址🚀](https://anti-ad.net/surge.txt)                 | Surge或其他工具                                              |
| `anti-ad-surge2.txt`       | [link](https://raw.githubusercontent.com/privacy-protection-tools/anti-AD/master/anti-ad-surge2.txt) | [官网地址🚀](https://anti-ad.net/surge2.txt)                | Surge或其他工具，DOMAIN-SET 格式性能更好                     |
| `anti-ad-clash.yaml`       | [link](https://raw.githubusercontent.com/privacy-protection-tools/anti-AD/master/anti-ad-clash.yaml) | [官网地址🚀](https://anti-ad.net/clash.yaml)                | Clash Premium 类似工具（[白名单](https://raw.githubusercontent.com/privacy-protection-tools/dead-horse/master/anti-ad-white-for-clash.yaml)） |
| `anti-ad-smartdns.conf`    | [link](https://raw.githubusercontent.com/privacy-protection-tools/anti-AD/master/anti-ad-smartdns.conf) | [官网地址🚀](https://anti-ad.net/anti-ad-for-smartdns.conf) | SmartDNS（[白名单](https://raw.githubusercontent.com/privacy-protection-tools/dead-horse/master/anti-ad-white-for-smartdns.txt)） |
| `anti-ad-sing-box.srs`     | [link](https://raw.githubusercontent.com/privacy-protection-tools/anti-ad.github.io/master/docs/anti-ad-sing-box.srs) | [官网地址🚀](https://anti-ad.net/anti-ad-sing-box.srs)      | sing-box（二进制文件，需`1.10.0-alpha.25`及以上版本）        |

> 使用官网地址，速度更稳定

## 争议域名



一些域名可能与广告/跟踪有关，但部分情况下它们发挥着其他的作用，拦截它们可能会造成额外的问题。本项目对部分此类有争议的域名做了整理和简单说明，您可根据自己的需要自行添加额外规则放行或拦截相关域名。

[点此查看](discretion/README.md)