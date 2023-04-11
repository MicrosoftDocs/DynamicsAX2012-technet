---
title: About vendor payment retention for projects
TOCTitle: About vendor payment retention for projects
ms:assetid: 75a23667-5997-4c42-90d9-315ec29e6943
ms:mtpsurl: https://technet.microsoft.com/library/Hh209239(v=AX.60)
ms:contentKeyID: 36058172
author: tonyafehr
ms.author: daxcpft
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- project add-in
- retention percentage
- vendor retention terms
- vendor retention
audience: Application User
ms.search.region: Global
---

# About vendor payment retention for projects 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Your organization might want to retain a portion of payments to vendors who work on projects for your organization. For example, you might want to make sure that the products from a subcontract vendor meet your expectations before you pay the vendor.

When you negotiate purchases for projects with vendors, you can specify the vendor retention terms that include the percentage or amount to retain. As a vendor delivers items and services, you deduct the specified retention percentage or amount from your payment to the vendor. When the project is completed or reaches an interim stage specified in the contract with the vendor, you release the retained amount and create a payment to the vendor.

Before you can set up retention terms for a project, you must complete the following prerequisites:

  - Set up a number sequence to generate the retention term identification number automatically when you create vendor retention terms and documents. For more information about how to set up numbering sequences, see [Project management and accounting parameters (form)](https://technet.microsoft.com/library/aa599440\(v=ax.60\)).

  - Select general ledger accounts for vendor retention transactions. For more information, see [Accounts for automatic transactions (form)](https://technet.microsoft.com/library/aa548973\(v=ax.60\)).

  - Set up one or more vendor retention terms, which you use to define the thresholds for retaining vendor payments and releasing the payments. For more information, see [Vendor retention terms (form)](https://technet.microsoft.com/library/hh227442\(v=ax.60\)).

## Example

The following example shows how a percentage of a vendor invoice amount is retained based on the percentage that is complete for a project.

Create a purchase order for 10 units of an item. The cost per unit is USD 100, and the total amount of the purchase order is 1,000. The number of units will be delivered in three stages with the following schedule:

  - Phase 1: 5 units, or 50 percent of the project

  - Phase 2: 3 units, or 80 percent of the project in total

  - Phase 3: 2 units, or 100 percent of the project

The following table lists the retention terms.

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Percentage of units delivered</p></th>
<th><p>Percentage to retain</p></th>
<th><p>Percentage to release</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>50%</p></td>
<td><p>20%</p></td>
<td><p>0%</p></td>
</tr>
<tr class="even">
<td><p>80%</p></td>
<td><p>10%</p></td>
<td><p>10%</p></td>
</tr>
<tr class="odd">
<td><p>100%</p></td>
<td><p>0%</p></td>
<td><p>100%</p></td>
</tr>
</tbody>
</table>


The transactions result in the following amounts:

  - Phase 1:
    
      - The amount payable is 5 x 100, or 500.
    
      - 20 percent of the amount, or 100, is retained and will be released at a later stage.
    
      - The amount that is paid to the vendor is 400.

  - Phase 2:
    
      - The amount payable is 3 x 100, or 300.
    
      - 10 percent of the amount, or 30, is retained.
    
      - 10 percent of the 100 that was retained in Phase 1, or 10, is released.
    
      - The amount that is paid to the vendor is 280. This amount consists of 300 less the 30 retention plus the 10 that was released from the Phase 1 retention.

  - Phase 3:
    
      - The amount payable is 2 x 100, or 200.
    
      - No amount is retained.
    
      - The amount that is released is 120. This amount consists of the 100 that was retained in Phase 1, less the 10 from Phase 1 that was released in Phase 2, plus the 30 that was retained in Phase 2.
    
      - The amount that is paid to the vendor is 320. This amount consists of the retained amount of 120 plus the 200 for completion of Phase 3.

The total amount that is paid to the vendor after the three phases are completed is 1,000, which is the total amount of the purchase order (400 + 280 + 320).

## See also

[Vendor invoices with retention (form)](https://technet.microsoft.com/library/hh209594\(v=ax.60\))

[Vendor retention terms (form)](https://technet.microsoft.com/library/hh227442\(v=ax.60\))

[Inquiry for vendor retained payments (form)](https://technet.microsoft.com/library/hh209466\(v=ax.60\))

  


