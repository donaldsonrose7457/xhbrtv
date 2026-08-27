最新前沿技术资讯

一、入门教程｜Getting Started
原标题：Hands‑on：简易连接池原型实现理解原理
简介：golang os.Exit 退出程序注意 defer 不执行，os.Exit 会直接退出，不会执行 defer，优雅退出不要直接 os.Exit。
 | 原文链接：http://book.excerw.asia/blog/3768537.sHtMl

原标题：Architecture：事件溯源架构模式适用业务场景
简介：golang proto 可选字段处理方案，protobuf 可选字段正确判断，区分未赋值与零值，业务逻辑不出现偏差。
 | 原文链接：http://book.excerw.asia/blog/6336553.sHtMl

原标题：golang 系统设计监控告警体系搭建思路
简介：批量操作分批处理防止 OOM，大批量数据处理不一次性加载全部数据，分批循环处理，避免内存溢出。
 | 原文链接：http://book.excerw.asia/blog/6383292.sHtMl

原标题：开源实践：开源Issue沟通技巧如何有效提Bug
简介：golang word 文档生成处理 go 方案，go 生成 word 文档报表，填充文本表格，输出 docx 文件。
 | 原文链接：http://book.excerw.asia/blog/3235536.sHtMl

原标题：项目实践：Docker镜像安全扫描本地实操
简介：golang trace 工具采集 go 程序执行轨迹，go trace 采集程序完整调度轨迹，分析协程调度阻塞问题。
 | 原文链接：http://book.excerw.asia/blog/6104023.sHtMl

原标题：Practice：实现多数据源动态切换组件实践
简介：golang go 无锁并发编程技巧，原子操作 sync/atomic，简单场景替换锁，提升并发性能。
 | 原文链接：http://book.excerw.asia/blog/8857932.sHtMl

原标题：设计思考：API网关和BFF职责边界划分
简介：golang fasthttp 服务开发完整示例，fasthttp 搭建 http 服务，路由、参数读取、响应返回完整业务。
 | 原文链接：http://book.excerw.asia/blog/2470026.sHtMl

原标题：开源实践：Fork上游项目，持续同步更新代码
简介：系统时间同步定时任务偏移，同步服务器系统时间，防止时间偏移，避免定时任务执行时间错乱。
 | 原文链接：http://book.excerw.asia/blog/9774253.sHtMl

原标题：正则表达式优化 CPU 占满问题
简介：golang time 时间比较 Before After Equal，时间比较不要直接减，使用内置方法判断时间先后。
 | 原文链接：http://book.excerw.asia/blog/0286574.sHtMl

原标题：数据库连接及时关闭连接泄漏
简介：golang go 符号表与调试信息取舍，区分生产环境调试符号取舍，平衡镜像体积与故障排查能力。
 | 原文链接：http://book.excerw.asia/blog/5675162.sHtMl

原标题：golang mysql 分表 id 路由逻辑
简介：配置外部化线上部署防错误，把配置从代码剥离，外部传入配置，修改配置不需要重新打包构建。
 | 原文链接：http://book.excerw.asia/blog/2653866.sHtMl

原标题：代码模块化组件化拆分思路
简介：前端 pdf 预览渲染方案对比，对比前端 PDF 预览库，分析性能、兼容性，给出业务选型参考。
 | 原文链接：http://book.excerw.asia/blog/2525748.sHtMl

原标题：零基础理解HTTP常用请求头与状态码
简介：golang net.Listener 包装自定义监听器，包装 Listener 做连接计数、连接拦截，扩展网络能力。
 | 原文链接：http://book.excerw.asia/blog/3159937.sHtMl

原标题：golang k8s liveness readiness 探针
简介：端口占用访问失败排查方案，讲解端口占用排查命令，定位占用进程，释放端口，解决服务启动端口被占用报错。
 | 原文链接：http://book.excerw.asia/blog/1500642.sHtMl

原标题：部署实践：容器时区统一配置解决方案
简介：系统文件描述符上限调大，调高操作系统文件描述符上限，解决高并发场景打开文件报错。
 | 原文链接：http://book.excerw.asia/blog/5329592.sHtMl

原标题：gitignore 文件编写过滤规则
简介：磁盘 inode 耗尽文件创建失败，排查磁盘 inode 占用，清理大量小文件，恢复文件创建能力。
 | 原文链接：http://book.excerw.asia/blog/9980836.sHtMl

原标题：Hands‑on：简易短链接服务完整开发实践
简介：golang http client 全局变量复用，http Client 不要每次请求新建，复用 Transport 提升性能。
 | 原文链接：http://book.excerw.asia/blog/3312947.sHtMl

