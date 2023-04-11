---
title: (POL) Post and print a sales order or a free text invoice
TOCTitle: (POL) Post and print a sales order or a free text invoice
ms:assetid: c73f0a4d-e0e8-46ca-82c3-c66501ebc67a
ms:mtpsurl: https://technet.microsoft.com/library/JJ711263(v=AX.60)
ms:contentKeyID: 49387081
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Poland
---

# (POL) Post and print a sales order or a free text invoice 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

To post a business document, first generate an invoice, and then post it by using the **Posting invoice** form. You can then send the information to the printer in the proper format.

## Post and print a sales order

1.  Click **Accounts receivable** \> **Common** \> **Sales orders** \> **All sales orders**.

2.  Open the record that is ready for invoicing.

3.  In the **Sales order** form, in **Header** view, on the **Setup** FastTab, verify that **Fiscal document** is selected in the **Printed document** field.
    
    If **Fiscal document** is not selected, select to edit the sales order record, and then update the **Printed document** field.

4.  On the **Action Pane**, on the **Invoice** tab, in the **Generate** group, click **Invoice** to generate an invoice for the sales order.

5.  In the **Posting invoice** form, on the **Parameters** tab, in the **Printed document** field, select **Fiscal document**.

6.  On the **Setup** tab, in the **Date of VAT register** field, enter the transaction date for the value-added tax (VAT) register period.

7.  Click **OK**.

## Post and print a free text invoice

1.  Click **Accounts receivable** \> **Common** \> **Free text invoices** \> **All free text invoices**.

2.  Open the record that is ready for invoicing.

3.  In the **Free text invoice** form, in **Header** view, on the **General** FastTab, verify that **Fiscal document** is selected in the **Printed document** field.
    
    If **Fiscal document** is not selected, select to edit the sales order record, and then update the **Printed document** field.

4.  On the **Action Pane**, click **Post** to post the free text invoice.

5.  In the **Posting invoice** form, on the **General** tab, in the **Printed document** field, select **Fiscal document**. Click **OK**.

## See also

[(POL) Sales orders (modified form)](https://technet.microsoft.com/library/jj678144\(v=ax.60\))

  


