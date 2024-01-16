# Part 2
<h2>Setting up Active Directory:</h2>
Firstly, I downloaded the Windows Server .iso file and configured it into a new virtual machine on VirtualBox. Then, I started up the VM. 
Once installed, I connected to the Admin account. 
From the Server Manager Dashboard, I went to the "Open Network & Internet Settings."
<br />
<br />
<p align="center">
Dashboard:<br/>
<img src="https://i.imgur.com/e0EWtg2.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<p align="left"><br />
Then, I went to the Desktop Adapter Ethernet Properties, assigned a static IPv4 address, and used the LAN IP address from the pfSense virtual machine as the Default gateway. 
<br />
<br />
<p align="center">
Dashboard:<br/>
<img src="https://i.imgur.com/YP1Ngrl.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<p align="left"><br />
After that, I renamed my PC to something easier to use/remember. Once I renamed the PC, I had to restart the VM. From there, I installed Active Directory Domain Services and promoted the Windows Workstation to the domain controller. 
Then, I created a new AD Forest and rebooted the VM.
<br />
<br />
Finally, I downloaded BadBlood onto the AD. BadBlood is a software that fills Active Directory with OS structure and thousands of objects to simulate a real-world environment. 
However, because the virtual network didn’t have wireless access, I had to plug in a USB drive with the software downloaded and transfer it into the VM.
From there, I opened up Powershell as an administrator, went to the folder containing BadBlood (cd command), launched the program, and watched it install.
<br />
<br />
<p align="center">
Terminal BadBlood Installation:<br/>
<img src="https://i.imgur.com/J0CivQk.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<img src="https://i.imgur.com/XLnLy2t.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<p align="left"><br />
After the installation, 2500 users, 500 groups, OU, and 100 computers were configured into my Active Directory VM.
<br />
<br />
