# Learn-WebSocket 
本代码库维护了一个简单的 WebSocket 服务器。该服务器用 Java 写成，我们用 Maven 作依赖管理。作为验证措施，我们也提供了一些前端代码。

## 运行服务器

使用下面的 shell 命令来启动 WebSocket 服务器。
```
$ mvn tomcat7:run
```

## 自我验证
服务器启动以后，打开浏览器 `http://localhost:8080`. 如果在网页上看到如下内容，就说明运行正确。

```
WebSocket Test

CONNECTED

SENT: WebSocket rocks

RESPONSE: {"from":"a-curious-websocket-learner","content":"Connected!"}

DISCONNECTED
```
