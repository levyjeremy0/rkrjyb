最新前沿技术资讯

一、入门教程｜Getting Started
原标题：golang 系统设计告警风暴抑制方案实现
简介：前端权限路由动态生成实现，根据后端返回权限，动态生成前端路由菜单，实现页面权限控制。
 | 原文链接：http://wiki.gp9zy7.asia/arts/638028.Doc

原标题：Troubleshoot：RPC序列化对象字段增减兼容踩坑
简介：golang go 基准测试 benchmark 编写，Benchmark 性能基准测试，测量函数执行耗时内存分配情况。
 | 原文链接：http://wiki.gp9zy7.asia/arts/106518.Doc

原标题：避坑：Nginx配置错误导致请求丢失Header
简介：golang go 服务压测前后性能对比，压测记录 QPS 延迟，优化前后对比，验证优化效果。
 | 原文链接：http://wiki.gp9zy7.asia/arts/723175.Doc

原标题：多实例部署 Session 共享方案
简介：RPC 报文大小上限调优大请求，调大 RPC 框架报文最大限制，支持传输大体积请求报文不被截断。
 | 原文链接：http://wiki.gp9zy7.asia/arts/018332.Doc

原标题：golang ip 限流黑名单实现方案
简介：golang go select 多路等待 channel，select 等待多个 channel，default 非阻塞，超时等待 channel。
 | 原文链接：http://wiki.gp9zy7.asia/arts/730784.Doc

原标题：gRPC 服务端客户端入门示例
简介：golang 配置中心 apollo go 客户端，apollo go sdk 读取配置，配置变更自动热更新无需重启服务。
 | 原文链接：http://wiki.gp9zy7.asia/arts/542706.Doc

原标题：部署实践：多实例服务部署无状态改造
简介：golang http 文件下载断点续传服务，服务端实现断点续传，支持大文件分段下载，提升大文件下载稳定性。
 | 原文链接：http://wiki.gp9zy7.asia/arts/675743.Doc

原标题：golang 系统设计密码存储哈希加盐实现
简介：golang minio 私有对象存储开发，minio s3 对象存储，bucket 管理，文件上传下载权限设置。
 | 原文链接：http://wiki.gp9zy7.asia/arts/537446.Doc

原标题：项目实践：本地模拟缓存失效风暴验证防护
简介：简易日志收集集中管理方案，搭建轻量日志收集方案，把多服务日志汇总，集中检索查看日志信息。
 | 原文链接：http://wiki.gp9zy7.asia/arts/503037.Doc

原标题：架构复盘：多级缓存架构，本地缓存+分布式缓存
简介：golang 子进程执行命令标准流处理，exec.Command 执行外部命令，处理 stdout stderr，防止缓冲区阻塞卡死。
 | 原文链接：http://wiki.gp9zy7.asia/arts/426253.Doc

原标题：部署复盘：服务启动顺序依赖处理方案
简介：golang 云存储 s3 协议对象存储，go s3 客户端，兼容 minio 阿里云 oss，实现文件上传下载签名访问。
 | 原文链接：http://wiki.gp9zy7.asia/arts/314819.Doc

原标题：设计思考：API网关和BFF职责边界划分
简介：golang grpc keepalive 保活配置，grpc keepalive 参数调优，检测断开僵死连接，释放无效连接资源。
 | 原文链接：http://wiki.gp9zy7.asia/arts/271702.Doc

原标题：golang 系统设计 git 钩子自动化校验实现
简介：golang io.Reader io.Writer 接口理解，io 读写接口，各类数据源统一抽象，适配 io 复制函数。
 | 原文链接：http://wiki.gp9zy7.asia/arts/575284.Doc

原标题：内网测试服务搭建团队调试
简介：golang 高并发下锁优化减少竞争，减小锁粒度，读写锁替换互斥锁，无锁编程降低锁竞争开销。
 | 原文链接：http://wiki.gp9zy7.asia/arts/133782.Doc

原标题：快速上手简易网关转发逻辑模拟
简介：golang cpu pprof 性能分析实操，使用 pprof 采集 CPU 性能数据，定位 CPU 高占用函数，做性能优化。
 | 原文链接：http://wiki.gp9zy7.asia/arts/859278.Doc

原标题：golang 系统设计 traceId 全链路透传完整方案
简介：golang strings.Builder 字符串高效拼接，strings.Builder 做字符串拼接，比 += 性能更高，减少内存拷贝。
 | 原文链接：http://wiki.gp9zy7.asia/arts/450369.Doc

原标题：golang 系统设计接口频率限制业务落地
简介：大事务拆分防止连接池耗尽，将执行时间很长的大事务拆分为小事务，减少事务占用连接时长。
 | 原文链接：http://wiki.gp9zy7.asia/arts/458496.Doc

