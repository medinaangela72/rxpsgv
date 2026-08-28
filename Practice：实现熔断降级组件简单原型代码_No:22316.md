最新前沿技术资讯

一、入门教程｜Getting Started
原标题：Practice：实现熔断降级组件简单原型代码
简介：golang os.Exit 退出程序注意 defer 不执行，os.Exit 会直接退出，不会执行 defer，优雅退出不要直接 os.Exit。
 | 原文链接：http://www.blog.maupu.cn/jingyingj/71900023.shtml

原标题：部署实践：Nginx反向代理传递真实客户端IP
简介：golang redis scan 遍历 key 避免阻塞，使用 scan 迭代遍历 redis 键，不用 keys 命令，防止阻塞 redis 服务。
 | 原文链接：http://www.blog.maupu.cn/jingyingj/67894284.shtml

原标题：Practice：模拟网络抖动验证服务容错能力
简介：golang grpc metadata 元数据透传，metadata 传递 traceId、鉴权信息，全链路透传上下文信息。
 | 原文链接：http://www.blog.maupu.cn/jingyingj/53129552.shtml

原标题：Shell 运维脚本服务器效率提升
简介：手写简易 MQ 理解消息存储消费，手写极简消息队列 Demo，理解消息存储、投递、消费完整流程。
 | 原文链接：http://www.blog.maupu.cn/jingyingj/33693898.shtml

原标题：Issue：文件编码混合GBKUTF‑8乱码随机出现
简介：golang go 变量逃逸场景汇总，切片、指针、返回局部变量引发逃逸，变量分配到堆影响 GC。
 | 原文链接：http://www.blog.maupu.cn/jingyingj/60893999.shtml

原标题：分页逻辑错误数据漏查修复
简介：golang go 项目依赖冲突解决完整思路，定位冲突包，replace、exclude、升级降级解决版本冲突。
 | 原文链接：http://www.blog.maupu.cn/jingyingj/94219330.shtml

原标题：golang 系统设计逻辑删除物理删除选型对比
简介：浏览器缓存强制刷新方案，设置 HTTP 缓存头，处理浏览器缓存旧静态资源，让用户加载更新后的页面。
 | 原文链接：http://www.blog.maupu.cn/jingyingj/40967305.shtml

原标题：前端虚拟列表大数据渲染优化
简介：golang os 进程 pid 获取父进程 pid，os.Getpid 获取进程 id，获取父进程 pid，进程间识别。
 | 原文链接：http://www.blog.maupu.cn/jingyingj/41667396.shtml

原标题：golang 系统设计代码评审关注点 checklist 清单
简介：环境变量不生效问题修复，排查环境变量加载顺序、作用域问题，修复环境变量读取不到的异常。
 | 原文链接：http://www.blog.maupu.cn/jingyingj/35402981.shtml

原标题：golang 系统设计链路数据存储选型对比讲解
简介：缓存穿透防护保护数据库，实现缓存穿透防护手段，拦截不存在的数据查询，避免请求直接打穿数据库。
 | 原文链接：http://www.blog.maupu.cn/jingyingj/68696229.shtml

原标题：golang 系统设计雪花算法 id 原理剖析
简介：nestjs 框架模块化项目搭建，从零搭建 NestJS 项目，模块化拆分业务，搭建规范后端项目骨架。
 | 原文链接：http://www.blog.maupu.cn/jingyingj/36803350.shtml

原标题：golang 系统设计技术债务识别登记治理思路
简介：消息队列消费堆积扩容处理，消息大量堆积时，扩容消费实例，优化消费逻辑，加快消息处理速度。
 | 原文链接：http://www.blog.maupu.cn/jingyingj/84664413.shtml

原标题：golang 系统设计配置本地缓存降级策略方案
简介：golang go 并发模式 errgroup 使用，errgroup 结合 context，协程组，任意协程出错整体取消任务。
 | 原文链接：http://www.blog.maupu.cn/jingyingj/75795411.shtml

原标题：golang 系统设计请求签名校验完整方案
简介：golang 系统 IO 阻塞 goroutine 场景，理解系统调用阻塞 M，P 会调度其他 M，掌握 go 调度行为。
 | 原文链接：http://www.blog.maupu.cn/jingyingj/26520725.shtml

原标题：golang 系统设计消息体序列化选型对比
简介：golang cobra 命令行参数配置绑定，cobra 绑定配置文件环境变量命令行参数，多源配置合并。
 | 原文链接：http://www.blog.maupu.cn/jingyingj/45964370.shtml

原标题：SSH 密钥配置 GitHub 免密登录
简介：golang math 包常用数学函数，绝对值取整平方根三角函数，业务数学计算工具。
 | 原文链接：http://www.blog.maupu.cn/jingyingj/90953121.shtml

原标题：开发测试生产多环境配置区分
简介：后端分页查询逻辑代码实现，编写后端分页接口，处理页码、每页条数参数，优化大数据量查询返回结果。
 | 原文链接：http://www.blog.maupu.cn/jingyingj/69732933.shtml

