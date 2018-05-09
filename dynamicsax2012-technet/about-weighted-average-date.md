---
title: About weighted average date
TOCTitle: About weighted average date
ms:assetid: a666ca8d-0044-49fe-9abd-c4b4444c8a5e
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Gg243048(v=AX.60)
ms:contentKeyID: 36058872
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# About weighted average date 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Weighted average date is an inventory model based on the weighted average principle, where issues from inventory are valued at the average value of the items that are received into inventory for each separate day in the inventory closing period.

When you run an inventory closing with weighted average date, all daily receipts are settled against a virtual issue. This holds the total received quantity and value for that day. This virtual issue has a corresponding virtual receipt from which the issues will be settled. In this manner, all issues get the same average cost. The virtual issue and receipt can be seen as a virtual transfer, which is named the weighted average inventory closing transfer.

If only one receipt has occurred on or before the date, you do not have to value the average. This is because all issues are settled from it and the virtual transfer will not be created. Likewise, if only issues occur on the date, there are no receipts from which to value the average, and the virtual transfer will not be created.

When you use weighted average date, you can mark inventory transactions so that a specific item receipt is settled against a specific issue. This means you do not use the weighted average date rule.

We recommend a monthly inventory closing when you use the weighted average date inventory model.

In Microsoft Dynamics AX, the weighted average date costing method is calculated by the following formula:

  - Weighted average = (Q1\*P1 + Q2\*P2 + Qn\*Pn) / (Q1 + Q2 + Qn)

During inventory close, the calculation will be executed daily through the closing period as illustrated in the following graphic.

![Weighted Average Date Daily Calculation Model](images/Gg243048.WeightedAverageDateDailyCalculationModel(AX.60).gif "Weighted Average Date Daily Calculation Model")

Inventory transactions leaving the inventory, including sales orders, inventory journals, and production orders, occur at an estimated cost price on the date of posting. This estimated cost price is also referred to as the running average cost price.

On the date of inventory close, Microsoft Dynamics AX will analyze the inventory transactions for previous periods, previous days, and the current day. This analysis is to determine which of the following closing principles should be used:

  - Direct settlement

  - Summarized settlement

Settlements are inventory close postings that adjust the issues to the correct weighted average as of the closing date.

**Note**   For more information about settlements in Microsoft Dynamics AX, see [About inventory close](about-inventory-close.md).

The following examples illustrate the impact of using weighted average with five different configurations:

  - Weighted average date direct settlement without the **Include physical value** option

  - Weighted average date summarized settlement without the **Include physical value** option

  - Weighted average date direct settlement with the **Include physical value** option

  - Weighted average date summarized settlement with the **Include physical value** option

  - Weighted average date with marking

## Weighted average date direct settlement without the Include physical value option

The direct settlement principle used in this version of Microsoft Dynamics AX is the same used for weighted average in earlier versions of the product. The system will settle directly between receipts and issues. Microsoft Dynamics AX uses this direct settlement principle in certain specific situations:

  - One receipt and one or several issues has been posted in the period

  - Only issues have been posted in the period and the inventory contains on-hand items from a previous closing

In the scenario below, a financially updated receipt and issue have been posted. During inventory close, Microsoft Dynamics AX will settle the receipt directly against the issue, and no adjustment to the cost price is needed on issue.

The following transactions are illustrated in the graphic below:

  - 1a. Inventory physical receipt updated for a quantity of 5 at a cost of USD 10.00 each

  - 1b. Inventory financial receipt updated for a quantity of 5 at a cost of USD 10.00 each

  - 2a. Inventory physical issue updated for a quantity of 2 at a cost of USD 10.00 each

  - 2b. Inventory financial issue updated for a quantity of 2 at a cost of USD 10.00 each

  - 3\. Inventory close was performed using the direct settlement method to settle the inventory financial receipt to the inventory financial issue.

