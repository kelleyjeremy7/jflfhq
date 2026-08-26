最新前沿技术资讯

一、入门教程｜Getting Started
原标题：golang 系统设计异步化改造业务流程思路
简介：全局时间标准统一逻辑错乱修复，全服务统一使用同一时间标准，不要混用本地时间 UTC，修复时间逻辑 bug。
 | 原文链接：http://wiki.fwfyza.asia/arts/909030.Doc

原标题：golang 系统设计多级缓存架构落地
简介：golang go 种子初始化 rand 随机，rand 初始化种子，不初始化会固定序列，理解随机数种子行为。
 | 原文链接：http://wiki.fwfyza.asia/arts/616100.Doc

原标题：设计思考：消息顺序性架构保证与业务妥协
简介：golang 消息队列中间件选型对比，kafka redis‑stream rabbitmq，对比吞吐量可靠性选型参考。
 | 原文链接：http://wiki.fwfyza.asia/arts/909813.Doc

原标题：数据库连接及时关闭连接泄漏
简介：接口限流逻辑简单模拟实现，编写简易限流逻辑，限制接口访问频次，保护服务，避免短时间大量请求压垮系统。
 | 原文链接：http://wiki.fwfyza.asia/arts/450268.Doc

原标题：实战项目：GitSubmodule管理多仓库实践
简介：golang cgo 性能开销避坑指南，cgo 调用开销，减少频繁 cgo 调用，规避 cgo 带来内存泄漏风险。
 | 原文链接：http://wiki.fwfyza.asia/arts/679864.Doc

原标题：golang 系统设计链路数据存储选型对比讲解
简介：数据库死锁成因规避方案，讲解数据库死锁产生条件，给出业务层面规避手段，减少死锁事件发生。
 | 原文链接：http://wiki.fwfyza.asia/arts/520000.Doc

原标题：坑点：Git仓库过大，clone速度极慢解决方案
简介：系统字符集统一乱码修复，统一数据库、程序、操作系统字符集，解决中文乱码显示异常问题。
 | 原文链接：http://wiki.fwfyza.asia/arts/468063.Doc

原标题：实战项目：WebSocket消息广播房间分组实践
简介：动态定时任务业务调度实现，实现可以动态增删启停定时任务，无需重启服务调整调度任务。
 | 原文链接：http://wiki.fwfyza.asia/arts/164080.Doc

原标题：一次数据库死锁现场分析与解决方案记录
简介：golang 静态文件服务搭建教程，Go 搭建静态文件服务，托管静态资源，实现文件直接对外访问。
 | 原文链接：http://wiki.fwfyza.asia/arts/003247.Doc

原标题：前端组件库按需加载性能优化
简介：golang 日志脱敏敏感字段过滤，日志打印自动脱敏敏感字段，避免日志输出手机号身份证泄露隐私。
 | 原文链接：http://wiki.fwfyza.asia/arts/051097.Doc

原标题：特殊输入字符过滤解析防护
简介：golang net/url 路径拼接处理，url.ParseRequestURI 处理请求 url，正确拼接 url 路径避免拼接错误。
 | 原文链接：http://wiki.fwfyza.asia/arts/311744.Doc

原标题：Security：文件路径穿越漏洞完整防护
简介：文件描述符优化进程卡死修复，及时关闭文件句柄，控制打开文件数量，解决文件句柄耗尽进程卡死。
 | 原文链接：http://wiki.fwfyza.asia/arts/347070.Doc

原标题：golang 系统设计错误码体系完整设计
简介：golang redis lua 脚本原子操作，使用 Lua 脚本实现原子逻辑，减少网络往返，保障多命令原子执行。
 | 原文链接：http://wiki.fwfyza.asia/arts/388477.Doc

原标题：安全实践：容器最小化镜像减少攻击面
简介：golang bufio.Scanner 按行读取大文件，Scanner 逐行读取文本文件，处理超大日志 csv。
 | 原文链接：http://wiki.fwfyza.asia/arts/954339.Doc

原标题：golang 系统设计滑动窗口限流代码示例
简介：golang atomic.Value 存储任意类型数据，atomic.Value 安全存储读取任意类型，配置热更新常用。
 | 原文链接：http://wiki.fwfyza.asia/arts/724676.Doc

原标题：请求重试组件退避策略实现
简介：浏览器本地存储安全使用技巧，讲解 localStorage、sessionStorage 使用边界，规避 XSS 泄露存储数据。
 | 原文链接：http://wiki.fwfyza.asia/arts/565551.Doc

原标题：golang 链路 traceId 透传中间件
简介：程序性能指标 CPU 内存监控，讲解基础性能指标含义，简单实现监控采集，初步定位程序运行性能瓶颈。
 | 原文链接：http://wiki.fwfyza.asia/arts/056285.Doc

