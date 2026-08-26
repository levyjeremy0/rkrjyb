最新前沿技术资讯

一、入门教程｜Getting Started
原标题：Practice：实现数据库事务消息最终一致性demo
简介：golang url 参数编码处理方案，Go URL 参数编码解码，处理特殊字符，避免 URL 参数错乱。
 | 原文链接：http://wiki.87s1od.asia/arts/888670.Doc

原标题：快速入门OpenAPI文档生成基础实践
简介：日志输出规范防止磁盘爆满，控制日志输出量，配置日志切割轮转，避免日志文件无限增长占满磁盘。
 | 原文链接：http://wiki.87s1od.asia/arts/458688.Doc

原标题：golang 系统设计密码存储哈希加盐实现
简介：golang sync.Map 适用场景与性能对比，读多写少，离散 key，对比普通 map 加锁性能差异。
 | 原文链接：http://wiki.87s1od.asia/arts/580531.Doc

原标题：golang 系统设计线上 ddl 变更安全执行思路
简介：代码模块化组件化拆分思路，讲解代码拆分原则，将大业务拆分为独立模块组件，提升代码复用与维护能力。
 | 原文链接：http://wiki.87s1od.asia/arts/806765.Doc

原标题：Performance：避免循环查询N+1问题完整优化
简介：golang fasthttp 高性能 http 库使用，fasthttp 高性能 http 实现，适合超高 QPS 场景，对比 net/http 差异。
 | 原文链接：http://wiki.87s1od.asia/arts/840719.Doc

原标题：golang redis 限流几种实现方案
简介：手写简易 RPC 服务通信原型，手写极简 RPC 原型，理解服务注册、网络传输、方法调用底层逻辑。
 | 原文链接：http://wiki.87s1od.asia/arts/398259.Doc

原标题：Architecture：链路追踪架构核心组件与埋点
简介：golang kafka 消费者组重平衡避坑，规避消费者组频繁 rebalance，减少消费抖动，保障消息消费稳定性。
 | 原文链接：http://wiki.87s1od.asia/arts/519318.Doc

原标题：架构笔记：海量消息堆积架构处理能力设计
简介：golang 高并发下锁优化减少竞争，减小锁粒度，读写锁替换互斥锁，无锁编程降低锁竞争开销。
 | 原文链接：http://wiki.87s1od.asia/arts/737204.Doc

原标题：踩坑：幂等键生成逻辑错误造成重复业务
简介：服务健康检查告警监控体系，搭建健康检查加告警体系，服务异常及时推送告警通知运维人员。
 | 原文链接：http://wiki.87s1od.asia/arts/705149.Doc

原标题：项目实践：消息队列消息堆积模拟处理实践
简介：批量操作分批处理防止 OOM，大批量数据处理不一次性加载全部数据，分批循环处理，避免内存溢出。
 | 原文链接：http://wiki.87s1od.asia/arts/329085.Doc

原标题：golang 系统设计消息发送确认机制配置实操
简介：网络读取超时设置连接挂起防护，设置网络读取超时时间，防止请求无限挂起不返回，占用连接资源。
 | 原文链接：http://wiki.87s1od.asia/arts/812021.Doc

原标题：Debug：分页偏移量过大数据库查询性能暴跌
简介：golang 配置文件热加载监听变更，监听配置文件改动，自动重新加载配置，业务即时生效无需重启。
 | 原文链接：http://wiki.87s1od.asia/arts/714850.Doc

原标题：golang k8s 监控 prometheus 部署
简介：golang 参数校验业务接口处理，Go 接口入参参数校验，拦截非法入参，减少业务层参数判断代码。
 | 原文链接：http://wiki.87s1od.asia/arts/951541.Doc

原标题：golang 信号捕获程序退出处理
简介：golang io.LimitReader 限制读取字节数，LimitReader 限制最大读取，防止读取超大数据。
 | 原文链接：http://wiki.87s1od.asia/arts/857035.Doc

原标题：记一次升级操作系统内核引发服务不稳定
简介：golang 消息队列中间件选型对比，kafka redis‑stream rabbitmq，对比吞吐量可靠性选型参考。
 | 原文链接：http://wiki.87s1od.asia/arts/074670.Doc

原标题：单元测试用例编写入门实操
简介：golang http body 必须关闭的重要性，无论成功失败必须关闭 request.Body，否则连接无法复用泄漏。
 | 原文链接：http://wiki.87s1od.asia/arts/731962.Doc

原标题：OOMKilled 容器被杀完整排查
简介：golang 负载均衡轮询加权轮询实现，手写负载均衡算法，轮询、加权轮询分发请求到后端节点。
 | 原文链接：http://wiki.87s1od.asia/arts/407548.Doc

