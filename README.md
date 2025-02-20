<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Ticket Lifecycle: Intake Through Resolution</h1>
This tutorial outlines the lifecycle of a ticket from intake to resolution within the open-source help desk ticketing system osTicket.<br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10 Pro </b> 

<h2>Ticket Lifecycle Stages</h2>

- Intake
- Assignment and Communication
- Working the Issue
- Resolution

<h2>Creating A Ticket</h2>

- We will be creating a ticket as an end user
- Go to the End Users osTicket URL: </b>
http://localhost/osTicket
- Click on Create a New Ticket
- Open a new ticket under User Karen created in the previous lab
- Fill out the ticket information

<img src="https://i.imgur.com/BnpLu9Y.png" height="80%" width="80%" alt=""/>

<img src="https://i.imgur.com/q1vKEh6.png" height="80%" width="80%" alt=""/>


<h2>Intake</h2>

- Go to the Admin/Analyst Login Page: </b>
http://localhost/osTicket/scp/login.php
-Login as John Doe

<img src="https://i.imgur.com/Uj7ci37.png" width="80%" alt=""/>

Select the ticket created earlier

<img src="https://i.imgur.com/d8aYg4H.png" width="80%" alt=""/>

- Since John's permissions are set to View Only, this Agent can only view the ticket but cannot change anything about it.

 <img src="https://i.imgur.com/nEirE5C.png" width="80%" alt=""/>

- To be able to complete the ticket, we can complete the ticket as Jane Doe or give John permission to access the ticket. In this case I'll be giving John Doe an All Access Role to change some things about the ticket.

<img src="https://i.imgur.com/7yJcpUB.png" width="80%" alt=""/>

<h2>Assignment and Communication</h2>

- Now that John has access to make changes to the ticket, we can start making changes to it

<img src="https://i.imgur.com/wkpTdNk.png" width="80%" alt=""/>

- Ticket Priority:
  - Since the ticket is about the online banking system being down it affects a lot of people so it is considered a High priority so that an agent can get to it as soon as possible

<img src="https://i.imgur.com/NZ1WLMe.png" width="80%" alt=""/>

- SLA Plan
  - Sev-A which means it has to be resolved within an hour.

<img src="https://i.imgur.com/hPYSlG7.png" width="80%" alt=""/>

- Help Topic
 - Update the help topic to one that matches the ticket best, in this case it falls under Report a Problem/Business Critial Outage

<img src="https://i.imgur.com/F9gfkmV.png" width="80%" alt=""/>

- Assigned To
- A ticket can be assigned to a Team or an individual, in this case the ticket has been assigned to Jane Doe

<img src="https://i.imgur.com/VlydUVf.png" width="80%" alt=""/>

<h2>Working the Issue</h2>

- Signin as Jane Doe

<img src="https://i.imgur.com/kVF99CT.png" width="80%" alt=""/>

- Select the ticket

<img src="https://i.imgur.com/R1WqGRo.png" width="80%" alt=""/>

- Solve the ticket
   - It is important to keep the user and other agents updated on the issue, when an agent writes something it is also sent to the user. Communication is key when handling tickets. 

<img src="https://i.imgur.com/i0Iw5mN.png" width="80%" alt=""/>

<h2>Resolution</h2>

- Once the issue has been fixed, the ticket can be resolved.

<img src="https://i.imgur.com/iyy5VUt.png" width="80%" alt=""/>

<img src="https://i.imgur.com/gUG3qF7.png" width="80%" alt=""/>






