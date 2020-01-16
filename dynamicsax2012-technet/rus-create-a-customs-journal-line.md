---
title: (RUS) Create a customs journal line
TOCTitle: (RUS) Create a customs journal line
ms:assetid: 980703d7-eb8b-4358-8462-d56b39abb013
ms:mtpsurl: https://technet.microsoft.com/library/JJ917356(v=AX.60)
ms:contentKeyID: 50952845
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Russia
---

# (RUS) Create a customs journal line 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Use the **Create customs journal lines** form to create a journal line for a customs journal. You can create journal lines for transactions that have the following sources:

  - Purchase orders that are associated with import operations for the passing of property after customs clearance

  - Purchase invoices that are associated with import operations for the passing of property before customs clearance

  - Sales invoices that are associated with export operations for postponed passing of property

  - Sales packing slips for common export operations

When you select a source transaction in the upper pane of the form, the associated transaction lines are displayed in the lower pane. In the lower pane, you can view the details of each transaction line. You can modify the quantity that is selected for common items. For units that are catch-weight (CW) enabled, you can also specify the quantity of common units or CW units that is selected for processing.

The quantity of units that is selected for common items cannot exceed the quantity of units that is available for common items. The quantity of units that is selected for CW-enabled items cannot exceed the quantity of units that is available for CW-enabled items.

1.  Click **Inventory management** \> **Common** \> **All customs journals**.

2.  Create a journal, or double-click an existing journal. For more information, see [(RUS) Create a customs journal for import or export operations](rus-create-a-customs-journal-for-import-or-export-operations.md).

3.  On the **Customs journal lines** FastTab, click **Create lines**.

4.  Select the **Choose** check box.

5.  In the **Selected CW qty** field, enter the quantity of CW units that is selected for processing. If you modify the value of the **Selected CW qty** field, Microsoft Dynamics AX recalculates the value in the **Selected quantity** field to a median value that is between the minimum and maximum range of quantities for a CW-item.
    

    > [!NOTE]
    > <P>The <STRONG>Quantity</STRONG> field displays the quantity of the inventory item on the journal line. The <STRONG>CW unit</STRONG> field displays the identification code of the unit of the CW-enabled item.</P>



6.  In the **Selected quantity** field, enter the quantity of units that is selected for processing. If you modify the value of the **Selected quantity** field for CW-enabled items, you must make sure that values are in the range of minimum and maximum quantities that you specify for the CW item. You receive an error message if you enter a value that is outside this range.

## See also

[Create and validate journals and journal lines](create-and-validate-journals-and-journal-lines.md)

[(RUS) Create customs journal (form)](https://technet.microsoft.com/library/jj853226\(v=ax.60\))

  


