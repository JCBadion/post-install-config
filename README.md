# Post-Install-Config
How to configure osTicket after installing
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

- Windows 10</b> (22H2)

<h2>Post-Install Configuration Objectives</h2>

- Configure Roles, Departments, Teams, Agents and Users
- Configure Service-Level Agreements (SLA)
- Configure Help Topics

<h2>Configuration Steps</h2>

<p>
<h4>osTicket Agent Portal</h4>
<img src="https://i.imgur.com/2OxqBON.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Once you login to osTicket for the first time, look at the upper right and click on the "Admin Panel". From there we will begin configuring the Ticketing system to be more usable.
</p>
<br />

<p>
<h4>osTicket Admin Panel</h4>
<img src="https://i.imgur.com/NnOXV5g.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Once inside the Admin Panel, click on the Agents tab. From the Agents Tab, you can view and create new Agents, new Roles, new Teams and new Departments. 
<br />

<p>
<h4>New Agent Page</h4>
<img src="https://i.imgur.com/IVSxzIB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
When making new agents, you can setup their name and an email for them to use while working within the system. You can also include their phone number and set a password for them to use, either as a one-time use or a permanent one. You can also change what type of permissions this person would have, which departments do they work for, and whose team they are working with. If an agent is accidentally locked out of their account due to too many password attempts, you can change or reset their password from the agent section, as well as unlock their account.
</p>
<br />  

<p>
<h4>Creating New Role</h4>
<img src="https://i.imgur.com/ei2fY4u.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<h4>New Role Permissions</h4>
<img src="https://i.imgur.com/T9xKDeV.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
When making new roles, you can adjust what they are allowed to do with tickets or their tasks. For example, the Supreme Admin would have full authorization of everything in the osTicket environment. They would be able to create tickets, close or delete tickets, assign other agents to a specific ticket, and even edit the tickets. Whereas a level I Support agent would probably only be able to respond to currently open tickets and close them, but would not be able to edit the tickets or delete them because it is outside of their scope of responsibilities.
</p>
<br />

<p>
<h4>Creating New Department</h4>
<img src="https://i.imgur.com/EneBV7y.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
When creating a new department in osTicket, you can change a lot of what a certain department is allowed to have access to. For the example department being made, System Administrators, a variety of options can be decided, for example:
  
  - "Are System Administrators allowed to receive tickets from the public, or are they internal affairs only?"
  - "When they receive a ticket, is their a specialized SLA (such as the need to respond faster due to urgency) they have to abide to, or is it the same as every other department?"
  - "Should their be an automatic response to people who send tickets to this department?"
  - "You can decide who is the manager of this department"
  
</p>
<br />
  
<p>
<h4>Creating New Team</h4>
<img src="https://i.imgur.com/oCJKvgt.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Making new teams is useful for organizing agents to work on a specific case or in specific departments, or even in special one-off projects and the team will consist of people from different departments. For this example, Level II Support is being created to handle tickets that Level I Support might not be qualified to handle or they don't have an answer to. Being in a team does not grant any special authorizations however. They are only there to build a proper structure of command. One department could only have one team, but another department might have many, with each team having more permissions or fewer permissions.
</p>
<br />

<p>
<h4>Creating New Users</h4>
<img src="https://i.imgur.com/x0dAPWt.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
To create a new user as an agent, from the admin panel look at the top right again and press the "Agent Panel" button to return to the agent's portal. Afterwards, press on the User section and from there you can create a new user or lookup an existing user's information. If a user is not registered within the osTicket system yet, you can add them to the directory with their name and email address attached. This would mean that this user is now within their system and when they create tickets their name and email will be used. Another way to look at users is as customers. When customers create an account with a company, this is effectively what they're doing; They are filling in their own information to be added into a company's user directory.
</p>
<br />

<p>
<h4>Service-Level Agreement Options</h4>
<img src="https://i.imgur.com/8gdF5rQ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
To get to Service-Level Agreements (SLA), click back to the Admin Panel, and under the Manage section, there is a subsection called "SLA" and click on that. For the example we'll use SEV-A (Severity-A). Tickets labeled as SEV-A mean that they need to be responded to within an hour after being created, and must be resolved ASAP. These tickets can occur at any time of the day or week, whether it is morning, night, or a holiday. Generally these tickets take the highest priority. Other types of SLAs include SEV-B and SEV-C. SEV-B means that the ticket is urgent and must be responded to generally within 4 hours after created, and must be addressed 24/7. And SEV-C tickets are generally less urgent tickets and can be addressed in about 8 hours, but only during business hours and holidays.
</p>
<br />

<p>
<h4>New Help Topics</h4>
<img src="https://i.imgur.com/n9IcRWd.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<h4>Ticket Setup Options</h4>
<img src="https://i.imgur.com/9uI00PZ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Under the Manage section again, at the far left of the subsections is the Help Topics section. Making new help topics can be useful for sending certain tickets to specific departments. For the example Personal Computer Issues, depending on what type of company this is, this ticket can be both an internal or external ticket, and can apply to both support agents and maintenance agents. You can change the parent topic of this inquiry, such as Reporting a problem/Access Issue. For Help Topics you can specify which departs will receive which ticket, depending on the ticket. You can also change how important a ticket is based on the agents authorized to receive it. A ticket could be sent directly to managers or system administrators due to its urgency.
  
  
  Once everything is set up you are ready to test out and try the newly-created osTicket System.
</p>
<br />


<h2>osTicket Part 3</h2>

  - ### [osTicket Ticket-Lifecycle](https://github.com/JCBadion/ticket-lifecycle)
