---
title: (IND) Create an export order for an EPCG incentive scheme
TOCTitle: (IND) Create an export order for an EPCG incentive scheme
ms:assetid: 7f75f8da-2827-4380-9940-ee107ac15227
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ677959(v=AX.60)
ms:contentKeyID: 49385922
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- (IND)
- india
- export order
- EPCG incentive scheme
- apply EPCG
- apply EPCG incentive scheme
---

# (IND) Create an export order for an EPCG incentive scheme 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

When you create a sales order to export products that meet the requirements for an Export Promotion Capital Goods (EPCG) incentive scheme, you assign a specific EPCG incentive scheme to the sales order.

**Prerequisites**

  - Create and approve an EPCG incentive scheme. For more information, see [(IND) Approval EPCG schemes (form)](https://technet.microsoft.com/en-us/library/jj710885\(v=ax.60\)).

  - Set up import and export taxes. For more information, see [(IND) Tax codes for incentive schemes (form)](https://technet.microsoft.com/en-us/library/jj664578\(v=ax.60\)).

  - Define currency exchange rates for customer currencies. For more information, see [Currency exchange rates (form)](https://technet.microsoft.com/en-us/library/hh209477\(v=ax.60\)).

<!-- end list -->

1.  Click **Sales and marketing** \> **Common** \> **Sales orders** \> **All sales orders**. On the **Action Pane**, on the **Sales order** tab, click **Sales order**.
    
    –or–
    
    Click **Accounts receivable** \> **Common** \> **Sales orders** \> **All sales orders**. On the **Action Pane**, on the **Sales order** tab, click **Sales order**.

2.  In the **Create sales order** form, select the **Export order** check box. Complete the remaining information in the form, and then click **OK**.
    
    For more information about how to create a sales order, see [Sales orders (form)](https://technet.microsoft.com/en-us/library/aa585863\(v=ax.60\)).

3.  In the **Sales order** form, on the **Action Pane**, on the **Sales order** tab, click **Line view**. On the **Sales order lines** FastTab, enter items on the lines.

4.  On the **Line details** FastTab, click the **Tax information** tab. Then, in the **EXIM incentive scheme** field group, in the **Incentive scheme group** field, select an EPCG incentive scheme.

5.  In the **Port ID** field, select the export-import (EXIM) port for the EPCG incentive scheme.

6.  In the **Product group** field, select the product group for the item.

7.  Complete and post the export sales order.

## See also

[(IND) About EPCG incentive schemes for export orders](ind-about-epcg-incentive-schemes-for-export-orders.md)

[(IND) Create an export sales order and post the confirmation order](ind-create-an-export-sales-order-and-post-the-confirmation-order.md)

[(IND) Create sales order (modified form)](https://technet.microsoft.com/en-us/library/jj664489\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

