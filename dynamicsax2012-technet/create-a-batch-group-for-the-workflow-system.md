---
title: Create a batch group for the workflow system
TOCTitle: Create a batch group for the workflow system
ms:assetid: e4777fab-5621-4ef9-8766-ccb830c27245
ms:mtpsurl: https://technet.microsoft.com/library/Gg732165(v=AX.60)
ms:contentKeyID: 35133114
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Create a batch group for the workflow system 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The workflow system uses batch jobs to process messages, determine due dates for work items, and process notifications for line items. Complete the following procedures to create a batch group for the workflow batch jobs.

## Create a batch group

Follow these steps to create a batch group for the batch jobs.

1.  Click **System administration** \> **Setup** \> **Batch group**.

2.  Click **New** to create a new batch group.

3.  In the **Group** field, enter a unique name for the batch group. For example, enter **Workflow**.

4.  In the **Description** field, enter a description to help you identify the batch group.

## Specify the servers that the batch group runs on

Follow these steps to specify the Application Object Server (AOS) instances that the batch group runs on.

1.  Click **System administration** \> **Setup** \> **Batch group**.

2.  Select the batch group that you created in the previous procedure.

3.  Click the **Batch servers** tab.
    
    The **Selected servers** list displays the AOS instances that the batch group runs on. The **Remaining servers** list displays the remaining AOS instances that are available as batch servers.

4.  Use the arrow buttons to add servers to the **Selected servers** list or to remove servers from the **Selected servers** list.

  