原标题：Redis 大 key 拆分集群卡顿解决
简介：Nginx 丢失请求头配置修正，修复 Nginx 代理转发丢失请求头配置，保证上游服务拿到完整请求头信息。
 | 原文链接：http://wiki.87s1od.asia/arts/966961.Doc

原标题：golang 信号量控制并发数量
简介：golang cgo 性能开销避坑指南，cgo 调用开销，减少频繁 cgo 调用，规避 cgo 带来内存泄漏风险。
 | 原文链接：http://wiki.87s1od.asia/arts/048974.Doc

原标题：踩坑：分布式事务状态不一致数据两边不一致
简介：多环境配置中心灵活切换方案，简易配置中心实现，支持多套环境配置，动态下发无需重启服务。
 | 原文链接：http://wiki.87s1od.asia/arts/179671.Doc

原标题：架构复盘：系统扩容缩容架构无状态优先原则
简介：RPC 报文大小上限调优大请求，调大 RPC 框架报文最大限制，支持传输大体积请求报文不被截断。
 | 原文链接：http://wiki.87s1od.asia/arts/416316.Doc

原标题：快速入门：API接口调试完整实操步骤
简介：golang gorm ORM 数据库操作，GORM 实操数据库 CRUD，模型定义，关联查询，简化 Go 数据库开发。
 | 原文链接：http://wiki.87s1od.asia/arts/677931.Doc

原标题：golang 系统设计配置回滚版本历史记录实现
简介：网关超时时间调优后端等待，调大网关向后端转发请求超时时间，给后端业务充足处理时间。
 | 原文链接：http://wiki.87s1od.asia/arts/806990.Doc

原标题：实战项目：Nginx限速、限流、防爬虫配置实践
简介：接口压测定位系统性能瓶颈，使用压测工具对接口施压，观察指标，定位系统性能瓶颈点。
 | 原文链接：http://wiki.87s1od.asia/arts/841592.Doc

原标题：golang 系统设计日志采样降低存储开销方案
简介：golang GC 调优 GOGC 参数调整，调整 GOGC 阈值，控制 GC 触发时机，权衡内存占用与 CPU 开销。
 | 原文链接：http://wiki.87s1od.asia/arts/305113.Doc

原标题：golang 单元测试 mock http 请求
简介：golang gorm 原生 SQL 执行处理，复杂场景执行原生 SQL，处理返回结果集，兼顾性能与灵活性。
 | 原文链接：http://wiki.87s1od.asia/arts/710810.Doc

原标题：golang 系统信号信号量处理
简介：golang go 包循环导入报错解决，A 导入 B B 导入 A，循环导入报错，重构代码拆分包消除循环依赖。
 | 原文链接：http://wiki.87s1od.asia/arts/477113.Doc

原标题：运维笔记：服务器定时任务运维脚本编写
简介：golang 接口限流中间件开发，Gin 开发限流中间件，接口层实现访问频率限制，防护接口流量。
 | 原文链接：http://wiki.87s1od.asia/arts/432049.Doc

原标题：项目实践：灰度发布简易方案落地实践
简介：内存广播本地进程消息通知，实现进程内内存消息广播，进程内部模块之间事件通知解耦。
 | 原文链接：http://wiki.87s1od.asia/arts/305320.Doc

原标题：坑点：gitreset误删本地代码恢复方案
简介：golang go 值传递引用传递理解，go 全部为值传递，指针本质拷贝指针值，理清参数传递行为。
 | 原文链接：http://wiki.87s1od.asia/arts/349437.Doc

原标题：golang gin 框架接口开发实战
简介：golang goreleaser 自动版本发布打包，goreleaser 自动化打包发布，生成多平台二进制归档文件。
 | 原文链接：http://wiki.87s1od.asia/arts/370205.Doc

原标题：golang 分布式 ID 雪花算法实现
简介：golang 项目目录分层规范设计，Go 后端项目目录分层规范，按领域分层，提高项目可读性可维护性。
 | 原文链接：http://wiki.87s1od.asia/arts/613528.Doc

原标题：优化实践：批量操作性能优化，减少数据库IO
简介：golang slice 切片底层原理与坑点，切片扩容、截取、底层数组共享，规避切片修改互相影响数据。
 | 原文链接：http://wiki.87s1od.asia/arts/005707.Doc

原标题：效率笔记：Git高级命令日常开发高频使用汇总
简介：热更新开发环境配置教程，配置代码热重载，修改代码无需重启服务立即生效，大幅提升本地开发调试效率。
 | 原文链接：http://wiki.87s1od.asia/arts/604223.Doc

