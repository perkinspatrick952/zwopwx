最新前沿技术资讯

一、入门教程｜Getting Started
原标题：Issue：文件句柄耗尽，服务缓慢卡死复盘
简介：golang 内存碎片问题识别与规避，大量小对象频繁分配产生内存碎片，通过对象池减少碎片。
 | 原文链接：http://wiki.skth0o.asia/arts/280039.Doc

原标题：记一次升级操作系统内核引发服务不稳定
简介：git rebase 整理提交历史实操，使用 rebase 整理杂乱提交记录，将多条提交合并，保持 git 提交历史干净线性。
 | 原文链接：http://wiki.skth0o.asia/arts/849385.Doc

原标题：golang 系统设计状态字段枚举约束设计思路
简介：OAuth2 第三方登录服务搭建，搭建 OAuth2 服务，支持第三方账号登录，实现授权登录能力。
 | 原文链接：http://wiki.skth0o.asia/arts/232495.Doc

原标题：开发复盘：异步消息解耦业务流程落地实践
简介：golang redis bitmap 位图业务实战，bitmap 做签到统计、用户状态标记，节省大量内存空间。
 | 原文链接：http://wiki.skth0o.asia/arts/178764.Doc

原标题：架构笔记：海量消息堆积架构处理能力设计
简介：golang sync.WaitGroup 协程等待控制，WaitGroup 控制一组协程等待全部执行完成，完成批量协程任务调度。
 | 原文链接：http://wiki.skth0o.asia/arts/288420.Doc

原标题：内网测试服务搭建团队调试
简介：防火墙 IP 白名单回调接口放行，配置防火墙白名单，放行第三方回调服务器 IP，接收回调请求正常。
 | 原文链接：http://wiki.skth0o.asia/arts/122037.Doc

原标题：开发复盘：大事务拆分优化业务性能实践
简介：端口占用释放资源重启服务，查找占用端口进程，结束占用进程，释放端口，让服务能够正常启动监听。
 | 原文链接：http://wiki.skth0o.asia/arts/151178.Doc

原标题：文件句柄上限调整上传随机失败
简介：golang benchmark 减少测试干扰，benchmark 执行循环 b.N，避免循环内部做非被测逻辑干扰结果。
 | 原文链接：http://wiki.skth0o.asia/arts/603375.Doc

原标题：nodejs 数据库连接池配置调优
简介：golang udp 服务端客户端开发示例，golang 实现 UDP 服务收发数据包，实现 udp 协议通信程序。
 | 原文链接：http://wiki.skth0o.asia/arts/487085.Doc

原标题：程序信号中断退出处理逻辑
简介：依赖版本冲突兼容修复方案，定位依赖版本冲突根源，通过版本约束、替换包，解决版本不兼容运行报错。
 | 原文链接：http://wiki.skth0o.asia/arts/552064.Doc

原标题：golang etcd 租约 lease 过期机制
简介：golang sync.Mutex 互斥锁正确模式，互斥锁 defer Unlock，锁粒度控制，避免锁范围过大。
 | 原文链接：http://wiki.skth0o.asia/arts/979415.Doc

原标题：安全复盘：业务登录暴力破解防护完整方案
简介：golang https 客户端跳过证书校验，开发测试环境跳过 tls 证书校验，仅用于内网测试禁止生产使用。
 | 原文链接：http://wiki.skth0o.asia/arts/157519.Doc

原标题：缓存穿透防护保护数据库
简介：前端静态缓存更新生效处理，修改静态资源版本标识，处理浏览器强缓存，让更新资源生效。
 | 原文链接：http://wiki.skth0o.asia/arts/260360.Doc

原标题：golang redis 事务 multi exec 使用
简介：golang goroutine 泄露常见场景汇总，channel 阻塞、context 忘记取消，导致协程无法退出发生泄露。
 | 原文链接：http://wiki.skth0o.asia/arts/198331.Doc

原标题：Issue：开源项目升级大版本后API不兼容踩坑
简介：golang base64 编码解码实操，Go Base64 编码解码示例，处理业务场景 Base64 格式数据转换。
 | 原文链接：http://wiki.skth0o.asia/arts/173676.Doc

原标题：golang 系统设计 mq 消息顺序性保证思路
简介：golang http 服务性能优化调参，调优 Go HTTP 服务参数，调整连接池，提升服务并发吞吐能力。
 | 原文链接：http://wiki.skth0o.asia/arts/347496.Doc

原标题：Security：接口鉴权越权漏洞检测与修复
简介：golang 优雅处理数据库事务，Go 数据库事务封装，正确处理事务提交回滚，保证业务数据一致性。
 | 原文链接：http://wiki.skth0o.asia/arts/121149.Doc

