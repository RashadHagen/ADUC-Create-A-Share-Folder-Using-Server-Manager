<h1>Server Manager - Create A Share Folder</h1>


<h2 style="font-family: Arial, sans-serif; font-size: 20px; font-weight: bold; margin-top: 24px; margin-bottom: 12px;">
⏹️ Description</h2>

<p style="font-family: Georgia, serif; font-size: 16px; margin-top: 12px; margin-bottom: 12px;">
This project goes over how to create a share folder using server manager using Server Manager. A share folder allows users on the network to access a specific folder and its contents as if they were directly on the server. This creates a central location for sharing files and folders, facilitating collaboration and reducing the need for manual file transfers between users.
</b>



<h2 style="font-family: Arial, sans-serif; font-size: 20px; font-weight: bold; margin-top: 24px; margin-bottom: 12px;">
⏹️ Utilities Used</h2>
  
<p style="font-family: Georgia, serif; font-size: 16px; margin-top: 12px; margin-bottom: 12px;">
 
 - <b>Server Manager</b>



<h2 style="font-family: Arial, sans-serif; font-size: 20px; font-weight: bold; margin-top: 24px; margin-bottom: 12px;"> 
⏹️ Environments Used </h2>

<p style="font-family: Georgia, serif; font-size: 16px; margin-top: 12px; margin-bottom: 12px;">
 
- <b>Windows 10 & Windows Server 2016</b>



<h2 style="font-family: Arial, sans-serif; font-size: 20px; font-weight: bold; margin-top: 24px; margin-bottom: 12px;"> 
<h2>
⏹️ Project Walk-Through:</h2>
 <br/>

<div style="text-align:center;">
  <span style="font-family: Arial, sans-serif; font-size: 16px;"><b>•	NOTE: By default Microsoft puts a Share Folder in File Explorer path: C: (drive) - Shares (folder) after creation.</b></span>  
<br/><br/>


<div style="text-align:center;">
  <span style="font-family: Arial, sans-serif; font-size: 16px;"><b>•	NOTE: After creating the Share Folder, it is not shared with anyone until you assign a user / group / organizational unit).</b></span>  
<br/><br/><br/><br/>


<div style="text-align:center;">
  <span style="font-family: Arial, sans-serif; font-size: 16px;"><b>Open: Server Manager.</b></span>  
<br/>

<table>
  <tr>
    <td><img src="https://imgur.com/iTsIabf.png" height="50%" width="100%" /></td>
    <td><img src="https://imgur.com/rKZuena.png" height="50%" width="100%" /></td>
  </tr>
</table>

<br /><br />


<div style="text-align:center;">
  <span style="font-family: Arial, sans-serif; font-size: 16px;"><b>Click: File and Storage Services (far-left column).</b></span>  
<br/>

<table>
  <tr>
    <td><img src="https://imgur.com/lTJCFlw.png" height="50%" width="100%" /></td>
    <td><img src="https://imgur.com/Wl6Do06.png" height="50%" width="100%" /></td>
  </tr>
</table>

<br /><br />


<div style="text-align:center;">
  <span style="font-family: Arial, sans-serif; font-size: 16px;"><b>Click: Shares (left-column).</b></span>  
<br/>

<table>
  <tr>
    <td><img src="https://imgur.com/67C6F4S.png" height="100%" width="100%" /></td>
    <td><img src=https://imgur.com/nfD0EdV.png" height="100%" width="100%" /></td>
  </tr>
</table>

<table>
  <tr>
    <td><img src="https://imgur.com/GgGy4IZ.png" height="50%" width="50%" /></td>
  </tr>
</table>

<br /><br />


<div style="text-align:center;">
  <span style="font-family: Arial, sans-serif; font-size: 16px;"><b>Right-Click: The white part in the middle of the screen below SHARES (top).</b></span>  
<br/>

<table>
  <tr>
    <td><img src="https://imgur.com/uTjvxsx.png" height="100%" width="100%" /></td>
    <td><img src="https://imgur.com/zEXfK2Z.png" height="100%" width="100%" /></td>
  </tr>
</table>

<table>
  <tr>
    <td><img src="https://imgur.com/CdLqdzz.png" height="50%" width="50%" /></td>
  </tr>
