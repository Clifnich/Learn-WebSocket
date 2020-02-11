# Learn-WebSocket
This repository contains a simple WebSocket server written in Java. We use Maven as the dependency manager. It also contains a web page together with JavaScript code to interact with the WebSocket server.

(provide a link to the Chinese version

## Run the Server

Use the following command to run the WebSocket server.
```
$ mvn tomcat7:run
```

## Verification
Once the server is running, open your browser and visit `http://localhost:8080`. You should see the following text in the web page.

```
## WebSocket Test

CONNECTED

SENT: WebSocket rocks

RESPONSE: {"from":"a-curious-websocket-learner","content":"Connected!"}

DISCONNECTED
```