原标题：部署复盘：配置不要硬编码进镜像最佳实践
简介：golang go 爬虫请求速率控制，爬虫限频、代理轮换，设置 UA，防止爬虫被目标站点封禁 IP。
 | 原文链接：http://wiki.skth0o.asia/arts/980809.Doc

原标题：架构笔记：任务调度系统架构设计与可靠性
简介：monorepo 项目多包管理最佳实践，monorepo 仓库管理多子包，统一版本管理，处理包之间互相依赖。
 | 原文链接：http://wiki.skth0o.asia/arts/435922.Doc

原标题：golang 系统设计接口参数防篡改校验
简介：缓存穿透防护保护数据库，实现缓存穿透防护手段，拦截不存在的数据查询，避免请求直接打穿数据库。
 | 原文链接：http://wiki.skth0o.asia/arts/327327.Doc

原标题：排错：DockerCompose依赖顺序启动顺序坑
简介：跨域偶现失败配置修复，解决跨域问题时而复现时而正常，定位配置漏配、请求头异常等隐性问题。
 | 原文链接：http://wiki.skth0o.asia/arts/120879.Doc

原标题：golang websocket 消息广播实现
简介：Redis 分布式锁高并发安全实现，基于 Redis 实现分布式锁，处理锁过期、续期，保障集群并发安全。
 | 原文链接：http://wiki.skth0o.asia/arts/903222.Doc

原标题：golang 大文件 http 下载服务
简介：简易网关请求路由过滤模拟，模拟网关基础能力，实现请求路由转发、简单过滤，理解网关核心工作逻辑。
 | 原文链接：http://wiki.skth0o.asia/arts/672587.Doc

原标题：性能复盘：锁等待严重业务逻辑优化记录
简介：golang golangci‑lint 静态代码检查配置，golangci‑lint 静态检查，代码规范检测，提前发现代码隐患。
 | 原文链接：http://wiki.skth0o.asia/arts/447292.Doc

原标题：golang 系统设计 websocket 协议原理梳理
简介：包管理器依赖冲突解决方案，分析依赖冲突产生根源，提供版本调整、锁定依赖等手段，解决项目依赖报错问题。
 | 原文链接：http://wiki.skth0o.asia/arts/521838.Doc

原标题：Nginx 反向代理路由配置实战
简介：golang udp 服务端客户端开发示例，golang 实现 UDP 服务收发数据包，实现 udp 协议通信程序。
 | 原文链接：http://wiki.skth0o.asia/arts/559376.Doc

原标题：golang 数据库慢查询监控实现
简介：golang grpc 客户端拦截器封装，grpc 客户端拦截器实现请求统一签名、重试、链路信息透传。
 | 原文链接：http://wiki.skth0o.asia/arts/469784.Doc

原标题：golang 系统设计密钥轮换安全实践思路
简介：golang 时间时区处理避坑指南，Go 时间时区常见坑，时区转换，时间比较，规避时间逻辑错误。
 | 原文链接：http://wiki.skth0o.asia/arts/075136.Doc

原标题：排错：容器OOM被杀死，日志看不到任何输出
简介：golang go 变量逃逸场景汇总，切片、指针、返回局部变量引发逃逸，变量分配到堆影响 GC。
 | 原文链接：http://wiki.skth0o.asia/arts/810466.Doc

原标题：运维笔记：服务器日志轮转logrotate配置
简介：golang 高并发下锁优化减少竞争，减小锁粒度，读写锁替换互斥锁，无锁编程降低锁竞争开销。
 | 原文链接：http://wiki.skth0o.asia/arts/269145.Doc

原标题：K8s 镜像拉取网络故障修复
简介：golang go work 多模块本地开发，go work 多模块本地同时开发，本地模块互相引用，无需推送仓库。
 | 原文链接：http://wiki.skth0o.asia/arts/938986.Doc

原标题：内存溢出问题现象识别排查
简介：golang etcd key 监听变更 watch 机制，watch 监听 etcd 键变化，配置变更实时感知，实现配置热更新。
 | 原文链接：http://wiki.skth0o.asia/arts/630649.Doc

原标题：golang 系统设计版本号语义化规范讲解
简介：service‑worker 离线缓存实践，使用 ServiceWorker 实现静态资源离线缓存，弱网环境页面依然可访问。
 | 原文链接：http://wiki.skth0o.asia/arts/498284.Doc

原标题：golang 系统设计压力测试性能测试执行流程
简介：golang sync.Mutex 互斥锁正确模式，互斥锁 defer Unlock，锁粒度控制，避免锁范围过大。
 | 原文链接：http://wiki.skth0o.asia/arts/522982.Doc

