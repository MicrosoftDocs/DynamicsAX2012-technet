---
title: Run end production
TOCTitle: Run end production
ms:assetid: 2a33886c-ee87-4e48-b755-35a87515d2ea
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa496859(v=AX.60)
ms:contentKeyID: 36056230
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Run end production [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Follow these steps to finish a production order.

1.  Click **Production control** \> **Periodic** \> **Production orders** \> **End**.

2.  In the **All production orders** list page, select a production order line. Click the **Production order** tab. On the **Action Pane**, click **End**.

3.  If the production job is not reported as finished, select the **Report as finished** check box on the **General** tab.

4.  Select the scrap method, and then click **OK**.

The production order is assigned the **Ended** status and can no longer be updated. The production order is cost accounted, and a receipt transaction with the **Purchased** status is generated for the produced item. All journals associated with the production order are closed.

## See also

[Production - End (class form)](https://technet.microsoft.com/en-us/library/aa582905\(v=ax.60\))

[Production orders (form)](https://technet.microsoft.com/en-us/library/aa617966\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

