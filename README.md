
<h1>Active Directory Homa Lab </h1>

<!-- ### [Kaltura Capture Recording](https://mediaspace.minnstate.edu/media/Kaltura+Capture+recording+-+April+26th+2025%2C+11%3A11%3A10+pm/1_sp0j5ef9) -->

<h2>Description</h2>
This project simulates a Windows Active Directory (AD) environment using Windows Server 2019 as the Domain Controller (DC) and Windows 10 as a domain-joined client, all within VirtualBox. The Domain Controller has Active Directory Domain Services (AD DS) and DNS configured, DHCP for IP address assignment,RAS/NAT role configured for internet access: NAT setup enables the internal domain client to access external resources via the DC's Internet NIC.

**Skills Practiced:**
-AD DS and DNS setup
-DHCP configuration
-Network Address Translation (NAT) with RRAS
-VirtualBox networking (internal + bridged)
-Client domain join and user authentication
<br />


<h2>Languages and Utilities Used</h2>

- <b>Windows Server 2019</b>
- <b>Windows 10</b>
- <b>Internet (Home Router)</b> 

<h2>Environments Used </h2>

- <b>Oracle VirtualBox</b> 

<h2>Program walk-through:</h2>

<p align="center">
Lab Design: <br/>
<img src="https://i.imgur.com/00Oq1nj.png" style="width:80%; height:auto;" alt="Disk Sanitization Steps"/>
<br />
<br />
VirtualBox Setup:  <br/>
<img src="https://i.imgur.com/GZgfuXA.png" style="width:80%; height:auto;" alt="Disk Sanitization Steps"/>
<br />
<br />
Interface and Static Route Configuration (Router R1):  <br/>
<img src="https://i.imgur.com/EgSTRkw.png" style="width:80%; height:auto;" alt="Disk Sanitization Steps"/>
<br />
<br />
Central-Office Server IP address and Subnet Mask (Server): <br/>
<img src="https://i.imgur.com/jP7OdJn.png" style="width:80%; height:auto;" alt="Disk Sanitization Steps"/>
<br />
<br />
Central-Office Server DHCP Service ON (Server):  <br/>
<img src="https://i.imgur.com/Ffiyksg.png" style="width:80%; height:auto;" alt="Disk Sanitization Steps"/>
<br />
<br />
Cell-Tower 3G/4G Server Range in meters:  <br/>
<img src="https://i.imgur.com/ESYdS0n.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Cell-Tower Attributes:  <br/>
<img src="https://i.imgur.com/BFh37gV.png" style="width:80%; height:auto;" alt="Disk Sanitization Steps"/>
<br />
<br />
Smartphone11 IP Received From Cell-Tower DHCP Server:  <br/>
<img src="https://i.imgur.com/PXy9ViO.png" style="width:80%; height:auto;" alt="Disk Sanitization Steps"/>
<br />
<br />
Smartphone12 IP Received From Cell-Tower DHCP Server: <br/>
<img src="https://i.imgur.com/NFf1bjb.png" style="width:80%; height:auto;" alt="Disk Sanitization Steps"/>
<br />
</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>