原标题：新手指南：看懂开源项目的Issue与PR
简介：golang 网卡 ip 读取网络信息获取，程序读取本机网卡 IP，多网卡环境筛选业务使用 IP 地址。
 | 原文链接：http://www.blog.maupu.cn/jingyingj/27261993.shtml

原标题：Troubleshooting：WSL文件权限问题大量踩坑
简介：golang time 时间比较 Before After Equal，时间比较不要直接减，使用内置方法判断时间先后。
 | 原文链接：http://www.blog.maupu.cn/jingyingj/09695433.shtml

原标题：坑点：gitrebase操作失误，代码提交丢失
简介：GET POST 接口请求参数处理，讲解两种请求方式参数传递区别，演示参数接收、解析、校验，适配不同接口调用场景。
 | 原文链接：http://www.blog.maupu.cn/jingyingj/16631665.shtml

原标题：service‑worker 离线缓存实践
简介：golang base64 编码解码实操，Go Base64 编码解码示例，处理业务场景 Base64 格式数据转换。
 | 原文链接：http://www.blog.maupu.cn/jingyingj/08943417.shtml

原标题：monorepo 项目多包管理最佳实践
简介：golang 大内存分配 GC 抖动规避，避免瞬时大量对象创建，分批处理，防止 GC 抖动业务抖动。
 | 原文链接：http://www.blog.maupu.cn/jingyingj/01089592.shtml

原标题：排错：DockerCompose依赖顺序启动顺序坑
简介：静态站点自动部署发布方案，配置流水线，代码更新自动构建静态站点并且部署上线，简化发布。
 | 原文链接：http://www.blog.maupu.cn/jingyingj/34341881.shtml

原标题：记一次内存Swap被大量使用系统响应缓慢
简介：golang gin 框架接口开发实战，Gin 框架搭建 HTTP 服务，开发增删改查接口，快速完成后端接口开发。
 | 原文链接：http://www.blog.maupu.cn/jingyingj/13889007.shtml

原标题：golang 系统设计死信队列 dlq 业务落地完整流程
简介：golang 处理连接被重置 reset 错误，识别 connection reset by peer，对端关闭连接异常处理逻辑。
 | 原文链接：http://www.blog.maupu.cn/jingyingj/80468862.shtml

原标题：系统字符集统一乱码修复
简介：golang tidb 数据库 go 项目适配，go 程序适配 tidb，兼容 mysql 协议，分布式数据库业务开发。
 | 原文链接：http://www.blog.maupu.cn/jingyingj/47539277.shtml

原标题：安全笔记：HTTPSTLS配置安全加固实践
简介：golang 僵尸进程处理 go 程序，正确等待子进程退出，避免产生僵尸进程，占用系统进程表。
 | 原文链接：http://www.blog.maupu.cn/jingyingj/61879339.shtml

原标题：分布式 ID 全局唯一生成方案
简介：跨库查询性能优化处理，减少跨库关联查询，做数据冗余或者中间表，规避跨库查询性能低下。
 | 原文链接：http://www.blog.maupu.cn/jingyingj/82346621.shtml

原标题：golang 系统设计降级策略开关配置方案
简介：本地简易配置中心动态管理，搭建轻量本地配置中心，业务动态读取配置，修改配置不重启服务。
 | 原文链接：http://www.blog.maupu.cn/jingyingj/42817749.shtml

原标题：网络读取超时设置连接挂起防护
简介：golang k8s 客户端 client‑go 简单示例，client‑go 操作 k8s 资源，增删改查 pod deployment 等资源对象。
 | 原文链接：http://www.blog.maupu.cn/jingyingj/38613909.shtml

原标题：golang 系统设计技术方案文档模板参考
简介：golang word 文档生成处理 go 方案，go 生成 word 文档报表，填充文本表格，输出 docx 文件。
 | 原文链接：http://www.blog.maupu.cn/jingyingj/13473221.shtml

原标题：实践：API错误统一捕获与告警通知实践
简介：Nginx 反向代理路由配置实战，配置 Nginx 反向代理，实现请求转发、路由分发，掌握 Nginx 基础配置能力。
 | 原文链接：http://www.blog.maupu.cn/jingyingj/49390809.shtml

原标题：golang 系统设计压测环境隔离避免影响生产
简介：nodejs 消息队列消费服务开发，Node 开发消息队列消费端，监听队列消息执行业务逻辑，异步解耦业务。
 | 原文链接：http://www.blog.maupu.cn/jingyingj/94852327.shtml

原标题：HelloWorld：快速上手新项目最小可运行示例
简介：前端权限路由动态生成实现，根据后端返回权限，动态生成前端路由菜单，实现页面权限控制。
 | 原文链接：http://www.blog.maupu.cn/jingyingj/86839170.shtml