原标题：全量回归测试提升代码质量
简介：nodejs 全局异常捕获进程防护，捕获未捕获异常与 Promise 拒绝，尽量保护进程不因为异常直接退出。
 | 原文链接：http://wiki.gp9zy7.asia/arts/015534.Doc

原标题：排错：GitLFS大文件推送失败完整排障
简介：ICMP 放通网络丢包问题修复，放开 ICMP 协议，解决 MTU 问题导致网络丢包，修复网络不稳定现象。
 | 原文链接：http://wiki.gp9zy7.asia/arts/861169.Doc

原标题：快速入门简单签名校验实现思路
简介：接口幂等性防重复请求实现，实现接口幂等逻辑，避免重复提交请求产生多条脏数据，保障业务数据安全。
 | 原文链接：http://wiki.gp9zy7.asia/arts/270319.Doc

原标题：DevOps：多阶段构建Dockerfile最佳实践
简介：GET POST 接口请求参数处理，讲解两种请求方式参数传递区别，演示参数接收、解析、校验，适配不同接口调用场景。
 | 原文链接：http://wiki.gp9zy7.asia/arts/381803.Doc

原标题：golang cpu pprof 性能分析实操
简介：golang go 模板执行错误捕获，捕获模板执行错误，防止模板错误直接返回空白页面。
 | 原文链接：http://wiki.gp9zy7.asia/arts/908381.Doc

原标题：golang mysql 存储过程简单使用
简介：﻿从零搭建本地开发环境完整教程，手把手完成环境配置，梳理踩坑点，帮助开发者快速搭建可用的本地开发环境，降低上手成本。
 | 原文链接：http://wiki.gp9zy7.asia/arts/322313.Doc

原标题：方案设计：多租户系统架构三种实现模式对比
简介：golang go 泛型约束与类型集合，泛型 type set 约束，限制泛型支持类型，写出安全泛型代码。
 | 原文链接：http://wiki.gp9zy7.asia/arts/729287.Doc

原标题：golang 系统设计内存高占用排查思路
简介：echarts 大数据渲染性能调优，大数据量 ECharts 图表调优，数据采样、分片渲染，解决图表卡顿。
 | 原文链接：http://wiki.gp9zy7.asia/arts/455006.Doc

原标题：一次数据库死锁现场分析与解决方案记录
简介：golang gin 静态资源访问配置，Gin 配置静态资源目录，直接对外提供静态文件访问服务。
 | 原文链接：http://wiki.gp9zy7.asia/arts/421559.Doc

原标题：golang mysql 防止 sql 注入实践
简介：golang 探测文件真实内容类型，读取文件头部字节判断真实文件格式，规避后缀伪造。
 | 原文链接：http://wiki.gp9zy7.asia/arts/496132.Doc

原标题：复盘总结：数据库迁移升级风险评估清单
简介：golang go 值传递引用传递理解，go 全部为值传递，指针本质拷贝指针值，理清参数传递行为。
 | 原文链接：http://wiki.gp9zy7.asia/arts/499601.Doc

原标题：Practice：从零实现轻量后端接口服务完整实践
简介：提交第一个开源 PR 完整流程，Fork 项目、修改代码、提交 Pull Request，讲解 PR 规范，提升合并通过率。
 | 原文链接：http://wiki.gp9zy7.asia/arts/780568.Doc

原标题：DevOps：WSL2生产环境使用风险提示
简介：golang tcp 四次挥手 go 程序行为，理解 tcp 四次挥手，处理连接关闭、重置、RST 包异常场景。
 | 原文链接：http://wiki.gp9zy7.asia/arts/095280.Doc

原标题：golang 项目目录分层规范设计
简介：HTTPS 证书过期更新操作，检测 HTTPS 证书到期，更新证书文件，恢复 HTTPS 服务正常访问。
 | 原文链接：http://wiki.gp9zy7.asia/arts/456455.Doc

原标题：快速入门简单签名校验实现思路
简介：服务器 Swap 关闭提升响应速度，关闭服务器 Swap 交换分区，避免内存交换磁盘拖慢程序响应性能。
 | 原文链接：http://wiki.gp9zy7.asia/arts/338413.Doc

原标题：快速入门YAML配置文件语法与示例
简介：golang sync.Map 适用场景与性能对比，读多写少，离散 key，对比普通 map 加锁性能差异。
 | 原文链接：http://wiki.gp9zy7.asia/arts/366765.Doc

原标题：CI 持续集成自动构建流程
简介：golang go 信号处理优雅重启实现，USR2 触发程序重启，不关闭监听 socket 实现零停机升级。
 | 原文链接：http://wiki.gp9zy7.asia/arts/050645.Doc

