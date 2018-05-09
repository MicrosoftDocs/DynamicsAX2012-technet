---
title: Considerations for installing multiple instances on a computer
TOCTitle: Considerations for installing multiple instances on a computer
ms:assetid: a568fd5e-1f2d-4d58-932d-3ac6f5c1e851
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa548643(v=AX.60)
ms:contentKeyID: 35132796
ms.date: 08/14/2014
mtps_version: v=AX.60
---

# Considerations for installing multiple instances on a computer 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

In a single environment, you can install multiple instances of Application Object Server (AOS) and the Microsoft Dynamics AX database.

You can install multiple instances of Microsoft Dynamics AX components on separate computers or on the same computer. AOS instances and databases cannot be shared among instances of Microsoft Dynamics AX.

Multiple Microsoft Dynamics AX instances are primarily used in development environments that support multiple customers.


> [!WARNING]
> <P>We do not support the installation of multiple versions of Microsoft Dynamics AX components on the same computer in a production environment.</P>



The following table lists the considerations when you install a second instance of a component.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Component</p></th>
<th><p>Considerations</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>AOS</p></td>
<td><p>Each AOS instance is automatically assigned a number between 01 and 99. This number is displayed in the <strong>Programs and Features</strong> item in Control Panel.</p>
<p>We recommend that you create a group in Active Directory Domain Services to manage permissions for the AOS accounts. For more information, see <a href="install-an-application-object-server-aos-instance.md">Install an Application Object Server (AOS) instance</a>.</p></td>
</tr>
<tr class="even">
<td><p>Database</p></td>
<td><p>During initialization, you can import existing data into the database.</p></td>
</tr>
<tr class="odd">
<td><p>Components that require .NET Business Connector</p></td>
<td><p>You can install only one instance of .NET Business Connector on a computer. In an environment that has multiple AOS instances, use the Microsoft Dynamics AX Configuration utility to make sure that the instance of .NET Business Connector on the local computer connects to the correct AOS instance for the component that you are installing.</p>
<p>In the utility, in the <strong>Configuration Target</strong> list, select <strong>Business Connector (non-interactive use only)</strong>. On the <strong>Connection</strong> tab, verify that the correct AOS instance is displayed.</p>
<p>For more information about how to use the Microsoft Dynamics AX Configuration utility, click the <strong>Help</strong> button in the utility.</p></td>
</tr>
<tr class="even">
<td><p>Reporting Services extensions</p></td>
<td><p>You can install multiple instances of Microsoft SQL Server Reporting Services on the same computer. In this kind of deployment environment, each instance of Reporting Services is connected to an independent Microsoft Dynamics AX installation. You may want to install multiple instances of Reporting Services on the same computer to support development and production installations of Microsoft Dynamics AX, or to support multiple production installations of Microsoft Dynamics AX.</p>
<p>For information about how to install multiple instances of Reporting Services, see <a href="install-multiple-instances-of-reporting-services-on-the-same-computer-for-use-with-microsoft-dynamics-ax.md">Install multiple instances of Reporting Services on the same computer (for use with Microsoft Dynamics AX)</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Enterprise Portal</p></td>
<td><p>You can install multiple Enterprise Portal instances on the same computer. Portals can be configured to access the same or different Microsoft Dynamics AX AOS instances. For more information, see <a href="install-multiple-enterprise-portals-on-the-same-server.md">Install multiple Enterprise Portals on the same server</a>.</p></td>
</tr>
</tbody>
</table>

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