原标题：Performance：后端接口性能优化完整分析流程
简介：后端登录鉴权模块完整开发，实现完整登录模块，包含账号校验、令牌发放、接口鉴权整套能力。
 | 原文链接：http://www.blog.maupu.cn/jingyingj/04446914.shtml

原标题：golang 系统设计监控缺失指标补全完整流程
简介：git stash 代码暂存切换分支，使用 stash 暂存未提交代码，切换其他分支处理紧急任务，再恢复原有工作进度。
 | 原文链接：http://www.blog.maupu.cn/jingyingj/06061910.shtml

原标题：golang redis hyperloglog 基数统计
简介：golang go 零停机升级实践要点，socket 继承，流量无损，旧连接处理完毕后旧进程退出。
 | 原文链接：http://www.blog.maupu.cn/jingyingj/27657450.shtml

原标题：nestjs 全局返回格式统一处理
简介：开发生产环境资源路径统一，对齐开发环境与生产环境资源路径，防止本地正常上线后资源找不到。
 | 原文链接：http://www.blog.maupu.cn/jingyingj/64416508.shtml

原标题：golang nginx 反向代理 go 服务配置
简介：文件锁正确使用避免死锁，合理使用文件锁，控制多进程访问同一个文件，规避文件锁死锁现象。
 | 原文链接：http://www.blog.maupu.cn/jingyingj/95478518.shtml

原标题：设计思考：缓存分层架构设计与失效处理策略
简介：静态网页 HTML CSS 快速入门实战，通过简单页面案例讲解标签、样式布局，从零编写页面，理解网页基础渲染原理。
 | 原文链接：http://www.blog.maupu.cn/jingyingj/39153413.shtml


二、踩坑排错｜Troubleshooting
原标题：golang 系统设计定时任务执行超时中断防护
简介：手写简易 ORM 理解对象映射，手写极简 ORM 示例，理解对象与数据库表字段映射底层原理。
 | 原文链接：http://www.blog.maupu.cn/jingyingj/18375609.shtml

原标题：全量回归测试提升代码质量
简介：golang 信号触发配置重载实践，收到 SIGUSR1 信号重新加载配置，线上无需重启刷新配置。
 | 原文链接：http://www.blog.maupu.cn/jingyingj/62064466.shtml

原标题：项目依赖安全扫描漏洞防范
简介：接口限流逻辑简单模拟实现，编写简易限流逻辑，限制接口访问频次，保护服务，避免短时间大量请求压垮系统。
 | 原文链接：http://www.blog.maupu.cn/jingyingj/16594287.shtml

原标题：性能复盘：GC停顿过长业务卡顿优化记录
简介：golang rabbitmq 死信队列延迟消息，rabbitmq 实现死信、延迟消息，处理延时业务场景。
 | 原文链接：http://www.blog.maupu.cn/jingyingj/16477951.shtml

原标题：开源实践：Fork上游项目，持续同步更新代码
简介：慢查询分析索引调优数据库实战，抓取慢查询，分析执行计划，优化索引，解决数据库慢查询拖慢业务。
 | 原文链接：http://www.blog.maupu.cn/jingyingj/93438720.shtml

原标题：golang 系统设计 http3 quic 简单原理了解
简介：静态资源 404 路径打包修复，修复打包后静态资源访问 404，调整资源输出路径，保证资源正常加载。
 | 原文链接：http://www.blog.maupu.cn/jingyingj/86198448.shtml

原标题：实践：Git工作流主干开发团队协作实践
简介：golang go panic 合理使用边界，panic 只用于不可恢复程序错误，业务逻辑禁止直接 panic。
 | 原文链接：http://www.blog.maupu.cn/jingyingj/90231071.shtml

原标题：golang 系统设计契约测试接口兼容性保障思路
简介：golang 配置中心 apollo go 客户端，apollo go sdk 读取配置，配置变更自动热更新无需重启服务。
 | 原文链接：http://www.blog.maupu.cn/jingyingj/89013192.shtml

原标题：golang 限流熔断降级完整示例
简介：golang go‑zero 分布式锁组件使用，go‑zero 内置 redis 分布式锁，业务直接调用实现并发控制。
 | 原文链接：http://www.blog.maupu.cn/jingyingj/48038935.shtml

原标题：优化实践：接口返回字段裁剪减少报文大小
简介：golang docker 多阶段构建 go 镜像，Go 项目 Docker 多阶段构建，编译与运行阶段分离，大幅度缩减最终镜像体积，提升镜像分发效率。
 | 原文链接：http://www.blog.maupu.cn/jingyingj/42783307.shtml

原标题：golang 系统设计 saga 事务补偿模式实现思路
简介：OOMKilled 容器被杀完整排查，排查容器被 OOM 终止完整流程，区分程序内存泄露和容器内存限制过小。
 | 原文链接：http://www.blog.maupu.cn/jingyingj/37450043.shtml

