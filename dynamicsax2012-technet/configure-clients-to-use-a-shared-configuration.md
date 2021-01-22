---
title: Configure clients to use a shared configuration
TOCTitle: Configure clients to use a shared configuration
ms:assetid: 6c2ef77d-c371-4dc3-ab5c-8a2dbedea98d
ms:mtpsurl: https://technet.microsoft.com/library/Hh378075(v=AX.60)
ms:contentKeyID: 36870658
author: Khairunj
ms.author: daxcpft
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Configure clients to use a shared configuration 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

By default, the Microsoft Dynamics AX client reads configuration information from the registry on the local computer. If you deploy many Microsoft Dynamics AX clients, it can be difficult to maintain or troubleshoot configurations. To enhance security and simplify client administration, we recommend that large deployments run the Microsoft Dynamics AX client as a Windows Server RemoteApp. For more information, see the Windows Server RemoteApp documentation on Microsoft on TechNet. If your organization cannot deploy the Microsoft Dynamics AX client as a remote application, we recommend that you deploy the client by using one of the methods that are listed in the following table.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Deployment method</p></th>
<th><p>For more information</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Microsoft System Center Configuration Manager</p></td>
<td><p><a href="deploy-the-client-by-using-microsoft-system-center-configuration-manager-2007.md">Deploy the client by using Microsoft System Center Configuration Manager 2007</a></p>
<p><a href="deploy-the-client-by-using-microsoft-system-center-2012-configuration-manager.md">Deploy the client by using Microsoft System Center 2012 Configuration Manager</a></p></td>
</tr>
<tr class="even">
<td><p>Group Policy</p></td>
<td><p><a href="deploy-the-client-by-using-group-policy.md">Deploy the client by using Group Policy</a></p></td>
</tr>
</tbody>
</table>


If you deploy the Microsoft Dynamics AX client by using one of these methods, we recommend that you configure clients to access configuration information from a file that is stored on a network share. A shared configuration file can reduce the time that you spend administering or troubleshooting clients.

## Before you begin

If your business or organization runs Microsoft Dynamics AX 2012 clients on both 32-bit and 64-bit versions of the Windows operating system, you must create multiple configuration files. Microsoft Dynamics AX clients that run on a 32-bit version of Windows must connect to a client configuration file that was created on a 32-bit version of Windows. Similarly, Microsoft Dynamics AX clients that run on a 64-bit version of Windows must connect to a client configuration file that was created on a 64-bit version of Windows.

## Create a shared configuration file

1.  On a file server or the server that hosts Application Object Server (AOS), create the directory that the clients share. Configure the directory so that all users of the Microsoft Dynamics AX client have read access.

2.  Use the Microsoft Dynamics AX 2012 Configuration utility to save a Microsoft Dynamics AX configuration as a file. For more information, see [Manage a client configuration](manage-a-client-configuration.md). If your business or organization runs both 32-bit and 64-bit versions of Windows, you must save a separate configuration file for each operating system. Open the Microsoft Dynamics AX 2012 Configuration utility on each operating system, and save a configuration as a file. We recommend that you give each configuration a name that identifies the version, such as 32bit.axc and 64bit.axc.

3.  Copy the configuration files to the share that you created in step 1.

## Set up clients to use the shared configuration file

The following table lists three methods that you can use to set up clients to use a shared configuration file. For more information, see [Install a client](install-a-client.md).

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Method</p></th>
<th><p>For more information</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>In the Setup wizard, enter the path of the shared configuration file when you install the Microsoft Dynamics AX client.</p></td>
<td><p><a href="install-a-client.md">Install a client</a></p></td>
</tr>
<tr class="even">
<td><p>Log on to a client computer, and use the <strong>Set Configuration Store</strong> option in the Microsoft Dynamics AX 2012 Configuration utility to specify the new shared configuration file. This method is useful when a client is already installed and configured to read configurations from the registry on the local computer.</p></td>
<td><p><a href="manage-a-client-configuration.md">Manage a client configuration</a></p></td>
</tr>
<tr class="odd">
<td><p>Use the ClientConfigFile setup parameter, and specify the path of the shared configuration file. This method can be used for client installations that are run in silent mode. The following example shows the format of the parameter.</p>
<pre><code>ClientConfigFile=&quot;%Drive%:\&lt;name of configuration file&gt;.axc&quot;</code></pre>
<div class="alert">

> [!TIP]
> <P>If you want to install clients, but you do not want to install the Microsoft Dynamics AX 2012 Configuration utility, set the ClientConfig parameter to 0 (zero).</P>


</div></td>
<td><p><a href="run-setup-in-silent-mode.md">Run Setup in silent mode</a></p></td>
</tr>
</tbody>
</table>


## See also

[Mass deployment of the Microsoft Dynamics AX Windows client](mass-deployment-of-the-microsoft-dynamics-ax-windows-client.md)

[Client security and protection](client-security-and-protection.md)

  