原标题：调试工具断点调试变量查看技巧
简介：golang accept 错误循环崩溃处理，accept 返回系统错误，处理临时错误，避免死循环占满 CPU。
 | 原文链接：http://wiki.fwfyza.asia/arts/203514.Doc

原标题：项目目录结构规范化最佳实践
简介：golang 布隆过滤器实现去重，Go 实现布隆过滤器，海量数据去重，节省内存开销，提升判断效率。
 | 原文链接：http://wiki.fwfyza.asia/arts/390548.Doc

原标题：项目实践：实现数据脱敏组件支持多种脱敏规则
简介：golang mqtt 客户端 go 开发物联网，paho.mqtt.golang 实现 mqtt 客户端，物联网设备消息收发。
 | 原文链接：http://wiki.fwfyza.asia/arts/375099.Doc

原标题：golang 系统设计故障定位排查通用步骤方法论
简介：程序性能指标 CPU 内存监控，讲解基础性能指标含义，简单实现监控采集，初步定位程序运行性能瓶颈。
 | 原文链接：http://wiki.fwfyza.asia/arts/402788.Doc

原标题：Issue：日志疯狂打日志快速占满磁盘空间
简介：golang sort 搜索查找切片元素，sort.Search 二分查找有序切片，快速定位元素索引位置。
 | 原文链接：http://wiki.fwfyza.asia/arts/039282.Doc

原标题：静态网页 HTML CSS 快速入门实战
简介：nodejs 消息队列消费服务开发，Node 开发消息队列消费端，监听队列消息执行业务逻辑，异步解耦业务。
 | 原文链接：http://wiki.fwfyza.asia/arts/420689.Doc

原标题：Practice：模拟网络抖动验证服务容错能力
简介：nodejs jwt 登录鉴权完整示例，Node 实现 JWT 登录鉴权，登录签发令牌，接口校验令牌身份。
 | 原文链接：http://wiki.fwfyza.asia/arts/290659.Doc

原标题：游标分页大数据查询性能提升
简介：nodejs 定时任务生产环境避坑，Node 定时任务线上踩坑汇总，集群重复执行、任务阻塞等问题解决方案。
 | 原文链接：http://wiki.fwfyza.asia/arts/305120.Doc

原标题：全平台系统环境变量配置
简介：浏览器内存泄漏排查前端页面，梳理前端页面内存泄漏场景，讲解排查手段，修复页面内存持续上涨。
 | 原文链接：http://wiki.fwfyza.asia/arts/046338.Doc

原标题：golang 系统设计 protobuf 可选字段使用技巧
简介：nodejs 定时任务生产环境避坑，Node 定时任务线上踩坑汇总，集群重复执行、任务阻塞等问题解决方案。
 | 原文链接：http://wiki.fwfyza.asia/arts/217009.Doc

原标题：Practice：实现业务唯一流水号生成组件实践
简介：Nginx 透传真实客户端 IP 配置，配置 Nginx 把真实客户端 IP 传递后端服务，后端拿到访问者真实 IP。
 | 原文链接：http://wiki.fwfyza.asia/arts/738695.Doc

原标题：开源实践：开源Issue沟通技巧如何有效提Bug
简介：golang go1.18 + 泛型基础实操，go 泛型基础语法，泛型函数泛型类型，实现通用工具函数。
 | 原文链接：http://wiki.fwfyza.asia/arts/753867.Doc

原标题：记一次字符集编码不一致乱码问题全排查
简介：golang go http 静态文件禁止目录遍历，http.FileServer 防止../ 路径穿越，了解底层安全实现。
 | 原文链接：http://wiki.fwfyza.asia/arts/459529.Doc

原标题：Hands‑on：编写shell健康检查自动重启脚本
简介：golang go 单二进制文件静态编译交叉编译，交叉编译不同操作系统架构二进制文件，实现一次编译多平台运行。
 | 原文链接：http://wiki.fwfyza.asia/arts/991266.Doc

原标题：Troubleshoot：跨库关联查询，性能急剧恶化
简介：golang time 时间比较 Before After Equal，时间比较不要直接减，使用内置方法判断时间先后。
 | 原文链接：http://wiki.fwfyza.asia/arts/017285.Doc

原标题：前端静态缓存更新生效处理
简介：golang 设置 net.Conn 读写超时，每次读写设置超时，防止连接永久阻塞挂起不返回。
 | 原文链接：http://wiki.fwfyza.asia/arts/757558.Doc

原标题：设计思考：业务系统如何设计优雅失败架构
简介：golang http cookie jar 会话处理，客户端 cookie jar 自动管理 cookie，处理登录态会话。
 | 原文链接：http://wiki.fwfyza.asia/arts/161307.Doc

