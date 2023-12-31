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

- Create example tickets as Admin.
- Create example Roles
- Create example Departments
- Create example Teams
- Create example SLA

<h2>Configuration Steps</h2>

<h2>Configure Roles</h2>

<p>
<img src="https://i.imgur.com/AjljBTH.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p> 
Select the Agent tab and then select Roles. Here, you are able to grant roles permission per dept. Roles are the permissions granted to Agents. Different departments have different permission granted to them. 
</p>
<br />

<p>
<img src="https://i.imgur.com/5QZyBXU.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Click "add New Role" 
</p>
<br />

<p>
<img src="https://i.imgur.com/LG5Ypaf.png)" height="60%" width="60%" alt="Disk Sanitization Steps"/>
</p>
<p>
Add the name Supreme Admin.
</p>
<br />

<p>
<img src="https://i.imgur.com/xXjhdNZ.png" height="50%" width="50%" alt="Disk Sanitization Steps"/>
</p>
<p>
Click and set permissions then press add.
</p>
<br />

<h2>Configure Departments</h2>

<p>
<img src="https://i.imgur.com/CkdoXDa.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>Click Agents and then Departments.
</p>
<br />

<p>
<img src="https://i.imgur.com/IHLP8Nw.png)" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Next, click add New Department.
</p>
<br />

<p>
<img src="https://i.imgur.com/NjSIFXO.png" height="60%" width="60%" alt="Disk Sanitization Steps"/>
</p>
<p>
Next , In the name section put System Administrators. Here you can input status, type, SLA, etc.
</p>
<br />

<h2>Configure Teams</h2>


<p>
<img src="https://i.imgur.com/W81WtJ5.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Under Agents, click teams and then "add a new team"
</p>
<br />

<h2>Configure Agents(workers)</h2>

<p>
<img src="https://i.imgur.com/a8hwexL.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Under the Admin panel-> Users-> and click "add new Agent"  
</p>
<br />

<p>
<img src="https://i.imgur.com/kw06Ll0.png" height="60%" width="60%" alt="Disk Sanitization Steps"/>
</p>
<p>
You can then assign Agents to different roles, what access they, permissions, and what team you want them on.
</p>

<h2>Configure Users (customers)</h2>

<p>
<img src="https://i.imgur.com/RJpTXcp.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
You must switch to the "Agent Pane l"-> Users-> then Click the user tab and then click "add User".
</p>
<br />


<p>
<img src="https://i.imgur.com/vEeNkHO.png" height="60%" width="60%" alt="Disk Sanitization Steps"/>
</p>
<p>
You can lookup current customers or create a new customer.
</p>
<br />

<h2>Configure SLA</h2>

<p>
<img src="https://i.imgur.com/dxeXBK3.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Select Manage tab-> SLA-> 
</p>
<br />

<p>
<img src="https://i.imgur.com/oI4dA9Z.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Click "Add New SLA Plan". Add name, status, grace period, schedule and any important notes.
</p>
<br />

All Done!

