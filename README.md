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

- Have your Azure tenant created (Organization)
- An active Azure subscription
- Create resource group
- Create a Windows 10 vitrual machine inside of resource group
- Remote desktop connection into created virtual machine
- Download <a href="https://drive.google.com/drive/u/1/folders/1APMfNyfNzcxZC6EzdaNfdZsUwxWYChf6">required installation files</a> for osTicket inside the virtual machine

<h2>Installation Steps</h2>

<p>
<img src="https://i.imgur.com/Xrrlwmi.png" height="80%" width="80%" alt="Install and Enable IIS in Windows"/>
<p>
Install and enable IIS in Windows with CGI and Common HTTP Features:
  For CGI:
  Open Control Panel => Click Programs => Turn Windows Features on or off => Internet Information Services =>
  World Wide Web Services => Application Development Features => Check the CGI box.
  For Common HTTP Features:
  The box is located inside of that World Wide Web Services folder below Application Development Features, just click that Common HTTP Features box.
</p>
<br />

<p>
<img src="https://i.imgur.com/CljBXBi.png" height="80%" width="80%" alt="IIS enabled"/>
</p>
<p>
To confirm wether or not you completed the enabling of IIS and Common HTTP Features:
  Open a web browser and type in 127.0.0.1 into the search bar, if the "Internet Information Services" webpage appears then you have completed the installation.
</p>
<br />

<p>
<img src="https://i.imgur.com/NccA6Zq.jpeg" height="80%" width="80%" alt="Installing PHP Manager for IIS"/>
</p>
<p>
Next you want to install the PHP Manager for IIS executable from the required installation files by executing the PGPManagerForIIS_V1.5.0.msi file. Once installed close the installer.
</p>
<br />

<p>
<img src="https://i.imgur.com/kYNENOs.jpeg" height="80%" width="80%" alt="Rewrite Installation"/>
</p>
<p>
After the PHP Manager for IIS install, the next executable to install will be the "rewrite_amd64_en-US.msi" file that is located in the required installations files.
</p>
<br />

<p>
<img src="https://i.imgur.com/WErvorO.jpeg" height="80%" width="80%" alt="PHP folder"/>
</p>
<p>
Next step is to create the directory C:\PHP:
  Open File explorer => This PC => Windows (C:) => Right Click and make a folder named PHP
</p>
<br />

<p>
<img src="https://i.imgur.com/bFmkPWi.jpeg" height="80%" width="80%" alt="PHP EXTRACTION"/>
</p>
<p>
For the next step we are going to take the "php-7.3.8-nts-Win32-VC15-x86.zip" file and extract that into the newly created PHP folder.
</p>
<br />

<p>
<img src="https://i.imgur.com/HUsQnmB.jpeg" height="80%" width="80%" alt="VCredistx86"/>
</p>
<p>
After extracting the files, execute the VC_redist.x86 file and complete the installation.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>

</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

