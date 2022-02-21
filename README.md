# Sec-Interview-4-2023
一个2023届毕业生在毕业前持续更新、收集的安全岗面试题及面试经验分享~

## 写在前面

1. 个人强烈感觉面试因人而异，对于简历上有具体项目经历的同学，个人感觉面试官会着重让你介绍自己的项目，包括但不限于介绍一次真实攻防/渗透/挖洞/CTF/代码审计的经历 => 因此对于自己的项目，面试前建议做一次复盘，最好能用文字描述出细节，在面试时才不会磕磕绊绊、或者忘了一些自己很得意的细节
2. 面试题会一直更新（大概，直到我毕业或者躺平为止吧...）包括一些身边同学（若他们同意的话）和牛客上扒拉下来的（若有，会贴出链接）还有自己的一些经历
3. 还有一点很想说的，就是面试题/面经，本质上只是一种“见识”，他并不能实质上提升自己的水平，还是希望大家（包括我自己）不要太局限于面经，可以查缺补漏但没必要面经问什么自己就一定要学什么，按自己的节奏学就行了，毕竟每人的技术特点不一样，面试的过程和问题也会不一样

**最后欢迎大家fork项目！xdm自己有面试经验的话也欢迎发pr！有分享就有收获！**

**若有不方便公开的内容请联系本人第一时间删除！**

**<big>目录</big>**

