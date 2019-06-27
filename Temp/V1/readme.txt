edge1 -d mm1 -a 10.1.1.2 -c ntop1 -k note1 -l c1.smsq.ml:10082 -p 31573 -br    & 
tcpdump -i mm1 -s0 -w 2_1.pcap icmp

edge1 -d mm1 -a 10.1.1.21 -c ntop1 -k note1 -l c1.smsq.ml:10082 -p 31573 -br    & 
tcpdump -i mm1 -s0 -w 21_1.pcap icmp