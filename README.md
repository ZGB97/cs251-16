<h1> Windows Server (Hyper-V) </h1>


<h2>Description</h2>
When using virtualization, one of the first things you to do is configure base images to be used as templates when creating virtual machines. A base image, sometimes called a reference or a golden image, is a virtual machine with an operating system installed and configured with settings that are common to all the systems with that particular operating system. In this lab, I completed the first part of this process, which is to create virtual machines and install the operating systems on the virtual machines.
<br />

<h2>Languages and Utilities Used</h2>

- <b>Windows Server 2019</b>
- <b>PowerShell</b>
- <b>Hyper-V Manager</b>

<h2>Program Screenshots:</h2>

<p align="center">
First Virtual Machine creation - Windows Server 2019 Datacenter edition : <br/>
<img src="https://i.imgur.com/Y0xHlqF.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Selected the Windows Server 2019 ISO Image File for DVD drive for VM:  <br/>
<img src="https://i.imgur.com/R3vPXqK.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Rearranged Boot Order (Windows Server 2019): <br/>
<img src="https://i.imgur.com/KFCQVpi.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Installing an OS on the First VM - Server 2019 Datacenter (Desktop Experience): <br/>
<img src="https://i.imgur.com/TldhipQ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Installing Windows Server Datacenter (No Desktop) on the 2nd VM after creation: <br/>
<img src="https://i.imgur.com/ZM9QVBA.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Installing Windows 10 DVD (Not Windows server 2019 DVD): <br/>
<img src="https://i.imgur.com/FXB3Rjf.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Rearranged Boot Order (Windows 10): <br/>
<img src="https://i.imgur.com/eohIoQq.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Installation completed (Windows Server 2019 Datacenter (Desktop Experience)): <br/>
<img src="https://i.imgur.com/SvCZSHB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Installation completed (Window Server Datacenter): <br/>
<img src="https://i.imgur.com/TW5Fy4U.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Installation completed (Windows 10 Education N): <br/>
<img src="https://i.imgur.com/vLiX0mY.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Turned off Windows Update Service on all 3 VMs:  <br/>
<img src="https://i.imgur.com/ThK9X9U.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
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
