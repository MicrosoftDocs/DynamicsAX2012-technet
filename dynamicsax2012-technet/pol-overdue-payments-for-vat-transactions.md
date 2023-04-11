---
title: (POL) Overdue payments for VAT transactions
TOCTitle: (POL) Overdue payments for VAT transactions
ms:assetid: 8bdae5f1-9523-4959-9124-b7b788e991b7
ms:mtpsurl: https://technet.microsoft.com/library/Dn753825(v=AX.60)
ms:contentKeyID: 62486000
author: tonyafehr
ms.date: 06/13/2014
mtps_version: v=AX.60
f1_keywords:
- VAT
- overdue customer debt
- Overdue payment
- Overdue payments
- overdue vendor debt
audience: Application User
ms.search.region: Poland
---

# (POL) Overdue payments for VAT transactions 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

An invoice is considered to be overdue when it is unpaid after the payment due date. When the customer or vendor has not settled the invoice within the specified overdue debt interval period, an invoice becomes an unpaid invoice.

For unpaid invoices, you can correct the output and input debt value-added tax (VAT). If the invoice is paid fully for the overdue debt, you can reverse the corrected VAT transaction. For partially paid invoices, you can reverse the VAT transaction in proportion to the original invoice amount.

## What are the types of payments that I can post overdue debt VAT corrections for?

You can post overdue debt VAT corrections for the following types of payments:

  - Overdue customer or vendor payments for which you have not posted input or output VAT corrections.

  - Overdue customer or vendor payments for which you have posted input or output VAT corrections.

  - Overdue customer or vendor payments for which you have posted input or output VAT corrections, and have received payments from the customer or made payments to the vendor. You can reverse VAT corrections for these payments.

## How can I exclude an invoice that I do not want to include in an overdue debt list?

You can identify customer overdue invoices and vendor overdue invoices based on the parameters that you set in the **Overdue debt journal calculation setup** form. To exclude customer invoices or vendor invoices that you do not want to process for overdue invoice corrections, follow these steps:

1.  In the **Overdue debt VAT** list page, select the journal that you want to correct, and then click **Edit**.

2.  In the **Overdue customer debt VAT lines** form or the **Overdue vendor debt VAT lines** form, select the **Exclude** check box for the invoices that you don’t want to correct.

If the VAT amount for an invoice is already paid, the invoice cannot be excluded from the overdue debt list.

## Can I cancel a posted overdue debt journal?

Yes, you can cancel the most recently posted overdue debt VAT journal. When you cancel the journal, the transactions are reversed. You can view the reversed transactions in the canceled journals. For more information, see [(POL) Create and manage an overdue customer debt VAT journal](pol-create-and-manage-an-overdue-customer-debt-vat-journal.md).

## Where can I view overdue debt VAT transaction information for an invoice?

To view overdue debt VAT information for an invoice, in the **Overdue vendor debt VAT lines** form or the **Overdue customer debt VAT lines** form, select one of the following options:

  - **Counting** – Open the **Counting of overdue vendor debts** form or the **Counting of overdue customer debts** form, where you can view a summary of the vendor or customer overdue debt VAT invoice information.

  - **Vouchers** – Open the **Voucher transactions** form, where you can view the transactions that are created after you post an overdue debt VAT journal or cancel the journal.

  - **Posted sales tax** – Open the **Posted sales tax** form, where you can view the posted sales tax transactions that are based on the sales tax codes from the overdue debt VAT invoices.

## Don't see your question here?

We're working to include as many questions as we can, so that Microsoft Dynamics AX Help will be more useful to people just like you.

Tell us what question you would like to add to this topic. Send email to <adocs@microsoft.com>.

## See also

[(POL) Create and manage an overdue vendor debt VAT journal](pol-create-and-manage-an-overdue-vendor-debt-vat-journal.md)

  


