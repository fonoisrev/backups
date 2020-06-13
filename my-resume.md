# 吴航

- 男 / 1988年
- 手机号：13925219347
- Email：wuhangdeyouxiang@126.com
- 本科 / 南京邮电大学 计算机学院 信息安全专业
- 工作年限：10年
- 期望职位：Java专家，架构师（支付或国际化中台方向）
- 期望城市：深圳

---

# 技能清单

- **Java编程及JVM调优**：并发与锁 / 线程调优 / 内存与GC调优 / NIO
- **后端框架**：Spring / Spring-Boot / Mybatis / Hibernate / JPA / Dubbo / Thymeleaf / Struts / Freemarker
- **中间件**：Redis / RocketMQ / ActiveMQ / Nginx / 工作流引擎
- **Sql及NoSql数据库**：Mysql / Oracle / MongoDB / Hbase / Hive
- **分布式理论及协议**：CAP / 微服务（Dubbo） / TCC / HTTP / JMS / AMQP / DCC
- **周边工具**： Maven / Ant / Git / Svn / Gradle 
- **H5前端框架**：Bootstrap / AngularJS / JQuery
- **其它技术**：Python / Shell / Groovy / 深度学习

---

# 工作经历

## OPPO 金融事业部（2019年1月 ~ 至今）

#### 项目：安全支付（中国及东南亚七个地区）

> OPPO、OnePlus、Realme手机上支付入口，业务范围覆盖中国、印度、印尼、泰国、越南、菲律宾、日本等多个国家，支持钱包支付、银行卡扣款、运营商短信扣费、点卡充值支付等多种不同的支付方式。

#### 主要贡献：

> 负责落地业务需求、提供解决方案、及系统的维护与优化。主要工作内容包括 **技术规范制订、架构设计、代码编写、性能测试、线上运维及调优**

1. 用一套聚合流程及接口，屏蔽不同支付满渠道的差异，并实现渠道分流。
2. 落地代币系统，解决海外支付存在差额的情况。
3. 落地优惠券及活动系统，满足营销推广的需要。
4. 落地对账系统，实现自动对账过程中灵活的人工审批，解决时差及汇率差异造成的差异。
5. 落地双机房双活灾备部署的方案。

## 中国移动（深圳）有限公司（2011年6月 ~ 2019年1月）

#### 项目：中国移动一级充值支付中心

> 是中国移动的**聚合支付**与**聚合充值**后台核心系统。交易量超过4800万笔/年。

#### 主要贡献：

> 是此项目的 **技术Leader** ，主要工作内容包括 **业务规范制订、架构设计、代码编写、性能测试、以及线上运维** 

1. 引入互联网常用框架，迁移旧系统到微服务架构，接入Skyworking链路跟踪，使用ELK对归集日志。
2. 编写了基于Spring-Boot的支付开发框架，统一了日志打印、异常处理、缓存、通信等基础功能。
3. 主导性能测试，完成调优，在20台Linux服务器（12Core/128G）上实现400TPS的目标。
4. 定位并解决难点问题，如 JVM栈溢出、连接池死锁、CPU占用率高等。
5. 设计并实现了客户端负载均衡的ActiveMQ集群方案，并开源到GitHub。
6. 设计了产品人员友好的记账专用规则引擎，避免语言化的规则配置。
7. 从SVN过渡到Git，解决开发人员多地办公的版本同步问题，主导使用Git替代SVN。

---

# 开源项目

- [ActiveMQ-ClientSide-LoadBalance](https://github.com/fonoisrev/ActiveMQ-ClientSide-LoadBalance)
  
  客户端负载均衡的ActiveMQ集群方案，使用Spring-Boot自动加载。

- [JsonSurfer](https://github.com/fonoisrev/JsonSurfer)
  
  一个从Json字符串中搜索关键字段的项目，解决了其NullPointerException问题，贡献了被采纳的代码。

---

# 技术博客

[https://www.jianshu.com/u/aa97fc7f3536](https://www.jianshu.com/u/aa97fc7f3536)

- [从零打造聚合支付系统：三、应用微服务架构](https://www.jianshu.com/p/041c65498ede)
- [从零打造聚合支付系统：二、建立领域模型](https://www.jianshu.com/p/a2b96d374d98)
- [从零打造聚合支付系统：一、浅谈聚合支付的核心价值](https://www.jianshu.com/p/9a2d5bfe6fee)
- [整合积分红包话费流量，玩转多凭证支付流程](https://www.jianshu.com/p/75b6e7a870cd)
- [StackOverflowError：正则表达式栈溢出错误](https://www.jianshu.com/p/87d0175e1aed)
- [【源码分析】Spring Boot中Relaxed Binding机制的不同实现](https://www.jianshu.com/p/a1fbfc4f9e12)
- [【源码阅读】看Spring Boot如何自动装配ActiveMQ收发组件](https://www.jianshu.com/p/6d6d6fe7a2b7)
- [APPARENT DEADLOCK!!! - C3P0连接池DeadLock机制分析](https://www.jianshu.com/p/1a0d5129b884)
