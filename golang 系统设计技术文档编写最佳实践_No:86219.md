最新前沿技术资讯

一、入门教程｜Getting Started
原标题：golang 系统设计技术文档编写最佳实践
简介：golang go http 文件服务器自定义，http.FileServer 自定义 FileSystem，拦截访问，增加鉴权逻辑。
 | 原文链接：http://wiki.zfpdg7.asia/arts/512727.Doc

原标题：golang k8s job 一次性任务执行
简介：golang 静态编译缩小镜像体积，Go 程序静态编译，不依赖系统库，产出单二进制文件，缩小镜像。
 | 原文链接：http://wiki.zfpdg7.asia/arts/034480.Doc

原标题：踩坑记录：浮点数作为Rediskey匹配异常
简介：golang context.Background 与 TODO 区别，Background 主流程根上下文，TODO 不确定用哪个上下文时使用。
 | 原文链接：http://wiki.zfpdg7.asia/arts/521752.Doc

原标题：golang 系统设计 api 网关核心能力梳理
简介：Redis 大 key 拆分集群卡顿解决，拆分 Redis 超大 Key，避免大 key 操作造成 Redis 集群卡顿阻塞。
 | 原文链接：http://wiki.zfpdg7.asia/arts/488858.Doc

原标题：golang k8s cronjob 定时任务配置
简介：golang 终端交互式输入选择，命令行交互式问答选择输入，实现交互式脚本工具。
 | 原文链接：http://wiki.zfpdg7.asia/arts/463525.Doc

原标题：踩坑记录：数值溢出造成业务ID错乱异常
简介：golang 表格驱动测试完整示例，表格驱动多组输入输出，批量执行测试用例，减少重复代码。
 | 原文链接：http://wiki.zfpdg7.asia/arts/590840.Doc

原标题：golang 项目 go mod 依赖管理
简介：系统字符集统一乱码修复，统一数据库、程序、操作系统字符集，解决中文乱码显示异常问题。
 | 原文链接：http://wiki.zfpdg7.asia/arts/968990.Doc

原标题：golang 系统设计分布式锁红锁优缺点梳理
简介：浏览器缓存强制刷新方案，设置 HTTP 缓存头，处理浏览器缓存旧静态资源，让用户加载更新后的页面。
 | 原文链接：http://wiki.zfpdg7.asia/arts/892444.Doc

原标题：OOMKilled 容器被杀完整排查
简介：容器资源限制防止宿主机过载，设置容器 CPU 内存资源上限，避免单个容器耗尽宿主机全部硬件资源。
 | 原文链接：http://wiki.zfpdg7.asia/arts/820141.Doc

原标题：定时任务重复执行分布式锁
简介：golang arp 缓存读取操作，读取系统 arp 缓存表，获取 ip 对应的 mac 地址信息。
 | 原文链接：http://wiki.zfpdg7.asia/arts/382258.Doc

原标题：跨域偶现失败配置修复
简介：全局时间标准统一逻辑错乱修复，全服务统一使用同一时间标准，不要混用本地时间 UTC，修复时间逻辑 bug。
 | 原文链接：http://wiki.zfpdg7.asia/arts/809646.Doc

原标题：性能笔记：TCP参数内核调优服务高并发场景
简介：golang grpc 客户端拦截器封装，grpc 客户端拦截器实现请求统一签名、重试、链路信息透传。
 | 原文链接：http://wiki.zfpdg7.asia/arts/274810.Doc

原标题：Practice：实现接口防重提交组件实践
简介：webpack chunk 分包策略详解，讲解 webpack chunk 分包策略，拆分第三方包与业务代码，优化缓存复用。
 | 原文链接：http://wiki.zfpdg7.asia/arts/539625.Doc

原标题：开发复盘：大事务拆分优化业务性能实践
简介：golang errors.Is errors.As 错误判断，判断是否为指定错误类型，提取自定义错误信息，错误处理进阶。
 | 原文链接：http://wiki.zfpdg7.asia/arts/722697.Doc

原标题：Debug：序列化反序列化版本不一致解析失败
简介：Nginx 静态代理负载均衡全套配置，一套 Nginx 配置示例，覆盖静态资源、反向代理、负载均衡场景。
 | 原文链接：http://wiki.zfpdg7.asia/arts/446888.Doc

原标题：效率笔记：VSCode插件集合后端前端开发效率
简介：golang CPU 绑定亲和性设置 go 程序，设置进程 CPU 亲和绑定核心，减少 CPU 调度开销，提升计算性能。
 | 原文链接：http://wiki.zfpdg7.asia/arts/182157.Doc

原标题：容器内存扩容 OOM 被杀死修复
简介：nodejs jwt 登录鉴权完整示例，Node 实现 JWT 登录鉴权，登录签发令牌，接口校验令牌身份。
 | 原文链接：http://wiki.zfpdg7.asia/arts/689536.Doc

