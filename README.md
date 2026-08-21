**osTicket — Prerequisites & Installation Guide**

<p align="center">
  
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo" width="70%">
</p>

📌 **Overview**

This project demonstrates the full installation of the open‑source help desk ticketing system osTicket inside a Windows 10 Azure Virtual Machine. It includes all prerequisites, IIS configuration, MySQL setup, and final osTicket deployment.

🧩 **Environments & Technologies Used**

Microsoft Azure (Virtual Machines / Compute)

Remote Desktop Protocol (RDP)

Internet Information Services (IIS)

PHP Manager

MySQL Server

osTicket Installer

🖥️ **Operating System Used**

Windows 10 (21H2)

📋 **Prerequisites Installed**

PHP Manager

Microsoft Visual C++ Redistributable

IIS URL Rewrite Module 2

MySQL Server

osTicket Installer

🚀 **Installation Steps**

1. Install PHP Manager
<p align="center">
<img src="https://i.imgur.com/rQRKhA6.png" width="80%">
</p>

This is the first required component for osTicket. PHP Manager allows IIS to run PHP applications.

2. Install Microsoft Visual C++ Redistributable
<p align="center">
<img src="https://i.imgur.com/cQfUEYX.png" width="80%">
</p>

This package is required for several PHP extensions and ensures compatibility with IIS.

3. Install IIS URL Rewrite Module 2
<p align="center">
<img src="https://i.imgur.com/riZLPGS.png" width="80%">
</p>

This module enables URL rewriting, which osTicket uses for clean and functional routing.

4. Install MySQL Server
<p align="center">
<img src="https://i.imgur.com/fTYyFP8.png" width="80%">
</p>

MySQL stores all osTicket data, including tickets, users, departments, and system configuration.

5. Install osTicket
<p align="center">
<img src="https://i.imgur.com/sL8tHoR.png" width="80%">
</p>

This final step installs the osTicket application and prepares it for configuration inside IIS.

🎯 **Outcome**

By completing this installation, you successfully deployed a fully functional osTicket help desk system inside Azure. This demonstrates hands‑on experience with:

IIS configuration

PHP environment setup

MySQL database deployment

Application hosting

Azure VM administration

Help desk system installation