</table>

<br /><br />


</div>
  <span style="font-family: Arial, sans-serif; font-size: 16px;"><b>Click: New Shares.
    <br/>
    
  <img src="https://imgur.com/pxoDAGT.png" height="50%" width="50%"/>  
  <br /><br /><br /><br />


<div style="text-align:center;">
  <span style="font-family: Arial, sans-serif; font-size: 16px;"><b>Selcct: The type of File Sharing Profile you want to do (SMB = Windows, NFS = Linux/Unix). (ex: SMB Share – Quick).  Click: Next.</b></span>  
<br/>

<table>
  <tr>
    <td><img src="https://imgur.com/vw6pv1n.png" height="100%" width="100%" /></td>
    <td><img src="https://imgur.com/XD0Jfia.png" height="100%" width="100%" /></td>
  </tr>
</table>

<table>
  <tr>
    <td><img src="https://imgur.com/qBZb4ZW.png" height="50%" width="50%" /></td>
  </tr>
</table>

<br /><br />


<div style="text-align:center;">
  <span style="font-family: Arial, sans-serif; font-size: 16px;"><b>Select: The server you want to put the shared drive with (ex: DCSERVER2016KIS).  Click: Next.</b></span>  
<br/>

<table>
  <tr>
    <td><img src="https://imgur.com/xE2IGKN.png" height="100%" width="100%" /></td>
    <td><img src="https://imgur.com/lb43Jcx.png" height="100%" width="100%" /></td>
  </tr>
</table>

<table>
  <tr>
    <td><img src="https://imgur.com/mKKH0Jk.png" height="50%" width="50%" /></td>
  </tr>
</table>

<br /><br />


<div style="text-align:center;">
  <span style="font-family: Arial, sans-serif; font-size: 16px;"><b>Type: The name of the share folder.  NOTE: The area named: Local path to share, is showing the path of the share folder being created.  Click: Next.</b></span>  
<br/>

<table>
  <tr>
    <td><img src="https://imgur.com/t4z76AC.png" height="100%" width="100%" /></td>
    <td><img src="https://imgur.com/L0jQ5oX.png" height="100%" width="100%" /></td>
  </tr>
</table>

<table>
  <tr>
    <td><img src="https://imgur.com/iqaYZTl.png" height="50%" width="50%" /></td>
  </tr>
</table>

<br /><br />


<div style="text-align:center;">
  <span style="font-family: Arial, sans-serif; font-size: 16px;"><b>Select: Configuration share settings.  Click: Next.</b></span>  
<br/>

<table>
  <tr>
    <td><img src="https://imgur.com/Vv2qUdH.png" height="50%" width="100%" /></td>
    <td><img src="https://imgur.com/DYLumSX.png" height="50%" width="100%" /></td>
  </tr>
</table>

<br /><br />


<div style="text-align:center;">
  <span style="font-family: Arial, sans-serif; font-size: 16px;"><b>Click: Create custom permissions  (AND/OR)  Click: Next.</b></span>  
<br/>

<table>
  <tr>
    <td><img src="https://imgur.com/F4f5YPJ.png" height="50%" width="100%" /></td>
    <td><img src="https://imgur.com/Kfjr2sw.png" height="50%" width="100%" /></td>
  </tr>
</table>

<br /><br />


<div style="text-align:center;">
  <span style="font-family: Arial, sans-serif; font-size: 16px;"><b>Click: Create.</b></span>  
<br/>

<table>
  <tr>
    <td><img src="https://imgur.com/BtOvwfG.png" height="50%" width="100%" /></td>
    <td><img src="https://imgur.com/4ZED9F9.png" height="50%" width="100%" /></td>
  </tr>
</table>

<br /><br />


<div style="text-align:center;">
  <span style="font-family: Arial, sans-serif; font-size: 16px;"><b>Click: Close.</b></span>  
<br/>

<table>
  <tr>
    <td><img src="https://imgur.com/go1Ef9C.png" height="50%" width="100%" /></td>
    <td><img src="https://imgur.com/4ZPKKoR.png" height="50%" width="100%" /></td>
  </tr>
</table>

<br /><br />
