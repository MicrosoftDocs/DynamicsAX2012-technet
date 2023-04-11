---
title: (POL) Create a free text invoice
TOCTitle: (POL) Create a free text invoice
ms:assetid: f42c2916-fa81-42bb-b17c-c73991b23c24
ms:mtpsurl: https://technet.microsoft.com/library/JJ711330(v=AX.60)
ms:contentKeyID: 49387148
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Poland
---

# (POL) Create a free text invoice 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

A free text invoice is an invoice that is not attached to a sales order. A free text invoice contains a header, and one or more lines for items or services that are not tracked in inventory. Use a free text invoice for sales that do not require a sales order or packing slip. For example, you can use a free text invoice for a consulting fee or services fee, or for a miscellaneous fee for an event reimbursement.

For more information about free text invoices, see [Key tasks: Free text invoices](key-tasks-free-text-invoices.md).

### Create a simple free text invoice

1.  Click **Accounts receivable** \> **Common** \> **Free text invoices** \> **All free text invoices**.

2.  On the **Action Pane**, in the **New** group, click **Free text invoice** to open the **Free text invoice** form.

3.  On the **Action Pane**, click **Header view** to view the free text invoice in the header view.

4.  On the **Free text invoice header** FastTab, select the customer account. The default information for the customer account is displayed.

5.  In the **Date of VAT register** field, select the transaction date for the value-added tax (VAT) register period. In the **Sales date** field, select the date of the sales transaction.

6.  On the **Action Pane**, click **Line view**.

7.  In the **Invoice lines** grid, follow these steps:
    
      - Enter a description for the invoice line, and enter the PKWiU code.
    
      - Select the sales tax and item sales tax groups.
    
      - Select the main account, and enter the quantity and unit price.

8.  In the **Service tariff number** field, select the service tariff number that is used when the VAT for the invoice is reported, if the customer is located outside Poland.

9.  On the **Line details** FastTab, enter any additional information.

10. To save your changes without posting the invoice, click **Close**.

  