![Weighted Ave Date DS without Include Physical Val](images/Gg243048.WeightedAverageDateDirectSettlementwithoutIncludePhysicalValue(AX.60).gif "Weighted Ave Date DS without Include Physical Val")

**Key to diagram**

  - Inventory transactions are represented by vertical arrows.

  - Receipts into inventory are represented by vertical arrows above the timeline.

  - Issues out of inventory are represented by vertical arrows below the timeline.

  - Above or below each vertical arrow, the value of the inventory transaction is specified in the form at Quantity@Unitprice.

  - An inventory transaction value enclosed in brackets indicates that the inventory transaction is physically posted into inventory.

  - An inventory transaction value without brackets indicates that the inventory transaction is financially posted into inventory.

  - Each new receipt or issue transaction is designated with a new label.

  - Each vertical arrow is labeled with a sequential identifier, such as *1a*. The identifiers indicate the sequence of inventory transaction postings in the timeline.

  - Inventory closings are represented by a red vertical dashed line and the label Inventory Close.

  - Settlements that are performed by inventory close are represented by dotted red arrows going diagonally from a receipt to an issue.

## Weighted average date summarized settlement without the Include physical value option

Weighted average in Microsoft Dynamics AX is based on the principle that all receipts within in a closing period are summarized into a new inventory transfer transaction. This transaction is named Weighted average inventory closing. All the receipts for the day will be settled against the issue of the newly created inventory transfer transaction. All issues for the day will be settled against the receipt of the new inventory transfer transaction.

If the on-hand inventory is positive after the inventory close, that on-hand inventory and value of the inventory are summarized on the new inventory transfer transaction receipt.

If the inventory on-hand is negative after the inventory close, the on-hand inventory and value of the inventory is the sum of individual issues that have not been fully settled.

In the scenario below, several financially updated receipts and issues have been posted during the period. During inventory close, Microsoft Dynamics AX will evaluate every day to determine how each one should be treated by closing.

The following are illustrated in the graph below:

**DAY 1:**

  - 1a. Inventory physical receipt updated for a quantity of 3 at USD 15.00 each.

  - 1b. Inventory financial receipt updated for a quantity of 3 at USD 15.00 each.

  - 2a. Inventory physical issue for a quantity of 1 at a running average cost of USD 15.00.

  - 2b. Inventory financial issue for a quantity of 1 at a running average cost of USD 15.00.

The system will use the direct settlement approach for Day 1.

**DAY 2:**

  - 3a. Inventory physical issue for a quantity of 1 at a running average cost of USD 15.00.

  - 3b. Inventory financial issue for a quantity of 1 at a running average cost of USD 15.00.

The system will use the direct settlement approach for Day 2.

**DAY 3:**

  - 4a. Inventory physical issue for a quantity of 1 at a running average cost of USD 15.00.

  - 4b. Inventory financial issue for a quantity of 1 at a running average cost of USD 15.00.

  - 5a. Inventory physical receipt for a quantity of 1 at USD 17.00 each.

  - 5b. Inventory financial receipt for a quantity of 1 at USD 17.00 each.

Inventory close is performed. The direct settlement will need to be used because there are multiple receipts crossing multiple days.

  - 7a. A weighted average inventory close transaction financial issue is created at for a quantity of 2 at USD 32.00 to summarize the settlements of all inventory financial receipts to date that have not been closed.

  - 7b. A weighted average inventory close transaction financial receipt is created as the offset to 7a.

Microsoft Dynamics AX will generate and post the summarized inventory transfer transaction. Also, Microsoft Dynamics AX will settle all the receipts for the day and on-hand inventory for previous days against the summarized inventory transfer issue transaction. All the issues for the day will be settled against the summarized inventory transfer receipt transaction. The weighted average cost price is calculated to be USD 16.00. The issue will have an adjustment of USD 1.00 to adjust to the weighted average cost. The new running average cost price is USD 16.00.

