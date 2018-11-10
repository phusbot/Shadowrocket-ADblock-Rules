## 自用的小众Shadowrocket规则
==========

基于[CloudGate](https://github.com/BurpSuite/Manual)修改的规则，本人目前使用Shadowrocket，所以只修改了Shadowrocket规则。

修改目的：因为我的服务器屏蔽了国内的服务（[项目地址](https://github.com/phusbot/ss-iptables-blockade)），使用原规则时发现新浪微博用不了，因原规则把新浪的域名设置为走代理。同时原规则把规则外的域名设置为走代理，造成未被墙的域名都走代理。

基于上述修原因，修改了多处“不合理”的地方，删掉多余（万年都用不上）的代理规则600余条，包括免费空间提供的网址和无效的网址，保留常用代理规则和去广告规则。

代理规则地址 <https://raw.githubusercontent.com/phusbot/Shadowrocket-ADblock-Rules/master/Shadowrocket-lite.Conf>

[Telegram社群](https://t.me/joinchat/Eeks0Eh3DYd_ndSdcpMmyg)
