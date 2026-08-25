最新前沿技术资讯

一、入门教程｜Getting Started
原标题：golang 系统设计代码评审 checklist 清单
简介：CI 持续集成自动构建流程，讲解 CI 基础概念，配置流水线实现代码提交后自动构建、测试，提升交付自动化。
 | 原文链接：http://book.3fpyao.asia/blog/0426628.sHtMl

原标题：性能复盘：慢查询日积月累拖垮数据库优化
简介：golang 大内存分配 GC 抖动规避，避免瞬时大量对象创建，分批处理，防止 GC 抖动业务抖动。
 | 原文链接：http://book.3fpyao.asia/blog/7218355.sHtMl

原标题：后端登录鉴权模块完整开发
简介：golang rabbitmq go 客户端生产消费，streadway/amqp 实现 rabbitmq 生产者消费者，队列交换机绑定。
 | 原文链接：http://book.3fpyao.asia/blog/7766897.sHtMl

原标题：golang k8s 监控 prometheus 部署
简介：vite 项目配置与构建提速技巧，讲解 vite 配置优化手段，提升开发热更新速度与生产构建打包效率。
 | 原文链接：http://book.3fpyao.asia/blog/3450973.sHtMl

原标题：golang 系统设计压测数据构造方法实现
简介：golang 文件上传下载接口开发，Go 开发文件上传下载接口，校验文件，处理文件读写存储逻辑。
 | 原文链接：http://book.3fpyao.asia/blog/6765726.sHtMl

原标题：性能笔记：TCP参数内核调优服务高并发场景
简介：依赖版本冲突兼容修复方案，定位依赖版本冲突根源，通过版本约束、替换包，解决版本不兼容运行报错。
 | 原文链接：http://book.3fpyao.asia/blog/3836056.sHtMl

原标题：坑点：Docker资源限制未设置导致宿主机卡死
简介：请求重试组件退避策略实现，封装重试组件，实现指数退避策略，避免大量请求同时重试压垮下游。
 | 原文链接：http://book.3fpyao.asia/blog/2282904.sHtMl

原标题：调优方案：gzip压缩开启降低网络传输体积
简介：golang errgroup 协程组错误处理，errgroup 捕获协程错误，context 取消剩余协程，简化并发任务。
 | 原文链接：http://book.3fpyao.asia/blog/8584372.sHtMl

原标题：golang 系统设计大流量削峰处理方案
简介：业务幂等键设计防重复逻辑，讲解幂等键设计思路，选择合适业务字段作为幂等标识，实现可靠防重复。
 | 原文链接：http://book.3fpyao.asia/blog/2621341.sHtMl

原标题：前端大文件分片上传完整方案
简介：业务错误码完整落地实践，落地完整业务错误码，枚举全部业务异常，统一返回，配套文档说明。
 | 原文链接：http://book.3fpyao.asia/blog/7512917.sHtMl

原标题：Practice：实现接口防重提交组件实践
简介：golang bufio 缓冲读写性能优化，bufio 带缓冲读写，减少系统调用，提升文件网络 IO 性能。
 | 原文链接：http://book.3fpyao.asia/blog/4394273.sHtMl

原标题：方案对比：轮询长轮询WebSocket推送架构选型
简介：golang go 爬虫异步并发抓取，协程池控制并发抓取网页，多协程采集，提升爬虫采集速度。
 | 原文链接：http://book.3fpyao.asia/blog/8970473.sHtMl

原标题：开源实践：给开源项目写单元测试贡献代码
简介：pnpm 包管理工具实战避坑指南，使用 pnpm 管理项目依赖，梳理常见坑点，充分利用 pnpm 优势。
 | 原文链接：http://book.3fpyao.asia/blog/3807245.sHtMl

原标题：新手向：npm/pip/maven依赖版本冲突入门排查
简介：express 中间件开发业务实践，开发 Express 自定义中间件，拦截请求，实现鉴权、日志记录等通用逻辑。
 | 原文链接：http://book.3fpyao.asia/blog/0815747.sHtMl

原标题：入门实践：简易进度条CLI工具实现demo
简介：限流组件计数器令牌桶模式实现，实现计数器、令牌桶两种限流算法，封装可复用限流组件。
 | 原文链接：http://book.3fpyao.asia/blog/5763765.sHtMl

原标题：部署实践：Nginx高可用配置方案实践
简介：vue pinia 状态管理实战教程，Pinia 完整实战示例，实现状态定义修改，模块拆分替代 Vuex。
 | 原文链接：http://book.3fpyao.asia/blog/7804310.sHtMl

原标题：架构复盘：业务系统中如何合理使用分库分表
简介：前端下载导出文件功能实现，前端实现文件流下载导出，处理异常，适配浏览器不同下载行为。
 | 原文链接：http://book.3fpyao.asia/blog/5562655.sHtMl