原标题：效率笔记：VSCode插件集合后端前端开发效率
简介：golang gorm 预加载关联查询优化，GORM 预加载关联数据，避免 N+1 查询问题，提升数据库查询性能。
 | 原文链接：http://book.excerw.asia/blog/3356268.sHtMl

原标题：实战项目：CLI批量文件处理工具开发全过程
简介：golang wasm 浏览器 js 交互，go wasm 与 js 互相调用，浏览器端 go 程序操作 dom 调用 js 函数。
 | 原文链接：http://book.excerw.asia/blog/0682822.sHtMl

原标题：新手快速上手 Git 版本控制实操指南
简介：golang http cookie jar 会话处理，客户端 cookie jar 自动管理 cookie，处理登录态会话。
 | 原文链接：http://book.excerw.asia/blog/3340455.sHtMl

原标题：golang 分布式 ID 雪花算法实现
简介：磁盘占满服务不可用清理方案，定位磁盘占用大文件，清理日志、缓存文件，恢复磁盘可用空间。
 | 原文链接：http://book.excerw.asia/blog/6353079.sHtMl

原标题：Architecture：事件溯源架构模式适用业务场景
简介：golang rsa 签名验签 pem 证书加载，加载 pem 格式密钥证书，rsa 签名与验签完整业务实现。
 | 原文链接：http://book.excerw.asia/blog/5530091.sHtMl

原标题：golang 系统设计分布式锁红锁优缺点梳理
简介：服务熔断防止故障级联传播，实现服务熔断逻辑，下游故障时快速失败，阻止故障向上游链式扩散。
 | 原文链接：http://book.excerw.asia/blog/1846380.sHtMl

原标题：golang 多协程任务池并发控制
简介：golang runtime.Gosched 主动让出调度，长计算循环主动 Gosched，让出调度权，防止其他协程饥饿。
 | 原文链接：http://book.excerw.asia/blog/5005804.sHtMl

原标题：排错：CI流水线构建失败，日志无明确报错
简介：Git 标签版本标记发布管理，使用 Git 标签标记项目版本，打标签推送远程，用于版本发布、版本回溯。
 | 原文链接：http://book.excerw.asia/blog/9711070.sHtMl

原标题：Debug：分布式会话时钟不同步令牌提前失效
简介：Redis 内存淘汰策略数据防丢失，合理配置 Redis 内存淘汰策略，防止内存满后误删除业务重要数据。
 | 原文链接：http://book.excerw.asia/blog/9991135.sHtMl

原标题：golang 系统设计 csrf 接口防护实现
简介：nodejs 跨域中间件配置细节，Express 跨域中间件配置细节，处理预检请求，修复偶现跨域失效。
 | 原文链接：http://book.excerw.asia/blog/7109547.sHtMl

原标题：架构复盘：多级缓存架构，本地缓存+分布式缓存
简介：golang 表格驱动测试完整示例，表格驱动多组输入输出，批量执行测试用例，减少重复代码。
 | 原文链接：http://book.excerw.asia/blog/6671668.sHtMl

原标题：快速入门ORM，实现简单数据库增删改查
简介：Git 代码冲突正确处理方式，讲解冲突产生场景，演示冲突文件修改，正确合并代码，防止代码丢失。
 | 原文链接：http://book.excerw.asia/blog/7999277.sHtMl

原标题：golang 系统设计本地缓存与分布式缓存
简介：读懂开源项目 README 实用技巧，教你快速解析开源项目说明文档，提取安装、运行、配置关键信息，快速上手项目。
 | 原文链接：http://book.excerw.asia/blog/8919755.sHtMl

原标题：Practice：实现简单信号处理优雅停机实践
简介：golang rabbitmq go 客户端生产消费，streadway/amqp 实现 rabbitmq 生产者消费者，队列交换机绑定。
 | 原文链接：http://book.excerw.asia/blog/6772137.sHtMl

原标题：golang 系统设计批量处理优化业务性能
简介：golang grafana 面板 go 业务指标可视化，prometheus 指标对接 grafana，配置监控面板可视化业务状态。
 | 原文链接：http://book.excerw.asia/blog/6470993.sHtMl

原标题：golang 项目 makefile 脚本编写
简介：百万数据 Excel 导出内存优化，优化大 Excel 导出逻辑，流式输出，避免一次性加载全部数据造成 OOM。
 | 原文链接：http://book.excerw.asia/blog/3056954.sHtMl

原标题：golang 系统设计 k8s 集群安全配置梳理
简介：服务健康检查告警监控体系，搭建健康检查加告警体系，服务异常及时推送告警通知运维人员。
 | 原文链接：http://book.excerw.asia/blog/8389441.sHtMl

