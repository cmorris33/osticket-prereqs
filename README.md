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

- MAC OS </b> 
- Windows 10 (21H2)

<h2>List of Prerequisites</h2>

- Enable IIS with CGI an Common HTTP Features
- Install PHP Manager for IIS 
- Install Rewrite Module 
- Install and download MYSQL
- Install osTisket

<h2>Installation Steps</h2>

<p>
<img src="https://i.imgur.com/WtOn77T.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
To enable Internet Information Services (IIS) on your computer for web browsing and application development, follow these steps. Right-click on the start menu and select "Run." In the Run dialog box, type "control panel" and press "OK" to open the Control Panel. From there, click on "Programs" and then choose "Turn Windows features on and off." This action will bring up a list of features. Look for "Internet Information Services" and expand the folder. Within the expanded folder, find "World Wide Web Services" and expand it further. Inside, locate the "Application Development Features" folder and click on "CGI." After that, collapse the Application Development folder and navigate to "Common HTTP Features." Ensure that all the checkboxes under Common HTTP Features are selected, and then click "OK" to save the changes. The installation process for the chosen features will begin, configuring IIS for web server functionality and facilitating website searching on your computer.
</p>
<br />

<p>
<img src="https://i.imgur.com/EzdtzX9.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Download the PHP Manager for IIS installation package from the official Microsoft website. Once downloaded, run the installer to initiate the setup process. Follow the on-screen instructions and select the desired installation options. After the installation is complete, open the IIS Manager on your computer. Within the IIS Manager, locate the server node and double-click on it. In the server node, find the "PHP Manager" icon and double-click on it to open the PHP Manager interface. From there, you can configure PHP settings, view PHP information, and manage PHP extensions. The installation of PHP Manager for IIS allows for efficient management of PHP configurations and enhances the functionality of PHP applications on the IIS web server.
</p>
<br />

<p>
<img src="https://i.imgur.com/hCe9k1g.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
To install the Rewrite Module, open the IIS Manager on your computer. Then, find the "Modules" option and click on it. Next, choose "Add Managed Module" and give the module a name, like "Rewrite Module." Finally, save the changes. Now, the Rewrite Module is installed and you can use it to easily change and control website URLs on your IIS server. Next, we can now create the directory for C:\PHP
</p>
<br />

<p>
<img src="https://i.imgur.com/YbnAweS.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Next, we would download MySQL. To download MySQL go to the official MySQL website. Look for the "Downloads" section and click on it. On the downloads page, you'll see different versions of MySQL. Choose the version that suits your needs, like "MySQL Community Edition." Click on the download button for your operating system, such as Windows or Mac. The download should start automatically. Once the download is complete, open the downloaded file and follow the installation instructions. After the installation is finished, you will have MySQL successfully downloaded on your computer, ready to use for managing databases. Then we would open IIS as an Admin and register PHP from within IIS. 
</p>
<br />

<p>
<img src="https://i.imgur.com/kkVXBof.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Finally,to downlaod and install osTicket download from either website or installation file folder. Extract and copy "upload" folder to C\inetpub\wwwroot. Within C:\inetpub\wwwroot, Rename "Upload" to "osTicket". Reload IIS then finish download the rest of the extensions that were not enabled. 
</p>
<br />
