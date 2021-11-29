---
title: (IND) About correcting a sales order packing slip before posting an invoice
TOCTitle: (IND) About correcting a sales order packing slip before posting an invoice
ms:assetid: 89be5f86-d277-41b9-b333-8b69b0d45dce
ms:mtpsurl: https://technet.microsoft.com/library/JJ678003(v=AX.60)
ms:contentKeyID: 49385964
author: Khairunj
ms.date: 05/01/2014
mtps_version: v=AX.60
f1_keywords:
- invoice
- order
- slip
- India
- IND
- packing
audience: Application User
ms.search.region: India
---

# (IND) About correcting a sales order packing slip before posting an invoice 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

When excise tax is calculated for the original packing slip for a sales order, the excise registers are updated for the packing slip based on the invoice date, delivery date, or document date. If the excise registers are updated for the packing slip based on the delivery date, you can correct or cancel a packing slip without creating a new packing slip ID.


> [!NOTE]
> <P>To view or change how excise registers are updated for packing slips, do the following:</P>
> <UL>
> <LI>
> <P>Click <STRONG>General ledger</STRONG> &gt; <STRONG>Setup</STRONG> &gt; <STRONG>General ledger parameters</STRONG>. In the left pane, click <STRONG>Sales tax</STRONG>, and then, on the <STRONG>General</STRONG> FastTab, see the values in the <STRONG>Vendor calculation date type</STRONG> and <STRONG>Customer calculation date type</STRONG> fields.</P></LI></UL>



When you correct a packing slip for a sales order, two lines are added to the corresponding excise registers. One line includes the quantity that was reversed and the excise tax for the original packing slip. The other line includes the updated quantity and recalculated excise tax. The original, reversed, and corrected values must each have a unique ID in the excise registers.

The following examples illustrate changes that are made in the excise registers depending on the settings that are selected for an item line on the packing slip.

## Example 1

If the **Excise record type** field for the item line is set to **RG23A** or **RG23C**, the following changes are made to the excise register:

  - A new line is created in Part-I and Part-II of the corresponding excise register, either **RG23A** or **RG23C**. This line includes the reversed quantity for the original packing slip.

  - Another line is created in Part-I and Part II of the corresponding excise register, either **RG23A** or **RG23C**. This line includes the recalculated excise tax for the quantity on the corrected packing slip.

## Example 2

If the **Excise record type** field for the item line is set to **RG23D**, the following changes are made to the excise register:

  - The excise tax is recalculated for the quantity on the corrected packing slip.

  - A new line is created in the **RG23D** excise register to reverse the quantity and excise tax for the original packing slip quantity.

  - Another line is created in the **RG23D** excise register to reflect the corrected quantity on the packing slip and the recalculated excise tax.

## Example 3

If the **DSA** check box is selected for the item line, the following changes are made to the excise register. For this example, the **Excise record type** field is set to **None**.

  - The excise tax is recalculated for the quantity on the corrected packing slip.

  - A new line is created in the **DSA** register to reverse the quantity and excise tax for the original packing slip.

  - Another line is created in the **DSA** register to reflect the corrected quantity on the packing slip and the recalculated excise tax.

  