原标题：golang 系统设计 go netpoll 多路复用简单理解
简介：内存泄漏定位分析完整流程，分享内存泄漏排查步骤，定位没有释放的对象，解决内存持续上涨问题。
 | 原文链接：http://www.blog.maupu.cn/jingyingj/10505816.shtml

原标题：Practice：实现熔断降级组件简单原型代码
简介：后端登录鉴权模块完整开发，实现完整登录模块，包含账号校验、令牌发放、接口鉴权整套能力。
 | 原文链接：http://www.blog.maupu.cn/jingyingj/30559850.shtml

原标题：Hands‑on：简易布隆过滤器实现与测试验证
简介：多实例部署 Session 共享方案，多服务实例部署场景，实现 Session 共享，保证用户登录状态跨实例生效。
 | 原文链接：http://www.blog.maupu.cn/jingyingj/41249205.shtml

原标题：开源实践：给开源项目写单元测试贡献代码
简介：golang excel 简单读写操作示例，Go 实现 Excel 简单读写，业务数据导出 Excel 报表。
 | 原文链接：http://www.blog.maupu.cn/jingyingj/26710200.shtml

原标题：gitignore 文件编写过滤规则
简介：golang https 客户端跳过证书校验，开发测试环境跳过 tls 证书校验，仅用于内网测试禁止生产使用。
 | 原文链接：http://www.blog.maupu.cn/jingyingj/59388867.shtml

原标题：实践：API错误统一捕获与告警通知实践
简介：golang 参数校验业务接口处理，Go 接口入参参数校验，拦截非法入参，减少业务层参数判断代码。
 | 原文链接：http://www.blog.maupu.cn/jingyingj/21723420.shtml

原标题：css 变量主题切换方案实现
简介：golang 容器健康检查接口开发，Go 开发 HTTP 健康接口，供容器编排工具探测实例存活状态。
 | 原文链接：http://www.blog.maupu.cn/jingyingj/60321538.shtml

原标题：模拟登录鉴权权限判断示例
简介：golang mysql 长连接检测保活设置，配置 mysql 连接保活检测，剔除失效连接，避免拿到断开无效数据库连接。
 | 原文链接：http://www.blog.maupu.cn/jingyingj/50765221.shtml

原标题：golang 系统设计配置敏感信息加密存储方案
简介：golang contract 契约测试微服务，微服务契约测试，保证接口变更不破坏调用方，提前发现兼容性问题。
 | 原文链接：http://www.blog.maupu.cn/jingyingj/80708343.shtml

原标题：开发代理服务网络限制解决
简介：特殊输入字符过滤解析防护，过滤用户输入特殊字符，防止解析报错，规避恶意字符带来业务异常。
 | 原文链接：http://www.blog.maupu.cn/jingyingj/41977339.shtml

原标题：超大数据集分页性能优化方案
简介：golang 项目目录分层规范设计，Go 后端项目目录分层规范，按领域分层，提高项目可读性可维护性。
 | 原文链接：http://www.blog.maupu.cn/jingyingj/16430524.shtml

原标题：实战：单元测试+集成测试完整项目落地实践
简介：golang 优雅处理 http 重定向逻辑，自定义控制 http 重定向跳转次数，防止无限重定向死循环。
 | 原文链接：http://www.blog.maupu.cn/jingyingj/70779868.shtml

原标题：内网 DNS 不稳定随机报错排查
简介：golang 分库分表 id 路由规则设计，分库分表 id 路由算法，id 映射库表，数据均匀打散避免热点分片。
 | 原文链接：http://www.blog.maupu.cn/jingyingj/27875589.shtml

原标题：golang 系统设计定时任务分片执行分布式思路
简介：golang 数据库连接池参数调优详解，最大连接空闲连接最大生命周期，结合业务合理配置避免资源浪费。
 | 原文链接：http://www.blog.maupu.cn/jingyingj/85704773.shtml

原标题：开发复盘：异步消息解耦业务流程落地实践
简介：内存泄漏定位分析完整流程，分享内存泄漏排查步骤，定位没有释放的对象，解决内存持续上涨问题。
 | 原文链接：http://www.blog.maupu.cn/jingyingj/42186328.shtml

原标题：避坑：正则回溯引发CPU占满DoS风险
简介：nestjs 框架模块化项目搭建，从零搭建 NestJS 项目，模块化拆分业务，搭建规范后端项目骨架。
 | 原文链接：http://www.blog.maupu.cn/jingyingj/45342952.shtml

原标题：Issue：WSL2内存持续暴涨不自动释放
简介：golang race 检测器性能开销，race 检测器有性能损耗，只用于测试环境，禁止生产开启 race。
 | 原文链接：http://www.blog.maupu.cn/jingyingj/12573557.shtml

原标题：golang docker 镜像构建最佳实践
简介：Nginx 静态代理负载均衡全套配置，一套 Nginx 配置示例，覆盖静态资源、反向代理、负载均衡场景。
 | 原文链接：http://www.blog.maupu.cn/jingyingj/00647079.shtml

