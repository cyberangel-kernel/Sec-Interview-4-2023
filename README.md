# Sec-Interview-4-2023
一个2023届毕业生在毕业前持续更新、收集的安全岗面试题及面试经验分享~

## 写在前面

1. 个人强烈感觉面试因人而异，对于简历上有具体项目经历的同学，个人感觉面试官会着重让你介绍自己的项目，包括但不限于介绍一次真实攻防/渗透/挖洞/CTF/代码审计的经历 => 因此对于自己的项目，面试前建议做一次复盘，最好能用文字描述出细节，在面试时才不会磕磕绊绊、或者忘了一些自己很得意的细节
2. 面试题会一直更新（大概，直到我毕业或者躺平为止吧...）包括一些身边同学（若他们同意的话）和牛客上扒拉下来的（若有，会贴出链接）还有自己的一些经历
3. 还有一点很想说的，就是面试题/面经，本质上只是一种“见识”，他并不能实质上提升自己的水平，还是希望大家（包括我自己）不要太局限于面经，可以查缺补漏但没必要面经问什么自己就一定要学什么，按自己的节奏学就行了，毕竟每人的技术特点不一样，面试的过程和问题也会不一样

**最后欢迎大家fork项目！xdm自己有面试经验的话也欢迎发pr！有分享就有收获！**


- [阿里面试复盘](#阿里面试复盘)
- [深信服面试复盘](#深信服面试复盘)
- [腾讯面试复盘](#腾讯面试复盘)
- [字节跳动面试复盘](#字节跳动面试复盘)
- [长亭科技面试复盘](#长亭科技面试复盘)
- [天融信面试复盘](#天融信面试复盘)
- [腾讯面试复盘](#腾讯面试复盘)
- [小鹏汽车面试复盘](#小鹏汽车面试复盘)



# 阿里面试复盘

时长：20分钟

1. 自我介绍
2. 看你简历上说擅长java、php代码审计，也没有类似的经历能够分享一下，比如说独自审的一套代码或者开源项目，从中发现的一些比较高危的问题
3. 在审项目的时候，比如一个web网站，简单说说思路
4. 简单描述一下什么是水平越权，什么是垂直越权，我要发现这两类漏洞，那我代码审计要注意什么地方
5. 解释一下ssrf
6. 怎么防御ssrf，场景：`http://ip/?url=image.jpg`
7. 常见的内网段有哪些，他们的掩码是什么
8. 教育系统攻防演练，分享一个渗透的例子
9. 除了学校，有没有试过渗透别的系统
10. 像这样的场景（给内网靶标），渗透内网系统的思路
11. 反问环节（问了工作内容）

# 深信服面试复盘

时长：15分钟

1. 自我介绍
2. 在xx实习的时候做什么东西
3. 渗透测试的思路简单说一下
4. 护网在里面担当一个什么样的角色
5. 红队的一些思路
6. 拿下系统后有没有做横向
7. 前段时间那个log4j有研究吗，可以简单说一下吗
8. （继上一个问题）有哪些混淆绕过的方法
9. 内存马有没有了解过
10. 冰蝎、哥斯拉这些工具有没有了解过
11. 做攻击队的时候有没有研究过什么攻击，比如研究一些工具还是魔改什么的
12. 那么多漏洞和攻击，比较擅长哪一个
13. 说一下shiro反序列化的形成原因、利用链
14. 对一些bypass的方法有没有了解过，有什么姿势可以简单介绍一下
15. 反问

# 腾讯面试复盘

## 一面

时长：20分钟

1. 自我介绍
2. 我看你简历上有过几次攻防演练的项目，结合几次项目讲一下实战渗透、攻防演练的一个流程
3. 讲一下做的比较好的信息收集的地方
4. 实战中遇到redis未授权访问漏洞中的利用姿势
5. 遇到命令执行无回显的情况，有什么好的处理方法
6. 漏洞预警、对最新漏洞的复现分析
7. 讲一下偏web应用方面的一些漏洞复现
8. 对知名组件的漏洞复现和分析
9. 对poc、exp编写这块熟悉吗
10. 之后的发展方向
11. 怎么安排实习和学习的时间？实习的时长？
12. 反问环节

## 二面

时长：30分钟

1. 自我介绍

2. 我看你简历上说xx攻破了一个系统，聊一聊是怎么打的

3. rce后做了什么，有进行内网的横向吗

4. xx报了两个漏洞，还有一个是什么

5. 你说想做安全研究，那么对漏洞研究这一块有什么了解，有没有做过一些漏洞分析

6. 你刚刚说的都是漏洞复现吧，就是想问有没有跟过一些知名应用的漏洞，做一个分析

7. 继上个问题，有没有对哪些类别的漏洞研究的比较多的，比如堡垒机、oa、cms之类的

8. 有没有深入了解过某一些组件的漏洞，讲一讲原理

   > 说自己想做安全研究属实给自己挖了个大坑....连问了好几个漏洞研究方向的问题，都答的不太好...面试官想要引导我往这个方向答然而我完全答不上来....

9. 聊聊两段实习经历分别做了什么，对自己有什么提升，从中学到了什么，或者对做的内容有什么自己的看法

10. 在A实习后有什么收获，对工作内容有什么觉得可以提升的地方

11. 在B的ctf出题是出给谁的

12. 面试官介绍工作内容

13. 惯例问实习base意向、实习时间、时长

14. 惯例反问环节

# 字节跳动面试复盘

## 一面

时长：50分钟

1. 你投的岗位是安全研究实习生，你了解我们这边主要是做什么的吗
2. 自我介绍
3. 现在有什么比较想做的方向吗，比如你写的代码审计、攻防演练、你导师的研究方向（密码学）其实是三个大方向，现在有什么比较想做的吗
   - 说了代码审计、安全研究
4. 有没有审过开源框架、cms、中间件之类的
5. 面试官介绍了工作内容
6. 我看你简历上有几段实习经历和项目经历，先聊一下实习经历吧，在A主要做什么的
7. 详细聊聊入侵检测主要在做什么，遇到的问题
8. 关于入侵检测产生大量误报的原因，有没有分析过，有没有比较好的解决方法
9. 和A比起来，B的应该就比较偏攻击方对吧，有打仗（雾，面试官好像确实是这么说的）有代码审计，聊一下在B主要做了些什么
10. 审表达式引擎的步骤和思路
11. 刚刚你说的审计听起来好像和普通开发的审计差不多，都是通过程序流、文档去做，有没有从安全方面入手审计一些项目
12. xxe是怎么造成的，从代码层面来看
13. 我看你简历有很多攻防演练经历对吧，这几段攻防演练经历有没有哪一次印象比较深刻的，挑一个聊一聊
14. 你的这次攻击好像更多的是利用弱口令，有没有一些更有技巧的方法
15. 这个头像上传的webshell是怎么上传的
16. 还有什么其他的检验方式？要怎么绕过？
17. 这两天log4j漏洞很火，有没有去了解一下
18. 面试官最后介绍业务
19. 反问环节

## 一面plus

> 很奇葩的剧情，一面面试官面完告诉我有base北京base深圳问我是不是想要深圳的，我说是，结果过了一个多星期hr告诉我因为我一面面试官是北京的，然后我选了深圳，所以一面不作数，重新约了一面
>
> 接着一面这天中午又收到了感谢信，然后看官网状态是流程已终止，本以为没得面了没想到还是正常进行....

岗位：安全研发实习生

> 等到二面才发现原来已经变成安全研发了，本来我投的是安全研究的...

时长：45分钟

1. 自我介绍

2. A护网做了什么

3. 做哪一层的处置，waf？ids？

4. 遇到的问题是什么，有什么印象深刻的处置

5. 怎么解决误报过多的情况，有做过什么规则能解决这个情况的

6. 他的内网误报是在办公网还是生产网

7. 比如mysql也会执行powershell，怎么做防护（前面说了很多内网误报是因为有人写了ps脚本触发的）

8. 有没有挖过src

9. 在做攻防的时候，资产收集这块有没有什么经验介绍的

10. 一个单位的一级域名可能不止一个，怎么收集某个单位的所有域名，注意不是子域名

11. 还有没有其他的资产收集的经验

12. 除了信息收集，有没有什么漏洞方面的攻击案例

13. 聊一下sql注入

14. 怎么防御

15. 遇到order by时怎么防御

16. 用转义字符防御时，如果遇到数据库的列名或是表名本身就带着特殊字符，应该怎么做

17. 宽字节注入

18. ssrf了解吗

19. 怎么修复

20. 基于黑白名单的修复，现在的生产基本都是用的docker，ip是随时变的，而且docker重启后可能什么都不一样了，怎么做一个修复

21. fastjson反序列化

22. redis的漏洞

23. mysql的提权

24. shiro反序列化

25. 最近很火的log4j，聊一下原理

26. jndi的解析流程和原理

27. 有没有什么你做的比较好的地方我没有问到的，可以聊一聊

28. 惯例介绍部门的主要业务

29. 惯例反问

## 二面

> 紧接在一面plus后，就隔了10分钟，一面复盘写一半就开始二面了

时长：25分钟

1. 聊攻防演练中比较得意、印象深刻的一次经历
2. 安全领域比较擅长什么
3. 审的一般是什么，java？python？
4. csrf了解吗，怎么做一个修复
5. 在拿到java系统的代码时，审计的流程是怎样的
6. java系统中的sql注入怎么做一个防御和修复
7. 在浏览器中输入一个域名去访问时，浏览器做了什么
8. 一个系统的登录页，通常可能出现什么漏洞
9. 云安全了解吗
10. 有做过安全工具的开发吗，比如waf或者扫描器之类的
11. 惯例介绍业务
12. 惯例反问

# 长亭科技面试复盘

岗位：安全服务工程师

## 一面

时长：30分钟

1. 自我介绍
2. web渗透测试有没有过实战
3. 讲一下sql注入原理
4. 有没有从代码层面了解过sql注入的成因（反问代码层面指的是不是sql语句，答是）
5. 了不了解xss，有没有从代码层面了解xss的原理
6. 对owasp top10漏洞哪个比较了解
7. 讲一讲怎么防御sql注入
8. sql注入怎么绕过过滤
9. 问了护网时xx有没有成为靶标，有没有对攻击队行为做过研判
10. 在xx护网时的工作内容，有没有做过流量包、数据包的研判
11. 学校攻防演练时担任的角色，主要工作内容，渗透测试的思路，有什么成果（这个问的还是挺细的，具体到分配的任务、有没有拿下主机或者域控、攻防演练的形式和持续时间等都聊了）
12. 平时ctf打的多不多，有什么成绩
13. 平时会不会关注一些新颖的漏洞，会不会做代码审计，比如shiro漏洞等有没有做过漏洞复现
14. 对钓鱼邮件这些有没有什么了解（因为上面聊xx护网时说了钓鱼邮件和微信钓鱼的事）
15. 目前学习的方向是什么
16. 最后介绍人才需求
17. 反问环节

## 二面

时长：34min

1. 自我介绍
1. 学代码审计偏哪个语言？擅长哪个语言
1. 拿到一份php代码做审计，审计的流程大概是怎样的
1. 对php开发框架熟吗？比如ThinkPHP这些
1. 给的源码是ThinkPHP框架的话，审计起来和没有使用框架的有什么不同，从流程上或者从关注的点上有什么不同
1. php原生的敏感函数有哪些，比如搜关键字的话会搜哪些
1. 反序列化漏洞了解吗
1. 反序列的时候，unserialize()反序列一个字符串的时候，对象会有一些魔术方法会被自动调用到，在找反序列化的链时，有哪些魔术方法是可以作为一个入手点去找的
1. 有没有审计过实际的项目，比如github上一些开源cms
1. java审计可以聊一下吗
1. 之前做渗透时有没有做过完整的项目，除了ctf
1. 能不能说一些找到的漏洞，怎么找到的
1. ssrf这类的漏洞熟悉吗，说一下原理和利用方式
1. 我们利用ssrf可以做什么，达到什么效果
1. 在php环境下，怎么最大程度的利用ssrf，拿到shell或者进内网
1. 怎么利用内网的机器请求内网中的服务
1. ssrf漏洞的修复建议，修复的时候需要注意哪些细节
1. 如果用白名单策略修复ssrf，从用户输入的变量里拿出要访问的目标，这个要注意哪些，因为一些url会通过特殊的字符做白名单绕过，对取变量这个操作有哪些要注意的细节？
1. php中三个等号和两个等号有什么区别
1. php代码常见入口函数怎么找
1. 有一些php的开发框架可以帮我们做一些url路由，对这些路由的方法熟悉吗
1. 介绍下PHP的变量覆盖
1. 有一个php的程序，本身就允许文件包含的操作，同时想要避免文件包含漏洞，写代码的时候要注意哪些
1. 远程文件包含和本地文件包含，这两种涉及的php设置有什么
1. 本地文件包含能不能通过php配置限制文件包含的路径（不通过代码直接通过配置项来解决）
1. php、java代码审计对哪个漏洞特别熟悉
1. php在做sql注入防御时有哪些方法
1. java做sql注入的防御
1. sql的二次注入了解吗，能介绍一下吗
1. 写代码的时候怎么防止二次注入

# 天融信面试复盘

时长：15~20分钟

1. 有没有做过现实环境的渗透测试？有没有提交过src？
2. 对免杀技术了解多少，制作的木马能不能过360
3. ctf的成绩？擅长什么方向的题？
4. 攻防演练有什么成果？
5. shiro漏洞了解吗，讲一下原理
6. 在linux下，现在有一个拥有大量ip地址的txt文本文档，但是里面有很多重复的，如何快速去重？
7. 在内网渗透中，通过钓鱼邮件获取到主机权限，但是发现内网拦截了tcp的出网流量，聊一下这个时候应该怎么进行通信？
8. 代码能力怎样，平时有没有做过代码审计？
9. 目前对什么方向感兴趣？

# 腾讯面试复盘

时长：15分钟

1. 自我介绍

1. sql注入了解吗，讲一讲二次注入的原理

1. 二次注入要怎么修复

1. sql注入过waf了解吗，若一个sql注入过滤了information关键词，怎么绕过

1. Redis未授权访问

1. 渗透测试的一个完整流程

1. 打ctf的时候有没有遇到什么印象特别深的题目

1. 文件下载漏洞有没有什么比较好的利用方式

1. 利用文件下载漏洞找文件名具体是找什么文件名（读取文件一般会读取哪些文件）（ctf中？实战中？）

1. 命令执行漏洞，http不出网有什么比较好的处理方法（发散一点说）

1. 接上一题，通过隧道通信，详细讲讲通过什么类型的隧道，讲讲具体操作

1. 漏洞预警

1. 有没有复现过中间件类型的漏洞（有没有完整的复现过漏洞）

1. 在学校的攻防演练中扮演的角色的主要职责是什么

# 小鹏汽车面试复盘

岗位：安全工程师

时长：37分钟

1. 自我介绍
1. 有没有挖过src？
1. 平时web渗透怎么学的，有实战吗？有过成功发现漏洞的经历吗？
1. 做web渗透时接触过哪些工具
1. xxe漏洞是什么？ssrf是什么？
1. 打ctf的时候负责什么方向的题
1. 为什么要搞信息安全，对安全这一块有多大的兴趣，以后会不会转行，还是打算一直从事安全方面工作
1. 自己平时怎么学安全的，如果让你做一个新的方向（app安全），会投入多少时间去学习，还是说有自己想做的方向
1. 聊一聊代码审计的流程
1. 平时是怎么做代码审计的
1. 有没有审计过开源框架、CMS？
1. 怎么判断一个数据库是mysql还是oracle的？
1. sql注入的种类，利用方式？
1. 聊一聊sql注入的原理及防御思路
1. 做开发的时候用的是什么语言
1. 做java开发的时候用过什么框架，能不能做java安全开发
1. 有没有做过安卓开发
1. 有没有用python写过工具？
1. msf利用的是哪个漏洞，有没有成功反弹？
1. 护网的时候主要做了些什么，聊一聊对安全产品的理解
1. 公司现在需要做app安全的人，现在要你做的话，你会去学吗，或者说感兴趣吗，还是说有别的想做的，不想做app安全，能投入多少时间去学
1. 内网渗透了解吗？聊一聊内网渗透的思路

