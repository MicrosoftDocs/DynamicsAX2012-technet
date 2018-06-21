---
title: Remove a batch order from a consolidated batch order
TOCTitle: Remove a batch order from a consolidated batch order
ms:assetid: f8b32cca-23db-4a60-b32c-407ba504af0d
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh328614(v=AX.60)
ms:contentKeyID: 36688046
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Remove a batch order from a consolidated batch order [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use this procedure to remove a batch order from a consolidated batch order. This procedure assumes that both the batch order and the consolidated batch order already exist.


> [!IMPORTANT]
> <P>The batch order that you remove from a consolidated batch order must be related to the other orders that are already included in the consolidated batch order.</P>



## From the Batch order form

1.  Click **Production control** \> **Common** \> **Production orders** \> **All production orders**.

2.  Double-click the batch order that you want to remove from the consolidated batch order.

3.  In the **Batch order** form, on the **Action Pane**, on the **Production order** tab, in the **Consolidated batch order** group, select **Remove from** to open the **Remove from consolidated batch order** dialog box.

4.  In the **Consolidated batch order** field, select the consolidated batch order from which the batch order must be removed. Then click **OK**.

## From the Consolidated batch orders form

1.  Click **Production control** \> **Common** \> **Consolidated batch orders**.

2.  Double-click the batch order to remove from the consolidated batch order.

3.  In the applicable **Bulk Orders** or **Packed Orders** grid, click **Functions**.

4.  Select **Remove from consolidated batch order** to open the **Choose consolidated batch order** dialog box.

5.  In the **Batch orders** field, select the batch order to remove. Then click **OK**.

## See also

[About consolidated batch orders](about-consolidated-batch-orders.md)

[Batch order (form)](https://technet.microsoft.com/en-us/library/hh352323\(v=ax.60\))

[Consolidated batch orders (form)](https://technet.microsoft.com/en-us/library/hh328731\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

