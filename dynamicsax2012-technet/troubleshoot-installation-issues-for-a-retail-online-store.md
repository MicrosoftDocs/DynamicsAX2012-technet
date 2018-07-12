---
title: Troubleshoot installation issues for a Retail online store
TOCTitle: Troubleshoot installation issues for a Retail online store
ms:assetid: d560274f-76b9-4fa1-a9da-1edc2caf33e4
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn903645(v=AX.60)
ms:contentKeyID: 63892670
ms.date: 05/18/2015
mtps_version: v=AX.60
---

# Troubleshoot installation issues for a Retail online store 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

This topic includes strategies and procedures to help you troubleshoot problems installing the Microsoft Dynamics AX Retail online store.

## General tips and strategies

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Tip/Strategy</p></th>
<th><p>Details</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>Check the amount of RAM on the SharePoint Server</strong></p></td>
<td><p>The System requirements for Microsoft Dynamics AX 2012 guide suggests a minimum of 16 GB of RAM. Depending on your infrastructure, 32 GB of RAM might be necessary. Many of the stop issues experienced with the Windows PowerShell deployment scripts resolve without additional troubleshooting if you increase the amount of RAM on the server.</p></td>
</tr>
<tr class="even">
<td><p><strong>Search the SharePoint ULS logs</strong></p></td>
<td><p>The SharePoint ULS logs can provide more information about errors than other logging sources. Search the ULS logs for a timestamp that reflects your deployment activities. By default, the logs are stored here:</p>
<p>C:\Program Files\Common Files\Microsoft Shared\Web Server Extensions\15\LOGS</p></td>
</tr>
<tr class="odd">
<td><p><strong>Configure tracing details in SharePoint Diagnostic Logging</strong></p></td>
<td><p>The Windows Event log and the SharePoint ULS log store exceptions for events triggered when you deploy the Retail online store. Traces for the Retail online store display “Dynamics AX Retail”. To help you troubleshoot your deployment, you can adjust tracing and information levels.</p>
<ol>
<li><p>In SharePoint Central Administration, click <strong>Monitoring</strong>, and then click <strong>Configure diagnostic logging</strong>.</p></li>
<li><p>Select <strong>Dynamics AX Retail</strong>.</p></li>
<li><p>Use the drop-down lists underneath the <strong>Categories</strong> and select <strong>Verbose</strong> as the least critical events and traces to log.</p></li>
<li><p>Save your changes.</p></li>
</ol></td>
</tr>
<tr class="even">
<td><p><strong>For manual installation, you can re-run Windows PowerShell scripts</strong></p></td>
<td><p>If you experience an error during the execution phase of one of the Windows PowerShell deployment scripts, you can rerun the script after you have resolved the error. You do not have to rerun completed scripts. If you rerun the Deploy-FarmSolutions script, the system automatically invokes the DeactivateOnly-Features.ps1 and RetractOnly-Solutions.ps1 scripts before you deploy the farm solution. These scripts clean up actions performed by the Deploy-FarmSolutions script before redeploying.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Return the SharePoint server to a clean state</strong></p></td>
<td><p>Perform the following steps if, for any reason, you want to return your server to a clean state.</p>
<ol>
<li><p>In SharePoint Central Administration, click <strong>System Settings</strong> and then click <strong>Manage Farm features</strong>. Deactivate the following features: <strong>Retail Custom Claims Provider</strong>, <strong>Retail Logging Service</strong>, and <strong>Retail Publishing Job</strong>. If you do not see one or more of these features, go to step 2, otherwise go to step 3.</p></li>
<li><p>On the <strong>System Settings</strong> page, click <strong>Manage farm solutions</strong>. Retract each solution and then click <strong>OK</strong>. IIS and SharePoint Central Administration will be temporarily unavailable.</p></li>
<li><p>On the <strong>Application Management</strong> page, click <strong>Manage web applications</strong>. Delete <strong>C1 Application for Retail Store Front - Internal</strong> and <strong>Out of box Store front – Public</strong>.</p></li>
<li><p>In SQL Manager, delete the following databases if they exist: AxRetailSP, SpFBA, and SpSqlAuthz</p></li>
<li><p>Restart the web service.</p></li>
</ol></td>
</tr>
<tr class="even">
<td><p><strong>Domain account password changed</strong></p></td>
<td><p>If a password for one or more of the required domain accounts changes, then you must update the credentials for that domain account in the following locations:</p>
<ol>
<li><p>In IIS Manager for any application pools that were configured to use the domain account.</p></li>
<li><p>In the Windows Services console, filter the list of services according to <strong>Log On As</strong> and change any service that was configured to use the domain account.</p></li>
<li><p>If necessary, in SharePoint Central Administration, click <strong>Security</strong> &gt; <strong>Configure managed accounts</strong>. Edit or delete accounts as necessary.</p></li>
</ol></td>
</tr>
</tbody>
</table>


