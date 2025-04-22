<table>
  <tr>
    <td>
      <img width="1000" alt="ADS1" src="https://github.com/user-attachments/assets/6764e034-271e-4809-8e91-bb25dba7ba17" />
    </td>
    <td>
      <img width="1000" alt="ADS2" src="https://github.com/user-attachments/assets/2dfb8569-f306-4f94-a01a-6790869d3475" />
    </td>
  </tr>
</table>

<h1>Creating Active Directory Infastructure in the Cloud (Azure)</h1>
This tutorial outlines the creation of an Active Directory infastructure within Azure. We will use this build to deploy and configure Active Directory in a future project. <br />

<h2>List of Prerequisites</h2>

- [Creating Virtual Machines in the Cloud](https://github.com/joshuaheck1/VM-creation)
  (Reference this project for help creating Virtual Manchines if needed.)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Active Directory Domain Services
- PowerShell

<h2>Operating Systems Used </h2>

- MacOS
- Windows Server 2022
- Windows 10 (21H2)


<h2>Deployment and Configuration Steps</h2>

<p>
<img width="800" alt="AD7" src="https://github.com/user-attachments/assets/3324e347-dda1-4ace-bb71-5417daaa7673" />

</p>

<p>
- In Azure, create a new Resource Group and two Virtual Machines. Ensure the VMs are in the same Virtual Network and Location (Region). Reference the project above in Prerequisites if you need a quick reminder.
<p>- Name the first VM "DC-1" (Domain Controller), set the image to Windows Server 2022, and at least (2 vcpus, 8 GiB memory) for size.</p>
<p>- Name the second VM "Client-1", set the image to Windows 10, and at least (2 vcpus, 8 GiB memory) for size.</p>
<p>- This would be a good time to note the Public IP addresses of both VMs. We will need them later for RDP.</p>
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
