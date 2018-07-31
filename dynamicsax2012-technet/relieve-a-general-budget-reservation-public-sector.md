---
title: Relieve a general budget reservation (Public sector)
TOCTitle: Relieve a general budget reservation (Public sector)
ms:assetid: 99336a75-c941-4d88-b791-bab15db9a354
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn792458(v=AX.60)
ms:contentKeyID: 65205503
ms.date: 05/05/2015
mtps_version: v=AX.60
f1_keywords:
- public sector
- budget reservation
- budget reservations
- general budget reservation
- general budget reservations
- relief of a budget reservation
- relief of a general budget reservation
- relief of budget reservations
audience: Application User
ms.search.region: Denmark, France
---

# Relieve a general budget reservation (Public sector) 


_**Applies To:** Microsoft Dynamics AX 2012 R3_

After a general budget reservation has been posted, it is relieved by one of the source documents that reference it.


> [!NOTE]
> <P>General budget reservations are available only if the <STRONG>Public Sector</STRONG> configuration key is selected and if Microsoft Dynamics AX 2012 R3 Cumulative Update 8 is installed with the following hotfix: KB3047235</P>



There are three main ways to consume or relieve a general budget reservation:

  - **Purchase order** - Reference the general budget reservation directly on a purchase order line. The reservation is relieved, or consumed, when the purchase order is confirmed. No purchase agreement is involved. To do this, create a purchase order according to your usual process. This might also involve using a purchase requisition. When you add a line to the purchase order, select the general budget reservation to use for the purchase order.

  - **Vendor invoice** - Reference the general budget reservation directly on a vendor invoice. You can assign a purchase agreement on the header of the invoice, but no purchase order is involved. The reservation is relieved when the invoice is posted. To do this, create a vendor invoice according to your usual process. When you add a line to the invoice, select the general budget reservation to use for the invoice.

  - **Purchase requisition** – Reference a general budget reservation line in a purchase requisition. The reservation is relieved when funds are released from the requisition. To do this, specify the purchase requisition on the budget reservation line when you create the reservation.
    

    > [!NOTE]
    > <P>Purchase requisitions require workflow. For more information about creating a purchase requisition workflow, see <A href="overview-of-a-purchase-requisition-workflow.md">Overview of a purchase requisition workflow</A>. Also see <A href="set-up-general-budget-reservation-workflows-public-sector.md">Set up general budget reservation workflows (Public sector)</A>.</P>




> [!NOTE]
> <P>You can also reference a general budget reservation on a purchase agreement.</P>
> <P>After you post or confirm a document that references a general budget reservation, the budget reservation balance reflects the relieving amount. If you edit, cancel, or finalize the referencing document, the relieved amount shown is not reduced or removed; there is no way to return a relieved amount to the balance on the referencing document.</P>



For more information about how to create a purchase order, see [Create a purchase order](create-a-purchase-order.md). For more information about how to create a purchase requisition, see [Key tasks: Create and submit a purchase requisition](key-tasks-create-and-submit-a-purchase-requisition.md). For more information about how to create invoices, see [Key tasks: Vendor invoices](key-tasks-vendor-invoices.md).

## Relieve a general budget reservation

To relieve a general budget reservation, use the following steps.

1.  Do one of the following:
    
      - Click **Procurement and sourcing \> Common \> Purchase orders \> All purchase orders**.
    
      - Click **Procurement and sourcing \> Common \> Purchase requisitions \> All purchase requisitions**.
    
      - Click **Accounts payable \> Common \> Vendor invoices\> Pending vendor invoices**.

2.  Select a document, and then, on the **Action Pane**, click **Edit**.

3.  Select a line.

4.  In the Action strip, click **Financials**, and then click **Distribute amounts**.
    
    The ledger dimension field on the new accounting distributions (parent and child) is set to the ledger dimension from the budget reservation line accounting distribution.
    
    The reference distribution on the new accounting distributions (parent and child) references the budget reservation line accounting distribution.
    
    For more information about accounting distributions, see [About accounting distributions and subledger journal entries for vendor invoices](about-accounting-distributions-and-subledger-journal-entries-for-vendor-invoices.md).

## See also

[About general budget reservations (Public sector)](about-general-budget-reservations-public-sector.md)

[Create a general budget reservation (Public sector)](create-a-general-budget-reservation-public-sector.md)

  


