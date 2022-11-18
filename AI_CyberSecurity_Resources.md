# AI_CyberSecurity_Resources
随着人工智能的兴起，国家对网络安全环境的极度重视，ML/DL+网络安全也逐步成为防守方的一大利器，虽然目前还存在很多问题，但我们仍然可以预见该技术将会成为中流砥柱，让我们一起共同努力，为营造一个良好的安全环境而努力。  

**该文档主要记录本人在ML/DL+网络安全方向的所见所想，始于2022.11.18，终于未来，以此为记录，梳理知识框架，同时希望能够帮助到有需要的同行和对此感兴趣的您，若您有希望我改进的地方，欢迎提issue，大家共同进步，也臭不要脸的希望能有个star。**

---

## AI CyberSecurity比赛
**进行中|待进行**

1. 天池 . [阿里云webshell文本检测大赛](https://tianchi.aliyun.com/competition/entrance/532035/introduction) ，**进行中**，初赛：2022.10.24~2022.11.25

2. DataCon.[大数据安全分析竞赛]([DataCon社区 (qianxin.com)](https://datacon.qianxin.com/datacon2022))，**即将开始，报名阶段**，2022.12.01~2022.12.10

**已结束**

1. DataFountain.[Web攻击检测与分类识别]([Web攻击检测与分类识别 竞赛 - DataFountain](https://www.datafountain.cn/competitions/596))，**已结束**， 2022.8.20~2022.11.18

2. DataFountain.[大数据平台安全事件检测与分类识别]([大数据平台安全事件检测与分类识别 竞赛 - DataFountain](https://www.datafountain.cn/competitions/595))，**已结束**，2022.8.20~2022.11
3. DataFountain.[基于人工智能的漏洞数据分类]([基于人工智能的漏洞数据分类 竞赛 - DataFountain](https://www.datafountain.cn/competitions/594))，**已结束**，2022.8.20~2022.11
4. DataFountain.[Linux跨平台二进制函数识别]([Linux跨平台二进制函数识别 竞赛 - DataFountain](https://www.datafountain.cn/competitions/593))，**已结束**，2022.8.20~2022.11

---

## 优秀的AI CyberSecurity Github&博客
1、[我的AI安全检测学习笔记](https://4o4notfound.org/index.php/archives/127/)
2、[dataRisk-detection-resources](https://github.com/LiaoWenzhe/dataRisk-detection-resources/blob/main/README_zh-CN.md)
3、[网络安全中机器学习大合集](https://github.com/jivoi/awesome-ml-for-cybersecurity/blob/master/README_ch.md)

---

## 优秀的AI CyberSecurity 书籍推荐
* 《Web安全之机器学习入门》
* 《Web安全之深度学习实战》
* 《Web安全之强化学习与GAN》

---

## CyberSecurity之工具篇
* 开源WAF工具：[ModSecurity](http://www.modsecurity.cn/)
* XSS注入工具：[Nikto](https://github.com/sullo/nikto)，	[OWASP Xenotix XSS](https://github.com/ajinabraham/OWASP-Xenotix-XSS-Exploit-Framework)、XSSChop、Libinjection
* SQLi工具：SQLMap、Libinjection、SQLChop、JSQL injection、超级SQL注入工具
* 开源IDS工具：Snort、Suricata、Zeek、OSSEC

---

## CyverSecurity之WAF
* 腾迅WAF： [WAF建设运营及AI应用实践](https://security.tencent.com/index.php/blog/msg/145)
* 开源WAF工具：[ModSecurity](http://www.modsecurity.cn/)
* Fortinet WAF： [FortiWeb Release 6.0: AI-based Machine Learing for Advanced Threat Detection](https://www.fortinet.com/blog/business-and-technology/fortiweb-release-6-0--ai-based-machine-learning-for-advanced-thr)
* 阿里云WAF: [揭秘阿里云WAF背后神秘的AI智能防御体系](https://developer.aliyun.com/article/723263?spm=a2c6h.14164896.0.0.7cc13a49u3CTps)

---

## AI+Web攻击检测篇
#### Web安全之SQLij检测
**1、SQLij攻击原理篇**
* [SQL注入攻击漏洞思维导图和原理介绍](https://blog.csdn.net/sycamorelg/article/details/125148706?spm=1001.2014.3001.5502)
* [SQL注入攻击如何分类](https://www.jianshu.com/p/52f4a371c8b7)、[SQL注入之HTTP头部注入](https://blog.csdn.net/qq_52072846/article/details/123006267)、[SQL注入分类及其各部分详解](https://www.cnblogs.com/sunny11/p/14402679.html#_label3)
* [SQL注入绕过入门总结篇](https://www.freebuf.com/articles/web/281586.html)、[SQL注入绕过技术](https://blog.csdn.net/Likhaooo/article/details/122746954)

**2、AI + SQLij攻击检测篇(博客等)**

* [基于机器学习的WEB攻击分类检测模型]( https://www.freebuf.com/news/184687.html)
* 长亭SQL注入检测方案： [SqlChop-一个新型SQL注入检测引擎](https://blog.chaitin.cn/sqlchop-the-sqli-detection-engine/)
* Fortinet SQL注入检测方案： [Syntax-based SQL Injection Detection](https://help.fortinet.com/fweb/580/Content/FortiWeb/fortiweb-admin/syntaxbased_sqli_detect.htm#syntax-sqli-detect-builtin-template)

**3、SQLij攻击&检测开源方案&工具篇**

* SQLMap、JSQL injection、超级SQL注入工具、Snort、Suricata、ModSecurity、Libinjection等

**4、SQLi攻击检测与防御论文之综述**

* A Survey on SQL Injection Attack: Detection and Challenge, 2021, ICIT
* Detection of SQL Injection Attack using Machine Learning Techniques: A Systemtic Literature Review, 2022, S&P

**5、SQLi攻击检测与防御论文之ML/DL**

* [Locate-Then_detect: Real-time Web Attack Detection via Attention-based Deep Neural Networks](https://www.ijcai.org/Proceedings/2019/0656.pdf)
* SQL Injection Attack Detection Framework Based on HTTP Traffic, 2021, ACM TURC

**6、SQLi攻击检测与防御论文之语义分析**

* [Long short-term memory on abstract systax tree for SQL injection detection](https://ietresearch.onlinelibrary.wiley.com/doi/10.1049/sfw2.12018)，2020，IET
* [Attack Intention Estimation Based on Syntax Analysis and Dynamic Analysis for SQL Injection](https://ieeexplore.ieee.org/abstract/document/9202752), 2020, IEEE

**7、SQLi攻击检测与防御论文之对抗攻击**

* A GAN-based Method for Generation SQL Injection Attack Samples, 2022, IEEE ITAIC

#### Web安全之XSS检测
**1、XSS攻击之原理篇**
**2、AI + XSS攻击检测(博客等)**

* [XSSChop：XSS语义分析](https://blog.51cto.com/u_15127693/4117204)

**3、XSS攻击&检测开源方案&工具篇**

* Libinjection
* Nkito
* OWASP Xenotix XSS

**4、XSS攻击检测与防御论文之综述**
**5、XSS攻击检测与防御论文之ML/DL**
**6、XSS攻击检测与防御论文之语义分析**
**7、XSS攻击检测与防御论文之对抗攻击**
* [Black-box adversarial attacks on XSS attack detection model](https://dl.acm.org/doi/10.1016/j.cose.2021.102554)，2021，Computer and Security

#### Web安全之命令注入检测

#### Web安全之webshell检测
**1、Webshell原理篇**
**2、AI + Webshell攻击检测(博客等)**
* [主机安全-洋葱Webshell检测实践与思考](https://security.tencent.com/index.php/blog/msg/152)

#### Web安全之代码执行检测

---

## CyberSecurity之知识图谱篇
- [AKG：攻击者知识图谱](https://4o4notfound.org/index.php/category/%E5%AE%89%E5%85%A8%E7%AE%97%E6%B3%95/)

---

## CyberSecurity之DGA/DNS/DoH隐蔽隧道篇
- [DNS隧道通信特征与检测](http://blog.nsfocus.net/dns-tunnel-communication-characteristics-detection/?from=timeline)
- [机器学习与威胁情报的融合：一种基于AI检测恶意域名的方法](https://www.freebuf.com/articles/es/187451.html)

* [Understanding DoH and DoT](https://incompass.netstar-inc.com/understanding-doh-and-dot/)
* [DoH Insight: Detecting DNS over HTTPS by Machine Learning](https://sappan-project.eu/wp-content/uploads/2020/09/DOH-2.pdf)



---

## AI模型安全篇


---

## AI+CyberSecurity经验总结
1、[Web安全检测中机器学习的经验之谈](https://iami.xyz/ML-IN-Webshell-Detection-Advantages-And-Disadvantages/)
2、

---

## AI+CyberSecurity数据合集
1、[HTTP DATASET CSIC 2010](https://www.tic.itefi.csic.es/dataset/)：包含SQL注入、XSS等攻击数据；
2、[www.xssed.com](http://www.xssed.com/)：包含XSS攻击数据集
3、https://github.com/foospidy/payloads：包含XSS、SQLi等各种数据集
4、https://github.com/duoergun0729/1book/tree/master/data：包括XSS、SQLI、Webshell、DGA、KDDcup99等各种数据集
5、https://github.com/swisskyrepo/PayloadsAllTheThing：包含SQLi、XSS等各种数据集

