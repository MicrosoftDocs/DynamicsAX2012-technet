---
title: Add a batch order to a consolidated batch order
TOCTitle: Add a batch order to a consolidated batch order
ms:assetid: 2ce1add1-9c2e-4dc0-a92d-6069d9855846
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh352192(v=AX.60)
ms:contentKeyID: 36687825
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Add a batch order to a consolidated batch order [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use this procedure to add a batch order to a consolidated order. This procedure assumes that both the batch order and the consolidated order already exist.


> [!IMPORTANT]
> <P>The batch order that you add to a consolidated order must be related to the other orders that are already included in the consolidated order. For example, to add a bulk batch order, that batch order should produce the same bulk item as the other bulk batch orders. If not, it should produce the bulk item that is used in producing the packed batch orders that are included in the batch order. If you add a packed batch order, that batch order should use at least one of the bulk orders in its production process.</P>



## From the Batch order form

1.  Click **Production control** \> **Common** \> **Production orders** \> **All production orders**.

2.  Double-click the batch order that you want to add to the consolidated order.

3.  In the **Batch order** form, on the **Action Pane**, on the **Production order** tab, in the **Consolidated batch order** group, select **Add to**.

4.  In the **Consolidated order** field, select the consolidated order to which the batch order must be added.

5.  Click **OK**.

## From the Consolidated orders form

1.  Click **Production control** \> **Common** \> **Consolidated batch orders**.

2.  Double-click the batch order to add to the consolidated order.

3.  In the applicable **Bulk Orders** or **Packed Orders** grid, click **Functions**.

4.  Select **Add to consolidated batch order**.

5.  In the **Batch orders** field, select the batch order to add.

6.  Click **OK**.

## See also

[About consolidated batch orders](about-consolidated-batch-orders.md)

[Batch order (form)](https://technet.microsoft.com/en-us/library/hh352323\(v=ax.60\))

[Consolidated batch orders (form)](https://technet.microsoft.com/en-us/library/hh328731\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

