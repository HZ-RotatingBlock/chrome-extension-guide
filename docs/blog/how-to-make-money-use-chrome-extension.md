## 我是如何通过开发天气扩展月入2500$【译】

#### 介绍

我叫 Tim Leland。 我于 2010 年获得计算机科学学位，并且在过去 7 年中一直从事软件开发工作。 我还会在业余时间做一些个人项目。

[Weather Extension](https://weatherextension.com/) 是一种浏览器扩展（Chrome | Firefox | Opera），我创建该浏览器扩展是为了满足自己快速在浏览器查看天气预报的需求。

该扩展程序在全球拥有超过 133,000 个用户，已被翻译成 12 种语言。

目前，我每个月的收入超过 2500 美元，平均每天安装近 2000 次。 我希望在未来几个月内继续增加每月收入，并吸引 200,000 个用户。

#### 初衷

早在 2015 年 7 月，我就有了为 Chrome 创建一个简单天气扩展程序的想法。其他天气网站的广告使我感到沮丧和其他烦恼。我知道我可以有一个更好的解决方案。我希望其他人会喜欢它，但我确实是为自己做的这个扩展。也并没有从扩展中赚钱的计划。

我几个晚上编写了 [Weather](https://weatherextension.com/) 的原始版本，并于2015 年 7 月发布到 Chrome 商店。该扩展很简单，由 HTML，CSS 和 JavaScript 组成。我使用了免费的 DarkSky 帐号来获取天气数据。它包括每天 1000 次免费请求，我从来没有想过能达到这个限制。

随着时间的流逝，我听取了用户的反馈，并对扩展进行了改进。我一直试图忠于我最初打算创造的东西。每当有空闲时间时，我都会在晚上和周末从事“天气”工作。

最终，我超过了 1,000 个免费 API 调用的门槛，不得不找出一种赚钱的方法。我决定重写 Weather，为 Pro 版本添加新功能。

#### 吸引用户

最初，我与我的朋友和家人以及在我的博客上分享了Weather。大约获得了 150 个用户。

我很幸运，因为以前的一篇博客与 Lifehacker 的作家建立了联系。我让他在 Lifehacker 上推广了我的扩展程序。文章帮助我在一周内获得了10,000 个用户！时至今日，文章能继续带来数百个安装。

![](./media/15955115605872.jpg)

我最近吸引用户的策略是为分享安装页面链接的人免费升级到专业版。这非常成功，我的用户对此表示赞赏。 我认为这比在 Facebook 或 Twitter 上支付广告便宜。

我曾经用来吸引用户的其他策略：

* 与其他扩展合作
* 在 Hacker News 和 ProductHunt 发布文章
*在 LaravelNews 上被选为精选文章
* 创建了一个演示视频
* 使用 Buffer 处理我的社交媒体帐户；它使设置和忘记密码变得容易

其他策略请查看我有关[营销浏览器扩展](https://timleland.com/how-to-market-browser-extensions)的文章。


![](./media/15955118140687.jpg)

#### 商业模式

我一开始使用 PayPal 捐款，对有人愿意为免费扩展捐款感到惊讶。早期激发了我继续进行扩展的工作的热情。

目前，我的商业模式很简单。我对解锁所有功能的专业升级收取 2 美元的费用。我从 Stripe 开始，但最终添加了 Paypal 按钮，为用户提供了不同的选择。

作为一项实验，早在 2016 年 12 月，我决定将Google Adsense 添加到我的博客中。起初，我不相信它将带来很多收入。令我惊讶的是，第一天我赚了大约 9 美元。我认为这可以支付我每天的咖啡习惯。

我继续尝试广告。到 2017 年 1 月，我知道我已经开始上手了。我连续几天赚了 100 多美元，甚至有几天我赚到了 160 美元。统计数据很清楚，我的Adsense 收入的大部分来自该扩展程序的介绍页。

综上所述，我的大部分收入来自 Adsense。我的每月开支约为 $100。我必须向 DarkSky 支付访问其 API 的费用，并向 DigitalOcean 支付服务器费用。

#### 未来

我 2017 年的目标是继续增加博客访问量，为天气应用吸引 200,000 多位活跃用户，并增加每月收入。

![](./media/15955121842764.jpg)

我也一直在尝试通过创建其他扩展来重导 Weather的成功。目前，我有[计步器](https://chrome.google.com/webstore/detail/step-tracker/mmehkkgdjeabomkpmpfkemcomagemjfn)和[保存链接](https://chrome.google.com/webstore/detail/read-later/hleifpgbhiladknmecmkpgbgfmlnjhoh)扩展。

我计划通过写博客，扩大我的社交媒体圈并告诉所有人我可以从事的工作来实现这些目标。

#### 挑战

到目前为止，我面临的最大挑战是服务器扩容。该扩展程序必须不断请求我的服务器，以使温度图标保持最新。随着扩展的增长，请求数量也随之增加。我通过设置 DigitalOcean 负载平衡并添加其他服务器解决了扩容问题。

扩容是大多数应用程序面临的挑战。想保持低成本并确保应用程序平稳运行。 我现在正使用 NewRelic来监控服务器的性能。这样，希望需要添加其他服务器时得到警告。

如果我重新开始，我会做的另一件事是监控服务器性能。早在 2017 年 2 月，服务器超载时，我失去了数千名用户。 硬件总是多多益善。

#### 优势


我帮助 Weather 成长的最大优势是，我在 2014 年底开始写博客。我无法强调通过博客和其他社交媒体平台建立形象的重要性。

![](./media/15955125792092.jpg)

Blog traffic from December 2014 to April 2017.

这需要时间和精力，但是一致性是关键。每个人都从零个关注者开始。 只有那些始终如一的人才能获胜。从外部看起来可能很幸运，但是每“幸运”时刻都会有100个“不幸”时刻。 我相信您必须努力创造自己的运气。

#### 建议

创建一个博客的目的是让他人了解您已经拥有的知识。说真的：从今天开始。

每天创建并分享您的经验。坚持不懈，不要期望在一夜之间获得成千上万的用户。如果您相信它，那就坚持下去，不要放弃。向他人学习，但尝试找出最适合您的方法。 听播客，并了解 IndieHackers 上的其他创始人的故事。

原文链接：https://www.indiehackers.com/interview/weather-extension-ad9b94660e


-------

关注 微信公众号「**程序化思维**」 获取最新 Chrome 插件开发故事。

![mp_wechat](/mp1.png)

