<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Ticket Lifecycle: Intake Through Resolution</h1>
This tutorial outlines the lifecycle of a ticket from intake to resolution within the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How to create, work, and resolves tickets within osTicket](https://www.youtube.com)

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
- Resolution

<h2>Lifecycle Stages</h2>

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Part 1: Admin Configuration and Ticket Creation (as End User)
Admin Panel Changes:

Change the SysAdmins Department to a Top Level Department.
Delete the Maintenance Department, not archive it.
Ticket Creation (as End User):

Create a ticket describing that the entire mobile/online banking system is down.
Assign the properties:
Priority: Sev-A (1 hour, 24/7).
Department: Online Banking Department.
Observe Ticket (as Help Desk Agent - john):

As the Help Desk Agent (john), observe the ticket properties:

Priority
Department
SLA
Assigned To
Set Ticket Properties to:

Priority: Sev-A (1 hour, 24/7).
Department: Online Banking Department.
Testing Ticket Access:

Try viewing the ticket again as john. Can changes be made?
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Part 2: Handling Additional Tickets and Working as Help Desk Agent
Create New Ticket (as End User):

Create a ticket that the accounting department needs an Adobe upgrade (broken).
Observe Ticket (as Help Desk Agent - john):

Observe the ticket’s properties:
Priority
Department
SLA
Assigned To
Set Ticket Properties (as Help Desk Agent - john):

Set:
Priority: Sev-B (4 hours, 24/7).
Department: Support.
Work the Ticket to Completion (as Help Desk Agent - john):

Resolve the ticket as john.
Create New Ticket (as End User):

Create a ticket regarding CFO’s laptop not turning on.
Observe Ticket (as Help Desk Agent - john):

Observe the properties and set the following:
Priority: Sev-B (4 hours, 24/7).
Department: Support.
Work the Ticket to Completion (as Help Desk Agent - john):

Resolve the ticket as john.

</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Part 3: Access Control and Final Ticket Observations
Set SEV-A Properties to All Tickets:

Change all tickets to Sev-A (SysAdmins last).
Observe ticket becomes inaccessible (indicating restricted access).
Admin Panel Adjustments:

Assign yourself View-access to SysAdmins in the admin panel.
Revisit the Ticket (as Help Desk Agent - john):

Go back to the escalated ticket in the agent panel and observe that you can no longer make changes to it.
Final Resolution:

Solve all tickets and ensure they are marked as resolved/completed.
</p>
<br />