原标题：golang 系统设计定时任务失败重试告警实现
简介：golang 容器信号转发处理问题修复，docker/k8s 正确转发 SIGTERM 信号，保证 go 程序收到信号优雅退出。
 | 原文链接：http://www.blog.maupu.cn/jingyingj/00940665.shtml

原标题：设计思考：防雪崩，系统过载保护架构设计
简介：golang 处理连接被重置 reset 错误，识别 connection reset by peer，对端关闭连接异常处理逻辑。
 | 原文链接：http://www.blog.maupu.cn/jingyingj/16315829.shtml

原标题：开发记录：网关实现接口鉴权、限流、日志打印
简介：golang sync/atomic 原子操作使用注意，理解原子操作内存顺序，规避原子操作错误使用带来 bug。
 | 原文链接：http://www.blog.maupu.cn/jingyingj/60156736.shtml

原标题：css 变量主题切换方案实现
简介：程序性能指标 CPU 内存监控，讲解基础性能指标含义，简单实现监控采集，初步定位程序运行性能瓶颈。
 | 原文链接：http://www.blog.maupu.cn/jingyingj/79238188.shtml

原标题：Cookie Session 会话状态管理
简介：golang go1.18 + 泛型基础实操，go 泛型基础语法，泛型函数泛型类型，实现通用工具函数。
 | 原文链接：http://www.blog.maupu.cn/jingyingj/88433854.shtml

原标题：实践：代码提交前自动格式化校验配置实践
简介：golang go yaml 解析自定义类型，yaml 自定义序列化，时间、特殊类型自定义解析逻辑。
 | 原文链接：http://www.blog.maupu.cn/jingyingj/50038582.shtml

原标题：golang 系统设计内部服务熔断降级配置思路
简介：WSL 内存上限限制防止资源耗尽，修改 WSL 内存上限配置，避免 WSL 占用主机大量内存资源。
 | 原文链接：http://www.blog.maupu.cn/jingyingj/78902282.shtml

原标题：GC 垃圾回收优化降低 CPU 占用
简介：golang 网卡 ip 读取网络信息获取，程序读取本机网卡 IP，多网卡环境筛选业务使用 IP 地址。
 | 原文链接：http://www.blog.maupu.cn/jingyingj/03527951.shtml

原标题：golang mysql limit 大分页优化
简介：接口压测定位系统性能瓶颈，使用压测工具对接口施压，观察指标，定位系统性能瓶颈点。
 | 原文链接：http://www.blog.maupu.cn/jingyingj/19549635.shtml

原标题：golang docker 部署 redis 配置要点
简介：golang ioutil 已废弃替换方案，ioutil 废弃之后替换为 os io 包函数，更新旧项目代码。
 | 原文链接：http://www.blog.maupu.cn/jingyingj/72005446.shtml

原标题：设计思考：缓存分层架构设计与失效处理策略
简介：monorepo 项目多包管理最佳实践，monorepo 仓库管理多子包，统一版本管理，处理包之间互相依赖。
 | 原文链接：http://www.blog.maupu.cn/jingyingj/48264292.shtml

三、实战开发｜Practice
原标题：golang 系统设计 ide 配置 go 开发效率提升技巧
简介：安全组端口开放网络访问，调整服务器安全组规则，开放业务需要端口，恢复外部网络访问服务。
 | 原文链接：http://www.blog.maupu.cn/jingyingj/04975217.shtml

原标题：golang 系统设计故障预案编写模板参考示例
简介：golang testify testify 断言库使用，testify assert require 断言，简化单元测试断言代码。
 | 原文链接：http://www.blog.maupu.cn/jingyingj/41941333.shtml

原标题：OpenSource：开源项目贡献者协作流程规范
简介：golang gin 框架接口开发实战，Gin 框架搭建 HTTP 服务，开发增删改查接口，快速完成后端接口开发。
 | 原文链接：http://www.blog.maupu.cn/jingyingj/96235696.shtml

原标题：golang 系统设计网关灰度流量切分简单方案
简介：golang embed 目录读取文件列表，embed 嵌入整个目录，读取目录下全部文件，做静态资源服务。
 | 原文链接：http://www.blog.maupu.cn/jingyingj/14945393.shtml

原标题：多套环境灵活切换配置方案
简介：不必要字符转义关闭业务异常，关闭多余自动转义逻辑，防止业务数据被错误转义，破坏原始数据。
 | 原文链接：http://www.blog.maupu.cn/jingyingj/94200443.shtml

原标题：实践：前后端分离项目登录状态保持完整方案
简介：golang go mod graph 查看依赖关系，go mod graph 打印依赖树，定位间接依赖来源，解决版本冲突。
 | 原文链接：http://www.blog.maupu.cn/jingyingj/29298984.shtml

