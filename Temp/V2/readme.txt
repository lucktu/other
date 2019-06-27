edged -d mm2 -a 10.2.1.2 -c ntop2 -k note2 -l c1.smsq.ml:10086 -p 32573 -brEfA &
tcpdump -i mm2 -s0 -w 2_2.pcap icmp

edged -d mm2 -a 10.2.1.21 -c ntop2 -k note2 -l c1.smsq.ml:10086 -p 32573 -brEfA &
tcpdump -i mm2 -s0 -w 21_2.pcap icmp
