
### Sample script to view different protocol headers 

```
import scapy
from scapy.all import DHCP, ARP, BOOTP, Ether, UDP, TCP, IP
```

- data link layer
- [ethernet] (http://www.networksorcery.com/enp/protocol/ethernet.htm)
```
ethernet = Ether()
ethernet.show()
```

- network layer
- [ARP] (http://www.networksorcery.com/enp/protocol/ARP.htm)
```
arp = ARP()
arp.show()
```

- [IP](http://www.networksorcery.com/enp/protocol/IP.htm)
```
ip = IP()
ip.show()
```

- transport layer
- [UDP](http://www.networksorcery.com/enp/protocol/UDP.htm)
```
udp = UDP()
udp.show()
```
- [TCP](http://www.networksorcery.com/enp/protocol/TCP.htm)
```
tcp = TCP()
tcp.show()
```

- [BOOTP + DHCP headers] (www.networksorcery.com/enp/protocol/DHCP.htm)
bootp = BOOTP()
bootp.show()
dhcp = DHCP()
dhcp.show()