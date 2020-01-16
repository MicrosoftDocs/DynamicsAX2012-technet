---
title: Explode a BOM from a purchase order line
TOCTitle: Explode a BOM from a purchase order line
ms:assetid: 5cb2dc78-685c-4a6f-ab73-67eaeaf58ea4
ms:mtpsurl: https://technet.microsoft.com/library/Aa549097(v=AX.60)
ms:contentKeyID: 36057573
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- explode a BOM from a purchase order line
- purchase order line
audience: Application User
ms.search.region: Global
---

# Explode a BOM from a purchase order line 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

To explode a BOM from a purchase order line, use the following procedure:

1.  Click **Accounts payable** \> **Common** \> **Purchase orders** \> **All purchase orders**. Double click a purchase order.

2.  Select the purchase order line you want to explode.

3.  Click **Purchase order line** on the Purchase order line FastTab \> **Explode** \> **BOM lines** and the **Explode BOM** form appears.

4.  Select the items from the Bill of material (BOM) you want transferred to the purchase order line. Alternatively, you can choose **Select all** and all the BOM lines will be selected.

5.  Click **OK**.
    
    The quantity specified for the original purchase order line is set to zero. Consequently, the BOM item is not included in item picking. Instead the component items of the BOM are multiplied by the quantity in the original purchase order header.


> [!NOTE]
> <P>If the purchase order that you want to explode a BOM line for is associated with a purchase agreement, Microsoft Dynamics AX 2012 will automatically search for matching purchase agreement lines within that purchase agreement. If matching purchase agreement lines are found, relevant information such as price and discount is transferred to the purchase order lines.</P>



## See also

[Explode BOM lines in purchase order (form)](https://technet.microsoft.com/library/aa500727\(v=ax.60\))

  


