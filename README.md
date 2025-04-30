<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post Configuration Setup</h1>
</p>
This tutorial demonstrates the post configuration setup of the osTicket system .<br />

<p>

</p>
</p>
<p>
Now that we have set up osTicket. Now, let’s do some basic system admin tasks.
First, we’ll create new roles for the help desk. Go to Admin Panel > Agents > Roles. We’ll create a Supreme Admin role.
Click "Add new role", type the name for the role, and set the permissions. For the Supreme Admin, give them all permissions. Roles control what agents can do, so not all agents will have full access.
If you followed the steps, you should see the "Supreme Admin" role created.
</p>
<img src="https://i.imgur.com/XHteqdt.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />
<p>
</p>
<p>
Click on the "Departments" button in the Agents tab. Here, you can create a new department. Each agent is assigned to a department based on their role in the help desk. For now, we’ll create the "System Administrators" department, where the Supreme Admins will be placed.
In the Departments tab, you can also set up things like SLAs, managers, and other email settings.
</p>
<br />
<p>
<img src="https://i.imgur.com/dGK0RVM.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
After setting up a new department, we’ll create a new team. Teams let you bring together agents from different departments. For example, you could create a team with top technicians from various departments to handle specific tasks. You might also create a help topic related to a product you offer and assign it to a team that specializes in that product.
To set up a team, go to Agents > Teams. A Level I Support Team is created by default. In this case, we’ll create a Level II Support Team.
</p>
<br />
<p>
<img src="https://i.imgur.com/cYzWBD2.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Now that we have set up a new team we will create a new setting that will allow anyone to create tickets. Admin Panel->Settings->User Settings.

</p>
<br />
<img src="https://i.imgur.com/H1q2Fdh.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Now, it’s time to create Agents. Agents are the employees who handle and resolve tickets in the help desk. Each agent is assigned to a primary department and given a primary role for tickets in that department.
Agents can also be given access to other departments and have different roles depending on where they are assigned. You can manage permissions, access, and teams in the Agents tab.
</p>
<br />
<img src="https://i.imgur.com/8WTOSre.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
After creating some agents we will create users. Users are customers that create tickets when they are having issues. A user is identified with their E-mail address. To create a user follow this path Agent Panel->Users->User Directory->Add new. 
</p>
<br />
<img src="https://i.imgur.com/xOprA9f.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
SLA Plans define how much time the help desk has to resolve a specific ticket. To create an SLA Plan, go to Admin Panel > Manage > SLA Plans. Each SLA plan includes a schedule, and within that schedule, there's a grace period.
Here the SEV-A plan has a 24/7 schedule and a one-hour grace period.
</p>
<br />
<img src="https://i.imgur.com/LpjCaLd.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Help topics help users categorize their tickets. In the example below we have made a help topic for "Business Critical Outage" this can be if customers cannot access mobile banking. 
</p>
<br />
<img src="https://i.imgur.com/kB7rts2.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
