<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Computer)
- Remote Desktop
- osTicket

<h2>Operating Systems Used </h2>

- Windows 11 Pro </b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

- Setting up ticketing system by configuring Roles, Departments, Teams, Agents, Users, SLA, and Help Topics

<h2>Post-Install Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/zezcGwY.jpeg"/>
</p>
<p>
To begin, log into osTicket as an admin user using the credentials that were set in the previous lab
</p>
<br />

<p>
<img src="https://i.imgur.com/tN4D175.png"/>  <img src="https://i.imgur.com/quSraah.png"/>
</p>
<p>
 - Once logged in begin to configure Roles: Click the "Admin Panel" on the top right corner > Select "Agents" tab
<p> - Add new role > in the Definition tab type the name: Supreme Admin
<p> - Permissions tab > check box everything in Tickets, Task, and Knowledge base section for full permissions then add role
<p>
  
<img src="https://i.imgur.com/dcYHWPF.png"/>
- Next begin to configure Departments: Select Departments in Agents tab > Add new > Parent: Top Level Department > Name: SysAdmins > Create Dept
</p>
<p>
</p>
<br />

<p>
<img src="https://i.imgur.com/pGWpqA7.png"/>
</p>
<p>
- Next configure Teams: Select Teams in Agents tab > Add new > Name: Online Banking > Create Team 
</p>
<br />

<p>
<img src="https://i.imgur.com/VZ6zsF3.png"/>
</p>
<p>
- In the Settings tab allow anyone to create tickets: Users > Make sure Require Registration is unchecked
</p>
<br />

<p>
<img src="https://i.imgur.com/BhfpM74.png"/> <img src="https://i.imgur.com/R2okXqC.png"/> <img src="https://i.imgur.com/Rc5pxxj.png"/> <img src="https://i.imgur.com/27wF3Jb.png"/> 
<p>
- Create Agents (workers): Proceed back to Agents tab > Add New > Create Jane Doe Agent 
<p> - Setting Password: Click Set Password > Uncheck "Send the agent a password reset email" > Come up with a password > Uncheck "Require password change at next login" > Set 
<p> - In Access Tab > Assign Jane SysAdmins in Department > Assign Jane Supreme Admin Role
<p> - In Teams Tab > Assign Jane to Online Banking > Create
</p>
<br />

<p>
<img src="https://i.imgur.com/5hFctLX.png"/> <img src="https://i.imgur.com/8SsPMyp.png"/>
</p>
<p>
- Then create another agent named John Doe 
<p> - Access Tab: Assign to Support Department > Assign Role to View Only > Create
<p> - Make sure to set password like we did for Jane Doe
</p>
<br />

<p>
<img src=""/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<p>
<img src=""/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<p>
<img src=""/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<p>
<img src=""/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<p>
<img src=""/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />
