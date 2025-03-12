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

A copper straight-through cable was used from the Device-Type selection box to connect the PC to the wireless router using the FastEthernet0 interface of the PC and the Ethernet 1 interface of the wireless router.

<img src="https://i.imgur.com/IhhKVii.png" height="80%" width="80%" alt="Building a virtual network in Cisco Packet Tracer"/>

<img src="https://i.imgur.com/Pg5JqCH.png" height="80%" width="80%" alt="Building a virtual network in Cisco Packet Tracer"/>

A copper straight-through cable was used from the Device-Type selection box to connect the wireless router to the cable modem using the internet interface of the wireless router and the Port 1 interface of the cable modem.

<img src="https://i.imgur.com/VgwCO3c.png" height="80%" width="80%" alt="Building a virtual network in Cisco Packet Tracer"/>

<img src="https://i.imgur.com/ehCSCXH.png" height="80%" width="80%" alt="Building a virtual network in Cisco Packet Tracer"/>

A coaxial cable was used from the Device-Type selection and attached to the Port 0 interface of the cable modem and the coaxial 7 interface of the internet cloud.

<img src="https://i.imgur.com/2nkctrL.png" height="80%" width="80%" alt="Building a virtual network in Cisco Packet Tracer"/>

<img src="https://i.imgur.com/2nkctrL.png" height="80%" width="80%" alt="Building a virtual network in Cisco Packet Tracer"/>

<h2 align="center">Configure the End Devices and Verify Connectivity:</h2>

Double clicking the PC allows us to navigate to the Desktop tab and then to the IP Configuration.

<img src="https://i.imgur.com/7cESyrc.png" height="80%" width="80%" alt="Building a virtual network in Cisco Packet Tracer"/>

Selecting DHCP for the IP Configuration heading will allow the PC to receive an IP address from the DHCP.

<img src="https://i.imgur.com/EYZAxa9.png" height="80%" width="80%" alt="Building a virtual network in Cisco Packet Tracer"/>

<img src="https://i.imgur.com/EYZAxa9.png" height="80%" width="80%" alt="Building a virtual network in Cisco Packet Tracer"/>

Navigate to command line within the PC and enter the "ipconfig /all" prompt to verify the PC received an IPv4 address in the 192.168.0.x range.

<img src="https://i.imgur.com/iRrVV1X.png" height="80%" width="80%" alt="Building a virtual network in Cisco Packet Tracer"/>


<h2 align="center">Configure the Laptop:</h2>

Double clicking the laptop will allow you to select the physical tab.

<img src="https://i.imgur.com/Kp46rci.png" height="80%" width="80%" alt="Building a virtual network in Cisco Packet Tracer"/>

Power off the laptop by pressing the power off button. Remove the currently installed Ethernet copper module by clicking on the module on the side of the laptop and dragging it to the modules pane on the left. 
Install WPC300N module by clicking it in the modules pane and dragging it to the empty module on the laptop. Power on laptop.

<img src="https://i.imgur.com/Kwz01MX.png" height="80%" width="80%" alt="Building a virtual network in Cisco Packet Tracer"/>

<img src="https://i.imgur.com/Lk5KCKA.png" height="80%" width="80%" alt="Building a virtual network in Cisco Packet Tracer"/>

With the wireless module connected, navigate to the PC wireless section of the Laptop and connect to the Home Network.

<img src="https://i.imgur.com/51RDhsB.png" height="80%" width="80%" alt="Building a virtual network in Cisco Packet Tracer"/>

Close the PC wireless tab and select the Web Browser. Within the web browser navigate to cisco.srv to verify the connectivity of the wireless network.

<img src="https://i.imgur.com/hfm4glc.png" height="80%" width="80%" alt="Editing Linux Permissions steps"/>



<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
