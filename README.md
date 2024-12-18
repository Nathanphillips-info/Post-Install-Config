# Post-Install-Config
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

- Item 1: Configure Roles
- Item 2: Configure Departments
- Item 3: Configure Teams 
- Item 4: Configure Agents
- Item 5: Configure Users
- Item 6: Configure SLA's
- Item 7: Configure Help Topics

<h2>Configuration Steps</h2>

<p>
- In Admin Panel/Agents/Roles, Create a Super Admin role with access to everything. 
</p>
<p>
- In Admin Panel/Agents/Departments, create a Sys Admin department. 
</p>
<p>
- Under the teams tab, create an online banking team. 
</p>
<p>
- In the Admin Panel/Settings/User settings, uncheck unregistered users can create tickets. Require registration to create tickets. 
</p>
<p>
- Configure new agents in the Admin Panel/Agents/Add new, and create Jane and John Doe agents. Add Jane to Sys admins and John to support. 
</p>
<br />

<p>
<img src="https://github.com/user-attachments/assets/4d8ed493-f191-4ef9-b549-1b7d0a0f7986"/>
</p>
<p>
- Next, configure users; in the Agent panel, click users and add new users. You can name them Karen and Ken. 
</p>
<p>
- Next, We will configure SLAs. You can add A Sev-A, Sev-B, and Sev-C. Give each a different level; for instance, Sev-A, I gave a 1-hour response window in a 24/7 schedule. This can be configured in Admin Panel/Manage/SLA. 
</p>
<br />

<p>
<img src="https://github.com/user-attachments/assets/f9f03387-83c3-42c6-bd89-c230c800d961"/>
</p>
<p> 
- Next, I configured help topics and added several, including a business-critical outage help topic, a personal computer issues help topic, an equipment reset help topic, a password reset help topic, and an "other" help topic. Help topics can be configured in the Admin Panel/Manage/Help topics. 
</p>
<br />
<p>
<img src="https://github.com/user-attachments/assets/326a31c0-f357-4328-ba0b-1ead7ff0bb0e"/>
</p>
