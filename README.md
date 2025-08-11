<h1>Windows Server 2025 Set Up</h1>

<h2>Description</h2>
This project documents my practical experience using Windows Active Directory and Windows Server environments. It demonstrates foundational skills in setting up a domain, installing Active Directory Domain Services and Domain Name Services (DNS) roles and features, creating a new forest and domain, and setting the server as the local network DNS server.
<br />


<h2>Utilities Used</h2>

- <b>Server Manager</b> 

<h2>Environments Used </h2>

- <b>Windows Server 2025</b> 

<h2>Program walk-through:</h2>

<p align="center">
I started by changing the server's IPv4 address from dynamically configured to a static IP address. A static IP address for the domain controller is crucial as it helps maintain network reliability. <br/>
<img src="https://github.com/user-attachments/assets/be0d05c5-a5ec-4431-bb75-b9188d7f5630" height="80%" width="80%" alt="Server IP address changed to 10.0.0.1"/>
<br />
<br />
In this step, I started the Add Roles and Features wizard to install Active Directory Domain Services and DNS server. I then clicked on the flag icon to promote the server to domain controller and followed the wizard. I made sure to click on the create a new forest setting and also named the domain.  <br/>
<img src="https://github.com/user-attachments/assets/f3bf0747-0226-46ba-9ddb-fd32ad44cca0" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
This concluded the preliminary setup of the domain controller. I configured the server's IP address to a static IP address, installed Active Directory Domain Services, DNS server, and promoted the server to domain controller. Now that I've created the domain and domain controller, I can start adding users, groups, computers, and organizational units. 
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
