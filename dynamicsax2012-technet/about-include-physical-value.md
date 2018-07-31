---
title: About Include physical value
TOCTitle: About Include physical value
ms:assetid: 224750d2-dcf3-49de-bfcb-ff315e782cca
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Gg230988(v=AX.60)
ms:contentKeyID: 36056172
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# About Include physical value 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The **Include physical value** check box on the **Inventory model** FastTab of the **Item model groups** form is used to specify whether physically updated transactions are factored into the calculation of the running average cost price for an item.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p><strong>Include physical value</strong> check box status</p></th>
<th><p>Result</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Selected</p></td>
<td><p>Both physically updated transactions and financially updated transactions are used to calculate the running average cost price.</p></td>
</tr>
<tr class="even">
<td><p>Cleared</p></td>
<td><p>Only financially updated transactions are used to calculate the running average cost price.</p></td>
</tr>
</tbody>
</table>


The **Include physical value** check box produces slightly different results, depending on the inventory model you use.

  - If you select the **Include physical value** check box when you use the FIFO, LIFO, or LIFO Date inventory model, inventory close also makes adjustments to physically updated transactions.

  - If you do not select the **Include physical value** check box when you use these inventory models, inventory close makes settlements only to financially updated transactions.

  - When you use the weighted average or weighted average date inventory model, inventory close settles only financially updated transactions, regardless of whether you select the **Include physical value** check box.

## Example

You have selected the **Include physical value** check box and receive the following purchase orders:

  - Purchase order for a quantity of 2; cost price is USD 10.00; packing slip updated

  - Purchase order for a quantity of 3; cost price is USD 12.00; invoice updated

In this case, the running average cost price will be USD 11.20, because both physically and financially updated transactions are used to calculate the cost price.

## Example

You have not selected the **Include physical value** check box, and the cost price on the item setup is USD 10.00. You receive the following purchase order:

  - Purchase order for a quantity of 20; cost price is USD 12.00; packing slip updated

When a sales order is posted, the posted cost amount is USD 10.00, because the running average cost price will not include physically posted transactions.


> [!NOTE]
> <P>For comparison, if <STRONG>Include physical value</STRONG> had been selected for this item, the sales order would have been posted with a cost amount of USD 12.00.</P>



## See also

[About running average cost price](about-running-average-cost-price.md)

[Specify an inventory model for inventory close](specify-an-inventory-model-for-inventory-close.md)

[Item model groups (form)](https://technet.microsoft.com/en-us/library/aa577092\(v=ax.60\))

  


