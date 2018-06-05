# 1 Concept of Neighbor
### 1.1 Overview the Neighbor System in Linux

Overview:

![Alt text](/pic/overview.png)

ARP/ND protocol in networking stack:

![Alt text](/pic/ARP_ND.png)

### 1.2 The Normal Neighbor System to do:

1. Supply a cache for L2/L3 transforming result.
2. Supply quick function to operate this Cache, include: Add, Delete, Modify and Search.
3. Supply aging mechanism for every Neighbor protocol.
4. Supply replace mechanism when Cache is full.
5. Supply solicitation require queue for each Neighbor, make sure the requirement being sent, until receive the acknowledge.


***In Linux, Only IPv4 and IPv6 can use the Proxy Neighbor Protocol.***


### 1.3 The condition of Proxy
1. Based on Device
2. Based on Destination

![Alt text](/pic/proxy.png)

### 1.4 When sent Requirement and Deal with Solicitation requirement

![Alt text](/pic/send.png)


![Alt text](/pic/Deal.png)
