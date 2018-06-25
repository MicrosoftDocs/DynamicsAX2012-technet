---
title: About synchronization of charges
TOCTitle: About synchronization of charges
ms:assetid: 2165b497-93a8-4c20-ad1f-ab5d45546f4f
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa496788(v=AX.60)
ms:contentKeyID: 36056165
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# About synchronization of charges [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Charges are synchronized only between the intercompany sales order and the intercompany purchase order, and synchronization always occurs.

If the **Allow price edit** field is selected on the intercompany purchase order or the intercompany sales order, you can add a charge manually to the intercompany sales order or the intercompany purchase order. Otherwise, you cannot.

If the **Allow price edit** field is not selected on the intercompany sales order, you cannot add a charge manually to an intercompany sales order.

If the **Allow price edit** field is not selected on the intercompany purchase order, you cannot add a charge on the intercompany purchase order.

If the **Allow price edit** field is enabled on both the intercompany purchase order and the intercompany sales order, you can add charges manually to both orders. However, this can result in many charges being added incorrectly.

To avoid these types of conflicts, the best practice is to allow charges to be added either to the intercompany sales order or the intercompany purchase order, but not both.

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

