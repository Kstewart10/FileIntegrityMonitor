<h1>File Integrity Monitor</h1>

<h2>Description</h2>
In this lab I have created a barebones File Integrity monitor using Powershell. The powershell script creates a baseline of files to be checked and alerts the user of changes made to said files. The purpose of this lab is to get some hands on practice with a file integrity monitor and further understand the concept of Integrity within the security and technology workspace. 
<br />


<h2>Languages and Utilities Used</h2>

- <b>PowerShell</b> 

<h2>Lab walk-through:</h2>

<p align="center">
Start of program: <br/>
<img src="https://i.imgur.com/zbPCCpd.png" height="80%" width="80%" alt="File Integrity Monitor"/>
<br />
<br />
Baseline Has Been Created:  <br/>
<img src="https://i.imgur.com/Sr8ss2L.png" height="80%" width="80%" alt="File Integrity Monitor"/>
<br />
<br />
Created Baseline File: <br/>
<img src="https://i.imgur.com/tCumd5m.png" height="80%" width="80%" alt="File Integrity Monitor"/>
<br />
<br />
Files to be Checked:  <br/>
<img src="https://i.imgur.com/JGGEpm3.png" height="80%" width="80%" alt="File Integrity Monitor"/>
<br />
<br />
Infinite Loop Begins to check for any changes to the selected folder:  <br/>
<img src="https://i.imgur.com/mDN7D9l.png" height="80%" width="80%" alt="File Integrity Monitor"/>
<br />
<br />
Removing File 'e' from the folder:  <br/>
<img src="https://i.imgur.com/YYfwDiT.png" height="80%" width="80%" alt="FIM"/>
<br />
<br />
Monitor reports that file 'e' has been deleted:  <br/>
<img src="https://i.imgur.com/vGPMaBd.png" height="80%" width="80%" alt="FIM"/>
 <br />
 <br />
Adding an 'e - copy' File to the Folder:  <br/>
<img src="https://i.imgur.com/axzj3Tx.png" height="80%" width="80%" alt="FIM"/>
<br />
<br />
Monitor Notifies a New File Being Created:  <br/>
<img src="https://i.imgur.com/yXLzBSX.png" height="80%" width="80%" alt="FIM"/>
 <br />
<br />
Making Changes to the 'b' File:  <br/>
<img src="https://i.imgur.com/Dw4Iyuq.png" height="80%" width="80%" alt="FIM"/>
 <br />
 <br />
Monitor Notifies that 'b' Has Been Changed:  <br/>
<img src="https://i.imgur.com/ACm7t3d.png" height="80%" width="80%" alt="FIM"/>
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
