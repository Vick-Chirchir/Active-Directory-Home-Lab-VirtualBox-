
<h1>Active Directory Homa Lab </h1>

<!-- ### [Kaltura Capture Recording](https://mediaspace.minnstate.edu/media/Kaltura+Capture+recording+-+April+26th+2025%2C+11%3A11%3A10+pm/1_sp0j5ef9) -->

<h2>Description</h2>
This project simulates a Windows Active Directory (AD) environment using Windows Server 2019 as the Domain Controller (DC) and Windows 10 as a domain-joined client, all within VirtualBox. The Domain Controller has Active Directory Domain Services (AD DS) and DNS configured, DHCP for IP address assignment, RAS/NAT role configured for internet access: NAT setup enables the internal domain client to access external resources via the DC's Internet NIC.

**Skills Practised:**
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
NIC’s Setup (Domain Controller-DC)  <br/>
<img src="https://i.imgur.com/GeZOeGt.png" style="width:80%; height:auto;" alt="Disk Sanitization Steps"/>
<br />
<br />
Internal NIC(Domain Controller-DC) <br/>
<img src="https://i.imgur.com/VH9vScu.png" style="width:80%; height:auto;" alt="Disk Sanitization Steps"/>
<br />
<br />
Active Directory Domain Controller Installed and Domain (mydomain.com) Configured (Domain Controller-DC)  <br/>
<img src="https://i.imgur.com/QRlRUWz.png" style="width:80%; height:auto;" alt="Disk Sanitization Steps"/>
<br />
<br />
Script to add Users to mydomain.com from name.txt file (Domain Controller-DC) <br/>
<img src="https://i.imgur.com/ZSD6Fqy.png" style="width:80%; height:auto;" alt="Disk Sanitization Steps"/>
<br />
<br />
Script running to add users to the Active Directory (Domain Controller-DC) <br/>
<img src="https://i.imgur.com/485asyY.png" style="width:80%; height:auto;" alt="Disk Sanitization Steps"/>
<br />
<br />
Users successfully added to the Active Directory (Domain Controller-DC) <br/>
<img src="https://i.imgur.com/ToOmut6.png" style="width:80%; height:auto;" alt="Disk Sanitization Steps"/>
<br />
<br />
Client1 has successfully joined mydomain.com (Domain Controller-DC) <br/>
<img src="https://i.imgur.com/XyygsbS.png" style="width:80%; height:auto;" alt="Disk Sanitization Steps"/>
<br />
<br />
RAS/NAT Configuration (NAT selected) (Domain Controller-DC)<br/>
<img src="https://i.imgur.com/UlUKMxD.png" style="width:80%; height:auto;" alt="Disk Sanitization Steps"/>
<br />
<br />
Remote Access Successfully Configured (Domain Controller-DC)<br/>
<img src="https://i.imgur.com/5XbzxFP.png" style="width:80%; height:auto;" alt="Disk Sanitization Steps"/>
<br />
<br />
Routing and Remote Access Details (Outside: Internet NIC and Inside: Internal NIC) (Domain Controller-DC) <br/>
<img src="https://i.imgur.com/97K9tJW.png" style="width:80%; height:auto;" alt="Disk Sanitization Steps"/>
<br />
<br />
DHCP Configuration (Domain Controller-DC)<br/>
<img src="https://i.imgur.com/wHPCIDM.png" style="width:80%; height:auto;" alt="Disk Sanitization Steps"/>
<br />
<br />
DHCP Pool Configuration (Domain Controller-DC)<br/>
<img src="https://i.imgur.com/ahtwL9h.png" style="width:80%; height:auto;" alt="Disk Sanitization Steps"/>
<br />
<br />
DHCP Start - End IP address and Subnet Mask (Domain Controller-DC) <br/>
<img src="https://i.imgur.com/RgpyfMi.png" style="width:80%; height:auto;" alt="Disk Sanitization Steps"/>
<br />
<br />
Complete DHCP Configuration (Domain Controller-DC)<br/>
<img src="https://i.imgur.com/IEeZeKZ.png" style="width:80%; height:auto;" alt="Disk Sanitization Steps"/>
<br />
<br />
CLIENT1 Installed and added to mydomain.com (CLIENT1) <br/>
<img src="https://i.imgur.com/oRotD3w.png" style="width:80%; height:auto;" alt="Disk Sanitization Steps"/>
<br />
<br />
CLIENT1 is successfully connected to mydomain.com (CLIENT1) <br/>
<img src="https://i.imgur.com/QC99MMe.png" style="width:80%; height:auto;" alt="Disk Sanitization Steps"/>
<br />
<br />
CLIENT1 IP Configuration-DHCP (DNS and Default Gateway) (CLIENT1).   <br/>
<img src="https://i.imgur.com/52s5t63.png" style="width:80%; height:auto;" alt="Disk Sanitization Steps"/>
<br />
<br />
Verifying that CLIENT1 can reach the Internet via DC and DNS is working (CLIENT1) <br/>
<img src="https://i.imgur.com/own5dGp.png" style="width:80%; height:auto;" alt="Disk Sanitization Steps"/>
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

