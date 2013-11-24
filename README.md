## Introduce

Write some sockets comunication demo using C language

Two processes can use `pipes`,`message queue` or `shared memory` which are
all inter process communication techniques
to comunicate with each other on a single system.

Socket is an end point of communication between two systems on a network.

简单理解起来socket就是ip+port,同一个网络里面不通系统之间的通信都是基于每台机器上存在的socket.

There are two types of network communication models:`OSI` and `TCP/IP`.
`OSI` is a theoretical perfect model and `TCP/IP` networking model is the most popular
and widely used.

## How to run this Demo

> gcc server.c -o server.out

> gcc client.c -o client.out

>./server.out

>./client.out 127.0.0.1
