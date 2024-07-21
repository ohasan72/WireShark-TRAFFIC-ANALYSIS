# WireShark-TRAFFIC-ANALYSIS
learn Wireshark trafic analysis
<h2>About this  Project</h2>
<b> RedLine Stealer is information-stealing malware that harvests login credentials and other sensitive data from a victim's Windows host. This Wireshark project uses a packet capture (pcap) that “crosses a line” separating normal traffic from malicious activity. The malicious activity in this pcap is a RedLine Stealer infection from July 2023. Our pcap provides experience analyzing RedLine traffic, and we can determine what specific data was stolen from an infected Windows computer.</b> 

<h2>Scenario</h2>
<b>Traffic for this Project occurred in an Active Directory (AD) environment during July 2023. Details of the local area network (LAN) environment for the pcap follow.</b>

<h3>Local Area Network (LAN) Details</h3>

- <b>LAN segment range: 10.7.10.0/24 (10.7.10.1 through 10.7.10.255)</b>
- <b>Domain: coolweathercoat.com</b>
- <b>Domain controller IP address: 10.7.10.9</b>
- <b>Domain controller hostname: WIN-S3WT6LGQFVX</b>
- <b>LAN segment gateway: 10.7.10.1</b>
- <b>LAN segment broadcast address: 10.7.10.255</b>

<h3>Scope</h3>

- <b>What is the date and time in UTC the infection started?</b> 
- <b>What is the IP address of the infected Windows client?</b>
- <b>What is the MAC address of the infected Windows client?</b>
- <b> What is the hostname of the infected Windows client?</b>
- <b> What is the user account name from the infected Windows host?</b> 
- <b>What type of information did this RedLine Stealer try to steal?</b>




<h2>Skills you'll practice</h2>

- <b>Virtual Machine</b> 
- <b>Azure</b>
- <b>Bastion</b>
- <b>Virtual Networks</b>

<h2>Environments Used </h2>

- <b>Azure portal</b> 

<h2>Program walk-through:</h2>

<p align="center">
project images: <br/>
<img src="https://d15cw65ipctsrr.cloudfront.net/93/7b3b3df5504a5bbb6f876f50cf9864/azurevmtask1.png"/>
<br />
<br />
project images  <br/>
<img src="https://d15cw65ipctsrr.cloudfront.net/1f/da8c00bf574a9fba6f18bafa0828c2/azurevmtask2.png"/>
<br />
<br />
project images <br/>
<img src="https://d15cw65ipctsrr.cloudfront.net/ac/7ef5de5201493fa7f56fd417683df6/azurevmtask3.png"/>
<br />
<br />
project images  <br/>
<img src="https://d15cw65ipctsrr.cloudfront.net/27/13c8730869415fad77759316e29b33/azurevmtask4.png"/>
<br />
<br />
project images  <br/>
<img src="https://d15cw65ipctsrr.cloudfront.net/60/3f774fbe3744279ab2f779616350f5/azurevmtask5.png"/>
<br />
<br />
project images  <br/>
<img src="https://d15cw65ipctsrr.cloudfront.net/38/027fc7dfd946a3a8fcd3d18332391b/azurevmtask6.png"/>
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
