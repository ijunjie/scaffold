
# Scaffold

传统的 Web 应用脚手架工程。

## 数据库

可以使用 docker 快速启动一个数据库。

```
docker run -d -p 3306:3306 --name miasql -e MYSQL_ROOT_PASSWORD=123456 mysql
```

执行 resources 下对应的 sql, 创建正式数据库和测试数据库。
git