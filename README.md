# 一些小练习 
- IO_Mutipath 
  - 简单实现了EPOLL,POLL,SELECT的回显服务器 
- My_Cp
  - 简单实现了一个cp指令
- My_malloc 
  - 通过系统调用sbrk(),基于双向链表管理实现了一个malloc和free
- Ping 
  - 使用原始套接字,拼接icmp报文,实现了一个简易的ping命令
- PV 
  - 使用IPC的信号量尝试解决了哲学家就餐问题
- shell
  - 一个简单的shell解释器 支持重定向和管道 
    - 不支持多重管道(思路:递归实现)
- TCPserver
  - 分别实现了多进程和多线程回显服务器
- UDPserver 
  - UDP无连接,while(1)recv报文...