原标题：Issue：开源项目升级大版本后API不兼容踩坑
简介：golang goroutine 池任务调度，实现 goroutine 池，复用协程，频繁任务场景减少协程创建销毁开销。
 | 原文链接：http://wiki.zfpdg7.asia/arts/168032.Doc

原标题：接口签名验签完整安全方案
简介：批量异步处理系统业务落地，构建批量异步处理系统，把耗时业务异步化，提升接口响应速度。
 | 原文链接：http://wiki.zfpdg7.asia/arts/318024.Doc

原标题：文件监控服务自动重启开发
简介：golang 错误静默忽略风险规避，禁止空忽略错误，必须处理或者明确注释为什么忽略错误。
 | 原文链接：http://wiki.zfpdg7.asia/arts/501625.Doc

原标题：新手指南：看懂开源项目的Issue与PR
简介：golang kitex 中间件与元数据传递，kitex 自定义中间件，透传 traceId 鉴权元数据，统一处理请求。
 | 原文链接：http://wiki.zfpdg7.asia/arts/486990.Doc

原标题：golang 系统设计网关 ssl 证书配置更新实操
简介：golang gin 静态资源访问配置，Gin 配置静态资源目录，直接对外提供静态文件访问服务。
 | 原文链接：http://wiki.zfpdg7.asia/arts/288247.Doc

原标题：golang 系统设计 csrf 接口防护实现
简介：后端分页查询逻辑代码实现，编写后端分页接口，处理页码、每页条数参数，优化大数据量查询返回结果。
 | 原文链接：http://wiki.zfpdg7.asia/arts/371892.Doc

原标题：golang 系统设计告警风暴抑制方案实现
简介：golang mysql 长连接检测保活设置，配置 mysql 连接保活检测，剔除失效连接，避免拿到断开无效数据库连接。
 | 原文链接：http://wiki.zfpdg7.asia/arts/216919.Doc

原标题：项目实践：MySQL读写分离本地模拟实践
简介：多操作系统开发兼容处理，解决不同系统路径、换行符、权限差异，保证项目跨平台正常运行。
 | 原文链接：http://wiki.zfpdg7.asia/arts/782375.Doc

原标题：Redis 大 key 拆分集群卡顿解决
简介：代码格式化工具团队统一风格，接入格式化工具，统一全团队代码书写风格，减少格式类 git 冲突。
 | 原文链接：http://wiki.zfpdg7.asia/arts/818617.Doc

原标题：性能笔记：压测如何定位真实系统瓶颈
简介：前端权限路由动态生成实现，根据后端返回权限，动态生成前端路由菜单，实现页面权限控制。
 | 原文链接：http://wiki.zfpdg7.asia/arts/312473.Doc

原标题：实战：单元测试+集成测试完整项目落地实践
简介：golang 滑动窗口限流算法 go 实现，滑动窗口限流，解决固定窗口临界流量突增漏洞，限流更精准。
 | 原文链接：http://wiki.zfpdg7.asia/arts/329541.Doc

原标题：golang ci 流水线自动部署 k8s 示例
简介：golang url 解析路径参数提取，url.Parse 解析 url，获取协议主机路径查询参数。
 | 原文链接：http://wiki.zfpdg7.asia/arts/938463.Doc

原标题：golang 项目环境变量加载方案
简介：项目脚手架模板生成工具，搭建项目模板脚手架，一键生成标准化项目骨架，减少重复初始化工作。
 | 原文链接：http://wiki.zfpdg7.asia/arts/974638.Doc

原标题：golang 系统设计缓存 key 淘汰雪崩防护思路
简介：项目脚手架模板生成工具，搭建项目模板脚手架，一键生成标准化项目骨架，减少重复初始化工作。
 | 原文链接：http://wiki.zfpdg7.asia/arts/343536.Doc

原标题：架构复盘：分表扩容架构平滑迁移思路
简介：golang rsa 公钥加密私钥解密，rsa 非对称加密，大文件分块加密，处理非对称加密长度限制。
 | 原文链接：http://wiki.zfpdg7.asia/arts/330980.Doc

原标题：浏览器本地存储安全使用技巧
简介：golang ssh 客户端远程命令执行，golang ssh 连接远程服务器，执行 shell 命令，获取命令输出结果。
 | 原文链接：http://wiki.zfpdg7.asia/arts/012007.Doc

原标题：接口压测定位系统性能瓶颈
简介：golang http cookie jar 会话处理，客户端 cookie jar 自动管理 cookie，处理登录态会话。
 | 原文链接：http://wiki.zfpdg7.asia/arts/018867.Doc

