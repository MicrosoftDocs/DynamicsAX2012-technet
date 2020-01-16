---
title: (HUN) Create and post a free text invoice with a specific VAT register date
TOCTitle: (HUN) Create and post a free text invoice with a specific VAT register date
ms:assetid: 3e2a886b-d272-4770-a876-30a4953b5ec1
ms:mtpsurl: https://technet.microsoft.com/library/JJ664266(v=AX.60)
ms:contentKeyID: 49385355
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- free text invoice
- VAT register date
audience: Application User
ms.search.region: Hungary
---

# (HUN) Create and post a free text invoice with a specific VAT register date 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

When you post an outgoing invoice, you can select a date for reporting value-added tax (VAT) that differs from the transaction date on invoice lines. Use this procedure to create and post a free text invoice that has a specific VAT register date.

1.  Click **Accounts receivable** \> **Common** \> **Free text invoices** \> **All free text invoices**. On the **Action Pane**, in the **New** group, click **Free text invoice**.

2.  In the **Free text invoice** form, in the **Date of VAT register** field, select the date on which to report the invoice VAT.

3.  Enter the required invoice details. For more information, see [(HUN) Free text invoice (modified form)](https://technet.microsoft.com/library/jj664332\(v=ax.60\)) and [Create free text invoices](create-free-text-invoices.md).

4.  After you enter the invoice lines to post, on the **Action Pane**, click **Post**.

5.  In the **Post free text invoice** form, select posting options, and then click **OK** to post the invoice.

When you post an invoice that includes outgoing tax that will be posted on a future date, the amount of VAT is posted to a temporary account. Later, on the VAT register date that you selected, it is posted to the VAT account.

## See also

[(EEUR) Free text invoice (modified form)](https://technet.microsoft.com/library/jj910975\(v=ax.60\))

[(HUN) Create a free text invoice that includes the VAT exchange rate](hun-create-a-free-text-invoice-that-includes-the-vat-exchange-rate.md)

  