原标题：实战：Docker资源监控查看容器状态实操
简介：golang runtime.Gosched 主动让出调度，长计算循环主动 Gosched，让出调度权，防止其他协程饥饿。
 | 原文链接：http://book.excerw.asia/blog/6191656.sHtMl

原标题：零基础理解前后端简单交互流程
简介：golang go 测试文件命名规范，_test.go 测试文件，TestXxx 单元测试函数命名规范。
 | 原文链接：http://book.excerw.asia/blog/1180618.sHtMl

原标题：方案对比：轮询长轮询WebSocket推送架构选型
简介：golang 后端节点健康检查机制实现，定时探测后端节点状态，自动剔除故障节点，保障转发可用。
 | 原文链接：http://book.excerw.asia/blog/4003281.sHtMl

原标题：零基础学习简单正则表达式实战案例
简介：golang 系统信号信号量处理，Go 处理系统各类信号，SIGINT、SIGTERM，实现程序可控退出。
 | 原文链接：http://book.excerw.asia/blog/0704844.sHtMl

原标题：golang k8s rbac 权限控制配置示例
简介：golang redis 客户端业务使用，Go Redis 客户端对接，实现缓存、计数器，适配各类 Redis 业务场景。
 | 原文链接：http://book.excerw.asia/blog/9089682.sHtMl

原标题：golang 系统设计本地缓存 redis 缓存多级组合
简介：golang 制品镜像版本号规范管理，镜像版本号结合 git commit，明确每个镜像对应代码版本便于追溯。
 | 原文链接：http://book.excerw.asia/blog/1903459.sHtMl


二、踩坑排错｜Troubleshooting
原标题：Hands‑on：简易速率限制中间件完整实现
简介：接口签名验签完整安全方案，一套完整接口签名方案，包含签名生成、请求携带、服务端验签校验。
 | 原文链接：http://book.excerw.asia/blog/8849844.sHtMl

原标题：Hands‑on：简易配置中心本地原型实现
简介：内网测试服务搭建团队调试，配置本地服务内网可访问，团队成员能够访问调试，方便前后端联调与内部演示。
 | 原文链接：http://book.excerw.asia/blog/3332572.sHtMl

原标题：Practice：模拟磁盘满，验证服务降级表现
简介：golang 字符编码转换 go 处理，iconv‑go 做编码转换 gbk utf8 互转，处理老旧系统 gbk 编码数据。
 | 原文链接：http://book.excerw.asia/blog/4511974.sHtMl

原标题：golang 系统设计消息 key 选择保证顺序性方案
简介：批量数据处理脚本编写技巧，编写脚本批量处理大量业务数据，循环处理、分批执行，提升数据处理效率。
 | 原文链接：http://book.excerw.asia/blog/5756109.sHtMl

原标题：实践：消息队列死信处理业务落地实践
简介：Docker 容器网络不通排查，排查容器网络模式、端口映射、防火墙，解决容器之间、容器外部网络不通。
 | 原文链接：http://book.excerw.asia/blog/9136367.sHtMl

原标题：golang 系统设计缓存更新策略 cache aside 讲解
简介：极简 API 网关路由转发实现，开发极简网关服务，完成请求路由转发，理解网关基础实现原理。
 | 原文链接：http://book.excerw.asia/blog/5842731.sHtMl

原标题：实战：Nginx实现文件限速下载配置实践
简介：golang net.Conn 包装自定义连接，包装 net.Conn，统计读写字节，日志打印，超时控制。
 | 原文链接：http://book.excerw.asia/blog/0990745.sHtMl

原标题：业务幂等键设计防重复逻辑
简介：golang proto 可选字段处理方案，protobuf 可选字段正确判断，区分未赋值与零值，业务逻辑不出现偏差。
 | 原文链接：http://book.excerw.asia/blog/3594930.sHtMl

原标题：项目实践：多环境配置管理组件设计与实现
简介：golang 限流熔断放在代理层实践，代理层统一限流熔断，对后端服务做流量保护。
 | 原文链接：http://book.excerw.asia/blog/6107400.sHtMl

原标题：golang k8s liveness readiness 探针
简介：golang 数据库连接耗尽排查思路，监控连接池状态，定位连接未归还，解决连接耗尽报错。
 | 原文链接：http://book.excerw.asia/blog/4797544.sHtMl

原标题：golang 系统设计延迟队列业务实现
简介：golang go 项目 CI github actions 配置，github actions 实现 go 项目 ci，自动测试、代码检查、编译打包镜像。
 | 原文链接：http://book.excerw.asia/blog/4279027.sHtMl