原标题：项目实践：Docker多环境镜像构建策略实践
简介：golang go mod 私有 git 仓库配置，配置 go mod 拉取私有仓库代码，处理私有模块依赖拉取问题。
 | 原文链接：http://wiki.skth0o.asia/arts/233936.Doc

原标题：多版本开发环境共存配置
简介：monorepo 项目多包管理最佳实践，monorepo 仓库管理多子包，统一版本管理，处理包之间互相依赖。
 | 原文链接：http://wiki.skth0o.asia/arts/568479.Doc

原标题：Issue：连接池参数不合理，大量连接被耗尽
简介：从零编写简易 CLI 命令行工具，通过实战案例实现基础命令交互，理解命令行程序执行逻辑，产出可运行小工具。
 | 原文链接：http://wiki.skth0o.asia/arts/051055.Doc

原标题：Hands‑on：手写简单RPC框架基础通信版本
简介：浏览器本地存储安全使用技巧，讲解 localStorage、sessionStorage 使用边界，规避 XSS 泄露存储数据。
 | 原文链接：http://wiki.skth0o.asia/arts/251845.Doc

原标题：新手避坑：第一次提交GitHub项目完整流程
简介：限流规则误拦截正常请求修复，修正限流规则阈值，避免合法用户被限流拦截，兼顾防护与可用性。
 | 原文链接：http://wiki.skth0o.asia/arts/295952.Doc

原标题：安全笔记：依赖包漏洞检测供应链安全
简介：nodejs 单元测试 jest 实操教程，Jest 单元测试实操，编写测试用例，mock 依赖，验证业务逻辑正确性。
 | 原文链接：http://wiki.skth0o.asia/arts/747870.Doc


二、踩坑排错｜Troubleshooting
原标题：Security：RPC调用身份认证安全加固
简介：golang go url url.Values 参数编码，url.Values 构建 url 查询参数，自动处理参数 url 编码。
 | 原文链接：http://wiki.skth0o.asia/arts/085448.Doc

原标题：JWT 令牌过期异常处理
简介：开源项目构建失败排查步骤，梳理构建报错排查流程，从依赖、网络、权限、脚本多角度定位项目构建失败原因。
 | 原文链接：http://wiki.skth0o.asia/arts/876521.Doc

原标题：优化实践：接口返回字段裁剪减少报文大小
简介：golang cgo 内存管理 C 与 Go 内存，区分 Go 内存 C 堆内存，防止 cgo 内存泄漏，正确释放 C 内存。
 | 原文链接：http://wiki.skth0o.asia/arts/457880.Doc

原标题：快速上手简单的限流逻辑模拟实现
简介：分布式锁失效问题排查修复，分析分布式锁失效场景，修复锁超时、续期问题，保证锁逻辑可靠。
 | 原文链接：http://wiki.skth0o.asia/arts/225364.Doc

原标题：nodejs 信号处理优雅关闭服务
简介：golang embed 目录读取文件列表，embed 嵌入整个目录，读取目录下全部文件，做静态资源服务。
 | 原文链接：http://wiki.skth0o.asia/arts/704454.Doc

原标题：多线程线程安全脏数据规避
简介：golang 配置热更新不重启服务，实现配置热加载，监听配置变更，更新内存配置，无需重启服务实例。
 | 原文链接：http://wiki.skth0o.asia/arts/231064.Doc

原标题：服务器 Swap 关闭提升响应速度
简介：Git 分支切换合并删除完整操作，实操分支全生命周期操作，包含切换、合并、删除，熟悉日常开发分支处理流程。
 | 原文链接：http://wiki.skth0o.asia/arts/310864.Doc

原标题：golang k8s 镜像拉取密钥配置
简介：golang consul 服务发现简单示例，对接 Consul 实现服务注册发现，微服务实例自动感知。
 | 原文链接：http://wiki.skth0o.asia/arts/048337.Doc

原标题：线上故障：热点Key打满RedisCPU节点过载
简介：golang http cookie jar 会话处理，客户端 cookie jar 自动管理 cookie，处理登录态会话。
 | 原文链接：http://wiki.skth0o.asia/arts/966659.Doc

原标题：golang 系统设计定时任务分布式锁
简介：golang go proxy 私有代理配置，配置 go proxy 私有代理，加速依赖下载，内网环境构建项目。
 | 原文链接：http://wiki.skth0o.asia/arts/824534.Doc

原标题：Issue：开源项目升级大版本后API不兼容踩坑
简介：golang 数据库连接池参数调优详解，最大连接空闲连接最大生命周期，结合业务合理配置避免资源浪费。
 | 原文链接：http://wiki.skth0o.asia/arts/200543.Doc