原标题：优化实践：接口批量合并减少网络请求次数
简介：golang pdf 生成 go 服务端生成 pdf，服务端动态生成 pdf 报表文件，直接输出下载给到前端。
 | 原文链接：http://wiki.87s1od.asia/arts/110084.Doc

原标题：安全复盘：Redis命令注入风险防护手段
简介：golang GC 调优 GOGC 参数调整，调整 GOGC 阈值，控制 GC 触发时机，权衡内存占用与 CPU 开销。
 | 原文链接：http://wiki.87s1od.asia/arts/201858.Doc

原标题：快速入门：API接口调试完整实操步骤
简介：日志切割配置防止日志丢失，配置日志切割轮转策略，日志按大小时间切割，防止日志文件丢失。
 | 原文链接：http://wiki.87s1od.asia/arts/709200.Doc

原标题：golang 系统设计回调重试幂等完整处理
简介：前端国际化多语言方案落地，搭建前端多语言国际化方案，切换语言，页面文本自动切换对应语种。
 | 原文链接：http://wiki.87s1od.asia/arts/844694.Doc

原标题：golang 系统设计 issue 模板 bug 反馈模板
简介：css 变量主题切换方案实现，使用 CSS 变量实现网页主题切换，多套主题样式快速切换无需大量 CSS。
 | 原文链接：http://wiki.87s1od.asia/arts/954373.Doc

原标题：golang redis 位图用户签到统计
简介：golang go 基准测试 benchmark 编写，Benchmark 性能基准测试，测量函数执行耗时内存分配情况。
 | 原文链接：http://wiki.87s1od.asia/arts/302599.Doc


二、踩坑排错｜Troubleshooting
原标题：nodejs 流处理大文件不占内存
简介：golang 简单爬虫请求防封禁，简易 Go 爬虫实现，增加请求间隔、UA 伪装，规避被目标站点封禁 IP。
 | 原文链接：http://wiki.87s1od.asia/arts/257987.Doc

原标题：golang 系统设计 protobuf 枚举类型规范写法
简介：golang go 死锁检测工具，静态检查、运行检测，发现 channel 锁导致死锁问题。
 | 原文链接：http://wiki.87s1od.asia/arts/225211.Doc

原标题：golang docker compose 部署 minio
简介：用户敏感数据脱敏代码实现，编写数据脱敏工具，对手机号、身份证做脱敏处理，防止敏感信息直接泄露。
 | 原文链接：http://wiki.87s1od.asia/arts/696744.Doc

原标题：Debug：分页偏移量过大数据库查询性能暴跌
简介：数据库读写分离性能优化，讲解读写分离原理，主库写入从库查询，分担数据库查询压力，提升查询性能。
 | 原文链接：http://wiki.87s1od.asia/arts/095894.Doc

原标题：效率笔记：提升开发效率shell脚本小工具合集
简介：golang mongodb go 驱动实操教程，mongo‑go‑driver 操作 mongodb，文档增删改查聚合查询。
 | 原文链接：http://wiki.87s1od.asia/arts/064592.Doc

原标题：Issue：本地数据库与线上数据库排序规则差异
简介：批量数据处理脚本编写技巧，编写脚本批量处理大量业务数据，循环处理、分批执行，提升数据处理效率。
 | 原文链接：http://wiki.87s1od.asia/arts/232957.Doc

原标题：OAuth2 第三方登录服务搭建
简介：项目脚手架模板生成工具，搭建项目模板脚手架，一键生成标准化项目骨架，减少重复初始化工作。
 | 原文链接：http://wiki.87s1od.asia/arts/563579.Doc

原标题：新手向：开源项目依赖安装失败排查
简介：Spring 事务传播机制配置生效，理解事务传播行为，正确配置，修复事务不生效、事务失效的业务 bug。
 | 原文链接：http://wiki.87s1od.asia/arts/442831.Doc

原标题：golang 系统设计接口向前兼容改造实操
简介：golang embed 目录读取文件列表，embed 嵌入整个目录，读取目录下全部文件，做静态资源服务。
 | 原文链接：http://wiki.87s1od.asia/arts/015775.Doc

原标题：效率笔记：Git高级命令日常开发高频使用汇总
简介：golang 协程 panic 捕获防止崩溃，协程内部捕获 panic，防止单个协程恐慌造成整个 Go 进程崩溃。
 | 原文链接：http://wiki.87s1od.asia/arts/963879.Doc

原标题：golang 系统设计排行榜几种实现
简介：golang kitex 字节微服务框架入门，kitex 开发 rpc 微服务，代码生成，服务注册发现完整流程。
 | 原文链接：http://wiki.87s1od.asia/arts/994605.Doc

