---
title: Set up user accounts and the POS user group
TOCTitle: Set up user accounts and the POS user group
ms:assetid: a129368a-5cf6-4f07-a041-92f45962030d
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ838774(v=AX.60)
ms:contentKeyID: 50120657
ms.date: 05/18/2015
mtps_version: v=AX.60
---

# Set up user accounts and the POS user group 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack_

This topic describes how to grant access to the components of Microsoft Dynamics AX for Retail POS.

## The POS user group

When you configure a database by using the Store Database Utility, a local Windows user group that is named **POSUsers** is created. The POS user group inherits the rights and permissions of the Standard user group on the computer. Typically, these rights and permissions are sufficient and do not have to be modified.

If a computer at the store does not have a local database, you must manually create the **POSUsers** user group on that computer.

If any of your users are logged on when they are added to the user group, they must log out of Windows, and log back in in order to access the system.


> [!IMPORTANT]
> <P>If you are running SQL Server Express, you must remove any users that are members of the <STRONG>POSUsers</STRONG> user group from the <STRONG>BUILTINUSERS</STRONG> user group.</P>



For more information about how to create local groups, see [Create a local group](http://technet.microsoft.com/en-us/library/cc731215) on TechNet.

## The SQL Server logon for POS users

When you configure a database by using the Store Database Utility, a Microsoft SQL Server logon that is named **POSUsers** is created for point of sale (POS) users.

The SQL Server logon provides access to the store database. This logon has read and write permissions, or **db\_datareader**, **db\_datawriter**, and **db\_executor** permissions, on the store database. If cashiers do not have this access, they cannot process transactions.

## User accounts for employees

Create a Windows user account for each store employee on each computer that the employee uses. To manage permissions for all employees at the same time, you should assign the local user accounts to the local **POSUsers** user group. You must also assign the account that is used by Commerce Data Exchange: Synch Service to the **POSUsers** user group.

Employees use their local user accounts to log on to Windows and start Retail POS. An employee can then log on to Retail POS by using credentials that were set up for that employee in Microsoft Dynamics AX.

All user accounts should have strong passwords that meet the password policy for the organization. Guest or temporary user accounts are not supported.

For more information about how to create local Windows user accounts, see [Create a local user account](http://technet.microsoft.com/en-us/library/cc770642.aspx) on TechNet.

## Set up users in Microsoft Dynamics AX

Before a worker can perform job duties in a retail store, you must set up the worker in Microsoft Dynamics AX. You must also assign the worker appropriate privileges, so that the worker can log on and perform tasks by using the Retail POS system. For more information, see [Setting up staff](setting-up-staff.md).

  


