

![JEECG](https://jeecgos.oss-cn-beijing.aliyuncs.com/files/logov3.png "JeecgBoot低代码开发平台")



JEECG BOOT AI Low Code Platform
===============

Current version: 3.8.2 (Release date: 2025-08-04)


[![AUR](https://img.shields.io/badge/license-Apache%20License%202.0-blue.svg)](https://github.com/zhangdaiscott/jeecg-boot/blob/master/LICENSE)
[![](https://img.shields.io/badge/Author-guojusoft-orange.svg)](http://www.jeecg.com)
[![](https://img.shields.io/badge/version-3.8.2-brightgreen.svg)](https://github.com/zhangdaiscott/jeecg-boot)
[![GitHub stars](https://img.shields.io/github/stars/zhangdaiscott/jeecg-boot.svg?style=social&label=Stars)](https://github.com/zhangdaiscott/jeecg-boot)
[![GitHub forks](https://img.shields.io/github/forks/zhangdaiscott/jeecg-boot.svg?style=social&label=Fork)](https://github.com/zhangdaiscott/jeecg-boot)



Project introduction
-----------------------------------

<h3 align="center">Java AI Low Code Platform</h3>

JeecgBoot is a `AI low code platform` based on code `generators`! Front and back end separation architecture SpringBoot2.x, SpringCloud, Ant Design&Vue, Mybatis plus, Shiro, JWT, support for microservices. The powerful code generator makes the front and back end of the code generation, low code development! JeecgBoot leads a new low-code development paradigm (OnlineCoding-> Code Generator -> Manual MERGE) that helps resolve 70% of the duplication in Java projects and makes development more business-focused. Not only can quickly improve efficiency, save research and development costs, but also do not lose flexibility!

JeecgBoot provides a series of low code modules to make Online development truly zero code: Online form development, online reports, report configuration capabilities, online chart design, large screen design, mobile configuration capabilities, form designer, online design flow, process automation configuration, plug-in capabilities (pluggable) and more!


The purpose of JEECG is: simple functions are implemented by OnlineCoding configuration, so that zero code development; Complex functions are generated by code generator and manually Merge to achieve low code development, which ensures both intelligence and flexibility. The implementation of low code development and support flexible coding at the same time, to solve the current low code products are generally not flexible drawbacks!

JEECG Business process: Using workflow to implement and extend the task interface for developing and writing business logic, forms provides a variety of solutions: form designer, online configuration form, and coding form. At the same time, the separation design of process and form (loose coupling) is realized, and the flexible configuration of task nodes is supported, which not only ensures the confidentiality of the company's process, but also reduces the workload of developers.

AI Empowering Low-Code: Currently, JeecgBoot supports AI large models such as ChatGPT and DeepSeek. The latest version defaults to using DeepSeek, which offers faster speed and higher quality. It now provides features such as AI chat assistant, AI table creation, and AI report generation.

Technical support
-----------------------------------

Problems or bugs in use can be found in [Making on the Issues](https://github.com/jeecgboot/JeecgBoot/issues/new?template=bug_report.md)


##### Project description

| Project                | description                     | 
|--------------------|------------------------|
| `jeecg-boot`    | SpringBoot background source code (support microservices)      |
| `jeecgboot-vue3` | Vue3+TS new front-end source code|
| `jeecg-uniapp` | [APP development framework, a code multi terminal adaptation, and support APP, small program, H5](https://github.com/jeecgboot/jeecg-uniapp) |


### Video Introduction

[![](https://upload.jeecg.com/jeecg/qiaoqiaoyunsite/jeecgvideo02.png)](https://www.bilibili.com/video/BV1Nk4y1o7Qc)



Download other source code
-----------------------------------
- APP SourceCode：https://github.com/jeecgboot/jeecg-uniapp



For the project
-----------------------------------
Jeecg-Boot AI low code platform can be applied in the development of any J2EE project, especially for SAAS projects, enterprise information management system (MIS), internal office system (OA), enterprise resource planning system (ERP), customer relationship management system (CRM), etc. Its semi-intelligent manual Merge development method, Can significantly improve the development efficiency of more than 70%, greatly reduce the development cost.


Starts the project
-----------------------------------

- [IDEA Quick start](https://help.jeecg.com/java/setup/idea/startup)
- [Docker Quick start](https://help.jeecg.com/java/docker/quick)



Technical documentation
-----------------------------------

- Website：  [http://www.jeecg.com](http://www.jeecg.com)
- Demo ： [OnlineDemo](http://boot3.jeecg.com) | [APP](http://jeecg.com/appIndex)
- Doc：  [DocumentCenter](http://help.jeecg.com) | [AI Config](https://help.jeecg.com/java/ai/aichat)
- Newbie guide： [Quick start](http://www.jeecg.com/doc/quickstart) |   [Q&A ](http://www.jeecg.com/doc/qa)  |  [1 minute experience](https://my.oschina.net/jeecg/blog/3083313)
- QQ group ： 964611995、⑩716488839(满)、⑨808791225(满)






Star charts
-----------------------------------

[![Star History Chart](https://api.star-history.com/svg?repos=jeecgboot/jeecg-boot&type=Date)](https://star-history.com/#jeecgboot/jeecg-boot)




Background directory Structure
-----------------------------------
```
project structure
├─jeecg-boot-parent
│  ├─jeecg-boot-base-core
│  ├─jeecg-module-demo    
│  ├─jeecg-module-system 
│  │  ├─jeecg-system-biz   
│  │  ├─jeecg-system-start system (8080）
│  │  ├─jeecg-system-api   
│  │  │  ├─jeecg-system-cloud-api  
│  │  │  ├─jeecg-system-local-api   
│  ├─jeecg-server-cloud           
     ├─jeecg-cloud-gateway       (9999)
     ├─jeecg-cloud-nacos       --Nacos(8848)
     ├─jeecg-system-cloud-start  --System(7001)
     ├─jeecg-demo-cloud-start    --Demo(7002)
     ├─jeecg-visual
        ├─jeecg-cloud-monitor       -- (9111)
        ├─jeecg-cloud-xxljob        -- (9080)
        ├─jeecg-cloud-sentinel     --sentinel (9000)
        ├─jeecg-cloud-test           
           ├─jeecg-cloud-test-more        
           ├─jeecg-cloud-test-rabbitmq     
           ├─jeecg-cloud-test-seata         
           ├─jeecg-cloud-test-shardingsphere    

```




Why JeecgBoot?
-----------------------------------
* Adopt the latest mainstream front and back separation framework (Springboot+Mybatis+antd), easy to use; Code generator has low dependency, flexible expansion ability, and can quickly realize secondary development;
* Support microservices SpringCloud Alibaba(Nacos, Gateway, Sentinel, Skywalking), and provide switching mechanism to support free switching between single and microservices
* High development efficiency, using code generator, single table, tree list, one-to-many, one-to-one and other data models, add, delete, change and search function one-key generation, menu configuration directly use;
* Code generator provides powerful template mechanism, support custom template, currently provide four sets of style template (single table two sets, tree model one set, one to many three sets)
* Code generator is very intelligent, online business modeling, online configuration, WYSIWYG support 23 kinds of controls, a key to generate front and back end code, greatly improve the development efficiency, no longer worry about repeated work.
* Low code ability: Online online form (without coding, through online configuration of the form, to achieve the addition, deletion, change and check of the form, support single table, tree, one-to-many, one-to-one model, to achieve everyone can code)
* Low code ability: Online online report (without coding, through online configuration, to achieve data report, can quickly extract data, reduce development pressure, to achieve everyone can code)
* Low code ability: Online online chart (without coding, through online configuration, to achieve graphs, bar graphs, data reports, etc., support custom layout, to achieve everyone can code)
* Complete encapsulation of user, role, menu, organization, data dictionary, online scheduled tasks and other basic functions, support access authorization, button permission, data permission and other functions
* Commonly used common package, various tools (scheduled task, SMS interface, email sending,Excel import and export, etc.), basically meeting 80% of project requirements
* Easy Excel import and export, support single table export and one-to-many table mode export, generated code with import and export function
* Integrated simple report tools, image report and data export is very convenient, can be extremely convenient to generate graphical reports, pdf, excel, word and other reports;
* Before and after the separation technology, the page UI style is exquisite, for the commonly used components to do the encapsulation: time, row table control, interception display control, report component, editor and so on
* Query filter: query function automatically generated, the background dynamic spell SQL additional query conditions; Supports multiple matching modes (full matching, fuzzy query, included query, and unmatched query).
* Data permission (fine data permission control, control to row level, list level, form field level, realize different people see different data, different people operate different fields on the same page
* Page verification automatically generated (must be input, digital verification, amount verification, time and space, etc.);
* Support SAAS service model and provide SaaS multi-tenant architecture solution.
* Distributed file service, integration of minio, Ali OSS and other excellent third parties, to provide convenient file upload and management, but also support local storage.
* Mainstream database compatibility, a set of code is fully compatible with Mysql, Postgresql, Oracle, Sqlserver, MariaDB, dream and other mainstream databases.
* Integrate workflow flowable and realize only the configuration of flow direction in the page, which can greatly simplify the development of bpm workflow; Using bpm's process designer to draw the flow direction, a workflow is basically complete with a small amount of java code;
* Low code ability: online process design, using open source Activiti process engine, to achieve online drawing process, custom form, form attachment, business flow
* Multi-data source: its simple way of use, online configuration of data source configuration, convenient to grab data from other data;
* Provide single sign-on CAS integration solution, and complete docking code has been provided in the project
* Low code ability: form designer, support user custom form layout, support single table, one to many forms, support select, radio, checkbox, textarea, date, popup, list, macro and other controls
* Professional interface docking mechanism, unified using restful interface, integrated swagger-ui online interface documentation, Jwt token security verification, convenient client docking
* Interface security mechanism, can be refined control interface authorization, very simple to realize different clients only see their own data control
* Advanced combination query function, online configuration support primary and sub-table associated query, can save the query history
* Provide a variety of system monitoring, real-time tracking system running conditions (monitoring Redis, Tomcat, jvm, server information, request tracking, SQL monitoring)
* Message center (support SMS, email, wechat push, etc.)
* Integrate Websocket message notification mechanism
* Excellent mobile adaptive effect, providing APP release scheme:
* Support multiple languages and provide internationalization solutions;
* Data change record log, can record each change of data content, through the version comparison function to view historical changes
* The platform UI is powerful and mobile adaptation is implemented
* Platform home page style, provide a variety of combination mode, support custom style
* Provide easy to use print plug-in, support Google, Firefox, IE11+ and other browsers
* Rich sample code, provide a lot of learning case reference
* Using maven module development method
* Support dynamic menu routing
* RBAC (Role-Based Access Control) is used for permission control.
* Provide new row edit table JVXETable, easily meet a variety of complex ERP layout, with higher performance, more flexible extension, more powerful functions

 
 
 
Technical Architecture:
-----------------------------------

#### Development Environment

- Language: Java Default Jdk17(support jdk8、jdk21)

- IDE(JAVA) : IDEA (lombok plug-in must be installed)

- IDE(front-end) : Vscode, WebStorm, IDEA

- Dependency management: Maven

- Cache: Redis

- Database: MySQL5.7 + [More Databases](https://my.oschina.net/jeecg/blog/4905722)


#### backend

- Basic framework: Spring Boot 2.7.18

- Microservice framework: Spring Cloud Alibaba 2021.0.6.2

- Persistence layer framework: MybatisPlus 3.5.3.2

- Report tool: JimuReport 1.9.5

- Security framework: Apache Shiro 1.13.0, Jwt 4.5.0

- Microservice technology stack: Spring Cloud Alibaba, Nacos, Gateway, Sentinel, Skywalking

- Database connection pool: Alibaba Druid 1.1.24

- Log printing: logback

- Others: autopoi, fastjson, poi, Swagger-ui, quartz, lombok (simplified code), etc.


#### The front end

- TechnologyStack：`Vue3.0+TypeScript+Vite+AntDesignVue+pinia+echarts`

#### Front-end environment requirements

*    `Node.js 、npm 、pnpm`
*   pnpm `v9+` is now required.
*   Node.js Version suggestion: `v20.15.0`
 ` ( Since Vite6 Node.js 18/20 + is now required )`
 

#### Support library

|  database   |  support   |
| --- | --- |
|   MySQL   |  √   |
|  Oracle11g   |  √   |
|  Sqlserver2017   |  √   |
|   PostgreSQL   |  √   |
|   MariaDB   |  √   |
|   达梦   |  √   |
|   人大金仓   |  √   |
|   TiDB   |  √   |


#### AI Support

| AI Model | Supported |
| --- | --- |
| DeepSeek | √ |
| ChatGPT | √ |
| Qwq | √ |
| 智库 | √ |
| Ollama本地搭建大模型 | √ |
| 等等。。 | √ |


AI Config： https://help.jeecg.com/java/ai/aichat

AI APP: https://help.jeecg.com/aigc


## Microservice solutions

- 1. Service registration and discovery Nacos √
- 2. Nacos √
- 3. Route gateway gateway(Three loading modes) √
- 4. Distributed http feign √
- 5. fuse degrade current limiting Sentinel √
- 6. Distributed files Minio and Alioss √
- 7. Unified permission control
- 8. Service monitoring SpringBootAdmin√
- 9. link tracking Skywalking  [reference document](https://help.jeecg.com/java/springcloud/super/skywarking)
- 10. Messaging middleware RabbitMQ √
- 11. Distributed task xxl-job √
- 12. Distributed Transaction Seata
- 13. Distributed log Loki+grafana
- 14. Support docker-compose, k8s, jenkins
- 15. CAS SSO √
- 16. Route traffic limiting √

   
#### Microservice architecture diagram
![微服务架构图](https://jeecgos.oss-cn-beijing.aliyuncs.com/files/jeecgboot_springcloud2022.png "在这里输入图片标题")

### Jeecg Boot product functionality blueprint
![功能蓝图](https://jeecgos.oss-cn-beijing.aliyuncs.com/upload/test/Jeecg-Boot-lantu202005_1590912449914.jpg "在这里输入图片标题")

### quick start
- Microservice Development：  [Monomer upgrade to microservice](https://help.jeecg.com/java/springcloud/switchcloud/monomer)
- [Docker starts the micro-service background](https://help.jeecg.com/java/docker/springcloud)


### Effect of system

##### ChatGPT AI Dialog
> Go to the JeecgBoot background home page and click "AI Assistant" in the middle of the right side of the home page. The AI Assistant dialog screen is displayed.
![](https://oscimg.oschina.net/oscnet/up-7c6405641a40f56638999d52da0cb5b4343.png)


##### PC
![](https://oscimg.oschina.net/oscnet/up-000530d95df337b43089ac77e562494f454.png)

![输入图片说明](https://static.oschina.net/uploads/img/201904/14155402_AmlV.png "在这里输入图片标题")

![](https://oscimg.oschina.net/oscnet/up-9d6f36f251e71a0b515a01323474b03004c.png)

![输入图片说明](https://static.oschina.net/uploads/img/201904/14160813_KmXS.png "在这里输入图片标题")

![输入图片说明](https://static.oschina.net/uploads/img/201904/14160935_Nibs.png "在这里输入图片标题")

![输入图片说明](https://static.oschina.net/uploads/img/201904/14161004_bxQ4.png "在这里输入图片标题")

#####  interactive
![](https://oscimg.oschina.net/oscnet/up-78b151fc888d4319377bf1cc311fe826871.png)

![](https://oscimg.oschina.net/oscnet/up-16c07e000278329b69b228ae3189814b8e9.png)


##### process Designer
![](https://oscimg.oschina.net/oscnet/up-981ce174e4fbb48c8a2ce4ccfd7372e2994.png)

![输入图片说明](https://static.oschina.net/uploads/img/201907/05165142_yyQ7.png "在这里输入图片标题")

![输入图片说明](https://static.oschina.net/uploads/img/201904/14160917_9Ftz.png "在这里输入图片标题")

![输入图片说明](https://static.oschina.net/uploads/img/201904/14160633_u59G.png "在这里输入图片标题")

##### min process

![](https://oscimg.oschina.net/oscnet/up-1dc0d052149ec675f3e4fad632b82b48add.png)

![](https://oscimg.oschina.net/oscnet/up-de31bc2f9d9b8332c554b0954cc73d79593.png)

![](https://oscimg.oschina.net/oscnet/up-7f83b25159663686d67ed080eb16068c3b4.png)

#####  dashboard Designer


![](https://jeecgos.oss-cn-beijing.aliyuncs.com/files/darg20240726105556.png)

![](https://jeecgos.oss-cn-beijing.aliyuncs.com/files/drag20240724135626.png)

![](https://jeecgos.oss-cn-beijing.aliyuncs.com/files/drag20240724135619.png)

![](https://jeecgos.oss-cn-beijing.aliyuncs.com/files/drag20240724135630.png)

![](https://jeecgos.oss-cn-beijing.aliyuncs.com/files/drag20240726105547.png)

![](https://oscimg.oschina.net/oscnet/up-fad98d42b2cf92f92a903c9cff7579f18ec.png)



##### report Designer
![](https://oscimg.oschina.net/oscnet/up-64648de000851f15f6c7b9573d107ebb5f8.png)

![](https://oscimg.oschina.net/oscnet/up-fa52b44445db281c51d3f267dce7450d21b.gif)

![](https://oscimg.oschina.net/oscnet/up-68a19149d640f1646c8ed89ed4375e3326c.png)

![](https://oscimg.oschina.net/oscnet/up-f7e9cb2e3740f2d19ff63b40ec2dd554f96.png)

##### form Designer
![](https://oscimg.oschina.net/oscnet/up-5f8cb657615714b02190b355e59f60c5937.png)

![](https://oscimg.oschina.net/oscnet/up-d9659b2f324e33218476ec98c9b400e6508.png)

![](https://oscimg.oschina.net/oscnet/up-4868615395272d3206dbb960ade02dbc291.png)

##### bigscreen Designer
![](https://oscimg.oschina.net/oscnet/up-402a6034124474bfef8dfc5b4b2bac1ce5c.png)

![](https://oscimg.oschina.net/oscnet/up-6f7ba2e2ebbeea0d203db8d69fd87644c9f.png)

![](https://oscimg.oschina.net/oscnet/up-ee8d34f318da466b8a6070a6e3111d12ce7.png)

![](https://oscimg.oschina.net/oscnet/up-6b81781b43086819049c4421206810667c5.png)

##### uniapp
![](https://oscimg.oschina.net/oscnet/up-aac943fbd26561879c57a41f7a406edf274.png)

![](https://oscimg.oschina.net/oscnet/up-9a44ba2e82b09c750629d12fafd7f60f553.png)

##### low app
![](https://oscimg.oschina.net/oscnet/up-4be29ae761b2615c8c54b3f668cd8432d9b.png)

![](https://oscimg.oschina.net/oscnet/up-787e76bc24b38ecc7ed19f338808d128255.png)

![](https://oscimg.oschina.net/oscnet/up-99d24a236c483362868523ad0d90f611487.png)

![](https://oscimg.oschina.net/oscnet/up-339a0f29d10449abc7724e3bcda802761c1.png)

![](https://oscimg.oschina.net/oscnet/up-b356670cdc14c609958c7619a537397c4b9.png)

##### app
![](https://oscimg.oschina.net/oscnet/da543c5d0d57baab0cecaa4670c8b68c521.jpg)
![](https://oscimg.oschina.net/oscnet/fda4bd82cab9d682de1c1fbf2060bf14fa6.jpg)

##### PAD
![](https://oscimg.oschina.net/oscnet/e90fef970a8c33790ab03ffd6c4c7cec225.jpg)
![](https://oscimg.oschina.net/oscnet/d78218803a9e856a0aa82b45efc49849a0c.jpg)
![](https://oscimg.oschina.net/oscnet/59c23b230f52384e588ee16309b44fa20de.jpg)


##### chart
![](https://oscimg.oschina.net/oscnet/up-218bc6a1669496b241ebb23506440c0083e.png)

![输入图片说明](https://static.oschina.net/uploads/img/201904/14160834_Lo23.png "在这里输入图片标题")
![输入图片说明](https://static.oschina.net/uploads/img/201904/14160842_QK7B.png "在这里输入图片标题")
![输入图片说明](https://static.oschina.net/uploads/img/201904/14160849_GBm5.png "在这里输入图片标题")
![输入图片说明](https://static.oschina.net/uploads/img/201904/14160858_6RAM.png "在这里输入图片标题")

##### swagger
![输入图片说明](https://static.oschina.net/uploads/img/201908/27095258_M2Xq.png "在这里输入图片标题")
![输入图片说明](https://static.oschina.net/uploads/img/201904/14160957_hN3X.png "在这里输入图片标题")


## donation

If so, buy the author a cup of coffee ☺

![](https://static.oschina.net/uploads/img/201903/08155608_0EFX.png)