原标题：性能复盘：GC停顿过长业务卡顿优化记录
简介：golang redis scan 遍历 key 避免阻塞，使用 scan 迭代遍历 redis 键，不用 keys 命令，防止阻塞 redis 服务。
 | 原文链接：http://wiki.zfpdg7.asia/arts/389425.Doc

原标题：站内邮件消息通知功能开发
简介：定时任务重复执行分布式锁，使用分布式锁控制定时任务，保证集群环境定时任务只会执行一次。
 | 原文链接：http://wiki.zfpdg7.asia/arts/934796.Doc

原标题：nodejs 数据库连接池配置调优
简介：golang 系统资源限制读取 cpu 内存，读取系统容器 cpu 内存限制，程序适配容器资源配额做业务调优。
 | 原文链接：http://wiki.zfpdg7.asia/arts/161054.Doc

原标题：eslint prettier 代码规范落地
简介：gRPC 服务端客户端入门示例，搭建 gRPC 服务端与调用客户端，学习 protobuf 定义，掌握 RPC 基础开发流程。
 | 原文链接：http://wiki.zfpdg7.asia/arts/064136.Doc

原标题：入门实践：简单图片上传预览本地demo
简介：golang mime 类型检测文件，mime 识别文件 mime 类型，设置 http 响应 Content‑Type。
 | 原文链接：http://wiki.zfpdg7.asia/arts/608410.Doc

原标题：快速上手搭建简易内网测试服务
简介：golang gin 获取客户端真实 IP，多层代理场景正确拿到用户真实访问 IP，避免拿到网关代理内网地址。
 | 原文链接：http://wiki.zfpdg7.asia/arts/633963.Doc


二、踩坑排错｜Troubleshooting
原标题：实战项目：CLI批量文件处理工具开发全过程
简介：golang 雪花 id 重复问题排查，排查雪花算法 ID 重复问题，时钟回拨、机器 ID 冲突，给出修复方案。
 | 原文链接：http://wiki.zfpdg7.asia/arts/363977.Doc

原标题：golang redis pipeline 批量操作
简介：golang tls 证书加载配置 https 服务，加载证书密钥，搭建 golang https 服务，配置 tls 版本安全策略。
 | 原文链接：http://wiki.zfpdg7.asia/arts/110911.Doc

原标题：golang 系统设计索引设计通用方法论汇总
简介：golang 响应 body 流式返回大数据，http 流式输出数据，边生成边返回，无需在内存组装完整返回结果。
 | 原文链接：http://wiki.zfpdg7.asia/arts/506799.Doc

原标题：服务器时钟同步任务错乱修复
简介：MySQL 慢查询索引优化实战，抓取慢查询 SQL，分析执行计划，新增或者调整索引，提升 SQL 执行速度。
 | 原文链接：http://wiki.zfpdg7.asia/arts/454853.Doc

原标题：golang kafka 核心概念分区副本
简介：nodejs 数据库连接池配置调优，调优 Node 数据库连接池参数，平衡性能与资源占用，避免连接耗尽。
 | 原文链接：http://wiki.zfpdg7.asia/arts/048193.Doc

原标题：优化实践：业务定时任务错开高峰避免资源争抢
简介：golang 灰度发布流量权重路由实现，根据权重切分流量，部分流量访问新版本服务，实现灰度发布。
 | 原文链接：http://wiki.zfpdg7.asia/arts/333025.Doc

原标题：记一次内存Swap被大量使用系统响应缓慢
简介：死信队列处理消息阻塞业务，配置死信队列，处理消费失败消息，避免失败消息阻塞整个队列业务。
 | 原文链接：http://wiki.zfpdg7.asia/arts/502866.Doc

原标题：Hands‑on：简易请求转发代理中间件实现
简介：golang io.Copy 流式拷贝数据，io.Copy 拷贝 reader 到 writer，不用加载全部数据到内存。
 | 原文链接：http://wiki.zfpdg7.asia/arts/538199.Doc

原标题：golang 接口请求日志记录中间件
简介：后端分页查询逻辑代码实现，编写后端分页接口，处理页码、每页条数参数，优化大数据量查询返回结果。
 | 原文链接：http://wiki.zfpdg7.asia/arts/317792.Doc

原标题：架构笔记：任务调度系统架构设计与可靠性
简介：RPC 报文大小上限调优大请求，调大 RPC 框架报文最大限制，支持传输大体积请求报文不被截断。
 | 原文链接：http://wiki.zfpdg7.asia/arts/665763.Doc

原标题：踩坑：大报文传输，RPC消息超过大小限制
简介：golang go mod 私有 git 仓库配置，配置 go mod 拉取私有仓库代码，处理私有模块依赖拉取问题。
 | 原文链接：http://wiki.zfpdg7.asia/arts/046970.Doc

