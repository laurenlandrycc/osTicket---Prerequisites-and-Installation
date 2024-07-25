
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

-Part 1 (Create Virtual Machine in Azure)
Create a Resource Group
Create a Windows 10 Virtual Machine (VM) with 2-4 Virtual CPUs


![image](https://github.com/laurenlandrycc/osTicket---Prerequisites-and-Installation/assets/174533836/97c2983b-df6b-4686-b6d8-fb4aa21f11e0)

![image](https://github.com/user-attachments/assets/62f1c414-76f7-46a7-b505-c85332e99f6d)

Create the directory C:\PHP
![image](https://github.com/user-attachments/assets/659982dc-b0ee-45a3-a429-669a991d572f)


From the Installation Files, download PHP 7.3.8 (php-7.3.8-nts-Win32-VC15-x86.zip) and unzip the contents into C:\PHP
From the Installation Files, download and install VC_redist.x86.exe.

From the Installation Files, download and install MySQL 5.5.62 (mysql-5.5.62-win32.msi)
![image](https://github.com/user-attachments/assets/77fe779d-52c8-41c9-b76d-122fc992b2fc)


Open IIS as an Admin

Register PHP from within IIS

Reload IIS (Open IIS, Stop and Start the server)

Install osTicket v1.15.8

Create a database called “osTicket”

Continue Setting up osticket in the browser






![image](https://github.com/laurenlandrycc/osTicket---Prerequisites-and-Installation/assets/174533836/504e854f-1ab5-46b9-b6d4-8f4692f09984)