原标题：golang 告警推送钉钉机器人实现
简介：golang strings.Builder 字符串高效拼接，strings.Builder 做字符串拼接，比 += 性能更高，减少内存拷贝。
 | 原文链接：http://wiki.gp9zy7.asia/arts/245369.Doc

原标题：Hands‑on：编写自定义Git钩子实现代码提交校验
简介：多版本开发环境共存配置，实现同一工具多版本并存，快速切换不同版本，适配不同项目对版本的差异化需求。
 | 原文链接：http://wiki.gp9zy7.asia/arts/194816.Doc

原标题：Hands‑on：简易配置热更新组件开发实践
简介：网络读取超时设置连接挂起防护，设置网络读取超时时间，防止请求无限挂起不返回，占用连接资源。
 | 原文链接：http://wiki.gp9zy7.asia/arts/812111.Doc

原标题：设计思考：系统容量评估架构前期估算思路
简介：golang 系统调用跟踪 strace 排查 go 程序，strace 跟踪系统调用，定位文件网络 IO 慢的底层原因。
 | 原文链接：http://wiki.gp9zy7.asia/arts/748130.Doc

原标题：golang 系统设计并发控制协程池任务池实现
简介：nodejs 内存溢出问题排查修复，Node.js 程序 OOM 排查流程，定位内存泄露，调整内存限制修复崩溃。
 | 原文链接：http://wiki.gp9zy7.asia/arts/941544.Doc

原标题：实战：数据库explain执行计划分析实操演练
简介：golang map 并发读写 panic 解决方案，map 非并发安全，讲解加锁、sync.map 方案解决并发读写崩溃。
 | 原文链接：http://wiki.gp9zy7.asia/arts/374378.Doc


二、踩坑排错｜Troubleshooting
原标题：零基础理解HTTP常用请求头与状态码
简介：golang golangci‑lint 静态代码检查配置，golangci‑lint 静态检查，代码规范检测，提前发现代码隐患。
 | 原文链接：http://wiki.gp9zy7.asia/arts/595698.Doc

原标题：实践：API接口文档自动导出离线文档实践
简介：golang ctx 传递规则不要存结构体，context 作为函数参数传递，禁止放入结构体字段存储。
 | 原文链接：http://wiki.gp9zy7.asia/arts/930002.Doc

原标题：SourceMap 生成线上报错定位
简介：极简 API 网关路由转发实现，开发极简网关服务，完成请求路由转发，理解网关基础实现原理。
 | 原文链接：http://wiki.gp9zy7.asia/arts/362403.Doc

原标题：开源实践：给开源项目写单元测试贡献代码
简介：语义化版本依赖管理防错乱，项目依赖遵循语义版本约束，规避依赖自动升级引入不兼容变更。
 | 原文链接：http://wiki.gp9zy7.asia/arts/673266.Doc

原标题：golang 系统设计分表字段选择路由规则设计
简介：golang go 测试 t.Run 子测试分组，t.Run 实现子测试，分组执行用例，输出分组测试结果。
 | 原文链接：http://wiki.gp9zy7.asia/arts/948549.Doc

原标题：golang 系统设计本地缓存 redis 缓存多级组合
简介：ORM 框架数据库增删改查实操，使用 ORM 框架完成数据库基础操作，减少手写 SQL，简化业务层数据库交互代码。
 | 原文链接：http://wiki.gp9zy7.asia/arts/979656.Doc

原标题：golang 系统设计线上问题复现思路简单讲解
简介：golang go http 文件服务器自定义，http.FileServer 自定义 FileSystem，拦截访问，增加鉴权逻辑。
 | 原文链接：http://wiki.gp9zy7.asia/arts/156940.Doc

原标题：golang 系统设计 tcp 粘包拆包处理方案实现
简介：服务熔断防止故障级联传播，实现服务熔断逻辑，下游故障时快速失败，阻止故障向上游链式扩散。
 | 原文链接：http://wiki.gp9zy7.asia/arts/194015.Doc

原标题：实践：消息队列死信处理业务落地实践
简介：全平台系统环境变量配置，汇总多操作系统环境变量配置方法，统一项目读取逻辑，适配不同运行平台。
 | 原文链接：http://wiki.gp9zy7.asia/arts/799287.Doc

原标题：项目实践：多租户数据隔离三种方案实操对比
简介：golang gorm select 指定查询字段，指定查询字段，避免查询全部字段，减少数据传输，提升查询性能。
 | 原文链接：http://wiki.gp9zy7.asia/arts/207707.Doc

原标题：golang 系统设计监控告警阈值设置思路
简介：golang gorm 事务手动回滚提交，手动控制事务流程，业务异常主动回滚，保障数据操作原子性。
 | 原文链接：http://wiki.gp9zy7.asia/arts/498370.Doc