原标题：架构笔记：冷热数据分离架构设计与迁移
简介：开发代理服务网络限制解决，搭建本地代理服务，解决开发环境网络访问受限，实现外部接口正常调用。
 | 原文链接：http://www.blog.maupu.cn/jingyingj/86737731.shtml

原标题：实践：OpenAPI自动生成接口文档完整实践
简介：golang docker 多阶段构建 go 镜像，Go 项目 Docker 多阶段构建，编译与运行阶段分离，大幅度缩减最终镜像体积，提升镜像分发效率。
 | 原文链接：http://www.blog.maupu.cn/jingyingj/29152114.shtml

原标题：安全笔记：文件下载接口路径校验安全
简介：golang goroutine 泄露常见场景汇总，channel 阻塞、context 忘记取消，导致协程无法退出发生泄露。
 | 原文链接：http://www.blog.maupu.cn/jingyingj/97439804.shtml

原标题：golang 系统设计自动化测试 ci 流水线集成实操
简介：golang interface 接口使用避坑，interface 判 nil 坑点，理解接口底层结构，避免判空逻辑失效。
 | 原文链接：http://www.blog.maupu.cn/jingyingj/51618651.shtml

原标题：设计思考：API网关和BFF职责边界划分
简介：系统文件描述符上限调大，调高操作系统文件描述符上限，解决高并发场景打开文件报错。
 | 原文链接：http://www.blog.maupu.cn/jingyingj/83747035.shtml

原标题：golang 系统设计 protobuf json 性能对比
简介：golang k8s secret 敏感配置加载，加载 k8s secret 存储密钥密码，敏感信息不存放配置文件。
 | 原文链接：http://www.blog.maupu.cn/jingyingj/50370216.shtml

原标题：Architecture：文件处理服务架构大文件内存规避
简介：golang go 代码覆盖率线上统计，单元测试覆盖率统计，找出未测试代码分支，提升测试质量。
 | 原文链接：http://www.blog.maupu.cn/jingyingj/60684858.shtml

原标题：golang k8s devops 流水线简单思路
简介：文件读写与异常捕获代码示例，演示文件读取写入操作，增加异常捕获逻辑，规避文件不存在、权限不足导致崩溃。
 | 原文链接：http://www.blog.maupu.cn/jingyingj/91591354.shtml

原标题：零基础理解读写分离基础思想
简介：golang 内存 dump 线上堆快照采集，线上生成内存 dump 文件，线下分析，定位内存泄漏问题。
 | 原文链接：http://www.blog.maupu.cn/jingyingj/22037877.shtml

原标题：nodejs 读取大文件 csv 处理方案
简介：内存溢出问题现象识别排查，识别内存溢出现象，梳理排查方向，定位内存持续上涨引发服务崩溃问题。
 | 原文链接：http://www.blog.maupu.cn/jingyingj/35051306.shtml

原标题：Performance：避免全表扫描索引失效场景汇总
简介：golang https 客户端跳过证书校验，开发测试环境跳过 tls 证书校验，仅用于内网测试禁止生产使用。
 | 原文链接：http://www.blog.maupu.cn/jingyingj/71026374.shtml

原标题：golang 批量任务协程控制防雪崩
简介：golang tcp_NODELAY 关闭延迟发送，设置 tcp_NODELAY，关闭 Nagle 算法，降低小包请求延迟。
 | 原文链接：http://www.blog.maupu.cn/jingyingj/95919265.shtml

原标题：Debug：消息队列死信队列堆积无人处理业务阻塞
简介：手写简易 MQ 理解消息存储消费，手写极简消息队列 Demo，理解消息存储、投递、消费完整流程。
 | 原文链接：http://www.blog.maupu.cn/jingyingj/55669565.shtml

原标题：golang ci 流水线漏洞扫描依赖检查
简介：WebSocket 聊天室实时通讯开发，基于 WebSocket 搭建简易聊天室，实现多人消息广播实时聊天效果。
 | 原文链接：http://www.blog.maupu.cn/jingyingj/09685465.shtml

原标题：Nginx 请求头大小上限调整
简介：golang redis hyperloglog 基数统计，hyperloglog 统计 UV 基数，海量数据去重统计，极低内存开销。
 | 原文链接：http://www.blog.maupu.cn/jingyingj/67693340.shtml

原标题：Architecture：中小型后端服务整体架构设计复盘
简介：golang 异步任务队列 worker 池开发，任务入数据库或 redis，worker 池消费执行，异步处理耗时业务。
 | 原文链接：http://www.blog.maupu.cn/jingyingj/61877818.shtml

原标题：golang redis 缓存预热实现思路
简介：golang gin 路由动态注册实现方案，根据配置动态注册接口路由，无需硬编码路由，适配动态业务模块。
 | 原文链接：http://www.blog.maupu.cn/jingyingj/16467339.shtml

原标题：开发记录：短信发送服务封装，失败重试策略
简介：Mock 接口服务快速搭建实操，搭建模拟后端接口，自定义返回数据、延迟响应，前端开发阶段无需依赖真实后端服务。
 | 原文链接：http://www.blog.maupu.cn/jingyingj/08326772.shtml

