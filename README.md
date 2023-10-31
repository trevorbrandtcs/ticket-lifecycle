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
<img src="https://imgur.com/oJ437v4.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Picking up where we left off. We successfully configured the ticketing system in the last tutorial. This time we'll be staring off from the End User's POV. Navigate to the webpage in osTicket that allows you to submit tickets. Here's the URL, just in case: http://localhost/osTicket/open.php. 
</p>
<br />

<p>
<img src="https://imgur.com/fdxlL7o.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
All types of tickets can be submitted through here. Let's say that Ken notices that the mobile app for the business is down. Submit a ticket as Ken. I'm only submitting one for the purposes of this tutorial, but you can submit as many as you like and practice triaging and resolving issues. 
</p>
<br />

<p>
<img src="https://imgur.com/5DMhhX9.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Now navigate to log in as the admin account you created, and make sure that your agents have the proper permissions to view the ticket(s) we submitted. Log in as an agent that has the ability to see and work the ticket. Explore the ticket to see your different options as a Queue Manager. Take note that you can reassign, respond in an email, change SLA, etc. 
</p>
<br />

<p>
<img src="https://imgur.com/9kWyDyI.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
From this screen, we'll post a reply. Write a reply as if you're triaging. Notice that you can choose to keep the ticket open, resolve it, or close it.
</p>
<br />

<p>
<img src="https://imgur.com/DZT0WDf.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
From here, we can see that there is a thread that's developing. Now let's say the issue was solved so we want to close it. Post another reply, but this time select resolved. The ticket will automatically close and you can see it in the "Closed Tickets" section under "Today".
</p>
<br />

<p>
Go ahead and continue to play around with different tickets, using different scenarios.
</p>
<br />

<p>
That concludes the series of tutorials in osTicket. We have officially built a ticketing system from scratch, all the way from preinstallation configurations, all the way to being able to triage and solve issues within the system. I hope you enjoyed, and go ahead and check the rest of this GitHub for more!
</p>
<br />
