DNShijack　DNS劫持 (DNS ハイジャック and 中間者攻撃)

experiment environment:
VirtualBox:
two VMs: 1. 192.168.99.100
         2. 192.168.99.101

set host-only network for two VMs

Tools:  Ettercap and Wireshark:

中間者攻撃
1.sniff the network interface
2.scan and get the target host IP
3. target it
4.ARP poisoning
5. capture packets with Wireshark

DNShijack

0.edit (/etc/ettercap/etter.nds)
1.sniff the network interface
2.scan and get the target host IP
4. find DNS server IP
3. target host and DNS server
4.ARP poisoning
5. DNS spoof


Screenshot
