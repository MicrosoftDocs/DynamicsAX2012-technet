---
title: (POL) Create a customer advance invoice for a free text invoice
TOCTitle: (POL) Create a customer advance invoice for a free text invoice
ms:assetid: 6b9150cd-0fae-43dc-a67e-8f85cabf7cb3
ms:mtpsurl: https://technet.microsoft.com/library/JJ678232(v=AX.60)
ms:contentKeyID: 49386954
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Poland
---

# (POL) Create a customer advance invoice for a free text invoice 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

An advance invoice is a document that you can create for a customer. The advance invoice states the amount that must be prepaid on a sales order. Usually, the prepayment must be made before the order is processed. The advance invoice is not an accounting document or a tax document, but is used only as the basis for prepayments..

You can create an advance invoice for a free text invoice. You can also reassign an existing advance invoice to a free text invoice, provided that no prepayments are linked to the advance invoice

1.  Click **Accounts receivable** \> **Common** \> **Advance invoices** \> **All advance invoices**. To open an existing advance invoice, double-click the advance invoice. To create a new advance invoice, on the **Action Pane**, on the **Advance invoice** tab, click **Advance invoice**.

2.  Enter the required information.

3.  Click **Post** to post the advance invoice.

4.  On the **Action Pane**, in the **Actions** group, click **Status** to open the **Change the status of an advance invoice** form. Then, in the **New status** field, select the status of the advance invoice.
    

    > [!NOTE]
    > <P>You can change the status of the advance invoice at any time. However, you cannot process advance invoices in transactions if the advance invoices have been closed.</P>



## VAT on advance invoices


> [!NOTE]
> <P>The specifications of value-added tax (VAT) are copied to the advance invoice lines only if the <STRONG>Type of tax</STRONG> field in the <STRONG>Sales tax codes</STRONG> form is set to <STRONG>Standard VAT</STRONG> or <STRONG>Reduced VAT</STRONG>. If the <STRONG>Type of tax</STRONG> field is set to another value, the line is copied to the advance invoice as if the VAT amount is 0 (zero).</P>


  