原标题：golang go test 覆盖率统计实操
简介：golang minio 私有对象存储开发，minio s3 对象存储，bucket 管理，文件上传下载权限设置。
 | 原文链接：http://wiki.fwfyza.asia/arts/431906.Doc

原标题：方案对比：单体、微服务、模块化单体取舍
简介：golang os.Exit 退出程序注意 defer 不执行，os.Exit 会直接退出，不会执行 defer，优雅退出不要直接 os.Exit。
 | 原文链接：http://wiki.fwfyza.asia/arts/461020.Doc

原标题：golang 系统设计依赖版本升级风险评估
简介：OpenAPI 自动接口文档生成，集成 OpenAPI 工具，自动扫描代码生成接口文档，减少文档维护成本。
 | 原文链接：http://wiki.fwfyza.asia/arts/840763.Doc

原标题：golang 系统设计数据库死锁分析规避
简介：代码模块化组件化拆分思路，讲解代码拆分原则，将大业务拆分为独立模块组件，提升代码复用与维护能力。
 | 原文链接：http://wiki.fwfyza.asia/arts/787370.Doc

原标题：Performance：大事务拆分，减少锁持有时间
简介：golang sftp 文件上传下载操作，sftp 协议远程文件上传下载，实现服务器之间文件传输功能。
 | 原文链接：http://wiki.fwfyza.asia/arts/157274.Doc

原标题：开发复盘：海量日志轮转清理脚本实践
简介：golang fuzz corpus 语料库使用，fuzz 语料存储历史输入，回归测试，持续复现曾经触发 bug 输入。
 | 原文链接：http://wiki.fwfyza.asia/arts/500930.Doc


二、踩坑排错｜Troubleshooting
原标题：CI 流水线构建失败日志排查
简介：golang 接口限流中间件开发，Gin 开发限流中间件，接口层实现访问频率限制，防护接口流量。
 | 原文链接：http://wiki.fwfyza.asia/arts/419958.Doc

原标题：Practice：批量异步任务处理系统设计实现
简介：golang go 值传递引用传递理解，go 全部为值传递，指针本质拷贝指针值，理清参数传递行为。
 | 原文链接：http://wiki.fwfyza.asia/arts/265169.Doc

原标题：Architecture：CI/CD流水线架构完整设计思考
简介：golang go 接口定义原则小接口，go 小接口设计原则，接口尽量小，只定义必要方法，提升代码灵活性。
 | 原文链接：http://wiki.fwfyza.asia/arts/421951.Doc

原标题：DevOps：多环境镜像标签版本管理规范
简介：golang recover 捕获 panic 使用边界，recover 只在 defer 内部生效，协程内部必须捕获本协程 panic。
 | 原文链接：http://wiki.fwfyza.asia/arts/189111.Doc

原标题：golang 系统设计配置中心核心能力梳理讲解
简介：golang 协程数量监控统计方案，统计运行中 goroutine 数量，监控协程泄露，协程数量异常及时告警。
 | 原文链接：http://wiki.fwfyza.asia/arts/657218.Doc

原标题：golang 系统设计多级缓存更新策略
简介：接口签名校验防篡改实现，实现请求签名验签逻辑，校验请求参数未被篡改，提升接口调用安全性。
 | 原文链接：http://wiki.fwfyza.asia/arts/065204.Doc

原标题：坑点：缓存穿透，大量无效请求打穿数据库
简介：css 动画性能优化 GPU 加速，优化 CSS 动画，使用 GPU 加速属性，避免动画过程页面卡顿掉帧。
 | 原文链接：http://wiki.fwfyza.asia/arts/524077.Doc

原标题：方案设计：分布式分页查询架构难点处理
简介：内存泄漏定位分析完整流程，分享内存泄漏排查步骤，定位没有释放的对象，解决内存持续上涨问题。
 | 原文链接：http://wiki.fwfyza.asia/arts/451436.Doc

原标题：Hands‑on：编写自定义Git钩子实现代码提交校验
简介：golang interface 接口使用避坑，interface 判 nil 坑点，理解接口底层结构，避免判空逻辑失效。
 | 原文链接：http://wiki.fwfyza.asia/arts/124319.Doc

原标题：golang 优雅处理 http 超时设置
简介：线上接口超时故障排查思路，从网络、数据库、代码逻辑逐层排查接口超时，定位慢请求根因。
 | 原文链接：http://wiki.fwfyza.asia/arts/888667.Doc

原标题：golang 单例模式实现几种方式
简介：golang redis pipeline 批量操作，使用 Redis Pipeline 批量执行多条命令，减少网络往返，提升批量操作性能。
 | 原文链接：http://wiki.fwfyza.asia/arts/192799.Doc

