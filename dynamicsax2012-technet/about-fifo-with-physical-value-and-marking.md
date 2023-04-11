---
title: About FIFO with physical value and marking
TOCTitle: About FIFO with physical value and marking
ms:assetid: 6a395fb1-8d66-4132-a6e2-62b74d8863b1
ms:mtpsurl: https://technet.microsoft.com/library/Gg231585(v=AX.60)
ms:contentKeyID: 36057978
author: tfehr
ms.author: daxcpft
ms.date: 05/02/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# About FIFO with physical value and marking 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

First in, First out (FIFO) is an inventory model in which the first acquired receipts are issued first. Financially updated issues from inventory are settled against the first financially updated receipts into inventory, based on the financial date of the inventory transaction.

## Considerations when using FIFO

When using FIFO, you have the option of marking inventory transactions so that a specific receipt is settled against a specific issue instead of following the FIFO rule.

We recommend a periodic inventory closing when you use the FIFO inventory model.

The following examples illustrate the effect of using FIFO with three different configurations:

  - FIFO without the **Include physical value** option

  - FIFO with the **Include physical value** option

  - FIFO with marking

## FIFO without the Include physical value option

In this FIFO example, the item model group is not marked to include physical value.

The following transactions are illustrated in the diagram later in this section:

  - 1a. Inventory physical receipt for a quantity of 1 at a cost of USD 10.00 each.

  - 1b. Inventory financial receipt for a quantity of 1 at a cost of USD 10.00 each.

  - 2a. Inventory physical receipt for a quantity of 2 at a cost of USD 10.00 each.

  - 2b. Inventory financial receipt for a quantity of 2 at a cost of USD 10.00 each.

  - 3a. Inventory physical receipt for a quantity of 1 at a cost of USD 25.00 each.

  - 4a. Inventory physical receipt for a quantity of 1 at a cost of USD 30.00 each.

  - 4b. Inventory financial receipt for a quantity of 1 at a cost of USD 30.00 each.

  - 5a. Inventory physical issue for a quantity of 1 at a cost price of USD 20.00 each (running average of financially updated transactions).

  - 5b. Inventory financial issue for a quantity of 1 at a cost price of USD 20.00 each with a running average of financially updated transactions.

  - 6\. Inventory close is performed. Based on the FIFO method, the first financially updated issue will be settled to the first financially updated receipt. An adjustment of negative USD 10.00 will be made on the issue transaction.

The new running average cost price reflects the average of the financially updated transactions.

The following diagram illustrates this series of transactions when the FIFO inventory model is used without the **Include physical value** option.

![FIFO without Include Physical Value](images/Gg231585.FIFOwithoutIncludePhysicalValue(AX.60).gif "FIFO without Include Physical Value")

## Key to diagram

  - Inventory transactions are represented by vertical arrows.

  - Receipts into inventory are represented by vertical arrows above the timeline.

  - Issues out of inventory are represented by vertical arrows below the timeline.

  - Above (or below) each vertical arrow, the value of the inventory transaction is specified in the format Quantity@Unitprice.

  - An inventory transaction value enclosed in brackets indicates that the inventory transaction is physically posted into inventory.

  - An inventory transaction value without brackets indicates that the inventory transaction is financially posted into inventory.

  - Each new receipt or issue transaction is designated with a new label.

  - Each vertical arrow is labeled with a sequential identifier, such as *1a*. The identifiers indicate the sequence of inventory transaction postings in the timeline.

  - Inventory closings are represented by a red vertical dashed line and the label Inventory Close.

  - Settlements that are performed by inventory close are represented by dotted red arrows going diagonally from a receipt to an issue.

## FIFO with the Include physical value option

If the **Include physical value** check box is selected for an item in the **Item model group** form, Microsoft Dynamics AX uses both physical and financial receipt transactions to calculate the running average cost price. Where applicable, the system also makes adjustments to the physically updated issue transaction. When the **Include physical value** check box is cleared, inventory close with the FIFO inventory model will make settlements only to transactions that are financially updated.

The following transactions are illustrated in the diagram later in this section:

  - 1a. Inventory physical receipt for a quantity of 1 at a cost of USD 10.00 each.

  - 1b. Inventory financial receipt for a quantity of 1 at a cost of USD 10.00 each.

  - 2a. Inventory physical receipt for a quantity of 1 at a cost of USD 20.00 each.

  - 2b. Inventory financial receipt for a quantity of 1 at a cost of USD 20.00 each.

  - 3a. Inventory physical receipt for a quantity of 1 at a cost of USD 25.00 each.

  - 4a. Inventory physical receipt for a quantity of 1 at a cost of USD 30.00 each.

  - 4b. Inventory financial receipt for a quantity of 1 at a cost of USD 30.00 each.

  - 5a. Inventory physical issue for a quantity of 1 at a cost price of USD 21.25 each with a running average of financial and physical updated transactions.

  - 5b. Inventory financial issue for a quantity of 1 at a cost price of USD 21.25 each with a running average of financial and physical updated transactions.

  - 6a. Inventory physical issue for a quantity of 1 at a cost price of USD 21.25 each.

  - 7\. Inventory close is performed. Based on the FIFO method, the first financial issue transaction will be adjusted or settled to the first updated receipt, either financial or physical.

Transaction 5b will be settled to receipt transaction 1b. There will be an adjustment of negative USD 11.25 to this issue transaction.

The new running average cost price reflects the average of the financially and physically updated transactions, USD 27.50.

The following diagram illustrates this series of transactions when the FIFO inventory model is used with the **Include physical value** option.

![FIFO with Include Physical Value](images/Gg231585.FIFOwithIncludePhysicalValue(AX.60).gif "FIFO with Include Physical Value")