原标题：HelloGitWorkflow：理解简单主干开发流程
简介：golang go 程序容器资源 requests limits，设置容器 cpu 内存配额，防止实例抢占集群资源，稳定调度。
 | 原文链接：http://wiki.87s1od.asia/arts/442445.Doc

原标题：排错：HTTPS证书过期导致接口调用失败
简介：Redis 内存淘汰策略数据防丢失，合理配置 Redis 内存淘汰策略，防止内存满后误删除业务重要数据。
 | 原文链接：http://wiki.87s1od.asia/arts/696159.Doc

原标题：部署复盘：静态站点部署CDN完整流程
简介：Cookie Session 会话状态管理，讲解 Cookie 与 Session 原理，理解登录状态保存，实现服务端会话管理逻辑。
 | 原文链接：http://wiki.87s1od.asia/arts/041621.Doc

原标题：开发记录：长连接连接管理自动清理僵死连接
简介：golang go mod 私有 git 仓库配置，配置 go mod 拉取私有仓库代码，处理私有模块依赖拉取问题。
 | 原文链接：http://wiki.87s1od.asia/arts/364179.Doc

原标题：golang es 索引生命周期管理思路
简介：golang goreleaser 自动版本发布打包，goreleaser 自动化打包发布，生成多平台二进制归档文件。
 | 原文链接：http://wiki.87s1od.asia/arts/085846.Doc

原标题：golang alertmanager 钉钉告警推送
简介：golang go http 文件服务器自定义，http.FileServer 自定义 FileSystem，拦截访问，增加鉴权逻辑。
 | 原文链接：http://wiki.87s1od.asia/arts/391606.Doc

原标题：golang 系统设计单元测试 mock 外部依赖技巧
简介：express 中间件开发业务实践，开发 Express 自定义中间件，拦截请求，实现鉴权、日志记录等通用逻辑。
 | 原文链接：http://wiki.87s1od.asia/arts/774372.Doc

原标题：提交第一个开源 PR 完整流程
简介：Mock 接口服务快速搭建实操，搭建模拟后端接口，自定义返回数据、延迟响应，前端开发阶段无需依赖真实后端服务。
 | 原文链接：http://wiki.87s1od.asia/arts/334333.Doc

原标题：golang 系统设计测试覆盖率目标合理设定思路
简介：golang 正则表达式 Go 实操案例，正则匹配提取替换，处理手机号邮箱校验，规避正则回溯 CPU 暴涨。
 | 原文链接：http://wiki.87s1od.asia/arts/548701.Doc

原标题：线上故障：Redis内存淘汰策略错误数据丢失
简介：golang sync/atomic 原子操作使用注意，理解原子操作内存顺序，规避原子操作错误使用带来 bug。
 | 原文链接：http://wiki.87s1od.asia/arts/266987.Doc

原标题：golang 系统设计日志规范结构化日志落地
简介：golang go 终端 pty 伪终端操作，pty 启动子进程，模拟终端交互，实现交互式命令调用。
 | 原文链接：http://wiki.87s1od.asia/arts/455173.Doc

原标题：golang 系统设计配置敏感信息加密存储方案
简介：golang 日志级别动态调整热更新，不用重启程序动态修改日志输出级别，线上调试排查问题十分方便。
 | 原文链接：http://wiki.87s1od.asia/arts/574436.Doc

原标题：方案设计：多租户系统架构三种实现模式对比
简介：golang gorm 软删除实现逻辑，Gorm 开启软删除，删除数据仅标记，数据保留可恢复，满足业务数据留存。
 | 原文链接：http://wiki.87s1od.asia/arts/608484.Doc

原标题：避坑：定时任务重复执行带来业务脏数据
简介：golang 处理连接被重置 reset 错误，识别 connection reset by peer，对端关闭连接异常处理逻辑。
 | 原文链接：http://wiki.87s1od.asia/arts/921118.Doc

原标题：方案设计：高可用Redis集群架构选型对比
简介：内存溢出问题现象识别排查，识别内存溢出现象，梳理排查方向，定位内存持续上涨引发服务崩溃问题。
 | 原文链接：http://wiki.87s1od.asia/arts/062503.Doc

原标题：pnpm 包管理工具实战避坑指南
简介：golang errors.Is errors.As 错误判断，判断是否为指定错误类型，提取自定义错误信息，错误处理进阶。
 | 原文链接：http://wiki.87s1od.asia/arts/657520.Doc

原标题：Practice：实现跨机器文件同步脚本实践
简介：golang 任务失败重试与死信队列，异步任务失败自动重试，超过重试次数进入死信队列人工处理。
 | 原文链接：http://wiki.87s1od.asia/arts/850918.Doc

原标题：排错：静态资源404，打包路径配置错误
简介：缓存过期策略优化防业务故障，合理设置缓存过期策略，规避集中过期，减少缓存失效带来业务抖动。
 | 原文链接：http://wiki.87s1od.asia/arts/922567.Doc