原标题：Practice：手写简易限流组件，计数器、令牌桶实现
简介：golang go 时间 time.Timer time.Ticker，定时器与周期定时器，Stop Reset 正确使用，防止资源泄漏。
 | 原文链接：http://wiki.gp9zy7.asia/arts/349556.Doc

原标题：golang websocket 服务端开发
简介：golang gin 参数绑定 query form json，掌握 Gin 多种参数绑定方式，适配不同请求格式参数读取。
 | 原文链接：http://wiki.gp9zy7.asia/arts/885942.Doc

原标题：Practice：实现请求body重复读取中间件实践
简介：golang go 模板执行错误捕获，捕获模板执行错误，防止模板错误直接返回空白页面。
 | 原文链接：http://wiki.gp9zy7.asia/arts/615937.Doc

原标题：排错：GitLFS大文件推送失败完整排障
简介：golang ip 限流黑名单实现方案，基于 IP 做限流与黑名单，拦截恶意 IP 访问，保护接口服务。
 | 原文链接：http://wiki.gp9zy7.asia/arts/616107.Doc

原标题：golang git 提交信息规范校验
简介：golang 图片处理 go 图片裁剪压缩，golang 图像处理库，图片缩放裁剪水印，服务端图片处理。
 | 原文链接：http://wiki.gp9zy7.asia/arts/125366.Doc

原标题：设计思考：消息队列重复消费架构层防御手段
简介：API 大版本不兼容平滑迁移，API 版本迭代不兼容旧接口，设计平滑迁移方案，逐步完成版本切换。
 | 原文链接：http://wiki.gp9zy7.asia/arts/233697.Doc

原标题：缓存穿透防护保护数据库
简介：程序预加载加快服务启动速度，把高频使用资源提前预加载，减少请求阶段初始化，加快服务启动。
 | 原文链接：http://wiki.gp9zy7.asia/arts/130433.Doc

原标题：golang 系统设计 debug 远程调试 go 程序实操
简介：WebSocket 聊天室实时通讯开发，基于 WebSocket 搭建简易聊天室，实现多人消息广播实时聊天效果。
 | 原文链接：http://wiki.gp9zy7.asia/arts/193004.Doc

原标题：踩坑：大事务引发数据库连接池耗尽
简介：golang gorm 原生 SQL 执行处理，复杂场景执行原生 SQL，处理返回结果集，兼顾性能与灵活性。
 | 原文链接：http://wiki.gp9zy7.asia/arts/831042.Doc

原标题：性能复盘：内存泄漏定位，内存持续上涨优化
简介：前端错误监控上报系统搭建，搭建前端错误监控，捕获页面 JS 错误，上报后端，快速发现线上页面 bug。
 | 原文链接：http://wiki.gp9zy7.asia/arts/605444.Doc

原标题：SDK 版本兼容线上崩溃修复
简介：定时任务周期调度 demo 开发，实现简单定时调度程序，按时间周期执行业务逻辑，理解定时任务运行机制。
 | 原文链接：http://wiki.gp9zy7.asia/arts/195485.Doc

原标题：golang mysql 字符集排序规则设置
简介：前端权限路由动态生成实现，根据后端返回权限，动态生成前端路由菜单，实现页面权限控制。
 | 原文链接：http://wiki.gp9zy7.asia/arts/045072.Doc

原标题：golang k8s devops 流水线简单思路
简介：Git 分支管理多人协作实战教程，详解分支创建、合并、冲突处理，适配团队开发场景，规范多人协同代码工作流。
 | 原文链接：http://wiki.gp9zy7.asia/arts/077563.Doc

原标题：开发记录：网关实现接口鉴权、限流、日志打印
简介：golang 配置文件多格式兼容加载，同时支持 yaml toml json 多种格式配置文件，灵活适配不同部署环境。
 | 原文链接：http://wiki.gp9zy7.asia/arts/817717.Doc

原标题：运维笔记：服务器定时任务运维脚本编写
简介：golang 错误处理最佳实践汇总，Go 错误处理规范，包装错误，堆栈携带，拒绝简单忽略错误。
 | 原文链接：http://wiki.gp9zy7.asia/arts/533600.Doc

原标题：golang http grpc 全链路埋点示例
简介：golang 图片处理 go 图片裁剪压缩，golang 图像处理库，图片缩放裁剪水印，服务端图片处理。
 | 原文链接：http://wiki.gp9zy7.asia/arts/072033.Doc

原标题：实战项目：搭建本地Mock服务快速开发联调
简介：golang consul 服务发现简单示例，对接 Consul 实现服务注册发现，微服务实例自动感知。
 | 原文链接：http://wiki.gp9zy7.asia/arts/989996.Doc

原标题：零基础理解模块化与组件化基础思想
简介：百万数据 Excel 导出内存优化，优化大 Excel 导出逻辑，流式输出，避免一次性加载全部数据造成 OOM。
 | 原文链接：http://wiki.gp9zy7.asia/arts/593672.Doc

