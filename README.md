<h1>🛜Provision CentOS 9 VM for Dev Application Server</h1>

 ### [YouTube Demonstration](https://youtu.be/7eJexJVCqJo)

<h2>Description</h2>
I provisioned a new CentOS Stream 9 virtual machine to support a new product launch for the software development team, per Infrastructure Team request. Task included full VM configuration, OS installation, hostname setup, and inventory logging in AssetTiger.

Objective: Learn how to provision and configure a Linux server from scratch in a virtualized environment.
<br />


<h2>Languages and Utilities Used</h2>

- <b>PowerShell</b>  
- <b>Diskpart</b>

<h2>Environments Used </h2>

- <b>VMware vSphere Client (used to provision and configure the VM)<b>
- <b>CentOS Stream 9 (guest OS)<b>
- <b>AssetTiger (inventory management tool)<b>

<b>


<h2>Program walk-through:</h2>

<p align="center">
Rex edit this to what you want it to say: <br/>

<img height="80%" width="80%" alt="REX IG github logo" src="https://github.com/user-attachments/assets/1885ba97-2039-4f65-9bd9-939a05d566c5" />

<br />

<img src="https://i.imgur.com/62TgaWL.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Select the disk:  <br/>
<img src="https://i.imgur.com/tcTyMUE.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Enter the number of passes: <br/>
<img src="https://i.imgur.com/nCIbXbg.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Confirm your selection:  <br/>
<img src="https://i.imgur.com/cdFHBiU.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Wait for process to complete (may take some time):  <br/>
<img src="https://i.imgur.com/JL945Ga.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Sanitization complete:  <br/>
<img src="https://i.imgur.com/K71yaM2.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Observe the wiped disk:  <br/>
<img src="https://i.imgur.com/AeZkvFQ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
