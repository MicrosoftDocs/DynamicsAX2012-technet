---
title: Add invoices to invoice groups
TOCTitle: Add invoices to invoice groups
ms:assetid: bd9b8868-b6e0-4792-b7f1-134c3eda27c4
ms:mtpsurl: https://technet.microsoft.com/library/Hh242778(v=AX.60)
ms:contentKeyID: 36059157
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- groups
- public sector
- invoice
- invoice groups
audience: Application User
ms.search.region: Global
---

# Add invoices to invoice groups 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can add invoices to an invoice group so that you can find and update invoices that are grouped together, without using a query.

### Set up Accounts payable to allow invoice groups

1.  Click **Accounts payable** \> **Setup** \> **Accounts payable parameters**.

2.  Click **Invoice** and select **Use invoice groups for this company**.

3.  In the **Default code for invoice groups** field, select the value to use as the default group code for new invoices: **User name**, **Date**, or **Custom**. For example, select **User name** to automatically group new invoices by the name of the user who created them. Users can change the code on individual invoices.

4.  In the **Custom code for invoice groups** field, enter a custom group code to use for new invoices. The code can be up to 10 alphanumeric characters long, and it can also include symbols and spaces. This field is available only if **Custom** is selected in the **Default code for invoice groups** field.

5.  In the **Custom code for web service invoices** field, enter a custom code to use for new invoices that are created by the web service. The code can be up to 10 alphanumeric characters long.

### Add invoices to an invoice group

1.  Click **Accounts payable** \> **Common** \> **Vendor invoices** \> **Pending vendor invoices**.

2.  On the **Action Pane**, click **Invoice** to create an invoice.
    
    –or–
    
    Click **From purchase order** to create an invoice from selected purchase orders.
    
    –or–
    
    Click **From product receipt** to create an invoice from selected product receipts.

3.  In the **Invoice group** field on the **Vendor invoice header** FastTab, select the invoice group code for the invoice. For example, you might create two invoices that have the invoice group code of HR and two invoices that have the invoice group code of FIRE. The four invoices are divided among the two groups, HR and FIRE.

## See also

[Accounts payable parameters (form)](https://technet.microsoft.com/library/aa596348\(v=ax.60\))

[Vendor invoice (form)](https://technet.microsoft.com/library/hh209644\(v=ax.60\))

  


