---
title: "Packet Headers"
subtitle: "All your favourite RFC diagrams in one place"
date: "2024-10-21"
toc: true # table of contents (only h2 and h3 added to toc)
bold: true # display post title in bold in posts list
math: true # load katex
---

## L2

## L3
### IPv4
```mermaid
---
title: "IPv4 Header"
---
packet-beta
0-3: "Version"
4-7: "IHL"
8-15: "Type of Service"
16-31: "Total Length"
32-47: "Identification"
48-50: "Flags"
51-63: "Fragment Offset"
64-71: "Time to Live"
72-79: "Protocol"
80-95: "Header Checksum"
96-127: "Source Address"
128-159: "Destination Address"
160-183: "Options"
184-191: "Padding"
```

[RFC 791 - INTERNET PROTOCOL](https://datatracker.ietf.org/doc/html/rfc791)

## L4
### UDP
```mermaid
---
title: "UDP Packet"
---
packet-beta
title UDP Packet
0-15: "Source Port"
16-31: "Destination Port"
32-47: "Length"
48-63: "Checksum"
64-95: "Data (variable length)"
```
### TCP
```mermaid
---
title: "TCP Packet"
---
packet-beta
0-15: "Source Port"
16-31: "Destination Port"
32-63: "Sequence Number"
64-95: "Acknowledgment Number"
96-99: "Data Offset"
100-105: "Reserved"
106: "URG"
107: "ACK"
108: "PSH"
109: "RST"
110: "SYN"
111: "FIN"
112-127: "Window"
128-143: "Checksum"
144-159: "Urgent Pointer"
160-191: "(Options and Padding)"
192-255: "Data (variable length)"
```

Todo: Ethernet - IPv4/v6 - ICMPv4/v6 - list RFCs - IPsec ESP tunnel Mode - IPSec Transport Mode - IKEv2 - PDU - Geneve - Vlan - VXLAN - SSL/TLS - HTTPs