原标题：快速入门WebSocket，实现简易双向通信demo
简介：Git commit 钩子提交规范校验，配置 Git 提交钩子，提交代码自动校验提交信息格式，规范提交记录。
 | 原文链接：http://wiki.fwfyza.asia/arts/977081.Doc

原标题：踩坑：重试逻辑未做幂等，重复生成业务数据
简介：项目构建脚本编译打包解析，解读项目构建脚本，理清编译、压缩、资源复制流程，理解打包后产物如何生成。
 | 原文链接：http://wiki.fwfyza.asia/arts/557370.Doc

原标题：golang 系统设计内部服务熔断降级配置思路
简介：golang 分库分表 id 路由规则设计，分库分表 id 路由算法，id 映射库表，数据均匀打散避免热点分片。
 | 原文链接：http://wiki.fwfyza.asia/arts/301711.Doc

原标题：设计思考：系统幂等性整体架构层面保障
简介：golang 消息队列中间件选型对比，kafka redis‑stream rabbitmq，对比吞吐量可靠性选型参考。
 | 原文链接：http://wiki.fwfyza.asia/arts/049894.Doc

原标题：Practice：实现接口签名、验签完整示例代码
简介：golang aes cbc gcm 模式加密对比，AES‑CBC AES‑GCM 模式加密解密，理解两种模式差异选型。
 | 原文链接：http://wiki.fwfyza.asia/arts/230858.Doc

原标题：本地简易配置中心动态管理
简介：接口签名校验防篡改实现，实现请求签名验签逻辑，校验请求参数未被篡改，提升接口调用安全性。
 | 原文链接：http://wiki.fwfyza.asia/arts/767073.Doc

原标题：golang 系统设计回调重试幂等完整处理
简介：分页逻辑错误数据漏查修复，修复分页查询逻辑漏洞，解决分页漏数据、重复返回数据等业务问题。
 | 原文链接：http://wiki.fwfyza.asia/arts/489070.Doc

原标题：golang 系统设计依赖漏洞扫描修复流程
简介：golang context 超时取消实战案例，使用 context 控制协程、http 请求超时，自动终止超时任务，避免协程无限阻塞。
 | 原文链接：http://wiki.fwfyza.asia/arts/823348.Doc

原标题：golang 系统设计大文件上传架构
简介：golang sqlx 原生 SQL 代码简化，sqlx 简化原生 SQL 结果映射结构体，兼顾性能与开发效率。
 | 原文链接：http://wiki.fwfyza.asia/arts/172542.Doc

原标题：golang ci 流水线自动部署 k8s 示例
简介：golang go1.18 + 泛型基础实操，go 泛型基础语法，泛型函数泛型类型，实现通用工具函数。
 | 原文链接：http://wiki.fwfyza.asia/arts/453076.Doc

原标题：golang 系统设计熔断降级架构讲解
简介：golang viper 多源配置管理实操，viper 读取配置文件环境变量命令行参数，多源配置优先级管理。
 | 原文链接：http://wiki.fwfyza.asia/arts/159823.Doc

原标题：看懂报错日志快速定位问题
简介：golang dns 自定义解析器实现，自定义 dns 解析，指定 dns 服务器，控制域名解析逻辑，适配内网环境。
 | 原文链接：http://wiki.fwfyza.asia/arts/497567.Doc

原标题：HelloShell：入门常用shell脚本编写
简介：golang go 服务压测前后性能对比，压测记录 QPS 延迟，优化前后对比，验证优化效果。
 | 原文链接：http://wiki.fwfyza.asia/arts/219962.Doc

原标题：安全笔记：第三方SDK安全风险评估要点
简介：golang goroutine 泄露常见场景汇总，channel 阻塞、context 忘记取消，导致协程无法退出发生泄露。
 | 原文链接：http://wiki.fwfyza.asia/arts/860754.Doc

原标题：设计思考：系统幂等性整体架构层面保障
简介：golang ctx 关闭之后资源释放，context 取消后，监听 Done ()，释放 goroutine 网络 IO 资源。
 | 原文链接：http://wiki.fwfyza.asia/arts/153594.Doc

原标题：部署实践：服务器SSH安全加固配置实践
简介：golang go 优雅处理信号丢失场景，处理信号丢失、信号被忽略，保障程序可以正常接收终止信号。
 | 原文链接：http://wiki.fwfyza.asia/arts/725422.Doc

原标题：设计思考：分布式系统时钟同步带来的架构问题
简介：golang ip2regionIP 地址解析实战，集成 ip2region 库，根据 IP 解析归属地城市，实现 IP 地域解析。
 | 原文链接：http://wiki.fwfyza.asia/arts/715153.Doc

原标题：golang 系统设计消息重试次数间隔策略设置
简介：多环境配置中心灵活切换方案，简易配置中心实现，支持多套环境配置，动态下发无需重启服务。
 | 原文链接：http://wiki.fwfyza.asia/arts/230392.Doc

