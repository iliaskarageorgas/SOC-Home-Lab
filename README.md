<h1>SOC Home Lab</h1>

<h2>Description</h2>
Project consists of building a simple SOC Lab at home following the tutorial of the associated lesson on LetsDefend platform. 
<br/>
(Lesson Link: https://app.letsdefend.io/training/lessons/building-a-soc-lab-at-home) 
<br />


<h2>Languages and Utilities Used</h2>

- <b>Virtual Box</b>
- <b>PFSense</b> 
- <b>Windows 10 AD</b>
- <b>Windows 2022 Server</b>
- <b>BadBlood</b>
- <b>Sysmon</b>
- <b>Crowdsec</b>

<h2>Environments Used </h2>

- <b>Windows 10</b> 
- <b>Linux</b>

<h2>Virtual Machines Created </h2>

- <b>SOC_PFSENSE</b>: This machine was made for the software pfSense which is used as a Firewall/Router. 
- <b>SOC_AD</b>: This machine is used as an Active Directory Domain Controller.
- <b>SOC_Win10</b>: This machine is used as a simple workstation instance. 

<h2>Creation walk-through:</h2>

<h3>PfSense Virtual Machine:</h3>
<p align="center">
Cofiguring Network Adapters <br/>
<img src="https://i.imgur.com/STvaVTR.png" height="80%" width="80%" alt="SOC Lab"/>
<br />
<br />
pfSense Installer <br/>
<img src="https://i.imgur.com/9NOfSGO.png" height="80%" width="80%" alt="SOC Lab"/>
<br />
<br />
Configuring Network Interfaces:  <br/>
<img src="https://i.imgur.com/Q7870zq.png" height="80%" width="80%" alt="SOC Lab"/>
<br />
<br />
</p>

<h3>Active Directory Virtual Machine:</h3>
<p align="center">
Seting Up the VM and Windows 2022 Server OS <br/>
<img src="https://i.imgur.com/ZGaMNfh.png" height="80%" width="80%" alt="SOC Lab"/>
<br />
<br />
Network Adapter Configuration <br/>
<img src="https://i.imgur.com/HLDVosz.png" height="80%" width="80%" alt="SOC Lab"/>
<br />
<br />
Active Directory Installation  <br/>
<img src="https://i.imgur.com/IId9kTS.png" height="80%" width="80%" alt="SOC Lab"/>
<br />
<br />
Making the server a domain controller  <br/>
<img src="https://i.imgur.com/t5LdACo.png" height="80%" width="80%" alt="SOC Lab"/>
<br />
<br />
Adding a new AD forest  <br />
<img src="https://i.imgur.com/Bpk3jql.png" height="80%" width="80%" alt="SOC Lab"/>
<br />
<br />
Initiating BadBlood to populate Active Directory <br />
<img src="https://i.imgur.com/4e302ms.png" height="80%" width="80%" alt="SOC Lab"/>
<br />
<br />
Windows 10 Workstation Setup<br />
<img src="https://i.imgur.com/p1aw3wd.png" height="80%" width="80%" alt="SOC Lab"/>
<br />
<br />
</p>

<h3>Windows Workstation Virtual Machine:</h3>
<p align="center">
Windows 10 Workstation Setup<br />
<img src="https://i.imgur.com/p1aw3wd.png" height="80%" width="80%" alt="SOC Lab"/>
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
