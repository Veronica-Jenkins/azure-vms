

<h1>Creating Virtual Machines</h1>
This tutorial outlines how to create Azure Virtual Machines.</br>
</br>
<h2>Environments & Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop

<h2>Operating Systems Used </h2>

- Windows 10 (22H2)
- Linux (Ubuntu Server)
</br>

<h2>Learning How to Create Virtual Machines</h2></br>

<p>
<img src="https://i.imgur.com/kr6ZAkY.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Create a resource group and select a region.
</p>
<br />
<p>
<img src="https://i.imgur.com/g8hTjnw.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Type <b><i>virtual machine</i></b> in the search bar. Select <b><i>create virtual machine</i></b>. Name the first virtual machne and select the region (*NOTE: Make sure the virtual machines are in the same region as the resource group that was created). From the dropdown menu select the following:
  
- <b>IMAGE:</b> Windows 10 Pro Version 22H2- 64-bit Gen 2
- <b>SIZE:</b> Standard_E2s_v3-2 vcps 16 GiB Memory</br>

Create a username and password (this will be needed in order to login remotely to the virtual machine).
</p>
<br />
<p>
<img src="https://i.imgur.com/RWsGm9i.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Go to --><b>Next:Disks</b> ---><b>Next:Networking</b> - Choose the already created virtual machine network then select <b><i>Review + Create</i></b>
</p>
<br />
<p>
<img src="https://i.imgur.com/FA3caNL.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
The virtual machine is created!
</p>
<br />
<p>
<img src="https://i.imgur.com/3pnhN4w.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
When creating the second virtual machine, follow the same steps used for the first machine. Since the second machine will be running on a Linux server, the image selection will be different (see below).
  
- <b>IMAGE:</b> Ubuntu Server 20.04 LTS-Gen 2
- <b>SIZE:</b> Standard_E2s_v3-2 vcps 16 GiB Memory</br>

Create a username and password for this new virtual machine as well.
</p>
<br />
<p>
<img src="https://i.imgur.com/m9YuEqL.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<p>
<img src="https://i.imgur.com/TgEYMrs.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<p>
<img src="https://i.imgur.com/avGz6fH.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
Now that both machines are created, we'll use the remote desktop (for Windows) to log into Virtual Machine 1 (VM1). Go to the bottom left hand corner of the screen and in the search bar type in <b><i>Remote Desktop Connection</i></b>. Copy the public IP Address for VM1 then paste it in


Click VM1 connect
Go to search bar at bottom of screen type in remote desktop connection.
Copy public IP address for vm1 then paste.

</p>
<br />






<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />
