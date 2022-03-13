# pcap


```
pcap过滤器基于一个声明式的谓词语法;
过滤器则是一个包含了过滤表达式的ASCII字符串;
表达式通过pcap_compile()翻译为一个内核级包过滤器的程序;
```



## 目录


* [pcap语法man手册](docs/pcap语法man手册.md)
* [tcpdump命令man手册](docs/tcpdump命令man手册.md)


## tcpdump常用命令

```
tcpdump -i eth1  # -i 指定网卡
tcpdump -i eth1  -nn   # 不做域名解析
tcpdump -i eth1  -nn  -w data.pcap   # 写入标准pcap到指定文件中
tcpdump -i eth1  -nn  -w data.pcap  -c 10    # 抓10个packets后结束退出
tcpdump -i eth1  -nn  -w data.pcap  -c 10  -t   # 每个packets开头不显示时间戳
tcpdump -i eth1  -nn  -w data.pcap  -c 10  -tttt   # 每个packets开头显示年月日时分秒时间戳
tcpdump -i eth1  -nn  -w data.pcap  -c 10  -s 32   # 指定所要解析packet大小，超过不解析
tcpdump -i eth1  -nn  -w data.pcap  -c 10  -A  # hexdump尽量以ASCII显示包内容，一般乱码
```





## pcap常用语法








































---
