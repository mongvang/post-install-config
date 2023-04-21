<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10 Pro</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

- Configure Roles
- Configure Departments
- Configure Teams
- Configure Agents (workers)
- Configure Users (customers)
- Configure SLA
- Configure Help Topics

<h2>Configuration Steps</h2>

<p>
1) Configure Roles<br>
Admin Panel -> Agents -> Add New Role <br>
Supreme Admin > Apply Permissions
</p>
<p>
<img src="https://i.imgur.com/xGrbVKt.png" height="50%" width="50%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/KDb4Z2i.png" height="50%" width="50%" alt="Disk Sanitization Steps"/>
</p>
<br />

<p>
2) Configure Departments<br>
Admin Panel -> Agents -> Add New Department<br>
- Add System Administrators<br>
</p>
<p>
<img src="https://i.imgur.com/NtoG6a3.png" height="70%" width="70%" alt="Disk Sanitization Steps"/><br>
<img src="https://imgur.com/yCuLEBl.png" height="40%" width="40%" alt="Disk Sanitization Steps"/>
</p>
<br />

<p>
3) Configure Teams<br>
Admin Panel -> Agents -> Teams<br>
Level I Support<br>
-Add Level II Support<br>
-Add Members (Employees)
</p>
<p>
<img src="https://i.imgur.com/6Psc8qK.png" height="70%" width="70%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/tE7obLj.png" height="50%" width="50%" alt="Disk Sanitization Steps"/>
</p>
<br />

<p>
4) Allow anyone to create tickets<br>
Admin Panel -> Settings -> User Settings<br>
Registration Required: Require registration and login to create tickets<br>
</p>
<p>
<img src="https://i.imgur.com/hfSWK8m.png" height="50%" width="50%" alt="Disk Sanitization Steps"/>
</p>
<br />

<p>
5) Configure Agents (workers) <br>
Admin Panel -> Agents -> Add New Agent<br>
-Configure each agents access and permission<br>
</p>
<p>
<img src="https://i.imgur.com/S6k3Axi.png" height="50%" width="50%" alt="Disk Sanitization Steps"/>
</p>
<br />

<p>
6) Configure Users (customers) <br>
Agent Panel -> Users -> Add User (Employees)
</p>
<p>
<img src="https://i.imgur.com/Cnm6nj3.png" height="50%" width="50%" alt="Disk Sanitization Steps"/>
</p>
<br />

<p>
7) Configure SLA (Service Level Agreements) *How fast a ticket should be answered<br>
Admin Panel -> Manage -> SLA <br>
*Sev-A (1 hour, 24/7) <br>
*Sev-B (4 hours, 24/7) <br>
*Sev-C (8 hours, business hours) <br>
</p>
<p>
<img src="https://i.imgur.com/j726jUo.png" height="50%" width="50%" alt="Disk Sanitization Steps"/>
</p>
<br />
