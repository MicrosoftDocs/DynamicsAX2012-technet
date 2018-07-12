---
title: 'Checklist: Configure Enterprise Portal security'
TOCTitle: 'Checklist: Configure Enterprise Portal security'
ms:assetid: fed77384-7e0c-446f-8f17-1fb3220a07c1
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dd362143(v=AX.60)
ms:contentKeyID: 35133351
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- EP security
---

# Checklist: Configure Enterprise Portal security 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

In Enterprise Portal for Microsoft Dynamics AX, security is enforced by using a combination of features and services. This topic includes checklists that can help you configure security in Enterprise Portal.

## Checklists for configuring Enterprise Portal security

By default, only the administrator who installed Enterprise Portal can access the site. Therefore, Enterprise Portal is effectively locked after it is installed. The configuration of security in Enterprise Portal involves verifying roles, enabling security features, and granting users access to the site. Information in the following tables can help you configure Enterprise Portal security.

Table 1: Security tasks for the server and operating system

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Task</p></th>
<th><p>More information</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Verify security settings for Internet Information Services (IIS) and SharePoint.</p></td>
<td><p>See the product documentation on Microsoft TechNet and MSDN.</p></td>
</tr>
<tr class="even">
<td><p>Encrypt Enterprise Portal client-server communications by using Secure Sockets Layer (SSL).</p></td>
<td><p><a href="http://go.microsoft.com/fwlink/?linkid=223135">How to Setup SSL on IIS 7</a></p></td>
</tr>
</tbody>
</table>


Table 2: Security tasks for extranet deployments

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Task</p></th>
<th><p>More information</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Enhance Enterprise Portal security in extranet deployments by using two domain controllers and two firewalls. This deployment model is called a traditional perimeter network.</p>
  
> [!TIP]
> <P>If you prefer not to deploy Enterprise Portal with multiple domain controllers, you can authenticate Enterprise Portal users by using claims-mode authentication. For more information, see the next item in this checklist.</P>

</td>
<td><p><a href="install-enterprise-portal-in-a-traditional-perimeter-network.md">Install Enterprise Portal in a traditional perimeter network</a></p></td>
</tr>
<tr class="even">
<td><p>Deploy an Enterprise Portal site that uses the claims mode authentication that is provided by SharePoint.</p>
<p>In the context of Microsoft Dynamics AX, this claims mode authentication is called Flexible authentication. Flexible authentication enables businesses and organizations to authenticate Enterprise Portal users without having to store user accounts in Active Directory Domain Services.</p></td>
<td><p><a href="deploy-an-enterprise-portal-site-that-uses-forms-based-authentication.md">Deploy an Enterprise Portal site that uses forms-based authentication</a></p></td>
</tr>
</tbody>
</table>


Table 3: Security tasks to enable user access

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Task</p></th>
<th><p>More information</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Verify that the Enterprise Portal site is registered in Microsoft Dynamics AX.</p></td>
<td><p>Click <strong>System administration</strong> &gt; <strong>Setup</strong> &gt; <strong>Enterprise Portal</strong> &gt; <strong>Web sites</strong>.</p></td>
</tr>
<tr class="even">
<td><p>Verify that Microsoft Dynamics AX role-based security is configured. At a minimum, users and groups must be members of the <strong>System user</strong> role.</p></td>
<td><p><a href="set-up-user-security-in-microsoft-dynamics-ax.md">Set up user security in Microsoft Dynamics AX</a></p>
<p><a href="set-up-user-security-in-microsoft-dynamics-ax.md">Set up user security in Microsoft Dynamics AX</a></p></td>
</tr>
<tr class="odd">
<td><p>Grant users and groups permission to view the site in SharePoint.</p></td>
<td><p><a href="enable-users-to-access-enterprise-portal.md">Enable users to access Enterprise Portal</a></p></td>
</tr>
<tr class="even">
<td><p>Specify user relations. User relations trim data based on a user's designated role and account. User relations are required for extranet deployments and for an employee self-service portal.</p>
<p>Employees who only access an employee self-service portal must be assigned a <strong>Worker</strong> relation in the <strong>User relations</strong> form.</p></td>
<td><p><a href="configure-user-relations.md">Configure user relations</a></p></td>
</tr>
<tr class="odd">
<td><p>Grant users and groups access to Microsoft SQL Server Reporting Services (SSRS) reports. Users and groups must have this access to view SSRS reports in Enterprise Portal and Role Centers.</p></td>
<td><p><a href="grant-users-access-to-reports.md">Grant users access to reports</a></p></td>
</tr>
<tr class="even">
<td><p>Grant users and groups access to Microsoft SQL Server Analysis Services (SSAS) cubes. Users and groups must have this access to view SSAS reports in Enterprise Portal and Role Centers.</p></td>
<td><p><a href="grant-users-access-to-cubes.md">Grant users access to cubes</a></p></td>
</tr>
<tr class="odd">
<td><p>Configure Enterprise Portal for data partitions.</p></td>
<td><p><a href="configure-enterprise-portal-to-access-data-in-a-partition.md">Configure Enterprise Portal to access data in a partition</a></p></td>
</tr>
</tbody>
</table>

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