## Specific errors

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Error</p></th>
<th><p>Details</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>The file name is required error</strong></p></td>
<td><p>If you experience this error in the Command Prompt window after you execute a script it means that you did not add the oob-topology.xml and oob-settings.xml files to the end of the script. Each script must be executed in the following form:</p>
<p>.\<em>ScriptName</em>.ps1 oob-topology.xml oob-settings.xml</p>
<p></p></td>
</tr>
<tr class="even">
<td><p><strong>Error: 500 Internal Server</strong></p></td>
<td><p>If you experience this error in the Command Prompt window after you execute the Deploy-FarmSolutions script, it means that you have not installed the <a href="http://go.microsoft.com/fwlink/?linkid=277134&amp;clcid=0x409">URL Rewrite Module 2.0</a> on the SharePoint server. Install the URL Rewrite Module and then execute the Deploy-FarmSolutions script again.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Error: System.Servicemodel.ServiceActivationException</strong></p></td>
<td><p>If you see this error in the Command Prompt window after you execute any of the PowerShell scripts, it means that the server has insufficient RAM to complete the operation. Verify that the server has a least 10 GB of RAM. If possible, increase the amount of RAM to 16 GB or 32 GB and then execute the scripts again.</p></td>
</tr>
<tr class="even">
<td><p><strong>Error: System.InvalidOperationException: standardCategoryField.TermSetId is empty Guid</strong></p></td>
<td><p>This error can mean one of the following.</p>
<ul>
<li><p>One of the SharePoint application pools is not running in IIS Manager.</p></li>
<li><p>The Managed Metadata Service application is not installed in SharePoint.</p></li>
<li><p>The wrong SKU of SharePoint is installed on the server.</p></li>
</ul>
<p>Verify that all application pools are running in IIS Manager and that the Managed Metadata Service application is installed and running in SharePoint. If you still see this error, then uninstall all versions of SharePoint and restart the server. Reinstall SharePoint Server 2013 and execute the PowerShell scripts again.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Error: Cannot add the specified assembly to the global assembly cache: &lt;DLL name&gt;</strong></p></td>
<td><p>There are two possible issues/solutions for this error.</p>
<p>The DLL you are trying to add to the global assembly cache (GAC) already exists on the server and is blocked by another process such as the SharePoint Timer service or IIS. Restart the server and rerun the deployment scripts.</p>
<p>The DLL does not exist on the server and you must manually add the DLL to the GAC by using the following command at a command prompt: gacutil -if &lt;DLL name&gt;</p>
<p>Rerun the deployment scripts</p></td>
</tr>
<tr class="even">
<td><p><strong>Error: System.UnauthorizedAccessException: Access is denied. (Exception from HRESULT: 0x80070005 (E_ACCESSDENIED)),</strong></p></td>
<td><p>Verify that the user you specified in the oob-settings.xml file for the ProductCatalog and PublishingPortal (storefront) application pools has sufficient permission to modify properties on the root website in SharePoint. One of the Windows PowerShell scripts tried to modify the title of the root web site when this error occurred.</p></td>
</tr>
</tbody>
</table>

  


