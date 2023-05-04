<p align="center">
<img src="https://i.imgur.com/Ua7udoS.png" alt="Traffic Examination"/>
</p>

<h1>Network Security Groups (NSGs) and Inspecting Traffic Between Azure Virtual Machines</h1>
In this tutorial, we observe various network traffic to and from Azure Virtual Machines with Wireshark as well as experiment with Network Security Groups. <br />




<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Various Command-Line Tools
- Various Network Protocols (SSH, RDH, DNS, HTTP/S, ICMP)
- Wireshark (Protocol Analyzer)

<h2>Operating Systems Used </h2>

- Windows 10 (21H2)
- Ubuntu Server 20.04

<h2>High-Level Steps</h2>

- Make 2 VMs with azure
- Connect to VM using Mircosoft Remote Desktop
- Download Wireshark
- Use Powershell to ping

<h2>Actions and Observations</h2>

<p>
<a href="https://imgur.com/BJAPRXk"><img src="https://i.imgur.com/BJAPRXk.jpg" title="source: imgur.com" /></a>
</p>
<p>
In this image, I am using VM1 to connect to the Remote Desktop Connection
</p>
<br />

<p>
<a href="https://imgur.com/AUPgQbv"><img src="https://i.imgur.com/AUPgQbv.jpg" title="source: imgur.com" /></a>
</p>
<p>
In this image, I am using VM2-nsg to set Inbound Security Rules
</p>
<br />

<p>
<a href="https://imgur.com/jFfJN7t"><img src="https://i.imgur.com/jFfJN7t.jpg" title="source: imgur.com" /></a>
</p>
<p>
In this image, I am inspecting the triffic between the Virtual Machines (VM1-2)
</p>
<br />
