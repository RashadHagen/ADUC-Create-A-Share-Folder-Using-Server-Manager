<h1>Active Directory Users and Computers (ADUC) - Create A Share Folder Using Server Manager</h1>


<h2 style="font-family: Arial, sans-serif; font-size: 20px; font-weight: bold; margin-top: 24px; margin-bottom: 12px;">
⏹️ Description</h2>

<p style="font-family: Georgia, serif; font-size: 16px; margin-top: 12px; margin-bottom: 12px;">
This project goes over how to create a share folder using server manager using Server Manager. A share folder allows users on the network to access a specific folder and its contents as if they were directly on the server. This creates a central location for sharing files and folders, facilitating collaboration and reducing the need for manual file transfers between users.
</b>



<h2 style="font-family: Arial, sans-serif; font-size: 20px; font-weight: bold; margin-top: 24px; margin-bottom: 12px;">
⏹️ Utilities Used</h2>
  
<p style="font-family: Georgia, serif; font-size: 16px; margin-top: 12px; margin-bottom: 12px;">
 
 - <b>Active Directory Users and Computers</b>



<h2 style="font-family: Arial, sans-serif; font-size: 20px; font-weight: bold; margin-top: 24px; margin-bottom: 12px;"> 
⏹️ Environments Used </h2>

<p style="font-family: Georgia, serif; font-size: 16px; margin-top: 12px; margin-bottom: 12px;">
 
- <b>Windows 10 & Windows Server 2016</b>



<h2 style="font-family: Arial, sans-serif; font-size: 20px; font-weight: bold; margin-top: 24px; margin-bottom: 12px;"> 
<h2>
⏹️ Project Walk-Through:</h2>
 <br/>

<div style="text-align:center;">
  <span style="font-family: Arial, sans-serif; font-size: 16px;"><b>Open: Server Manager.</b></span>:  
<br/>

<table>
  <tr>
    <td><img src="https://imgur.com/txb6Mot.png" height="50%" width="100%" /></td>
    <td><img src="https://imgur.com/AcOJlQA.png" height="50%" width="100%" /></td>
  </tr>
</table>

<br /><br />


<div style="text-align:center;">
  <span style="font-family: Arial, sans-serif; font-size: 16px;"><b>Click: File and Storage Services (far-left column).</b></span>:  
<br/>

<table>
  <tr>
    <td><img src="https://imgur.com/txb6Mot.png" height="50%" width="100%" /></td>
    <td><img src="https://imgur.com/AcOJlQA.png" height="50%" width="100%" /></td>
  </tr>
</table>

<br /><br />


<div style="text-align:center;">
  <span style="font-family: Arial, sans-serif; font-size: 16px;"><b>Click: Shares (left-column).</b></span>:  
<br/>

<table>
  <tr>
    <td><img src="https://imgur.com/MPzu4yq.png" height="100%" width="100%" /></td>
    <td><img src="https://imgur.com/QTgQ623.png" height="100%" width="100%" /></td>
  </tr>
</table>

<table>
  <tr>
    <td><img src="https://imgur.com/kw4bQDE.png" height="50%" width="50%" /></td>
  </tr>
</table>

<br /><br />


<div style="text-align:center;">
  <span style="font-family: Arial, sans-serif; font-size: 16px;"><b>Right-Click: The white part in the middle of the screen below SHARES (top).</b></span>:  
<br/>

<table>
  <tr>
    <td><img src="https://imgur.com/MPzu4yq.png" height="100%" width="100%" /></td>
    <td><img src="https://imgur.com/QTgQ623.png" height="100%" width="100%" /></td>
  </tr>
</table>

<table>
  <tr>
    <td><img src="https://imgur.com/kw4bQDE.png" height="50%" width="50%" /></td>
  </tr>
</table>

<br /><br />


</div>
  <span style="font-family: Arial, sans-serif; font-size: 16px;"><b>Click: New Shares. 
    <a href="https://github.com/RashadHagen/ADUC-Find-Computer-User-Printer-Shared-Folder-Organizational-Unit-Common-Queries" style="font-family: Arial, sans-serif; font-size: 22px; font-weight: bold;"> How To Find</b></span>  
  <br/>
  <img src="https://imgur.com/weAIRRS.png" height="50%" width="50%"/>  
  <br /><br /><br /><br />


