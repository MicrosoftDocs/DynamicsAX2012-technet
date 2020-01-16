---
title: About purchase order encumbrances
TOCTitle: About purchase order encumbrances
ms:assetid: 80dd88b0-7397-42e6-aaa2-9b634a67c5c5
ms:mtpsurl: https://technet.microsoft.com/library/Hh209307(v=AX.60)
ms:contentKeyID: 36058354
ms.date: 03/25/2015
mtps_version: v=AX.60
f1_keywords:
- budget control
- enable encumbrance process
- pre-encumbrance
- encumbrance
audience: Application User
ms.search.region: Global
---

# About purchase order encumbrances 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

An encumbrance is a reservation of budget funds that are set aside to make sure that actual expenditures do not exceed the available budget. If the encumbrance process is enabled, you can create purchase order encumbrances that are recorded in the general ledger when a purchase order is confirmed. Encumbered amounts can then be spent when vendor invoices that reference a purchase order are confirmed. Encumbered amounts on a purchase order are relieved when a vendor invoice is confirmed to spend all or part of the encumbered amount. Relieved amounts are subtracted from the amount of the purchase order encumbrance.

A pre-encumbrance is a request to reserve budget funds for planned expenditures. The funds have been requested, but have not yet been approved for a purchase order. If the pre-encumbrance process is enabled, you can create purchase requisitions with a pre-encumbered amount for the planned expenditure. The pre-encumbered amounts are then recorded in the general ledger. For information about how to create a purchase requisition and reserve budget funds for a pre-encumbrance, see [Purchase requisitions (list page)](https://technet.microsoft.com/library/hh227485\(v=ax.60\)).

When purchase requisitions are approved, you can create purchase orders for the requested amounts. When you create and confirm a purchase order for the pre-encumbered amount on a purchase requisition, a purchase order encumbrance is created for that amount. The pre-encumbered amount is then automatically relieved. This avoids having a budget reservation be counted two times in the general ledger, as both a pre-encumbrance and an encumbrance.

If you are in the public sector and use general budget reservations, see [Encumber a general budget reservation (Public sector)](encumber-a-general-budget-reservation-public-sector.md) and [About general budget reservations (Public sector)](about-general-budget-reservations-public-sector.md).


> [!NOTE]
> <P>General budget reservations are available only if the <STRONG>Public Sector</STRONG> configuration key is selected and if Microsoft Dynamics AX 2012 R3 Cumulative Update 8 is installed with the following hotfix: KB3047235</P>



For information about how to create a purchase order from a purchase requisition, see [Purchase requisition consolidation (form)](https://technet.microsoft.com/library/hh227441\(v=ax.60\)). For information about how to enable the encumbrance and pre-encumbrance processes, see [Encumber purchase orders](encumber-purchase-orders.md).

## Examples

**Example 1: Encumbrance processing and pre-encumbrance processing are both enabled**

A department manager in your organization creates a purchase requisition for expected purchases for the department. One of the lines in the purchase requisition is for 12,000.00 in new office furniture. The request is later approved and a purchase order is created that has a line to cover the 12,000.00 cost. The 12,000.00 pre-encumbrance on the purchase requisition is automatically relieved when the new purchase order is confirmed. The relieved amount on the purchase requisition line is then replaced by a 12,000.00 encumbrance on the purchase order.

**Example 2: Encumbrance processing is enabled, but pre-encumbrance processing is not**

The purchasing agent for your organization creates a purchase order for a 10,000.00 contract with an architect who is designing an addition to a building. No requisition is created. An encumbrance for that amount is created when the purchase order is confirmed.

## See also

[Encumber purchase orders](encumber-purchase-orders.md)

  