原标题：golang k8s configmap secret 配置
简介：golang k8s 客户端 client‑go 简单示例，client‑go 操作 k8s 资源，增删改查 pod deployment 等资源对象。
 | 原文链接：http://wiki.skth0o.asia/arts/288635.Doc

原标题：安全实践：接口错误信息不要暴露内部细节
简介：限流规则误拦截正常请求修复，修正限流规则阈值，避免合法用户被限流拦截，兼顾防护与可用性。
 | 原文链接：http://wiki.skth0o.asia/arts/908523.Doc

原标题：架构复盘：慢查询治理架构层面优化手段
简介：golang goroutine 协程基础实操，Goroutine 基础实操案例，启动协程执行任务，理解轻量级协程特性。
 | 原文链接：http://wiki.skth0o.asia/arts/347656.Doc

原标题：golang 系统设计 api 网关核心能力梳理
简介：golang 信号量控制并发数量，使用信号量控制并发，限制同时执行任务数量，保护下游资源。
 | 原文链接：http://wiki.skth0o.asia/arts/744690.Doc

原标题：实战：接口压力测试实操，定位系统瓶颈
简介：golang 优雅处理数据库事务，Go 数据库事务封装，正确处理事务提交回滚，保证业务数据一致性。
 | 原文链接：http://wiki.skth0o.asia/arts/347887.Doc

原标题：部署实践：服务器防火墙安全组配置实践
简介：golang ctx 关闭之后资源释放，context 取消后，监听 Done ()，释放 goroutine 网络 IO 资源。
 | 原文链接：http://wiki.skth0o.asia/arts/824733.Doc

原标题：Issue：防火墙拦截ICMP，MTU问题网络丢包
简介：golang gin 框架接口开发实战，Gin 框架搭建 HTTP 服务，开发增删改查接口，快速完成后端接口开发。
 | 原文链接：http://wiki.skth0o.asia/arts/262933.Doc

原标题：API 接口调试与异常处理实战
简介：golang go 单二进制文件静态编译交叉编译，交叉编译不同操作系统架构二进制文件，实现一次编译多平台运行。
 | 原文链接：http://wiki.skth0o.asia/arts/693277.Doc

原标题：golang 系统设计接口不兼容平滑迁移方案
简介：golang 程序崩溃 core dump 生成调试，开启 core dump，程序崩溃生成转储文件，事后分析崩溃原因。
 | 原文链接：http://wiki.skth0o.asia/arts/162554.Doc

原标题：数据库连接及时关闭连接泄漏
简介：golang json omitempty 零值坑，omitempty 会忽略零值，区分业务是否需要输出零值字段。
 | 原文链接：http://wiki.skth0o.asia/arts/268435.Doc

原标题：记一次分布式锁失效引发的数据错乱问题
简介：golang go 程序守护进程实现思路，go 程序不做 daemon 化，依靠 systemd pm2 k8s 实现进程守护。
 | 原文链接：http://wiki.skth0o.asia/arts/717470.Doc

原标题：golang 系统设计本地缓存过期淘汰策略选型
简介：前端打包分包加载提速方案，前端打包做代码分包，拆分大 bundle，页面按需加载，提升首屏加载速度。
 | 原文链接：http://wiki.skth0o.asia/arts/545913.Doc

原标题：golang k8s job 一次性任务执行
简介：JWT 工具封装令牌刷新过期，封装 JWT 工具类，实现令牌生成、校验、过期刷新整套令牌管理逻辑。
 | 原文链接：http://wiki.skth0o.asia/arts/657235.Doc

原标题：部署实践：服务器SSH安全加固配置实践
简介：golang go xml 解析生成 xml 文档，encoding/xml 解析 xml，结构体标签映射 xml 节点属性。
 | 原文链接：http://wiki.skth0o.asia/arts/012075.Doc

原标题：TCP 长连接参数优化 TIME_WAIT
简介：golang time duration 解析时间字符串，time.ParseDuration 解析 1h30m 时间间隔字符串。
 | 原文链接：http://wiki.skth0o.asia/arts/052885.Doc

原标题：批量操作分批处理防止 OOM
简介：golang 分布式锁 redis 实现，基于 Redis 实现 Go 分布式锁，解决多实例并发竞争资源问题。
 | 原文链接：http://wiki.skth0o.asia/arts/238305.Doc

原标题：Debug：网关超时时间小于后端接口超时设置
简介：golang 优雅处理 http 超时设置，Go HTTP 请求设置各类超时，防止请求无限阻塞，保护协程与连接。
 | 原文链接：http://wiki.skth0o.asia/arts/310194.Doc

原标题：golang docker 基础命令实操汇总
简介：golang errors.Is errors.As 错误判断，判断是否为指定错误类型，提取自定义错误信息，错误处理进阶。
 | 原文链接：http://wiki.skth0o.asia/arts/684227.Doc

原标题：Hands‑on：简易跨进程通信demo开发实践
简介：golang 时间轮算法实现延时调度，手写简易时间轮，高并发大量延时任务，降低轮询 CPU 消耗。
 | 原文链接：http://wiki.skth0o.asia/arts/279494.Doc

原标题：方案设计：短链接系统完整架构方案拆解
简介：golang go decimal 定点小数金额计算，decimal 库处理金额，规避 float64 精度丢失，财务计算。
 | 原文链接：http://wiki.skth0o.asia/arts/414576.Doc

原标题：AI实践：大模型生成代码后审查与重构实践
简介：golang goroutine 协程基础实操，Goroutine 基础实操案例，启动协程执行任务，理解轻量级协程特性。
 | 原文链接：http://wiki.skth0o.asia/arts/867699.Doc

原标题：排错：CI流水线构建失败，日志无明确报错
简介：golang k8s informer 机制原理理解，informer 监听 k8s 资源变更，本地缓存，减少 apiserver 压力。
 | 原文链接：http://wiki.skth0o.asia/arts/211498.Doc

原标题：Troubleshoot：MySQL字符集utf8非utf8mb4emoji报错
简介：golang kafka 批量消费性能优化，开启批量拉取消息，调整批量大小，提升 kafka 消息消费吞吐量。
 | 原文链接：http://wiki.skth0o.asia/arts/227697.Doc

原标题：golang 系统设计接口参数防篡改校验
简介：golang panic 崩溃日志完整收集，捕获所有 panic，打印堆栈，记录日志，方便定位崩溃根源。
 | 原文链接：http://wiki.skth0o.asia/arts/198114.Doc

原标题：全局时间标准统一逻辑错乱修复
简介：golang 环境变量读取与类型转换，读取系统环境变量，做类型转换默认值处理，适配多环境部署。
 | 原文链接：http://wiki.skth0o.asia/arts/055415.Doc

原标题：golang 系统设计数据库扩容几种方式
简介：特殊输入字符过滤解析防护，过滤用户输入特殊字符，防止解析报错，规避恶意字符带来业务异常。
 | 原文链接：http://wiki.skth0o.asia/arts/011075.Doc

原标题：golang yaml 解析配置加载实操
简介：CLI 批量处理工具文件操作开发，开发命令行批量工具，实现批量文件处理，提升重复文件处理效率。
 | 原文链接：http://wiki.skth0o.asia/arts/114280.Doc

原标题：快速上手简易网关转发逻辑模拟
简介：golang go 服务日志输出 journald，systemd journald 接收程序 stdout 日志，统一管理服务日志。
 | 原文链接：http://wiki.skth0o.asia/arts/183737.Doc

原标题：Hands‑on：手写简单RPC框架基础通信版本
简介：golang 协程 panic 捕获防止崩溃，协程内部捕获 panic，防止单个协程恐慌造成整个 Go 进程崩溃。
 | 原文链接：http://wiki.skth0o.asia/arts/327419.Doc

三、实战开发｜Practice
原标题：gRPC 服务端客户端入门示例
简介：WebSocket 双向通信 demo 开发，搭建简易 WebSocket 服务，实现客户端服务端双向消息推送，理解实时通信原理。
 | 原文链接：http://wiki.skth0o.asia/arts/228763.Doc

原标题：排错：多实例部署session共享失效登录失效
简介：Nginx 丢失请求头配置修正，修复 Nginx 代理转发丢失请求头配置，保证上游服务拿到完整请求头信息。
 | 原文链接：http://wiki.skth0o.asia/arts/073623.Doc

原标题：golang 系统设计索引设计通用方法论汇总
简介：golang 进程信号捕获 SIGUSR 自定义信号，捕获用户自定义信号，实现线上不重启触发调试、日志切换。
 | 原文链接：http://wiki.skth0o.asia/arts/949557.Doc

原标题：项目构建脚本编译打包解析
简介：接口签名验签完整安全方案，一套完整接口签名方案，包含签名生成、请求携带、服务端验签校验。
 | 原文链接：http://wiki.skth0o.asia/arts/767097.Doc

原标题：golang redis 过期 key 监听业务
简介：golang go 泛型使用避坑注意点，泛型与 interface 区别，泛型性能，什么时候适合使用泛型。
 | 原文链接：http://wiki.skth0o.asia/arts/915116.Doc

原标题：实战项目：搭建本地Mock服务快速开发联调
简介：golang staticcheck 静态代码分析，staticcheck 深度静态检查，发现代码错误、性能问题、风格问题。
 | 原文链接：http://wiki.skth0o.asia/arts/486923.Doc

