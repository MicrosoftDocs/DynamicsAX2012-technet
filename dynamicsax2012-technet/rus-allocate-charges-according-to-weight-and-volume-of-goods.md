---
title: (RUS) Allocate charges according to weight and volume of goods
TOCTitle: (RUS) Allocate charges according to weight and volume of goods
ms:assetid: 36911789-1d8c-4760-b20c-9b142d23d5ec
ms:mtpsurl: https://technet.microsoft.com/library/JJ665278(v=AX.60)
ms:contentKeyID: 49387367
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- volume
- weight
- miscellaneous
- charges
- Russia
- RUS
audience: Application User
ms.search.region: Russia
---

# (RUS) Allocate charges according to weight and volume of goods 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Use this procedure to allocate charges to purchase order lines according to the gross weight and volume of the goods that are received. For order lines that contain items, the allocation is based on the information in the item record. For category-based lines, the allocation is based on the information on the order line. Category-based order lines do not contain any volume information for the goods.

1.  Click **Accounts payable** \> **Common** \> **Purchase orders** \> **All purchase orders**.

2.  Create a new purchase order.

3.  Click the **Purchase** tab, and then click **Allocate charges**.

4.  In the **Charges allocation** field, select the allocation method:
    
      - **Net amount** – Charges are allocated according to the amount for each line in relation to the total net amount for the purchase order or invoice.
    
      - **Quantity** – Charges are allocated according to the number of units for each line in relation to the total number of units for the purchase order or invoice.
    
      - **Per line** – Charges are allocated equally, according to the total number of lines.
    
      - **Gross weight** – Charges are allocated equally, according to the gross weight of the goods that are received.
    
      - **Volume** – Charges are allocated equally, according to the volume of the goods that are received.

5.  Click **OK** to allocate the charges.

## See also

[(RUS) Allocate charges (modified form)](https://technet.microsoft.com/library/jj665432\(v=ax.60\))

[Create a purchase order](create-a-purchase-order.md)

  


