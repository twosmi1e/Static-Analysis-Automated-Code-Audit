# Static Analysis & Automated Code Audit
静态分析及代码审计自动化相关资料收集

## 公开课
- [南京大学软件分析](https://pascal-group.bitbucket.io/teaching.html)，[课程视频](https://zhuanlan.zhihu.com/p/110050716)，以及一些[直播课录屏](https://space.bilibili.com/238948858/)

- [北京大学软件分析](https://xiongyingfei.github.io/SA/2020/main.htm)


## 论文
- [Detecting Node.js Prototype Pollution Vulnerabilities via Object Lookup Analysis](https://github.com/twosmi1e/Static-Analysis-and-Automated-Code-Audit/blob/main/paper/Detecting%20Node.js%20Prototype%20Pollution%20Vulnerabilities%20via%20ObjectLookup%20Analysis.pdf)
- [ConDySTA: Context-Aware Dynamic Supplement to Static Taint Analysis](https://readpaper.com/paper/3154138117)
- [A Principled Approach to Selective Context Sensitivity for Pointer Analysis](https://readpaper.com/paper/3030148664)
- [Static Analysis-Based Approaches for Secure Software Development](https://readpaper.com/paper/2884058242)
- [An Empirical Study on the Effectiveness of Static C Code Analyzers for Vulnerability Detection](https://dl.acm.org/doi/10.1145/3533767.3534380)

## 文章
### 研究者
- [从0开始聊聊自动化静态代码审计工具](https://lorexxar.cn/2020/09/21/whiteboxaudit/)
- [软件测试简介](https://github.com/RangerNJU/Static-Program-Analysis-Book)
- [白盒综述](https://forum.90sec.com/t/topic/1087)
- [基于JS语义分析的Dom-XSS自动化研究](https://mp.weixin.qq.com/s/PWVJSd6nrKt6ErnIHIPRzA)
- [构造一个CodeDB来探索全新的白盒静态扫描方案](https://lorexxar.cn/2020/10/30/whitebox-2/)
- [owasp整理的白盒工具大全](https://owasp.org/www-community/Source_Code_Analysis_Tools)
- [漏洞挖掘的艺术-面向二进制的静态漏洞挖掘](https://www.freebuf.com/articles/network/248487.html)
- [漏洞挖掘的艺术-面向源码的静态漏洞挖掘](https://www.freebuf.com/articles/network/248215.html)
- [Blackhat-Do You Speak My Language? Make Static Analysis Engines Understand Each Other](https://www.blackhat.com/us-21/briefings/schedule/#do-you-speak-my-language-make-static-analysis-engines-understand-each-other-22797)

### 企业
- 58集团白盒代码审计系统建设实践
  - [58集团白盒代码审计系统建设实践1：技术选型](https://xz.aliyun.com/t/9335)
  - [58集团白盒代码审计系统建设实践2：深入理解SAST](https://xz.aliyun.com/t/9429)
  - [Java 供应链(依赖)安全检测实践](https://mp.weixin.qq.com/s/1fnDelBE1HisEaopEyk8nQ)
- 腾讯Xcheck
  - [Xcheck之Node.js安全检查引擎](https://mp.weixin.qq.com/s/Kl9omJ91R3rGSe4h8gk0PQ)
  - [Xcheck之Python安全检查引擎](https://mp.weixin.qq.com/s/_UEofmOavtkYqNpti_FcxA)
  - [Xcheck之PHP代码安全检查](https://mp.weixin.qq.com/s/K29g9Gu-JQvOoOQ98sreBg)
  - [Xcheck之Golang安全检查引擎](https://mp.weixin.qq.com/s/VzjcXp3O8zc97aIppy4LUA)
  - [Xcheck之Java安全检查引擎](https://mp.weixin.qq.com/s/rb1BfcZeCTr2PIiypXqVjw)
  - [SAST大规模应用实践](https://mp.weixin.qq.com/s/7_r7N3X_fn22uGJWcW-8GQ)
  - [Xcheck Java引擎漏洞挖掘&防护识别](https://mp.weixin.qq.com/s/FPMUVoSqc0Lsf5BQx07ADw)
- [360移动端工具fireline](http://magic.360.cn/zh/index.html)
- [阿里代码规范检查工具](https://github.com/alibaba/p3c)
- [DevSecOps建设之白盒续篇](https://www.freebuf.com/articles/es/317975.html)

### CodeQL研究
- [代码分析引擎 CodeQL 初体验](https://paper.seebug.org/1078)
- [CodeQL 的学习以及尝试漏洞挖掘](https://bestwing.me/codeql.html)
- [Finding security vulnerabilities in JavaScript with CodeQL](https://www.youtube.com/watch?v=pYzfGaLTqC0)
- [Finding security vulnerabilities in Java with CodeQL](https://www.youtube.com/watch?v=nvCd0Ee4FgE)
- [使用 CodeQL 分析 AOSP](https://xz.aliyun.com/t/11080)
- [CodeQL 提升篇](https://xz.aliyun.com/t/10852)
- [利用CodeQL分析并挖掘Log4j漏洞](https://xz.aliyun.com/t/10707)
- [codeql分析grafana任意文件读取](https://xz.aliyun.com/t/10648)
- [如何用CodeQL数据流复现 apache kylin命令执行漏洞](https://xz.aliyun.com/t/8240)
- [使用 CodeQL 挖掘 CVE-2020-9297](https://xz.aliyun.com/t/7979)
- [codeql学习——污点分析](https://xz.aliyun.com/t/7789)
- [Codeql 入门教程](https://xz.aliyun.com/t/7657)
- [如何利用CodeQL挖掘CVE-2020-10199](https://www.anquanke.com/post/id/202987)
- [使用codeql 挖掘 ofcms](https://www.anquanke.com/post/id/203674)
- [从Java反序列化漏洞题看CodeQL数据流](https://www.anquanke.com/post/id/256967)
- [Codeql分析Vulnerability-GoApp](https://www.freebuf.com/articles/web/253491.html)
- [semgrep 分析log4j漏洞](https://www.freebuf.com/articles/web/321757.html)


## 书籍
- [编译原理](https://github.com/twosmi1e/Static-Analysis-and-Automated-Code-Audit/blob/main/book/%E7%BC%96%E8%AF%91%E5%8E%9F%E7%90%86%E9%BE%99%E4%B9%A6%E4%B8%AD%E6%96%87%E7%AC%AC%E4%BA%8C%E7%89%88.pdf)
- [Secure_programming_with_Static_Analysis](https://github.com/twosmi1e/Static-Analysis-and-Automated-Code-Audit/blob/main/book/Secure_programming_with_Static_Analysis.pdf)


## 工具
- [CodeQL](https://codeql.github.com/docs/)
- [gosec](https://github.com/securego/gosec)
- [Kunlun-M](https://github.com/LoRexxar/Kunlun-M)
- [Cobra](https://github.com/FeeiCN/Cobra)
- [sast-scan](https://github.com/ShiftLeftSecurity/sast-scan)

