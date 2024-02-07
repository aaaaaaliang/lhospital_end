//├── cmd                     # 应用程序的入口点
//│   ├── myapp               # “myapp”应用程序的启动命令
//│   │   └── main.go         # “myapp”应用程序的主函数
//│   └── myapp-cli           # 另一个命令行应用程序的启动命令
//│       └── main.go
//├── internal                # 私有应用程序和库代码
//│   ├── api                 # API处理器，请求/响应的逻辑
//│   ├── model               # 应用程序的数据模型
//│   ├── service             # 业务逻辑层
//│   ├── repo                # 数据访问层（数据库等）
//│   └── util                # 常用的工具或辅助函数
//├── pkg                     # 可以被外部应用程序使用的库代码
//│   ├── auth                # 认证相关的代码
//│   ├── logging             # 日志相关的代码
//│   └── middleware          # 中间件相关的代码
//├── configs                 # 配置文件模板或默认配置
//├── scripts                 # 构建脚本、部署脚本等
//├── deployments             # 部署相关的配置文件和脚本
//├── test                    # 额外的外部测试应用程序和测试数据
//├── web                     # Web应用程序特定的组件：静态文件、模板等
//├── Dockerfile              # 用于构建Docker容器的Dockerfile
//├── Makefile                # 项目的Makefile，定义了构建和运行项目的规则
//├── go.mod                  # 依赖文件
//├── go.sum                  # 依赖校验文件
//└── README.md               # 项目的README文件