原标题：性能笔记：锁优化减少竞争提升并发吞吐
简介：vite 项目配置与构建提速技巧，讲解 vite 配置优化手段，提升开发热更新速度与生产构建打包效率。
 | 原文链接：http://wiki.fwfyza.asia/arts/415666.Doc

原标题：Hands‑on：简易连接池原型实现理解原理
简介：golang go 模块迁移从 GOPATH 到 GoMod，老项目从 GOPATH 迁移 go mod，解决依赖管理混乱问题。
 | 原文链接：http://wiki.fwfyza.asia/arts/116753.Doc

原标题：golang 简易埋点日志上报实现
简介：golang go‑zero 框架项目快速搭建，go‑zero 脚手架生成微服务项目，api rpc 服务快速开发。
 | 原文链接：http://wiki.fwfyza.asia/arts/365200.Doc

原标题：Practice：从零实现轻量后端接口服务完整实践
简介：golang 工具函数库封装思路，Go 通用工具库封装思路，错误处理、类型转换，业务项目复用工具代码。
 | 原文链接：http://wiki.fwfyza.asia/arts/856007.Doc

原标题：分布式锁失效问题排查修复
简介：请求工具封装统一异常处理，对网络请求做二次封装，统一捕获各类请求异常，标准化接口返回格式。
 | 原文链接：http://wiki.fwfyza.asia/arts/985756.Doc

原标题：架构笔记：缓存雪崩缓存击穿架构防护方案
简介：热更新开发环境配置教程，配置代码热重载，修改代码无需重启服务立即生效，大幅提升本地开发调试效率。
 | 原文链接：http://wiki.fwfyza.asia/arts/045980.Doc

原标题：express 中间件开发业务实践
简介：前端静态缓存更新生效处理，修改静态资源版本标识，处理浏览器强缓存，让更新资源生效。
 | 原文链接：http://wiki.fwfyza.asia/arts/531052.Doc

原标题：golang 系统设计 graphql 接口优缺点梳理
简介：golang base64 编码解码实操，Go Base64 编码解码示例，处理业务场景 Base64 格式数据转换。
 | 原文链接：http://wiki.fwfyza.asia/arts/459967.Doc

原标题：运维笔记：服务器故障排查常用命令清单
简介：golang 日志 zap 结构化日志实践，接入 Zap 结构化日志库，打印结构化日志，方便日志检索解析。
 | 原文链接：http://wiki.fwfyza.asia/arts/075087.Doc

原标题：golang 系统设计网关鉴权鉴权转发流程讲解
简介：golang os 打开文件 O_APPEND O_CREATE 标志，OpenFile 标志位，控制文件创建追加截断行为。
 | 原文链接：http://wiki.fwfyza.asia/arts/850199.Doc

原标题：实战项目：数据导出Excel百万级大数据导出方案
简介：请求重试组件退避策略实现，封装重试组件，实现指数退避策略，避免大量请求同时重试压垮下游。
 | 原文链接：http://wiki.fwfyza.asia/arts/423037.Doc

三、实战开发｜Practice
原标题：零基础理解跨域问题产生原因与基础方案
简介：nodejs 中间件模式原理剖析，拆解 Node 中间件设计模式，理解请求逐层处理流转的底层原理。
 | 原文链接：http://wiki.fwfyza.asia/arts/112008.Doc

原标题：Performance：JSON序列化性能优化实践
简介：Cookie 跨环境登录配置调整，调整 Cookie 域、Secure 属性，适配开发测试生产环境，修复登录失效。
 | 原文链接：http://wiki.fwfyza.asia/arts/990657.Doc

原标题：golang k8s hpa 水平 pod 自动扩缩容
简介：ORM 框架数据库增删改查实操，使用 ORM 框架完成数据库基础操作，减少手写 SQL，简化业务层数据库交互代码。
 | 原文链接：http://wiki.fwfyza.asia/arts/787449.Doc

原标题：golang 时间时区处理避坑指南
简介：内网测试服务搭建团队调试，配置本地服务内网可访问，团队成员能够访问调试，方便前后端联调与内部演示。
 | 原文链接：http://wiki.fwfyza.asia/arts/942954.Doc

原标题：部署复盘：配置热更新不用重启服务方案
简介：golang time 时间比较 Before After Equal，时间比较不要直接减，使用内置方法判断时间先后。
 | 原文链接：http://wiki.fwfyza.asia/arts/606983.Doc

原标题：react 状态管理方案选型对比
简介：golang gorm 软删除实现逻辑，Gorm 开启软删除，删除数据仅标记，数据保留可恢复，满足业务数据留存。
 | 原文链接：http://wiki.fwfyza.asia/arts/855430.Doc

