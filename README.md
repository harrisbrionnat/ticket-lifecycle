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

- Intake
- Assignment and Communication
- Working the Issue


<h2>Lifecycle Stages</h2>

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
1. Create a ticket as a User by logging  into this URL: http://localhost/osTicket
  <br>
2. Enter the user credentials created in the Post Installation repository (Bill Harris)
3. Provide the user's full name and email. 
4. Select a help topic and then click 
5. Provide a description of the problem.
6. Click 'Create Ticket'.
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
  1. Login as agent
Once an end user submits a ticket, the appropriate agent will be able to respond to that ticket. For our agent, Timmy Jones, to work the ticket from Peter Jones. He must login to his OsTicket account using this URL: http://localhost/osTicket/scp/login.php. Once he is logged in, he will be able to immediately see his open tickets, including the one from Peter Jones. When Timmy clicks on Peter's ticket he would be able to do things like, modify the priority level, transfer to a different department, change to SLA Plan or Due Date, etc. If Timmy wishes to post notes regarding the ticket that he does not want the end user to see, if can post it under the ta 'Internal Notes'. He can also provide additional notes to Timmy under the tab Post Reply.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
If the Peter's problem has been resolved, then on the ticket you can scroll down to 'Ticket Status' and select 'Resolved' from the drop down menu. If you would like to close the ticket without resolving the issue, you could just select 'Close'.
</p>
<br />
