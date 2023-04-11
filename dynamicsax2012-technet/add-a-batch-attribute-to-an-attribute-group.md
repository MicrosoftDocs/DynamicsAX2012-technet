---
title: Add a batch attribute to an attribute group
TOCTitle: Add a batch attribute to an attribute group
ms:assetid: ebe7bf92-8d2f-4d73-a1b2-3db997853dbf
ms:mtpsurl: https://technet.microsoft.com/library/Hh227494(v=AX.60)
ms:contentKeyID: 36059888
author: tonyafehr
ms.author: daxcpft
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Add a batch attribute to an attribute group 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use this procedure to add a batch attribute to a batch attribute group.

1.  Click **Inventory management** \> **Setup** \> **Batch attributes** \> **Batch attribute groups**.

2.  Select the batch attribute group.

3.  Click **Group attributes**. The **Group attributes** form is displayed.

4.  Press CTRL+N to add a new batch attribute.

5.  In the **Attribute** field, select the batch attribute.

6.  In the **Target** field, enter the optimal value for the batch attribute. If the attribute is tied to a quality test, this value represents the outcome that you want from testing.

7.  If the batch attribute type is **Integer** or **Fraction**, enter values in these fields:
    
      - In the **Minimum** field, enter the minimum value in the batch attribute range.
    
      - In the **Maximum** field, enter the maximum value in the batch attribute range.
    
      - In the **Increment** field, enter the increment that determines the batch attribute values that you can enter in the **Minimum** and **Maximum** range. For example, if the increment is 5 and the minimum and maximum range is 1 to 30, you could enter batch attribute values of 5, 10, 15, 20, 25, and 30.

## See also

[About batch attributes](about-batch-attributes.md)

[Batch attribute groups (form)](https://technet.microsoft.com/library/hh209431\(v=ax.60\))

[Group attributes (form)](https://technet.microsoft.com/library/hh209573\(v=ax.60\))

  


