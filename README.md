# 基于Openresty和proxy_pool的动态代理


## Usage
```
cd 项目目录

docker-compose up -d

设置你的http/https代理为 vps:9976 即可

proxy_pool一直在后台实时爬取最新代理，并且每40秒同步更新一次openresty的代理池库
```