原标题：golang 项目 makefile 脚本编写
简介：定时任务周期调度 demo 开发，实现简单定时调度程序，按时间周期执行业务逻辑，理解定时任务运行机制。
 | 原文链接：http://book.excerw.asia/blog/1970856.sHtMl

原标题：golang 系统设计 docker compose 本地开发环境搭建
简介：golang go 包循环导入报错解决，A 导入 B B 导入 A，循环导入报错，重构代码拆分包消除循环依赖。
 | 原文链接：http://book.excerw.asia/blog/6346167.sHtMl

原标题：git stash 代码暂存切换分支
简介：golang 信号捕获程序退出处理，Go 捕获操作系统信号，做资源回收，控制程序退出流程。
 | 原文链接：http://book.excerw.asia/blog/0545753.sHtMl

原标题：Debug：消息队列死信队列堆积无人处理业务阻塞
简介：golang go sum 校验失败处理方案，go sum 校验不匹配，排查网络代理，清理缓存解决校验报错。
 | 原文链接：http://book.excerw.asia/blog/7162479.sHtMl

原标题：golang 系统设计秒杀防超卖方案
简介：golang GC 调优 GOGC 参数调整，调整 GOGC 阈值，控制 GC 触发时机，权衡内存占用与 CPU 开销。
 | 原文链接：http://book.excerw.asia/blog/2839911.sHtMl

原标题：坑点：gitpull冲突处理不当造成代码丢失
简介：golang go 程序版本号内置编译注入，编译时注入 git commit 版本号，程序运行输出版本便于排查。
 | 原文链接：http://book.excerw.asia/blog/8766626.sHtMl

原标题：新手指南：如何读懂开源项目报错日志
简介：golang kitex 超时重试熔断配置，kitex 配置调用超时、重试、熔断策略，保障微服务调用稳定性。
 | 原文链接：http://book.excerw.asia/blog/5029463.sHtMl

原标题：Troubleshoot：磁盘inode耗尽，无法新建文件
简介：本地简易配置中心动态管理，搭建轻量本地配置中心，业务动态读取配置，修改配置不重启服务。
 | 原文链接：http://book.excerw.asia/blog/8394629.sHtMl

原标题：开发记录：业务错误告警邮件通知组件实践
简介：golang e2e 端到端测试 go 接口，编写 e2e 测试，完整模拟用户请求，校验整套业务链路正确性。
 | 原文链接：http://book.excerw.asia/blog/9492658.sHtMl

原标题：消息队列生产消费模型入门
简介：golang k8s secret 敏感配置加载，加载 k8s secret 存储密钥密码，敏感信息不存放配置文件。
 | 原文链接：http://book.excerw.asia/blog/2737098.sHtMl

原标题：golang websocket 服务端开发
简介：JWT 令牌过期异常处理，捕获 JWT 过期、篡改异常，编写业务处理逻辑，引导用户重新获取令牌。
 | 原文链接：http://book.excerw.asia/blog/3161523.sHtMl

原标题：开发环境变量配置全平台教程
简介：golang rabbitmq 死信队列延迟消息，rabbitmq 实现死信、延迟消息，处理延时业务场景。
 | 原文链接：http://book.excerw.asia/blog/6356538.sHtMl

原标题：实战：GraphQL服务搭建与CRUD实操
简介：golang go1.18 + 泛型基础实操，go 泛型基础语法，泛型函数泛型类型，实现通用工具函数。
 | 原文链接：http://book.excerw.asia/blog/8585054.sHtMl

原标题：开发复盘：数据库批量更新优化性能实践
简介：内存广播本地进程消息通知，实现进程内内存消息广播，进程内部模块之间事件通知解耦。
 | 原文链接：http://book.excerw.asia/blog/2572059.sHtMl

原标题：golang 系统设计 changelog 变更日志维护
简介：golang rabbitmq go 客户端生产消费，streadway/amqp 实现 rabbitmq 生产者消费者，队列交换机绑定。
 | 原文链接：http://book.excerw.asia/blog/9039271.sHtMl

原标题：Docker 容器入门镜像实操教程
简介：短信服务封装失败自动重试，封装短信发送组件，处理发送失败自动重试，兼容多短信服务商。
 | 原文链接：http://book.excerw.asia/blog/2679477.sHtMl

原标题：入门实践：简单图片上传预览本地demo
简介：正则表达式文本处理实战案例，结合业务场景演示正则匹配、提取、替换，处理手机号、邮箱等各类文本校验需求。
 | 原文链接：http://book.excerw.asia/blog/1301837.sHtMl

原标题：HelloGitHubPages：部署你的第一个静态博客
简介：hosts 配置本地回环访问修复，修改 hosts 配置，修复 127.0.0.1 解析异常，本地服务访问失败问题。
 | 原文链接：http://book.excerw.asia/blog/4102681.sHtMl

