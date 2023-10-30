<h1>Setup SIEM in Azure Lab</h1>

<h2>Description</h2>
In this lab we walk through how to setup a SIEM in Azure and connect it to a Virtual Machine acting a honeypot. We will observe live attacks (RDP Brute Force) from around the world. We will look up the attacker's Geolocation information and plot it on the Azure Sentinel Map using a custom PowerShell Script.
<br />


<h2>Languages and Utilities Used</h2>

- <b>Azure</b> 
- <b>PowerShell</b>

<h2>Environments Used </h2>

- <b>Windows 11</b> (22H2)
- <b>Microsoft Azure</b> 

<h2>Program walk-through:</h2>

<p align="center">
Create Virtual Machine: <br/>
<img src="https://i.imgur.com/g4xg5IW.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Create Network Security Group: <br/>
<img src="https://i.imgur.com/QcMngKJ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Create Logs Analytics Workspace: <br/>
<img src="https://i.imgur.com/QvgyX85.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Turn off Windows Defender for the SQL Servers: <br/>
<img src="https://i.imgur.com/9znziVd.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Connect Virtual Machine to Log Analytics: <br/>
<img src="https://i.imgur.com/X15j8Eb.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br /> 
Create Microsoft Sentinel (SIEM): <br/>
<img src="https://i.imgur.com/bIxlb83.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br /> 
Log in to Virtual Machine with Remote Desktop Connection app: <br/>
<img src="https://i.imgur.com/ihsXQxh.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />   
Disable firewall in Virtual Machine: <br/>
<img src="https://i.imgur.com/vA3S7US.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br /> 
Run code with API in PowerShell inside Virtual Machine: <br/>
<img src="https://i.imgur.com/gN6Y18h.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br /> 
Create custom log: <br/>
<img src="https://i.imgur.com/Wa7OZws.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br /> 
Run FAILED_RDP_WITH_GEO_CL code in logs: <br/>
<img src="https://i.imgur.com/emqLPn3.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br /> 
Microsoft Sentinel: <br/>
<img src="https://i.imgur.com/tFmss4g.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Run query code and choose maps as vizualization: <br/>
<img src="https://i.imgur.com/GW1ognZ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Map of attacks: <br/>
<img src="https://i.imgur.com/6S3u9Ce.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
