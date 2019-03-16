## Team Structure
Team structure is reflected in a service’s architecture with the roles below for a web application development team: 
* UX designer: Standardization of UI/UX for the company’s brand.
* FED(Front End Developer):Static views implementation, decouple dwith the data provided from the services. 
* BED(Back End Developer): Services implementation and maintenance.
* Tester: Manual and automatic tests to ensure the quality of UI, security, performance, etc. 
* DevOps: CI/CD infrastructure (Infrastructure as Code) and application-operation monitoring.
![Team Structure](./images/team-structure.png)

目前的问题：
* 没有UX人员，导致用户体验不统一。
* 前后端没有分离，导致数据绑定到页面：前端无法独立开发页面，后端无法独立实现微服务接口。
* 测试指标应该明确，比如UI测试，安全测试，性能测试等。
* 没有运维人员，导致本地环境=开发环境=测试环境=生产环境；部署不是代码化，而是手动进行；没有健康监控。

## Microservice Architecture
The Microservice architecture includes modules as below:
* API Gateway: Web applications can scale easily in response to load and performance bottleneck with products like Nginx, Netflix Zuul, Spring Cloud Gateway, Linkerd, Envoy, Undertow, Gatling.
* Cache: Redis or Memcached can maintain session state for days, weeks and months to keey track of states while users interact with multiple stateless services or store the transient real-time data. 
![Microservice Architecture](./images/Microservice_Architecture.png)


![Web Developer Roadmap Introduction](./images/intro.png)

## Frontend Roadmap

![Frontend Roadmap](./images/frontend.png)

## Back-end Roadmap

![Back-end Roadmap](./images/backend.png)

## DevOps Roadmap

![DevOps Roadmap](./images/devops.png)
