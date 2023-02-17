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
To continue where we left off, we are going to log back into osTicket as an admin. If you don't remember the address to login, here is the link to do so http://localhost/osTicket/scp/login.php. You must use the credentials you use to setup osTicket as admin.Once you are logged in click admin panel tab to get started with configuring. </p>
<br />

<p>
<img src=https://i.imgur.com/c5r61Q9.png height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Once you are in the admin panel, what we want to do next is click on agents-> roles-> now click on add a new role It can be named anything, but i will name mine Supreme Admin. Next we will add permissions as well.As a Supreme admin, we will be in total control. Now Click permissions, then check every box in tasks,tickets, and knowledgebase. Click save changes.
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
Next we will be adding agents. In the admin panel -> click agents -> then add new agents-> add a name for your agent and set password. Uncheck the two boxes that says (Send the agent a password reset email) and (Require password change at next login). Create a password and hit set. Furthermore, we want to give this agent access. click access at the top then add your agent to system administrators and the role could be supreme admin,also i will be adding jane to the level II support team. The choice is yours to decide which department and role he/she will be engaging into. You can repeat this process to add more agents. 
</p>
<br /v

<p>
<img src= https://i.imgur.com/0Jx7SHc.png height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Next we will be configuring users. For the first time we are going to click into to the agent panel, then tap users. From there you want to add users, add a name & email address. then click add user. You can add more users if you like. 
</P>
<br /v

<p>
<img src= https://i.imgur.com/IpNU1s6.png height="80%" width="80%" alt="Disk Sanitization Steps"/>  
</p>
<p>

Next we will be configuring SLA's. SLA stands for Service Level Agreements, which means the length of time to resolve the tickets. To add these set times we will be adding SLA plans. So next we are going to go back into admin panel -> tap manage -> then tap SLA -> add a new SLA. We will name it Sev-A with a grace period of 1 hour with it being scheduled 24/7. So if its in 24/7 it have to be done within 24/7 time span. Furthermore, we will create another SLA called SEV-B with a grace period of 4 hours and scheduled for 24/7 as well. Next we will be creating another SLA named SEV-C with a grace period of 8 hrs and a scheduled time with monday thru friday 8am-5pm with holidays.  
</p>
<br /v

<p>
<img src= https://i.imgur.com/cNlPYUn.png height="80%" width="80%" alt="Disk Sanitization Steps"/>  
</p>
<p>
Next we will be configuring Help topics. Help topics is a great way for end users to have a great experience with help with problems they have. First we are go into admin panel -> mangage -> then click help topics-> click add new. We are going to create 4 which are business critical outage, personal computer issues, password reset, equipment request.
