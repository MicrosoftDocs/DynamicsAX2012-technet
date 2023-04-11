---
title: Select inventory batches for an active ingredient in a batch order
TOCTitle: Select inventory batches for an active ingredient in a batch order
ms:assetid: 14b055b1-6f66-41ec-b6c7-a7d4033c572d
ms:mtpsurl: https://technet.microsoft.com/library/JJ838723(v=AX.60)
ms:contentKeyID: 50120606
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Select inventory batches for an active ingredient in a batch order 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Use this procedure to select inventory batches for the active ingredients in a batch order formula. When you select an available inventory batch, the balanced quantity is calculated based on the active quantity of the active ingredient in the batch order formula. You can remove a batch from reservation by clearing the **Mark** check box for that batch. After you select an active quantity for the active ingredient, you can select another active ingredient in the batch order formula.

1.  Click **Production control** \> **Common** \> **Production orders** \> **All production orders**. Select a production order with the status **Started**, and then click **Batch balancing**.

2.  In the upper pane, select an active ingredient.

3.  In the lower pane, select the **Mark** check box for the inventory batches to associate them with the selected active ingredient.

4.  Click **Balance batch ingredients**.
    
    The following actions occur:
    
      - If there are any compensating ingredients in the batch order formula, the balanced and active quantities are calculated based on the compensating factor for each compensating ingredient.
    
      - If there are any filler ingredients in the batch order formula, the balanced and active quantities are calculated based on the difference between the total estimated quantities for the active and compensating ingredients and the total balanced quantities for the active and compensating ingredients.
    
      - The balanced quantity for an ingredient with active ingredient type **None** is set to **Estimated quantity**.

5.  Click **Confirm formula** to confirm the batch order formula and update it with the balanced quantities.

## See also

[Batch balancing (form)](https://technet.microsoft.com/library/jj838768\(v=ax.60\))

[(PM) Production orders (form)](https://technet.microsoft.com/library/jj838764\(v=ax.60\))

[Define an active ingredient in a formula line](define-an-active-ingredient-in-a-formula-line.md)

  


