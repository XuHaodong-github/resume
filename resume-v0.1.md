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
2021.09-2023.06，武汉大学，测绘遥感信息工程国家重点实验室，计算机技术专业，保送研究生
2017.09-2021.06，东北大学，测绘工程


## 工作履历：
2023.08-至今，比亚迪汽车工业有限公司，高级软件开发工程师
工作职责：
- 从事后端开发工作，主要参与公司各项流程信息化与线上化建设
- 主导需求分析和实施，推动团队技术升级，确保项目在周期内高质量交付完成


## 技术栈：
后端：熟悉Java 8、Java 11，了解Node.js
数据库。熟悉PostgreSQL、了解MySQL、MongoDB
中间件：熟悉RabbitMQ、Redis、MinIO、Activiti，了解ElasticSearch、Debzium
分布式：了解Seata、ZooKeeper
网络。熟悉WebSocket、SSE、了解Nginx、CDN
DevOps：熟悉Git分支管理、K8S、Arthas、CI\CD、了解Jenkins、Docker、Grafana
前端：了解Javascript、HTML、Vue、Typescript
项目管理：禅道


## 项目经历：

比亚迪集团专利布局奖系统
项目简介：项目有专家打分、场次管理、项目管理
工作内容：
- 负责组织9人团队进行项目开发，涵盖需求分析、原型设计、技术选型、项目开发、测试运维部署等工作全流程
- 协调部门资源完成技术底座搭建、连通内部文件服务系统、公司人员组织数据同步、OA应用接入、企业微信OAuth登录与内网代理对接等工作
- 使用禅道进行团队项目计划和用户需求反馈管理，减少沟通时间成本，使团队成员能够及时对项目问题进行反应
- 针对项目生产环境上线SQL流程混乱，以及特定保密数据查询权限管理不严格问题，引入Alchemy进行生产数据库SQL上线和权限控制，规范了项目信息等保密数据修改和查询流程
- 对于运维部署和测试问题修复通知不及时问题，搭建容器云流水线以及代码仓库合并PR全流程消息通知Webhook机器人，减少了团队成员重复页面操作
- 项目初期需要设计大量数据库表，出现了不同成员设计的重复基础字段不统一问题，引入PdManner管理数据库表设计，使数据库表设计操作简单易行，可以进行继承和可视化编辑


比亚迪公益慈善义卖
项目简介：一共多少人使用，每年举行多少次，每次多少人商品
工作内容：
- 在进行多实例部署时，实例间Websocket消息无法进行共享，使用Redis Pub\Sub解决了多实例间消息不同步问题，增强了项目横向拓展性
- 慈善义卖全流程涉及到商品、订单、出价等多个模块，使用RabbitMQ进行业务解耦，搭建了完善的异步、重试、补偿机制，提高了系统的稳定性和响应速度
- 在进行多实例大量操作日志并发插入时，引入Zookeeper进行调控workerid取值，解决了Mybatis Plus IDWorker雪花算法有一定概率生成主键重复问题，提高了系统的并发处理能力
- 进行了SpringBoot RabbitMQ并发参数调优，断连问题【待优化】
- 为了更好的记录用户参与互动情况，设计了用户操作前后端埋点方案，便于运营进行用户活跃度和商品库存情况分析
- 进行系统性能优化时，使用SkyWalking配合运维进行压测全链路跟踪，优化了系统接口、数据库、网关等层面性能，提升了系统并发量
- 上线初期面对大量用户同时访问获取图片的场景，使用Nginx配置图片压缩代理，协调企微部门进行流量监控，减少了系统网络带宽占用
- 总结了流量回放工具的使用


总裁办信息平台
项目简介：多种业务整合
工作内容：
- 通过Jsoup解析现有OA新闻文稿，负责完成了新闻文稿格式校验接口，月均检测1000+次，减少了审稿员大量人力重复工作
- 参与解决了集团三十周年庆生活动点赞数缓存击穿问题【STAR，事业部人数】
- 解决了ElasticSearch 7.6.2版本LocalDateTime处理Bug
- 集团文化电梯广告系统需要上传大体积视频文件，通过引入MinIO进行文件分片断点上传，提高了上传稳定性，
- 实现了自定义Redisson锁注解，spEL表达式，函数式接口，提高了开发效率
- 引入了mybatis plus代码生成器FastAutoGenerator，提高了小组内项目新模块开发效率
- 解决了XXL-JOB定时任务存在多个调度中心实例时，定时任务被重复调度问题，缺少了一把数据库锁，Redis锁只能排队，不能解决独占问题
- 排查了SpringBoot注解事务和自定义Redisson锁注解同时存在时，事务注解不生效问题
- 分析对比了微信小程序和H5页面，最终确定使用H5页面
- 负责优化礼宾接待系统查询SQL性能


