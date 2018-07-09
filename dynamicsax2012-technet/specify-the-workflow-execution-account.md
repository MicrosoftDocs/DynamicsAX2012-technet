---
title: Specify the workflow execution account
TOCTitle: Specify the workflow execution account
ms:assetid: e53382f6-5e30-4175-b497-9f644ed748b3
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Gg732189(v=AX.60)
ms:contentKeyID: 35133137
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Specify the workflow execution account [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Complete the following procedure to select a domain account to serve as the workflow execution account. The workflow execution account runs business logic for the application and accesses Microsoft Dynamics AX data.

The domain account that you select to serve as the workflow execution account must have the following characteristics:

  - It must be a dedicated account. A dedicated account is used only for a specific purpose.

  - It must have a password that does not expire.

  - It must have minimal access to network resources.

<!-- end list -->

1.  Click **System administration** \> **Setup** \> **System** \> **System service accounts**.

2.  Go to the **Workflow execution account** area of the form.

3.  Specify a domain account to serve as the workflow execution account. You can specify the domain account in one of two ways:
    
      - Enter the domain and user name, or alias, of the account.
    
      - Select a Microsoft Dynamics AX user.
    
    The account that you specify is assigned to the Microsoft Dynamics AX system administrator role.

4.  If you are using Microsoft Dynamics AX 2012 R2 or later, repeat steps 1 through 3 for each partition in your Microsoft Dynamics AX installation.

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

