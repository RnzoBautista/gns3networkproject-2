<h1 align="center">ENTERPRISE NETWORK PROJECT #2</h1>
<h3 align="center">Dual-Site Enterprise Network Design in GNS3 | SD-WAN + BGP + Route-Map Configuration</h3>

![Network Topology](/NetworkProject-2.png)

**Overview:**
This GNS3 lab demonstrates a dual-site enterprise network (HQ and Branch) with:
- SD-WAN design concepts (policy-based path selection / failover)
- BGP (iBGP/eBGP) between sites and ISPs
- Route-maps (AS-path prepend / local preference) to influence routing
- IPsec tunnels for site-to-site secure connectivity (tunnel over dynamic routing)

<h2 align="center">IPsec Configuration on HQ & BRANCH1</h2>

![ipsecimg](/ipsec3.png)
![ipsecimg](/ipsec4.png)
![ipsecimg](/ipsec5.png)

<h4>IPsec Config note: Always make sure to have wan interface link on both branch reachable, otherwise IPsec will fail. Also consider to have matching Authentication - Phase 1 - Phase 2 similarity. :)</h4>

<h2 align="center">STATIC ROUTES</h2>

![ipsecimg](/staticroutesHQBR.png)

<h2 align="center">OSPF CONFIGURATION</h2>

![ipsecimg](/OSPF.png)

<h2 align="center">BGP CONFIGURATION</h2>

![ipsecimg](/BGP.png)

<h2 align="center">NETWORK MONITOR</h2>

![ipsecimg](/wholenetwork.png)


Check my Youtube channel for the actual configuration. 
---
*Renzo Bautista*  
- Computer Engineer | CCNA Certified  
- [GitHub Portfolio](https://github.com/RnzoBautista)  
- [YouTube Channel](https://youtube.com/@rnzobautista2329)  
- renzobautista107@gmail.com

---
*Project built and tested using GNS3 with Cisco IOSv, IOSvL2, and FortiGate VM images.*
*