弗迪精工流程中心（用户量，MQ顺序问题
项目简介：部门转向无纸化，其中工厂各种流程线上化，需要进行消息通知
工作内容：
- 
- 负责过大规模消息失败发送恢复机制




## 荣誉奖项：
1、比亚迪信息中心事业部优秀应届生
2、武汉大学硕士研究生入学奖学金





<!-- 渲染版本 -->






慈善义卖
项目描述：负责阿里巴巴集团搜索服务的核心模块开发，迁移主搜Java平台，提高查询速度30%；
个人职责：主导需求分析和实施，推动团队技术升级，确保项目周期内高质量完成。

<!-- 其他 -->
关于事务：
- 本地事务，spring注解
- redis事务，redis操作时判断键是否还在，redis加锁释放锁和设置过期时间
- mq事务，mq解耦的业务，怎么保证消费和发送是一致的



<!-- 参考资料 -->
鱼皮模拟面试
知乎
以前的项目笔记




<!-- 可以补充的 -->
熟悉MS Project项目管理工具的使用
熟悉性能监测工具Granfa的使用、会设置jvm exporter
统计慈善义卖活动的并发量、三十周年活动的并发量
HTTP三次握手四次挥手，和DDOS攻击三种类型的区别
压测英语benchmarking

websocket开发局域网共享剪切板，部署一个demo网站使用【轻松传】

流程中心总共的处理量，看OA待办管理

新闻发布校验接口月均1000次检测，常见的问题【开发的时候接口开关设置、校验逻辑的设计、日志统计、CSS格式文件校验方法】

生产环境脏数据问题的处理和思考

生产环境SQL权限控制平台搭建

token网关鉴权设计，需要每次请求都请求一次鉴权服务吗，第一次请求有token没过期就可以正常用，不用再请求一次鉴权【公司内部系统网关和鉴权的问题以及解决方案，最终的解决结果】
鉴权的system服务总是需要额外获取用户信息，怎么进行设计。只有需要的接口才去查询这些，或者在不能用redis的情况下添加本地缓存，减少HTTP开销，提升系统并发量

流量抓包实践WireShark

30周年缓存击穿问题总结

项目配置过Druid MaxActive参数，并且分析过配置不生效的原因，并深入MSP框架代码找到了没生效的原因【自己定义了扫描路径，和SpringBoot2/1的版本的自动配置扫描顺序也有关系】

慈善义卖流量中最大的问题是图片（解决方法压缩、缓存、Nginx gzip、CDN），三十周年的是图片动效
Nginx gzip主要是压缩静态css html这些文本，不适合压缩图片，不适合压缩变化的JSON请求体
JSON请求体可以后端压缩（哈夫曼压缩），也可以前端压缩(pako.js)


做过国际化，其中对怎么抛出异常，定义异常信息有要求。全局异常捕获GlobalAdvice，以及异常类型定义枚举ResultType（包括异常码和异常信息），


mybatis plus分页插件查询速度慢，自定义COUNT优化


定位线上很卡，日志问题，流程中心，最后通过数据库触发器，依赖另一个字段，发现很多id重复

荣誉奖项，证书

公司内部讲座分享

流程中心工单系统，成本

告警机器人

缓存依赖解决

项目内存溢出，启动过不了健康检查，一直重启问题解决


熟悉spel表达式，实现过spel注解的spring redis注解


了解拦截器的实现，ThreadLocal
了解全局异常的处理


流量回放工具

nacos配置和使用，nacos的实现

了解mybatis plus代码生成器FastAutoGenerator的使用和实现，用于项目提效。了解原理，其中freeMaker的使用，其中consumer函数方法的使用
怎么解决同一个库里不能有同名表的问题，会多次生成相同字段，不同schema里同名表也不行