原标题：接口签名验签完整安全方案
简介：golang time 时间比较 Before After Equal，时间比较不要直接减，使用内置方法判断时间先后。
 | 原文链接：http://book.3fpyao.asia/blog/2287190.sHtMl

原标题：golang 批量任务协程控制防雪崩
简介：正则表达式优化 CPU 占满问题，优化正则表达式写法，避免回溯，防止正则运算 CPU 占用 100%。
 | 原文链接：http://book.3fpyao.asia/blog/6069858.sHtMl

原标题：golang 互斥锁读写锁并发安全
简介：nodejs 跨域中间件配置细节，Express 跨域中间件配置细节，处理预检请求，修复偶现跨域失效。
 | 原文链接：http://book.3fpyao.asia/blog/2624081.sHtMl

原标题：Hands‑on：简易配置中心本地原型实现
简介：golang 单元测试 table‑driven，表格驱动单元测试写法，批量输入多组测试用例，简化单元测试代码。
 | 原文链接：http://book.3fpyao.asia/blog/2878336.sHtMl

原标题：golang gitlab runner 部署与注册实操
简介：golang redis 过期时间处理技巧，设置 key 过期，监控过期事件，基于过期特性实现业务缓存逻辑。
 | 原文链接：http://book.3fpyao.asia/blog/5318065.sHtMl

原标题：开发复盘：大事务拆分优化业务性能实践
简介：golang 熔断降级简易组件开发，Go 简易熔断组件，下游故障触发熔断，保护上游服务不被拖垮。
 | 原文链接：http://book.3fpyao.asia/blog/2254054.sHtMl

原标题：序列化版本不一致解析失败
简介：golang grpc 客户端流上传数据，客户端流式请求，客户端分批上传数据到服务端，适合大文件传输。
 | 原文链接：http://book.3fpyao.asia/blog/9739544.sHtMl

原标题：Troubleshoot：MySQL字符集utf8非utf8mb4emoji报错
简介：golang grpc 负载均衡客户端实现，grpc 客户端负载均衡，轮询随机权重，分发请求到多个服务实例。
 | 原文链接：http://book.3fpyao.asia/blog/8052384.sHtMl

原标题：快速上手简单的限流逻辑模拟实现
简介：不必要字符转义关闭业务异常，关闭多余自动转义逻辑，防止业务数据被错误转义，破坏原始数据。
 | 原文链接：http://book.3fpyao.asia/blog/0053498.sHtMl

原标题：部署实践：多实例服务部署无状态改造
简介：golang go 第三方库选型评估要点，评估库活跃度维护情况、性能、依赖数量，选择合适开源库。
 | 原文链接：http://book.3fpyao.asia/blog/6405855.sHtMl

原标题：安全复盘：业务接口越权测试与修复实践
简介：golang 单元测试 table‑driven，表格驱动单元测试写法，批量输入多组测试用例，简化单元测试代码。
 | 原文链接：http://book.3fpyao.asia/blog/6662165.sHtMl

原标题：实战项目：WebSocket消息广播房间分组实践
简介：开发代理服务网络限制解决，搭建本地代理服务，解决开发环境网络访问受限，实现外部接口正常调用。
 | 原文链接：http://book.3fpyao.asia/blog/1842006.sHtMl

原标题：golang etcd 租约 lease 过期机制
简介：GC 垃圾回收优化降低 CPU 占用，调整 GC 参数，优化对象创建销毁，降低垃圾回收带来 CPU 开销。
 | 原文链接：http://book.3fpyao.asia/blog/2735024.sHtMl

原标题：架构复盘：消息队列在业务系统中边界与最佳实践
简介：多套环境灵活切换配置方案，实现配置动态切换，通过环境变量、配置文件，快速切换开发测试生产环境。
 | 原文链接：http://book.3fpyao.asia/blog/4905364.sHtMl

原标题：Cookie Session 会话状态管理
简介：golang 模糊测试 go fuzz 基础编写，Fuzz 测试函数，自动生成随机输入，发现代码崩溃 panic。
 | 原文链接：http://book.3fpyao.asia/blog/9459555.sHtMl

原标题：实战：数据库索引设计，复合索引最佳实践
简介：golang go http 文件服务器自定义，http.FileServer 自定义 FileSystem，拦截访问，增加鉴权逻辑。
 | 原文链接：http://book.3fpyao.asia/blog/9023359.sHtMl

原标题：nodejs 全局异常捕获进程防护
简介：golang context.Background 与 TODO 区别，Background 主流程根上下文，TODO 不确定用哪个上下文时使用。
 | 原文链接：http://book.3fpyao.asia/blog/0116576.sHtMl

