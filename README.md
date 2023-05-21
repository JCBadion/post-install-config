# post-install-config
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
<img src="https://i.imgur.com/2OxqBON.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Once you login to osTicket for the first time, look at the upper right and click on the "Admin Panel". From there we will begin configuring the Ticketing system to be more usable.
</p>
<br />

<p>
<img src="https://i.imgur.com/NnOXV5g.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Once inside the Admin Panel, click on the Agents tab. From the Agents Tab, you can view and create new Agents, new Roles, new Teams and new Departments. 
<br />

<p>
<img src="https://i.imgur.com/IVSxzIB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
When making new agents, you can setup their name and an email for them to use while working within the system. You can also include their phone number and set a password for them to use, either as a one-time use or a permanent one. You can also change what type of permissions this person would have, which departments do they work for, and whose team they are working with. If an agent is accidentally locked out of their account due to too many password attempts, you can change or reset their password from the agent section, as well as unlock their account.
</p>
<br />  

<p>
<img src="https://i.imgur.com/ei2fY4u.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/T9xKDeV.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
When making new roles, you can adjust what they are allowed to do with tickets or their tasks. For example, the Supreme Admin would have full authorization of everything in the osTicket environment. They would be able to create tickets, close or delete tickets, assign other agents to a specific ticket, and even edit the tickets. Whereas a level I Support agent would probably only be able to respond to currently open tickets and close them, but would not be able to edit the tickets or delete them because it is outside of their scope of responsibilities.
</p>
<br />

<p>
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
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />
  
<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />
