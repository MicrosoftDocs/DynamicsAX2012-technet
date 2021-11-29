---
title: (CZE) Create a customer advance invoice
TOCTitle: (CZE) Create a customer advance invoice
ms:assetid: 223099c3-0e43-4c1c-9583-794b464111fe
ms:mtpsurl: https://technet.microsoft.com/library/JJ677482(v=AX.60)
ms:contentKeyID: 49384784
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Czech Republic
---

# (CZE) Create a customer advance invoice 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

An advance invoice is a document that you can create for a customer. The advance invoice states the amount that must be prepaid on a sales order. Usually, the prepayment must be made before the order is processed. The advance invoice is not an accounting document or a tax document, but is used only as the basis for prepayments. You can create an advance invoice for a free text invoice. You can also reassign an existing advance invoice to a free text invoice, provided that no prepayments are linked to the advance invoice.

You can create an advance invoice for a free text invoice. You can also reassign an existing advance invoice to a free text invoice, provided that no prepayments are linked to the advance invoice.

1.  Click **Accounts receivable** \> **Common** \> **Advance invoices** \> **All advance invoices**. To open an existing advance invoice, double-click the advance invoice. To create a new advance invoice, on the **Action Pane**, on the **Advance invoice** tab, click **Advance invoice**.

2.  Enter the required information.

3.  Click **Post** to post the advance invoice.

4.  On the **Action Pane**, in the **Actions** group, click **Status** to open the **Change the status of an advance invoice** form. Then, in the **New status** field, select the status of the advance invoice.
    

    > [!NOTE]
    > <P>You can change the status of the advance invoice at any time. However, you cannot process advance invoices in transactions if the advance invoices have been closed.</P>



## VAT on advance invoices

According to Czech legislation, companies must record value-added tax (VAT) on prepayments from customers, even though the sale has not been completed. You can add a line that contains VAT specifications to an advance invoice, so that you can post VAT from a prepayment. The VAT specifications are taken from sales order lines.


> [!NOTE]
> <P>The VAT specifications are copied to the advance invoice lines only if the <STRONG>Type of tax</STRONG> field in the <STRONG>Sales tax codes</STRONG> form is set to <STRONG>Standard VAT</STRONG> or <STRONG>Reduced VAT</STRONG>. If the <STRONG>Type of tax</STRONG> field is set to another value, the line is copied to the advance invoice as if the VAT amount is 0 (zero).</P>



## See also

[(CZE) Create a customer advance invoice for a free text invoice](cze-create-a-customer-advance-invoice-for-a-free-text-invoice.md)

[(CZE) Payment proposal from advance sales invoice](cze-payment-proposal-from-advance-sales-invoice.md)

  


