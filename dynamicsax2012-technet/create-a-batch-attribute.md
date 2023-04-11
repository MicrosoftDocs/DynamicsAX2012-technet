---
title: Create a batch attribute
TOCTitle: Create a batch attribute
ms:assetid: 281555d7-5a21-4f97-91c8-e7d2255748b1
ms:mtpsurl: https://technet.microsoft.com/library/Hh352189(v=AX.60)
ms:contentKeyID: 36687822
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- batch attributes
- create batch attributes
audience: Application User
ms.search.region: Global
---

# Create a batch attribute 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use this procedure to create batch attributes. Batch attributes are characteristics of raw materials or finished products that you can assign to items when the batch dimension is active.

1.  Click **Inventory management** \> **Setup** \> **Batch attributes** \> **Batch attributes**.

2.  Press CTRL+N to add a new line.

3.  In the **Attribute** field, enter an identifier for the attribute.

4.  In the **Description** field, optionally enter a description for the attribute.

5.  In the **Attribute type** field, select the type of attribute.
    
      - If you leave this field blank, the default type **String** is used.
    
      - If you select **Integer** or **Fraction**, the **Minimum**, **Maximum**, and **Increment** fields are available and you can define these values.
    
      - If you select **Enumerate**, define the value and sequence for the attribute in the **Attribute enumerate values** form.

6.  In the **Tolerance action** field, select the action to take when an **Integer** or **Fraction** attribute falls outside the minimum and maximum range that is specified.

7.  In the **Target** field, enter the optimal value for the range. For example, if you selected the attribute type **Date**, select the optimal date in the displayed calendar.

## See also

[About batch attributes](about-batch-attributes.md)

[Attribute enumerate values (form)](https://technet.microsoft.com/library/hh208618\(v=ax.60\))

[Batch attributes (form)](https://technet.microsoft.com/library/hh209255\(v=ax.60\))

  


