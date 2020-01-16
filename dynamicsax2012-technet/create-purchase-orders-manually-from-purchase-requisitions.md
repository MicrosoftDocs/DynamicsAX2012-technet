---
title: Create purchase orders manually from purchase requisitions
TOCTitle: Create purchase orders manually from purchase requisitions
ms:assetid: 95726644-14a6-4088-ad3a-e2054fe96046
ms:mtpsurl: https://technet.microsoft.com/library/Gg232214(v=AX.60)
ms:contentKeyID: 36058621
author: Khairunj
ms.date: 03/25/2015
mtps_version: v=AX.60
f1_keywords:
- purchase orders
- purchase
- purchase requisitions
audience: Application User
ms.search.region: Global
---

# Create purchase orders manually from purchase requisitions 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use this procedure to create purchase orders manually from approved purchase requisitions.

If you are in the public sector and will be using general budget reservations, see also [About general budget reservations (Public sector)](about-general-budget-reservations-public-sector.md).


> [!NOTE]
> <P>General budget reservations are available only if the <STRONG>Public Sector</STRONG> configuration key is selected and if Microsoft Dynamics AX 2012 R3 Cumulative Update 8 is installed with the following hotfix: KB3047235</P>



If a purchase requisition has already been referenced by a general budget reservation, it will no longer be available for manual purchase order creation.

A purchase order is created for each currency, vendor, or legal entity that is identified on the purchase requisition lines. For example, if a purchase requisition has two lines, and each line has a different vendor, currency, or legal entity, two purchase orders are created. Also, depending on how purchasing policies are configured for your organization, separate purchase orders can be created if the purchase requisition lines have different requesters, line types, or procurement categories.


> [!NOTE]
> <P>Public sector entities that use commitments to manage budget reservations cannot create purchase orders from purchase requisitions. For more information, see <A href="fra-about-commitments-public-sector.md">(FRA) About commitments (Public sector)</A>.</P>



## Create a purchase order manually from a purchase requisition

1.  Click **Procurement and sourcing** \> **Common** \> **Purchase requisitions** \> **Release approved purchase requisitions**.
    
    This form lists all the approved purchase requisition lines for which no purchase order lines have been created. The list is sorted by consolidation status, purchase requisition ID and line.
    

    > [!NOTE]
    > <P>Purchase requisition lines that have been added to an open consolidation opportunity cannot be added to a purchase order from the <STRONG>Release approved purchase requisitions</STRONG> list page. Instead, they must be added to a purchase order from the consolidation opportunity. For more information about how to create a consolidation opportunity, see <A href="key-tasks-consolidate-purchase-requisitions.md">Key tasks: Consolidate purchase requisitions</A>.</P>



2.  Select the purchase requisition lines that you want to create a purchase order for.

3.  On the **Action Pane**, in the **New** group, click **Purchase order**.

An Infolog message appears and lists the purchase orders that have been created. The requisition lines are removed from the **Release approved purchase requisitions** form.

All information on the purchase requisition lines is copied to the purchase order lines. However, if price information such as a trade agreement or a base price is available, some of the amounts might be recalculated based on policy rules for price and discount transfers. The following table describes whether line prices and discounts are recalculated when the purchase order is created.

<table>
<colgroup>
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Purchase requisition line type</p></th>
<th><p>Line refers to a request for quotation or demand consolidation</p></th>
<th><p>Pricing information is recalculated or copied</p></th>
<th><p>Policy rule exists</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Internal catalog item</p></td>
<td><ul>
<li><p>Yes</p></li>
<li><p>No</p></li>
</ul></td>
<td><ul>
<li><p>Copied</p></li>
<li><p>Recalculated if no policy rule exists for transfer of prices and discounts.</p></li>
</ul></td>
<td><ul>
<li><p>No impact</p></li>
<li><p>The policy rule controls whether the price information from the requisition should always be transferred or if it is only transferred when no other price can be retrieved. For information about how to set up policy rules for transfer of prices and discounts, see <a href="set-up-rules-for-demand-consolidation-and-for-creating-purchase-orders.md">Set up rules for demand consolidation and for creating purchase orders</a>.</p></li>
</ul></td>
</tr>
<tr class="even">
<td><p>External catalog item</p></td>
<td><ul>
<li><p>Not applicable</p></li>
</ul></td>
<td><ul>
<li><p>Copied</p></li>
</ul></td>
<td><ul>
<li><p>No impact</p></li>
</ul></td>
</tr>
<tr class="odd">
<td><p>Non-catalog item</p></td>
<td><ul>
<li><p>Yes</p></li>
<li><p>No</p></li>
</ul></td>
<td><ul>
<li><p>Copied</p></li>
<li><p>Copied</p></li>
</ul></td>
<td><ul>
<li><p>No impact</p></li>
<li><p>No impact</p></li>
</ul></td>
</tr>
</tbody>
</table>


## See also

[Release approved purchase requisition (form)](https://technet.microsoft.com/library/hh242658\(v=ax.60\))

[Purchase order creation and demand consolidation rule (form)](https://technet.microsoft.com/library/hh209698\(v=ax.60\))

[Set up rules for demand consolidation and for creating purchase orders](set-up-rules-for-demand-consolidation-and-for-creating-purchase-orders.md)

[Key tasks: Consolidate purchase requisitions](key-tasks-consolidate-purchase-requisitions.md)

[Create a request for quotation from a purchase requisition](create-a-request-for-quotation-from-a-purchase-requisition.md)

[Relieve a general budget reservation (Public sector)](relieve-a-general-budget-reservation-public-sector.md)

  


