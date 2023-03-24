# SIEM-Tutorial-using-Sentinel
<p align="center">
<img src="https://i.imgur.com/pU5A58S.png" alt="Microsoft Active Directory Logo"/>
</p>

<h1>Using Azure Sentinel to monitor live attacks</h1>
This tutorial outlines the implementation of Azure Sentinel and the creation of a honeypot.<br />



<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines)
- Remote Desktop
- Azure Sentinel(SIEM)

<h2>Operating Systems Used </h2>

- Windows 10 (21H2)

<h2>Deployment and Configuration Steps</h2>

What we'll being doing is creating a virtual machine using Azure, which will act as our honeypot. Then we will use Sentinel to monitor and log attacks coming from all over the world trying to gain access to our vulnerable machine. So first, lets create our virtual machine that will be exposed to the internet.
<p>
<img src="https://imgur.com/2oBZlEv.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
</p>
<br />

Continue to "Networking" and scroll to "NIC network security group" and choose advanced. Click on "Create New". Remove the default inbound rule and then add a new inbound rule.  
<p>
<img src="https://imgur.com/2YE7ECP.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
Remove the default inbound rule. We will create a new inbound rule which will allow all traffic from the internet into the VM. This will make it easily discoverable. Create the VM and let's move on to the next step.
<p>
<img src="https://imgur.com/R5EZQlp.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />

Next, we're going to create a Log Analytics Workspace so that we can ingest logs from our VM. Then we're going to create our own custom log that contains geographic information. Logs will be stored here and our SIEM will connect to this workspace and then be able to display geodata on a map. So, naviagte to Log Analystics Workspace on Azure and create one.
<p>
<img src="https://imgur.com/a5wLtZJ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
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
