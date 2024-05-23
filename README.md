<h1>Active Directory Home Lab Setup</h1>

 ### [YouTube Demonstration](https://youtu.be/)

<h2>Description</h2>
<p>
This project outlines the setup of an Active Directory Home Lab, detailing steps from the initial download of necessary software to the creation and configuration of virtual machines within VirtualBox. It serves as a guide to setting up a domain controller, configuring network settings, and adding client machines to the domain.
</p>

<h2>Languages and Utilities Used</h2>
<ul>
<li><b>VirtualBox</b>: For virtualization and creating virtual machines.</li>
<li><b>PowerShell</b>: For scripting, including user creation scripts.</li>
</ul>

<h2>Environments Used</h2>
<ul>
<li><b>Windows 10</b> (Client Machines)</li>
<li><b>Server 2019</b> (Domain Controller)</li>
</ul>

<h2>Setup Walk-through:</h2>

<h3>Step 1: Download Required Software</h3>
<p align="center">
VirtualBox, Windows 10 ISO, Server 2019 ISO.<br/>
<img src="https://i.imgur.com/pLZQbfo.png" height="80%" width="80%" alt="Download Software"/>
<br/>
</p>

<h3>Step 2: Create the Domain Controller Virtual Machine</h3>
<p align="center">
Details on creating the VM in VirtualBox.<br/>
<img src="#STEP2_IMAGE_URL" height="80%" width="80%" alt="Create VM"/>
<br/>
</p>

<h3>Step 3: Network Configuration for VM</h3>
</p>

<h3>Step 4: Install Server 2019 on the VM</h3>
</p>

<h3>Step 5: Assign IP addressing for the internal network (the external network will automatically get IP addressing from the home network</h3>

<h3>Step 6: Name the server, install the active directory, and create our domain</h3>

<h3>Step 7: Configure domain and routing so the clients on the private network can reach the internet through the domain controller</h3>

<h3>Step 8: Set up a DHCP on the domain controller so that when we create our Windows 10 machine, it can automatically get an IP address</h3>

<h3>Step 9: The last thing on the domain controller, before creating our client virtual machine, is to run a PowerShell script that automatically creates a thousand users.</h3>

<h3>Step 10: After creating the users, we are going to create another virtual machine and install Windows 10 on it, and that virtual machine will be connected to the private virtual box network.</h3>

<h3>Step 11: We are going to name that machine client 1 and join it to the domain.</h3>

<h3>Step 12: We’re going to log it into one of our domain accounts.</h3>

<h2>Congratuations, Setup Complete!</h2>
<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
