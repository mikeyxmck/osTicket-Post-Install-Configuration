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
- Allow Users to create tickets
- Configure Agents (workers) & Users (customers)
- Configure SLA

<h2>Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/L0zqlLG.jpg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
  <img src="https://i.imgur.com/Tnlcokk.jpg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
1)  Once you have logged into your OsTicket, make sure you are inside of the Admin Panel. You will need to click on the 'Agent' tab then click on 'Role' and then 'Add New Role'

2) Then, you will want to create the Supreme Admin Role.
</p>
<br />

<p>
<img src="https://i.imgur.com/8voVU01.jpg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
3) Next, you will need to click on the 'Department' tab, located next to the 'Role' tab, and then click on 'Add New Department' then label that new department as 'System Administrators'

  <img src="https://i.imgur.com/gyUePIw.jpg" height="80%" width="80%" alt="Disk Sanitization Steps"/>

   <img src="https://i.imgur.com/gcpTTg5.jpg" height="80%" width="80%" alt="Disk Sanitization Steps"/>

4)  Once the System Administrator is created, you will need to click on the 'Teams' tab and then 'Add New Team'. We already have Level One Support created, but we will need to make a Level Two Support Team. This Team will handle the higher-tier tickets.
</p>
<br />

<p>
<img src="https://i.imgur.com/5wBGDyq.jpg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
  
  <img src="https://i.imgur.com/d9NEbRs.jpg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
5)  Next, you will need to click on the 'Settings' tab, then Users. the reason is that we are going to require clients/customers to have to be registered and have a login in order to create tickets. Once completed, we will go and create our 'Agents' that will be answering those tickets.

<img src="https://i.imgur.com/nXlFV5u.jpg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
  
  <img src="https://i.imgur.com/mqUuTga.jpg" height="80%" width="80%" alt="Disk Sanitization Steps"/>

  <img src="https://i.imgur.com/9QlMlhC.jpg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
  
  6)  Return back to the 'Agent' Tab and click on 'Add New Agent.' for the First/Last name, enter 'Jane Smith', and for the username, put 'Jane.Smith. ' This will be your Agent. For the password, make sure you click on 'Set Password' and unclick both squares requiring the agent to change their password. (NOTE: DO NOT DO THIS ON THE ACTUAL JOB.) 
</p>


<p>
<img src="https://i.imgur.com/kvCnRm3.jpg" height="80%" width="80%" alt="Disk Sanitization Steps"/>

  <img src="https://i.imgur.com/fKSAdIj.jpg" height="80%" width="80%" alt="Disk Sanitization Steps"/>

  <img src="https://i.imgur.com/zps9nIF.jpg" height="80%" width="80%" alt="Disk Sanitization Steps"/>

  <img src="https://i.imgur.com/jf9Pvtf.jpg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
  
</p>
<p>
7) Next, go and click on the 'Agent Panel' This is where you will create a 'User' account for the client/customer to use to actually create the tickets.  Go click on the 'User' tab, then 'Add New User.' The Username will be Karen.Johnson. It's a pretty similar process to creating the 'Agent', but after you put in the information, you will need to click 'Register' on the account. Upon doing so you will need to uncheck the box that would reset the password. (NOTE: ONCE AGAIN, DO NOT DO THIS ON THE ACTUAL JOB.)


<img src="https://i.imgur.com/53YeoCa.jpg" height="80%" width="80%" alt="Disk Sanitization Steps"/>

<img src="https://i.imgur.com/zA9DwJ1.jpg" height="80%" width="80%" alt="Disk Sanitization Steps"/>

<img src="https://i.imgur.com/irtil19.jpg" height="80%" width="80%" alt="Disk Sanitization Steps"/>

8) Finally, you will be creating the SLAs for the ticketing system; go back to the 'Admin Panel' and click the 'Manage tab, then 'SLA' in the drop-down, then click 'Add New SLA Plan'
9) You will create all three SLA plans:
     -Sev-A, which only has a 1-hour grace period and can happen 24/7
     -Sev-B, which has only a 4-hour grace period and can happen 24/7
     -Sev-C, which has an 8-hour grace period and can only happen during business hours.
   (NOTE: Change the grace period and schedule according to each Sev Level.)

   There you have it! You have successfully finished the post-installation of the OsTicketing System! creating Roles, Departments, all the way to even the SLA's!
</p>

<br />
