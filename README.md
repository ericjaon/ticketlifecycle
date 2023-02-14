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

- Windows 10</b> (21H2)

<h2>Ticket Lifecycle Stages</h2>

- New
- Open
- Pending 
- On-Hold 
- Solved 
- Closed 

<h2>Lifecycle Stages</h2>

<p>
<img src="https://i.imgur.com/zBwINES.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
  
  New: An agent has not taken the ticket yet. Once the agent updates the ticket from New to Open, it cannot be moved back to New.
  
 Open: The ticket is assigned to an agent who is working to solve it.
  
Pending: The agent needs additional information from the requester or customer to continue solving the ticket. 
</p>
<br />

<p>
<img src="https://i.imgur.com/oDXgDyY.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
On-Hold: The agent is awaiting additional information or a resolution from a third party. This is an optional status that your admin enables.
  
Solved: The issue is solved. A solved ticket is reopened (if necessary) when the requester replies.
  
Closed: The ticket is closed by the system and cannot be reopened. A closed ticket is view only and not edited in any way. As a general rule, tickets are closed after four days of being in the solved status with no response. Your admin may adjust this timeframe. .
</p>
<br />


