#网络IPC:套接字


- 对于上一张我们学了经典的多进程通信机制IPC:管道 、FIFO有名管道、消息队列、信号量、以及共享存储
- 这些队列允许在同一台计算机上运行的进程可以互相通信。
- 但是在本章
##Scoket
- 通过网络连接来使得不同计算机上的进程相互通信。网络进程间通信(Network IPC).一个拉风的名字 
- 在本章中，我们将描述桃姐在网络进程件通信接口，进程用该接口能够和其他进程通信，无论他们是在同一计算机内，还是在不同的计算机上。
- 实际上这就是网络套接字的设计目标之一，同样的接口既可以用于计算机间通信。也可以用于计算机内通信。
- 尽管套接字接口可以采用不同的网络协议进行通信，但本章的讨论限制在因特网事实上的通信标准。TCP/IP协议栈。
