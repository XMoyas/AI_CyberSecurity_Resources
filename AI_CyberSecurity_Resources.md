# AI_CyberSecurity_Resources
随着人工智能的兴起，国家对网络安全环境的极度重视，ML/DL+网络安全也逐步成为防守方的一大利器，虽然目前还存在很多问题，但我们仍然可以预见该技术将会成为中流砥柱，让我们一起共同努力，为营造一个良好的安全环境而努力。  

**该文档主要记录本人在ML/DL+网络安全方向的所见所想，始于2022.11.18，终于未来，以此为记录，梳理知识框架，同时希望能够帮助到有需要的同行和对此感兴趣的您，若您有希望我改进的地方，欢迎提issue，大家共同进步，也臭不要脸的希望能有个star。**

---

## AI CyberSecurity比赛

* [competition](https://github.com/XMoyas/AI_CyberSecurity_Resources/blob/main/AI_CyberSecurity_competition.md)

## 优秀的AI CyberSecurity Github&博客
<details>
<summary></summary>
    
* 我的AI安全检测学习笔记 [[博客](https://4o4notfound.org/index.php/archives/127/)]
* dataRisk-detection-resources [[Github](https://github.com/LiaoWenzhe/dataRisk-detection-resources/blob/main/README_zh-CN.md)] 
* 网络安全中机器学习大合集 [[Github](https://github.com/jivoi/awesome-ml-for-cybersecurity/blob/master/README_ch.md)]
</details>

## 优秀的AI CyberSecurity 书籍推荐
<details>
<summary></summary>
    
* 《Web安全之机器学习入门》
* 《Web安全之深度学习实战》
* 《Web安全之强化学习与GAN》
</details>

## CyberSecurity之工具篇
<details>
<summary></summary>
    
* 开源WAF工具：[ModSecurity](http://www.modsecurity.cn/)
* XSS注入工具：[Nikto](https://github.com/sullo/nikto)，	[OWASP Xenotix XSS](https://github.com/ajinabraham/OWASP-Xenotix-XSS-Exploit-Framework)、XSSChop、Libinjection
* SQLi工具：SQLMap、Libinjection、SQLChop、JSQL injection、超级SQL注入工具
* 开源IDS工具：Snort、Suricata、Zeek、OSSEC
</details>

## CyverSecurity之WAF
<details>
<summary></summary>
    
* 腾迅WAF： WAF建设运营及AI应用实践 [[技术文章](https://security.tencent.com/index.php/blog/msg/145)
* 开源WAF工具：ModSecurity [[官网](http://www.modsecurity.cn/)]
* Fortinet WAF： FortiWeb Release 6.0: AI-based Machine Learing for Advanced Threat Detection [[技术文章](https://www.fortinet.com/blog/business-and-technology/fortiweb-release-6-0--ai-based-machine-learning-for-advanced-thr)]
* 阿里云WAF: 揭秘阿里云WAF背后神秘的AI智能防御体系 [[技术文章](https://developer.aliyun.com/article/723263?spm=a2c6h.14164896.0.0.7cc13a49u3CTps)]
</details>

## AI+Web攻击检测篇
* [AIweb安全](https://github.com/XMoyas/AI_CyberSecurity_Resources/tree/main/AI_CyberSecurity_web)
<details>
<summary>Web安全之SQLij检测</summary>

</details>

<details>
<summary>Web安全之XSS检测</summary>
    
**1、XSS攻击之原理篇**

**2、AI + XSS攻击检测(博客等)**

* XSSChop：XSS语义分析 [[技术文章](https://blog.51cto.com/u_15127693/4117204)]

**3、XSS攻击&检测开源方案&工具篇**

* Libinjection
* Nkito
* OWASP Xenotix XSS

**4、XSS攻击检测与防御论文之综述**
**5、XSS攻击检测与防御论文之ML/DL**
* GraphXSS: An efficient XSS payload detection approach based on graph convolutional network [[Paper](https://dl.acm.org/doi/10.1016/j.cose.2021.102597)] 

**6、XSS攻击检测与防御论文之语义分析**
**7、XSS攻击检测与防御论文之对抗攻击**
* Black-box adversarial attacks on XSS attack detection model，2021，Computer and Security [[Paper](https://dl.acm.org/doi/10.1016/j.cose.2021.102554)]

</details>
    
<details>
<summary>Web安全之命令注入检测</summary>
</details>

<details>
<summary>web安全之webshell检测</summary>

**1、Webshell原理篇**
**2、AI + Webshell攻击检测(博客等)**
* 主机安全-洋葱Webshell检测实践与思考 [[博客](https://security.tencent.com/index.php/blog/msg/152)]
</details>

<details>
<summary>Web安全之代码执行检测</summary>

</details>

## CyberSecurity之知识图谱篇
- AKG：攻击者知识图谱 [[博客](https://4o4notfound.org/index.php/category/%E5%AE%89%E5%85%A8%E7%AE%97%E6%B3%95/)]

---

## CyberSecurity之DGA/DNS/DoH隐蔽隧道篇
<details>
<summary></summary>
    
- DNS隧道通信特征与检测 [[技术文章](http://blog.nsfocus.net/dns-tunnel-communication-characteristics-detection/?from=timeline)]
- 机器学习与威胁情报的融合：一种基于AI检测恶意域名的方法 [[技术文章](https://www.freebuf.com/articles/es/187451.html)]

* Understanding DoH and DoT [[技术文章](https://incompass.netstar-inc.com/understanding-doh-and-dot/)]
* DoH Insight: Detecting DNS over HTTPS by Machine Learning [[技术文章](https://sappan-project.eu/wp-content/uploads/2020/09/DOH-2.pdf)]

</details>

---

## CyberSecurity之图神经网络
[AI安全之图神经网络](https://github.com/XMoyas/AI_CyberSecurity_Resources/blob/main/AI_CyberSecurity_GNN.md)

## AI模型安全篇


---

## AI+CyberSecurity经验总结
1、Web安全检测中机器学习的经验之谈 [[博客](https://iami.xyz/ML-IN-Webshell-Detection-Advantages-And-Disadvantages/)]
2、

---

## AI+CyberSecurity数据合集
<details>
<summary>AI安全数据集</summary>
    
1、HTTP DATASET CSIC 2010 ：包含SQL注入、XSS等攻击数据 [[DataSet](https://www.tic.itefi.csic.es/dataset/)]

2、xssed ：包含XSS攻击数据集 [[DataSet](http://www.xssed.com/)]

3、foospidy payloads：包含XSS、SQLi等各种数据集 [[DataSet](https://github.com/foospidy/payloads)]

4、Web安全书籍数据集：包括XSS、SQLI、Webshell、DGA、KDDcup99等各种数据集 [[DataSet](https://github.com/duoergun0729/1book/tree/master/data)]

5、swisskyrepo PayloadsAllTheThing：包含SQLi、XSS等各种数据集 [[DataSet](https://github.com/swisskyrepo/PayloadsAllTheThing)]

6、Advanced-SQL-Injection-Cheatsheet：包含SQL注入数据集 [[Dataset](https://github.com/kleiton0x00/Advanced-SQL-Injection-Cheatsheet)]
</details>
