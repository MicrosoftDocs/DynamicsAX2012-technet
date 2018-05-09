---
title: About creating production orders for projects
TOCTitle: About creating production orders for projects
ms:assetid: e62f4247-d532-41c9-80bb-a74da6716437
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Gg243228(v=AX.60)
ms:contentKeyID: 36059799
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- production orders
- consumed item
- link to order
- finished item
- production costs
---

# About creating production orders for projects 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

A project-related production order can be linked to a sales order or item requirement by using either the finished item or consumed item method. If the production order is created manually, there is no link between the production order and the sales order or item requirement (no link to order). If the production order was created automatically to fulfill a sales order or an item requirement, there is a link between the production order and sales order or item requirement (link to order).


> [!NOTE]
> <P>A finished item has been assembled for sale using a bill of materials. Production orders that are associated with the consumed-item method involve time spent and costs incurred during production. The individual time and item costs that occur during production can be invoiced to the customer.</P>



Based on combinations of these options, use one of the following methods:

  - Finished item/link to order

  - Finished item/no link to order

  - Consumed item/link to order

  - Consumed item/no link to order

Depending on the method that you select, you can post the actual cost of the production at earlier stages instead of viewing committed costs only as the production progresses. You can set the default method of finished item or consumed item on the **Project parameters** form: Click **Project management and accounting** \> **Setup** \> **Project management and accounting parameters**.


> [!NOTE]
> <P>The posting method that you choose in the <STRONG>Project parameters</STRONG> form determines the default production integration method regardless of whether the production order is linked to a sales order or an item requirement.</P>



## Finished item/link to order

If you select the finished item/link to order method, you can link the project to a sales order or an item requirement. By using this method, actual project costs are posted when the sales order is invoiced or when the packing slip is updated for the item requirement. The cost is posted as a finished item.

## Finished item/no link to order

If you select the finished item/no link to order method, you cannot post actual costs until the production cycle for an item has a status of Ended. The cost for the finished item is posted as a single transaction.

## Consumed item/link to order

If you select the consumed item/link to order method, you can link the project to an item requirement. By using this method, you can view actual project costs when the production has a status of Started or is reported as Finished. The costs are posted as multiple project item transactions for raw materials and hours consumed for production. When the packing slip is updated for the item requirement, no project costs are posted. You can also define the level in the BOM hierarchy at which projects in the production are tracked. You can create the hierarchy in the **BOM line** form by choosing **Pegged supply** in the **Line type** field and selecting the **Set subproduction to Consumed** check box. This procedure creates the subproductions for your hierarchy.

## Consumed item/no link to order

If you select the consumed item/link to order method, you can link the project to an item requirement. By using this method, you can view actual project costs when production has a status of Started or is reported as Finished. The costs are posted as multiple project item transactions for raw materials and hours consumed for the production. You can also define the level in the BOM hierarchy at which the projects in the production are tracked. You can create the hierarchy in the **BOM line** form by choosing **Pegged supply** in the **Line type** field and selecting the **Set subproduction to Consumed** check box. This procedure creates the subproductions for your hierarchy.


> [!NOTE]
> <P>The consumed item/link to order method does not support indirect costs and standard costs.</P>



## See also

[About creating production orders](about-creating-production-orders.md)

[About estimated costs for a production order](about-estimated-costs-for-a-production-order.md)

[About analyzing costs for a production order](about-analyzing-costs-for-a-production-order.md)

[Create production orders manually](create-production-orders-manually.md)

[Production orders (form)](https://technet.microsoft.com/en-us/library/aa617966\(v=ax.60\))

[Create production order (form)](https://technet.microsoft.com/en-us/library/aa497150\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

