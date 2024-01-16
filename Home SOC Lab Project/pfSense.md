# Part One
<h2>Setting up pfSense:</h2>

The first virtual machine I created was a pfSense firewall machine. This would be a dedicated VM only for firewall purposes.
I downloaded the latest pfSense .iso file and compared SHA-256 hashes to ensure the file wasn’t tampered with.
I ran the “certutil -hashfile [file location] SHA256” command and compared hashes from what I received from the command line and the hash I downloaded in the .iso link.
<br />

As you can see below, the hashes are a perfect match.<br />

<p align="center">
Hash Check: <br/>
<img src="https://i.imgur.com/8CL9kIr.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<p align="left"><br />
After configuring and creating the VM, I activated 3 Network Adapters. One for the external network (WAN), the internal network (LAN), and the Demilitarized Zone (DMZ). Then, I launched the VM.
<p align="center">
pfSense Downloaded:<br/>
<img src="https://i.imgur.com/8CL9kIr.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<p align="left"><br />
Once I could install pfSense onto the VM, I had to link the 3 Network Adapters to which type of network they would represent on pfSense (WAN, LAN, etc.). 
Lastly, I added a static IP address for the LAN adapter. This made it easy to remember to use throughout this project. Then, I enabled DHCP for the WAN.
<p align="center">
pfSense Configured:<br/>
<img src="https://i.imgur.com/hmqLxtY.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