原标题：安全笔记：CORS跨域配置错误安全风险
简介：golang 系统 IO 阻塞 goroutine 场景，理解系统调用阻塞 M，P 会调度其他 M，掌握 go 调度行为。
 | 原文链接：http://book.3fpyao.asia/blog/0523831.sHtMl

原标题：Debug：并发场景下数据覆盖丢失问题定位
简介：golang gorm select 指定查询字段，指定查询字段，避免查询全部字段，减少数据传输，提升查询性能。
 | 原文链接：http://book.3fpyao.asia/blog/4612840.sHtMl

原标题：调优方案：gzip压缩开启降低网络传输体积
简介：golang 异步任务队列 worker 池开发，任务入数据库或 redis，worker 池消费执行，异步处理耗时业务。
 | 原文链接：http://book.3fpyao.asia/blog/9337380.sHtMl

原标题：排错：CI流水线构建失败，日志无明确报错
简介：golang uuid 生成多种版本实现，生成 uuid v1 v4，生成唯一标识，业务用于单据编号场景。
 | 原文链接：http://book.3fpyao.asia/blog/5059750.sHtMl

原标题：golang 分页查询封装通用工具
简介：简易日志收集集中管理方案，搭建轻量日志收集方案，把多服务日志汇总，集中检索查看日志信息。
 | 原文链接：http://book.3fpyao.asia/blog/1943402.sHtMl

原标题：限流组件计数器令牌桶模式实现
简介：golang 协程 panic 捕获防止崩溃，协程内部捕获 panic，防止单个协程恐慌造成整个 Go 进程崩溃。
 | 原文链接：http://book.3fpyao.asia/blog/7490466.sHtMl


二、踩坑排错｜Troubleshooting
原标题：静态博客部署 GitHub Pages 教程
简介：golang os 环境变量读取设置，os.Getenv os.Setenv os.Unsetenv 读写环境变量，环境变量多值处理。
 | 原文链接：http://book.3fpyao.asia/blog/5962937.sHtMl

原标题：线上异常：缓存雪崩带来数据库压力瞬间飙升
简介：golang sort 稳定排序 Stable，稳定排序保留相等元素原有顺序，业务需要稳定排序场景。
 | 原文链接：http://book.3fpyao.asia/blog/1925727.sHtMl

原标题：快速入门YAML配置文件语法与示例
简介：百万数据 Excel 导出内存优化，优化大 Excel 导出逻辑，流式输出，避免一次性加载全部数据造成 OOM。
 | 原文链接：http://book.3fpyao.asia/blog/7143383.sHtMl

原标题：CI 持续集成自动构建流程
简介：golang time 定时器重置 Reset 正确用法，Timer Reset 调用前提，避免 Reset 带来逻辑错误。
 | 原文链接：http://book.3fpyao.asia/blog/8254892.sHtMl

原标题：golang 系统设计缓存基准测试对比方案
简介：golang rsa 公钥加密私钥解密，rsa 非对称加密，大文件分块加密，处理非对称加密长度限制。
 | 原文链接：http://book.3fpyao.asia/blog/8878268.sHtMl

原标题：golang 系统设计网关灰度流量切分简单方案
简介：内存泄漏定位分析完整流程，分享内存泄漏排查步骤，定位没有释放的对象，解决内存持续上涨问题。
 | 原文链接：http://book.3fpyao.asia/blog/3535012.sHtMl

原标题：golang 日志 zap 结构化日志实践
简介：golang io.LimitReader 限制读取字节数，LimitReader 限制最大读取，防止读取超大数据。
 | 原文链接：http://book.3fpyao.asia/blog/1010843.sHtMl

原标题：复盘总结：数据库迁移升级风险评估清单
简介：Cookie 跨环境登录配置调整，调整 Cookie 域、Secure 属性，适配开发测试生产环境，修复登录失效。
 | 原文链接：http://book.3fpyao.asia/blog/2062721.sHtMl

原标题：golang 系统设计容器 OOM 故障完整排查
简介：golang go1.18 + 泛型基础实操，go 泛型基础语法，泛型函数泛型类型，实现通用工具函数。
 | 原文链接：http://book.3fpyao.asia/blog/6807613.sHtMl

原标题：数值 key 浮点匹配异常规避
简介：golang regexp 正则捕获分组提取数据，正则捕获分组提取子匹配内容，拿到需要业务字段。
 | 原文链接：http://book.3fpyao.asia/blog/6573949.sHtMl

原标题：Nginx 反向代理路由配置实战
简介：全量回归测试提升代码质量，搭建全量回归测试集，版本发布执行回归测试，避免迭代引入旧 bug。
 | 原文链接：http://book.3fpyao.asia/blog/8642088.sHtMl

原标题：Practice：实现接口防重提交组件实践
简介：golang go 程序运行时动态修改配置，运行时热加载配置结构体，原子更新保证并发读取安全。
 | 原文链接：http://book.3fpyao.asia/blog/5472521.sHtMl