原标题：部署复盘：容器资源限制CPU内存配置实践
简介：golang hertz http 框架快速上手，hertz 高性能 http 框架，路由中间件参数校验快速开发接口服务。
 | 原文链接：http://wiki.zfpdg7.asia/arts/885218.Doc

原标题：排错：GitLFS大文件推送失败完整排障
简介：golang kafka 消费者组重平衡避坑，规避消费者组频繁 rebalance，减少消费抖动，保障消息消费稳定性。
 | 原文链接：http://wiki.zfpdg7.asia/arts/820689.Doc

原标题：踩坑记录：数值溢出造成业务ID错乱异常
简介：golang go 调用动态链接库 so 文件，go 加载 so 动态库调用函数，复用编译好的 C 动态库。
 | 原文链接：http://wiki.zfpdg7.asia/arts/724544.Doc

原标题：Hands‑on：简易短消息模板渲染组件实践
简介：API 接口调试与异常处理实战，覆盖接口请求、参数组装、错误捕获，提供调试思路，高效定位接口返回异常问题。
 | 原文链接：http://wiki.zfpdg7.asia/arts/126685.Doc

原标题：nodejs 集成测试业务流程编写
简介：golang influxdb 时序数据库读写操作，influxdb 存储时序指标，业务指标监控数据存取。
 | 原文链接：http://wiki.zfpdg7.asia/arts/337751.Doc

原标题：OpenSource：开源项目版本发布CHANGELOG编写
简介：nodejs 多进程任务分发处理，多进程拆分处理 CPU 密集任务，主进程分发任务，利用多核提升处理速度。
 | 原文链接：http://wiki.zfpdg7.asia/arts/247939.Doc

原标题：性能笔记：HTTP连接复用性能优化实践
简介：golang 半关闭 tcp 连接 shutdown，tcp 连接 shutdown 半关闭，单向关闭读或者写，理解 tcp 关闭流程。
 | 原文链接：http://wiki.zfpdg7.asia/arts/194088.Doc

原标题：快速入门对象存储基础使用场景
简介：golang 半关闭 tcp 连接 shutdown，tcp 连接 shutdown 半关闭，单向关闭读或者写，理解 tcp 关闭流程。
 | 原文链接：http://wiki.zfpdg7.asia/arts/233552.Doc

原标题：Security：开源项目安全审计简易检查清单
简介：golang go test 单元测试命令参数详解，gotest 参数覆盖率，指定测试用例，跳过测试，单元测试命令实操。
 | 原文链接：http://wiki.zfpdg7.asia/arts/500461.Doc

原标题：开发记录：业务错误告警邮件通知组件实践
简介：本地数据库开发环境搭建指南，讲解数据库安装配置、账号权限设置、连接测试，快速搭建用于开发调试的数据库实例。
 | 原文链接：http://wiki.zfpdg7.asia/arts/715865.Doc

原标题：实战：Docker资源监控查看容器状态实操
简介：golang context.Background 与 TODO 区别，Background 主流程根上下文，TODO 不确定用哪个上下文时使用。
 | 原文链接：http://wiki.zfpdg7.asia/arts/042131.Doc

原标题：DevOps：私有镜像仓库搭建与权限管控
简介：golang kitex 字节微服务框架入门，kitex 开发 rpc 微服务，代码生成，服务注册发现完整流程。
 | 原文链接：http://wiki.zfpdg7.asia/arts/716535.Doc

原标题：golang gorm 预加载关联查询优化
简介：golang 处理连接被重置 reset 错误，识别 connection reset by peer，对端关闭连接异常处理逻辑。
 | 原文链接：http://wiki.zfpdg7.asia/arts/900615.Doc

原标题：golang 系统设计 mq 消息丢失完整防护
简介：CLI 工具进度条交互效果开发，在命令行工具增加进度条展示，直观反馈任务执行进度，优化命令行体验。
 | 原文链接：http://wiki.zfpdg7.asia/arts/353795.Doc

原标题：Architecture：中小型后端服务整体架构设计复盘
简介：golang 处理连接被重置 reset 错误，识别 connection reset by peer，对端关闭连接异常处理逻辑。
 | 原文链接：http://wiki.zfpdg7.asia/arts/151109.Doc

原标题：golang 系统设计缓存预热脚本编写实操
简介：golang os 文件权限 mode，os.FileMode 文件权限，读写执行权限位，跨平台权限注意事项。
 | 原文链接：http://wiki.zfpdg7.asia/arts/721863.Doc

原标题：坑点：gitreset误删本地代码恢复方案
简介：golang fasthttp 高性能 http 库使用，fasthttp 高性能 http 实现，适合超高 QPS 场景，对比 net/http 差异。
 | 原文链接：http://wiki.zfpdg7.asia/arts/455705.Doc

