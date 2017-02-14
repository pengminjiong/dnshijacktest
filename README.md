DNShijack　DNS劫持 (DNS ハイジャック and 中間者攻撃)

experiment environment:
VirtualBox:
two VMs: a) 192.168.99.100
         b) 192.168.99.101

set host-only network for two VMs

Tools:  Ettercap and Wireshark:

中間者攻撃:

1.sniff the network interface
2.scan and get the target host IP
3. target it
4.ARP poisoning
5. capture packets with Wireshark

DNShijack:

0.edit (/etc/ettercap/etter.nds)
1.sniff the network interface
2.scan and get the target host IP
4. find DNS server IP
3. target host and DNS server
4.ARP poisoning
5. DNS spoof



Results:劫持 谷歌网址成功
![image](https://github.com/pengminjiong/dnshijacktest/blob/master/Screen2.png)





extra： 基于apache 做一个钓鱼网站， 吸引填写密码 呵呵， 小试牛刀。
end