原标题：golang 系统设计告警风暴抑制方案实现
简介：图片上传预览格式大小处理，实现图片上传接口，校验文件格式、大小，完成上传后预览处理。
 | 原文链接：http://book.excerw.asia/blog/2627493.sHtMl

原标题：golang 开发环境快速搭建指南
简介：golang 处理连接被重置 reset 错误，识别 connection reset by peer，对端关闭连接异常处理逻辑。
 | 原文链接：http://book.excerw.asia/blog/0793082.sHtMl

原标题：Practice：实现业务唯一流水号生成组件实践
简介：CI 构建缓存加速编译速度，开启 CI 流水线依赖缓存，复用上一次构建依赖包，缩短流水线构建耗时。
 | 原文链接：http://book.excerw.asia/blog/1561570.sHtMl

原标题：Docker 多阶段构建镜像瘦身
简介：golang go 整洁架构代码组织实践，整洁架构依赖向内，解耦业务逻辑与外部基础设施。
 | 原文链接：http://book.excerw.asia/blog/7422420.sHtMl

原标题：实战项目：WSL开发环境完整配置实操
简介：Git LFS 大文件推送失败解决，配置 Git LFS，处理仓库大文件，解决大文件推送报错推送失败。
 | 原文链接：http://book.excerw.asia/blog/9432435.sHtMl

原标题：golang 系统设计布隆过滤器拦截不存在 key
简介：服务熔断防止故障级联传播，实现服务熔断逻辑，下游故障时快速失败，阻止故障向上游链式扩散。
 | 原文链接：http://book.excerw.asia/blog/0590538.sHtMl

原标题：调优方案：前端静态资源打包性能体积优化
简介：golang 单例模式实现几种方式，Go 单例模式多种实现对比，sync.Once 等方式，实现全局唯一实例。
 | 原文链接：http://book.excerw.asia/blog/1281110.sHtMl

原标题：golang 互斥锁读写锁并发安全
简介：nodejs 多进程任务分发处理，多进程拆分处理 CPU 密集任务，主进程分发任务，利用多核提升处理速度。
 | 原文链接：http://book.excerw.asia/blog/3589248.sHtMl

原标题：golang consul 服务发现简单示例
简介：golang validator 自定义校验规则，Gin Validator 自定义校验器，实现业务特殊参数校验逻辑。
 | 原文链接：http://book.excerw.asia/blog/3233775.sHtMl

原标题：开发记录：搭建CI/CD流水线自动构建部署项目
简介：golang netlink 系统信息获取，netlink 获取系统网络信息，网卡地址，内核网络状态读取。
 | 原文链接：http://book.excerw.asia/blog/7803571.sHtMl

原标题：前端 pdf 预览渲染方案对比
简介：golang sync.Once 只执行一次，sync.Once 做单例初始化，保证代码只执行一次，并发安全。
 | 原文链接：http://book.excerw.asia/blog/8455644.sHtMl

三、实战开发｜Practice
原标题：golang 系统设计本地缓存过期淘汰策略选型
简介：golang 错误静默忽略风险规避，禁止空忽略错误，必须处理或者明确注释为什么忽略错误。
 | 原文链接：http://book.excerw.asia/blog/8652281.sHtMl

原标题：安全笔记：GitHubAction密钥安全管理
简介：golang bytes.Buffer 字节缓冲区使用，bytes.Buffer 字节内存缓冲区，拼接字节，避免频繁内存分配。
 | 原文链接：http://book.excerw.asia/blog/2170026.sHtMl

原标题：nestjs 框架模块化项目搭建
简介：golang grpc 重试机制客户端配置，grpc 客户端配置重试策略，临时故障自动重试，提升调用稳定性。
 | 原文链接：http://book.excerw.asia/blog/7705585.sHtMl

原标题：Redis 内存淘汰策略数据防丢失
简介：golang go sum 校验失败处理方案，go sum 校验不匹配，排查网络代理，清理缓存解决校验报错。
 | 原文链接：http://book.excerw.asia/blog/6240502.sHtMl

原标题：Redis 热点 key 拆分降低集群压力
简介：golang os 进程 pid 获取父进程 pid，os.Getpid 获取进程 id，获取父进程 pid，进程间识别。
 | 原文链接：http://book.excerw.asia/blog/7586385.sHtMl

原标题：踩坑：对象未释放，长时间运行内存持续上涨
简介：golang go 模板执行错误捕获，捕获模板执行错误，防止模板错误直接返回空白页面。
 | 原文链接：http://book.excerw.asia/blog/2781715.sHtMl

