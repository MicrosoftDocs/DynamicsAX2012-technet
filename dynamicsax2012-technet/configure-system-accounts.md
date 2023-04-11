---
title: Configure system accounts
TOCTitle: Configure system accounts
ms:assetid: 56e3522e-38a8-41ba-b95e-3ad3c7d53178
ms:mtpsurl: https://technet.microsoft.com/library/Dd309681(v=AX.60)
ms:contentKeyID: 35132641
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Configure system accounts 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Click **System administration** \> **Setup** \> **System** \> **System service accounts**. –or– Open the **System service accounts** form from the initialization checklist or the upgrade checklist.

Use the **System service accounts** form to configure the accounts used to run Microsoft Dynamics AX services. Service accounts include the Business Connector proxy account, the workflow execution account, the Microsoft Project Server synchronization service account, and the Bing Maps account.

## Configure the Business Connector proxy account

In the **Alias** and **Network domain** fields, enter the user name and domain for the Business Connector proxy account.

The Business Connector proxy account is used for communication between Microsoft Dynamics AX and other applications.

For more information about the requirements for this account, see [Specify the .NET Business Connector proxy account](specify-the-net-business-connector-proxy-account.md).

## Configure the Workflow execution account

The Workflow execution account is used for running application business logic and accessing Microsoft Dynamics AX data. You can use one of the following accounts.

  - Enter a domain account in the **Alias** and **Network domain** fields to use a domain user for the Workflow execution account.

  - Enter a new or existing Microsoft Dynamics AX user to access the database.


> [!NOTE]
> <P>This option is not available from the Initialization Checklist if you are using Microsoft Dynamics AX 2012 R3 or AX 2012 R2. In AX 2012 R3 and AX 2012 R2, a workflow execution account must be specified for each partition.</P>



For more information about how to configure this account, see [Specify the workflow execution account](specify-the-workflow-execution-account.md).

## Configure the synchronization service account

The synchronization service account is used for communication between Microsoft Dynamics AX, Windows Message Queuing, and Microsoft Project Server. You can use one of the following accounts.

  - Enter a domain account in the **Alias** and **Network domain** fields to use a domain user for the synchronization service account.

  - Enter a Microsoft Dynamics AX user for the synchronization service to communicate with. You can associate the service with a new or existing Microsoft Dynamics AX user.

For more information about the requirements for the synchronization service account, see [Create service accounts](create-service-accounts.md).

## Configure the Bing Maps account

The Bing Maps account is used to access the online Bing Maps when working in Enterprise Portal.

You can find the Bing Maps account name and password on [CustomerSource](https://mbs.microsoft.com/customersource).

By selecting the check box and entering the information, you agree to be bound by the Microsoft Bing Maps and MapPoint Web Service [End User Terms of Use](https://go.microsoft.com/fwlink/?linkid=21969).

  


