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


  - Configure Roles
  - Configure Departments
  - Configure Teams
  - Configure Agents
  - Configure Users
  - Configure SLA
  - Configure Help Topics

<h2>Configuration Steps</h2>

<h3 align="center">Configure Roles</h3>
<br />
<p>
  Admin Panel -> Agents -> Roles.
</p>
<p>
  Supreme Admin:
</p>
<p>
  
 ![roles](https://github.com/user-attachments/assets/d11bf918-08bc-4cd2-a3b7-87f758cc256f)

</p>
<br />
<br />
<h3 align="center">Configure Departments</h3>
<br />
<p>
  Admin Panel -> Agents -> Departments.
</p>
<p>
  System Administrators:
</p>
<p>
  
![departments](https://github.com/user-attachments/assets/89bb4ca9-e4af-4346-8788-4bbe172ac274)

</p>
<br />
<br />
<h3 align="center">Configure Teams</h3>
<br />
<p>
  Admin Panel -> Agents -> Teams.
</p>
<p>
Online Banking Team:
</p>
<p>
  
![teams](https://github.com/user-attachments/assets/02f7658d-5ebb-4bb6-bea7-70bf5f109913)

</p>
<br />
<br />
<h3 align="center">Configure Agents (workers)</h3>
<br />
<p>
  Admin Panel -> Agents -> Add New.
</p>
<p>
  Jane Doe in SysAdmins Department:
</p>

 ![jane](https://github.com/user-attachments/assets/01657816-b821-46be-b86a-de531c2cc306)
![jane sysadmin](https://github.com/user-attachments/assets/7fb89801-9666-4eb8-809e-4420f23eae5f)

<p>
  John Doe in Support Department:
</p>
<p>
  
  ![john](https://github.com/user-attachments/assets/98d00f57-ef9e-4a66-aaf9-1d683d4cf662)
![john support](https://github.com/user-attachments/assets/2a73cca9-c6b6-4cc8-b14e-853c4f0e5116)

  
</p>
<h3 align="center">Configure Users (customers)</h3>
<br />
<p>
  Admin Panel -> Users -> Add New.
</p>
<p>
  Ken User:
</p>

![ken](https://github.com/user-attachments/assets/25581d44-4cc5-4ff4-9241-91ac81db5859)

<p>
  Repeat the same above for Karen User.
</p>
<br />
<br />
<h3 align="center">Configure SLA</h3>
<br />
<p>
  Admin Panel -> Manage -> SLA.
</p>
<p>
  Sev-A (1 hour, 24/7).
</p>
<p>
  Sev-B (4 hours, 24/7).
</p>
<p>
  Sev-C (8 hours, business hours):
</p>
<p>
  
 ![Sev-a](https://github.com/user-attachments/assets/cf566c22-608b-46f3-8567-be089d89ca96)
![sev-b](https://github.com/user-attachments/assets/cb7f7917-fd76-4f7d-bef6-2d9d14539e37)
![sev-c](https://github.com/user-attachments/assets/d64097f0-aed0-4a93-8b8b-f6c0efad5cae)


</p>
<br />
<br />
<h3 align="center">Configure Help Topics</h3>
<br />
<p>
  Admin Panel -> Manage -> Help Topics.
</p>
<p>
  Business Critical Outage.
</p>
<p>
  Personal Computer Issues.
</p>
<p>
  Equipment Request.
</p>
<p>
  Password Reset.
</p>
<p>
  Other.
  </p>
<p>
  
  ![business crital outage](https://github.com/user-attachments/assets/93ee44c4-92d6-4359-b17d-9c7fa20c3a98)
![personal computer issues](https://github.com/user-attachments/assets/5d296760-a879-461d-8c86-910476729d21)
![equipment request](https://github.com/user-attachments/assets/9b6541ac-b9ad-4d11-9413-7d6136a16ba9)
![password reset](https://github.com/user-attachments/assets/00bdf71e-facc-4dcd-9537-7c554e39ef28)
![other](https://github.com/user-attachments/assets/c0d7f2b3-6cfc-44de-92af-eb078c3b3a33)

 
</p>
<br />
<br />
<p>
  This now fully configures our osTicket. I hope this guide was able to help clarify and assist you in setting up your osTicket. It is recommended to practice triaging and solving tickets.
</p>
<p>
  This is a very important skill to have for any help desk specialist, as they are the first line of communication between a company and it's customers when it comes to handling issues regarding a product or service they provide.
</p>
