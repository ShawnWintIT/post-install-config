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