原标题：Troubleshoot：磁盘打满导致服务全部不可用
简介：golang 终端交互式输入选择，命令行交互式问答选择输入，实现交互式脚本工具。
 | 原文链接：http://wiki.fwfyza.asia/arts/150537.Doc

原标题：项目实践：OpenTelemetry链路追踪本地部署实践
简介：golang defer 闭包变量捕获坑，defer 捕获循环变量引用，变量被复写，理解闭包变量捕获规则。
 | 原文链接：http://wiki.fwfyza.asia/arts/388847.Doc

原标题：调试工具断点调试变量查看技巧
简介：golang go 变量逃逸场景汇总，切片、指针、返回局部变量引发逃逸，变量分配到堆影响 GC。
 | 原文链接：http://wiki.fwfyza.asia/arts/509611.Doc

原标题：Issue：文件编码混合GBKUTF‑8乱码随机出现
简介：golang runtime.Gosched 主动让出调度，长计算循环主动 Gosched，让出调度权，防止其他协程饥饿。
 | 原文链接：http://wiki.fwfyza.asia/arts/421913.Doc

原标题：Architecture：限流计数器架构时间窗口选型对比
简介：ServiceWorker 缓存页面更新清理，处理 ServiceWorker 缓存，实现页面新版本更新，用户可以加载最新页面。
 | 原文链接：http://wiki.fwfyza.asia/arts/168129.Doc

原标题：方案对比：轮询长轮询WebSocket推送架构选型
简介：gitignore 文件编写过滤规则，讲解 gitignore 语法，编写过滤配置，忽略缓存、编译产物、密钥文件，保持仓库整洁。
 | 原文链接：http://wiki.fwfyza.asia/arts/009800.Doc

原标题：线上故障：慢查询拖垮整个数据库服务
简介：golang grpc 负载均衡客户端实现，grpc 客户端负载均衡，轮询随机权重，分发请求到多个服务实例。
 | 原文链接：http://wiki.fwfyza.asia/arts/209840.Doc

原标题：golang 系统设计网关灰度流量切分简单方案
简介：golang hystrix 模式简易熔断实现，简易熔断组件，错误率达到阈值触发熔断，快速失败保护下游。
 | 原文链接：http://wiki.fwfyza.asia/arts/074180.Doc

原标题：golang 分库分表简单路由实现
简介：golang ctx 传递规则不要存结构体，context 作为函数参数传递，禁止放入结构体字段存储。
 | 原文链接：http://wiki.fwfyza.asia/arts/381640.Doc

原标题：golang 系统设计消息发送确认机制配置实操
简介：golang grpc 服务端流推送数据，服务端流式响应，服务端持续向客户端推送多条响应消息。
 | 原文链接：http://wiki.fwfyza.asia/arts/833091.Doc

原标题：部署实践：Nginx反向代理传递真实客户端IP
简介：golang pprof 线上采集性能数据，线上环境采集 pprof 性能样本，不用停机，分析线上性能问题。
 | 原文链接：http://wiki.fwfyza.asia/arts/200567.Doc

原标题：golang 系统设计业务指标系统指标定义思路
简介：golang 容器时区设置镜像构建处理，镜像内部设置正确时区，解决容器时间与宿主机不一致。
 | 原文链接：http://wiki.fwfyza.asia/arts/686348.Doc

原标题：golang 系统设计缓存热点 key 问题业务规避
简介：golang grafana 面板 go 业务指标可视化，prometheus 指标对接 grafana，配置监控面板可视化业务状态。
 | 原文链接：http://wiki.fwfyza.asia/arts/829409.Doc

原标题：方案设计：异步解耦业务架构边界识别
简介：golang nats 轻量消息队列 go 开发，nats 高性能轻量消息系统，发布订阅模式异步解耦业务。
 | 原文链接：http://wiki.fwfyza.asia/arts/803685.Doc

原标题：service‑worker 离线缓存实践
简介：golang 数据库分表策略按时间分片，按时间维度分表，历史数据拆分，单表数据量控制保证查询性能。
 | 原文链接：http://wiki.fwfyza.asia/arts/663607.Doc

原标题：从零搭建简单定时任务demo
简介：golang tcp 连接泄露排查定位，netstat 查看连接状态，找出未正常关闭连接，定位连接泄漏代码。
 | 原文链接：http://wiki.fwfyza.asia/arts/052158.Doc

原标题：Hands‑on：简易速率限制中间件完整实现
简介：线程池拒绝策略任务丢失防护，合理设置线程池拒绝策略，处理任务队列满场景，避免业务任务直接丢失。
 | 原文链接：http://wiki.fwfyza.asia/arts/654466.Doc

原标题：避坑：预编译SQL失效，出现SQL注入风险
简介：Git 标签版本标记发布管理，使用 Git 标签标记项目版本，打标签推送远程，用于版本发布、版本回溯。
 | 原文链接：http://wiki.fwfyza.asia/arts/159776.Doc

