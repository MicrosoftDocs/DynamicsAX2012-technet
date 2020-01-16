---
title: Add invoices to payment groups
TOCTitle: Add invoices to payment groups
ms:assetid: a0c16724-de1f-4c19-b3ef-3de67463a3c3
ms:mtpsurl: https://technet.microsoft.com/library/Hh209449(v=AX.60)
ms:contentKeyID: 36058770
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- vendor
- payment
- invoice
- settlement
- settle
- payment group
audience: Application User
ms.search.region: Global
---

# Add invoices to payment groups 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can add invoices to payment groups to group invoices by a common code. If one invoice in the payment group is settled, the other invoices in the group are included in the same settlement.


> [!NOTE]
> <P>Invoices that belong to the same payment group must be settled at the same time. If one invoice in a payment group cannot be settled for any reason, no invoices in the same payment group can be settled. For example, if an invoice in the FIRE payment group is not approved, that invoice must be approved or removed from the payment group before the other invoices in the FIRE payment group can be settled.</P>



## Set up Accounts payable to allow payment groups

1.  Click **Accounts payable** \> **Setup** \> **Accounts payable parameters**.

2.  Click **Invoice** and select the **Activate invoice payment groups** check box.

## Add an invoice to a payment group

1.  Click **Accounts payable** \> **Common** \> **Vendor invoices** \> **Pending vendor invoices**.

2.  On the **Action Pane**, click **Invoice** to create an invoice.
    
    –or–
    
    Click **From purchase order** to create an invoice from selected purchase orders.
    
    –or–
    
    Click **From product receipt** to create an invoice from selected product receipts.

3.  Specify the header details for the invoice, such as the invoice account. Then click **Header view** on the **Action Pane** to view the complete header information for the invoice.

4.  In the **Payment group code** field on the **Payment** FastTab, enter or select the payment group code to use for the invoice. The payment group code can be up to 10 alphanumeric characters long, and it can also include symbols and spaces.

## See also

[Key tasks: Vendor payments and settlements](key-tasks-vendor-payments-and-settlements.md)

[Accounts payable parameters (form)](https://technet.microsoft.com/library/aa596348\(v=ax.60\))

[Vendor invoice (form)](https://technet.microsoft.com/library/hh209644\(v=ax.60\))

  


