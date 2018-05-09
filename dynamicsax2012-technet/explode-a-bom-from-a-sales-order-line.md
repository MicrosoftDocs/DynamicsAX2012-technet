---
title: Explode a BOM from a sales order line
TOCTitle: Explode a BOM from a sales order line
ms:assetid: 3fa4b63a-e76c-4b74-8f43-cd5abf980265
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa496944(v=AX.60)
ms:contentKeyID: 36056706
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Explode a BOM from a sales order line 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Explode a BOM from a sales order line:

1.  Click **Sales and marketing** \> **Common** \> **Sales orders** \> **All sales orders**. Click **New** or double-click a sales order to open it.

2.  Select the sales order line that you want to explode.

3.  Click **Sales order line** \> **Explode** \> **BOM lines**, and the **Explode BOM** form appears.

4.  Select the items that you want transferred from the bill of materials (BOM) to the sales order line. Or, you can choose **Select all**, and all the BOM lines will be selected.

5.  Click **OK**.
    
    The quantity specified for the original sales order line is set to zero; consequently, the BOM item is not included. Instead, the component items of the BOM are multiplied by the quantity in the original sales order header.

## See also

[Explode BOM lines in purchase order (form)](https://technet.microsoft.com/en-us/library/aa500727\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

