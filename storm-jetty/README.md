
# 基于jetty+spring+mybatis实现API服务

### 执行命令

```
mvn sql:execute

注：执行完以后，更新项目（Update Project）即可以看到数据库。

mvn clean package [-Dmaven.test.skip=true]
```

### 接口说明
1. http://localhost:8111/users/{uid}   POST: User
2. http://localhost:8111/users/{uid}/{mid}   DELETE
3. http://localhost:8111/users/{uid}/{mid}/gender  GET

> 待修改Bug：执行DELETE操作时，狂打日志。。。

### 开发人员

WeChat: wgybzb

QQ: 1010437118

E-mail: wgybzb@sina.cn


