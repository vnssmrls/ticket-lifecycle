<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Ticket Lifecycle: Intake Through Resolution</h1>
This tutorial outlines the lifecycle of a ticket from intake to resolution within the open-source help desk ticketing system osTicket.<br />

- Admin/Analyst Login Page: <a href="http://localhost/osTicket/scp/login.php">http://localhost/osTicket/scp/login.php</a><br>
  
- End User Portal: <a href="http://localhost/osTicket">http://localhost/osTicket</a><br>

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop/ Windows App
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2> Ticket Lifecycle Stages</h2>

- Intake
- Assignment and Communication
- Working the Issue
- Resolution

<h2>Lifecycle Stages</h2>

<h3> Intake </h3>
<h4>Scenario: Entire Mobile/Online Banking System is Down</h4>
<p>
 End-user portal -> End User creates the ticket submission form describing the outage -> Submits the request for IT support </br>
</p>

<p>
<img src="https://i.imgur.com/OlUO20k.png" height="80%" width="80%" alt="Create a Ticket"/>
</p>

<h4> Assignment and Communication</h4>
<p>
Help Desk Agent (John) -> Agent Panel -> Reviews ticket properties: Priority, Department, SLA, Assigned To</br> -> Sets ticket properties:
<ul>
  - SLA: <b>Sev-A (1 hour, 24/7)</b><br> 
   - Department/Assigned To: <b>Online Banking/Jane</b><br>
   - Communicates with the end-user through internal notes and replies within the ticket</br>
</ul>
</p>

<p>
<img src="https://i.imgur.com/ZU0FMDH.png" height="80%" width="80%" alt="assg and comm"/>
</p>

<h4> Working the Issue</h4>
<p>
 Agent (Jane) begins diagnosing the outage and confirms the scope of impact -> Escalates to the SysAdmins department if further investigation is required -> Tracks all updates and progress within osTicket -> All actions and communications are automatically logged in the ticket thread
</p>

<p>
<img src="https://i.imgur.com/dKmuHtm.png" height="80%" width="80%" alt="Issue work"/>
</p>

<p>
<h4> Resolution</h4>
<p>
 Agent (Jane) verifies that the online banking system is restored -> Updates the ticket with detailed resolution notes -> Sets the ticket status to <b>Resolved</b> or <b>Closed</b> -> End-user receives an automated email confirming the issue has been resolved.
</p>
<br />

<p>
<img src="https://i.imgur.com/VKDJHum.png" height="80%" width="80%" alt="resolution"/>
</p>

<p>Each ticket follows a structured workflow from creation to resolution, ensuring timely handling and clear communication. Proper classification improves accountability, and centralized tracking allows for efficient reporting and performance analysis. EVERYTHING gets documented</p>
