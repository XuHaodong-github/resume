## 基本信息
姓名：徐浩东
性别：男
年龄：25
学校：武汉大学
学历：硕士
职业：后端开发工程师
电话：18971823958
邮箱：xuhaodong_work@163.com
博客地址：https://github.com/XuHaodong-github

## 教育背景：
2021.09-2023.06，武汉大学，测绘遥感信息工程国家重点实验室，计算机技术专业，保研
2017.09-2021.06，东北大学，测绘工程


## 工作履历：
2023.08-至今，比亚迪汽车工业有限公司，高级软件开发工程师
工作职责：
- 从事后端开发工作，主要参与公司各项流程线上信息化建设
- 负责需求分析和实施，推动团队技术升级，确保在项目周期内高质量交付完成


## 技术栈：
后端：熟悉Java 8、Java 11，了解Go、Node.js
数据库。熟悉PostgreSQL、了解MySQL、MongoDB
中间件：熟悉RabbitMQ、Redis、MinIO、Activiti，了解ElasticSearch、Debzium
分布式：了解Seata、ZooKeeper
网络。熟悉WebSocket、了解SSE、Nginx、CDN
DevOps：熟悉Git分支管理、K8S、Arthas、了解Jenkins、Docker、Prometheus
前端：了解Javascript、HTML、Vue、Typescript
项目管理：禅道


## 项目经历：

比亚迪集团专利布局奖系统
项目简介：项目有专家打分、场次管理、项目管理
工作内容：
- 负责组织9人团队进行项目开发，涵盖需求分析、原型设计、技术选型、项目开发、测试运维部署等工作全流程
- 使用禅道进行团队项目计划和用户需求反馈管理，减少沟通时间成本，使团队成员能够及时对项目问题进行响应
- 协调部门资源完成技术底座搭建、连通内部文件服务系统、公司人员组织数据同步、OA应用接入、企业微信OAuth登录与内网代理对接等工作
- 针对项目生产环境上线SQL流程混乱，以及特定保密数据查询权限管理不严格问题，引入Alchemy进行生产数据库SQL上线和权限控制，规范了项目信息等保密数据修改和查询流程
- 对于运维部署和测试问题修复通知不及时问题，搭建容器云流水线以及代码仓库合并PR全流程消息通知Webhook机器人，减少了团队成员重复页面操作
- 项目初期需要设计大量数据库表，出现不同成员设计的重复基础字段不统一问题，引入PdManner管理数据库表设计，可以进行字段继承和可视化编辑，简化了数据库表设计操作


比亚迪公益慈善义卖
项目简介：一共多少人使用，每年举行多少次，每次多少人商品
工作内容：
- 进行多实例部署时实例间Websocket消息无法进行共享，使用Redis Pub\Sub解决了多实例间消息不同步问题，横向拓展了服务器负载【提升了几个负载】
- 慈善义卖全流程涉及到商品、订单、出价等多个模块，使用RabbitMQ进行业务解耦，搭建了完善的异步、重试、补偿机制，提高了系统的稳定性和响应速度
- 多实例大量操作日志并发插入出现重复主键，采用Zookeeper调控workerId取值，解决了Mybatis Plus IDWorker多实例部署时有一定概率生成主键重复问题，提高了系统的并发处理能力
- 为了更好的记录用户参与互动情况，设计了用户操作前后端埋点方案，便于运营进行用户活跃度和商品库存情况分析
- 对于进行系统性能优化时调用链路不明确问题，使用SkyWalking配合运维进行压测全链路跟踪，优化了系统接口、数据库、网关等层面性能，提升了系统并发量【多少并发提升了】
- 面对上线初期大量用户同时访问获取图片的场景，使用Nginx配置图片压缩代理，协调企微部门进行流量监控，减少了系统网络带宽占用【多少带宽减少了】
- 义卖活动具有周期性，为了预防流量峰值下可能出现的问题，采用jvm-sandbox进行流量回放演练，减少了用户集中访问时出现的系统异常情况
- 项目初期参与进行了前端技术调研，分析对比了微信小程序和H5页面实现，总结了相关微信小程序申请经验


总裁办信息平台
项目简介：多种业务整合
工作内容：
- 负责完成新闻文稿格式校验功能开发，通过Jsoup解析公司OA系统新闻文稿，月均检测次数1000+，减少了审稿员大量人力重复工作
- 负责完成集团文化电梯广告投放系统开发，其中投放需要上传大体积视频文件，通过前后端沟通对MinIO进行文件分片断点上传，提高了大文件上传稳定性
- 参与解决集团三十周年点赞互动活动，出现大量用户同时访问Redis缓存击穿问题，提高了缓存覆盖率和无用流量对数据库造成的压力【多少百分比，多少用户】
- 参与开发新闻全文搜索功能，其中引入的ElasticSearch 7.6.2版本对于LocalDateTime时间格式保存文档后查询转换出现异常，通过同名Bean覆盖注入方式解决了版本存在的时间格式转换Bug
- 参与解决XXL-JOB定时任务存在多个调度中心实例情况时，定时任务被重复调度问题
- 参与进行礼宾接待业务性能优化，优化了数据库SQL查询效率，减少了服务间重复Feign调用，提高了业务模块访问体验
- 实现自定义Redisson锁、限流等注解，通过spEL表达式、函数式接口，提高了组内相关功能开发效率
- 引入Mybatis Plus代码生成器FastAutoGenerator，提高了组内新项目新模块开发效率


弗迪精工流程中心
项目简介：部门转向无纸化，其中工厂各种流程线上化，需要进行消息通知（用户量，MQ顺序问题
工作内容：
- 负责过大规模消息失败发送恢复机制


## 荣誉奖项：
1、比亚迪信息中心事业部优秀应届生
2、武汉大学硕士研究生入学奖学金