原标题：实战：Nginx配置静态站点、反向代理、负载均衡
简介：golang http cookie jar 会话处理，客户端 cookie jar 自动管理 cookie，处理登录态会话。
 | 原文链接：http://book.3fpyao.asia/blog/3385503.sHtMl

原标题：实战：Redis过期回调实现业务事件通知实践
简介：golang 大文件读取内存优化，Go 流式读取大文件，分块处理，避免大文件一次性加载全部到内存。
 | 原文链接：http://book.3fpyao.asia/blog/4965142.sHtMl

原标题：前端国际化多语言方案落地
简介：golang 优雅关闭 grpc 服务示例，gRPC 服务优雅关闭，等待现有请求处理完成再停止服务。
 | 原文链接：http://book.3fpyao.asia/blog/5931279.sHtMl

原标题：安全实践：最小权限原则数据库账号管控
简介：golang go ring 环形容器循环队列，ring 环形链表实现循环队列，环形缓冲区业务场景。
 | 原文链接：http://book.3fpyao.asia/blog/0170548.sHtMl

原标题：开发生产环境资源路径统一
简介：nodejs 数据库连接池配置调优，调优 Node 数据库连接池参数，平衡性能与资源占用，避免连接耗尽。
 | 原文链接：http://book.3fpyao.asia/blog/1092475.sHtMl

原标题：golang redis 分布式计数器开发
简介：API 大版本不兼容平滑迁移，API 版本迭代不兼容旧接口，设计平滑迁移方案，逐步完成版本切换。
 | 原文链接：http://book.3fpyao.asia/blog/0143849.sHtMl

原标题：设计思考：消息顺序性架构保证与业务妥协
简介：golang 优雅处理 http 超时设置，Go HTTP 请求设置各类超时，防止请求无限阻塞，保护协程与连接。
 | 原文链接：http://book.3fpyao.asia/blog/5088903.sHtMl

原标题：Practice：实现接口mock动态返回不同响应
简介：golang go‑pg postgres 客户端实操，go‑pg 操作 PostgreSQL 数据库，CRUD 关联查询业务开发。
 | 原文链接：http://book.3fpyao.asia/blog/9025248.sHtMl

原标题：运维笔记：服务器定时任务运维脚本编写
简介：golang md5 sha 加密工具实现，实现 MD5、SHA 哈希工具，做数据摘要，用于签名校验场景。
 | 原文链接：http://book.3fpyao.asia/blog/2443367.sHtMl

原标题：golang redis hyperloglog 基数统计
简介：短信服务封装失败自动重试，封装短信发送组件，处理发送失败自动重试，兼容多短信服务商。
 | 原文链接：http://book.3fpyao.asia/blog/5009794.sHtMl

原标题：golang 系统设计并发控制协程池任务池实现
简介：提交第一个开源 PR 完整流程，Fork 项目、修改代码、提交 Pull Request，讲解 PR 规范，提升合并通过率。
 | 原文链接：http://book.3fpyao.asia/blog/8527711.sHtMl

原标题：golang k8s ingress‑nginx 配置 ssl 证书
简介：golang systemd 配置 go 服务部署，编写 systemd unit 文件管理 go 服务，开机自启、崩溃自动重启。
 | 原文链接：http://book.3fpyao.asia/blog/6622596.sHtMl

原标题：golang 系统设计链路追踪核心概念 trace span 讲解
简介：数据库连接池参数调优，调整连接池最大最小连接数，空闲超时，避免连接耗尽或者资源浪费。
 | 原文链接：http://book.3fpyao.asia/blog/1217163.sHtMl

原标题：golang 系统设计大事务拆分实战思路
简介：golang html 模板渲染简单示例，Go HTML 模板渲染，服务端渲染页面，填充数据输出 HTML 页面。
 | 原文链接：http://book.3fpyao.asia/blog/1977979.sHtMl

原标题：golang mongodb 文档结构设计原则
简介：golang 分库分表 id 路由规则设计，分库分表 id 路由算法，id 映射库表，数据均匀打散避免热点分片。
 | 原文链接：http://book.3fpyao.asia/blog/5291021.sHtMl

原标题：golang 系统设计序列化性能选型对比
简介：golang 分布式锁 redis 实现，基于 Redis 实现 Go 分布式锁，解决多实例并发竞争资源问题。
 | 原文链接：http://book.3fpyao.asia/blog/3109618.sHtMl

原标题：golang 系统设计开源项目依赖版本升级维护
简介：数据库连接池参数调优，调整连接池最大最小连接数，空闲超时，避免连接耗尽或者资源浪费。
 | 原文链接：http://book.3fpyao.asia/blog/6464980.sHtMl