<div style="text-align:center;">
  <span style="font-family: Arial, sans-serif; font-size: 16px;"><b>Selcct: The type of File Sharing Profile you want to do (SMB = Windows, NFS = Linux/Unix). (ex: SMB Share – Quick).  Click: Next.</b></span>:  
<br/>

<table>
  <tr>
    <td><img src="https://imgur.com/MPzu4yq.png" height="100%" width="100%" /></td>
    <td><img src="https://imgur.com/QTgQ623.png" height="100%" width="100%" /></td>
  </tr>
</table>

<table>
  <tr>
    <td><img src="https://imgur.com/kw4bQDE.png" height="50%" width="50%" /></td>
  </tr>
</table>

<br /><br />


<div style="text-align:center;">
  <span style="font-family: Arial, sans-serif; font-size: 16px;"><b>Select: The server you want to put the shared drive with (ex: DCSERVER2016KIS).  Click: Next.</b></span>:  
<br/>

<table>
  <tr>
    <td><img src="https://imgur.com/MPzu4yq.png" height="100%" width="100%" /></td>
    <td><img src="https://imgur.com/QTgQ623.png" height="100%" width="100%" /></td>
  </tr>
</table>

<table>
  <tr>
    <td><img src="https://imgur.com/kw4bQDE.png" height="50%" width="50%" /></td>
  </tr>
</table>

<br /><br />


<div style="text-align:center;">
  <span style="font-family: Arial, sans-serif; font-size: 16px;"><b>Type: The name of the share folder.  NOTE: The area named: Local path to share, is showing the path of the share folder being created.  Click: Next.</b></span>:  
<br/>

<table>
  <tr>
    <td><img src="https://imgur.com/MPzu4yq.png" height="100%" width="100%" /></td>
    <td><img src="https://imgur.com/QTgQ623.png" height="100%" width="100%" /></td>
  </tr>
</table>

<table>
  <tr>
    <td><img src="https://imgur.com/kw4bQDE.png" height="50%" width="50%" /></td>
  </tr>
</table>

<br /><br />


<div style="text-align:center;">
  <span style="font-family: Arial, sans-serif; font-size: 16px;"><b>Select: Configuration share settings.  Click: Next.</b></span>:  
<br/>

<table>
  <tr>
    <td><img src="https://imgur.com/txb6Mot.png" height="50%" width="100%" /></td>
    <td><img src="https://imgur.com/AcOJlQA.png" height="50%" width="100%" /></td>
  </tr>
</table>

<br /><br />


<div style="text-align:center;">
  <span style="font-family: Arial, sans-serif; font-size: 16px;"><b>Click: Create custom permissions  (AND/OR)  Click: Next.</b></span>:  
<br/>

<table>
  <tr>
    <td><img src="https://imgur.com/txb6Mot.png" height="50%" width="100%" /></td>
    <td><img src="https://imgur.com/AcOJlQA.png" height="50%" width="100%" /></td>
  </tr>
</table>

<br /><br />


<div style="text-align:center;">
  <span style="font-family: Arial, sans-serif; font-size: 16px;"><b>Click: Create.</b></span>:  
<br/>

<table>
  <tr>
    <td><img src="https://imgur.com/txb6Mot.png" height="50%" width="100%" /></td>
    <td><img src="https://imgur.com/AcOJlQA.png" height="50%" width="100%" /></td>
  </tr>
</table>

<br /><br />


<div style="text-align:center;">
  <span style="font-family: Arial, sans-serif; font-size: 16px;"><b>Click: Close</b></span>:  
<br/>

<table>
  <tr>
    <td><img src="https://imgur.com/txb6Mot.png" height="50%" width="100%" /></td>
    <td><img src="https://imgur.com/AcOJlQA.png" height="50%" width="100%" /></td>
  </tr>
</table>

<br /><br />
