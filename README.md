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
You will now allow anyone to create tickets. To do this, click Admin Panel > click Settings > click users > then uncheck "require registrations and login to create tickets".
</p>
<p>
<img width="1912" height="1218" alt="image" src="https://github.com/user-attachments/assets/31fdbae4-da56-4247-b46e-a6de0086a6e2" />
</p>
<br/>

<p>
Now you will configure agents (workers). This is important because whenever someone gets hired as a help desk agent, a new agent account has to be created for them. The agents will be the ones who are troubleshooting and resolving tickets. To do this, click Admin Panel > click Agents > Click Add New Agent. You will create Jane who will be in the SysAdmin department, who will have a Supreme Admin role, and who will be a part of the Online Banking team.
</p>
<p>
<img width="1914" height="1092" alt="image" src="https://github.com/user-attachments/assets/c5d1de37-d287-46ae-9a5a-a9c490602cdf" />
</p>
<br/>

<p>
After creating the agents, next you will create end users who may create a ticket. To do this, click Agent Panel > click User > Click Add User.
</p>
<p>
<img width="1910" height="658" alt="image" src="https://github.com/user-attachments/assets/0f980666-7d1b-4942-9090-8d31f910dd80" />
</p>
<br/>

<p>
Now you will configure an SLA. An SLA is an agreement that dictates how much time you have to complete a specific task. To do this, click Admin Panel > click Manage > click SLA > click add new SLA plan. You will configure three SLAs that have a severity of A, B, and C (going from most to least severe). This is how Sev-A looks.
</p>
<p>
<img width="1912" height="1056" alt="image" src="https://github.com/user-attachments/assets/4bec5d59-60b8-4246-81cf-57b7e274c382" />
</p>
<br/>

<p>
Lastly, you will configure Help Topics. When a user creates a ticket, they choose the category that the ticket relates to. To do this, click Admin Panel > click Manage > click Help Topics.
</p>
<p>
<img width="1918" height="1000" alt="image" src="https://github.com/user-attachments/assets/bdaacf96-1537-407b-a2a2-928d77f1d296" />
</p>
<br/>

<h2>Summary</h2>
<p>
Created some roles, departments, a team, a few users who are actually using the platform (Jane & David). Created an end user who is working in some department that might make a ticket in the future. Created our SLAs which will be used when creating, working, assigning, and configuring tickets. Created help topics which will help the end user categorize the tickets when they’re creating them for the analysts
</p>