The following diagram illustrates this series of transactions with the effects of choosing the Weighted average inventory model and the summarized settlement principle without the **Include physical value** option.

![Weighted Ave Date SS without Include Physical Val](images/Gg243048.WeightedAverageDateSummarizedSettlementwithoutIncludePhysicalValue(AX.60).gif "Weighted Ave Date SS without Include Physical Val")

**Key to diagram**

  - Inventory transactions are represented by vertical arrows.

  - Receipts into inventory are represented by vertical arrows above the timeline.

  - Issues out of inventory are represented by vertical arrows below the timeline.

  - Above or below each vertical arrow, the value of the inventory transaction is specified in the format Quantity@UnitPrice.

  - An inventory transaction value enclosed in brackets indicates that the inventory transaction is physically posted into inventory.

  - An inventory transaction value without brackets indicates that the inventory transaction is financially posted into inventory.

  - Each new receipt or issue transaction is designated with a new label.

  - Each vertical arrow is labeled with a sequential identifier, such as *1a*. The identifiers indicate the sequence of inventory transaction postings in the timeline.

  - Inventory closings are represented by a red vertical dashed line and the label Inventory Close.

  - Settlements that are performed by inventory close are represented by dotted red arrows going diagonally from a receipt to an issue.

  - Red diagonal arrows illustrate the receipt transactions being settled to the issue transaction created by the system.

  - The green diagonal arrow represents the offsetting system-generated receipt transaction to which the originally posted issue transaction is settled.

## Weighted average date direct settlement with Include physical value option

The direct settlement principle used for weighted average date in this version of Microsoft Dynamics AX is the same as used in earlier versions. The system will settle directly between receipts and issues. Microsoft Dynamics AX uses this direct settlement principle in certain specific situations:

  - One receipt and one or several issues has been posted in the period

  - Only issues have been posted in the period and the inventory holds an on-hand inventory from a previous closing

Select the **Include physical value** check box for an item in the **Item model group** form. Then Microsoft Dynamics AX will use physically updated receipts when calculating the estimated cost price, or running average. Issues will be posted based on this estimated cost price during the period. During the inventory close, financially updated receipts only will be considered in the weighted average calculation.

## Weighted average date summarized settlement with the Include physical value option

Select the **Include physical value** check box for an item in the **Item model group** form. Then Microsoft Dynamics AX will use physically updated receipts when calculating the estimated cost price, or running average. Issues will be posted based on this estimated cost price during the period. During the inventory close, financially updated receipts only will be considered in the weighted average calculation.

Weighted average settlement is based on the principle that receipts within in a closing period are summarized into a new inventory transfer transaction called Weighted average inventory closing. All the receipts for the day will be settled against the issue of the newly created inventory transfer transaction. All issues for the day will be settled against the receipt of the new inventory transfer transaction.

If the on-hand inventory is positive after the inventory close, that on-hand inventory and value of the inventory are summarized on the new inventory transfer transaction (receipt).

If the inventory on-hand is negative after the inventory close, the on-hand inventory and value of the inventory is the sum of individual issues that have not been fully settled.

## Weighted average date marking

Marking is a process in Microsoft Dynamics AX that lets you link, or mark, an issue transaction to a receipt transaction. Marking can occur either before or after a transaction is posted. You can use marking when you want to make sure of the exact cost of the inventory when the transaction is posted or when the inventory close is performed.

For example, your Customer Service department accepted a rush order from an important customer. Because this is a rush order, you will have to pay more for this item to service your customer’s request. You must certain the cost of this inventory item is reflected in the margin, or cost of goods sold (COGS), for this sales order invoice.

When the purchase order is posted, the inventory is received at a cost of USD 120.00. The sales order document is marked to the purchase order before the packing slip or invoice is posted. Then the COGS will be USD 120.00 instead of the current running average cost for the item. If the sales order packing slip or invoice is posted before the marking occurs, the COGS will be posted at the running average cost price.

