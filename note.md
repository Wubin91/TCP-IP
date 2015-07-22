####TCP/IP端口号
TCP、UDP通过16bits的端口号来识别应用程序，下面是一些常用协议的固定端口号：
* FTP - TCP端口号 - 21
* Telnet - TCP端口号 - 23
* TFTP（简单文件传送协议） - UDP端口号 - 69

可以通过`grep xxx /etc/services`查看具体xxx所使用的端口号
