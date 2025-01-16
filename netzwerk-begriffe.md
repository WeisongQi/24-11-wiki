ARP:Address Resolution Protocol

ICMP:Internet Control Message Protocol

TCP/IP:Transport Control Protocol / Internet Protocol

HTTP/HTTPS: HyperText Transfer Protocol / HyperText Transfer Protocol Secure

FTP: File Transfer Protocol

POP3: Post Office Protocol 3

SMTP: Simple Mail Transfer Protocol

SSH: Secure Shell

DNS: Domain Name System

PPPoE: Point-to-Point Protocol over Ethernet

DHCP: Dynamic Host Configuration Protocol

LAN: Local Area Network

WAN: Wide Area Network

PAN: Personal Area Network

MAN: Metropolitan Area Network

NAT（Network Address Translation）
网络地址转换是一种用于在私有网络和公有网络之间转换IP地址的技术。NAT的主要功能是将私有网络中的内部IP地址转换为公共IP地址，从而使多个设备可以通过一个公共IP地址访问互联网。NAT有助于节约IP地址资源，并提供了一定程度的网络安全性。

DNS（Domain Name System）
域名系统是一种用于将域名（如 www.example.com）转换为IP地址（如 192.0.2.1）的系统。DNS是一种分布式数据库，通过DNS服务器进行管理和查询。它使得用户可以通过记忆容易的域名访问网站，而无需记住复杂的IP地址。

Private Subnet（私有子网）
私有子网是一个IP地址范围，主要用于组织内部网络中，不直接对外部网络（如互联网）开放。私有子网使用私有IP地址（如 192.168.x.x，10.x.x.x 等），这些地址在互联网中不能路由，主要用于公司、学校等内部网络的通信。

Public Subnet（公共子网）
公共子网是一个IP地址范围，直接对外部网络（如互联网）开放。公共子网使用公共IP地址，这些地址在互联网上可以路由，允许外部网络访问。公共子网通常用于托管网站、邮件服务器和其他需要对外公开访问的服务。

Software Ports（软件端口）
软件端口是网络通信中用于标识特定应用程序或服务的数字标识符。端口号范围从0到65535，其中一些常见的端口号有特定的用途（如 HTTP 的端口80，HTTPS 的端口443）。端口号帮助确保数据包可以传递给正确的应用程序或服务。

常见端口列表
20：FTP数据传输

21：FTP控制（命令）

22：SSH（安全外壳协议）

23：Telnet（不推荐使用，因为不安全）

25：SMTP（简单邮件传输协议）

53：DNS（域名系统）

67/68：DHCP（动态主机配置协议）

80：HTTP（超文本传输协议）

110：POP3（邮局协议3）

119：NNTP（网络新闻传输协议）

123：NTP（网络时间协议）

143：IMAP（互联网消息访问协议）

161/162：SNMP（简单网络管理协议）

179：BGP（边界网关协议）

443：HTTPS（安全超文本传输协议）

465：SMTPS（简单邮件传输协议安全）

514：Syslog（系统日志协议）

993：IMAPS（安全互联网消息访问协议）

995：POP3S（安全邮局协议3）

1080：SOCKS代理

1433：MSSQL（微软SQL服务器）

1521：Oracle数据库

3306：MySQL数据库

3389：RDP（远程桌面协议）

5900：VNC（虚拟网络计算）

6379：Redis缓存

8080：HTTP备用端口

8443：HTTPS备用端口