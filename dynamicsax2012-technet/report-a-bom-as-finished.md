---
title: Report a BOM as finished
TOCTitle: Report a BOM as finished
ms:assetid: 158f940f-5414-4344-ac57-32310d90f17c
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa569796(v=AX.60)
ms:contentKeyID: 36056063
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Report a BOM as finished [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

A bill of material (BOM) can be reported as finished when no further changes are necessary and when you want to post the inventory transactions.

You can report a BOM as finished from the following locations:

  - Click **Product information management** \> **Common** \> **Released products**. Select the item that you want to report as finished. On the **Action Pane**, on the **Engineer** tab, in the **Process** group, click **Report as finished**.

  - Click **Inventory management** \> **Periodic** \> **Bills of materials** \> **Report as finished**.

<!-- end list -->

1.  At a minimum, enter information in the following fields:
    
      - **Date**
    
      - **Item number**
    
      - **BOM** number
    
      - Any applicable **Configuration**
    
      - **Quantity**

2.  To post the item issue and receipt transactions immediately, select the **Post now** check box.

3.  Adjustments are made to the journal name used for **Bills of materials**.

4.  Click **OK**.
    
    An Infolog message tells you when the process is complete. You can see the posted or unposted inventory transactions (depending on the selection you made) in the **Bills of materials** journal.

## See also

[Report BOM as finished (class form)](https://technet.microsoft.com/en-us/library/aa500110\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

