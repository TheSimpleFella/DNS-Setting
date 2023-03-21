# DNS (Domain Name System)
Active Directory Domain Services: Setting DNS so users can log into their account.

<p align="center">
<img src="https://user-images.githubusercontent.com/126700220/226635953-574a772b-a2d4-4f68-8c49-cb06d0d6b3e7.png"/>
</p>

<h1>Active Directory Domain Services Lab</h1>
<br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Active Directory Domain Services
- Service Manager
- Active Directory Users and Computers
- Windows Server for Domain Controller

Quick Note: 

-DC=Domain Controller

-VM=Virtual Machine

-ICMP=Internet Control Message Protocol

-DS=Domain Service

-DNS=Domain Name System


<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)
- Windows 11 PC

<h2>A brief look at the steps.</h2>
I show how I connected the client DNS to the DC successfully.
Enjoy the slides.

<h2>Screenshots of Steps</h2>

<p>
<img src="https://user-images.githubusercontent.com/126700220/226655207-286d7d51-8128-4237-9e64-91650356e865.png" width="80%" alt="Disk Sanitization Steps"/>
</p>
I logged into the AZure portal. Then I located the client VM.
<p>
</p>
<br />

<p>
<img src="https://user-images.githubusercontent.com/126700220/226655606-706f491a-03dc-4a75-9585-8c8806646cbe.png" width="80%" alt="Disk Sanitization Steps"/>
</p>
Selected the Networking tab.
<p>
</p>
<br />

<p>
<img src="https://user-images.githubusercontent.com/126700220/226656048-9604dc34-1287-4c52-8533-03445053ede0.png" width="80%" alt="Disk Sanitization Steps"/>
</p>
Clicked on the virtual NIC (Network Interface Card). 
<p>
</p>
<br />

<p>
<img src="https://user-images.githubusercontent.com/126700220/226656406-66d2955e-0b76-43f4-b012-3e2f51b91744.png" width="80%" alt="Disk Sanitization Steps"/>
</p>
Selected DNS Server. 
<p>
</p>
<br />

<p>
<img src="https://user-images.githubusercontent.com/126700220/226656570-25ac23cb-a997-4449-83d0-e3ca50206c25.png" width="80%" alt="Disk Sanitization Steps"/>
</p>
Selected "Custom" then entered the DC's private IP address. This allows the thousands of users to log into their accounts successfully. 
<p>
</p>
<br />

<p>
<img src="https://user-images.githubusercontent.com/126700220/226657086-ce0512a4-b1bc-4256-95ca-7a9eb1f7610d.png" width="80%" alt="Disk Sanitization Steps"/>
</p>
Restarted the client. 
<p>
</p>
<br />

<p>
<img src="https://user-images.githubusercontent.com/126700220/226657337-59450100-1591-4d68-a18f-ce7961f40809.png" width="80%" alt="Disk Sanitization Steps"/>
</p>
Within the client VM, I changed the domain to the DC's domain. In this instance, the domain was michael.com.
<p>
</p>
<br />

<p>
<img src="https://user-images.githubusercontent.com/126700220/226657825-5cb53453-6c66-4d6b-9242-2924c3b4ed2c.png" width="80%" alt="Disk Sanitization Steps"/>
</p>
Now Jane Doe can log into her account as a user. 
<p>
</p>
<br />


Check out the other link: 

-Link: - [Azure: Active Directory Domain Services](https://github.com/TheSimpleFella/Deploying-Active-Directory.git)


Thank you for looking at my work.
