<p align="center">
<img src="https://i.imgur.com/pU5A58S.png" alt="Microsoft Active Directory Logo"/>
</p>

<h1>On-premises Active Directory Deployed in the Cloud (Azure)</h1>
This tutorial outlines the implementation of on-premises Active Directory within Azure Virtual Machines.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How to Deploy on-premises Active Directory within Azure Compute](https://www.youtube.com)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Active Directory Domain Services
- PowerShell

<h2>Operating Systems Used </h2>

- Windows Server 2022
- Windows 10 (21H2)

<h2>High-Level Deployment and Configuration Steps</h2>

- Step 1: Setup Resources in Azure
- Step 2: Ensure Connectivity between the client and Domain Controller
- Step 3: Install Active Directory
- Step 4: Create an Admin and Normal User Account in AD
- Step 5: Join Client-1 to my domain
- Step 6: Setup Remote Desktop for non-administrative users on Client-1
- Step 7: Create a bunch of additional users and attempt to log into client-1 with one of the users

<h2>Deployment and Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/LDja8M5.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
I start this project off by creating my usual resources in Azure. Then I proceed to ensuring the connectivity between the client and Domain Controller is running smoothly. Then I Install Active Directory.
</p>
<br />

<p>
<img src="https://i.imgur.com/ENJHiFL.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
  Then I Create an Admin and Normal User Account in AD
 Join Client-1 to my domain Setup Remote Desktop for non-administrative users on Client-1.
</p>
<br />

<p>
<img src="https://i.imgur.com/YvlxiIS.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lastly, I created a bunch of additional users and attempted to log into client-1 with one of the users and that ended my project.
</p>
<br />