原标题：golang docker 镜像安全扫描漏洞
简介：golang 日志按日期切割实现方案，实现日志文件按天切割，自动归档旧日志，防止单个日志文件过大。
 | 原文链接：http://wiki.skth0o.asia/arts/689101.Doc

原标题：Issue复现：内存泄漏定位完整复盘记录
简介：golang 字符串处理常用技巧汇总，字符串拼接、分割、替换、类型转换实操，规避字符串高频错误。
 | 原文链接：http://wiki.skth0o.asia/arts/256416.Doc

原标题：Troubleshooting：k8s镜像拉取失败镜像仓库网络问题
简介：golang redis stream 消息队列实战，redis stream 实现可靠消息队列，消费组、ack 确认，消息不丢失。
 | 原文链接：http://wiki.skth0o.asia/arts/867101.Doc

原标题：安全实践：防止JSON解析漏洞恶意payload
简介：golang cgo 性能开销避坑指南，cgo 调用开销，减少频繁 cgo 调用，规避 cgo 带来内存泄漏风险。
 | 原文链接：http://wiki.skth0o.asia/arts/043325.Doc

原标题：Practice：模拟热点key，验证缓存防护策略
简介：跨平台换行符统一异常修复，统一代码文件换行符，解决不同操作系统换行符不一致带来脚本执行异常。
 | 原文链接：http://wiki.skth0o.asia/arts/779190.Doc

原标题：golang redis 网络超时参数调优
简介：golang sync.Pool 对象池复用对象，sync.Pool 复用临时对象，减少内存分配，降低 GC 频率提升性能。
 | 原文链接：http://wiki.skth0o.asia/arts/017212.Doc

原标题：开发复盘：大JSON解析分批处理避免内存溢出
简介：golang bytes.Buffer 字节缓冲区使用，bytes.Buffer 字节内存缓冲区，拼接字节，避免频繁内存分配。
 | 原文链接：http://wiki.skth0o.asia/arts/125140.Doc

原标题：golang 系统设计数据库版本迁移回滚方案
简介：golang grpc 双向流双向通信开发，grpc 双向流，服务端客户端持续互发消息，长连接流式业务场景。
 | 原文链接：http://wiki.skth0o.asia/arts/109222.Doc

原标题：部署复盘：配置热更新不用重启服务方案
简介：golang aes 对称加密解密示例，AES 对称加密解密实现，业务敏感数据加密存储传输。
 | 原文链接：http://wiki.skth0o.asia/arts/565123.Doc

原标题：golang ip 限流黑名单实现方案
简介：前端图片懒加载性能优化，实现图片懒加载，页面可视区域才加载图片，减少页面初始网络请求。
 | 原文链接：http://wiki.skth0o.asia/arts/677601.Doc

原标题：golang 系统设计锁优化减少竞争提升吞吐
简介：golang redis 过期时间处理技巧，设置 key 过期，监控过期事件，基于过期特性实现业务缓存逻辑。
 | 原文链接：http://wiki.skth0o.asia/arts/596707.Doc

原标题：效率笔记：调试网络请求curl命令高级用法
简介：golang ip2regionIP 地址解析实战，集成 ip2region 库，根据 IP 解析归属地城市，实现 IP 地域解析。
 | 原文链接：http://wiki.skth0o.asia/arts/085924.Doc

原标题：golang 系统设计日志架构采集存储检索完整链路
简介：golang redis bitmap 位图业务实战，bitmap 做签到统计、用户状态标记，节省大量内存空间。
 | 原文链接：http://wiki.skth0o.asia/arts/724548.Doc

原标题：golang 系统设计网关限流熔断降级配置思路
简介：golang gorm 子查询嵌套查询写法，Gorm 实现子查询、嵌套查询，复杂条件查询简化代码编写。
 | 原文链接：http://wiki.skth0o.asia/arts/095781.Doc

原标题：golang 系统设计唯一索引业务使用场景
简介：开源项目本地运行排错完整清单，汇总开源项目拉取后运行失败各类问题，给出排查思路，快速解决本地启动异常。
 | 原文链接：http://wiki.skth0o.asia/arts/555999.Doc

原标题：大事务拆分回滚日志暴涨解决
简介：语义化版本依赖管理防错乱，项目依赖遵循语义版本约束，规避依赖自动升级引入不兼容变更。
 | 原文链接：http://wiki.skth0o.asia/arts/642577.Doc

原标题：golang 系统设计数据库慢查询治理方案
简介：CORS 跨域问题多种解决方案，对比 CORS、代理等不同跨域方案优缺点，根据业务场景选择合适的跨域处理方式。
 | 原文链接：http://wiki.skth0o.asia/arts/503570.Doc

