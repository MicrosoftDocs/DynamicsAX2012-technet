---
title: Security architecture of the Microsoft Dynamics AX application
TOCTitle: Security architecture of the Microsoft Dynamics AX application
ms:assetid: 7d8a9cda-d97f-4b99-acd7-a42b9b662656
ms:mtpsurl: https://technet.microsoft.com/library/Aa496919(v=AX.60)
ms:contentKeyID: 35132694
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Security architecture of the Microsoft Dynamics AX application 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

When you understand the security architecture of Microsoft Dynamics AX, you can more easily customize security to fit the needs of your business. The following diagram provides a high-level overview of the security architecture of Microsoft Dynamics AX.

![security architecture diagram](images/Aa496919.SecurityArchitecture(AX.60).gif "security architecture diagram")

## Authentication

By default, only authenticated users who have user rights in Microsoft Dynamics AX can establish a connection.

The Microsoft Dynamics AX client uses integrated Windows authentication to authenticate Active Directory users.

Enterprise Portal supports flexible authentication, which allows you to use authentication providers other than Active Directory. If you configure Enterprise Portal to use a different authentication provider, users are authenticated by that provider.

After a user connects to the client or Enterprise Portal, access is determined by the duties and privileges that are assigned to the security roles that the user belongs to.

## Authorization

Authorization is the control of access to the Microsoft Dynamics AX application. Security permissions are used to control access to individual elements of the application: menus, menu items, action and command buttons, reports, service operations, web URL menu items, web controls, and fields in the Microsoft Dynamics AX client and Enterprise Portal for Microsoft Dynamics AX.

In Microsoft Dynamics AX, individual security permissions are combined into privileges, and privileges are combined into duties. The administrator grants security roles access to the application by assigning duties and privileges to the roles.

For more information about role-based security in Microsoft Dynamics AX, see [Role-based security in Microsoft Dynamics AX](role-based-security-in-microsoft-dynamics-ax.md).

## Data security

Authorization is used to grant access to elements of the application. By contrast, data security is used to deny access to tables, fields, and rows in the database.

Use the extensible data security framework to control access to transactional data by assigning data security policies to security roles. Data security policies can restrict access to data, based on the effective date or based on user data, such as the sales territory or organization. For more information about how to use data security policies in Microsoft Dynamics AX, see [Overview of Security Policies for Table Records](https://technet.microsoft.com/library/hh272123\(v=ax.60\)).

In addition to the extensible data security framework, record-level security can be used to limit access to data that is based on a query. However, because the record-level security feature is becoming obsolete in a future release of Microsoft Dynamics AX, we recommend that you use data security policies, instead.

Additionally, the Table Permissions Framework helps protect some data. Data security for specific tables is enforced by Application Object Server (AOS). For more information about the Table Permissions Framework, see [Manage data access by using the Table Permissions Framework](manage-data-access-by-using-the-table-permissions-framework.md).

  