原标题：golang 系统设计网关鉴权鉴权转发流程讲解
简介：nestjs 框架模块化项目搭建，从零搭建 NestJS 项目，模块化拆分业务，搭建规范后端项目骨架。
 | 原文链接：http://book.excerw.asia/blog/0100832.sHtMl

原标题：golang 系统设计 saga 事务补偿模式实现思路
简介：nodejs 内存溢出问题排查修复，Node.js 程序 OOM 排查流程，定位内存泄露，调整内存限制修复崩溃。
 | 原文链接：http://book.excerw.asia/blog/5646338.sHtMl

原标题：数据库连接及时关闭连接泄漏
简介：代理 HTTPS 证书访问异常处理，配置代理根证书，解决代理环境 HTTPS 证书校验失败无法访问外网。
 | 原文链接：http://book.excerw.asia/blog/2955532.sHtMl

原标题：golang redis 锁超时业务处理
简介：缓存过期打散防止缓存雪崩，对缓存过期时间增加随机偏移，避免大量缓存同时失效引发缓存雪崩。
 | 原文链接：http://book.excerw.asia/blog/3297788.sHtMl

原标题：Docker Compose 一键搭建本地栈
简介：特殊输入字符过滤解析防护，过滤用户输入特殊字符，防止解析报错，规避恶意字符带来业务异常。
 | 原文链接：http://book.excerw.asia/blog/5370159.sHtMl

原标题：Git 标签版本标记发布管理
简介：Git 代码冲突正确处理方式，讲解冲突产生场景，演示冲突文件修改，正确合并代码，防止代码丢失。
 | 原文链接：http://book.excerw.asia/blog/2186485.sHtMl

原标题：实战项目：多实例部署会话一致性验证实践
简介：golang go 优雅处理信号丢失场景，处理信号丢失、信号被忽略，保障程序可以正常接收终止信号。
 | 原文链接：http://book.excerw.asia/blog/7024900.sHtMl

原标题：安全实践：备份文件访问权限安全管控
简介：golang pdf 生成 go 服务端生成 pdf，服务端动态生成 pdf 报表文件，直接输出下载给到前端。
 | 原文链接：http://book.excerw.asia/blog/1403283.sHtMl

原标题：golang 系统设计第三方接口调用封装思路
简介：golang go 并发模式 or‑channel 信号合并，合并多个 done 信号，任意一个完成触发退出逻辑。
 | 原文链接：http://book.excerw.asia/blog/9703654.sHtMl

原标题：golang 系统设计 git 工作流本地开发提交流程
简介：数值 key 浮点匹配异常规避，避免浮点数作为 Redis 等存储的 key，防止精度问题引发 key 匹配失败。
 | 原文链接：http://book.excerw.asia/blog/8769173.sHtMl

原标题：nodejs jwt 登录鉴权完整示例
简介：业务接口幂等完整落地案例，完整业务场景幂等落地示例，覆盖表单提交、回调、重试各类场景。
 | 原文链接：http://book.excerw.asia/blog/7985248.sHtMl

原标题：前端下载导出文件功能实现
简介：golang 分布式锁 redis 实现，基于 Redis 实现 Go 分布式锁，解决多实例并发竞争资源问题。
 | 原文链接：http://book.excerw.asia/blog/3231108.sHtMl

原标题：golang ci 流水线漏洞扫描依赖检查
简介：golang gin 路由动态注册实现方案，根据配置动态注册接口路由，无需硬编码路由，适配动态业务模块。
 | 原文链接：http://book.excerw.asia/blog/6456142.sHtMl

原标题：Security：接口鉴权越权漏洞检测与修复
简介：golang https 客户端跳过证书校验，开发测试环境跳过 tls 证书校验，仅用于内网测试禁止生产使用。
 | 原文链接：http://book.excerw.asia/blog/5104034.sHtMl

原标题：实践：分布式事务本地模拟验证实践
简介：容器软链接文件权限修复，修复容器内软链接文件权限，让程序能够正常读取软链接指向的文件。
 | 原文链接：http://book.excerw.asia/blog/4570056.sHtMl

原标题：golang 系统设计混沌测试简单场景模拟实现
简介：golang 数据库连接耗尽排查思路，监控连接池状态，定位连接未归还，解决连接耗尽报错。
 | 原文链接：http://book.excerw.asia/blog/4623296.sHtMl

原标题：golang es bool 查询条件组合技巧
简介：简易网关请求路由过滤模拟，模拟网关基础能力，实现请求路由转发、简单过滤，理解网关核心工作逻辑。
 | 原文链接：http://book.excerw.asia/blog/0934741.sHtMl

原标题：SDK 版本兼容线上崩溃修复
简介：golang race 检测器性能开销，race 检测器有性能损耗，只用于测试环境，禁止生产开启 race。
 | 原文链接：http://book.excerw.asia/blog/0913023.sHtMl