原标题：前端组件库按需加载性能优化
简介：定时任务周期调度 demo 开发，实现简单定时调度程序，按时间周期执行业务逻辑，理解定时任务运行机制。
 | 原文链接：http://wiki.87s1od.asia/arts/819457.Doc

原标题：零基础理解数据库事务基础ACID概念
简介：golang http.Server 配置参数详解，ReadTimeout WriteTimeout IdleTimeout，全方位防护慢请求攻击。
 | 原文链接：http://wiki.87s1od.asia/arts/526353.Doc

原标题：后端大文件分片上传接口开发
简介：golang 跨平台系统差异处理方案，处理 windows linux mac 路径、信号、文件权限差异，代码跨平台兼容。
 | 原文链接：http://wiki.87s1od.asia/arts/711035.Doc

原标题：golang mysql 行锁表锁场景区分
简介：golang strings.Builder 字符串高效拼接，strings.Builder 做字符串拼接，比 += 性能更高，减少内存拷贝。
 | 原文链接：http://wiki.87s1od.asia/arts/671759.Doc

原标题：golang 系统设计配置灰度下发简单实现思路
简介：golang cpu pprof 性能分析实操，使用 pprof 采集 CPU 性能数据，定位 CPU 高占用函数，做性能优化。
 | 原文链接：http://wiki.87s1od.asia/arts/295717.Doc

原标题：nodejs jwt 登录鉴权完整示例
简介：golang tls 证书加载配置 https 服务，加载证书密钥，搭建 golang https 服务，配置 tls 版本安全策略。
 | 原文链接：http://wiki.87s1od.asia/arts/997322.Doc

原标题：方案设计：统一错误处理架构全链路方案
简介：golang go http 安全头配置实践，设置 http 安全响应头，防范 XSS、点击劫持，提升 web 服务安全性。
 | 原文链接：http://wiki.87s1od.asia/arts/789406.Doc

原标题：异步任务堆积消费能力优化
简介：对象存储上传下载权限实操，演示对象存储文件上传、下载、访问权限设置，适配业务文件存储场景。
 | 原文链接：http://wiki.87s1od.asia/arts/290200.Doc

原标题：设计实践：如何设计可扩展业务数据库表结构
简介：golang defer 闭包变量捕获坑，defer 捕获循环变量引用，变量被复写，理解闭包变量捕获规则。
 | 原文链接：http://wiki.87s1od.asia/arts/852431.Doc

原标题：踩坑记录：浮点精度错误造成业务计算错误
简介：消息队列消费堆积扩容处理，消息大量堆积时，扩容消费实例，优化消费逻辑，加快消息处理速度。
 | 原文链接：http://wiki.87s1od.asia/arts/896330.Doc

原标题：golang 系统设计 e2e 端到端测试简单落地思路
简介：golang 定时任务任务持久化存储，定时任务持久化到数据库，服务重启任务不丢失，动态管理任务。
 | 原文链接：http://wiki.87s1od.asia/arts/297858.Doc

三、实战开发｜Practice
原标题：Architecture：服务注册发现架构原理与选型
简介：跨平台 uniapp 多端开发实操，uniapp 开发一套代码，编译多端，梳理多端差异处理与适配技巧。
 | 原文链接：http://wiki.87s1od.asia/arts/772763.Doc

原标题：OpenSource：开源项目贡献者协作流程规范
简介：golang json number 数字不转 float64，使用 json.Number 保留原始数字字符串，防止大数字精度丢失。
 | 原文链接：http://wiki.87s1od.asia/arts/559435.Doc

原标题：排错：DockerCompose依赖顺序启动顺序坑
简介：golang go mod graph 可视化依赖图，可视化 go 依赖关系，直观看到包之间依赖，定位冲突。
 | 原文链接：http://wiki.87s1od.asia/arts/151210.Doc

原标题：安全实践：输入输出双向过滤安全最佳实践
简介：golang redis scan 遍历 key 避免阻塞，使用 scan 迭代遍历 redis 键，不用 keys 命令，防止阻塞 redis 服务。
 | 原文链接：http://wiki.87s1od.asia/arts/145956.Doc

原标题：方案对比：同步事务vs事务消息最终一致性
简介：golang redis stream 消息队列实战，redis stream 实现可靠消息队列，消费组、ack 确认，消息不丢失。
 | 原文链接：http://wiki.87s1od.asia/arts/412439.Doc

原标题：数据库排序规则统一结果一致
简介：golang nacos go 客户端配置服务发现，nacos‑go 对接 nacos，配置管理、微服务注册发现。
 | 原文链接：http://wiki.87s1od.asia/arts/771157.Doc