原标题：安全复盘：业务数据脱敏防止泄露实践
简介：端口占用释放资源重启服务，查找占用端口进程，结束占用进程，释放端口，让服务能够正常启动监听。
 | 原文链接：http://wiki.zfpdg7.asia/arts/114856.Doc

原标题：golang 系统设计大文件上传架构
简介：golang go 服务蓝绿发布实践思路，蓝绿两套实例，流量一键切换，回滚快速降低发布风险。
 | 原文链接：http://wiki.zfpdg7.asia/arts/791916.Doc

原标题：golang redis hyperloglog 基数统计
简介：前端防抖节流高频事件处理，封装防抖节流工具，处理滚动、输入框输入等高频触发事件减少执行次数。
 | 原文链接：http://wiki.zfpdg7.asia/arts/458865.Doc

原标题：Hands‑on：编写自定义Git钩子实现代码提交校验
简介：golang os.Signal 信号监听完整示例，signal.Notify 监听信号，缓冲 channel 防止信号丢失。
 | 原文链接：http://wiki.zfpdg7.asia/arts/216395.Doc

原标题：golang 系统设计日志本地打印线上关闭调试信息
简介：golang 日志级别动态调整热更新，不用重启程序动态修改日志输出级别，线上调试排查问题十分方便。
 | 原文链接：http://wiki.zfpdg7.asia/arts/500051.Doc

原标题：入门实践：使用Git完成第一次代码提交与推送
简介：golang bcrypt 密码哈希加密存储，bcrypt 做用户密码哈希，加盐存储密码，保障用户密码安全。
 | 原文链接：http://wiki.zfpdg7.asia/arts/636702.Doc

原标题：golang 协程泄露问题排查方法
简介：Git 误删提交代码恢复找回，使用 Git reflog 工具找回被误删除提交记录，恢复误删除代码。
 | 原文链接：http://wiki.zfpdg7.asia/arts/030485.Doc

原标题：快速启动：本地运行开源项目排障清单
简介：golang go 项目依赖冲突解决完整思路，定位冲突包，replace、exclude、升级降级解决版本冲突。
 | 原文链接：http://wiki.zfpdg7.asia/arts/212700.Doc

原标题：golang 系统设计第三方调用超时重试熔断
简介：golang go 爬虫 html 解析 goquery，goquery 解析 html 文档，css 选择器提取网页内容，实现网页数据抓取。
 | 原文链接：http://wiki.zfpdg7.asia/arts/539301.Doc

原标题：golang 日志 zap 结构化日志实践
简介：golang tidb 数据库 go 项目适配，go 程序适配 tidb，兼容 mysql 协议，分布式数据库业务开发。
 | 原文链接：http://wiki.zfpdg7.asia/arts/198864.Doc

原标题：Practice：实现定时任务动态启停管理接口
简介：golang grpc keepalive 保活配置，grpc keepalive 参数调优，检测断开僵死连接，释放无效连接资源。
 | 原文链接：http://wiki.zfpdg7.asia/arts/271374.Doc

原标题：网关集成鉴权限流日志一体化
简介：golang 接口返回统一封装工具，封装 Go 接口统一返回工具，标准化成功失败返回结构体。
 | 原文链接：http://wiki.zfpdg7.asia/arts/594355.Doc

三、实战开发｜Practice
原标题：golang 令牌桶限流中间件 gin
简介：golang grpc 客户端拦截器封装，grpc 客户端拦截器实现请求统一签名、重试、链路信息透传。
 | 原文链接：http://wiki.zfpdg7.asia/arts/342246.Doc

原标题：golang yaml 解析配置加载实操
简介：多操作系统开发兼容处理，解决不同系统路径、换行符、权限差异，保证项目跨平台正常运行。
 | 原文链接：http://wiki.zfpdg7.asia/arts/229475.Doc

原标题：快速启动：本地运行开源项目排障清单
简介：golang grpc 客户端拦截器封装，grpc 客户端拦截器实现请求统一签名、重试、链路信息透传。
 | 原文链接：http://wiki.zfpdg7.asia/arts/607889.Doc

原标题：golang k8s service 服务暴露几种类型
简介：golang os 文件权限 mode，os.FileMode 文件权限，读写执行权限位，跨平台权限注意事项。
 | 原文链接：http://wiki.zfpdg7.asia/arts/857202.Doc

原标题：golang es 分词器选型业务适配
简介：golang 表格驱动测试完整示例，表格驱动多组输入输出，批量执行测试用例，减少重复代码。
 | 原文链接：http://wiki.zfpdg7.asia/arts/554558.Doc

原标题：OpenSource：如何高效阅读大型开源项目源码
简介：pnpm 包管理工具实战避坑指南，使用 pnpm 管理项目依赖，梳理常见坑点，充分利用 pnpm 优势。
 | 原文链接：http://wiki.zfpdg7.asia/arts/137511.Doc