原标题：操作系统内核版本适配服务
简介：golang time 时间格式化参考时间牢记，2006‑01‑02T15:04:05Z07:00，掌握 go 时间格式化关键点。
 | 原文链接：http://book.3fpyao.asia/blog/4224577.sHtMl

原标题：Security：RPC调用身份认证安全加固
简介：golang smtp 邮件发送完整示例，调用 smtp 服务发送文本与 html 格式邮件，实现邮件通知能力。
 | 原文链接：http://book.3fpyao.asia/blog/2686654.sHtMl

原标题：新手向：项目目录结构规范与含义解析
简介：轻量 API 后端接口服务快速开发，快速搭建简易 API 服务，实现基础接口能力，快速支撑小型业务需求。
 | 原文链接：http://book.3fpyao.asia/blog/2081338.sHtMl

原标题：golang redis 分布式锁 redisson 思路
简介：golang grpc keepalive 保活配置，grpc keepalive 参数调优，检测断开僵死连接，释放无效连接资源。
 | 原文链接：http://book.3fpyao.asia/blog/8705316.sHtMl

原标题：golang 系统设计结构化日志字段规范约定
简介：golang go 模板执行错误捕获，捕获模板执行错误，防止模板错误直接返回空白页面。
 | 原文链接：http://book.3fpyao.asia/blog/8139201.sHtMl

原标题：golang docker 运行 etcd 本地测试
简介：前端错误监控上报系统搭建，搭建前端错误监控，捕获页面 JS 错误，上报后端，快速发现线上页面 bug。
 | 原文链接：http://book.3fpyao.asia/blog/3771712.sHtMl

原标题：golang 系统设计架构图绘图工具选型对比
简介：golang consul 服务发现简单示例，对接 Consul 实现服务注册发现，微服务实例自动感知。
 | 原文链接：http://book.3fpyao.asia/blog/2617139.sHtMl

原标题：Hands‑on：简易反向代理中间件实现
简介：前端权限路由动态生成实现，根据后端返回权限，动态生成前端路由菜单，实现页面权限控制。
 | 原文链接：http://book.3fpyao.asia/blog/2795853.sHtMl

原标题：golang 系统设计压测工具 wrk 使用实操
简介：golang os 环境变量读取设置，os.Getenv os.Setenv os.Unsetenv 读写环境变量，环境变量多值处理。
 | 原文链接：http://book.3fpyao.asia/blog/3838017.sHtMl

原标题：golang jwt 过期刷新 token 实现
简介：热更新开发环境配置教程，配置代码热重载，修改代码无需重启服务立即生效，大幅提升本地开发调试效率。
 | 原文链接：http://book.3fpyao.asia/blog/0222429.sHtMl

原标题：部署实践：服务器防火墙安全组配置实践
简介：服务器 Swap 关闭提升响应速度，关闭服务器 Swap 交换分区，避免内存交换磁盘拖慢程序响应性能。
 | 原文链接：http://book.3fpyao.asia/blog/3232629.sHtMl

三、实战开发｜Practice
原标题：Troubleshoot：跨库关联查询，性能急剧恶化
简介：golang go 爬虫异步并发抓取，协程池控制并发抓取网页，多协程采集，提升爬虫采集速度。
 | 原文链接：http://book.3fpyao.asia/blog/8648939.sHtMl

原标题：golang 系统设计海量数据分页查询
简介：Git LFS 大文件推送失败解决，配置 Git LFS，处理仓库大文件，解决大文件推送报错推送失败。
 | 原文链接：http://book.3fpyao.asia/blog/9161992.sHtMl

原标题：踩坑记录：乐观锁版本号处理不当更新失败
简介：批量异步处理系统业务落地，构建批量异步处理系统，把耗时业务异步化，提升接口响应速度。
 | 原文链接：http://book.3fpyao.asia/blog/6106811.sHtMl

原标题：WSL 搭建 Windows Linux 开发环境
简介：配置与镜像分离防止信息泄露，业务配置不打包进镜像，外部挂载配置，避免密钥配置随镜像泄露。
 | 原文链接：http://book.3fpyao.asia/blog/1186820.sHtMl

原标题：golang redis 布隆过滤器安装使用
简介：golang 路径处理 filepath 包规范写法，使用 filepath 处理路径拼接分割，自动适配操作系统路径分隔符。
 | 原文链接：http://book.3fpyao.asia/blog/2090535.sHtMl

原标题：坑点：版本号语义化理解错误依赖版本错乱
简介：golang os 文件权限 mode，os.FileMode 文件权限，读写执行权限位，跨平台权限注意事项。
 | 原文链接：http://book.3fpyao.asia/blog/2848831.sHtMl

原标题：避坑：正则回溯引发CPU占满DoS风险
简介：golang k8s 客户端 client‑go 简单示例，client‑go 操作 k8s 资源，增删改查 pod deployment 等资源对象。
 | 原文链接：http://book.3fpyao.asia/blog/7065177.sHtMl