原标题：golang 系统设计网关 ssl 证书配置更新实操
简介：并发数据覆盖加锁安全处理，多线程并发修改同一数据，增加锁机制，防止并发覆盖丢失更新数据。
 | 原文链接：http://wiki.87s1od.asia/arts/522060.Doc

原标题：golang 系统设计批量处理优化业务性能
简介：golang context 包标准用法规范，context 传递请求元数据、超时、取消，函数第一个参数传入 ctx。
 | 原文链接：http://wiki.87s1od.asia/arts/883580.Doc

原标题：快速入门YAML配置文件语法与示例
简介：golang prometheus 指标埋点开发，业务埋点计数器、仪表盘、直方图，对接 prometheus 采集监控指标。
 | 原文链接：http://wiki.87s1od.asia/arts/641369.Doc

原标题：golang 系统设计配置热更新不重启服务实现
简介：golang rsa 签名验签 pem 证书加载，加载 pem 格式密钥证书，rsa 签名与验签完整业务实现。
 | 原文链接：http://wiki.87s1od.asia/arts/600872.Doc

原标题：安全笔记：GitHubAction密钥安全管理
简介：TCP 心跳检测清理僵死连接，开启 TCP 心跳机制，自动清理僵死无效连接，释放连接资源。
 | 原文链接：http://wiki.87s1od.asia/arts/773555.Doc

原标题：Practice：实现多数据源动态切换组件实践
简介：数据库事务 ACID 原理讲解，拆解事务四大特性，理解事务隔离、原子性，明白事务如何保障数据安全。
 | 原文链接：http://wiki.87s1od.asia/arts/678921.Doc

原标题：服务健康检查告警监控体系
简介：golang go 死锁检测工具，静态检查、运行检测，发现 channel 锁导致死锁问题。
 | 原文链接：http://wiki.87s1od.asia/arts/071209.Doc

原标题：golang 系统设计线上日志快速检索技巧
简介：golang redis scan 遍历 key 避免阻塞，使用 scan 迭代遍历 redis 键，不用 keys 命令，防止阻塞 redis 服务。
 | 原文链接：http://wiki.87s1od.asia/arts/498780.Doc

原标题：踩坑记录：乐观锁版本号处理不当更新失败
简介：golang 速率限制令牌桶实现，Go 实现令牌桶限流算法，可复用限流器，控制业务调用速率。
 | 原文链接：http://wiki.87s1od.asia/arts/004356.Doc

原标题：实践：消息队列死信处理业务落地实践
简介：golang url 解析路径参数提取，url.Parse 解析 url，获取协议主机路径查询参数。
 | 原文链接：http://wiki.87s1od.asia/arts/433851.Doc

原标题：定时任务周期调度 demo 开发
简介：golang smtp 邮件发送完整示例，调用 smtp 服务发送文本与 html 格式邮件，实现邮件通知能力。
 | 原文链接：http://wiki.87s1od.asia/arts/566845.Doc

原标题：Troubleshoot：DNS解析异常导致第三方调用失败
简介：K8s 镜像拉取网络故障修复，排查 K8s 集群镜像拉取网络问题，配置镜像源，恢复镜像正常拉取。
 | 原文链接：http://wiki.87s1od.asia/arts/967265.Doc

原标题：Practice：实现熔断降级组件简单原型代码
简介：golang go mod graph 可视化依赖图，可视化 go 依赖关系，直观看到包之间依赖，定位冲突。
 | 原文链接：http://wiki.87s1od.asia/arts/611274.Doc

原标题：浏览器本地存储安全使用技巧
简介：golang cgo 内存管理 C 与 Go 内存，区分 Go 内存 C 堆内存，防止 cgo 内存泄漏，正确释放 C 内存。
 | 原文链接：http://wiki.87s1od.asia/arts/233324.Doc

原标题：记一次字符集编码不一致乱码问题全排查
简介：golang errors.Is errors.As 错误判断，判断是否为指定错误类型，提取自定义错误信息，错误处理进阶。
 | 原文链接：http://wiki.87s1od.asia/arts/776057.Doc

原标题：运维笔记：系统监控指标大盘搭建实操
简介：golang os 环境变量读取设置，os.Getenv os.Setenv os.Unsetenv 读写环境变量，环境变量多值处理。
 | 原文链接：http://wiki.87s1od.asia/arts/071093.Doc

原标题：踩坑：Docker容器内时区不一致引发的时间BUG
简介：golang socket 文件描述符继承重启，父进程传递 listener fd 给子进程，实现 go 程序零停机热重启。
 | 原文链接：http://wiki.87s1od.asia/arts/223221.Doc