原标题：开发记录：日志脱敏防止敏感信息输出实践
简介：golang 接口返回统一封装工具，封装 Go 接口统一返回工具，标准化成功失败返回结构体。
 | 原文链接：http://wiki.zfpdg7.asia/arts/718398.Doc

原标题：golang 系统设计消息堆积排查扩容完整步骤
简介：golang http client Transport 参数调优，Transport 最大连接空闲连接，TLS 配置，http 客户端调优。
 | 原文链接：http://wiki.zfpdg7.asia/arts/567141.Doc

原标题：golang 系统设计 issue 模板 bug 反馈模板
简介：golang 优雅处理 http 重定向逻辑，自定义控制 http 重定向跳转次数，防止无限重定向死循环。
 | 原文链接：http://wiki.zfpdg7.asia/arts/151336.Doc

原标题：从零搭建简单Mock接口服务
简介：简易日志收集集中管理方案，搭建轻量日志收集方案，把多服务日志汇总，集中检索查看日志信息。
 | 原文链接：http://wiki.zfpdg7.asia/arts/133258.Doc

原标题：golang 空接口 interface 使用技巧
简介：golang trace 可视化分析协程阻塞，使用 trace 网页 UI，定位协程阻塞、系统调用阻塞、锁等待。
 | 原文链接：http://wiki.zfpdg7.asia/arts/142400.Doc

原标题：golang k8s service 服务暴露几种类型
简介：CI 流水线超时时间延长配置，调大 CI 任务超时阈值，解决构建任务耗时较长被流水线强制终止。
 | 原文链接：http://wiki.zfpdg7.asia/arts/168971.Doc

原标题：架构笔记：数据脱敏架构接入层与存储层方案
简介：文件句柄上限调整上传随机失败，调高系统文件句柄上限，解决高并发上传场景随机打开文件失败。
 | 原文链接：http://wiki.zfpdg7.asia/arts/831847.Doc

原标题：内存溢出问题现象识别排查
简介：异步异常捕获避免进程崩溃，捕获异步代码内部抛出异常，防止未捕获异常直接导致整个进程退出。
 | 原文链接：http://wiki.zfpdg7.asia/arts/600975.Doc

原标题：包管理器依赖冲突解决方案
简介：DNS TTL 配置域名切换生效，调整 DNS 解析 TTL，缩短缓存时间，域名变更后可以快速全网生效。
 | 原文链接：http://wiki.zfpdg7.asia/arts/002090.Doc

原标题：安全实践：接口错误信息不要暴露内部细节
简介：golang 时间戳秒毫秒纳秒转换，Unix UnixMilli UnixNano 互相转换，区分单位避免时间逻辑 bug。
 | 原文链接：http://wiki.zfpdg7.asia/arts/265503.Doc

原标题：golang 系统设计混沌测试简单场景模拟实现
简介：golang go‑fuzz 模糊测试开发，go fuzz 模糊测试，自动构造异常输入，发现代码隐藏 bug。
 | 原文链接：http://wiki.zfpdg7.asia/arts/744155.Doc

原标题：nodejs 单元测试 jest 实操教程
简介：golang go 程序权限最小化运行，容器内使用普通用户运行程序，拒绝 root 运行提升安全等级。
 | 原文链接：http://wiki.zfpdg7.asia/arts/275200.Doc

原标题：golang 系统设计开源 pr 评审合并流程实操
简介：分布式 ID 全局唯一生成方案，讲解分布式 ID 生成思路，实现全局唯一 ID，满足分布式系统主键生成需求。
 | 原文链接：http://wiki.zfpdg7.asia/arts/820285.Doc

原标题：文件句柄耗尽资源泄露处理
简介：golang go 容器 heap 堆实现优先队列，实现 heap 接口，构建优先队列，任务优先级调度。
 | 原文链接：http://wiki.zfpdg7.asia/arts/641007.Doc

原标题：限流规则误拦截正常请求修复
简介：golang time duration 解析时间字符串，time.ParseDuration 解析 1h30m 时间间隔字符串。
 | 原文链接：http://wiki.zfpdg7.asia/arts/531883.Doc

原标题：TCP 心跳检测清理僵死连接
简介：游标分页大数据查询性能提升，使用游标分页替代偏移分页，解决大数据 offset 分页性能越来越差问题。
 | 原文链接：http://wiki.zfpdg7.asia/arts/459114.Doc

原标题：异步异常捕获避免进程崩溃
简介：开发环境变量配置全平台教程，区分 Windows、macOS、Linux 系统，讲解环境变量配置、加载优先级与常见失效原因。
 | 原文链接：http://wiki.zfpdg7.asia/arts/159918.Doc

