# FileStructure

```markdown
├── Demo_NettyChat_Client
│   ├── src/main/java/com/nettyClient
│   │   ├── ChatClient.java
|   |   ├── ChatClientHandler.java
├── Demo_NettyChat_Client_Copy
│   ├── src/main/java/com/nettyClient
│   │   ├── ChatClient.java
|   |   ├── ChatClientHandler.java
├── Demo_NettyChat_Server
│   ├── src/main/java/com/demoServer/ChatServer
│   │   ├── ChatServer.java
|   |   ├── ChatServerHandler.java
```

# Getting Started

1. Configure all three applications seperately
2. Run Demo_NettyChat_Server first, wait till you saw `Chat Server started. Ready to accept chat clients.`
3. Run Demo_NettyChat_Client and Demo_NettyChat_Client_Copy, enter names in each console, then start typing messages.
4. Currently when one client send messages, all connected clients will receive the messages.