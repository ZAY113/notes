# Neo4j文档
## 驱动&编程语言向导
使用驱动来通过Bolt或Http协议连接到Neo4j
### 二进制Bolt协议
二进制协议Bolt，基于包流的序列化，支持Cypher类型的系统，协议版本，安全认证和TLS证书。对Neo4j集群，Bolt提供了负载均衡和故障转移的智能客户端路由。
Neo4j默认使用Bolt协议。官方提供.NET, Java, Spring, JavaScript, Go和Python的驱动。
### Http协议
