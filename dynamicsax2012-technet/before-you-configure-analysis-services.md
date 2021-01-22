---
title: Before you configure Analysis Services
TOCTitle: Before you configure Analysis Services
ms:assetid: 7c89294e-ba10-42a4-82c7-efe96d5bc1e3
ms:mtpsurl: https://technet.microsoft.com/library/Gg731841(v=AX.60)
ms:contentKeyID: 35132693
author: Khairunj
ms.author: daxcpft
ms.date: 06/03/2014
mtps_version: v=AX.60
---

# Before you configure Analysis Services 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Before you configure Microsoft SQL Server Analysis Services for use with Microsoft Dynamics AX, you must complete the following procedures.

## Verify that you have the required permissions to configure Analysis Services

To configure Analysis Services, you must have the required permissions. For more information, see [Verify that you have the required permissions for installation](verify-that-you-have-the-required-permissions-for-installation.md).

## Create a domain account to run the Analysis Services service

Create a domain account that can run the Analysis Services service. For more information, see [Create service accounts](create-service-accounts.md).

## Assign the Business Connector proxy account to the Analysis Services server administrator role

The proxy account for Business Connector must be assigned to the server administrator role in Analysis Services. To complete that task, follow these steps.

1.  Open Microsoft SQL Server Management Studio and connect to your Analysis Services instance.

2.  In the tree view, right-click the Analysis Services instance, and then click **Properties**. The **Analysis Services Properties** window is displayed.

3.  In the **Select a page** area, click **Security**.

4.  Click **Add**. The **Select Users or Groups** form is displayed.

5.  Enter the Business Connector proxy account in the following format: \[DomainName\]\\\[UserName\]. Click **OK**.

## Install prerequisites

On the computer where Analysis Services is installed, or where you plan to install Analysis Services, run the prerequisite validation utility to verify that system requirements have been met. For information about how to run the prerequisite validation utility, see [Check prerequisites](check-prerequisites.md).

For more information about the hardware and software requirements for Microsoft Dynamics AX, see the [system requirements](https://go.microsoft.com/fwlink/?linkid=165377).

  