原标题：golang 系统设计日志本地打印线上关闭调试信息
简介：golang makefile 多平台编译脚本，makefile 一键交叉编译多平台二进制，打包镜像，执行测试。
 | 原文链接：http://wiki.gp9zy7.asia/arts/657679.Doc

原标题：golang 系统设计密码存储哈希加盐实现
简介：golang go regexp 正则预编译，regexp.MustCompile 预编译正则，不要循环内部编译正则，节省 CPU。
 | 原文链接：http://wiki.gp9zy7.asia/arts/878084.Doc

原标题：golang rate‑limiter 限流组件
简介：前端工程化 webpack 打包优化，针对 webpack 项目做打包调优，分包、压缩、Tree‑Shaking，缩减包体积。
 | 原文链接：http://wiki.gp9zy7.asia/arts/126814.Doc

原标题：Practice：实现多级缓存本地缓存+Redis实践
简介：golang go proxy 私有代理配置，配置 go proxy 私有代理，加速依赖下载，内网环境构建项目。
 | 原文链接：http://wiki.gp9zy7.asia/arts/592846.Doc

原标题：CI 构建缓存加速编译速度
简介：浏览器缓存强制刷新方案，设置 HTTP 缓存头，处理浏览器缓存旧静态资源，让用户加载更新后的页面。
 | 原文链接：http://wiki.gp9zy7.asia/arts/537515.Doc

原标题：golang 系统信号信号量处理
简介：golang go http 安全头配置实践，设置 http 安全响应头，防范 XSS、点击劫持，提升 web 服务安全性。
 | 原文链接：http://wiki.gp9zy7.asia/arts/088103.Doc

原标题：nodejs 单元测试 jest 实操教程
简介：golang kitex 超时重试熔断配置，kitex 配置调用超时、重试、熔断策略，保障微服务调用稳定性。
 | 原文链接：http://wiki.gp9zy7.asia/arts/920337.Doc

原标题：golang etcd 配置中心简单使用
简介：golang time 时间比较 Before After Equal，时间比较不要直接减，使用内置方法判断时间先后。
 | 原文链接：http://wiki.gp9zy7.asia/arts/498852.Doc

原标题：实战：Docker资源监控查看容器状态实操
简介：Nginx 静态代理负载均衡全套配置，一套 Nginx 配置示例，覆盖静态资源、反向代理、负载均衡场景。
 | 原文链接：http://wiki.gp9zy7.asia/arts/788116.Doc

原标题：快速入门对象存储基础使用场景
简介：golang go 项目工程目录布局标准，不同规模 go 项目目录结构，小型项目中型项目大型微服务项目布局。
 | 原文链接：http://wiki.gp9zy7.asia/arts/101922.Doc

原标题：性能复盘：内存泄漏定位，内存持续上涨优化
简介：JWT 工具封装令牌刷新过期，封装 JWT 工具类，实现令牌生成、校验、过期刷新整套令牌管理逻辑。
 | 原文链接：http://wiki.gp9zy7.asia/arts/009930.Doc

三、实战开发｜Practice
原标题：安全复盘：OAuth2授权流程安全坑点汇总
简介：配置外部化线上部署防错误，把配置从代码剥离，外部传入配置，修改配置不需要重新打包构建。
 | 原文链接：http://wiki.gp9zy7.asia/arts/593678.Doc

原标题：golang 系统设计代码仓库权限管理方案
简介：golang time.After 内存泄漏场景，for 循环使用 time.After 会创建大量 timer，造成内存泄漏。
 | 原文链接：http://wiki.gp9zy7.asia/arts/108712.Doc

原标题：HTTP 状态码请求头完整梳理
简介：golang aes 对称加密解密示例，AES 对称加密解密实现，业务敏感数据加密存储传输。
 | 原文链接：http://wiki.gp9zy7.asia/arts/088377.Doc

原标题：新手向：开源项目本地构建失败通用排查步骤
简介：文件分片上传断点续传功能，实现文件分片上传，记录上传进度，支持断点续传大文件上传。
 | 原文链接：http://wiki.gp9zy7.asia/arts/184777.Doc

原标题：Performance：数据库大表优化，冷热数据分离
简介：前端下载导出文件功能实现，前端实现文件流下载导出，处理异常，适配浏览器不同下载行为。
 | 原文链接：http://wiki.gp9zy7.asia/arts/145111.Doc

原标题：排错：CI流水线构建失败，日志无明确报错
简介：golang 限流器熔断降级组合使用，限流熔断降级组合架构，流量防护完整方案，保障服务稳定性。
 | 原文链接：http://wiki.gp9zy7.asia/arts/516884.Doc

