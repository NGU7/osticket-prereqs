<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>
This tutorial outlines the prerequisites and installation of the open-source help desk ticketing system osTicket.<br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

- Enable IIS (Internet Information Services) on the PC, allowing us to host a web server
- Install mySQL and PHP
- Register PHP to the IIS Web server
- Upload the osTicket Code into the Web Server
- Enable PHP Manager Extensions to allow osTicket to run
- Install Heidi to allow us to create a database specifically for osTicket (End of Prereqs)
- Create an admin account 
- Access osTicket

<h2>Actions and Observations</h2>

<p>
  <img width="1440" alt="osTicket Preinstall Checklist" src="https://github.com/user-attachments/assets/71fd7e3d-9470-402b-a7b9-75dbad07e469" />
</p>
<p>
  Before using osTicket, an installation process is required before it is an accessible web server. OsTicket Requires a web server to be installed and configured. It also requires you to download PHP, MySQL, and Heidi to construct a backend database for the Web Server.
</p>
<br />

<p>
<img width="1440" alt="Screen Shot 2025-01-22 at 5 59 48 PM" src="https://github.com/user-attachments/assets/06e4fb4e-8616-42f1-9885-ea815c8e0626" />

</p>
<p>
Once the prerequisites are complete the web server will display green checkmarks allowing you to continue into the ticketing system. From here we create the name of our help desk and our admin overseer to manage our ticketing system. On the right is the IIS allowing us to change out PHP settings to align with osTicket.
</p>
<br />

<p>
  <img width="1440" alt="Successful OsTicket Login" src="https://github.com/user-attachments/assets/fb37f7e7-64ec-410a-9897-cf01729d7992" />
</p>
<p>
  After a successful installation and login, the first panel you access is the ticketing panel where all end-user and agents' current tickets will be displayed.
</p>
<br />