原标题：golang 系统设计日志脱敏敏感字段过滤处理
简介：golang grpc 双向流双向通信开发，grpc 双向流，服务端客户端持续互发消息，长连接流式业务场景。
 | 原文链接：http://book.excerw.asia/blog/0445744.sHtMl

原标题：Architecture：安全防护架构XSSCSRFSQL注入防御
简介：golang sync.Pool 对象池复用对象，sync.Pool 复用临时对象，减少内存分配，降低 GC 频率提升性能。
 | 原文链接：http://book.excerw.asia/blog/2423929.sHtMl

原标题：Nginx 丢失请求头配置修正
简介：轻量 API 后端接口服务快速开发，快速搭建简易 API 服务，实现基础接口能力，快速支撑小型业务需求。
 | 原文链接：http://book.excerw.asia/blog/7640228.sHtMl

原标题：CI 构建缓存加速编译速度
简介：CI 构建缓存加速编译速度，开启 CI 流水线依赖缓存，复用上一次构建依赖包，缩短流水线构建耗时。
 | 原文链接：http://book.excerw.asia/blog/6431970.sHtMl

原标题：Docker 网络模式容器互通设置
简介：golang redis 事务 multi exec 使用，Redis 事务 multi exec 实现批量命令原子执行，理解 redis 事务隔离特性。
 | 原文链接：http://book.excerw.asia/blog/9018126.sHtMl

原标题：项目依赖安全扫描漏洞防范
简介：Nginx 静态代理负载均衡全套配置，一套 Nginx 配置示例，覆盖静态资源、反向代理、负载均衡场景。
 | 原文链接：http://book.excerw.asia/blog/6990312.sHtMl

原标题：golang 系统设计 ci 流水线安全管控思路
简介：golang rabbitmq go 客户端生产消费，streadway/amqp 实现 rabbitmq 生产者消费者，队列交换机绑定。
 | 原文链接：http://book.excerw.asia/blog/6780838.sHtMl

原标题：golang 系统设计读写分离架构示例
简介：nodejs 日志轮转生产环境配置，配置 Node 日志轮转切割，防止日志文件无限变大，适配生产环境。
 | 原文链接：http://book.excerw.asia/blog/6094759.sHtMl

原标题：安全笔记：Cookie安全属性SecureHttpOnly
简介：项目脚手架模板生成工具，搭建项目模板脚手架，一键生成标准化项目骨架，减少重复初始化工作。
 | 原文链接：http://book.excerw.asia/blog/1289163.sHtMl

原标题：golang 系统设计压测指标确定与分析
简介：golang 网卡 ip 读取网络信息获取，程序读取本机网卡 IP，多网卡环境筛选业务使用 IP 地址。
 | 原文链接：http://book.excerw.asia/blog/4762782.sHtMl

原标题：golang redis 分布式锁 redisson 思路
简介：golang cgo 内存管理 C 与 Go 内存，区分 Go 内存 C 堆内存，防止 cgo 内存泄漏，正确释放 C 内存。
 | 原文链接：http://book.excerw.asia/blog/4619807.sHtMl

原标题：移动端适配 rem vw 方案对比
简介：golang hertz 性能优化参数调优，hertz 连接池、缓冲区参数调优，最大化接口吞吐性能。
 | 原文链接：http://book.excerw.asia/blog/0809354.sHtMl

原标题：零基础理解数据库事务基础ACID概念
简介：golang time 时间格式化参考时间牢记，2006‑01‑02T15:04:05Z07:00，掌握 go 时间格式化关键点。
 | 原文链接：http://book.excerw.asia/blog/7991621.sHtMl

原标题：golang 系统设计开发环境本地调试最佳实践
简介：golang dns 自定义解析器实现，自定义 dns 解析，指定 dns 服务器，控制域名解析逻辑，适配内网环境。
 | 原文链接：http://book.excerw.asia/blog/3788381.sHtMl

原标题：架构复盘：业务系统中如何合理使用分库分表
简介：golang 终端交互式输入选择，命令行交互式问答选择输入，实现交互式脚本工具。
 | 原文链接：http://book.excerw.asia/blog/1839904.sHtMl

原标题：golang validator 自定义校验规则
简介：nodejs 集群模式多核利用实现，使用 cluster 集群模式，充分利用服务器多核 CPU，提升服务处理能力。
 | 原文链接：http://book.excerw.asia/blog/2879661.sHtMl

四、架构设计｜Architecture
原标题：快速入门Nginx基础配置，反向代理示例
简介：golang sqlx 原生 SQL 代码简化，sqlx 简化原生 SQL 结果映射结构体，兼顾性能与开发效率。
 | 原文链接：http://book.excerw.asia/blog/1242163.sHtMl