Before inventory close is performed, these two transactions can still be marked to each other.

When a receipt transaction is marked to an issue transaction, the valuation method defined in the item’s item model group will be disregarded. Microsoft Dynamics AX will settle these transactions to each other.

You can mark an issue transaction to a receipt before the transaction is posted. Open the **Sales order** form, select a transaction line, and then click the **Inventory** button on the transaction line and select **Marking**. The **Marking** form will open and display all the open receipt transactions. You can then select one of these transactions to match to, or mark, this issue transaction.

You can mark an issue transaction to a receipt after the transaction has been posted. Navigate to the inventory item on the **Inventory transactions** form and then click the **Transaction** button. Select the issue transaction that you want to mark, and then click the **Inventory** button and select **Marking**. The **Marking** form will open and display all the open receipt transactions. You can then select one of these transactions to match to, or mark, this issue transaction.

The following transactions are illustrated in the graphic below:

  - 1a. Inventory physical receipt for a quantity of 1 at a cost price of USD 10.00 each.

  - 1b. Inventory financial receipt for a quantity of 1 at a cost price of USD 10.00 each.

  - 2a. Inventory physical receipt for a quantity of 1 at a cost price of USD 20.00 each.

  - 2b. Inventory financial receipt for a quantity of 1 at a cost price of USD 20.00 each.

  - 3a. Inventory physical receipt for a quantity of 1 at a cost price of USD 25.00 each.

  - 4a. Inventory physical receipt for a quantity of 1 at a cost price of USD 30.00 each.

  - 4b. Inventory financial receipt for a quantity of 1 at a cost price of USD 30.00 each.

  - 5a. Inventory physical issue for a quantity of 1 at a cost price of USD 21.25 (running average of financial and physical updated transactions).

  - 5b. Inventory financial issue for a quantity of 1 is marked to the inventory receipt 2b before the transaction is posted. This transaction is posted at a cost price of USD 20.00.

  - 6a. Inventory physical issue for a quantity of 1 at a cost price of USD 21.25.

  - 7\. Inventory close is performed. Because the financially updated transaction is marked to an existing receipt, these transactions are settled to each other and no adjustment is made.

The new running average cost price reflects the average of the financially and physically updated transactions at USD 27.50.

The following diagram illustrates this series of transactions with the effects of choosing the Weighted average date inventory model with marking.

![Weighted Average Date with Marking](images/Gg243048.WeightedAverageDatewithMarking(AX.60).gif "Weighted Average Date with Marking")

**Key to diagram**

  - Inventory transactions are represented by vertical arrows.

  - Receipts into inventory are represented by vertical arrows above the timeline.

  - Issues out of inventory are represented by vertical arrows below the timeline.

  - Above (or below) each vertical arrow, the value of the inventory transaction is specified in the format Quantity@Unit price.

  - An inventory transaction value enclosed in brackets indicates that the inventory transaction is physically posted into inventory.

  - An inventory transaction value without brackets indicates that the inventory transaction is financially posted into inventory.

  - Each new receipt or issue transaction is designated with a new label.

  - Each vertical arrow is labeled with a sequential identifier, such as *1a*. The identifiers indicate the sequence of inventory transaction postings in the timeline.

  - Inventory closings are represented by a red vertical dashed line and the label Inventory Close.

  - Settlements that are performed by inventory close are represented by dotted red arrows going diagonally from a receipt to an issue.

## See also

[Specify an inventory model for inventory close](specify-an-inventory-model-for-inventory-close.md)

[About FIFO with physical value and marking](about-fifo-with-physical-value-and-marking.md)

[About LIFO with physical value and marking](about-lifo-with-physical-value-and-marking.md)

[About LIFO Date with physical value and marking](about-lifo-date-with-physical-value-and-marking.md)

[About weighted average with physical value and marking](about-weighted-average-with-physical-value-and-marking.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

