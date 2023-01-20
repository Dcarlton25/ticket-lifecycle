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
Next, you will need to go back to http://localhost/osTicket/scp/login.php and login as one of the agents you created earlier in the lab. After that, you will need to click on the ticket with the "entire mobile banking is down" subject, then update the priority level from normal to emergency, then type "Business impacting event" (example) in the description box and click "update". Next, assign this ticket to the agent that you logged in with, then click "assign". Next, update the SLA plan to "SEV-A", then write "Business impacting, critical incident" (example) in the description box, and then click "update". Next, transfer the department from "Support" to "System Administrators", then type "Sys Admins responsible for mobile banking infrastructure" (example), and then click "transfer". After that, scroll down and type "Coordinating with Sys Admin Team to bring mobile banking back online" (example) in the response box, and then click "post reply". After that, type "Jerry from System Engineering found and corrected a failed load balancer. Mobile banking should be back up" (example), then update the ticket status from open to closed, and then click "post reply". Now you have responded to and closed an open ticket. Examples above.
</p>
<br />

<p>
<img src="https://i.imgur.com/Ud4sFAw.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
After that, click on the ticket with the "entire accounting dept adobe reader not working" subject, then update the priority level from normal to high, and then click "update". Next, update the SLA plan to "SEV-B", and then click "update". Next, assign this ticket to one of the other agents you created earlier in this lab, and then click "assign". After that, scroll downn and type "Reassigned to SEV-B, reached out to John for a warm handoff" (example) in the reply box, and then click "post reply". Next, log out and switch to the agent that you assigned this ticket to, then click on the ticket, then scroll down and type "Rolled back version of Adobe Reader to previous version allowing them to work. In the meantime, I will research why the new version doesn't work on accounting department's hardware" (example), and then update the ticket status from open to resolved, and then click "post reply". Now you have resolved the second ticket. Examples above.
</p>
<br />

<p>
<img src="https://i.imgur.com/DWlqlXK.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Next, check the ticket with the "osticket installed" subject, and then click "delete". After that, click on the ticket with the "when are we getting a hardware refresh" subject, and then update it's priority level from normal to low, and then click "update". Next, you will need to assign this ticket to the agent that you are logged in as, then update the SLA plan to "SEV-C", and then click "update". After that, scroll down and type "Hardware refresh is slated for Q1, if you like, you and your dept can start testing the new units today. Just shoot me an email." (example) in the reply box, and then update the ticket status to "resolved", and click "post reply". Now you have responded to and closed all the tickets and that is the end of the lab. Examples above.
</p>
<br />
