---
title: (HUN) Create a customer advance invoice for a free text invoice
TOCTitle: (HUN) Create a customer advance invoice for a free text invoice
ms:assetid: a63df3e8-98dd-4f60-bd36-d459cf563410
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ664343(v=AX.60)
ms:contentKeyID: 49385431
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# (HUN) Create a customer advance invoice for a free text invoice [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

The advance invoice is a document created for a customer that states the amount to be prepaid on a sales order. Usually, the prepayment must be made before the order is processed. The advance invoice is not an accounting or tax document.

You can create an advance invoice for a free text invoice or reassign an existing advance invoice to a free text invoice as long as no prepayments are linked to the advance invoice.

1.  Click **Accounts receivable** \> **Common** \> **Advance invoices** \> **All advance invoices**. To open an existing advance invoice, double-click the advance invoice. To create a new advance invoice, on the **Action pane**, on the **Advance invoice** tab, click **Advance invoice**
    
    On the **Action pane**, in the **Related information** group, click **Free text invoice** in the **Advance invoice** form to open the **Select free text invoice for advance invoice** form where you can link the free text invoice to the advance invoice. You must create the advance invoice and the free text invoice independently.

2.  Click **Post** to post the advance invoice.

3.  On the **Action pane**, in the **Actions** group, click **Status** to open the **Change the status of an advance invoice** form, and then select the status of the advance invoice in the **New status** field.
    

    > [!NOTE]
    > <P>You can change the status of the advance invoice at any time. However, you cannot process closed advance invoices in transactions.</P>



## VAT on advance invoices

According to Czech legislation, companies must record VAT on prepayments from customers even though the sale has not been completed. You can add a line containing VAT specifications, taken from sales order lines, to an advance invoice for posting VAT from a prepayment.


> [!NOTE]
> <P>The VAT specifications are copied to the advance invoice lines only if the <STRONG>Type of tax</STRONG> field in the <STRONG>Sales tax codes</STRONG> form is set to <STRONG>Standard VAT</STRONG> or <STRONG>Reduced VAT</STRONG>. If the <STRONG>Type of tax</STRONG> field contains a different value, then the line is copied to the advance invoice as if it contains a zero VAT amount.</P>


  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

