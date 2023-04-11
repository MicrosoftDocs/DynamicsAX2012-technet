---
title: About running average cost price
TOCTitle: About running average cost price
ms:assetid: e39f603a-494e-4f98-bee7-58c14066d2fa
ms:mtpsurl: https://technet.microsoft.com/library/Gg243219(v=AX.60)
ms:contentKeyID: 36059724
author: tfehr
ms.author: daxcpft
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# About running average cost price 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The inventory close process in Microsoft Dynamics AX settles issue transactions to receipt transactions based on the inventory valuation method that is selected in the item’s item model group.

However, in the time before inventory close is run, Microsoft Dynamics AX calculates a running average cost price that most of the time is used for posting issue transactions.

Microsoft Dynamics AX estimates this running average cost price for an item by using the following formula:

  - Estimated price = (physical amount + financial amount) / (physical quantity + financial quantity)

The following table indicates when Microsoft Dynamics AX posts inventory transactions using the running average cost price, and when it uses the cost price defined on the item master record instead.

<table>
<colgroup>
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
</colgroup>
<thead>
<tr class="header">
<th><p>IF…</p></th>
<th><p></p></th>
<th><p>Estimated running average cost price</p></th>
<th><p>Cost price defined on the item master</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Both the numerator and denominator are positive</p></td>
<td><p>THEN Microsoft Dynamics AX uses…</p></td>
<td><p>x</p></td>
<td><p>Blank</p></td>
</tr>
<tr class="even">
<td><p>The numerator, denominator, or both are negative</p></td>
<td><p>THEN Microsoft Dynamics AX uses…</p></td>
<td><p>Blank</p></td>
<td><p>x</p></td>
</tr>
<tr class="odd">
<td><p>If the denominator is 0 (zero)</p></td>
<td><p>THEN Microsoft Dynamics AX uses…</p></td>
<td><p>Blank</p></td>
<td><p>x</p></td>
</tr>
</tbody>
</table>


\* Numerator = (physical amount + financial amount); Denominator = (physical quantity + financial quantity)


> [!NOTE]
> <P>If the <STRONG>Include physical value</STRONG> option is not selected for an item, Microsoft Dynamics AX uses zero for both physical amount and physical quantity. For information about this option, see <A href="about-include-physical-value.md">About Include physical value</A>.</P>



## The Pricing Amplification Issue

On rare occasions, you may encounter a pricing amplification scenario that yields overly inflated running average cost price estimates. These are possible when Microsoft Dynamics AX prices several issues before it has sufficient receipts to base a price on.

However, there are steps that you can take to avoid the issue, or to lessen its impact when it does occur, as explained in the following scenario.

**Scenario**

The following transactions occur with an item for which you have applied the **Include physical value** option:

1.  You receive 100 @USD 100.00 financially.

2.  You issue 200 financially.

3.  You receive 101 @USD 202.00 physically.

When you examine the estimated running average cost price for the item, you expected a cost price of USD 1.51. However, you discover an estimated running average of USD 102.00 based on the following formula:

  - Estimated price = \[202 + (-100)\] / \[101 + (-100)\] = 102/1 = 102

This occurs because when 200 items are issued financially in step 2, Microsoft Dynamics AX is forced to price 100 of the items before it has any corresponding receipts. This causes negative inventory. Microsoft Dynamics AX then estimates a unit price of USD 1.00, which we might expect, but when the corresponding 100 receipts come, they are at a unit price of USD 2.00 each.


> [!NOTE]
> <P>Even though the issues create negative inventory, inventory is positive at the time the issue price is computed. That is why the running average cost price is used, instead of the price on the item master.</P>



At this point, Microsoft Dynamics AX has an inventory value offset of USD 100.00. While that offset was built up over 100 pieces, with a unit offset of USD 1.00 each, we now have only one piece in inventory. That offset of USD 100.00 is allocated to this single piece. This results in the overly inflated estimated cost price.


> [!NOTE]
> <P>For comparison, notice that if steps 2 and 3 are reversed in the example, 200 items will be issued at a unit price of USD 1.51, and one piece will remain at a unit price of USD 1.51.</P>



Because this pricing amplification scenario can occur when negative inventory is involved, it is difficult to avoid in the following cases:

  - You must estimate issue prices on the on-hand value and quantity

  - You must adjust the on-hand value and quantity on issues and receipts

  - Your business model allows for sending out, or pricing, more pieces than you have

  - You must accept any receipt value and quantity submitted to you

However, if your business model allows for them, the following practices can help you avoid the negative quantities that make the pricing amplification scenario possible:

  - If you select the **Include physical value** option for an item, clear the **Physical negative inventory** check box on the **Setup** tab in the **Item model groups** form.

  - If you do *not* select the **Include physical value** option for an item, clear the **Financial negative inventory** option on the **Setup** tab in the **Item model groups** form.

Consider also that the maximum offset in your physical inventory value is limited by the number of physical transactions and the difference between physical and financial prices. As long as all physical transactions are eventually updated financially, the physical value cannot rise to extreme levels.

In addition, the amplification effect decreases significantly when the accumulated offset is spread out over several on-hand pieces instead of just one.

## See also

[About inventory close](about-inventory-close.md)

[About physical and financial updates](about-physical-and-financial-updates.md)

[About Include physical value](about-include-physical-value.md)

[Track running average cost per inventory dimension](track-running-average-cost-per-inventory-dimension.md)

  


