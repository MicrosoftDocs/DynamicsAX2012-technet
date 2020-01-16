---
title: About reversing production order status
TOCTitle: About reversing production order status
ms:assetid: 23d700b1-27db-458f-8b76-0a41dd425dd1
ms:mtpsurl: https://technet.microsoft.com/library/Aa496806(v=AX.60)
ms:contentKeyID: 37832495
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- reverse
- status
- revert
- change production
- production order
audience: Application User
ms.search.region: Global
---

# About reversing production order status 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

If you reverse the status of a production order, the order and all operations that are associated with the routes revert to a previous step in the production life cycle.

For example, if a production order has the status **Scheduled** and you change it back to **Created**, the application first changes it to the status immediately before, which is **Estimated**, and from there to the status you want, which is **Created**.


> [!NOTE]
> <P>If your order has reached the status <STRONG>Report as finished</STRONG> and you want to reverse it back to an earlier stage, you can do so. However, you must run estimation and operations scheduling or job scheduling, or both, again to update the information on the order. This is because any reservations of remaining item consumption and operations resource consumption must also be reset.</P>



You can view what occurs in the application when you reverse the status of a production order in the following ways:

  - From estimated to created

  - From scheduled to estimated

  - From released to scheduled

  - From started to released

## From estimated to created

When you reverse the status from **Estimated** back to **Created**, the item consumption that was calculated for the items in the BOM is removed. Inventory transactions on the production line are deleted, and the **Remain status** field on the production's BOM lines is reset to **Ended**.

Any underlying purchase orders or production orders are deleted when the **Derived purchases** and **Derived production** check boxes are selected. If you estimated the costs of the production order or manually reserved items for use in production, these transactions are also removed.

## From scheduled to estimated

When you reverse the status from **Scheduled** back to **Estimated**, the scheduled start and end dates and times are removed. Capacity reservations that were made during scheduling are removed, and jobs that were created during job scheduling are deleted. All information about operation scheduling and job scheduling that is recorded in the **Production order details** form is reset. For more information, see [Production orders (form)](https://technet.microsoft.com/library/aa617966\(v=ax.60\)).

## From released to scheduled

When you reverse the status of a production order from **Released** to **Scheduled**, the only result is a change in the status field.

## From started to released

When you revert the status of a production order from **Started** to **Released**, all items that were reported as finished are also reverted. If material has been picked or inbound and outbound deliveries have been made to production, these settings are also reverted.

The **Remain status** field on the production’s BOM lines is changed from **Ended** to **Material consumption**. If time has been registered or quantities have been reported as finished for the operations in the production route, this is reversed.

The **Remain status** field is changed from **Ended** to **Route consumption** in the production route. The settings for all items that are posted as in process or work in process are also reversed.

Fields in the **Production order details** form that show a quantity started or reported as finished, and the dates for these transactions, are reset.

## See also

[About production order status](about-production-order-status.md)

  