## Key to diagram

  - Inventory transactions are represented by vertical arrows.

  - Receipts into inventory are represented by vertical arrows above the timeline.

  - Issues out of inventory are represented by vertical arrows below the timeline.

  - Above (or below) each vertical arrow, the value of the inventory transaction is specified in the format Quantitly@Unitprice.

  - An inventory transaction value enclosed in brackets indicates that the inventory transaction is physically posted into inventory.

  - An inventory transaction value without brackets indicates that the inventory transaction is financially posted into inventory.

  - Each new receipt or issue transaction is designated with a new label.

  - Each vertical arrow is labeled with a sequential identifier, such as *1a*. The identifiers indicate the sequence of inventory transaction postings in the timeline.

  - Inventory closings are represented by a red vertical dashed line and the label Inventory Close.

  - Settlements that are performed by inventory close are represented by dotted red arrows going diagonally from a receipt to an issue.

## FIFO with marking

Marking is a process in Microsoft Dynamics AX that lets you link, or mark, an issue transaction to a receipt transaction. Marking can occur either before or after a transaction is posted. You can use marking when you want to make sure of the exact cost of the inventory when the transaction is posted or when the inventory close is performed.

Suppose the Customer Service department accepted a rush order from an important customer. Because this is a rush order, you must pay more for this item to service your customer’s request. You must be certain that the cost of this inventory item is reflected in the margin, or cost of goods sold (COGS), for this sales order invoice.

When the purchase order is posted, the inventory is received at a cost of USD 120.00. If this sales order document is marked to the purchase order before the packing slip or invoice is posted, the COGS will be USD 120.00 instead of the current running average cost for the item. If the sales order packing slip or invoice is posted before the marking occurs, the COGS will be posted at the running average cost price.

Before inventory close is performed, these two transactions can still be marked to each other.

When a receipt transaction matches an issue transaction, the valuation method defined in the item model group is disregarded, and Microsoft Dynamics AX settles these transactions to each other.

You can mark an issue transaction to a receipt before a transaction is posted. Click **Sales and marketing** \> **Common** \> **Sales orders** \> **All sales orders**. Select an sales line, click **Inventory**, and then **Marking**. The **Marking** form opens and displays all the open receipt transactions. You can then select one of thse transactions to match to, or mark, this issues transaction.

You can mark an issue transaction to a receipt after it is posted. Click **Inventory management** \> **Journals** \> **Item transactions** \> **Inventory adjustment**. Select the issue transaction that you want to mark, click **Lines**, then select **Inventory**, then **Marking**. The **Marking** form opens and displays all the open receipt transactions. You can then select one of these transactions to match to, or mark, this issue transaction.

The following transactions are illustrated in the diagram later in this section:

  - 1a. Inventory physical receipt for a quantity of 1 at a cost of USD 10.00 each.

  - 1b. Inventory financial receipt for a quantity of 1 at a cost of USD 10.00 each.

  - 2a. Inventory physical receipt for a quantity of 1 at a cost of USD 20.00 each.

  - 2b. Inventory financial receipt for a quantity of 1 at a cost of USD 20.00 each.

  - 3a. Inventory physical receipt for a quantity of 1 at a cost of USD 25.00 each.

  - 4a. Inventory physical receipt for a quantity of 1 at a cost of USD 30.00 each.

  - 4b. Inventory financial receipt for a quantity of 1 at a cost of USD 30.00 each.

  - 5a. Inventory physical issue for a quantity of 1 at a cost price of USD 21.25 each (running average of financial and physical updated transactions).

  - 5b. Inventory financial issue for a quantity of 1 is marked to inventory receipt 2b before the transaction is posted. This transaction is posted at a cost price of USD 20.00 each.

  - 6a. Inventory physical issue for a quantity of 1 at a cost price of USD 21.25 each.

  - 7\. Inventory close is performed. Because the financially updated FIFO transaction is marked to an existing receipt, these transactions are settled to each other, and no adjustment is made.

The new running average cost price reflects the average of the financially and physically updated transactions, USD 27.50.

The following diagram illustrates this series of transactions when the FIFO inventory model is used with marking between issues and receipts.

![FIFO with Marking](images/Gg231585.FIFOwithMarking(AX.60).gif "FIFO with Marking")

## Key to diagram

  - Inventory transactions are represented by vertical arrows.

  - Receipts into inventory are represented by vertical arrows above the timeline.

  - Issues out of inventory are represented by vertical arrows below the timeline.

  - Above (or below) each vertical arrow, the value of the inventory transaction is specified in the format Quantity@Unitprice.

  - An inventory transaction value enclosed in brackets indicates that the inventory transaction is physically posted into inventory.

  - An inventory transaction value without brackets indicates that the inventory transaction is financially posted into inventory.

  - Each new receipt or issue transaction is designated with a new label.

  - Each vertical arrow is labeled with a sequential identifier, such as *1a*. The identifiers indicate the sequence of inventory transaction postings in the timeline.

  - Inventory closings are represented by a red vertical dashed line and the label Inventory Close.

  - Settlements that are performed by inventory close are represented by dotted red arrows going diagonally from a receipt to an issue.

## See also

[Specify an inventory model for inventory close](specify-an-inventory-model-for-inventory-close.md)

[About LIFO with physical value and marking](about-lifo-with-physical-value-and-marking.md)

[About LIFO Date with physical value and marking](about-lifo-date-with-physical-value-and-marking.md)

[About weighted average with physical value and marking](about-weighted-average-with-physical-value-and-marking.md)

[About weighted average date](about-weighted-average-date.md)

  


