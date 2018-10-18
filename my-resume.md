
> 本简历网址：[https://github.com/fonoisrev/backups/blob/master/my-resume.md](https://github.com/fonoisrev/backups/blob/master/my-resume.md)

# 联系方式

- 手机/微信号：13925219347
- Email：wuhangdeyouxiang@126.com / 13925219347@126.com
- QQ：413896368

---

# 个人信息

 - 吴航 / 男 / 1988 
 - 本科 / 南京邮电大学 计算机学院 信息安全专业
 - 工作年限：8年
 - 技术博客：[https://www.jianshu.com/u/aa97fc7f3536](https://www.jianshu.com/u/aa97fc7f3536)
 - Github：[https://github.com/fonoisrev/](https://github.com/fonoisrev/)

 - 期望职位：Java专家，架构师
 - 期望薪资：税前年薪100w（包括股票期权）
 - 期望城市：深圳

---

# 工作经历

## 中移信息技术有限公司（2011年6月 ~ 至今）
> 毕业至今一直在此就职，公司前身是**中国移动（深圳）有限公司**，于2018年初改名。

### 项目：中国移动一级充值支付中心 （2013年 ~ 至今）
> 此项目原名*统一支付*，至今已经历了5期（5年）的建设。从2013年白手起家，至今已经发展成为中国移动的**聚合支付**与**聚合充值**后台核心系统。2017年-2018上半年成交总金额超过2900亿元，交易量4800万笔，峰值超过2000TPS。

> 在此过程中，我也从一个基础开发人员成长为架构师。目前，我是此项目的 **技术负责人** 与 **主程序员** ，主要工作职责包括 **规范制订、架构设计、详细设计、核心代码编写、性能测试等、也参与过运维工作** 。

我对此项目的主要贡献包括：

1. 为了简化接入，我设计了一套支付流程，一个接口聚合多家支付机构。
2. 为了性能、可扩展性与团队分工，我主导将系统迁移到微服务架构。
3. 我编写了基于Spring-Boot的支付开发框架，统一了日志打印、异常处理、缓存、通信等基础功能。
4. 我主导了系统的性能测试工，完成调优后，在20台Linux服务器（12Core/128G）上实现4000TPS的目标。
5. 我定位并解决一些产生问题，如 JVM栈溢出、连接池死锁、CPU占用率高等（部份问题在博客中有记录）。
6. 为了避免搭建复杂的ActiveMQ集群，我设计并实现了客户端负载均衡的ActiveMQ集群方案，并开源到GitHub。
7. 为了让没有编程基础的业务人员也能使用规则引擎，避免语言化的规则配置，我设计并实现了为支付记账专用规则引擎，目前正在申请专利。
8. 为了解决开发人员多地办公的版本同步问题，我主导使用Git替代SVN。
9.  为了实现精细化监控，我主导搭建了基于SkyWalking的全链路跟踪框架。
10. 为了方便查看生产日志，我主导使用ELK对系统日志进行归集。

---

# 开源项目和作品

## 开源项目

- [ActiveMQ-ClientSide-LoadBalance](https://github.com/fonoisrev/ActiveMQ-ClientSide-LoadBalance)

  客户端负载均衡的ActiveMQ集群方案，使用Spring-Boot自动加载，这个是我开源的，已发布到Maven中央仓库中。
- [JsonSurfer](https://github.com/fonoisrev/JsonSurfer)

  一个从Json字符串中搜索关键字段的项目，在使用过程中发现了NullPointerException问题，因此，我贡献了一个解决此问题的 [Pull Request](https://github.com/jsurfer/JsonSurfer/pull/40)，并被采纳。

## 技术文章

- [从零打造聚合支付系统：三、应用微服务架构](https://www.jianshu.com/p/041c65498ede)
- [从零打造聚合支付系统：二、建立领域模型](https://www.jianshu.com/p/a2b96d374d98)
- [从零打造聚合支付系统：一、浅谈聚合支付的核心价值](https://www.jianshu.com/p/9a2d5bfe6fee)
- [整合积分红包话费流量，玩转多凭证支付流程](https://www.jianshu.com/p/75b6e7a870cd)
- [StackOverflowError：正则表达式栈溢出错误](https://www.jianshu.com/p/87d0175e1aed)
- [【源码分析】Spring Boot中Relaxed Binding机制的不同实现](https://www.jianshu.com/p/a1fbfc4f9e12)
- [【源码阅读】看Spring Boot如何自动装配ActiveMQ收发组件](https://www.jianshu.com/p/6d6d6fe7a2b7)
- [APPARENT DEADLOCK!!! - C3P0连接池DeadLock机制分析](https://www.jianshu.com/p/1a0d5129b884)
- 更多文章请查看个人技术博客：[https://www.jianshu.com/u/aa97fc7f3536](https://www.jianshu.com/u/aa97fc7f3536)

---

# 技能清单

以下均为我熟练使用的技能
- Java与JVM机制：Lambda / NIO / 并发与锁 / 内存与GC / 字节码与类加载 
- Spring框架：Spring-Boot / Spring-Cloud / Mybatis / Thymeleaf / Struts / Hibernate / Freemarker / JPA
- 协议： HTTP / JMS / DCC
- 中间件： ActiveMQ / Redis / Tomcat / Nginx / Workflow
- 开发工具： IDEA / Eclipse / Maven / Svn / Git / Ant
- WEB前端框架：Bootstrap / AngularJS / JQuery
- 数据库相关：MySQL / Oracle
- 文档和自动化部署工具：Swagger / Jenkins / Docker
- 其它语言与平台：Python / Shell（Linux） / Hadoop / Groovy / PHP / SQL

以下是我的业余爱好
- 电吉他
- 游泳

---

# 荣誉

> - 阿里云栖社区专家，昵称：天上只北
> - 2015年与2017年两次获评公司“优秀党员”称号
> - 2014年、2015年、2017年三次获评公司“优秀员工”称号

---

# 致谢
感谢您花时间阅读我的简历，期待能有机会和您共事。
