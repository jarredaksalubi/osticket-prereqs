# osticket-prereqs<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>
This tutorial outlines the prerequisites and installation of the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How To Install osTicket with Prerequisites](https://www.youtube.com)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

- Create Virtual Machine in Azure
- Installation of files ( PHP Manager for ISS, Rewrite Module, PHP 7.3.8, VC_redist.x86.exe., MySQL5.5.62)
- Post Installation Setup 
- Ticket and Ticket Lifecycle


<h2>Installation Steps</h2>

<p>
<img src="https://i.imgur.com/JYC65OM.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p> Create a Resource Group and Virtual Machine (VM) with 2-4 Virtual CPUs. Name VM, create a user name and password for remote desktop access. 
<p>

</p>
<br />

<p>
<img src="https://i.imgur.com/bNwbgOb.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Install/Enable ISS in Windows with CGI, expand World Wide Web Srvices->Application Development Features->[X] CGI
</p>
<br />

<p>
<img src="https://i.imgur.com/aCTPLn0.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<img src="https://i.imgur.com/aiqJKrn.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
Download and install PHP Manager for ISS, Rewrite Module, PHP 7.3.8, VC_redist.x86.exe.and MySQL5.5.62. 
-Typical Setup ->
-Launch Configuration Wizard (after install) ->
-Standard Configuration ->
-Create Password

</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Open ISS as a admin, Register PHP from within ISS, Reload ISS (Open IIS, Stop and Start the server)
</p>
<br />
