---
title: Create a batch disposition code
TOCTitle: Create a batch disposition code
ms:assetid: f84c5118-eb9f-4db2-9995-4e9867a8b8b0
ms:mtpsurl: https://technet.microsoft.com/library/Hh227557(v=AX.60)
ms:contentKeyID: 36060047
author: Khairunj
ms.author: daxcpft
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Create a batch disposition code 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use this procedure to create a batch disposition code. You use batch disposition codes with inventory batches to indicate whether a batch is available to be reserved, picked, and shipped. You also use them for master planning.

1.  Click **Inventory management** \> **Setup** \> **Batch disposition** \> **Batch disposition master**.

2.  Press CTRL+N to add a new batch disposition code.

3.  In the **Batch disposition code** field, enter a unique name or identifier for the disposition code.

4.  In the **Description** field, enter a description for the disposition code.

5.  In the **Batch disposition status** field, select the status if it differs from the default, which is **Unavailable**.
    
      - If you accept the **Unavailable** status, all fields on the **Setup FastTab** are available for entry. Select the appropriate fields for any blocking required. If the inventory batch is available for master planning, you also select **Nettable**.
    
      - If you select **Available**, all **Block** fields are automatically cleared, and the **Nettable** field is selected. You cannot change these values as long as the status is **Available**.

## See also

[Batch disposition master (form)](https://technet.microsoft.com/library/hh208612\(v=ax.60\))

  


