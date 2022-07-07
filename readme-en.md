## docker-compose quickly deploy   applications and dependencies

### directory

```
.
├── bin // Programs is here
│   ├── Dockerfile
│   ├── config
│   │   └── conf.yaml
│   └── srv-example // binary
├── cache  // redis cache
├── data   // database data
├── db     // Database base image, initialization script
│   ├── 01-init.sh
│   └── Dockerfile
├── docker-compose.yaml
├── log     // log
│   └── test.log
├── readme-en.md
└── readme.md

```

### usage
- start up `docker-compose up --build`,start up with background `docker-compose up -d --build`
- stop `docker-compose stop`
- View logs `docker-compose logs`