原标题：包管理器依赖冲突解决方案
简介：vite 项目配置与构建提速技巧，讲解 vite 配置优化手段，提升开发热更新速度与生产构建打包效率。
 | 原文链接：http://www.blog.maupu.cn/jingyingj/36796712.shtml

原标题：实战项目：实现简单缓存服务缓存穿透击穿防护
简介：golang rsa 公钥加密私钥解密，rsa 非对称加密，大文件分块加密，处理非对称加密长度限制。
 | 原文链接：http://www.blog.maupu.cn/jingyingj/27970141.shtml

原标题：golang 系统设计单元测试表驱动测试 table‑driven
简介：Git 标签版本标记发布管理，使用 Git 标签标记项目版本，打标签推送远程，用于版本发布、版本回溯。
 | 原文链接：http://www.blog.maupu.cn/jingyingj/19701056.shtml

原标题：性能笔记：压测如何定位真实系统瓶颈
简介：RPC 接口字段增减兼容处理，RPC 接口新增删除字段做好向前兼容，老版本服务不会解析报错崩溃。
 | 原文链接：http://www.blog.maupu.cn/jingyingj/30800178.shtml

原标题：Redis 热点 key 拆分降低集群压力
简介：golang docker compose 开发环境 go 服务，docker compose 编排 go 服务与中间件，本地一键拉起整套开发环境。
 | 原文链接：http://www.blog.maupu.cn/jingyingj/32148951.shtml

原标题：踩坑记录：浮点精度错误造成业务计算错误
简介：golang net.Listener 包装自定义监听器，包装 Listener 做连接计数、连接拦截，扩展网络能力。
 | 原文链接：http://www.blog.maupu.cn/jingyingj/53450705.shtml

原标题：入门实践：Git分支创建切换合并完整演示
简介：golang 数据库 ORM 框架选型对比，gorm xorm sqlx 对比各 ORM 优缺点，根据业务场景选型。
 | 原文链接：http://www.blog.maupu.cn/jingyingj/42545957.shtml

原标题：效率笔记：批量处理文本命令行工具实战案例
简介：golang redis hyperloglog 基数统计，hyperloglog 统计 UV 基数，海量数据去重统计，极低内存开销。
 | 原文链接：http://www.blog.maupu.cn/jingyingj/66469428.shtml

原标题：Hands‑on：简易短消息模板渲染组件实践
简介：golang go ring 环形容器循环队列，ring 环形链表实现循环队列，环形缓冲区业务场景。
 | 原文链接：http://www.blog.maupu.cn/jingyingj/57896898.shtml

原标题：调优方案：gzip压缩开启降低网络传输体积
简介：文件分片上传断点续传功能，实现文件分片上传，记录上传进度，支持断点续传大文件上传。
 | 原文链接：http://www.blog.maupu.cn/jingyingj/46620910.shtml

原标题：golang 系统设计读写分离架构示例
简介：golang 分布式 ID 雪花算法实现，Go 实现雪花算法，生成分布式全局唯一 ID，适配分库分表主键。
 | 原文链接：http://www.blog.maupu.cn/jingyingj/34962321.shtml

原标题：性能笔记：数据库表字段设计影响查询性能
简介：golang redis 客户端业务使用，Go Redis 客户端对接，实现缓存、计数器，适配各类 Redis 业务场景。
 | 原文链接：http://www.blog.maupu.cn/jingyingj/02124009.shtml

原标题：Git commit 钩子提交规范校验
简介：golang gin 参数绑定 query form json，掌握 Gin 多种参数绑定方式，适配不同请求格式参数读取。
 | 原文链接：http://www.blog.maupu.cn/jingyingj/81439476.shtml

原标题：Practice：实现接口mock动态返回不同响应
简介：请求工具封装统一异常处理，对网络请求做二次封装，统一捕获各类请求异常，标准化接口返回格式。
 | 原文链接：http://www.blog.maupu.cn/jingyingj/90586957.shtml

原标题：golang 系统设计限流熔断降级组合使用
简介：WSL 内存上限限制防止资源耗尽，修改 WSL 内存上限配置，避免 WSL 占用主机大量内存资源。
 | 原文链接：http://www.blog.maupu.cn/jingyingj/49143180.shtml

原标题：开发记录：业务错误告警邮件通知组件实践
简介：golang socket 文件描述符继承重启，父进程传递 listener fd 给子进程，实现 go 程序零停机热重启。
 | 原文链接：http://www.blog.maupu.cn/jingyingj/89369073.shtml

四、架构设计｜Architecture
原标题：项目目录结构规范化最佳实践
简介：服务器 Swap 关闭提升响应速度，关闭服务器 Swap 交换分区，避免内存交换磁盘拖慢程序响应性能。
 | 原文链接：http://www.blog.maupu.cn/jingyingj/78514192.shtml