原标题：Troubleshoot：跨库关联查询，性能急剧恶化
简介：golang 子进程执行命令标准流处理，exec.Command 执行外部命令，处理 stdout stderr，防止缓冲区阻塞卡死。
 | 原文链接：http://wiki.gp9zy7.asia/arts/808522.Doc

原标题：Issue：防火墙拦截ICMP，MTU问题网络丢包
简介：golang time 时间格式化避坑，Go 时间格式化参考时间牢记，处理时间解析格式化，解决时间输出错乱。
 | 原文链接：http://wiki.gp9zy7.asia/arts/538404.Doc

原标题：golang k8s 监控 prometheus 部署
简介：react 状态管理方案选型对比，对比 Redux、Zustand 等 React 状态管理库，分析适用业务场景辅助选型。
 | 原文链接：http://wiki.gp9zy7.asia/arts/161776.Doc

原标题：Debug：表单自动转义特殊字符业务逻辑出错
简介：golang accept 错误循环崩溃处理，accept 返回系统错误，处理临时错误，避免死循环占满 CPU。
 | 原文链接：http://wiki.gp9zy7.asia/arts/715124.Doc

原标题：Hands‑on：模拟RPC超时重试业务异常场景
简介：golang httptest 模拟 http 请求单元测试，httptest 模拟 http 请求，测试 http handler 逻辑不用启动服务。
 | 原文链接：http://wiki.gp9zy7.asia/arts/821333.Doc

原标题：golang 日志 zap 结构化日志实践
简介：开发代理服务网络限制解决，搭建本地代理服务，解决开发环境网络访问受限，实现外部接口正常调用。
 | 原文链接：http://wiki.gp9zy7.asia/arts/629331.Doc

原标题：golang 项目 makefile 脚本编写
简介：golang cpu pprof 性能分析实操，使用 pprof 采集 CPU 性能数据，定位 CPU 高占用函数，做性能优化。
 | 原文链接：http://wiki.gp9zy7.asia/arts/036919.Doc

原标题：记一次限流组件误配置把正常用户拦截
简介：golang nats jetstream 持久消息队列，nats jetstream 持久化消息，保证消息不丢失，实现可靠消费。
 | 原文链接：http://wiki.gp9zy7.asia/arts/967795.Doc

原标题：Architecture：鉴权授权系统架构设计思路
简介：golang nil channel 阻塞特性，nil channel 读写永久阻塞，理解 nil channel 行为做逻辑控制。
 | 原文链接：http://wiki.gp9zy7.asia/arts/659685.Doc

原标题：缓存基础原理与简单代码实现
简介：浮点计算精度错误处理方案，讲解浮点数计算精度丢失问题，使用合适数据类型，规避金额计算出错。
 | 原文链接：http://wiki.gp9zy7.asia/arts/446215.Doc

原标题：golang 系统设计分布式配置中心思路
简介：golang lru 缓存淘汰算法编写，手写 LRU 缓存淘汰算法，实现本地缓存，淘汰最久未使用数据。
 | 原文链接：http://wiki.gp9zy7.asia/arts/202123.Doc

原标题：Hands‑on：手写简单RPC框架基础通信版本
简介：golang 协程数量监控统计方案，统计运行中 goroutine 数量，监控协程泄露，协程数量异常及时告警。
 | 原文链接：http://wiki.gp9zy7.asia/arts/212386.Doc

原标题：部署复盘：静态资源版本哈希缓存策略
简介：文件句柄耗尽资源泄露处理，定位文件句柄泄露，修复文件忘记关闭问题，解决句柄耗尽服务报错。
 | 原文链接：http://wiki.gp9zy7.asia/arts/861662.Doc

原标题：golang 系统设计线上问题复现思路简单讲解
简介：golang socket 文件描述符继承重启，父进程传递 listener fd 给子进程，实现 go 程序零停机热重启。
 | 原文链接：http://wiki.gp9zy7.asia/arts/875966.Doc

原标题：踩坑：大事务引发数据库连接池耗尽
简介：golang go1.18 + 泛型基础实操，go 泛型基础语法，泛型函数泛型类型，实现通用工具函数。
 | 原文链接：http://wiki.gp9zy7.asia/arts/742841.Doc

原标题：golang 跨域处理中间件编写
简介：vite 插件开发自定义构建逻辑，开发自定义 vite 插件，介入构建生命周期，实现项目个性化构建逻辑。
 | 原文链接：http://wiki.gp9zy7.asia/arts/275691.Doc

原标题：golang http client 连接池调优
简介：接口限流逻辑简单模拟实现，编写简易限流逻辑，限制接口访问频次，保护服务，避免短时间大量请求压垮系统。
 | 原文链接：http://wiki.gp9zy7.asia/arts/133259.Doc