原标题：方案对比：同步事务vs事务消息最终一致性
简介：monorepo 项目多包管理最佳实践，monorepo 仓库管理多子包，统一版本管理，处理包之间互相依赖。
 | 原文链接：http://book.3fpyao.asia/blog/1224351.sHtMl

原标题：方案设计：统一错误处理架构全链路方案
简介：golang 滑动窗口限流算法 go 实现，滑动窗口限流，解决固定窗口临界流量突增漏洞，限流更精准。
 | 原文链接：http://book.3fpyao.asia/blog/5679820.sHtMl

原标题：部署实践：容器时区统一配置解决方案
简介：golang grpc 拦截器开发鉴权日志，开发 grpc 服务端拦截器，统一做鉴权、日志打印、异常捕获处理。
 | 原文链接：http://book.3fpyao.asia/blog/5664302.sHtMl

原标题：慢查询分析索引调优数据库实战
简介：ORM 框架数据库增删改查实操，使用 ORM 框架完成数据库基础操作，减少手写 SQL，简化业务层数据库交互代码。
 | 原文链接：http://book.3fpyao.asia/blog/3860834.sHtMl

原标题：golang 系统设计唯一索引业务使用场景
简介：﻿从零搭建本地开发环境完整教程，手把手完成环境配置，梳理踩坑点，帮助开发者快速搭建可用的本地开发环境，降低上手成本。
 | 原文链接：http://book.3fpyao.asia/blog/9354460.sHtMl

原标题：容器软链接文件权限修复
简介：Redis 热点 key 拆分降低集群压力，拆分访问量极高的热点 Key，分散请求压力，避免 Redis 节点压力过高。
 | 原文链接：http://book.3fpyao.asia/blog/1280965.sHtMl

原标题：golang 系统设计分布式配置中心思路
简介：golang go math 大数高精度计算，math/big 处理超大整数、高精度浮点数，金额大数运算。
 | 原文链接：http://book.3fpyao.asia/blog/9805076.sHtMl

原标题：golang 系统设计分库分表扩容平滑迁移
简介：前端静态缓存更新生效处理，修改静态资源版本标识，处理浏览器强缓存，让更新资源生效。
 | 原文链接：http://book.3fpyao.asia/blog/0977767.sHtMl

原标题：nodejs 内存溢出问题排查修复
简介：golang sort 稳定排序 Stable，稳定排序保留相等元素原有顺序，业务需要稳定排序场景。
 | 原文链接：http://book.3fpyao.asia/blog/5912981.sHtMl

原标题：Nginx 请求头大小上限调整
简介：项目依赖安全扫描漏洞防范，扫描项目第三方依赖包，修复存在安全漏洞依赖，防范供应链攻击。
 | 原文链接：http://book.3fpyao.asia/blog/9385045.sHtMl

原标题：golang 系统设计网关 websocket 转发配置要点
简介：golang go decimal 定点小数金额计算，decimal 库处理金额，规避 float64 精度丢失，财务计算。
 | 原文链接：http://book.3fpyao.asia/blog/2726865.sHtMl

原标题：方案对比：几种任务队列架构选型优缺点
简介：从零编写简易 CLI 命令行工具，通过实战案例实现基础命令交互，理解命令行程序执行逻辑，产出可运行小工具。
 | 原文链接：http://book.3fpyao.asia/blog/0110936.sHtMl

原标题：跨平台 uniapp 多端开发实操
简介：golang hertz http 框架快速上手，hertz 高性能 http 框架，路由中间件参数校验快速开发接口服务。
 | 原文链接：http://book.3fpyao.asia/blog/6099863.sHtMl

原标题：坑点：gitreset误删本地代码恢复方案
简介：golang 高并发下锁优化减少竞争，减小锁粒度，读写锁替换互斥锁，无锁编程降低锁竞争开销。
 | 原文链接：http://book.3fpyao.asia/blog/2030439.sHtMl

原标题：golang 系统设计 protobuf 可选字段使用技巧
简介：golang rsa 签名验签 pem 证书加载，加载 pem 格式密钥证书，rsa 签名与验签完整业务实现。
 | 原文链接：http://book.3fpyao.asia/blog/7200356.sHtMl

原标题：golang 系统设计内部服务调用超时设置要点
简介：站内邮件消息通知功能开发，实现站内消息、邮件通知推送，业务事件触发通知，提醒用户业务状态变更。
 | 原文链接：http://book.3fpyao.asia/blog/3802889.sHtMl

原标题：后端分页查询逻辑代码实现
简介：golang 限制 multipart 内存大小，设置 MaxMemory，大文件写入磁盘临时文件防止内存暴涨。
 | 原文链接：http://book.3fpyao.asia/blog/6129638.sHtMl