原标题：golang git 提交信息规范校验
简介：gRPC 服务端客户端入门示例，搭建 gRPC 服务端与调用客户端，学习 protobuf 定义，掌握 RPC 基础开发流程。
 | 原文链接：http://www.blog.maupu.cn/jingyingj/82925511.shtml

原标题：运维笔记：服务器定时任务运维脚本编写
简介：golang 环境变量读取与类型转换，读取系统环境变量，做类型转换默认值处理，适配多环境部署。
 | 原文链接：http://www.blog.maupu.cn/jingyingj/14519607.shtml

原标题：Practice：模拟网络抖动验证服务容错能力
简介：前端 pdf 预览渲染方案对比，对比前端 PDF 预览库，分析性能、兼容性，给出业务选型参考。
 | 原文链接：http://www.blog.maupu.cn/jingyingj/03725935.shtml

原标题：分布式事务最终一致性实现
简介：golang gitlab ci go 项目流水线编写，gitlab ci 流水线执行单元测试、静态检查、构建推送镜像。
 | 原文链接：http://www.blog.maupu.cn/jingyingj/84785362.shtml

原标题：安全复盘：环境变量密钥泄露风险与防护
简介：多实例部署 Session 共享方案，多服务实例部署场景，实现 Session 共享，保证用户登录状态跨实例生效。
 | 原文链接：http://www.blog.maupu.cn/jingyingj/57563026.shtml

原标题：大事务拆分回滚日志暴涨解决
简介：程序信号中断退出处理逻辑，捕获系统中断信号，执行资源释放、关闭连接，实现程序优雅退出。
 | 原文链接：http://www.blog.maupu.cn/jingyingj/17504824.shtml

原标题：Debug：长连接未设置心跳，连接僵死不回收
简介：golang dns 自定义解析器实现，自定义 dns 解析，指定 dns 服务器，控制域名解析逻辑，适配内网环境。
 | 原文链接：http://www.blog.maupu.cn/jingyingj/18685629.shtml

原标题：golang 系统设计缓存优化落地实操指南
简介：css 动画性能优化 GPU 加速，优化 CSS 动画，使用 GPU 加速属性，避免动画过程页面卡顿掉帧。
 | 原文链接：http://www.blog.maupu.cn/jingyingj/36183799.shtml

原标题：Troubleshooting：代理环境下证书校验失败HTTPS报错
简介：跨域偶现失败配置修复，解决跨域问题时而复现时而正常，定位配置漏配、请求头异常等隐性问题。
 | 原文链接：http://www.blog.maupu.cn/jingyingj/13384816.shtml

原标题：Performance：长连接管理优化减少连接重建开销
简介：golang go 爬虫代理池轮换使用，http 代理池轮换，请求自动切换代理 IP，突破访问限制。
 | 原文链接：http://www.blog.maupu.cn/jingyingj/78196192.shtml

原标题：从零学习简单分布式ID生成思路
简介：从零编写简易 CLI 命令行工具，通过实战案例实现基础命令交互，理解命令行程序执行逻辑，产出可运行小工具。
 | 原文链接：http://www.blog.maupu.cn/jingyingj/08823470.shtml

原标题：Debug：静态资源缓存策略错误，用户看不到更新
简介：安全组端口开放网络访问，调整服务器安全组规则，开放业务需要端口，恢复外部网络访问服务。
 | 原文链接：http://www.blog.maupu.cn/jingyingj/89464296.shtml

原标题：golang 系统设计配置热更新不重启服务实现
简介：CI 流水线构建失败日志排查，阅读 CI 流水线输出日志，定位构建脚本、依赖、环境导致流水线失败问题。
 | 原文链接：http://www.blog.maupu.cn/jingyingj/89364330.shtml

原标题：HelloMarkdown：GitHubMarkdown完整语法速查
简介：golang httptest 模拟外部 http 服务，httptest.NewServer 模拟第三方 http 服务，单元测试 mock 外部接口。
 | 原文链接：http://www.blog.maupu.cn/jingyingj/44042566.shtml

原标题：nodejs 脚手架工具开发完整教程
简介：内网 DNS 不稳定随机报错排查，定位内网 DNS 抖动问题，配置备选 DNS，解决偶现域名解析失败。
 | 原文链接：http://www.blog.maupu.cn/jingyingj/20861956.shtml

原标题：golang makefile 自动化构建脚本
简介：golang go 爬虫 html 解析 goquery，goquery 解析 html 文档，css 选择器提取网页内容，实现网页数据抓取。
 | 原文链接：http://www.blog.maupu.cn/jingyingj/54735204.shtml

原标题：复盘总结：系统压测报告模板与分析思路
简介：并发数据覆盖加锁安全处理，多线程并发修改同一数据，增加锁机制，防止并发覆盖丢失更新数据。
 | 原文链接：http://www.blog.maupu.cn/jingyingj/10975514.shtml

?