- [致谢](#致谢)
- [0x00 字节跳动-渗透测试实习生](#0x00-字节跳动-渗透测试实习生)
- [0x01](#0x01)
- [0x02 深信服-漏洞研究员实习](#0x02-深信服-漏洞研究员实习)
- [0x03](#0x03)
- [0x04 字节跳动-安全研究实习生](#0x04-字节跳动-安全研究实习生)
- [0x05 长亭科技-安全服务工程师](#0x05-长亭科技-安全服务工程师)
- [0x06 天融信面试复盘](#0x06-天融信面试复盘)
- [0x07 腾讯-安全技术实习生](#0x07-腾讯-安全技术实习生)
- [0x08 小鹏汽车-安全工程师](#0x08-小鹏汽车-安全工程师)
- [0x09 阿里巴巴-阿里云安全](#0x09-阿里巴巴-阿里云安全)
- [0x0A](#0x0a)
- [0x0B 字节跳动-无恒实验室](#0x0b-字节跳动-无恒实验室)
- [0x0C 58同城-安全工程师](#0x0c-58同城-安全工程师)
- [0x0D 腾讯-玄武实验室](#0x0d-腾讯-玄武实验室)
- [0x0E 360-安全工程师](#0x0e-360-安全工程师)
- [0x0F 快手-安全实习生](#0x0f-快手-安全实习生)
- [0x10 华顺信安-安全服务工程师](#0x10-华顺信安-安全服务工程师)
- [0x11 奇安信面试复盘](#0x11-奇安信面试复盘)
- [0x12 京东-安全研发](#0x12-京东-安全研发)
- [0x13 安恒面试复盘](#0x13-安恒面试复盘)
- [0x14 浙江东岸检测](#0x14-浙江东岸检测)
- [0x15 360-安全工程师实习](#0x15-360-安全工程师实习)
- [0x16 某一线实验室实习](#0x16-某一线实验室实习)
- [0x17 腾讯-科恩实验室实习](#0x17-腾讯-科恩实验室实习)


# 致谢

感谢 `PolarPeak` 、 `lalalashenle` 、 `4ra1n` 师傅的分享！

# Stars

 [![Stargazers over time](https://starchart.cc/vvmdx/Sec-Interview-4-2023.svg)](https://starchart.cc/vvmdx/Sec-Interview-4-2023) 

# 0x00 字节跳动-渗透测试实习生

> 字节直接找朋友内推的效率很高，当天上午投简历，下午就约了面试，裸面挺痛苦的建议复习一下再去

1. 自我介绍
2. 渗透的流程
3. 信息收集如何处理子域名爆破的泛解析问题
4. 如何绕过CDN查找真实ip
5. phpinfo你会关注哪些信息
6. 有没有了解过权限维持
7. 说一个你感觉不错的漏洞，展开讲讲
8. 输出到href的XSS如何防御
9. samesite防御CSRF的原理
10. CSRF防御
11. json格式的CSRF如何防御
12. 浏览器解析顺序和解码顺序
13. 过滤逗号的SQL注入如何绕过
14. 过滤limit后的逗号如何绕过
15. fastjson相关漏洞
16. 说一个你知道的python相关的漏洞（SSTI原理，利用过程,payload相关的东西）开放性问答

# 0x01

# 0x02 深信服-漏洞研究员实习

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

# 0x03

# 0x04 字节跳动-安全研究实习生

## 一面

时长：50分钟

1. 你投的岗位是安全研究实习生，你了解我们这边主要是做什么的吗
2. 自我介绍
3. 现在有什么比较想做的方向吗，比如你写的代码审计、攻防演练、你在学校的研究方向（密码学）其实是三个大方向，现在有什么比较想做的吗
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

## 一面plus-安全研发实习生

> 很奇葩的剧情，一面面试官面完告诉我有base北京base深圳问我是不是想要深圳的，我说是，结果过了一个多星期hr告诉我因为我一面面试官是北京的，然后我选了深圳，所以一面不作数，重新约了一面
>
> 接着一面这天中午又收到了感谢信，然后看官网状态是流程已终止，本以为没得面了没想到还是正常进行....

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

# 0x05 长亭科技-安全服务工程师

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

# 0x06 天融信面试复盘

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

# 0x07 腾讯-安全技术实习生

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

# 0x08 小鹏汽车-安全工程师

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

---

> 接下来从0x09~0x0B都是同一位博主的面经，发在牛客上，看了下感觉很不错就转过来了，再附上这个博主的一些面试题/学习笔记的链接，个人觉得挺好的
>
> [CSDN 网络安全-常见面试题](https://blog.csdn.net/lady_killer9/article/details/120075430)
>
> [CSDN 网络安全-自学笔记](https://blog.csdn.net/lady_killer9/article/details/106791542)

# 0x09 阿里巴巴-阿里云安全

作者：宠你＆我的天性

链接：https://www.nowcoder.com/discuss/642461?source_id=profile_create_nctrack&channel=-1

来源：牛客网

## 一面

1.  自我介绍一下，讲一下课题和课外实践？ 

2.  WAF管理平台后端API有做过压力测试吗？ 

3.  你现在的论文已经发表了吗？ 

4.  你的毕业论文是什么？ 

5.  在字节跳动训练营最大的收获是什么？ 

6.  在研究生期间或日常生活中有什么可以分享的有意义的事情？ 

7. 快排的时间复杂度是多少？ 

   - 最快的情况下是多少？是什么样的情况？ 

   - 最慢的情况下是多少？是什么样的情况？ 

8.    哈希冲突有哪些解决办法？  

9.    编程题(easy) 

##  二面

1. 自我介绍一下？ 
2. 我们这里是密码管理服务，密码这块你了解多少呢？ 
3. 你未来计划更偏向于安全研究还是安全研发？ 
4. 你对云上PKI的安全，身份认证的能力感兴趣吗？ 
5. 介绍一下字节跳动训练营做了什么？

   - Sql注入的原理和防御方案有哪些？ 

   - WAF防护SQL注入的原理是什么？ 

   - 本次训练营中，怎么分工协作的？你的角色是什么？你的贡献是什么？有没有提升效率的可能？ 

   - 漏洞挖掘是纯工具还是有一些手工的？ 

   - WAF管理平台后端API有哪些功能？ 

   - WAF的增删改查数据量大吗？ 

   - Redis解决了什么问题？ 

   - 热点数据怎么保证redis和db中的一致？ 

   - 用户登录认证是怎么做的？ 

   - Token的安全怎么保护？ 

   - Token的内容该如何设计？ 

   - 怎么保证数据不被篡改呢？ 

6. SDN漏洞挖掘的思路？ 
   - 漏洞挖掘有挖掘出RCE漏洞吗？ 
   - 对栈溢出、堆溢出有研究吗？ 

7. 说一下https协议的过程？ 
   - 随机数一般有几个？ 
   - 如果有一个的话会如何？ 

8. 对C++或C熟悉吗？ 
9. 哈希表的原理和冲突解决办法？（和一面重复了） 
10. Mysql查询快的原因？ 
    - 事务的四大特性，mysql隔离级别？ 
    - 解释一下乐观锁和悲观锁？ 

11. 多并发编程有涉及过吗？ 
    - 读写锁和互斥锁/排他锁用过吗？有什么区别？为什么会用？  

12. 有一项软件著作权，做的什么软件？    
13. 编程题(medium)  

##  三面（交叉面）

1. 字节跳动训练营越权问题解决办法？ 
   - 防火墙都是自己写的规则去防御吗？ 
   - 任务都是一样，你们得了第一，你们团队做的好的地方在哪里？ 
2.  SDN漏洞挖掘项目，你能列举一个比较有技术含量的漏洞吗？漏洞原理和挖掘过程？ 
3.  Python2和Python3的区别？ 
   - Xrange和range返回的是什么？ 
4.  数据库索引的作用？mysql索引的变化？ 
5.  数据库弱口令，登进去后如何提权？ 
6.  你自己写项目的时候，怎么进行的   SQL注入防御？   
7.  怎么进行CSRF防御？
   - Token加密什么东西？ 
   -  校验什么？ 
   -  Token为什么需要加密？ 
   -  使用明文随机数可以吗？ 
8.  怎么防重放攻击 ？    
9.  Docker有哪些安全上的好处？    
10.  个人发展方向？    
11.  当前在哪里日常实习？   
12.  实习多久了？为什么想来阿里？



# 0x0A





# 0x0B 字节跳动-无恒实验室

部门：无恒实验室

岗位：安全工程师

作者：宠你＆我的天性

链接：https://www.nowcoder.com/discuss/749954?source_id=discuss_experience_nctrack&channel=-1

来源：牛客网

---

1. 自我介绍
2. 阿里巴巴实习介绍？
3. 启明星辰实习介绍？
4. 消息队列是自研的，还是开源的？叫什么名字？
5. 任务下发？状态监测
6. 子域名扫描插件怎么写的？
7. 指纹识别插件怎么写的？
8. wappalyzer怎么进行指纹识别的？
9. CSDN的XSS漏洞挖掘过程？
10. SQL注入的原理？
11. 目前防御SQL注入的方式有哪些？
12. 有哪些SQL语句无法使用预编译的方式？
13. SQL注入如何判断注入点？ 
14. 已知example.com/?id = 1，是mysql，如何获得mysql版本？
15. 无回显情况下怎么弄？ceye dnslog外带
16. 除了外带呢？
17. CSRF的原理？
18. CSRF使用POST请求时，如何攻击？隐藏表单
19. 不是表单呢？
20. AJAX发送POST请求？
21. Ajax发送POST请求会发几个数据包？ 
22. 让你来写一个CSRF攻击插件，你怎么写？包含哪些模块？
23. SSRF的原理？
24. 让你写一个SSRF插件，你怎么写？
25. 反问环节



# 0x0C 58同城-安全工程师

岗位：安全工程师

作者：Lamber-maybe

链接：https://www.nowcoder.com/discuss/766311?source_id=discuss_experience_nctrack&channel=-1

来源：牛客网

---

1. 你先做个自我介绍吧

2. 假如说有个SQL注入如下

   ```
   select * from user where userid = {};
   ```

   1. response里面没有返回内容 
   2. 1s就超时了，直接返回404页面 

   这种情况下如何注入?

3. 比如说我写一个安全SDK
   1. sql注入的修复, 怎么写(伪代码)

      答：我倾向于使用预编译的方式

   2. 但是预编译的话, 研发可能不会用怎么办呢, 就是说如果他觉得改起来太麻烦了能不能更方便一点. 因为预编译的话, 我每条SQL每条查询都得去改.

      答：那设计一个白名单怎么样呢

   3. 那你大概写一下怎样设计一个白名单. 你可以分场景, 比如说什么场景什么场景的SQL注入, 或者是参数里面应该做什么操作

   4. xss的修复, 怎么写(伪代码)
      答: 用实体化转义

   5. 但是我们有一个场景啊, 你看我们上传简历这里, 有时候会支持上传html的简历, 对吧. 他本身业务就需要用到html, 如果用html实体化转义的话, 他全都会被转义, 那这样的话业务就崩了嘛, 对不对. 那这种情况下我们要怎么样去写一个xss的过滤, 或者是说转义, 去解决这个类似于简历这个场景. 你可以想一想, 写不出来代码也没关系.

      答：白名单限制, 黑名单过滤.

   6. 其实我们自己是这样做的, 对于这种情况, 我们第一是会做一个html标签的白名单, 第二是事件的白名单. 黑名单我们就不搞了.

   7. rce的修复, 怎么写(伪代码)(java或者python的命令执行)
      答: 白名单限制, 只允许需要的函数. 但RCE的话我感觉在业务场景当中, 一般来说也不是很容易出现
      面试官: 欸, 我们就出现了很多. 尤其是运维部门.

      我: 我打CTF比较多, 我了解的RCE都是PHP方面的. 比如说system, popen之类的. 一般来说都是直接做过滤

   8. 那PHP中这些函数全部被黑名单了, 你还有什么方法

      答: 字符串拼接 `$a=p.h.p.i.n.f.o()`

   9. 你有没有用过php里面的反引号啊

      答: 还有用 `chr()` 函数来绕过

   10. 面试官: 编码是吧
   11. xxe的修复, 怎么写(伪代码)
       答: 对XXE来说, 我只了解他的攻击方式, 对他的防御不是很了解. 攻击方式就是做XML的外部实体化注入. 一个攻击模板, 可以读文件, 可以做命令执行
   12. XXE怎么做命令执行呢, 就拿php来说, XXE怎么做命令执行
   13. XXE这个命令执行是要他的服务端本身支持某些特殊的协议, 一般来说是不行的

4. 了解过自动化代码[审计]()的工具吗, 类似于fortify这种

   答: 我只用过那个一个比较老的那个, 我想不起来了(指seay)

5. 没关系, 那你有没有了解过他的一些原理, 大概怎么做的

   我: 他原理一般都是通过匹配一些特殊函数, 去定位可能出现漏洞的函数的位置

6. 但这种的话他误报很高欸, 就像我这种RCE的话, 你直接匹配的话他很多都是误报了, 很多他都不是web思路的

   我: 还有一种是, 给他加一些自定义规则

7. 那有没有更好的办法呢, 误报太多了我们没办法接受啊

   我: 我有一个想法就是, 他自己匹配了之后, 能不能从前端从一个黑盒的层面再去验证一遍

8. 那黑盒验证, 我就有需求是, 首先我得知道, 首先我php里面我这个函数到底是哪个入口传进来的, 对吧. 但这个有可能经过了层层调用, 甚至有可能是`include()`这种, 那这种的话, 对于我来说 , 我并不知道他影响到了哪一些入口, 这种情况怎么办呢
9. 你们学校有学编译原理吗
10. 其实我觉得安全专业还是要学一下编译原理

11. 有没有搞过linux的这种后渗透相关的

    1. 面试官: 比如这个linux被我攻陷了, 我想去拿到更多的信息, 比如说一些横向的信息, 那种有没有搞过
       我: 这种不是很了解, 但windows的会一点

    2. 面试官: 那你可以简单讲一下, 比如你先攻陷一台windows的机器, 然后我想在这个windows的域内去做一些横向移动, 我想把这个windows的域的权限给拿到, 这种你该怎么做
       我: 通过票据伪造, 白银票据和黄金票据
       面试官: 你这个票据伪造要怎么做呢
       我: 一般用mimikatz就可以了吧

    3. 面试官: 你mimikatz抓取的是内存里面的密码和一些他的票据, 那我如果本身是低权限的呢, 就我本身抓不了密码, 或者我抓到的用户密码并不是域账号的, 是一个低权限账号呢. 因为大部分渗透进来都是个应用, 应用他可能并没有域权限
       我: 从低权限往上提

    4. 面试官: 那你一般会怎么提权
       我: 一般windows的漏洞吧
       面试官: 那现在就用这个windows系统的提权, 我现在就一个webshell, 那我怎么样去提权

    5. 面试官: 你可以这样嘛, 你上传一个提权的脚本或者exe嘛, 你webshell去跑这个exe, 他就把这个web应用权限提权了

12. 那你最后有什么想问我的吗



# 0x0D 腾讯-玄武实验室

作者：立志区块链安全的菜鸡

链接：https://www.nowcoder.com/discuss/711602?source_id=discuss_experience_nctrack&channel=-1

来源：牛客网

部门：玄武实验室

1. 自我介绍
2. 讲解一下CSRF原理吧
3. 什么时候接触web安全的
4. 为什么学WEB安全
5. 参加过哪些比赛
6. 你发挥了那行作用
7. 讲讲反序列化吧
8. 说一说最近你关注的安全圈大事
9. 那你说说你遇到最优印象的吧
10. 我看你简历上有黑盒测试 说一说吧
    - 一个是钱包的测试 一个是交易所的测试，钱包主要是信息泄露，水平越权
11. 怎么发现的
    - 信息泄露是webpack可以直接查看api 等调用信息，水平越权是构造josn包返回了用户数据账户密码之类的
12. 怎么构造的
13. 那继续说说交易所
14. （区块链相关）讲一讲逆向函数涉及到的接收参数的指令集
15. 说说重入漏洞
16. 有对最近那个最大的区块链安全事件有了解吗
17. 好，那你对密码学有什么接触嘛
18. 我看你简历有许多对Defi的审计，那你有什么对漏洞的挖掘的经验吗
19. 嗯好 那现在我问你个问题 你思考下 在DEFI项目中建立了各种各样的经济模型 怎样才能找出可能存在的漏洞
20. 讲讲你对未来可能出现的新型漏洞的猜想吧
21. 有一种 游戏在猜对正确答案后可获得奖励
22. 反问

# 0x0E 360-安全工程师

作者：Djade

链接：https://www.nowcoder.com/discuss/628090?source_id=discuss_experience_nctrack&channel=-1

来源：牛客网

1. 自我介绍 

2. WAF及其绕过方式 

3. IPS/IDS/HIDS 

4. 云安全 

5. 怎么绕过安骑士/安全狗等 

6. Gopher扩展攻击面 

7. Struct2漏洞 

8. UDF提权 

9. DOM XSS 

10. 数据库提权 

11. 怎么打Redis 

12. 内网渗透 

13. 容器安全 

14. k8s docker逃逸 

15. linux、windows命令：过滤文件、查看进程环境变量 

16. 站库分离怎么拿webshell



# 0x0F 快手-安全实习生

作者：ArrowQin

链接：https://www.nowcoder.com/discuss/651317?source_id=discuss_experience_nctrack&channel=-1

来源：牛客网

部门：系统运营部

## 一面

1. 自我介绍
2. 问项目
3. 针对项目问了很多详细的问题，不便透露，通用问题如下：
4. 做项目的时候有没有遇到什么问题，怎么解决
5. 做项目学到了什么东西
6. 项目中有没有什么地方自己做过优化
7. 有没有对网站做过渗透测试
8. Linux操作熟悉吗，怎么看进程PID
9. 用过什么数据库，答：sqlite,mongodb,面试官好像不太了解没咋问
10. 为什么用mongodb
11. 了解ES吗(Elasticsearch)
12. HTTPS建立过程
13. python怎么管理内存
14. 深拷贝和浅拷贝区别
15. python多进程、多线程、协程有用到吗，都在什么地方用到
16. python可以实现真正的多线程吗
17. 代码题：ip排序

（转成元组排序就行了，记得把str转成int，不然192会比50大）

```
输入：iplist = ["1.1.1.1","192.168.1.110","10.192.2.4","10.50.2.3","10.50.2.10","111.120.12.1","172.18.5.112"]
输出：
1.1.1.1
10.50.2.3
10.50.2.10
10.192.2.4
111.120.12.1
172.18.5.112
192.168.1.110
```

18. 写Web API的时候怎么防止SQL注入
19. 怎么防XSS
20. 了解越权漏洞么，有没有挖过越权漏洞
21. 有没有什么比较擅长的我还没问到的

## 二面

1. 问项目

2. 项目哪一块时间花的比较多

3. 怎么溯源攻击

4. 举一个溯源攻击的例子

5. 怎么检测webshell

6. sql注入在mysql和sqlserver中有什么区别

7. 想找安全开发的岗位还是安全研究的岗位

8. 代码题：手机九宫格键盘，输入数字，输出所有的字母组合

   如输入23，输出['ad','ae','af','bd','be','bf','cd','ce','cf']

9. 讲一下DNS协议的作用、解析过程

10. DNS协议的安全问题

11. 实习时间



# 0x10 华顺信安-安全服务工程师

来源：知乎

链接：https://zhuanlan.zhihu.com/p/426763642

1. 自我介绍
2. 红蓝队经验
3. 关于shiro漏洞了解多少
4. 说说你APP测试的经验
5. xposed用的什么框架，有没有自己写过app解密
6. Xss、SSRF、SQL 产生的原因，修复方案？
7. 如果你Xss打了后台，发现是内网的怎么办
8. 假设给你一个目标站，你要怎么做？
9. linux和windows提权知多少。
10. 会不会进程注入？
11. 做过几次应急？
12. 讲讲windows和linux应急你咋做的
13. 用过没用过我们家的goby和fofa?
14. 会不会apk反编译？
15. 你python水平咋样？
16. 你php怎么审的

---

> 备注：从0x11~0x14都是同一位师傅的面经，来源于知乎，里面有这位师傅的回答及一些总结、知识点，我这只是选了几个个人认为比较有代表性的公司和面经的题目出来
>
> 来源：知乎
>
> 链接：https://zhuanlan.zhihu.com/p/164774894
>

# 0x11 奇安信面试复盘

1. MVC框架详细说一下
2. 详细介绍一下sql注入
3. xss与csrf的区别
4. csrf的原理以及如何防范
5. 还有什么你擅长的但是没有问到的吗
6. 讲一下xxe的原理
7. xxe会用到哪些函数
8. 文件上传，详细说说
9. 常见的web容器有哪些
10. apache 7.0 文件上传黑名单怎么绕过，详细说说
11. 密码学的对称密码与非对称密码有哪些
12. md5是不是对称加密
13. apache可以执行php文件吗
14. 了解哪些数据库
15. 说说反序列化的原理
16. 反序列化会用到哪些函数
17. xxe有没有实战过
18. java的多线程
19. python有过哪些项目，写过什么东西
20. 之前python学到什么地方



# 0x12 京东-安全研发

1. 首先根据简历提问
2. 问我的一个项目完成的怎么的样了，//简历中的
3. Java基础怎么样，
4. 有没有自己动手写过一些工具
5. 有没有想过自己以后要写一下扫描器
6. sql注入的简单原理及其如何防御
7. 有没有了解过反序列化 尤其是Java方向的
8. 数据结构还记得多少
9. src主要挖掘一些什么类型的漏洞
10. 了解的MSF框架怎么样
11. 数据库主要了解的哪些，主要学的什么数据库
12. ssrf的原理及其防御 ---> 这有深入



# 0x13 安恒面试复盘

1. sqlmap爆出当前库名的参数是什么？

2. namp探测系统的参数是什么 --->大写还是小写

3. namp的小写o与a是干嘛的

4.  布尔型盲注的具体语句是什么

5.  宽字节的原理

6.  python有没有反序列化

7.  get传参与post传参的区别

8.  Http有哪些请求方式

9.  如何判定cdn与cdn的作用

10.  如何确认服务器的真实IP

11.  详细说了说信息收集过程

12.  一串编码如何确认是base64

13.  栅栏密码的原理是什么

14.  base64与md5如何区别

15.  oracle的默认端口是多少

16.  mysql的管理员密码一般放到哪

17.  如果substr()函数被禁用，你脑子里有多少替换函数

18.  redis如何拿下，哪个端口，具体语句，具体操作

19.  如何通过邮箱知道对方的IP

20.  说一下同源策略

21.  如何收集网站管理员邮箱等等

22.  ssrf有哪些危害

23.  如何防御ssrf-->问的较深---->建议在详细了解一下

24.  Linux的某两个文件怎么分辨（忘了具体是哪两个文件了）

25.  MSF框架稍微问的深入了一些

26.  web容器（中间件）有哪些解析漏洞与原理

27.  如何防范sql注入 --->这问的很深




# 0x14 浙江东岸检测

1. xss的标签
2. 说说大学这几年，你最自豪的事情
3. 简单说说sql注入
4. 说说偏移注入
5. 说说ctf你都做哪些题型
6. 遇到的比较困难的web题型的ctf题目
7. xxe了解吗，有没有自己审计出
8. 说说反序列化
9. bypass说说
10. 假如，让你设计一个waf，你会怎么设计
11. 内网渗透与提权了解吗
12. 平常都挖掘哪些src
13. 有没有自己手写过一些脚本
14. 说说sql注入，手工怎么爆出所有库名字



# 0x15 360-安全工程师实习

时长：45min

来源：知乎

链接：https://zhuanlan.zhihu.com/p/362868972

1. 自我介绍

2. WAF及其绕过方式

3. IPS/IDS/HIDS

4. 云安全

5. 怎么绕过安骑士/安全狗等

6. Gopher扩展攻击面

7. Struct2漏洞

8. UDF提权

9. DOM XSS

10. 数据库提权

11. 怎么打Redis

12. 内网渗透

13. 容器安全

14. k8s docker逃逸

15. linux、windows命令：过滤文件、查看进程环境变量

16. 站库分离怎么拿webshell



# 0x16 某一线实验室实习

来源：知乎

链接：https://zhuanlan.zhihu.com/p/426747686

## 技术面

1. 面试官：你好，听说你对来我们公司的意愿非常强烈，是为什么呢？
   我：因为我在项目中与贵公司的人员有过合作，感觉无论是技术还是硬件或者是待遇都算圈子里一流的

2. 面试官：那你了解我们实验室吗？
   我：我有了解过，巴拉巴拉说了一下

3. 面试官：那我先给你介绍一下实验室的方向，分为三个方向….
   我：好的明白了

4. 面试官：你在项目中是否使用过我们公司的设备，感觉使用体验如何（意思就是让说设备的优缺点）
   我：那我就实话实说了？

5. 面试官：没问题的，我就想听听你的意见
   我：我使用过…. ,优点就是性能好，能探测到更多的威胁情报之类的（大家脑补吧），感觉不足的就是探测和分析出的威胁，没法给出具体的流量片段，没法通过一个设备有效确定攻击，没有流量特征不好和其他全流量设备进行联动，可能是设备出场的保护机制，保护特征库不被外泄。

6. 面试官：你知道主流的设备原理和开发过程吗
   我：（我就说了一下原理，还不知道对不对）

7. 面试官：你在项目中是做过流量分析对吗？能不能说说你的具体案例
   我：我在国家hvv中协助发现过0day，单独发现过frp反弹定时回确认包向外输送流量，shiro反序列化等漏洞（我主要讲了我frp反弹的发现思路和流程）

8. 面试官：除了这些常规的特征发现，你自己还有什么快速确定的方法吗？
   我：（给大家分享一下我自己的流量分析心得）
   1.确定事件的类型（确定事件是什么样的攻击，比如sql注入和爆破和frp的流量分析步骤就不一样）
   2.确定事件的时间，首先划定一个时间段
   3.确定数据流，攻击的数据流我们是要看HTTP，TCP，还是ssh
   4.分析是内网—>外网还是外网—>内网，内网和外网时两种查询方法，正确的查询能有效的通过分析更少的数据包获取结果
   比如 内网—>外网 我们确定后，第一步肯定先去先查看外网ip的流量，判断行为
   外网—>内网 这样一般都是拿下了一个外网的服务器当做跳板机，我们肯定要先去分析内网的受害者服务器，看看有没有被攻击成功

    ```text
    首先我们需要确定到攻击行为后，再深入的流量分析和应急响应，很多都是误报
            数据包的大小也是分析的条件，分析SSL数据包需要解密
   
            爆破攻击：
            SMB,SSH,MSSQL等协议比较多，看包的大小，成功登陆的包很大
            看ACK，SYN包的次数，如果成功至少20起步，放到科莱上为40起步，但是注意不是失效包和重传的包（注意加密流的ack和syn包也很多，为客户端一次，服务端一次）
   
            重传攻击：
            如果一个数据包非常大，几个G或者一个G，我们就考虑数据包是否进行了重传，然后查看数据包的重传数，打个比方就是刷新，如果短时间重传数非常多，就为机器操作，判定为攻击
   
            我们发现一个攻击（如平台登录后的sql注入）我们可以通过流量回溯装置抓取那个被登录用户的用户名和密码，登录平台后自己利用发现的payload进行尝试，看是否能注入成功
    ```

9. 面试官：听说你还做过红队？是哪个项目，你在里面的职责是什么？
   我：介绍了一下我的项目经验，然后说我在红队的是突击手负责打点（我们当时孤军奋战没后援，也没擅长内网的选手）

10. 面试官：说说你项目中的成果
    我：….

11. 面试官：说一下你在项目里遇到的问题
    我：我们通过exp拿下了一个锐捷路由器的webshell，但是卡在了反弹shell上面，无法进行反弹

12. 面试官：那说一下项目结束后你是否有思考过这个问题，是否咨询过他人，解决方式是什么？（我感觉真的非常重视思考和问题解决，非常重视项目的闭环）
    我：我有问过也拿过锐捷路由器的朋友，然后我认为是数据库和网站分离开了，然后只能拿下来webshell权限

13. 面试官：你如何快速准确的确定资产？
    我：通过fofa，谷歌语法，钟馗之眼，一些的注册信息

14. 面试官：fofa的语法是什么？

15. 面试官：你如何在这些资产中快速的确定漏洞？
    我：最快的就是扫描器先扫描一遍，然后进行信息搜集，针对性的攻击，或者我们通过fofa语法针对性的在资产表中搜集是否存在特殊的cms或者oa系统….

16. 面试官:一般扫描都会封禁你，你会怎么办
    我：我会第一就是使用ip池代理，要么就是使用5g

17. 面试官：你这些信息搜集和攻击都是效率不是很高的，项目结束后你有没有思考解决方法呢
    我：我有想过自己写一个程序，把代码池和一些信息搜集和特定的利用方法融合，但是没写出来（又一次感到代码不好的痛苦）

18. 面试官：那你是否有了解过国家hvv红队的隐藏流量过防火墙的技术呢？
    我：有了解过，但是这个我不太会，没有地方去学（有点尴尬）

19. 面试官：你们在打点的时候有没有什么特殊的方法呢？
    我：我们除了搜索特点的oa系统，还会搜集资产里的邮件系统，进行信息搜集登录邮件系统，搜集各种配置文件数据库文件登录网站后台，我们成功登录到两个网站后台，和一个邮件系统，也拿下了几个oa

20. 面试官：你们这么针对特定oa，是因为有0day吗（笑）
    我：我们队有这几个oa的0ady和半day

21. 面试官：开发这边怎么样？能直接上手开发吗？
    我：python还能自己开发几个小工具，java还是只能看懂（好尴尬我真不行，可能是学安全时间还不够长，本来想今年主攻代码的）

22. 面试官：意思就是只能开发几个简单的扫描脚本对么（大家一定啊要好好学代码）
    我：是（尴尬的笑），最近在学习使用pos3编写poc

23. 面试官：你如果来实习你想进行哪方面的学习呢？
    我：（我选择了一个偏向防御类的方向，因为我知道攻击类的我应该水平不够，我很有自知之明）
    然后就是一些询问能工作几个月，什么时候能到岗

> 综合下来我认为面试官认为我的不足就是，红队时的攻击和信息搜集效率不高需要改进，可能缺少一点项目的反思和解决思路

## hr面

1. 首先介绍一下你自己的经历？
2. 你才大二该大三，你在学校是怎么自学安全的？
3. 你是怎么接触安全的？
4. 你现在的学习内容是什么？
5. 近期的学习规划是什么？
6. 你在大学中平时课程和安全的学习是怎么分配的？是否会冲突？



# 0x17 腾讯-科恩实验室实习

## 一面

时长：一个半小时

1. tcp三次握手
2. 介绍一次渗透测试过程  
   - 讲了一次代码审计
3. SSRF漏洞
4. 内网渗透大致流程
5. 再介绍一次难度比较高的渗透测试
6. 防守方有哪些入侵检测手段，有哪些痕迹是可以抓到的‌
7. 介绍进程和线程
8. 进程和线程内存空间的关系
9. 父子进程的介绍
10. 孤儿进程和僵尸进程    
    - 这个我讲反掉了
11. kill一个进程的时候，都发生了那些事情，从父子进程角度讲
12. 反弹shell的几种方式    
    - 本质是用tcp协议传输bash程序
13. att&ck矩阵的类别，介绍其中的CC
14. 到域名下拿到命令执行的结果
    - 这部分没听清楚，面试的时候直接说了不知道，复盘听录音还是没怎么听清，但好像大概想问的是DNS域名解析获取命令执行回显
15. Linux命令通配符
16. 护网的溯源、威胁分析工作之类的问了十分钟左右
    - 完全不会，以后简历上再也不写护网了
17. xx攻防演练中防守方有哪些手段，问的比较杂，主要就是问入侵痕迹检测和溯源之类的东西
    - 这部分也不太会

18. SVM、KNN介绍

19. 卷积神经网络介绍

20. 莱文斯坦距离

21. 搜索引擎算法
    - 不太了解，大概讲了下字典树

22. 倒排索引
23. 恶意样本给出函数家族的md5，如何进行分类
    - 从统计规律讲了下
24. 反问



## 二面

时长：半小时

1. 第一个问题就直接问了护网，和一面问的差不多，直接裂开
2. Linux开机自启动方式
3. init.d脚本介绍
4. Linux怎么查看程序调用了哪些文件
5. 如何监控Linux文件操作
   - 问到这里就已经非常慌了，Linux比较进阶的操作都不是很会，而且面试官一直在叹气我日
6. Linux有哪些系统调用
   - 不会
7. GDB调试
   - 不会
8. 查看Linux开放的网络端口、多线程状态
9. 反弹shell的方式
10. Linux下怎么隐藏文件
11. 子域名收集
12. DNS重绑定
13. DNS解析的流程
14. CC流量
    - 听都没听过
15. ssh隧道
    - 面试没听清楚，听到隧道就以为是UDP穿越隧道开讲了
16. https证书机制介绍
17. burpsuite一些使用方法，插件开发方法
18. nmap的基本操作
19. syn开放链接原理
20. redis漏洞利用
21. runc容器逃逸原理
22. 常见WAF种类(不知道为什么还特别问了长亭的WAF)
23. MySQL的UAF
    - 没听过
24. 算法题(比较简单，leetcode easy级别)
25. Linux进程通信
26. 反问



---

> 备注：从0x18~0x1B均来自于许少牛客网的分享，不多说了，许少yyds
>
> 作者：4ra1n
>
> 链接：https://www.nowcoder.com/discuss/772753?source_id=profile_create_nctrack&channel=-1
>
> 来源：牛客网

# 0x18 某四字大厂面试复盘

这个面试有许少的两个问答式文章，建议参考

一面链接：https://zhuanlan.zhihu.com/p/412934756

二面链接：https://zhuanlan.zhihu.com/p/413684879

## 一面

1. 看你做java多一些，讲讲java内存马原理和利用
2. 那你讲下如何查杀java内存马，工具和原理角度
3. 冰蝎和哥斯拉了解吗，讲讲原理
4. 你之前在其他公司实习做了些什么事情
5. 有绕waf的实战经验吗，从各种漏洞的角度谈下
6. 熟悉webshell免杀吗，讲下原理
7. 做过其他免杀吗，比如结合cs和msfvenom的
8. 谈谈fastjson反序列化原理和常见利用链吧
9. 数据结构熟悉吗，谈谈红黑树原理
10. java的hashmap用到红黑树，讲下hashmap的原理
11. 有没有流量分析的经验
12. 谈谈代码审计经验
13. 看你有些cnvd和cve，讲讲挖洞的过程
14. 有打过知名的ctf吗，讲将经历
15. 熟悉内网渗透，域控这些，说一下实战经历
16. 谈谈java反序列化的cc链原理吧
17. 看你重写过sqlmap，读过sqlmap源码吗
18. 看你熟悉mysql，讲讲索引，存储结构等
19. 讲讲mysql为什么要用b+树
20. 看过mysql源码吗
21. 分析过二进制漏洞吗
22. 有没有用汇编写过东西
23. 谈谈linux内核的漏洞
24. 挖过缓冲区溢出漏洞吗
25. python的沙箱逃逸了解吗
26. python的flask模版注入讲讲
27. 看你做过抽象语法树相关的项目，谈一谈
28. 讲讲rasp的概念和原理
29. 谈谈rasp的对抗
30. 谈谈php和golang语言本身的安全问题
31. 机器学习和算法相关懂嘛
32. 看你尝试写过简单的操作系统，谈谈思路
33. 你有什么要问我的吗

## 二面

1. 讲讲你挖过印象最深的洞
2. 讲讲你写过的安全工具，从出发点和原理层面谈谈
3. 讲讲文件上传这里怎样绕WAF
4. SSRF的利用和绕WAF手段
5. 谈谈MSSQL如果XPCMDSHELL不能用怎么拿SHELL
6. 遇到没有回显的RCE怎么办
7. 不使用SQLMAP的OS-SHELL，各种数据库怎么写SHELL
8. 给你一个比较大的日志，应该如何分析
9. 谈谈redis未授权会导致哪些问题
10. 讲讲SYN FLOOD原理，防御，检测手段
11. 讲讲UDP反射放大的原理，防御，检测手段
12. 说一说自己的优势吧
13. 你有什么要问我的吗

## 三面

1. Padding Oracle Attack讲讲
2. Fastjson反序列化原理以及1.2.47绕过的原理
3. 除了readObject以外造成反序列化的函数有哪些
4. CC链中找你最熟悉的几条链讲一讲
5. Shiro550反序列化的原理及利用工具编写思路
6. Spring/Struts2的RCE中印象最深的讲一讲分析过程
7. sql注入绕WAF的方式尽可能多说
8. 分块传输绕WAF的原理
9. 文件上传绕WAF的方式都有哪些
10. 讲讲你挖过这些CVE中印象最深的
11. 你自己最大的优点和缺点是什么
12. 未来你想做安全的哪一个领域
13. 你学校成绩如何有挂科吗
14. 你有什么要问我的吗



# 0x19 某四字大厂实习面试复盘

## 一面

1. 自我介绍
2. 数组和链表各自的优势和原因
3. 操作系统层面解释进程和线程区别
4. 线程和进程通信方式以及数据安全问题
5. 多进程和多线程的选用场景以及原因
6. 了解过哪些WAF说说原理
7. 尽可能多地说下SQL注入绕WAF方式
8. FUZZ绕WAF的Payload长度通常是多少
9. 写过哪些正则说说具体的场景
10. 不查资料不能测试直接写ipv4的正则
11. Fastjson的反序列化原理
12. Java反射机制会导致怎样的安全问题
13. XSS和CSRF的相同点以及如何配合利用
14. CSRF_TOKEN的位置以及原理和绕过
15. 尽可能多地说你所知道的HTTP头
16. Nmap常见扫描方式的原理以及NSE脚本原理
17. 看到你有不少CNVD证书讲一讲挖洞过程
18. 讲一讲你考过的证书都学到了些什么
19. 看到你Github有不少项目讲讲
20. 你觉得自己还有什么亮点吗
21. 你有什么要问我的

## 二面

1. 自我介绍
2. 熟悉哪些Web漏洞讲讲
3. 跨域的解决办法原理以及安全问题
4. Python多进程和多线程如何选择
5. Python的GIL锁本质上做了什么事情
6. Java的JVM为什么要有GCROOT
7. Java的JVM有哪些垃圾收集器
8. 垃圾回收计数引用机制的缺点是什么
9. CSRF怎么拿到Cookie
10. 如何判断一个网站是钓鱼网站
11. 不同域名怎样通过CSRF拿Cookie
12. 说一些常见的HTTP头以及作用
13. HTTP-Only本质上做了什么事情
14. 平衡二叉树和二叉搜索树讲一下
15. SYN Flood攻击原理及解决方案
16. SYN 反向探测的原理是什么
17. TCP SYN Cookie的原理
18. ARP欺骗攻击原理及解决方案
19. UDP端口探测的有效方式是什么
20. Nmap的FIN扫描和空扫描是什么
21. 三次握手的序列号变化说一下
22. Python的值类型和引用类型是哪些
23. Python的list和dict线程安全吗
24. 讲一下你做过收获最大的一个项目
25. 你有什么要问我的

## 三面

1. 自我介绍
2. 解释下CSRF
3. 结合实际的例子说说SSRF
4. 结合实际的例子讲讲RCE
5. 为什么现在文件上传很少了
6. 基于语义分析的WAF了解吗
7. 讲一下你上一段实习做了什么
8. 讲几个印象深刻的挖洞经历
9. 讲一下你对未来的规划
10. 有没有转正的意愿
11. 你有什么要问我的

## 四面（HR）

1. 面试的体验怎么样
2. 谈人生理想
3. 最早实习时间



# 0x1A 某两字大厂面试复盘

## 一面

1. 自我介绍
2. 前两段实习做了些什么
3. 中等难度的算法题
4. java的class文件结构
5. kafka的原理了解吗
6. fastjson反序列化原理
7. 讲讲你研究最深入的领域

## 二面

1. 排序处不能用预编译应该怎么防
2. 从白盒黑盒两个角度讲下挖过的漏洞
3. ssrf的绕过和防御
4. 讲讲fortity等代码审计工具原理
5. 存储过程角度讲讲预编译的原理
6. csp是如何防御xss的
7. csrf为什么用token可以防御
8. 给你一个项目讲下审计思路
9. 内网相关的问题
10. 讲下你挖过的逻辑漏洞
11. 讲讲你用golang写过的东西
12. 什么是安全

## 三面

1. 讲下你自己写ysoserial的思路
2. 确定sql注入漏洞后如何进一步利用
3. 泛微OA的漏洞原理讲讲
4. 新爆出的Confluence RCE讲讲
5. 以前的实习中做了什么事
6. ***原理以及实战中的绕过
7. 红蓝对抗的流程讲讲

## 四面

1. java反序列化原理和工具
2. 讲讲关于指纹识别的方式
3. shiro反序列化工具的原理
4. 不用sqlmap情况下sql注入点如何找
5. 讲讲你挖到的这几个cve
6. 二进制方面有无了解



# 0x1B 某安全公司-安全研究员

## 一面

1. 讲讲你写的几个Burp插件原理
2. 做过什么JavaWeb项目吗
3. CC1-7找熟悉的讲一下原理
4. Fastjson和Jackson反序列化原理讲讲
5. BCEL可以用其他类加载器吗
6. XStream反序列化讲讲
7. 最基本的反序列化原理是什么
8. 了解JEP290的原理吗
9. 讲下RMI原理以及相关的漏洞
10. JdbcRowSetImpl如何触发的JNDI注入
11. CC链四个Transformer区别
12. 讲下你挖过的CVE和CNVD
13. 反序列化除了readObject还有什么触发点
14. 讲下Spring相关的RCE原理
15. 讲讲IIOP和T3反序列化原理
16. PHP等语言的反序列化讲讲

## 二面

1. 做了几年安全
2. 未来想做什么
3. 讲讲实习期间做的事
4. 工作地点要求