原标题：跨平台换行符统一异常修复
简介：golang go‑zero 框架项目快速搭建，go‑zero 脚手架生成微服务项目，api rpc 服务快速开发。
 | 原文链接：http://book.3fpyao.asia/blog/6209427.sHtMl

原标题：部署实践：Nginx反向代理传递真实客户端IP
简介：OOMKilled 容器被杀完整排查，排查容器被 OOM 终止完整流程，区分程序内存泄露和容器内存限制过小。
 | 原文链接：http://book.3fpyao.asia/blog/5908147.sHtMl

原标题：接口请求重试容错机制实现
简介：golang 反向代理 http 服务开发，手写简易 http 反向代理，转发请求，修改请求头响应头。
 | 原文链接：http://book.3fpyao.asia/blog/6006570.sHtMl

原标题：踩坑记录：数值溢出造成业务ID错乱异常
简介：golang cgo 性能开销避坑指南，cgo 调用开销，减少频繁 cgo 调用，规避 cgo 带来内存泄漏风险。
 | 原文链接：http://book.3fpyao.asia/blog/4805731.sHtMl

原标题：记一次内存Swap被大量使用系统响应缓慢
简介：项目目录结构规范化最佳实践，梳理源码、配置、静态资源目录划分，规范项目布局，提升代码可读性和可维护性。
 | 原文链接：http://book.3fpyao.asia/blog/0368542.sHtMl

原标题：golang 系统设计 protobuf oneof 类型业务场景
简介：Shell 运维脚本服务器效率提升，编写常用运维 Shell 脚本，自动化服务器运维操作，减少手工重复工作。
 | 原文链接：http://book.3fpyao.asia/blog/8242464.sHtMl

原标题：Practice：实现数据库连接池简易模拟实现
简介：golang 异步任务队列 worker 池开发，任务入数据库或 redis，worker 池消费执行，异步处理耗时业务。
 | 原文链接：http://book.3fpyao.asia/blog/3711531.sHtMl

原标题：实践：代码提交前自动格式化校验配置实践
简介：golang go 爬虫请求速率控制，爬虫限频、代理轮换，设置 UA，防止爬虫被目标站点封禁 IP。
 | 原文链接：http://book.3fpyao.asia/blog/5456482.sHtMl

原标题：golang 系统设计 io 瓶颈磁盘网络优化实践
简介：golang go proxy 私有代理配置，配置 go proxy 私有代理，加速依赖下载，内网环境构建项目。
 | 原文链接：http://book.3fpyao.asia/blog/9031348.sHtMl

原标题：golang redis 地理位置 geo 使用
简介：golang go 优雅处理信号丢失场景，处理信号丢失、信号被忽略，保障程序可以正常接收终止信号。
 | 原文链接：http://book.3fpyao.asia/blog/4450978.sHtMl

原标题：版本升级服务启动失败处理
简介：golang 布隆过滤器实现去重，Go 实现布隆过滤器，海量数据去重，节省内存开销，提升判断效率。
 | 原文链接：http://book.3fpyao.asia/blog/3350543.sHtMl

原标题：安全实践：防止JSON解析漏洞恶意payload
简介：golang gin 中间件执行顺序讲解，理解 Gin 中间件注册顺序，区分前置后置逻辑，规避中间件顺序 bug。
 | 原文链接：http://book.3fpyao.asia/blog/6736420.sHtMl

原标题：部署实践：Nginx反向代理传递真实客户端IP
简介：系统字符集统一乱码修复，统一数据库、程序、操作系统字符集，解决中文乱码显示异常问题。
 | 原文链接：http://book.3fpyao.asia/blog/7830429.sHtMl

原标题：项目实践：实现数据脱敏组件支持多种脱敏规则
简介：前端错误监控上报系统搭建，搭建前端错误监控，捕获页面 JS 错误，上报后端，快速发现线上页面 bug。
 | 原文链接：http://book.3fpyao.asia/blog/6100386.sHtMl

原标题：预编译 SQL 防注入实现
简介：大事务拆分回滚日志暴涨解决，拆分大型数据库事务，减少回滚日志生成量，避免磁盘被回滚日志占满。
 | 原文链接：http://book.3fpyao.asia/blog/7938776.sHtMl

原标题：项目实践：Docker多环境镜像构建策略实践
简介：Spring 事务传播机制配置生效，理解事务传播行为，正确配置，修复事务不生效、事务失效的业务 bug。
 | 原文链接：http://book.3fpyao.asia/blog/9986000.sHtMl

四、架构设计｜Architecture
原标题：golang 系统设计分布式锁红锁优缺点梳理
简介：golang udp 服务端客户端开发示例，golang 实现 UDP 服务收发数据包，实现 udp 协议通信程序。
 | 原文链接：http://book.3fpyao.asia/blog/2727796.sHtMl