原标题：安全复盘：业务数据脱敏防止泄露实践
简介：golang redis pipeline 与 txpipeline 区别，区分普通管道与事务管道，根据业务场景选择合适批量执行方案。
 | 原文链接：http://wiki.87s1od.asia/arts/460920.Doc

原标题：安全笔记：GitHubAction密钥安全管理
简介：WebSocket 聊天室实时通讯开发，基于 WebSocket 搭建简易聊天室，实现多人消息广播实时聊天效果。
 | 原文链接：http://wiki.87s1od.asia/arts/964091.Doc

原标题：golang mysql 主从同步延迟兼容
简介：golang go 服务蓝绿发布实践思路，蓝绿两套实例，流量一键切换，回滚快速降低发布风险。
 | 原文链接：http://wiki.87s1od.asia/arts/613277.Doc

原标题：新手教程：Gittag版本标签打标签实操
简介：死信队列处理消息阻塞业务，配置死信队列，处理消费失败消息，避免失败消息阻塞整个队列业务。
 | 原文链接：http://wiki.87s1od.asia/arts/781422.Doc

原标题：方案对比：轮询长轮询WebSocket推送架构选型
简介：数据库连接池参数调优，调整连接池最大最小连接数，空闲超时，避免连接耗尽或者资源浪费。
 | 原文链接：http://wiki.87s1od.asia/arts/837358.Doc

原标题：golang mysql 行锁表锁场景区分
简介：golang etcd key 监听变更 watch 机制，watch 监听 etcd 键变化，配置变更实时感知，实现配置热更新。
 | 原文链接：http://wiki.87s1od.asia/arts/238029.Doc

原标题：线上异常：时间时区问题，定时任务执行偏移
简介：golang go1.18 + 泛型基础实操，go 泛型基础语法，泛型函数泛型类型，实现通用工具函数。
 | 原文链接：http://wiki.87s1od.asia/arts/290269.Doc

原标题：部署复盘：配置热更新不用重启服务方案
简介：golang bytes.Buffer 字节缓冲区使用，bytes.Buffer 字节内存缓冲区，拼接字节，避免频繁内存分配。
 | 原文链接：http://wiki.87s1od.asia/arts/777980.Doc

原标题：运维笔记：服务器Swap分区调优生产实践
简介：CI/CD 流水线自动构建部署落地，搭建完整 CI/CD 流水线，代码提交自动构建、测试、部署到目标环境。
 | 原文链接：http://wiki.87s1od.asia/arts/137379.Doc

原标题：golang k8s cronjob 定时任务配置
简介：golang loki 日志收集 go 服务集成，日志输出适配 loki，标签携带 traceId，日志集中检索排查问题。
 | 原文链接：http://wiki.87s1od.asia/arts/334650.Doc

原标题：架构笔记：数据库连接池架构参数调优思路
简介：golang 项目 makefile 脚本编写，编写 Makefile 脚本，封装编译、测试、构建命令，简化项目操作。
 | 原文链接：http://wiki.87s1od.asia/arts/898214.Doc

原标题：golang 系统设计缓存 key 命名规范最佳实践
简介：nodejs 多进程任务分发处理，多进程拆分处理 CPU 密集任务，主进程分发任务，利用多核提升处理速度。
 | 原文链接：http://wiki.87s1od.asia/arts/317388.Doc

原标题：文件句柄耗尽资源泄露处理
简介：静态资源 404 路径打包修复，修复打包后静态资源访问 404，调整资源输出路径，保证资源正常加载。
 | 原文链接：http://wiki.87s1od.asia/arts/612509.Doc

原标题：前端工程化 webpack 打包优化
简介：golang grpc metadata 元数据透传，metadata 传递 traceId、鉴权信息，全链路透传上下文信息。
 | 原文链接：http://wiki.87s1od.asia/arts/293340.Doc

原标题：手写简易 ORM 理解对象映射
简介：golang 大文件读取内存优化，Go 流式读取大文件，分块处理，避免大文件一次性加载全部到内存。
 | 原文链接：http://wiki.87s1od.asia/arts/471429.Doc

原标题：动态定时任务业务调度实现
简介：golang 协程泄露问题排查方法，识别 Go 协程泄露现象，分析泄露场景，给出排查定位协程泄露手段。
 | 原文链接：http://wiki.87s1od.asia/arts/958416.Doc

原标题：避坑：CookieSecure属性造成测试环境登录失败
简介：多环境配置中心灵活切换方案，简易配置中心实现，支持多套环境配置，动态下发无需重启服务。
 | 原文链接：http://wiki.87s1od.asia/arts/175335.Doc

