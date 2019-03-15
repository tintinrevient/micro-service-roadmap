## 痛点 或者 为什么要用微服务
* 高并发
* UI/UX统一
* 定制开发和部署每个城市的不同系统，不同版本
* 推送服务器不稳定
* 单点登录
* 开发，测试与发布版本的流程？

## 微服务能做什么？
* 不同项目组技术选型的独立性
* 低耦合，高业务相关
* 易扩展，高容错

## 微服务不能做什么？
* 增加性能，加快响应时间
* UI/UX统一
* 定制开发和部署每个城市的不同系统，不同版本

## Before和After项目微服务化的测试指标 或者 技术选型量化指标
* Availability（100% 90% 80%）
* Performance（响应时间多少毫秒？比如在高并发时，比如数据插入与查询）
* Maintenance（代码维护和重用，低耦合，高业务相关）
* Scalability（是否易于扩展，比如数据库扩展）
* 现有技术人员的合理分配与将来的技术培养（前后端分离？怎么持续集成？怎么自动化测试？项目分组？）

## 现有项目可改进的地方
* 前后端分离
  * 前端代码没压缩，导致Performance得分低： https://developers.google.com/speed/pagespeed/insights/?url=http%3A%2F%2F171.217.92.33%3A43170%2Furban-screen%2F&tab=desktop
  * 难以针对接口的自动化测试
* 没有持续集成（微服务带来的一个好处是不用发布Monolith版本）
  * 开发流程和代码规范
  * 不同环境，不同版本的部署以及测试流程，发布流程
  * 监控

## 现有项目分析和重构演进路线
* 服务接口与数据格式的定义
* 高业务相关的服务界定：Structure 101
* 数据库解耦合，Transaction解耦合：SchemaSpy

## 技术架构

## 疑难
* 如何部署到腾讯云，阿里云和政务云（Spring Cloud和AWS结合很好）
* 技术盲区和技术学习（可不可以通过做PoC来排难？从最简单可掌握的开始）
  * Spring Boot
  * Spring Cloud Netflix
  * Maven/Gradle
  * Git
  * Redis
  * NOSQL DB（MongoDB, Cassandra, HBase...）
  * Nginx
  * Jenkins
  * Web Socket
  * 前端框架？
  * Docker?
  * DevOps?
  * Automation Test（Python, Prometheus, Grafana...）

## 开发人员发展方向

![Web Developer Roadmap Introduction](./images/intro.png)

## Frontend Roadmap

![Frontend Roadmap](./images/frontend.png)

## Back-end Roadmap

![Back-end Roadmap](./images/backend.png)

## DevOps Roadmap

![DevOps Roadmap](./images/devops.png)
