---
title: Place an Accounts payable payment on hold
TOCTitle: Place an Accounts payable payment on hold
ms:assetid: 19d282bb-4276-4e77-926d-3a6fc446b36a
ms:mtpsurl: https://technet.microsoft.com/library/Hh208452(v=AX.60)
ms:contentKeyID: 36056116
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- vendor
- payments
- public sector
- invoice
- accounts payable
- hold
- release date
audience: Application User
ms.search.region: Global
---

# Place an Accounts payable payment on hold 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can put Accounts payable payments on hold until a specified date, or indefinitely. You can hold all payments for a specific vendor or invoice. You might want to hold all payments for a vendor until a dispute is resolved, or you might want to hold the payment for an invoice until funds become available.

## Hold payments for a vendor

1.  Click **Accounts payable** \> **Common** \> **Vendors** \> **All vendors**.

2.  Select a vendor account.

3.  On the **Action Pane**, click **On hold**.

4.  In the form that is displayed, select **Payment** in the **Vendor hold** field.

5.  In the **Vendor hold release date** field, enter the date when the payment hold should end, and payments should again be made to the vendor. If you do not enter a date, the payment hold lasts indefinitely.

## Hold payments for a vendor invoice

1.  Click **Accounts payable** \> **Common** \> **Vendor invoices** \> **Pending vendor invoices**. Double-click an invoice or click **Invoice** on the **Action Pane** to create a new invoice.

2.  In the **Vendor invoice** form, on the **Action Pane**, click **Header view** to view the complete header information for the invoice.

3.  In the **Invoice payment release date** field on the **Approval** FastTab, enter the date until which the invoice payment will be on hold. If you enter a date, the payment will not be generated until that date. This field is available only if the invoice is approved.
    
    To remove a payment hold, clear the value in this field. Any user can clear the payment release date, regardless of which user entered it.

4.  Enter an optional comment in the **Release date comment** field.

## See also

[Key tasks: Vendor payments and settlements](key-tasks-vendor-payments-and-settlements.md)

[Key tasks: Vendor invoices](key-tasks-vendor-invoices.md)

  


