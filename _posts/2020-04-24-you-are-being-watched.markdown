---
layout: post
title:  "你被监视着"
date:   2020-04-24 09:34:33 -0700
categories: jekyll update
---
珍爱生活：远离国产流氓软件

众所周知国内软件的毒瘤简直不能太恶心：每个流氓软件都要给自家的用户当成猪，等猪养肥了就好宰。互联网行业国内起步晚，很多软件模式都是copy to china。因为墙的原因，互联行创业者无非就是将国外那套搬过来翻译一下而已。临摹抄袭还不算，连抄都抄不好还要给自家圈地。争相圈到自家猪圈里喂屎。

国内的商业软件是绝对不能信任的，基本上总带有一股流氓的特性，不是偷隐私就是给你推广告，更可能会在不告知你的情况下将你的设备安装P2P节点，甚至监控你的生活等。主系统从Windows系统切换到Linux有段时间了。当时换系统的理由有以下几点：
1.因为我是从事后端相关开发的，很多开源库的支持顺序Linux > OS X > Windows。
2.受够了和国产软件斗智斗勇，有这时间精力我更愿意下一盘棋。

但由于办公不得不使用微信、QQ之类的软件，还得在VirtualBox装上Windows再装这些流氓软件。这也挺讽刺，工作协作不是用邮件、Trello等等。而且工作模式完全依靠同事同步模式，而不是以一种类似异步的模式进行。回到主题，能用web服务的就是用web服务而尽量不用客户端，如果web服务不提供https那不用也罢，毕竟都2020年了。

在Android端就更恶心了，国内Android软件一些特点：
1.索要权限不合理，不给权限不让运行。
2.后台任务唤醒运行，占用资源，耗电。
3.臃肿无比，尽搞一些用不到的服务。
4.注册服务，嵌入第三方SDK收集隐私。
5.互相唤醒。
……

如果用iOS，iCloud运营商应该选择境外。

百度李彦宏曾说过：“中国人对隐私问题的态度更加开放，相对来说也没那么敏感。如果他们可以用隐私换取便利和效率，在很多情况下他们就愿意这么做”。隐私和便利似乎两者不可兼得的，我选择隐私。每次安全事件泄漏，这已经很足以说明问题。如果某家公司的某款产品出现过安全问题，那么通常会将那家公司列入黑名单恨屋及乌嘛。如果那片土地反复出现同类事情，就不能怪别人地图炮了。

原则上尽量使用开源的软件，隐私的信息只放在自己知道的地方。别想着肉身在墙内，信息放在墙外服务商那就安全了，毕竟谁能保证呢？注册服务时，要仔细阅读隐私政策/条款，是否有注销服务。注册/使用时请使用Google Authenticator/Authy之类打开两步验证，而不是用短信/邮箱验证。如果临时使用可以考虑临时邮箱/短信接号网站注册。再说一点 端到端加密 ≠ 安全。

以下为小白容易泄漏信息的一些特点：
1.不要使用相同密码、弱密码、不要使用带有信息的密码。服务商对于用户来说是一个黑盒，你不知道里面是什么代码，一旦其中一个服务商泄漏，其他所有帐号都有可能被撞库。
2.不要让你的电脑/手机裸奔。设置密码，电脑要设置开屏密码及全盘加密。输入密码时注意身边有没有摄像头及键盘监听。至于指纹/面部等生物识别不评价，这类识别只能代表user，不能代表password。
3.保护身份证/驾照/信用卡等信息。信用卡只要卡号、有效期、名字、CVV码就能消费，不要拍照存到手机存放在第三方云。
4.不要使用免费的上网工具/帐号。打着免费的口号，实际可能会截取你的通信避免中间人攻击。
5.不要下载、安装、浏览可疑文件。安装包尽量选择用官方网站/商店下载，下载完成要校验散列值/数字签名。要特别谨慎破解软件，你不知道被重新打包多少次。在Windows下就流行一个低劣的骗术——把一个.exe的可执行文件内置一个jpg 的图标，然后再通过适当地修改文件名，伪装成一个吸引人的图片文件，此时该文件的扩展名依然是.exe，但是一般人通过资源管理器查看这个文件，误认为是个图片。上当的人会直接双击该文件（想要打开图片），但其实是运行了一个恶意的可执行文件。
6.不要点击、使用可疑链接包括邮件、网页中的链接等。
7.不要使用第三方输入法包括复制粘帖工具等。
8.大部分境外消费都是磁条卡，不带安全芯片。磁条信息和PIN码会被商家留下机器记录。用Bitcoin交易，地址尽量使用一次就废弃。
9.安全问题不要留下个人隐私信息。
……

理论来说留下的信息越多风险越高，做到以上几点不一定能完全保证你的信息安全，但能抵御大部分的风险。在大数据时代中，从众多个服务商中拼凑出一个完整的用户画像简直易如反掌。

保护个人隐私，保护的不单是你自己；比如在社交软件中，你的朋友/家人默认是信任你的，你是否应该保护好这些信息呢？隐私保护不当与不保护隐私是两种风险程度，个人信息安全取决于最薄弱的一环。

推荐些主打隐私相关的工具
邮箱
[ProtonMail](https://protonmail.com/)
[Mailbox](https://mailbox.org/)
[Tutanota](https://tutanota.com/)

搜索引擎
[searx](https://searx.me/)
[DuckDuckGo](https://duckduckgo.com/)
[Qwant](https://www.qwant.com/)
千万别用百度，它是一个梦魇。

浏览器
[Firefox](https://firefox.com/)
[Tor](https://www.torproject.org/)
请区分Firefox和火狐。

避免留下浏览器指纹，以下扩展并非必要，可以考虑安装
[uBlock Origin](https://addons.mozilla.org/firefox/addon/ublock-origin/)
[Everywhere](https://www.eff.org/https-everywhere)
[Cookie AutoDelete](https://addons.mozilla.org/firefox/addon/cookie-autodelete/)
[Privacy Badger](https://www.eff.org/privacybadger)

文件分享
[FireFox Send](https://send.firefox.com/)

密码管理器
[Bitwarden](https://bitwarden.com/)

电脑操作系统
[Fedora](https://getfedora.org/)
[Debian](https://www.debian.org/)
尽量选择长期支持版本，不要选择测试版。

手机操作系统
[GrapheneOS](https://grapheneos.org/)
[LineageOS](https://www.lineageos.org/)
Android & iOS都不是完全开源的。iOS没什么好说的，其实Android也不是完全开源的，只有开源AOSP（Android Open Source Project），而 GMS（Google Mobile Services）是闭源的。而Android慢慢占领市场份额后，Google逐渐把AOSP中的模块转移到GMS中，两者的关系有点类似Chromium和Chrome。

References：
https://www.privacytools.io/

[jekyll-docs]: http://jekyllrb.com/docs/home
[jekyll-gh]:   https://github.com/jekyll/jekyll
[jekyll-talk]: https://talk.jekyllrb.com/