了解HTTP强制缓存和协商缓存，慈善义卖前端缓存用到了这个技术


关于高并发实现，乐观锁和悲观锁，数据库MVCC


写过自定义注解。校验数字集合是否连续，主要用到了@Constraint(validatedBy = )

SSE和websocket的区别
- SSE原生支持重连，websocket需要另外的组件
- SSE支持的连接数上限，浏览器端限制有6个【需要实践，但是影响不大】
- SSE和websocket都有单服务多实例，怎么共享消息的问题



rabbitmq springboot并发参数调整


----
<!-- 个人信息 -->
博客和github：

2023年比亚迪信息中心优秀应届生



<!-- 技术栈 -->
java，mq
jmeter，mat



<!-- 项目经验 -->
使用了xxx技术，解决了xxx问题，给项目带来xxx收益和性能优化




----
<!-- 慈善义卖 -->
项目时间：2024.05~2024.11
技术栈：Spring Boot、Mybatis Plus、WebSocket、RabbitMQ、Redisson、XXL-JOB、ZooKeeper、Nginx、Spring Cloud GateWay、Spring Feign、SkyWalking、K8S、Swagger、Minio
技术点：多个实例的WebSocket消息同步、消息队列、Nginx网关缓存数据、压测性能调优 
其他：禅道、git



项目基本功能：商品上架、竞拍、结算订单排名、黑名单、买家信息统计、浏览量围观设计
通过企业微信通知
也属于微服务项目架构，有system和msp


项目描述：负责比亚迪集团线上举行义卖活动，将职工以及各种途径收到的爱心物品转化为实际支持，实现了资源高效利用和正能量传播；
个人职责：负责主导需求分析和实施，推动团队技术升级，确保项目周期内高质量完成。
这个项目属于上一个平台的某一个模块



- 优化了mybatis主键生成器，采用了开源的ZooKeeper版本分发实例WorkerId
- 自己设计并发布了一个mybatis基于redis的主键生成器，有开源经验【待定】
- 压测遇到的问题：
    - 主键重复(数据库自己生成id、通过分布式调控中间件Zk解决)
    - 注解事务和注解锁在一起不生效(注解的顺序，导致加锁和事务之间没有完全锁住，等于没有加锁，具体排查的Spring事务源码分析)
    - 接口并发数量低沿着链路排查到网关(直连和经过网关的并发数区别，网关Netty参数调优和思路，先把下游服务打满，然后接收更多请求)【参数详见录屏】
    - 接口查询速度慢（添加缓存项设计，添加分级缓存，以数据库表为维度，以接口为维度、以页为维度）
    - 网络层图片Nginx缓存配置
    - 最高出价排名的redis应用
    - websocket在多个实例时广播消息传达不到，并且有一定随机性。（解决方法：适配器、一致性哈希、黏性连接）（这几种解决方法的区别）
    - 按照skywalking的链路排查，然后调整本服务的druid连接池配置，调整上游服务的netty配置
- 其他问题：
    - XXL-JOB定时任务怎么保证多个调度中心实例，只执行一次
    - MQ消息失败了怎么进行补偿，并且保证不重复消费（订单乐观锁）（基本思路：设置发布确认模式，重试，重试失败加入日志，定时重发，保证幂等）
    - 高可用实践：分级、超时、异步、降级、幂等
    - 用户行为信息怎么统计。使用埋点，前后端埋点的区别和使用场景
    - CDN
    - rabbitMQ时间类序列化
    - 浏览量的设计(用到了定时任务)
    - 结算的设计（用到了定时任务）
    - 涉及到Redis操作时的事务问题【数据库到缓存，缓存到数据库，缓存设计时的注意事项】
    - 【其他人做的部分】30周年点赞活动。统计其中的并发量，学习里面的弹幕和点赞



其他笔记：
- Spring注解有哪几种顺序？
- SocketIO是怎么使用Netty的
- 并发优化思路
- 了解AMQP协议源码
- 结合skywalking分析性能问题，调用链，netty网关，数据库性能排查，配合其他团队
- QPS，单机QPS，峰值QPS
- 分布式锁的实现方式（数据库、redis、本地缓存、zk）
- 分布式id的实现方式（问题来源mybatis自带的idworker多实例还是会重复，几种解决方法）（号段、数据库自增、数据库自增在集群下的问题和解决方法、同理redis自增、uuid、除了雪花的其他开源算法，雪花的原理，最终解决方法）
- 缓存的设计（商品分页、每一页都可以固定，减少缓存，可以放到性能优化里讲）
- 缓存漫谈，除了redis还有其他的系统可以用吗（etcd、dragonfly）（redis的缺点）
- 有过微信小程序开发对接经验（最后没用到是因为小程序不支持大量websocket连接）
- 方案设计、核心开发、项目管理
- websocket功能通信优化（避免广播风暴，根据业务只在满足最高价的条件的情况下广播信息）
- 排查过rabbitmq生产环境断连问题【QueuesNotAvailableException、SimpleRabbitListenerContainerFactory.setMissingQueuesFatal】，具体了解过源码配置，根据错误信息提示排查，配置找不到消费者时怎么处理
- 排查过rabbitmq生产环境重启消费者数量不正确，重启的初期只有一个消费者的问题。【SimpleRabbitListenerContainerFactory.setStartConsumerMinInterval】【spring bean加载顺序】

----





<!-- 总裁办信息平台 -->
项目时间：2024.01~2024.10
技术栈：Spring Boot、Mybatis Plus、Minio、Swagger、ElasticSearch、
技术点：日历类multiplePoints问题、
其他：pdma管理数据库文档

项目参与模块：广告投放、新闻发布、人事档案、生日祝福、财务分析、闭环管理




技术问题：
    - 数据库字段变动日志功能设计。(Spring Event)
    - 为什么多线程执行方法的时候，分布式锁注解会报错ExposeInvocationInterceptor
    - 策略模式的应用。策略模式实现的几种落地方法，函数式接口，spring环境类，最基本的继承类【详见笔记】
    - 单例模式的使用。ObjectMapper
    - MybatisHandler集中自动生成处理公共字段
    - Nacos动态更新配置项
    - Redis分级锁设置，通过接口参数来从锁名层面限制
    - mybatis多数据源配置
    - 自定义注解实现redis缓存，通过SPEL表达式来动态生成注解锁名称，写切面
    - 大文件分片上传、断点续传（MD5一定能保证文件不重复吗，怎么解决）(文件上传服务实现思路)
    - 人员数据同步
    - 动态定时任务实现。自定义实现xxljob调用api，动态生成定时任务
    - 解决了Feign调用接口提示"incomplete output stream executing"和"too many bytes written executing Post"问题（引入Feign包解决的，原理是缺少包之后默认调用的JDK网络通信，默认的sun包为什么会报错；Feign本身调用也有大小限制，要取消Content-Length，这个好像是Spring Clould的bug）

其他亮点：
    - 和其他部门进行合作，其中一个模块孵化成了一个科室的平台，生产数据对接流程
    - 服务拆分重构。将文件、定时任务、消息模块进行拆分
    - 解决了循环依赖问题
    - 数据权限模型，角色模型，RBAC
    - 表单数据分级校验（Validated参数使用）
    - 邮件、企微消息接口对接
    - 排查了ES某个版本时间类序列化的问题（7.6.2， bug）
    - HeaderInterceptor拦截器鉴权和放行、SecurityContextHolder
    - 网关配置外部系统接口白名单，和OA对接
    - 能够对新闻格式进行校验，Jsoup文档格式校验分析(字体，字号，缩进，图片居中方式，行距)
    - Java8大量Stream流使用、Optional
    - Spring Retry实现接口重试
    - 新闻稿定时自动保存功能实现（Redis缓存）
    - FlowAble流程历史对接
    - mybatis typeHandler使用
    - mybatis MetaInfoHandler使用
    - 使用Redis时注意了缓存击穿、双写、一致性问题（双写只是一种方法，可以在更新数据库之前，之后，还可以异步）
    - 关于RestTemplate、OkHttp，以及Spring 6升级的RestClient
    - 涉及到redis的操作，怎么加锁【给redis代码段整个加一个redis锁，防止之前判断没有的锁突然出现，或者之前判断有的锁突然没有了】
    - 数据库 Large IN 问题解决【拆分in，原理是什么】
    - 解决过缓存击穿的问题