原标题：记一次第三方回调IP变动未更新防火墙拦截
简介：golang systemd 信号与优雅退出配合，systemd 停止服务发送 SIGTERM，go 程序捕获信号优雅关闭。
 | 原文链接：http://wiki.zfpdg7.asia/arts/371687.Doc

原标题：架构笔记：数据脱敏架构接入层与存储层方案
简介：golang sort 稳定排序 Stable，稳定排序保留相等元素原有顺序，业务需要稳定排序场景。
 | 原文链接：http://wiki.zfpdg7.asia/arts/038376.Doc

原标题：实践：API接口文档自动导出离线文档实践
简介：golang go 泛型使用避坑注意点，泛型与 interface 区别，泛型性能，什么时候适合使用泛型。
 | 原文链接：http://wiki.zfpdg7.asia/arts/707474.Doc

原标题：golang 系统设计 sql 注入 xss 防护实践
简介：golang 配置文件热加载监听变更，监听配置文件改动，自动重新加载配置，业务即时生效无需重启。
 | 原文链接：http://wiki.zfpdg7.asia/arts/711469.Doc

原标题：golang prometheus histogram 指标
简介：golang 工具函数库封装思路，Go 通用工具库封装思路，错误处理、类型转换，业务项目复用工具代码。
 | 原文链接：http://wiki.zfpdg7.asia/arts/229126.Doc

原标题：系统文件描述符上限调大
简介：golang os 文件权限 mode，os.FileMode 文件权限，读写执行权限位，跨平台权限注意事项。
 | 原文链接：http://wiki.zfpdg7.asia/arts/993811.Doc

原标题：vite 插件开发自定义构建逻辑
简介：golang go proxy 私有代理配置，配置 go proxy 私有代理，加速依赖下载，内网环境构建项目。
 | 原文链接：http://wiki.zfpdg7.asia/arts/892111.Doc

原标题：HTTPS 证书过期更新操作
简介：Spring 事务传播机制配置生效，理解事务传播行为，正确配置，修复事务不生效、事务失效的业务 bug。
 | 原文链接：http://wiki.zfpdg7.asia/arts/941700.Doc

原标题：golang 系统设计单元测试边界条件覆盖思路
简介：golang redis 过期键监听回调，监听 key 过期事件，过期触发业务逻辑，实现过期自动处理业务场景。
 | 原文链接：http://wiki.zfpdg7.asia/arts/680607.Doc

原标题：hosts 配置本地回环访问修复
简介：golang http 文件下载断点续传服务，服务端实现断点续传，支持大文件分段下载，提升大文件下载稳定性。
 | 原文链接：http://wiki.zfpdg7.asia/arts/953542.Doc

原标题：golang 系统设计基准测试 benchmark 编写
简介：golang go mod tidy 依赖清理，go mod tidy 自动增删依赖，整理 go.mod go.sum 文件。
 | 原文链接：http://wiki.zfpdg7.asia/arts/739411.Doc

原标题：包管理器依赖缓存清理
简介：golang go 死锁检测工具，静态检查、运行检测，发现 channel 锁导致死锁问题。
 | 原文链接：http://wiki.zfpdg7.asia/arts/196403.Doc

原标题：性能笔记：数据库表字段设计影响查询性能
简介：数据库分表路由写入分片修正，修复分表路由逻辑，保证数据写入正确分片，不会出现数据丢失错乱。
 | 原文链接：http://wiki.zfpdg7.asia/arts/498636.Doc

原标题：golang 时间时区处理避坑指南
简介：golang 滑动窗口限流算法 go 实现，滑动窗口限流，解决固定窗口临界流量突增漏洞，限流更精准。
 | 原文链接：http://wiki.zfpdg7.asia/arts/801957.Doc

原标题：方案对比：缓存更新策略Cache‑Aside读写模式
简介：文件分片上传断点续传功能，实现文件分片上传，记录上传进度，支持断点续传大文件上传。
 | 原文链接：http://wiki.zfpdg7.asia/arts/209506.Doc

原标题：golang 系统设计日志系统架构思路
简介：golang 消息队列实现事务消息方案，基于 kafka 实现事务消息，业务执行成功才对外投递消息。
 | 原文链接：http://wiki.zfpdg7.asia/arts/404547.Doc

原标题：golang 项目 go mod 依赖管理
简介：golang testify mock 模拟接口，mock 接口生成 mock 对象，单元测试模拟外部依赖行为。
 | 原文链接：http://wiki.zfpdg7.asia/arts/382337.Doc

四、架构设计｜Architecture
原标题：全局本地依赖隔离冲突规避
简介：Mock 接口服务快速搭建实操，搭建模拟后端接口，自定义返回数据、延迟响应，前端开发阶段无需依赖真实后端服务。
 | 原文链接：http://wiki.zfpdg7.asia/arts/485116.Doc