原标题：golang redis 缓存更新策略讲解
简介：golang go 线上故障排查完整流程，CPU 高、内存上涨、接口超时、goroutine 泄露一套排查处理流程。
 | 原文链接：http://wiki.gp9zy7.asia/arts/201252.Doc

原标题：开源实践：给开源项目写单元测试贡献代码
简介：golang go yaml 解析自定义类型，yaml 自定义序列化，时间、特殊类型自定义解析逻辑。
 | 原文链接：http://wiki.gp9zy7.asia/arts/824496.Doc

原标题：golang es 查询语句 DSL 实操
简介：nodejs http 服务性能调优实战，调优 Node HTTP 服务内核参数，连接复用，提升接口并发处理能力。
 | 原文链接：http://wiki.gp9zy7.asia/arts/318509.Doc

原标题：前端防抖节流高频事件处理
简介：golang https 客户端跳过证书校验，开发测试环境跳过 tls 证书校验，仅用于内网测试禁止生产使用。
 | 原文链接：http://wiki.gp9zy7.asia/arts/354336.Doc

原标题：实践：数据库回滚点业务调试实践
简介：golang minio 私有对象存储开发，minio s3 对象存储，bucket 管理，文件上传下载权限设置。
 | 原文链接：http://wiki.gp9zy7.asia/arts/071639.Doc

原标题：Architecture：API设计RESTful最佳实践与反模式
简介：golang go 变量逃逸场景汇总，切片、指针、返回局部变量引发逃逸，变量分配到堆影响 GC。
 | 原文链接：http://wiki.gp9zy7.asia/arts/831912.Doc

原标题：安全复盘：CSRF跨站请求伪造防护配置
简介：跨库查询性能优化处理，减少跨库关联查询，做数据冗余或者中间表，规避跨库查询性能低下。
 | 原文链接：http://wiki.gp9zy7.asia/arts/882689.Doc

原标题：Practice：简易限流器分布式版本Redis实现
简介：golang go panic 合理使用边界，panic 只用于不可恢复程序错误，业务逻辑禁止直接 panic。
 | 原文链接：http://wiki.gp9zy7.asia/arts/505569.Doc

原标题：golang gorm ORM 数据库操作
简介：golang io.Copy 流式拷贝数据，io.Copy 拷贝 reader 到 writer，不用加载全部数据到内存。
 | 原文链接：http://wiki.gp9zy7.asia/arts/505372.Doc

原标题：Hands‑on：简易短消息模板渲染组件实践
简介：golang GC 频繁 STW 停顿优化，减少小对象分配，调整 GOGC，降低 GC 停顿对接口延迟影响。
 | 原文链接：http://wiki.gp9zy7.asia/arts/961032.Doc

原标题：多环境配置中心灵活切换方案
简介：日志敏感信息脱敏泄露防护，日志打印时自动脱敏手机号身份证，避免日志输出泄露用户隐私数据。
 | 原文链接：http://wiki.gp9zy7.asia/arts/860727.Doc

原标题：Performance：数据库大表优化，冷热数据分离
简介：站内邮件消息通知功能开发，实现站内消息、邮件通知推送，业务事件触发通知，提醒用户业务状态变更。
 | 原文链接：http://wiki.gp9zy7.asia/arts/571100.Doc

原标题：数据库连接池参数调优
简介：前端骨架屏提升页面体验，实现页面骨架屏，数据未加载完成展示占位，优化页面白屏感知体验。
 | 原文链接：http://wiki.gp9zy7.asia/arts/948147.Doc

原标题：golang 接口限流中间件开发
简介：golang 任务失败重试与死信队列，异步任务失败自动重试，超过重试次数进入死信队列人工处理。
 | 原文链接：http://wiki.gp9zy7.asia/arts/178415.Doc

原标题：多版本开发环境共存配置
简介：golang goroutine 泄露常见场景汇总，channel 阻塞、context 忘记取消，导致协程无法退出发生泄露。
 | 原文链接：http://wiki.gp9zy7.asia/arts/030637.Doc

原标题：记一次分库分表路由计算错误数据写入错误分片
简介：项目构建脚本编译打包解析，解读项目构建脚本，理清编译、压缩、资源复制流程，理解打包后产物如何生成。
 | 原文链接：http://wiki.gp9zy7.asia/arts/029047.Doc

原标题：golang 系统设计单元测试边界条件覆盖思路
简介：golang loki 日志收集 go 服务集成，日志输出适配 loki，标签携带 traceId，日志集中检索排查问题。
 | 原文链接：http://wiki.gp9zy7.asia/arts/873086.Doc

四、架构设计｜Architecture
原标题：限流组件计数器令牌桶模式实现
简介：golang go mod vendor 本地依赖导出，导出 vendor 目录，离线环境编译项目，无需访问外网拉依赖。
 | 原文链接：http://wiki.gp9zy7.asia/arts/692664.Doc

