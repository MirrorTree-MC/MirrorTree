---
title: 对“棱镜树的小屋”作为Wiki网站的三点批判
date: 2024-11-19 22:00:00
sticky: 0
tags:
  - xxbc的反动言论
---

> 该页面旨在整理[小熊白菜](/docs/server/players.html#小熊白菜)在本站建设过程中对于其作为Wiki的属性提出的几点质疑与或许可行的修改意见，

棱镜树的小屋（本站，简称“小屋”）是由[Veritas](/docs/server/players.html#概要)牵头，[AC_Mnky](/docs/server/players.html#AC)主要协助搭建的棱镜树半官方Wiki站点，截至2024年11月19日已经产生了23篇[docs](/docs)文章与5篇[posts](/archives/)文章。目前[docs](/docs)主要聚焦于服务器的介绍与新人加入所需要知道的信息，[posts](/archives/)则相对内容自由发散。

[小熊白菜](/docs/server/players.html#小熊白菜)支持小屋的建设，但认为目前网站的建设方式不是最优解。结合维基百科[Wiki](https://en.wikipedia.org/wiki/Wiki)页面的介绍与个人理解，他提出了对小屋作为Wiki网站的三条主要批判观点：

1. [参与内容编辑壁垒较高](#参与内容编辑壁垒较高)

2. [内容结构可拓展性较弱](#内容结构可拓展性较弱)

3. [呈现形式匹配内容不佳](#呈现形式匹配内容不佳)

### 参与内容编辑壁垒较高

> "A wiki invites all users—not just experts—to edit any page or to create new pages within the wiki website, using only a standard 'plain-vanilla' Web browser without any extra add-ons." *翻译：“Wiki网站邀请所有用户（而不仅仅是专家）在Wiki网站内编辑任何页面或创建新页面，仅使用标准的‘普通’网络浏览器，无需任何额外的附加组件。”* -  *The Wiki Way: Quick Collaboration on the Web* （转引自 [Wiki-Characteristics](https://en.wikipedia.org/wiki/Wiki#Characteristics)）

[小熊白菜](/docs/server/players.html#小熊白菜)认为，有别于少数权威或专家撰写[说明文档](https://en.wikipedia.org/wiki/Software_documentation)，Wiki最本质的特征在于内容撰写的公众参与。为公众参与Wiki撰写提供尽可能的便利是网站建设的重点。

目前小屋以架设在[GitHub Pages](https://docs.github.com/zh/pages/getting-started-with-github-pages/about-github-pages)上的静态markdown站点实现，仅就网站本身而言，参与内容撰写需要登录一个已被加入到组织[MirrorTree-MC](https://github.com/MirrorTree-MC)的GitHub账号，通过上传/修改/删除GitHub仓库[MirrorTree](https://github.com/MirrorTree-MC/MirrorTree)中的markdown文件实现。 ~~（[小熊白菜](/docs/server/players.html#小熊白菜)在此处并不想考虑写好之后在群里让[Veritas](/docs/server/players.html#概要)或[AC](/docs/server/players.html#AC)代发表的途径，并且歪曲本意地引用了[AC](/docs/server/players.html#AC)“需要考虑社恐人群”的观点支撑）~~

[小熊白菜](/docs/server/players.html#小熊白菜)认为，考虑到棱镜树的玩家群体的广泛性群众性，以上内容撰写的渠道存在较高参与壁垒。一方面通过编辑GitHub仓库文件的方式撰写内容本身流程相比站内Web文本编辑器不够方便，另一方面GitHub在境内访问的强不稳定性或许导致相当比例的玩家尝试登录账号/加入组织/修改文件受阻。

较高的参与壁垒势必会削弱大部分玩家撰写Wiki内容的意愿。[小熊白菜](/docs/server/players.html#小熊白菜)认为，**这实际上筛选了可以参与Wiki编写的玩家**，可能会降低Wiki内容的公众性，同时影响充实Wiki内容的速度。

### 内容结构可拓展性较弱

> "What separates wikis from blogs and traditional content management systems is that wikis are inherently amorphous. " *翻译：“wiki与博客和传统内容管理系统的区别在于，wiki本质上是没有结构的。”* - [Easy Wiki Hosting, Scott Hanselman's blog, and Snagging Screens](https://learn.microsoft.com/en-us/archive/msdn-magazine/2008/july/easy-wiki-hosting-scott-hanselman-s-blog-and-snagging-screens)

[小熊白菜](/docs/server/players.html#小熊白菜)认为无定形的、由页面之间链接形成的内容网络，相比于目前的文件目录半树状结构半独立文章，更有利于向Wiki加入新的内容并建立联系。

![小熊白菜设想中的Wiki内容结构（A）与小屋目前的内容结构（B）](https://cos.bearcabbage.top/wp-content/uploads/2024/11/IMG_3751.jpeg)*小熊白菜设想中的Wiki内容结构（A）与他认为小屋目前的内容结构（B）：点代表页面，蓝色连线代表页面之间链接形成的“软联系”，黑色连线代表目录结构或全局菜单带来的“硬联系”*

[小熊白菜](/docs/server/players.html#小熊白菜)在向[Veritas](/docs/server/players.html#概要)解释“可拓展性较弱”这一点时举了一个例子。

    例如：加入“第一块自然生成的冰”条目：
    
    - 在图A的无定形内容网络中，直接加入一个“第一块自然生成的冰”页面即可，可以通过链接与“地下室博物馆”条目产生双向联系；

    - 在图B所示目前小屋的内容结构中，或许需要专门新开一个文章目录“地标建筑”，再向其中加入“出生点博物馆”文章，再向其中加入“第一块自然生成的冰”条目。

没有固定结构的设计更匹配公众参与撰写带来的多元化内容组织需要。援引维基百科[Wiki](https://en.wikipedia.org/wiki/Wiki)页面中的观点，无定形化的结构有助于帮助新主题条目产生。[小熊白菜](/docs/server/players.html#小熊白菜)认为，虽然现在内容较少，但搭建好一个适用范围更大的内容框架对于长期发展和内容充实是有利的。

此外，[小熊白菜](/docs/server/players.html#小熊白菜)针对[Veritas](/docs/server/players.html#概要)提出的“需要让目前[docs](/docs)部分文章保持清晰的树状结构”的想法也做出了回应：他认为，这部分文章可以通过添加页内链接、反向链接与导航页面的方式（参考[Wiki-Navigation](https://en.wikipedia.org/wiki/Wiki#Navigation)），继续在无定形内容网络中保持树状结构。两者区别仅在于从“硬联系”变成“软联系”，内容结构本质没有发生变化，但可以实现[docs](/docs)与[posts](/archives/)组织结构上的统一。

### 呈现形式匹配内容不佳

[小熊白菜](/docs/server/players.html#小熊白菜)认可形式应服务于内容与功能的理念，并且反对超出内容与功能需要的形式堆砌。对于Wiki网站，他认为其最主要的功能是内容阅读与信息快速检索 ~~（他在写这个页面的过程中从维基百科[Wiki](https://en.wikipedia.org/wiki/Wiki)页面了解到Wiki是夏威夷语Quick的意思）~~ ，并不需要与写作类博客 *（例如，[VichainLee](/docs/server/players.html#VichainLee)的[报纸屋](https://v.bearcabbage.top/)）* 一样尝试通过网站主题奠定某种氛围基调。

因此，[小熊白菜](/docs/server/players.html#小熊白菜)曾多次试图游说[Veritas](/docs/server/players.html#概要)（以及游说[AC](/docs/server/players.html#AC)帮自己劝说[Veritas](/docs/server/players.html#概要)）换成[MediaWiki](https://www.mediawiki.org/wiki/MediaWiki)的传统Wiki软件；（截至2024年11月19日）游说没有起效。不过据[小熊白菜](/docs/server/players.html#小熊白菜)透露，他只是相对[MediaWiki](https://www.mediawiki.org/wiki/MediaWiki)不那么喜欢目前的小屋模板 ~~(他说：救命甚至页面每个部件都有开屏动效x)~~，但并不反对继续用它。

另一方面，[小熊白菜](/docs/server/players.html#小熊白菜)指出目前小屋的评论功能使用不方便。评论需要登录GitHub账号，以发布issue的原理评论，这一方式同样适用于第一条批判[“参与内容编辑壁垒较高”](#参与内容编辑壁垒较高)。

### ~~（叠甲）~~ 补充说明

[小熊白菜](/docs/server/players.html#小熊白菜)反复申明，他支持小屋的建设，尊重建设者的劳动，并且愿意参与到小屋内容的撰写充实中来 ~~(这篇[《批判》](/criticism)也算是充实内容吧awa)~~！以上的内容是其提出的 ~~（或许是）~~ 建设性意见，不要因此[炖了小熊做汤](/news/mt19.html)啊啊啊啊啊啊啊啊x

![小熊捅刀子awa](https://cos.bearcabbage.top/wp-content/uploads/2024/11/IMG_6418.gif)

### 各方反馈

#### [VichainLee](/docs/server/players.html#VichainLee) 24.11.19

提议很有效，我认可小熊白菜的全部提议awa