原标题：Security：服务器最小权限账号运维实践
简介：golang go 逃逸分析实操查看，go build‑gcflags=-m 查看逃逸分析，减少堆分配优化程序性能。
 | 原文链接：http://book.3fpyao.asia/blog/1897135.sHtMl

原标题：Docker 容器时区错误修复方案
简介：golang 字符串处理常用技巧汇总，字符串拼接、分割、替换、类型转换实操，规避字符串高频错误。
 | 原文链接：http://book.3fpyao.asia/blog/6836429.sHtMl

原标题：golang redis pipeline 批量操作
简介：golang sync/atomic 原子操作使用注意，理解原子操作内存顺序，规避原子操作错误使用带来 bug。
 | 原文链接：http://book.3fpyao.asia/blog/1066464.sHtMl

原标题：性能复盘：热点key导致RedisCPU飙升优化
简介：golang go sum 校验失败处理方案，go sum 校验不匹配，排查网络代理，清理缓存解决校验报错。
 | 原文链接：http://book.3fpyao.asia/blog/0244434.sHtMl

原标题：开源实践：Fork上游项目，持续同步更新代码
简介：nodejs 进程间通信 IPC 实操，演示 Node.js 主进程子进程 IPC 通信，进程之间传递消息数据。
 | 原文链接：http://book.3fpyao.asia/blog/9641372.sHtMl

原标题：golang docker compose 依赖启动顺序
简介：golang go 测试 t.Run 子测试分组，t.Run 实现子测试，分组执行用例，输出分组测试结果。
 | 原文链接：http://book.3fpyao.asia/blog/9776945.sHtMl

原标题：实战项目：Nginx限速、限流、防爬虫配置实践
简介：golang 单元测试 mock http 请求，mock HTTP 外部接口，单元测试不依赖外部网络，保证用例稳定运行。
 | 原文链接：http://book.3fpyao.asia/blog/1573309.sHtMl

原标题：golang es 聚合统计查询实现
简介：golang fasthttp 客户端连接池调优，fasthttp 客户端连接池配置，复用连接提升请求性能。
 | 原文链接：http://book.3fpyao.asia/blog/1809652.sHtMl

原标题：golang 系统设计防爬虫简单策略
简介：golang http 中间件洋葱模型原理，理解 go http 中间件洋葱模型，请求响应流转顺序，编写自定义中间件。
 | 原文链接：http://book.3fpyao.asia/blog/0449578.sHtMl

原标题：golang k8s 节点污点容忍度配置
简介：文件句柄耗尽资源泄露处理，定位文件句柄泄露，修复文件忘记关闭问题，解决句柄耗尽服务报错。
 | 原文链接：http://book.3fpyao.asia/blog/6824138.sHtMl

原标题：配置与镜像分离防止信息泄露
简介：文件描述符优化进程卡死修复，及时关闭文件句柄，控制打开文件数量，解决文件句柄耗尽进程卡死。
 | 原文链接：http://book.3fpyao.asia/blog/8220941.sHtMl

原标题：复盘总结：系统压测报告模板与分析思路
简介：golang kitex 超时重试熔断配置，kitex 配置调用超时、重试、熔断策略，保障微服务调用稳定性。
 | 原文链接：http://book.3fpyao.asia/blog/3845574.sHtMl

原标题：golang k8s 监控 prometheus 部署
简介：golang sync/atomic 原子操作使用注意，理解原子操作内存顺序，规避原子操作错误使用带来 bug。
 | 原文链接：http://book.3fpyao.asia/blog/3779229.sHtMl

原标题：部署复盘：配置热更新不用重启服务方案
简介：Docker 容器时区错误修复方案，修复 Docker 容器内部时区偏差，解决容器内时间不对引发业务逻辑异常。
 | 原文链接：http://book.3fpyao.asia/blog/1324169.sHtMl

原标题：排错：对象存储跨域配置不生效前端上传失败
简介：golang os 环境变量读取设置，os.Getenv os.Setenv os.Unsetenv 读写环境变量，环境变量多值处理。
 | 原文链接：http://book.3fpyao.asia/blog/3902292.sHtMl

原标题：golang docker compose 本地开发最佳实践
简介：hosts 配置本地回环访问修复，修改 hosts 配置，修复 127.0.0.1 解析异常，本地服务访问失败问题。
 | 原文链接：http://book.3fpyao.asia/blog/5981246.sHtMl

原标题：golang k8s hpa 水平 pod 自动扩缩容
简介：Docker 网络模式容器互通设置，选择合适 Docker 网络模式，实现容器之间网络互相访问通信。
 | 原文链接：http://book.3fpyao.asia/blog/3183191.sHtMl

?
