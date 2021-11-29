---
title: About role-based security in services and AIF
TOCTitle: About role-based security in services and AIF
ms:assetid: 9bf376f8-b07a-4f07-a606-3e2088407a66
ms:mtpsurl: https://technet.microsoft.com/library/Ee355069(v=AX.60)
ms:contentKeyID: 36941315
author: Khairunj
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
---

# About role-based security in services and AIF 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Security for Microsoft Dynamics AX services and Application Integration Framework (AIF) is based on the role-based security that is used in Microsoft Dynamics AX. For an overview of role-based security in Microsoft Dynamics AX, see [Role-based security in Microsoft Dynamics AX](role-based-security-in-microsoft-dynamics-ax.md). This topic describes how services and AIF help enforce security requirements through users, roles, duties, and privileges.

## AIF users

The following types of user can work with services and AIF.

### ![Ee355069.collapse\_all(en-us,AX.60).gif](images/Gg841655.collapse_all(en-us,AX.60).gif "Ee355069.collapse_all(en-us,AX.60).gif")Submitting user

The submitting user submits the message to Microsoft Dynamics AX. The submitting user must be an authenticated Microsoft Dynamics AX user.

The following table explains the process that AIF uses to determine the submitting user.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Data exchange method</p></th>
<th><p>Submitting user</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>File system adapter</p></td>
<td><p>The submitting user is the owner of the message request file as returned by the Windows GetFileSecurity (OWNER_SECURITY_INFORMATION) function. You can specify a default message owner that AIF uses when file ownership cannot be resolved deterministically. See <a href="configure-addresses-for-enhanced-integration-ports.md">Configure addresses for enhanced integration ports</a>.</p></td>
</tr>
<tr class="even">
<td><p>MSMQ adapter</p></td>
<td><p>The submitting user is the sender of the message as set on the SenderId property of the message.</p></td>
</tr>
<tr class="odd">
<td><p>Web services</p></td>
<td><p>The submitting user is the Windows identity of the caller.</p></td>
</tr>
</tbody>
</table>


### ![Ee355069.collapse\_all(en-us,AX.60).gif](images/Gg841655.collapse_all(en-us,AX.60).gif "Ee355069.collapse_all(en-us,AX.60).gif")Authorized port user

When you configure an integration port, you can restrict access to the port to a list of authorized users. For information about how to restrict users to authorized users, see [Configure security for integration ports](configure-security-for-integration-ports.md).

### ![Ee355069.collapse\_all(en-us,AX.60).gif](images/Gg841655.collapse_all(en-us,AX.60).gif "Ee355069.collapse_all(en-us,AX.60).gif")Claims user

A claims user is a type of Microsoft Dynamics AX user. Claims users are authenticated by an external system, not by Application Object Server (AOS). To gain authorization to access services, a claims user must be authenticated, and then impersonated by a trusted intermediary user. See the next section.

### ![Ee355069.collapse\_all(en-us,AX.60).gif](images/Gg841655.collapse_all(en-us,AX.60).gif "Ee355069.collapse_all(en-us,AX.60).gif")Trusted intermediary user

Trusted intermediaries are typically used for business-to-business data exchanges. A trusted intermediary is a type of submitting user that can act on behalf of another user, such as a claims user. A trusted intermediary is not a type of Microsoft Dynamics AX user. Instead, trusted intermediaries are typically middleware applications, such as Microsoft BizTalk Server or Electronic Data Interchange (EDI) services. These applications are represented by Microsoft Dynamics AX users or user groups that are authorized to submit inbound requests to an integration port. By using trusted intermediaries, you can delegate authentication to a trusted source, whereas authorization continues to be managed by Microsoft Dynamics AX through the role-based security framework.

Trusted intermediaries are associated with integration ports. You can define custom intermediaries when you configure an integration port. For information about how to configure integration ports to use trusted intermediaries, see [Configure security for integration ports](configure-security-for-integration-ports.md).

A trusted intermediary must always be an Active Directory user, never a claims user. A trusted intermediary can impersonate any other Microsoft Dynamics AX user, even a claims user. When the submitting user is a trusted intermediary, AIF provides authorization to the user that is defined in the message header by the \<LogonAsUser\> element. Otherwise, this element is ignored.


> [!IMPORTANT]
> <P>When you use a trusted intermediary, make sure that the trusted intermediary represents a known, valid partner or a trusted system.</P>



### ![Ee355069.collapse\_all(en-us,AX.60).gif](images/Gg841655.collapse_all(en-us,AX.60).gif "Ee355069.collapse_all(en-us,AX.60).gif")Proxy user

If a proxy is used, .NET Business Connector can connect on behalf of Microsoft Dynamics AX users when authentication is performed by an AOS instance. For more information, see [Specify the .NET Business Connector proxy account](specify-the-net-business-connector-proxy-account.md).

## Roles, duties, and privileges

Users who have the roles that are described in the following table can configure integration port settings for services and AIF.

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Role</p></th>
<th><p>AOT name</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>Information technology manager</strong></p></td>
<td><p><strong>SysServerITManager</strong></p></td>
<td><p>This role has the following two duties that are related to services and AIF:</p>
<ul>
<li><p><strong>AifIntegrationMaintain</strong>, which provides the privileges that are required for typical AIF tasks, such as configuring integration ports, viewing the message queue, and reviewing history information.</p></li>
<li><p><strong>AifSyncConfigure</strong>, which provides the privileges that are required to configure document filters.</p></li>
</ul></td>
</tr>
<tr class="even">
<td><p><strong>System administrator</strong></p></td>
<td><p><strong>-SYSADMIN-</strong></p></td>
<td><p>A user who has this role is a super user, and therefore has full permission for every operation in Microsoft Dynamics AX.</p></td>
</tr>
</tbody>
</table>


Every service operation is associated with an entry point privilege. This privilege provides permissions for the tables that the service reads or modifies. For example, the **SalesSalesOrderServiceCreate** service operation is associated with the **SalesSalesOrderServiceCreate** privilege. The **ServiceOperation** duty provides privileges for all service operations. Other duties provide privileges for specific service operations, depending on the responsibilities of the duty and its associated roles. For example, among the privileges that the **DOCommerceOnlineSalesOrderMaintain** duty provides is the **SalesSalesOrderServiceCreate** privilege.

To understand the relationships between roles, duties, privileges, and permissions, see the **Security** node of the Application Object Tree (AOT).

  
**Announcements:** New book: "Inside Microsoft Dynamics AX 2012 R3" now available. Get your copy at the [MS Press Store](https://www.microsoftpressstore.com/store/inside-microsoft-dynamics-ax-2012-r3-9780735685109).

