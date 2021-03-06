---
layout: post
title: "做快乐的程序员"
date: 2012-05-07 13:23
comments: true
categories: Life
---
看了一篇很不错的文章，忍不住转了，原文[链接](http://www.nowamagic.net/php/php_BeHappyProgrammer.php)

### 什么是程序员的基本功？

广义来说就比较多了，抛开数据结构、算法、编程思想、设计模式等不说，丰富的想象力，缜密的逻辑思维、学习能力、恒心和毅力、沟通能力….太多了，这些都算是基本功。

所谓基本功，就是说抽空都要练习的。就像一个学武之人一样，每天早上要跑步、扎马步，也像一个京剧演员样，一大早就要吼几嗓子，我们程序员也得每天练习基本功。

广义的基本功涉及到生活的方方面面，时时刻刻都能练习。这里着重强调下狭义的基本功：数据结构，基本算法、编程思想和设计模式、至少精通一门语言等。

程序员都知道程序=数据结构+算法，可见数据结构和算方法对我我们程序员来说是何等重要。

编程通俗一点说就是，想个办法把一堆旧数据按照要求整理整理变成另一堆新数据。首先要想好的就是把旧数据放好，你可以把计算机的存储设备想象成一个大的盒子。我们要想办法占用尽量小的空间（少用内存），把这些旧的数据放好。（当然还要考虑整理这些数据的方便性，比方说移除掉，或者新增数据等。）放好了旧的数据，现在就要开动大脑，想出个好方法—–如何操作才能使得整理的时间尽量的短（少用CPU）。编程其实就是这个目的，所以我们程序员常常思考的问题就是这两个了：1、如何放置数据 2、用什么方法处理速度快。

一般来说，我们不需要太苛求占用尽量少的内存和CPU。毕竟现在的机器性能不是制约我们的主导因素，现在制约我们的主导因素是，“用尽量少的时间把需求合理的完成”。可以说，绝大部分企业对程序员的要求并不高，他们仅仅要求你按照需求在规定的时间做出来即可，并不是非常关心你占用多少计算机资源，硬盘不够，买，内存不足，补。但是这个并不意味着我们可以肆无忌惮的滥用计算机资源。

举个实际的例子，假如浏览一个网页，本来需要1秒的时间能够打开，结果由于程序员的失误或粗心，或者说基本功力不足，使得整个过程变成2秒，你可能认为这个无所谓，不就是多了一秒么，应该没什么大不了的。如果你真这么想就大错特错了。

就拿个一般的网站举例，每天1W PV，那么浪费的时间就是每天166.67分钟，1年就浪费60834.55分钟。约等于42个昼夜。你说这42个昼夜的时间干什么不好，非要浪费在计算机上，而且这个对计算机的损耗，以及浪费的电能等都还没有计算。

可能有人说，对于这种普通的站点，一年42个昼夜也算不了什么，但是请注意我的例子只是说系统的一个地方，假如一个系统有不止一个这样的地方那就更夸张了。

对于大型的互联网网站，这个就更夸张了，类似百度和google这样的企业，一天都有上亿的PV。就按1亿计算。大约是3年2月1.4天！

对于我们做开源程序的程序员来说，这个尤其值得关注。要知道并不是每个HDWiki系统都是可以随意使用计算机资源的。

### 重视解决问题的思路和事物的本质

重视思想、重视问题的本质，不要浮在表面看待问题。例如我面试人的时候常常问一个 web 开发的基础问题：说说 session 的原理。这个对于搞 web 开发的人来说，是个很基本的问题。如果连 session 的原理都搞不清楚，说明这个人不是很喜欢思考。平时开发肯定都用别人说的，别人怎么说，他就怎么做。至于为什么一个用户能够登录成功，他始终是不清楚的。当然，不明白 session 的原理不是说就不能搞程序开发，一个项目也需要一些纯的coder。纯的coder就是按照要求填写代码的，基本不需要思考。我相信每个有追求的程序员都不会甘愿成为一个纯的 coder，那么，请在遇到实际问题的时候，多深入思考思考，多问几个为什么，一直深入到问题的本质。这样坚持下去，你绝对是一个有思想的程序员。碰到问题就很容易拿出一个靠谱的方案。

可能会有人说，我怎么感觉平时没什么问题好问的，好像自己什么都知道了。知识就像是车轮，学得越多，这个车轮就越大，转一周所需要的行程就越长，而你会发现，车轮变大的同时，所接触的东西也是越来越多了，然后猛然发现，不会的东西变得更多了。如果一个人没有问题问，只能说明知道的太少了。

在我们的日常工作中，需要问的东西太多了。为何我们要用框架？hibernate有什么用，用了有什么好处，用了有什么坏处？java为何是编程第一流行语言？Ruby 为何突然火爆起来了？PHP还能火多少年？HDWiki 能超过Discuz么？Lucene这个东西为何命名为Lucene？丁磊为何要养猪？……

重视思想和本质带给我们什么好处呢？首先，作为一个了解本质的程序员，心里就很踏实，和其他技术人员交流，不会被鄙视。第二，能够让我们能够知其所以然，而不至于内心痛苦。例如数据库索引，大家都知道，建立了索引后，SQL查询条件”=”的时候，速度就提高很多。如果我们把这个当作经验背诵下来，你会马上碰到一个反例。例如当你的表有个标识字段，1表示有效，0表示无效。这时候如果在这个字段上建立了索引，按照经验，我们肯定认为速度会提高很多，但是实际上，基本没有变化。这个时候自己就很郁闷了。如果想做一个快乐的程序员，就一定要搞清楚索引的本质，为何索引建立后就快了。如果明白这个本质，就不会有这样的疑虑了。第三，能够让我们提高工作效率。第四，让自己更加清醒，不会被表象所迷惑。

### 简单就是美，我们都是艺术家

什么是美？我想是事物给人无论是哪种感官上的体验都还不错，这就是美了。比如夕阳柔和的余辉洒在眼中，呼吸带着草味儿的空气，要做的事情做好了，静坐着享 受美好的一刻。简单的东西不会使人厌烦，就好象天边几片单调的云彩，徐徐清风拂面，带来的是心情舒畅，头脑冷静，能给自己一个澄澈的思维空间。

在程序的世界里，同样遵循这一原理。一个程序如果写的漂亮，很容易让别人看懂。程序不是写给机器看的，程序是写给人看的。当一个程序出问题了，我们希望迅速解决问题。如果程序写的很美，随便一个技术人员都能够看的懂，那么就非常有利于我们解决问题。

有 百度知道，就有腾讯爱问，有浩方对战平台，就有QQ对战平台，有土豆网，就有了QQ视频，….马化腾自己也说：模仿也是一种成功！现在他用铁的事实来证实了这一点。

对程序员来说，模仿能力也很重要。比方说我们要做一个弹出式DIV，这个时候你千万不要自己去从头开始去做。首先，我们要想办法找找看，看看是否有适合我们的已经存在的。如果有，我们直接下载，然后就可以用了。如果没有，可以找找类似的，然后再改改，还是可以为我所用。这样的话，可以为我们节省不少时间。 项目的进度有可能会提前。

一个程序员刚进入一个公司的时候，短时间内还难以了解系统的整体构架。这个时候也不要发怵。怎么办呢？咱模仿项目组的其他老同学，模仿别人的开发流程、模仿别人的代码结构，模仿别人的命令规则……只要你模仿能力强，肯定把大家怔住了。给你的评价就很不错。为什么会这样呢，因为项目组的老同学正用的 肯定是目前比较合理的，只要你模仿着做，基本就不会有问题，你说你过试用期还会有问题？

模仿能力就类似于段誉的“吸星大法”。吸星大法修炼起来的难处有两点：难处一，是要散去全身内力；难处二，散功之后，又须吸取旁人的真气。模仿和这个不同的地方就是，模仿只是复制，并不需要毁灭别人。从这个角度来说，模仿应该比吸星大法更加人道主义些。模仿有时候也得暂时忘掉或者放弃自己的然后再学习别人的。只有敞开心扉才能容纳万物！

总之，模仿不仅能给我们节省不少的时间，还能够让我们迅速找到解决问题的正确思路和方法，正如牛顿所说“我之所以站得高，是因为我站在巨人的肩上”，模仿也是站在别人的肩膀上，能够省却我们不少的体力，何乐而不为呢？

### 关注技术趋势，热爱学习

作为专业的程序员，技术趋势不能不关注。IT行业发展迅猛，新的思想和新的东西不断涌现。如果我们不睁大双眼去观察，去了解，我们就会被逐渐淘汰。

每天都有新的软件产品诞生，有新的版本发布，也有新的解决问题的方法出现。如果我们抽空关注下，我们很可能会有意外收获。例如今天，你看到一条消息，PHP5.3版本开始支持闭包。这个意味着什么呢？意味着你的程序写法可以进行更优美的改造。再如你看到消息说MySQL推 出了一种新的引擎，你就要看看这个引擎有什么特点，以后对我的工作有什么帮助。

就是这样，我们在一点一滴中积累，每天坚持修炼自己的基本功，长期的坚持。我们会发现自己一天比一天快乐，因为我们每天都能够轻松的像艺术家一样说笑间就完成了自己的工作，你怎能不快乐？
