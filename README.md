<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>
This tutorial outlines the prerequisites and installation of the open-source help desk ticketing system osTicket.<br />


<h2>Full Video Demonstration</h2>

- ### [How To Install osTicket with Prerequisites](https://www.flexclip.com/share/1836597584816606a89ee81934fc14d2e28131d.html)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

- Install/Enable IIS
- Install Web Platform Installer and download mySQL 5.5 and appropriate php files up to 7.3 (x86)
- Download osTicket zip files
- Download HeidiSQL

<h2>Abbreviated Installation Steps</h2>

<p>
 <img src="https://user-images.githubusercontent.com/47663923/209570627-6a50ce8e-dd73-46eb-a5a5-2f3a127ea318.png" height="80%" width="80%" alt="Web Platform Installing"/>
</p>
<p>
Choose the PHP files up to 7.3 (x86) and mySQL 5.5 in Web Platform Installer, download and install them, and reinstall anything that fails.
</p>
<br />

<p>
<img src="https://user-images.githubusercontent.com/47663923/209570787-2415b246-4b83-4158-86f5-63c72d09d2bf.png" height="80%" width="80%" alt="Enabling PHP files"/>
</p>
<p>
Open IIS, navigate to PHP manager, and enable php_imap, php_intl and php_opache.
</p>
<br />

<p>

<img src="https://user-images.githubusercontent.com/47663923/209571252-09a6fb7e-7952-4b5a-9c9d-71a51dd08b97.png" height="80%" width="80%" alt="HeidiSQL"/>
</p>
<p>
Download HeidiSQL and create a new database called osTicket.
</p>
<br />


<img src="https://user-images.githubusercontent.com/47663923/209571363-7ce685b8-cb3f-45ed-a0fc-ca4da1f3bedb.png" height="80%" width="80%" alt="HeidiSQL"/>
</p>
<p>
Open osTicket install page via IIS, mysites, and clicking Browse *:80 (http). Go through set up phase and press Install now.
</p>
<br />
