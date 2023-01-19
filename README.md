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
- Resolution

<h2>Lifecycle Stages</h2>

<p>
<img src="https://i.imgur.com/6ncLUqV.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/y4yFjYG.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
To begin this section of the lab you will need to open a new tab and go to http://localhost/osTicket/, and then click "open a new ticket". Next, you will need to fill out the contact information required for opening a ticket which includes an email address and a full name, then click "select a help topic", then select "Business Critical Outage", then in the Issue Summary box type "entire mobile banking is down" (example), then in the details box type "customers are reporting they are getting a 404 error when browsing to online banking" (example), and then click "create ticket". After that, click "open a new ticket", then fill out the contact information, then choose "personal computer issues" as your help topic, then type "entire accounting dept adobe reader not working" (example) in the issue summary box, then type "Ever since the upgrade last night, nobody in accounting has been able to use adobe reader" (example) in the details box, and then click "create ticket". After that, click "open a new ticket", then fill out the contact information once more, then select "General Inquiry" as your help topic, the type "when are we getting a hardware refresh" (example) in the issue summary box, then type "Most of my dept is having issues with their current tablets, we need this ASAP. Please provide info" (example) in the description box, and then click "create ticket". Now you have opened 3 support tickets. Examples above.
</p>
<br />

<p>
<img src="https://i.imgur.com/FuoepLk.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/ICqreZN.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Next, you will need to go back to http://localhost/osTicket/scp/login.php and login as one of the agents you created earlier in the lab. After that, you will need to click on the ticket with the "entire mobile banking is down" subject, then update the priority level from normal to emergency, then type "Business impacting event" in the description box and click "update". Next, assign this ticket to the agent that you logged in with, then click "assign". Next, update the SLA plan to "SEV-A", then write "Business impacting, critical incident" in the description box, and then click "update". Next, transfer the department from "Support" to "System Administrators", then type "Sys Admins responsible for mobile banking infrastructure" (example), and then click "transfer". Examples above.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />
