<h1>Microsoft Entra ID - How To Create A Group Account</h1>


<h2 style="font-family: Arial, sans-serif; font-size: 20px; font-weight: bold; margin-top: 24px; margin-bottom: 12px;">
⏹️ Description</h2>

<p style="font-family: Georgia, serif; font-size: 16px; margin-top: 12px; margin-bottom: 12px;">
In this project, you will learn a controlled method to grant external users access to selected resources within a Microsoft Entra ID tenant without creating internal accounts. You will invite an external user into Microsoft Entra ID as a B2B guest and validate the end-to-end invitation and acceptance process. You access Microsoft Entra ID through the Azure portal, initiate the external user invitation from the Users section, and complete the required configuration across the Basics, Properties, Assignments, and Review + Create tabs. After sending the invitation, you refresh the tenant view and verify the process by having the external user accept the invitation, complete email verification, and sign in using their existing credentials. The external user will successfully be added to the tenant as a guest account, confirming that B2B collaboration access can be provisioned securely and validated through the Microsoft Entra ID invitation workflow.
</b>



<h2 style="font-family: Arial, sans-serif; font-size: 20px; font-weight: bold; margin-top: 24px; margin-bottom: 12px;">
⏹️ Utilities Used</h2>
  
<p style="font-family: Georgia, serif; font-size: 16px; margin-top: 12px; margin-bottom: 12px;">
 
 - <b>Microsoft Azure, Microsoft Entra ID</b>



<h2 style="font-family: Arial, sans-serif; font-size: 20px; font-weight: bold; margin-top: 24px; margin-bottom: 12px;"> 
⏹️ Environments Used </h2>

<p style="font-family: Georgia, serif; font-size: 16px; margin-top: 12px; margin-bottom: 12px;">
 
- <b>Windows 11 & Windows Server 2025</b>



<h2 style="font-family: Arial, sans-serif; font-size: 20px; font-weight: bold; margin-top: 24px; margin-bottom: 12px;"> 
<h2>
⏹️ Project Walk-Through:</h2>
 <br/>

</div>
  <span style="font-family: Arial, sans-serif; font-size: 16px;"><b>•	NOTE: Group accounts can include user accounts or devices.</b></span>  
<br/><br/>

</div>
  <span style="font-family: Arial, sans-serif; font-size: 16px;"><b>•	Static groups require administrators to add and remove members manually</b></span>  
<br/>

</div>
  <span style="font-family: Arial, sans-serif; font-size: 16px;"><b>•	Dynamic groups update automatically based on the properties of a user account or device. For example, job title.</b></span>  
<br/><br/><br/


</div>
  <span style="font-family: Arial, sans-serif; font-size: 16px;"><b>Open: Microsoft Entra ID from https://portal.azure.com</b></span>  
<br/><br/>

<div style="text-align:center;">
  <span style="font-family: Arial, sans-serif; font-size: 16px;"><b><a href="https://github.com/RashadHagen/How-To-Open-Microsoft-Entra-ID-From-PortaldotAzuredotcom" style="font-family: Arial, sans-serif; font-size: 22px; font-weight: bold;"> (LINK: How To Open Entra ID From portal.azure.com)</b></span>  
  <br/>

<table>
  <tr>
    <td><img src="https://imgur.com/hK5Ae3Y.png" height="100%" width="100%" /></td>
    <td><img src="https://imgur.com/7S0vn9f.png" height="100%" width="100%" /></td>
  </tr>
</table>

<br /><br />


<div style="text-align:center;">
  <span style="font-family: Arial, sans-serif; font-size: 16px;"><b>Click: Manage (far left side).</b></span>  
<br/>

<table>
  <tr>
    <td><img src="https://imgur.com/RngFGri.png" height="100%" width="100%" /></td>
    <td><img src="https://imgur.com/BxFKUDP.png" height="100%" width="100%" /></td>
  </tr>
</table>