原标题：安全笔记：Git仓库密钥硬编码泄露处理方案
简介：CDN 缓存刷新获取最新静态资源，调用 CDN 刷新接口，清除节点旧缓存，用户访问到更新后的静态文件。
 | 原文链接：http://wiki.skth0o.asia/arts/639100.Doc

原标题：Cookie 跨环境登录配置调整
简介：golang go mod graph 查看依赖关系，go mod graph 打印依赖树，定位间接依赖来源，解决版本冲突。
 | 原文链接：http://wiki.skth0o.asia/arts/752548.Doc

原标题：入门实践：使用Git完成第一次代码提交与推送
简介：golang jwt jwk 公钥验证令牌，使用 jwk 公钥校验 jwt，非对称方式签发校验令牌，提升安全性。
 | 原文链接：http://wiki.skth0o.asia/arts/566578.Doc

原标题：多版本开发环境共存配置
简介：golang go 项目 CI github actions 配置，github actions 实现 go 项目 ci，自动测试、代码检查、编译打包镜像。
 | 原文链接：http://wiki.skth0o.asia/arts/500355.Doc

原标题：架构笔记：冷热数据分离架构设计与迁移
简介：golang go proxy 私有代理配置，配置 go proxy 私有代理，加速依赖下载，内网环境构建项目。
 | 原文链接：http://wiki.skth0o.asia/arts/572373.Doc

原标题：golang 系统设计内网外网服务隔离方案
简介：golang 任务失败重试与死信队列，异步任务失败自动重试，超过重试次数进入死信队列人工处理。
 | 原文链接：http://wiki.skth0o.asia/arts/231006.Doc

原标题：消息队列消费堆积扩容处理
简介：golang go 依赖漏洞检测 govulncheck，govulncheck 扫描依赖安全漏洞，发现项目供应链风险。
 | 原文链接：http://wiki.skth0o.asia/arts/129133.Doc

原标题：OpenSource：开源项目README高质量编写指南
简介：golang 消息队列实现事务消息方案，基于 kafka 实现事务消息，业务执行成功才对外投递消息。
 | 原文链接：http://wiki.skth0o.asia/arts/328474.Doc

原标题：golang 系统设计布隆过滤器原理与落地
简介：Git 标签版本标记发布管理，使用 Git 标签标记项目版本，打标签推送远程，用于版本发布、版本回溯。
 | 原文链接：http://wiki.skth0o.asia/arts/567321.Doc

原标题：golang 系统设计压测环境隔离避免影响生产
简介：golang defer 闭包变量捕获坑，defer 捕获循环变量引用，变量被复写，理解闭包变量捕获规则。
 | 原文链接：http://wiki.skth0o.asia/arts/071021.Doc

原标题：golang 分页查询封装通用工具
简介：Redis 大 key 拆分集群卡顿解决，拆分 Redis 超大 Key，避免大 key 操作造成 Redis 集群卡顿阻塞。
 | 原文链接：http://wiki.skth0o.asia/arts/033651.Doc

原标题：分布式任务调度集群原型开发
简介：简易网关请求路由过滤模拟，模拟网关基础能力，实现请求路由转发、简单过滤，理解网关核心工作逻辑。
 | 原文链接：http://wiki.skth0o.asia/arts/570398.Doc

原标题：坑点：Git工作区换行符CRLF/LF跨平台坑
简介：pnpm 包管理工具实战避坑指南，使用 pnpm 管理项目依赖，梳理常见坑点，充分利用 pnpm 优势。
 | 原文链接：http://wiki.skth0o.asia/arts/412733.Doc

原标题：golang dockerfile 多阶段构建详解
简介：golang go 死锁检测工具，静态检查、运行检测，发现 channel 锁导致死锁问题。
 | 原文链接：http://wiki.skth0o.asia/arts/300270.Doc

原标题：nodejs 单元测试 jest 实操教程
简介：golang gorm group by 分组统计，GORM 分组聚合统计，实现 count sum 等统计查询，快速完成统计业务。
 | 原文链接：http://wiki.skth0o.asia/arts/724523.Doc

原标题：架构复盘：网关层、应用层、数据库层层限流架构
简介：golang go 错误包装 fmt.Errorf % w，使用 % w 包装错误，支持 errors.Is errors.As 判断错误类型。
 | 原文链接：http://wiki.skth0o.asia/arts/535342.Doc

原标题：架构笔记：分布式事务方案对比与业务取舍
简介：接口签名验签完整安全方案，一套完整接口签名方案，包含签名生成、请求携带、服务端验签校验。
 | 原文链接：http://wiki.skth0o.asia/arts/279269.Doc

四、架构设计｜Architecture
原标题：数据库主从延迟业务兼容处理
简介：golang go 信号处理优雅重启实现，USR2 触发程序重启，不关闭监听 socket 实现零停机升级。
 | 原文链接：http://wiki.skth0o.asia/arts/312442.Doc

