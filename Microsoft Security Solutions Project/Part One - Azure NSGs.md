# Azure Network Security Groups (NSGs)

<h2>Objective</h2>

The objective of this activity was to gain a comprehensive understanding of network security configurations using Azure's Network Security Groups (NSGs) 
and to test inbound and outbound connectivity in a virtual machine (VM) environment. <br/>
Through this activity, I explored the fundamental parameters of a pre-existing VM, 
created and configured NSGs to manage inbound and outbound traffic effectively, and tested the functionality of NSG rules to ensure secure connectivity.
<br/>
<br/>

<h2>Part One</h2> 
<h3>Learning Virtual Machine Parameters</h3>

 In this task, the goal was to gain an understanding of the basic parameters associated with the pre-existing virtual machine (VM) intended for use in this project.  <br/>

  1. Accessed Microsoft Edge and navigated to https://portal.azure.com.
  2. Signed in using provided admin credentials.
  3. Located and selected the "Virtual Machines" section.
  4. Clicked on the designated VM named SC900-WinVM.
  5. Selected "Network Settings" from the left navigation panel.
  6. Observed the absence of a Network Security Group (NSG) assigned to the VM's network interface.

Task One provided insights into the initial state of the VM, establishing a foundation for subsequent tasks involving network security configurations.
<br/>
<br/>

<p align="center">
<img src="https://i.imgur.com/ANwKWuq.png" width="600" height="400">
<br />
<p align="left"><br />
<br/>
 
<h2>Part Two</h2> 
<h3>Network Security Groups</h3>
  
The objective of this task was to create an NSG, associate it with the VM's network interface, and establish an inbound rule for Remote Desktop Protocol (RDP) traffic.

  1. Searched for "Network security groups" in Azure services and selected it.
  2. Clicked on "Create network security group" and configured settings on the Basics tab.
  3. Reviewed settings and created the NSG.
  4. Verified NSG creation and absence of custom rules.
  5. Associated the NSG with the VM's network interface.
  6. Confirmed NSG association and proceeded to create an inbound security rule for RDP traffic.
  7. Defined rule parameters and ensured its appearance in the list of inbound rules.

Task Two demonstrated administrative steps involved in creating and configuring NSGs, emphasizing effective management of inbound traffic.
<br/>
<br/>

<p align="center">
<img src="https://i.imgur.com/01ZM5Mn.png" width="600" height="400">
<br />
<p align="left"><br />
<br/>
 
<h2>Part Three</h2> 
<h3>Testing Inbound Rule and Outbound Internet Connectivity</h3>

This task aimed to test the newly created inbound rule for RDP and verify outbound connectivity to the Internet from the VM.

  1. Accessed the SC900-WinVM page and verified RDP port accessibility.
  2. Established an RDP connection to the VM.
  3. Tested outbound Internet connectivity by accessing www.bing.com.
  4. Confirmed successful access and left the VM running.

Task Three provided a user perspective, validating the successful implementation of NSG rules and confirming both inbound and outbound connectivity.
<br/>
<br/>

<p align="center">
<img src="https://i.imgur.com/WjqEed0.png" width="600" height="400">
<br />
<p align="left"><br />
<br/>
 
<h2>Part Four</h2> 
<h3>Creating Custom Outbound Rule and Testing</h3>

In this task, the objective was to create a custom outbound rule to block Internet traffic and test its effectiveness.

  1. Accessed the SC900-WinVM | Connect page and selected Networking.
  2. Accessed the Outbound port rules tab and observed default outbound rule.
  3. Added a custom outbound rule to block Internet traffic.
  4. Waited for the rule to take effect and attempted to access www.bing.com.
  5. Confirmed the page did not display, indicating the effectiveness of the custom rule.

Task Four highlighted the ability to customize outbound rules for specific scenarios, demonstrating the flexibility of NSGs in controlling outbound traffic.
<br/>
<br/>

<p align="center">
<img src="https://i.imgur.com/B1GJJ34.png" width="600" height="400">
<br />
<p align="left"><br />
<br/>

<h2>Concusion</h2>

In conclusion, Activity One provided a comprehensive exploration of Azure Network Security Groups (NSGs) and their functionalities. 
It facilitated understanding of VM parameters, creation and configuration of NSGs, testing inbound and outbound connectivity, and customization of rules to meet specific security requirements. 
Through these tasks, valuable insights were gained, contributing to the development of skills essential for cybersecurity roles.