原标题：golang mysql 长连接短连接对比
简介：golang influxdb 时序数据库读写操作，influxdb 存储时序指标，业务指标监控数据存取。
 | 原文链接：http://wiki.gp9zy7.asia/arts/342964.Doc

原标题：开发复盘：百万数据批量导入数据库优化方案
简介：主干开发团队代码合并策略，讲解主干开发模式，团队代码合并流程，适合高频迭代的团队协作模式。
 | 原文链接：http://wiki.gp9zy7.asia/arts/151082.Doc

原标题：HelloGitHubPages：部署你的第一个静态博客
简介：golang go http 静态文件禁止目录遍历，http.FileServer 防止../ 路径穿越，了解底层安全实现。
 | 原文链接：http://wiki.gp9zy7.asia/arts/759845.Doc

原标题：golang github actions 完整工作流示例
简介：golang k8s secret 敏感配置加载，加载 k8s secret 存储密钥密码，敏感信息不存放配置文件。
 | 原文链接：http://wiki.gp9zy7.asia/arts/597351.Doc

原标题：golang 系统设计一致性哈希原理讲解
简介：线程调度优化减少上下文切换，优化线程数量，减少线程频繁切换，降低 CPU 上下文切换开销。
 | 原文链接：http://wiki.gp9zy7.asia/arts/831453.Doc

原标题：Performance：避免循环查询N+1问题完整优化
简介：缓存穿透击穿雪崩全套防护，完整梳理缓存三大问题，落地全套防护策略，保障缓存层稳定运行。
 | 原文链接：http://wiki.gp9zy7.asia/arts/150639.Doc

原标题：HelloGitWorkflow：理解简单主干开发流程
简介：业务幂等键设计防重复逻辑，讲解幂等键设计思路，选择合适业务字段作为幂等标识，实现可靠防重复。
 | 原文链接：http://wiki.gp9zy7.asia/arts/995357.Doc

原标题：文件批量导入导出功能实现
简介：golang kitex 中间件与元数据传递，kitex 自定义中间件，透传 traceId 鉴权元数据，统一处理请求。
 | 原文链接：http://wiki.gp9zy7.asia/arts/801788.Doc

原标题：golang 系统设计布隆过滤器拦截不存在 key
简介：golang embed 目录读取文件列表，embed 嵌入整个目录，读取目录下全部文件，做静态资源服务。
 | 原文链接：http://wiki.gp9zy7.asia/arts/842968.Doc

原标题：golang 系统设计测试覆盖率目标合理设定思路
简介：缓存穿透防护保护数据库，实现缓存穿透防护手段，拦截不存在的数据查询，避免请求直接打穿数据库。
 | 原文链接：http://wiki.gp9zy7.asia/arts/001964.Doc

原标题：golang mysql 行锁表锁场景区分
简介：golang strings 常用函数业务实战，字符串分割替换包含判断前缀后缀，掌握 strings 包高频函数。
 | 原文链接：http://wiki.gp9zy7.asia/arts/414769.Doc

原标题：手写简易 MQ 理解消息存储消费
简介：开源项目本地运行排错完整清单，汇总开源项目拉取后运行失败各类问题，给出排查思路，快速解决本地启动异常。
 | 原文链接：http://wiki.gp9zy7.asia/arts/022192.Doc

原标题：golang 系统设计雪花算法 id 原理剖析
简介：golang context.Background 与 TODO 区别，Background 主流程根上下文，TODO 不确定用哪个上下文时使用。
 | 原文链接：http://wiki.gp9zy7.asia/arts/729334.Doc

原标题：golang 系统设计单元测试 mock 外部依赖技巧
简介：golang go embed 嵌入静态资源文件，使用 go embed 把静态文件编译进二进制，单文件部署携带静态资源。
 | 原文链接：http://wiki.gp9zy7.asia/arts/379109.Doc

原标题：快速入门日志打印与日志分级基础用法
简介：golang go 版本管理 go install 安装工具，go install 安装指定版本 go 工具，管理本地 go 工具版本。
 | 原文链接：http://wiki.gp9zy7.asia/arts/021817.Doc

原标题：排错：多实例部署session共享失效登录失效
简介：golang kitex 中间件与元数据传递，kitex 自定义中间件，透传 traceId 鉴权元数据，统一处理请求。
 | 原文链接：http://wiki.gp9zy7.asia/arts/226047.Doc

原标题：golang 系统设计无锁编程思路简单示例
简介：golang 内存 dump 线上堆快照采集，线上生成内存 dump 文件，线下分析，定位内存泄漏问题。
 | 原文链接：http://wiki.gp9zy7.asia/arts/935411.Doc

?
