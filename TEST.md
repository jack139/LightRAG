# TEST


## 创建容器

```bash
docker compose -f docker-compose-test.yml build
```


## 启动容器

```bash
docker compose -f docker-compose-test.yml up

# 后台启停
docker compose -f docker-compose-test.yml up -d
docker compose -f docker-compose-test.yml down
```


## 测试页面

```bash
http://127.0.0.1:9621
```