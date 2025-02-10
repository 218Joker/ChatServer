# ChatServer
使用muduo库,其中的EventLoop内部封装了IO多路复用技术(epoll),提高系统的 I/O 处理能力和资源利用率<br>
使用nginx tcp负载均衡,通过负载均衡算法将请求分发到不同主机,提高并发能力<br>
使用json库序列化和反序列化消息作为私有通信协议<br>
使用redis的发布订阅功能,实现跨服务器之间的消息通信<br>
使用MySql数据库作为项目数据的存储<br>
