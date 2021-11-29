---
title: (DNK) Post a sales invoice with a payment slip
TOCTitle: (DNK) Post a sales invoice with a payment slip
ms:assetid: 6b466186-1837-4500-9d02-640a05efec26
ms:mtpsurl: https://technet.microsoft.com/library/Hh242612(v=AX.60)
ms:contentKeyID: 36057987
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- Denmark
- payment slip
- sales invoice
audience: Application User
ms.search.region: Denmark
---

# (DNK) Post a sales invoice with a payment slip 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can post a sales invoice with a payment slip attachment in a specified format. The payment slip is printed with the creditor identification number and invoice number to identify the payment.

1.  Click **Sales and marketing** \> **Common** \> **Sales orders** \> **All sales orders**.

2.  Create a new sales order or select an open sales order.

3.  Click **Invoice** \> **Invoice** to open the **Posting invoice** form. For more information, see [Sales posting (form)](https://technet.microsoft.com/library/aa550287\(v=ax.60\)).

4.  In the **Associated payment attachment on customer invoice** field, select a payment slip to print with the sales invoice. Choose from the following options:
    
      - **None** – Do not print a payment slip. Choose this option if the payment amount is in a currency other than Danish kroner (DKK).
    
      - **FIK 751** – Print an FIK 751 payment slip if you intend to write the payment amount and due date on the payment slip manually.
    
      - **FIK 752** – Print an FIK 752 payment slip if you intend to use a computer-generated payment slip with a preprinted payment amount and due date.

5.  Click **OK** to post the sales invoice with the payment slip attachment.

6.  Close the forms to save your changes.

## See also

[(DNK) Set up a payment slip format for customers](dnk-set-up-a-payment-slip-format-for-customers.md)

[Sales orders (form)](https://technet.microsoft.com/library/aa585863\(v=ax.60\))

  