四、架构设计｜Architecture
原标题：golang 系统设计回调异步处理防止超时阻塞
简介：特殊输入字符过滤解析防护，过滤用户输入特殊字符，防止解析报错，规避恶意字符带来业务异常。
 | 原文链接：http://wiki.87s1od.asia/arts/235913.Doc

原标题：golang etcd 分布式锁实现原理
简介：golang word 文档生成处理 go 方案，go 生成 word 文档报表，填充文本表格，输出 docx 文件。
 | 原文链接：http://wiki.87s1od.asia/arts/863975.Doc

原标题：golang redis 主从复制哨兵原理
简介：golang 限流器熔断降级组合使用，限流熔断降级组合架构，流量防护完整方案，保障服务稳定性。
 | 原文链接：http://wiki.87s1od.asia/arts/931001.Doc

原标题：golang 系统设计 protobuf json 性能对比
简介：前端工程化 webpack 打包优化，针对 webpack 项目做打包调优，分包、压缩、Tree‑Shaking，缩减包体积。
 | 原文链接：http://wiki.87s1od.asia/arts/342624.Doc

原标题：golang 分库分表简单路由实现
简介：golang sync.RWMutex 读写锁使用场景，读多写少场景读写锁，读共享写互斥，提升并发性能。
 | 原文链接：http://wiki.87s1od.asia/arts/182876.Doc

原标题：Performance：避免全表扫描索引失效场景汇总
简介：golang 图片处理 go 图片裁剪压缩，golang 图像处理库，图片缩放裁剪水印，服务端图片处理。
 | 原文链接：http://wiki.87s1od.asia/arts/862363.Doc

原标题：本地简易配置中心动态管理
简介：内存广播本地进程消息通知，实现进程内内存消息广播，进程内部模块之间事件通知解耦。
 | 原文链接：http://wiki.87s1od.asia/arts/088521.Doc

原标题：golang redis 计数器防超卖示例
简介：golang time 时间比较 Before After Equal，时间比较不要直接减，使用内置方法判断时间先后。
 | 原文链接：http://wiki.87s1od.asia/arts/314065.Doc

原标题：系统时间同步定时任务偏移
简介：golang go ring 环形容器循环队列，ring 环形链表实现循环队列，环形缓冲区业务场景。
 | 原文链接：http://wiki.87s1od.asia/arts/034444.Doc

原标题：golang 系统设计防爬虫简单策略
简介：开源项目本地运行排错完整清单，汇总开源项目拉取后运行失败各类问题，给出排查思路，快速解决本地启动异常。
 | 原文链接：http://wiki.87s1od.asia/arts/167023.Doc

原标题：golang 系统设计多租户数据隔离方案
简介：golang go 模板执行错误捕获，捕获模板执行错误，防止模板错误直接返回空白页面。
 | 原文链接：http://wiki.87s1od.asia/arts/781416.Doc

原标题：RPC 接口字段增减兼容处理
简介：包管理器依赖缓存清理，清理本地依赖缓存，解决缓存旧包引发问题，拉取最新版本依赖包。
 | 原文链接：http://wiki.87s1od.asia/arts/782801.Doc

原标题：方案设计：短链接系统完整架构方案拆解
简介：依赖版本冲突兼容修复方案，定位依赖版本冲突根源，通过版本约束、替换包，解决版本不兼容运行报错。
 | 原文链接：http://wiki.87s1od.asia/arts/630624.Doc

原标题：golang git 提交信息规范校验
简介：golang errors.Is errors.As 错误判断，判断是否为指定错误类型，提取自定义错误信息，错误处理进阶。
 | 原文链接：http://wiki.87s1od.asia/arts/803003.Doc

原标题：golang 系统设计配置中心核心能力梳理讲解
简介：序列化版本不一致解析失败，保证序列化对象版本对齐，修复版本不匹配导致对象反序列化失败。
 | 原文链接：http://wiki.87s1od.asia/arts/558012.Doc

原标题：OpenAPI 自动接口文档生成
简介：SSH 密钥配置 GitHub 免密登录，分步生成配置 SSH 密钥，实现 GitHub 免密推送拉取，免去重复输入账号密码的麻烦。
 | 原文链接：http://wiki.87s1od.asia/arts/648176.Doc

原标题：消息队列消费堆积扩容处理
简介：golang go‑zero 框架项目快速搭建，go‑zero 脚手架生成微服务项目，api rpc 服务快速开发。
 | 原文链接：http://wiki.87s1od.asia/arts/307146.Doc

原标题：开发复盘：统一错误码体系设计落地实践
简介：分页逻辑错误数据漏查修复，修复分页查询逻辑漏洞，解决分页漏数据、重复返回数据等业务问题。
 | 原文链接：http://wiki.87s1od.asia/arts/315777.Doc

?
