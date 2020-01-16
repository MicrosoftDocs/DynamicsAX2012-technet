---
title: Set up prerequisites to report quality order results for a potency item
TOCTitle: Set up prerequisites to report quality order results for a potency item
ms:assetid: 7b7c956a-9722-433d-b894-da753bd3906e
ms:mtpsurl: https://technet.microsoft.com/library/JJ838739(v=AX.60)
ms:contentKeyID: 50120622
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Set up prerequisites to report quality order results for a potency item 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Use this procedure to set up prerequisites to report quality order results for a potency item. To set up and use quality orders for potency items, you must first set up inventory parameters that are related to quality orders. You must also set up test groups to update inventory batch attributes, and you must specify other parameters to determine how test results are evaluated. For more information, see [Set up prerequisites for quality orders](set-up-prerequisites-for-quality-orders.md).

## Set up inventory parameters for quality orders

1.  Click **Inventory management** \> **Setup** \> **Inventory and warehouse management parameters**.

2.  In the left pane, click **Quality management**.

3.  Select the **Update inventory batch attribute** check box to update inventory batch attributes with test result values.

4.  Select the **Use quality management** check box to activate quality management.

## Set up test groups to update inventory batch attributes

1.  Click **Inventory management** \> **Setup** \> **Quality control** \> **Test groups**.

2.  Select a test group, and then click the **General** tab in the lower pane. For more information, see [(PM) Test groups (form)](https://technet.microsoft.com/library/hh328633\(v=ax.60\)).

3.  Select the **Update inventory batch attribute** check box to update inventory batch attributes with test result values.

4.  In the **Test value determination** field, select **Average**, **Minimum**, or **Maximum** as the method that is used to determine the test result value.

5.  Click the **Test** tab.

6.  In the **Attribute** field, select the inventory batch attribute that is associated with the quality test group.

## See also

[(PM) Inventory and warehouse management parameters (form)](https://technet.microsoft.com/library/hh352320\(v=ax.60\))

  


