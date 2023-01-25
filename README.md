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

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

- Azure Virtual Machines
- osTicket website
- osTicket Installation files

<h2>Configuration Steps</h2>

<p>
<img src="https://i.imgur.io/4LZ8Z6F_d.webp?maxwidth=640&shape=thumb&fidelity=medium" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Login with your credentials on the osTicket website. Register as an Agent panel and proceed to Agents = Roles = Add New Role. Create any sort of username for Name and go to permissions. Depending on the organization it may request divergent roles but let's check and add every role under Tickets, tasks, and Knowledgebase for this tutorial. 
</p>
<br />

<p>
<img src="https://i.imgur.io/4OcX0mj_d.webp?maxwidth=640&shape=thumb&fidelity=medium" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Formulate a new department, agents, and team by going to Agents = Departments = Add New Department, create a new name for the department. Replicate the same steps for Teams and Agents. Under Add New Agents, fill in all the information necessary for the agents. When creating Agent password, uncheck Send the agent a password reset email and Require password change at next login. The Access, Permissions, and Teams section permits the agent access to be assigned in any role. Next, go to Users = User Directory, and duplicate the same protocol for customers 
<br />

<p>
<img src="https://i.imgur.io/n6E0VN5_d.webp?maxwidth=640&shape=thumb&fidelity=medium" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Go to Admin Panel = Settings = Usersettings and ensure Require registration and login to create tickets is unchecked. Configure SLA by going to Admin Panel = Manage = SLA. Create three SLA plans: Sev-A (1 hour 24/7), Sev-B (4 hour 24/7), Sev-C (8 hours, business hours)
</p>
<br />

<p>
<img src="https://i.imgur.io/w3B6i8J_d.webp?maxwidth=640&shape=thumb&fidelity=medium" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Go to Admin Panel = Manage = Help Topics. Enter the four technical issues (Business Critical Outage, Personal Computer Issues, Equipment Request, Password Reset) under Topic separately and Save Changes.
</p>
<br />
