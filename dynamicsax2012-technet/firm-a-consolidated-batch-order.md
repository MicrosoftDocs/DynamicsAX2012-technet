---
title: Firm a consolidated batch order
TOCTitle: Firm a consolidated batch order
ms:assetid: 52f2c77b-e9bc-46f0-b8ac-8da1a7518675
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh352203(v=AX.60)
ms:contentKeyID: 36687837
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- firm batch orders
- firm consolidated batch orders
- firm planned batch orders
- firm planned consolidated batch orders
---

# Firm a consolidated batch order 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use this procedure to firm a consolidated batch order. A consolidated order is a grouping of batch orders. A consolidated order can contain one or multiple packed item batch orders and one or multiple bulk item batch orders. All batch orders that are associated with the consolidated order either produce or consume the same bulk item.


> [!IMPORTANT]
> <P>You must firm a planned consolidated batch order before you can produce it. You can firm an individual order or multiple orders. All associated bulk and packed planned orders are firmed at the same time. However, you may want to firm each order separately to ensure that the quantity that is produced is also fully consumed.</P>



1.  Click **Master planning** \> **Common** \> **Planned orders**.

2.  Select the planned batch orders that you want to firm.

3.  On the **Action Pane**, on the **Planned order** tab, in the **Process** group, click **Firm and Consolidate**.
    
      - If you selected only planned orders for products that are defined as packed products, you are asked to confirm that no planned orders for bulk products were selected. Click **OK** to continue. The **Consolidated batch orders** form is displayed with the selected planned orders for packed products. If you click **No**, the **Consolidated batch orders** form is not displayed.
    
      - If you selected only planned orders for products that are defined as bulk products, you are asked to confirm that no planned orders for packed products were selected. Click **OK** to continue. The **Consolidated batch orders** form is displayed with the selected planned orders for both packed and bulk products. If you select **No**, the **Consolidated batch orders** form is displayed with only the selected planned orders for bulk products.
    
      - If you selected planned orders for products that are defined as packed and bulk products, the **Consolidated batch orders** form is displayed.

4.  Make any necessary adjustments to the **Make** quantities in the batch orders.

5.  Select the consolidated batch order to firm, and then click **Firm**.

## See also

[About consolidated batch orders](about-consolidated-batch-orders.md)

[Consolidated batch orders (form)](https://technet.microsoft.com/en-us/library/hh328731\(v=ax.60\))

[Planned orders (form)](https://technet.microsoft.com/en-us/library/aa620351\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