<table>
  <tr>
    <td><img src="https://imgur.com/KPpF3St.png" height="100%" width="100%" /></td>
  </tr>
</table>

<br /><br />


<div style="text-align:center;">
  <span style="font-family: Arial, sans-serif; font-size: 16px;"><b>Click: Groups (under Manage drop-down).</b></span>  
<br/>

<table>
  <tr>
    <td><img src="https://imgur.com/An54kDI.png" height="100%" width="100%" /></td>
  </tr>
</table>

<table>
  <tr>
    <td><img src="https://imgur.com/IpEnIGH.png" height="100%" width="100%" /></td>
  </tr>
</table>

<br /><br />


<div style="text-align:center;">
  <span style="font-family: Arial, sans-serif; font-size: 16px;"><b>Click: New group (top-middle, above Overview).</b></span>  
<br/>

<table>
  <tr>
    <td><img src="https://imgur.com/jrMielL.png" height="100%" width="100%" /></td>
  </tr>
</table>

<table>
  <tr>
    <td><img src="https://imgur.com/HeqKDhG.png" height="100%" width="100%" /></td>
  </tr>
</table>

<table>
  <tr>
    <td><img src="https://imgur.com/kMPKPnp.png" height="100%" width="100%" /></td>
  </tr>
</table>

<table>
  <tr>
    <td><img src="https://imgur.com/HM34ofe.png" height="100%" width="100%" /></td>
  </tr>
</table>

<br /><br />


</div>
  <span style="font-family: Arial, sans-serif; font-size: 16px;"><b>Type & Select: Group information.</b></span>
<br/>

<table>
  <tr>
    <td><img src="https://imgur.com/l4AQPuc.png" height="100%" width="100%" /></td>
  </tr>
</table>

<br /><br />


</div>
  <span style="font-family: Arial, sans-serif; font-size: 16px;"><b>Click: No owners selected (bottom of list, under Owners).</b></span>
<br/>

<table>
  <tr>
    <td><img src="https://imgur.com/4Y8zT1A.png" height="100%" width="100%" /></td>
  </tr>
</table>

<table>
  <tr>
    <td><img src="https://imgur.com/rpOQbRO.png" height="100%" width="100%" /></td>
  </tr>
</table>

<br /><br />


</div>
  <span style="font-family: Arial, sans-serif; font-size: 16px;"><b>Click: No members selected (bottom of list, under Members).</b></span>
<br/>

<table>
  <tr>
    <td><img src="https://imgur.com/JHuGIRg.png" height="100%" width="100%" /></td>
  </tr>
</table>

<table>
  <tr>
    <td><img src="https://imgur.com/Ym82k8r.png" height="100%" width="100%" /></td>
  </tr>
</table>

<br /><br />


</div>
  <span style="font-family: Arial, sans-serif; font-size: 16px;"><b>Click: Create (very bottom-left).</b></span>
<br/>

<table>
  <tr>
    <td><img src="https://imgur.com/0berBxV.png" height="100%" width="100%" /></td>
  </tr>
</table>

<br /><br />


</div>
  <span style="font-family: Arial, sans-serif; font-size: 16px;"><b>After clicking Create, you will be redirected back to the Microsoft Entra ID Groups Overview webpage.</b></span>
<br/><br/>

</div>
  <span style="font-family: Arial, sans-serif; font-size: 16px;"><b>•	ACTION REQUIRED: Refresh the Microsoft Entra ID Groups Overview webpage to update the amount of the group type you created (Dynamic  OR  Security) under Basic Information.</b></span>
<br/>

<table>
  <tr>
    <td><img src="https://imgur.com/neU28fC.png" height="50%" width="50%" /></td>
  </tr>
</table>

<table>
  <tr>
    <td><img src="https://imgur.com/mmkPz81.png" height="50%" width="50%" /></td>
  </tr>
</table>

<table>
  <tr>
    <td><img src="https://imgur.com/S1CdavE.png" height="100%" width="100%" /></td>
  </tr>
</table>

<br /><br />