原标题：golang 系统设计传输加密 tls 配置要点
简介：golang go 并发模式 or‑channel 信号合并，合并多个 done 信号，任意一个完成触发退出逻辑。
 | 原文链接：http://wiki.zfpdg7.asia/arts/415002.Doc

原标题：golang 信号量控制并发数量
简介：golang csv 百万级数据导入数据库，流式读取 csv 分批写入数据库，避免一次性加载全部数据。
 | 原文链接：http://wiki.zfpdg7.asia/arts/481659.Doc

原标题：golang websocket 服务端开发
简介：golang wasm webassembly go 编译，go 编译为 wasm，浏览器执行 go 代码，拓展 go 运行场景。
 | 原文链接：http://wiki.zfpdg7.asia/arts/245592.Doc

原标题：设计思考：API网关和BFF职责边界划分
简介：特殊输入字符过滤解析防护，过滤用户输入特殊字符，防止解析报错，规避恶意字符带来业务异常。
 | 原文链接：http://wiki.zfpdg7.asia/arts/152185.Doc

原标题：方案设计：接口版本管理架构向前兼容策略
简介：golang cgo 内存管理 C 与 Go 内存，区分 Go 内存 C 堆内存，防止 cgo 内存泄漏，正确释放 C 内存。
 | 原文链接：http://wiki.zfpdg7.asia/arts/239419.Doc

原标题：内存广播本地进程消息通知
简介：golang rate 令牌桶限流器源码理解，拆解令牌桶限流核心逻辑，理解令牌生成消耗，掌握限流底层原理。
 | 原文链接：http://wiki.zfpdg7.asia/arts/564525.Doc

原标题：Debug：分页偏移量过大数据库查询性能暴跌
简介：多实例部署 Session 共享方案，多服务实例部署场景，实现 Session 共享，保证用户登录状态跨实例生效。
 | 原文链接：http://wiki.zfpdg7.asia/arts/301048.Doc

原标题：全局本地依赖隔离冲突规避
简介：GitHub Markdown 文档语法汇总，整理 Markdown 常用语法，编写仓库 README、文档，提升开源项目文档排版质量。
 | 原文链接：http://wiki.zfpdg7.asia/arts/374282.Doc

原标题：文件编码统一随机乱码修复
简介：golang delve 远程调试 go 线上程序，delve 远程调试，线上环境附加进程调试排查线上 bug。
 | 原文链接：http://wiki.zfpdg7.asia/arts/907384.Doc

原标题：golang gin 静态资源访问配置
简介：数值 key 浮点匹配异常规避，避免浮点数作为 Redis 等存储的 key，防止精度问题引发 key 匹配失败。
 | 原文链接：http://wiki.zfpdg7.asia/arts/383930.Doc

原标题：前端错误监控上报系统搭建
简介：golang slice 切片底层原理与坑点，切片扩容、截取、底层数组共享，规避切片修改互相影响数据。
 | 原文链接：http://wiki.zfpdg7.asia/arts/073360.Doc

原标题：防火墙 IP 白名单回调接口放行
简介：Docker 容器入门镜像实操教程，介绍 Docker 基础概念，演示镜像拉取、容器启停，帮助新手建立容器化开发认知。
 | 原文链接：http://wiki.zfpdg7.asia/arts/133656.Doc

原标题：方案设计：高可用Redis集群架构选型对比
简介：golang 自定义 pprof 扩展业务指标，扩展 pprof，输出业务自定义指标，结合性能数据分析业务状态。
 | 原文链接：http://wiki.zfpdg7.asia/arts/582762.Doc

原标题：避坑：Nginx配置错误导致请求丢失Header
简介：golang mysql 事务回滚异常处理，Go MySQL 事务异常捕获，正确回滚事务，保证异常场景数据回滚。
 | 原文链接：http://wiki.zfpdg7.asia/arts/526000.Doc

原标题：入门实践：使用模板快速生成项目脚手架
简介：golang go http 静态文件禁止目录遍历，http.FileServer 防止../ 路径穿越，了解底层安全实现。
 | 原文链接：http://wiki.zfpdg7.asia/arts/011776.Doc

原标题：架构复盘：多实例部署业务状态无状态改造
简介：golang 系统信号信号量处理，Go 处理系统各类信号，SIGINT、SIGTERM，实现程序可控退出。
 | 原文链接：http://wiki.zfpdg7.asia/arts/373936.Doc

原标题：轻量 API 后端接口服务快速开发
简介：axios 二次封装请求拦截处理，对 axios 做二次封装，统一请求拦截响应拦截，处理错误、token 自动刷新。
 | 原文链接：http://wiki.zfpdg7.asia/arts/584007.Doc

?
