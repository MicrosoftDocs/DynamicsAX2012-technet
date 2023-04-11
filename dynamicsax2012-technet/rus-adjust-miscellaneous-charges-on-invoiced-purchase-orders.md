---
title: (RUS) Adjust miscellaneous charges on invoiced purchase orders
TOCTitle: (RUS) Adjust miscellaneous charges on invoiced purchase orders
ms:assetid: 2e68db2e-2c41-4ef9-a1c9-c4b363555d5e
ms:mtpsurl: https://technet.microsoft.com/library/JJ665242(v=AX.60)
ms:contentKeyID: 49387331
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- orders
- purchase
- charges
- invoiced
- Russia
- RUS
audience: Application User
ms.search.region: Russia
---

# (RUS) Adjust miscellaneous charges on invoiced purchase orders 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Use this procedure to adjust charges on an invoiced purchase order and allocate the charges to the invoice lines by using the weight and volume information on the lines. For order lines that contain items, the allocation is based on the information in the item record. For category-based lines, the allocation is based on the information on the order line. Category-based order lines do not contain any volume information for the goods.

1.  Click **Accounts payable** \> **Inquiries** \> **Journals** \> **Invoice journal**.

2.  Select a vendor invoice that has been posted.

3.  Click **Charges** \> **Adjustment** to open the **Allocate charges** form.

4.  In the **Charges allocation** field, select the allocation method from the following options:
    
      - **Net amount** – Charges are allocated according to the amount for each line in relation to the total net amount for the purchase order or invoice.
    
      - **Quantity** – Charges are allocated according to the number of units for each line in relation to the total number of units for the purchase order or invoice.
    
      - **Per line** – Charges are allocated equally, according to the total number of lines.
    
      - **Gross weight** – Charges are allocated equally, according to the gross weight of the goods that are received.
    
      - **Volume** – Charges are allocated equally, according to the volume of the goods that are received.

5.  In the **Charges code** field, select a charges code based on which the charges are allocated to the selected vendor invoice.

6.  Click **OK**.

## See also

[(RUS) Allocate charges - Invoice (modified form)](https://technet.microsoft.com/library/jj665349\(v=ax.60\))

  


