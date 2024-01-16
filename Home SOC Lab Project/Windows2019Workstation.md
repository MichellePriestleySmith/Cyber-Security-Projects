# Part Three
<h2>Setting up Windows 2019 Workstation:</h2>
I began by downloading a Windows 10 .iso file and used it to create another virtual machine on VirtualBox.
Then, I configured a Network Adapter for the VM and booted the VM.
From there, I configured the VM with the Windows Workstation .iso file.
<br />
<br />
<p align="center">
Installing the Workstation:<br/>
<img src="https://i.imgur.com/B3kAPaw.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<p align="left"><br />
<br />
Once the Workstation was loaded, I went to the network adapter and changed its IPv4 properties to connect with the pfSense VM created previously and statically added the DNS server to the IPv4 address of the Active Directory VM.
<br />
<p align="center">
IPv4 Network Properties:<br/>
<img src="https://i.imgur.com/qeUMpZB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<p align="left"><br />
Then, I decided to confirm the connection between the Workstation VM and the pfSense VM by using the ping command, which returned successfully.
After testing the connection, I renamed the Workstation to something simpler and restarted the VM.
<br/>
<p align="center">
Ping Test:<br/>
<img src="https://i.imgur.com/hSiBjfk.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<p align="left"><br />
I then connected the Workstation to the AD Domain created in the Active Directory VM. I did this by going to “Advanced system settings” (System Properties), making the Workstation a member of the Domain "soc.lab", and finally logging into the Administrator account. 
<p align="center">
System Properties:<br/>
<img src="https://i.imgur.com/Wv8ie21.png" height="80%" width="80%" alt="Disk Sanitization Steps"/> 
 <br />
  <br />
  <br />
Here's the successful login screenshot:
<img src="https://i.imgur.com/WN4d8Ml.png" height="80%" width="80%" alt="Disk Sanitization Steps"/> 
<p align="left"><br />