关于缓存击穿：
- 缓存击穿怎么发生的。
  - 很多人都来查，但是之前缓存里并没有。
  - 这样就成了缓存的一种漏洞，有缓存但是还是没有挡住大量请求一瞬间到数据库，没有起到缓冲的作用
- 缓存击穿的解决方案。
  - 学生方案，布隆过滤器（像助力值这种敏感信息，用布隆是可以的。但是布隆会有误判），缓存预热（对于大量的key来说，预热不一定是最好的，而且有些key不一定会用到）
  - 业务方案，流量上分流（比如一个公司80w人，分事业部推送，相当于提前减少流量），设置缓存过期时间大于活动结束时间，第一次请求进来没拿到key就返回0，点击助力之后刷新缓存值，这样就有key了，然后查询值就等于实际值。（还可以然后记录key->6627231,value->null，再次查询发现=null，就请求数据库；规避缓存失效的时候，进来第一次第二次第三次查询数据都不正确的问题，可以让除了第一次以外的查询数据都准确【资源和技术有限的情况下】
  - 综合方案。限流降级熔断，前后端cookie配合；系统的看，这个问题的解决方法不只是后端，可以把这个助力值写到前端缓存里，后端请求都不用了。然后把是否点过助力的状态放到cookie里，判断是否要在缓存过期的时候重新拿一遍数据
- 对布隆过滤器的理解
  - 布隆过滤器不适用于会删除数据的情况，也就是假阳性
  - 但是用户作为id这种，用户一般不会被删除，所以比较适用
- 穿透、击穿、雪崩的区别
  - 穿透，一个key在数据库中并不存在
  - 击穿，一个key在数据库中存在
  - 雪崩，多个key在数据库中存在，过期了


其他：
- 会使用WireShark抓包工具分析。IO broken pipe问题，rabbitmq exceptionhandler执行过程
- 会使用pdmanner管理数据库开发
- 会使用sourceTree
- 会搭建git flow工作流，对分支代码管理有心得（前后端不分离，前后端分离，dev/UAT/PROD，加上二主三辅）（了解版本发布号设计）
- 项目中还用到了弹幕系统设计，分成推和拉两种方式
- 项目中还用到了Seata，分布式事务应用场景，几种机制的区别和使用，内部系统适合用AT模式
- 会使用Swggger管理文档，最开始是手写
- 文件服务的设计(DFS、后端服务分离，上传、缓存、minio存储、同名服务、图片视频处理、预览、鉴权)
- Spring retry使用（对接外部接口）
- 有过企业微信的对接开发经验
- 操作日志设计、字段变更日志功能设计（Spring Event）




<!-- 弗迪精工、新材料、基础院流程中心 -->
项目时间：2023.10~2024.06
消息队列怎么保证消息的顺序性
- 最终一致性。只需要看是否发过待办了，如果发过就不处理
- 严格一致性。可以通过查询上一个审批节点是否处理完了，没处理完就重回队列

顺序性的实现方式
- 发送端保证。发送的时候插入到表里
- 消费者保证。消费者消费的时候进行校验，比如时间戳判断

消息补偿机制：
- 哪些地方可能会出现失败
  - 发送失败。比如说网络原因，发送到消息队列前就失败了，或者mq挂了；或者发送到的队列不正确
  - 消费失败。比如说消费者调用外部接口，OA或者企微，OA企微的接口掉不通，或者调用时参数出了问题。
- 补偿机制
  - 发送失败。【本地消息表】
  - 消费失败。【消费异常补偿表】
  - 人工补偿接口

- 会使用MongoDB基本使用

其他：
- activiti工作流、flowable工作流、BPMN流程规范
- 单点登录
- k8s
- k8s滚动更新，停止更新流程
- 外部服务接口调用
- 排查过TCP的 IO异常分析\Broken Pipe问题
- 项目打包流程，Jenkins
- 数据库触发器、存储过程
- QPS、单机QPS、峰值QPS
- 接口ip调用、k8s服务名调用区别、公网域名调用
- excel导出，异步，大数据量导出，数据库CDC，读写分离
- 浅谈一下低代码前后端设计
- 数据库触发器使用（pgsql，存储过程，解决了主键重复问题，原主键是MD5）
