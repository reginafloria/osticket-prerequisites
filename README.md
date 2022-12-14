<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>
This tutorial outlines the prerequisites and installation of the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How To Install osTicket with Prerequisites](https://youtu.be/cUkEAbX7SIQ)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

- Connect to your Virtual Machine with Remote Desktop
- Install / Enable IIS in Windows
- Install Web Platform Installer
- Install osTicket v1.15.8
- Reload IIS (Open IIS, Stop and Start the server)
- Enable Extensions in IIS: Note that some extensions are not enabled
- Refresh the osTicket site in your browse, observe the changes
- Rename:
	From: C:\inetpub\wwwroot\osTicket\include\ost-sampleconfig.php
	To: C:\inetpub\wwwroot\osTicket\include\ost-config.php
- Assign Permissions: ost-config.php
- Continue Setting up osTicket in the browser (click Continue)
- Download and Install HeidiSQL
- Continue Setting up osticket in the browser
- MySQL Database: osTicket
- Click “Install Now!"
- Congratulations, hopefully it is installed with no errors
- Clean up
Delete: C:\inetpub\wwwroot\osTicket\setup
Set Permissions to “Read” only: C:\inetpub\wwwroot\osTicket\include\ost-config.php
- Login to the osTicket Admin Panel

<h2>Installation Steps</h2>

<p>
<img src="https://imgur.com/qGjslsX.jpg" height="80%" width="80%" alt="Created virtual machine for os-Ticketing system"/>
</p>
<p>
In Azure virtual machine was created for the os-Ticketing system.
</p>
<br />

<p>
<img src="https://imgur.com/pQs86Ab.jpg" height="80%" width="80%" alt="Connection to virtual machine through Remote Desktop App"/>
</p>
<p>
Connected to the virtual machine using the Remote Desktop App with the public IP address of the Azure virtual machine.
</p>
<br />

<p>
<img src="https://imgur.com/xSyXMhd.jpg" height="80%" width="80%" alt="Installed Internet Information Services"/>
</p>
<p>
Installed and enabled Internet Information Services within Windows 10.
</p>
<br />

<p>
<img src="https://imgur.com/m6EjwXL.jpg" height="80%" width="80%" alt="Installed Web Platform Installer and then opened app"/>
</p>
<p>
Installed Web Platform Installer and then opened app
</p>
<br />

<p>
<img src="https://imgur.com/eOo14Py.jpg*" height="80%" width="80%" alt="Installed MySQL and php files"/>
</p>
<p>
Installed my SQL and php files
</p>
<br />

<p>
<img src="https://imgur.com/CCvVIwF.jpg*" height="80%" width="80%" alt="Add screenshot description here"/>
</p>
<p>
Successful installation of the osTicket
</p>
<br />

<p>
<img src="https://imgur.com/QQCXKnq.jpg*" height="80%" width="80%" alt="Add screenshot description here"/>
</p>
<p>
Download and installation of HeidiSQL used to create a database
</p>
<br />

<p>

