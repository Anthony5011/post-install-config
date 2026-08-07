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

- Windows 11</b> (25H2)

<h2>Post-Install Configuration Objectives</h2>

- Configure Roles
- Configure Departments
- Configure Teams
- Configure Agents
- Configure Users
- Configure SLA
- Configure Help Topics

<h2>Configuration Steps</h2>

<p>
Now that we have osTicket configured, the next step is to configure new roles within the help desk. To do this you click Admin Panel > click Agents > click Roles > click add new role >  type in Supreme Admin > check off every box in the permissions tab. Keep in mind, roles is used to group permissions together and then you can assign that role to certain people. If you followed the steps correctly your screen should like something like this. As you can see we have successfully created the "Supreme Admin" role.
</p>
<p>
<img width="1916" height="832" alt="image" src="https://github.com/user-attachments/assets/eda856d7-b717-43a6-873e-88f458e2d60c" />
</p>
<br/>

<p>
Next is to configure the different departments that can get tickets assigned to them. You can configure departments in such a way that only the agents in those specific departments get to see their own tickets. To configure departments, click Admin Panel > click Agents > click Departments > click add new department. You will be creating the "SysAdmins department" which they will be given the ability to see all tickets. Type in SysAdmins for name then click Support for Parent. You don't have to worry about the other inputs and can just create the department.
</p>
<p>
<img width="1926" height="1538" alt="image" src="https://github.com/user-attachments/assets/15cba89e-f62b-455d-90b1-d2a27534ad82" />
</p>
<br/>

<p>
Next, you will configure teams. The purpose of teams is to pull agents from different departments. To do this, click Admin Panel > click Agents > click Teams > click add new team. Name the team "Online Banking" then leave everything else as is and then create the team.
</p>
<p>
<img width="1918" height="916" alt="image" src="https://github.com/user-attachments/assets/cd1dc07b-84f4-4428-83c3-9328e18adf9d" />
</p>
<br/>

<p>

</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />
