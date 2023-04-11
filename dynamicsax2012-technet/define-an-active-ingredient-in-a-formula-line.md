---
title: Define an active ingredient in a formula line
TOCTitle: Define an active ingredient in a formula line
ms:assetid: cc76ede2-2e30-401d-9eea-9ba96db18e88
ms:mtpsurl: https://technet.microsoft.com/library/JJ838749(v=AX.60)
ms:contentKeyID: 50120632
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Define an active ingredient in a formula line 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Use this procedure to select an ingredient type for a specified formula line. A formula can have more than one active ingredient type selected at a time.

1.  Click **Product information management** \> **Common** \> **Released products**.

2.  Select a potency item, click the **Engineer** tab, and then click **Lines**.

3.  In the **Formula line** form, create a formula line. For more information, see [Formula line (form)](https://technet.microsoft.com/library/hh352331\(v=ax.60\)).

4.  In the **Ingredient type** field, select the active ingredient type from the following options:
    
      - **None** ─ This is the default value for items that have no base attributes specified or whose quantity is not be affected by an item with a base attribute. You can also select this option for an item that has a base attribute but that is not treated as a potency item in a formula.
    
      - **Active** ─ An adjustment is calculated based on the base attribute value of the active ingredient and raw material.
    
      - **Compensating** ─ Compensation is calculated to increase or decrease the estimated consumption of the raw material based on an attribute of the active ingredient.
    
      - **Filler** ─ An adjustment is calculated based on the difference between the total quantity that is estimated for the active and compensating ingredients.

5.  In the **Item number** field, select the potency item number.
    

    > [!NOTE]
    > <P>The <STRONG>Active quantity</STRONG> field is updated with the ingredient quantity at 100-percent concentration based on the quantity and target value of the base attribute.</P>



6.  Select the **Resource consumption** check box to assign material consumption for the formula line to a resource. The resource is a production unit that defines a picking warehouse.

## See also

[Batch attributes (form)](https://technet.microsoft.com/library/hh209255\(v=ax.60\))

[(PM) Released product details (form)](https://technet.microsoft.com/library/hh352306\(v=ax.60\))

  


