---
title: About release sales order picking/release transfer order picking
TOCTitle: About release sales order picking/release transfer order picking
ms:assetid: dbf269f8-6acf-4b43-8b28-2fe2f8c4ce26
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa551256(v=AX.60)
ms:contentKeyID: 36059672
ms.date: 05/02/2014
mtps_version: v=AX.60
f1_keywords:
- picking lists
- release orders
- picking orders
- release for picking
---

# About release sales order picking/release transfer order picking [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The release order picking functionality has been introduced to give warehouse employees an overview of the orders that are to be released for picking, based on actual availability of items, while taking into account customer service priority. Using this platform for the picking process ensures that picking lists are created only for items that are available in stock.

You can use the **Release sales order picking** form to monitor and process sales orders, and the **Release transfer order picking** form to monitor and process transfer orders. These forms are designed to be used for backorders or for the order process in general, where you have all the necessary information on one form.

## Query form

When you first open the **Release sales order picking** and **Release transfer order picking** forms, you are presented with a **Query** form that you can use to view relevant order lines.

For example, you could use the query to:

  - View all order lines on or up to a certain ship date, to allocate on-hand to important orders.

  - Process order lines for customers who are in a high-priority customer classification group.

  - Show sales or transfer backorders for which there is an actual on-hand, so that one or more orders can be fulfilled.

  - Show all sales backorders, regardless of the actual on-hand.

## Order picking forms

## Order parameters section

At the top of the order picking forms is a **Deduct released for picking** check box. This feature addresses the problem that some companies encounter when they create picking lists without reserving items for the picking list. If you picking list update a sales order line without reserving the items on the line, then it might appear that these items are available for use in another order, even though the items have been earmarked for the original order by their inclusion in the picking list for the original order.

By selecting this parameter, you ensure that any order lines for which there is no quantity of on-hand at all that has not been picking list updated, but not reserved, are eliminated from the order picking form. Therefore, the **Deduct released for picking** check box enables order takers to get a clearer picture of whether they can allocate on-hand at all for an order line.

You can also view the range of ship dates, if selected in the query form, and the date and time at which the form was last updated.

## Sales lines or Transfer order line tab

The order lines that are displayed are the result of the query. The query results show the lines quantity ordered and the quantity that is available for activation. You can then enter a quantity that you want to activate. There are check boxes for activation information and to warn you of any possible conflicts.

The **Sales order** or **Transfer order** tab shows the order header details of the selected line.

## Quantity field section

View the ordered item status of the selected line to see the picked, reserved, and delivered quantities, in addition to the reserved and nonreserved picking list quantity. You can also make or change a reservation for the items, just as when you use the **Reservation** form.

## On-hand field section

View the on-hand–item status of the selected line to see the physical, reserved, and available quantity; the nonreserved picking list quantity; and the quantity that is available for activation.

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