原标题：Mock 接口服务快速搭建实操
简介：跨平台 uniapp 多端开发实操，uniapp 开发一套代码，编译多端，梳理多端差异处理与适配技巧。
 | 原文链接：http://book.excerw.asia/blog/6581736.sHtMl

原标题：golang 系统设计磁盘满故障应急处理步骤
简介：多环境配置中心灵活切换方案，简易配置中心实现，支持多套环境配置，动态下发无需重启服务。
 | 原文链接：http://book.excerw.asia/blog/1505634.sHtMl

原标题：安全实践：输入输出双向过滤安全最佳实践
简介：golang 灰度发布流量权重路由实现，根据权重切分流量，部分流量访问新版本服务，实现灰度发布。
 | 原文链接：http://book.excerw.asia/blog/5243311.sHtMl

原标题：golang 系统设计分表跨表 join 业务处理方案
简介：golang time 定时器重置 Reset 正确用法，Timer Reset 调用前提，避免 Reset 带来逻辑错误。
 | 原文链接：http://book.excerw.asia/blog/4640488.sHtMl

原标题：golang 系统设计内存复用 sync.pool 使用
简介：golang go toml 配置注释保留，toml 解析保留注释，修改配置后写回保留原有注释。
 | 原文链接：http://book.excerw.asia/blog/2414379.sHtMl

原标题：golang 系统设计内部服务契约测试简单思路
简介：开发环境变量配置全平台教程，区分 Windows、macOS、Linux 系统，讲解环境变量配置、加载优先级与常见失效原因。
 | 原文链接：http://book.excerw.asia/blog/8280139.sHtMl

原标题：踩坑：重试逻辑未做幂等，重复生成业务数据
简介：golang time 时间格式化避坑，Go 时间格式化参考时间牢记，处理时间解析格式化，解决时间输出错乱。
 | 原文链接：http://book.excerw.asia/blog/4852799.sHtMl

原标题：golang 系统设计排行榜几种实现
简介：全局异常处理器接口返回统一，接入全局异常捕获，拦截业务全部异常，对外输出统一格式返回值。
 | 原文链接：http://book.excerw.asia/blog/5950101.sHtMl

原标题：开发复盘：超时参数统一治理线上服务实践
简介：golang 项目目录分层规范设计，Go 后端项目目录分层规范，按领域分层，提高项目可读性可维护性。
 | 原文链接：http://book.excerw.asia/blog/4479533.sHtMl

原标题：golang 系统设计开源项目依赖版本升级维护
简介：golang go list 双向链表使用，container/list 双向链表，频繁增删节点业务场景使用。
 | 原文链接：http://book.excerw.asia/blog/9797360.sHtMl

原标题：开发记录：接口请求日志记录完整中间件实现
简介：golang 协程数量监控统计方案，统计运行中 goroutine 数量，监控协程泄露，协程数量异常及时告警。
 | 原文链接：http://book.excerw.asia/blog/9392573.sHtMl

原标题：golang 系统设计监控告警体系搭建思路
简介：前端 pdf 预览渲染方案对比，对比前端 PDF 预览库，分析性能、兼容性，给出业务选型参考。
 | 原文链接：http://book.excerw.asia/blog/9873273.sHtMl

原标题：踩坑记录：CPU亲和配置不合理多核心负载不均
简介：前端下载导出文件功能实现，前端实现文件流下载导出，处理异常，适配浏览器不同下载行为。
 | 原文链接：http://book.excerw.asia/blog/9064109.sHtMl

原标题：复盘总结：缓存改造业务落地踩坑复盘
简介：大文件导出内存溢出防护，流式处理大文件导出，边读边写，不把全部数据加载内存，规避 OOM。
 | 原文链接：http://book.excerw.asia/blog/4914749.sHtMl

原标题：GitHub Markdown 文档语法汇总
简介：golang loki 日志收集 go 服务集成，日志输出适配 loki，标签携带 traceId，日志集中检索排查问题。
 | 原文链接：http://book.excerw.asia/blog/8908388.sHtMl

原标题：golang 系统设计数据库死锁分析规避
简介：golang bufio 缓冲读写性能优化，bufio 带缓冲读写，减少系统调用，提升文件网络 IO 性能。
 | 原文链接：http://book.excerw.asia/blog/6519616.sHtMl

原标题：golang 系统设计 traceId 全链路透传完整方案
简介：golang testify testify 断言库使用，testify assert require 断言，简化单元测试断言代码。
 | 原文链接：http://book.excerw.asia/blog/0972842.sHtMl

?
