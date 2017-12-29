# shadowsocks-
ss~ssr节点
如果选着的端口不能使用旧，请换个端口就可以。

shadowsocks  普通ss

ip 107.170.196.108

密码 ： i.wuw.red

端口 从5000 -6403  比如5001 ，5242，6321等等

加密方式 aes-256-cfb

shadowsocksR

ip 107.170.196.108

密码 i.wuw.red

端口 从5000 -6403 可以从中选个端口

加密方式 aes-256-cfb

协议 auth_sha1_v4

混淆 tls1.2_ticket_auth

因为现在国内对混淆进行了封锁。可以对混淆进行伪装

http_simple和tls1.2_ticket_auth，这两种混淆的参数分别可以设置为：

http_simple:

www.baidu.com#User-Agent: 123\nAccept: text/html\nConnection: keep-alive
tls1.2_ticket_auth:

cloudflare.com,www.baidu.com,www.youku.com
#逗号表示会在几个网址间随机选择，也可以只填其中一个网址
设置了混淆参数之后，网站才能打开，暂时ss 不会受影响

希望大家使用愉快！！！
