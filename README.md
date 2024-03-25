<h1>Building a virtual network in Cisco Packet Tracer</h1>


<h2>Description</h2>
Building a simple network in Cisco Packet Tracer in the Logical Workspace by: deploying and connecting the network devices in a logical network, connecting devices to the router and verifying connectivity, setting up IP configuration, reviewing IP configuration in Command Line and also configuring a wirelesss laptop connection.
<br />


<h2>Languages and Utilities Used</h2>

- <b>Command Line</b> 
- <b>Cisco Packet Tracer</b> 

<h1>Program walk-through:</h1>



<h2 align="center">Adding devices to the workspace: </h2>
  
PC, Laptop and Cable Modem were added to the network using the Device-Type selection box

<img src="https://i.imgur.com/P7VeBS0.png" height="80%" width="80%" alt="Building a virtual network in Cisco Packet Tracer"/>


<h2 align="center">Add correct physical cabling to devices in the workspace:</h2>

Copper straight-through cable was used to connect the PC to the wireless router using the FastEthernet0 interface of the PC and the Ethernet 1 interface of the wireless router.

<img src="https://i.imgur.com/IhhKVii.png" height="80%" width="80%" alt="Building a virtual network in Cisco Packet Tracer"/>

<img src="https://i.imgur.com/rbAXliB.png" height="80%" width="80%" alt="Building a virtual network in Cisco Packet Tracer"/>


<h2 align="center">Change file permissions:</h2>

The organization does not allow others to have write access to any files. Using Linux commands I will identify the files which need permissions modified and use linux commands to modify them.

The file project_k.txt has granted other users permission to write files. 

<img src="https://i.imgur.com/kShlx4m.png" height="80%" width="80%" alt="Editing Linux Permissions steps"/>

In the chmod command u sets the permissions for the user who owns the file, g sets the permissions for the group that owns the file, and o sets the permissions for others.

The following command will modify the other user permissions to remove the permission to write files: chmod o-w project_k.txt.

This is the outcome of the permissions successfully modified: 

<img src="https://i.imgur.com/k3uxC4M.png" height="80%" width="80%" alt="Editing Linux Permissions steps"/>


<h2 align="center">Change file permissions on a hidden file:</h2>

The research team has archived .project_x.txt, which is why it’s a hidden file. This file should not have write permissions for anyone, but the user and group should be able to read the file. I know .project_x.txt is a hidden file because it starts with a full stop (.).


<img src="https://i.imgur.com/QGaV7AQ.png" height="80%" width="80%" alt="Editing Linux Permissions steps"/>

Currently the user and group can both write to the hidden file and the user is the only user type who can read the file.

The following command ensures to remove the write permissions for both the user and group and add the read permissions for the group:

<img src="https://i.imgur.com/6lagvDp.png" height="80%" width="80%" alt="Editing Linux Permissions steps"/>

This is the successful outcome:

<img src="https://i.imgur.com/M2ZcWJ5.png" height="80%" width="80%" alt="Editing Linux Permissions steps"/>


<h2 align="center">Change directory permissions:</h2>

The files and directories in the projects directory belong to the researcher2 user. Only researcher2 should be allowed to access the drafts directory and its contents. Use a Linux command to modify the permissions accordingly.

Currently group users have permissions to execute files in the drafts directory.

<img src="https://i.imgur.com/hGOWugA.png" height="80%" width="80%" alt="Editing Linux Permissions steps"/>

To remove the group permissions to remove the executable permissions for the group user this command is used:

<img src="https://i.imgur.com/Hgaw7OI.png" height="80%" width="80%" alt="Editing Linux Permissions steps"/>

This is the outcome:

<img src="https://i.imgur.com/UINsdDD.png" height="80%" width="80%" alt="Editing Linux Permissions steps"/>


<h2 align="center">Summary:</h2>


Linux commands were used to modify, remove & add permissions for the three user types: user, group and other as per the organizations requirements. Removing unauthorized access and adding authorized access ensures that the system can stay secure.


<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