原标题：golang 系统信号信号量处理
简介：golang yaml 解析配置加载实操，Go 解析 YAML 配置文件，读取配置参数，驱动业务运行。
 | 原文链接：http://wiki.skth0o.asia/arts/982968.Doc

原标题：部署实践：多实例服务部署无状态改造
简介：golang 跨平台系统差异处理方案，处理 windows linux mac 路径、信号、文件权限差异，代码跨平台兼容。
 | 原文链接：http://wiki.skth0o.asia/arts/482241.Doc

原标题：HelloWorld：快速上手新项目最小可运行示例
简介：环境变量不生效问题修复，排查环境变量加载顺序、作用域问题，修复环境变量读取不到的异常。
 | 原文链接：http://wiki.skth0o.asia/arts/547432.Doc

原标题：安全实践：SQL注入产生场景与完整防御手段
简介：golang jwt 令牌刷新逻辑实现，实现 JWT 双令牌机制，access 短期有效 refresh 刷新令牌，实现无感续期登录。
 | 原文链接：http://wiki.skth0o.asia/arts/595399.Doc

原标题：golang 系统设计分布式锁红锁优缺点梳理
简介：golang go 初始化顺序包变量 init 函数，包级变量初始化，init 执行顺序，理解包加载执行流程。
 | 原文链接：http://wiki.skth0o.asia/arts/276609.Doc

原标题：Docker 容器时区错误修复方案
简介：SDK 版本兼容线上崩溃修复，处理 SDK 版本升级之后线上崩溃，定位 API 变更，做版本兼容适配改造。
 | 原文链接：http://wiki.skth0o.asia/arts/481033.Doc

原标题：golang 系统设计 sql 注入 xss 防护实践
简介：golang socket 文件描述符继承重启，父进程传递 listener fd 给子进程，实现 go 程序零停机热重启。
 | 原文链接：http://wiki.skth0o.asia/arts/681877.Doc

原标题：golang redis 分布式计数器开发
简介：golang http 代理客户端配置，Go HTTP Client 配置代理，通过代理服务器发起网络请求。
 | 原文链接：http://wiki.skth0o.asia/arts/529046.Doc

原标题：golang 系统设计避免索引失效书写 sql 原则
简介：前端权限路由动态生成实现，根据后端返回权限，动态生成前端路由菜单，实现页面权限控制。
 | 原文链接：http://wiki.skth0o.asia/arts/711257.Doc

原标题：golang 系统设计第三方调用超时重试熔断
简介：golang kitex 中间件与元数据传递，kitex 自定义中间件，透传 traceId 鉴权元数据，统一处理请求。
 | 原文链接：http://wiki.skth0o.asia/arts/275444.Doc

原标题：golang 系统设计数据库查询优化完整流程
简介：golang grpc protobuf 开发实操，Go gRPC 开发，编写 Protobuf 定义，服务端客户端完整示例。
 | 原文链接：http://wiki.skth0o.asia/arts/044374.Doc

原标题：golang net/http 超时全套配置
简介：程序日志分级输出规范实践，区分日志等级，规范日志打印内容，合理输出日志，方便线上问题排查定位。
 | 原文链接：http://wiki.skth0o.asia/arts/451007.Doc

原标题：新手避坑：第一次提交GitHub项目完整流程
简介：golang go 程序抢占调度理解，理解 go 抢占式调度原理，长循环阻塞调度，造成协程调度延迟。
 | 原文链接：http://wiki.skth0o.asia/arts/203423.Doc

原标题：排错：容器OOM被杀死，日志看不到任何输出
简介：golang http client 连接池调优，调优 Go HTTP Client 连接池参数，复用 TCP 连接，减少连接创建开销。
 | 原文链接：http://wiki.skth0o.asia/arts/452073.Doc

原标题：golang 系统设计结构化日志字段规范约定
简介：golang go 服务蓝绿发布实践思路，蓝绿两套实例，流量一键切换，回滚快速降低发布风险。
 | 原文链接：http://wiki.skth0o.asia/arts/860662.Doc

原标题：性能笔记：线程池参数调优任务队列策略
简介：golang sort 切片排序自定义 less，sort.Slice 切片快速排序，自定义 less 函数实现业务排序。
 | 原文链接：http://wiki.skth0o.asia/arts/895916.Doc

原标题：踩坑：大报文传输，RPC消息超过大小限制
简介：Docker 容器时区错误修复方案，修复 Docker 容器内部时区偏差，解决容器内时间不对引发业务逻辑异常。
 | 原文链接：http://wiki.skth0o.asia/arts/138661.Doc

?