原标题：API 大版本不兼容平滑迁移
简介：golang k8s informer 机制原理理解，informer 监听 k8s 资源变更，本地缓存，减少 apiserver 压力。
 | 原文链接：http://wiki.fwfyza.asia/arts/743900.Doc

原标题：线上故障：热点Key打满RedisCPU节点过载
简介：golang atomic 原子操作整数，atomic 加减比较交换，无锁更新整型变量，简单计数器场景。
 | 原文链接：http://wiki.fwfyza.asia/arts/522111.Doc

原标题：Troubleshooting：依赖安装失败完整排查清单
简介：服务器 Swap 关闭提升响应速度，关闭服务器 Swap 交换分区，避免内存交换磁盘拖慢程序响应性能。
 | 原文链接：http://wiki.fwfyza.asia/arts/754797.Doc

原标题：排错：HTTPS证书过期导致接口调用失败
简介：golang redis 过期时间处理技巧，设置 key 过期，监控过期事件，基于过期特性实现业务缓存逻辑。
 | 原文链接：http://wiki.fwfyza.asia/arts/431357.Doc

原标题：Issue：浏览器缓存ServiceWorker导致旧页面常驻
简介：golang cgo 性能开销避坑指南，cgo 调用开销，减少频繁 cgo 调用，规避 cgo 带来内存泄漏风险。
 | 原文链接：http://wiki.fwfyza.asia/arts/135292.Doc

原标题：golang 系统设计 api 接口兼容性设计原则
简介：golang sort 稳定排序 Stable，稳定排序保留相等元素原有顺序，业务需要稳定排序场景。
 | 原文链接：http://wiki.fwfyza.asia/arts/804701.Doc

原标题：golang mysql 批量导入数据实操
简介：数据库读写分离性能优化，讲解读写分离原理，主库写入从库查询，分担数据库查询压力，提升查询性能。
 | 原文链接：http://wiki.fwfyza.asia/arts/677162.Doc

原标题：golang 数据库连接泄露排查
简介：空指针异常判空容错处理，讲解空指针产生场景，规范判空逻辑，增加容错，避免空指针直接造成程序崩溃。
 | 原文链接：http://wiki.fwfyza.asia/arts/517807.Doc

原标题：手写简易 RPC 服务通信原型
简介：SourceMap 生成线上报错定位，项目打包生成 SourceMap 文件，线上报错可以还原源码，快速定位报错位置。
 | 原文链接：http://wiki.fwfyza.asia/arts/660081.Doc

原标题：实战：gRPC服务编写客户端服务端完整demo
简介：golang jaeger 链路追踪部署对接，jaeger 接收 opentelemetry 链路数据，可视化完整调用链路。
 | 原文链接：http://wiki.fwfyza.asia/arts/979730.Doc

原标题：golang kafka 重试机制配置实操
简介：golang 僵尸进程处理 go 程序，正确等待子进程退出，避免产生僵尸进程，占用系统进程表。
 | 原文链接：http://wiki.fwfyza.asia/arts/236290.Doc

原标题：golang mysql 批量导入数据实操
简介：golang 协程泄露问题排查方法，识别 Go 协程泄露现象，分析泄露场景，给出排查定位协程泄露手段。
 | 原文链接：http://wiki.fwfyza.asia/arts/720673.Doc

原标题：线上故障：Redis内存淘汰策略错误数据丢失
简介：nodejs 集群模式多核利用实现，使用 cluster 集群模式，充分利用服务器多核 CPU，提升服务处理能力。
 | 原文链接：http://wiki.fwfyza.asia/arts/524252.Doc

原标题：容器资源限制防止宿主机过载
简介：golang 配置热更新不重启服务，实现配置热加载，监听配置变更，更新内存配置，无需重启服务实例。
 | 原文链接：http://wiki.fwfyza.asia/arts/784111.Doc

原标题：线程池拒绝策略任务丢失防护
简介：代码格式化工具团队统一风格，接入格式化工具，统一全团队代码书写风格，减少格式类 git 冲突。
 | 原文链接：http://wiki.fwfyza.asia/arts/866242.Doc

原标题：golang 系统设计索引设计通用方法论汇总
简介：golang go 优雅处理信号丢失场景，处理信号丢失、信号被忽略，保障程序可以正常接收终止信号。
 | 原文链接：http://wiki.fwfyza.asia/arts/150819.Doc

四、架构设计｜Architecture
原标题：golang 系统设计缓存过期时间设置原则梳理
简介：golang go 输入数据校验防御，所有外部入参严格校验长度格式，防止恶意输入造成业务异常。
 | 原文链接：http://wiki.fwfyza.asia/arts/144203.Doc

原标题：开发复盘：长轮询接口实现服务端消息推送
简介：看懂报错日志快速定位问题，讲解日志阅读方法，解析堆栈信息含义，学会从报错信息中定位代码出错位置。
 | 原文链接：http://wiki.fwfyza.asia/arts/695846.Doc

原标题：架构笔记：冷热数据分离架构设计与迁移
简介：golang grpc 客户端流上传数据，客户端流式请求，客户端分批上传数据到服务端，适合大文件传输。
 | 原文链接：http://wiki.fwfyza.asia/arts/989279.Doc

原标题：性能调优：MySQL查询性能优化实战清单
简介：预编译 SQL 防注入实现，使用预编译 SQL 方式，杜绝 SQL 注入风险，提升数据库访问层安全能力。
 | 原文链接：http://wiki.fwfyza.asia/arts/492268.Doc

原标题：golang 系统设计契约测试接口兼容性保障思路
简介：API 大版本不兼容平滑迁移，API 版本迭代不兼容旧接口，设计平滑迁移方案，逐步完成版本切换。
 | 原文链接：http://wiki.fwfyza.asia/arts/263285.Doc

原标题：golang 系统设计分库分表本地测试调试技巧
简介：gRPC 服务端客户端入门示例，搭建 gRPC 服务端与调用客户端，学习 protobuf 定义，掌握 RPC 基础开发流程。
 | 原文链接：http://wiki.fwfyza.asia/arts/713329.Doc

原标题：golang kafka 同步异步消费对比
简介：项目构建脚本编译打包解析，解读项目构建脚本，理清编译、压缩、资源复制流程，理解打包后产物如何生成。
 | 原文链接：http://wiki.fwfyza.asia/arts/370709.Doc

原标题：git cherry‑pick 规范操作防 bug
简介：数据库分表路由写入分片修正，修复分表路由逻辑，保证数据写入正确分片，不会出现数据丢失错乱。
 | 原文链接：http://wiki.fwfyza.asia/arts/590519.Doc

原标题：golang 系统设计数据库慢查询治理方案
简介：golang contract 契约测试微服务，微服务契约测试，保证接口变更不破坏调用方，提前发现兼容性问题。
 | 原文链接：http://wiki.fwfyza.asia/arts/575134.Doc

原标题：部署复盘：容器资源限制CPU内存配置实践
简介：golang 微服务网关简易实现，http 反向代理、路由匹配、鉴权限流，理解网关核心原理。
 | 原文链接：http://wiki.fwfyza.asia/arts/856550.Doc

原标题：golang 系统设计故障复盘模板 postmortem 参考
简介：golang k8s 客户端 client‑go 简单示例，client‑go 操作 k8s 资源，增删改查 pod deployment 等资源对象。
 | 原文链接：http://wiki.fwfyza.asia/arts/812189.Doc

原标题：golang 系统设计逻辑删除物理删除选型对比
简介：Git LFS 大文件推送失败解决，配置 Git LFS，处理仓库大文件，解决大文件推送报错推送失败。
 | 原文链接：http://wiki.fwfyza.asia/arts/305479.Doc

原标题：Architecture：CI/CD流水线架构完整设计思考
简介：RPC 报文大小上限调优大请求，调大 RPC 框架报文最大限制，支持传输大体积请求报文不被截断。
 | 原文链接：http://wiki.fwfyza.asia/arts/703061.Doc

原标题：浏览器缓存强制刷新方案
简介：缓存基础原理与简单代码实现，讲解缓存设计思路，编写简易缓存逻辑，减少重复计算与重复请求，提升程序响应速度。
 | 原文链接：http://wiki.fwfyza.asia/arts/727332.Doc

原标题：golang mongodb 分页性能优化技巧
简介：静态博客部署 GitHub Pages 教程，将静态博客项目部署至 GitHub Pages，完成线上访问，快速搭建个人技术博客站点。
 | 原文链接：http://wiki.fwfyza.asia/arts/207896.Doc

原标题：golang 系统设计密码存储哈希加盐实现
简介：golang 工具函数库封装思路，Go 通用工具库封装思路，错误处理、类型转换，业务项目复用工具代码。
 | 原文链接：http://wiki.fwfyza.asia/arts/614834.Doc

原标题：踩坑记录：端口被占用导致服务启动失败
简介：golang kafka 同步异步消费对比，对比 Kafka 同步消费异步消费，分析优缺点，业务选型参考。
 | 原文链接：http://wiki.fwfyza.asia/arts/647881.Doc

原标题：运维笔记：服务器Swap分区调优生产实践
简介：golang 数据库 ORM 框架选型对比，gorm xorm sqlx 对比各 ORM 优缺点，根据业务场景选型。
 | 原文链接：http://wiki.fwfyza.asia/arts/056786.Doc

?
