## docker-compose 一键部署部署依赖以及应用

### 目录结构

```
.
├── bin // 需要允许的程序放这里
│   ├── Dockerfile
│   ├── config
│   │   └── conf.yaml
│   └── srv-example // 可执行文件
├── cache // redis 缓存数据
├── data // 数据库数据
├── db // 数据库基础镜像，初始化脚本
│   ├── 01-init.sh
│   └── Dockerfile
├── docker-compose.yaml
├── log //应用日志
│   └── test.log
└── readme.md
└── readme.md

```

### 用法
- 启动 `docker-compose up --build`,后台启动 `docker-compose up -d --build`
- 停止 `docker-compose stop`
- 查看日志 `docker-compose logs`
