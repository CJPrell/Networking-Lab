<h1>Networking Lab 01: TCP/IP and Network Traffic Analysis</h1>

<h2>Description</h2>
This project documents the construction of a small virtual networking lab hosted on my ZimaOS home server. The environment consists of a Windows 11 client virtual machine and an Ubuntu Linux virtual machine connected through the same virtual network.

The purpose of this lab is to develop practical experience with foundational networking concepts commonly used in IT support, network administration, and cybersecurity roles. The lab includes IP configuration, connectivity testing, DNS name resolution, packet analysis, service hosting, and basic network troubleshooting.<br />


<h2>Languages and Utilities Used</h2>

- <b>PowerShell</b> 
- <b>Windows Command Prompt</b>
- <b>Linux Bash</b>
- <b>Wireshark</b>
- <b>Python HTTP Server</b>
- <b>ipconfig</b>
- <b>ping</b>
- <b>nslookup</b>
- <b>tracert</b>
- <b>arp</b>
- <b>Test-NetConnection</b>

<h2>Environments Used </h2>

- <b>ZimaOS Home Server</b>
- <b>Windows 11 Virtual Machine (24H2)</b> 
- <b>Ubuntu Linux Virtual Machine</b> 
- <b>ZimaOS Virtual Network</b> 
- <b>GitHub</b>
 
<h2>Program walk-through:</h2>

<p align="center">
01 - VM Creation: <br/>
 
 I created two virtual machines on my ZimaOS home server:
 
- <b>A Windows 11 client VM <b/>
- <b>An Ubuntu Linux VM <b/>

Both virtual machines were connected to the same ZimaOS virtual network so that they could communicate with each other.

<p align="center">
  <img src="https://i.imgur.com/QBkxOik.png"
       alt="Windows 11 VM configuration in ZimaOS"
       width="750">
</p>

<p align="center">
  <em>Figure 1: Windows 11 virtual machine configuration in ZimaOS.</em>
 
<p align="center">
  <img src="https://i.imgur.com/QBkxOik.png"
       alt="UBUNTU VM configuration in ZimaOS"
       width="750">
</p>

<p align="center">
  <em>Figure 2: Ubuntu virtual machine configuration in ZimaOS.</em>

 <p align="center">
  <img src="https://i.imgur.com/CXI3GIe.png"
       alt="Both VMs Running"
       width="750">
</p>

<p align="center">
  <em>Figure 3: Both VMs Running.</em>
<br />
<br />
02 - Network design:  <br/>
 
 The lab consists of two virtual machines hosted on a ZimaOS home server. 
 
 Both virtual machines are connected to the same virtual network, allowing them to communicate with each other and access external network resources through the home router.
 
 <p align="center">
  <img src="https://i.imgur.com/KbfaXsJ.png"
       alt="Network Design"
       width="750">
</p>

<p align="center">
  <em>Figure 4: Network topology showing the Windows 11 and Ubuntu Linux virtual machines connected to the same virtual network on the ZimaOS home server.</em>
<br />
<br />
03 - Windows Network Configuration: <br/>
<img src="https://i.imgur.com/nCIbXbg.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
04 - Ubuntu Network Configuration:  <br/>
<img src="https://i.imgur.com/cdFHBiU.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
05 - Internet Connectivity:  <br/>
<img src="https://i.imgur.com/JL945Ga.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
06 - VM Conectivity:  <br/>
<img src="https://i.imgur.com/K71yaM2.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
07 - Ubuntu Web Server:  <br/>
<img src="https://i.imgur.com/AeZkvFQ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
 08 - VM Connectivity:  <br/>
<img src="https://i.imgur.com/K71yaM2.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
 09 - Wire Shark Setup:  <br/>
<img src="https://i.imgur.com/K71yaM2.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
 10 - ARP Analysis:  <br/>
<img src="https://i.imgur.com/K71yaM2.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
  11 - ICMP Analysis:  <br/>
<img src="https://i.imgur.com/K71yaM2.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
  12 - DNS Analysis:  <br/>
<img src="https://i.imgur.com/K71yaM2.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
  13 - TCP HTTP Analysis:  <br/>
<img src="https://i.imgur.com/K71yaM2.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
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
