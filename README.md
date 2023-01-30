<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket. More importantly, we are going to mainly configure roles as an admin. <br />



<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)



<h2>Configuration Steps</h2>

<p>
<img src=https://i.imgur.com/f4MVnF0.png height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
To continue where we left off, we are going to log back into osTicket as an admin. If you don't remember the address to login, here is the link to do so http://localhost/osTicket/scp/login.php. You must use whatever credentials you use to setup osTicket as admin.Once you are logged in click admin panel tab to get started with configuring. </p>
<br />

<p>
<img src=https://i.imgur.com/c5r61Q9.png height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
You should already be in the admin panel, once you are in the admin panel, what we want to do next is click on agents-> then roles-> now click on add a new role It can be named anything, but i will name mine Supreme Admin. Next we will add permissions as well.As a Supreme admin, one is in total control right. Now Click permissions, then check every box in tasks,tickets, and knowledgebase. Click save changes.
</p>
<br />

<p>
<img src= https://i.imgur.com/somaNko.png height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Next, we will configure departments in admin panel. click agents -> click departments -> add new department-> the name will be System Administrators. Then click create Department.
</p>
<br />

<p> 
<img src= https://i.imgur.com/SFAsu4x.png height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Next we will be creating a new team, click agents-> click teams-> name will be level II Support-> tap members and add yourself to the team if you would like to.
</p>
<br />

<p>
<img src= https://i.imgur.com/hzNdm0y.png height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
next we want to make sure anyone can create a ticket, admin panel -> settings -> then tap user settings. We want to make sure the box is unchecked for  require registration and login to create ticket.
</p>
<br /v

<p>
<img src= https://i.imgur.com/nixDmoH.png height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Next we will be adding agents. In the admin panel -> click agents -> then add new agents-> add a name for your agent and set password. Uncheck the two boxes that says (Send the agent a password reset email) and (Require password change at next login). Create a password and hit set. Furthermore, we want to give this agent access. click access at the top then add your agent to system administrators and the role could be supreme admin. The choice is yours to decide which department and role he/she will be engaging into. You can repeat this process to add more agents. 
</p>
<br /v

<p>
<img src  
