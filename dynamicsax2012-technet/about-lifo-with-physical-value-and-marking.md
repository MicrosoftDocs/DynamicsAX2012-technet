---
title: About LIFO with physical value and marking
TOCTitle: About LIFO with physical value and marking
ms:assetid: 83869272-ea6e-4afa-b486-b7de6e882c72
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Gg213162(v=AX.60)
ms:contentKeyID: 36058377
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# About LIFO with physical value and marking [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Last in, First out (LIFO) is an inventory model in which the last (newest) receipts are issued first. Issues from inventory are settled against the last receipts into inventory based on the date of the inventory transaction.

When using LIFO, you have the option of marking inventory transactions so that a specific item issue is settled against a specific receipt instead of using the LIFO rule.

We recommend a periodic inventory closing when you use the LIFO inventory model.

The following examples illustrate the impact of using LIFO with three different configurations:

  - LIFO without the **Include physical value** option

  - LIFO with the **Include physical value** option

  - LIFO with marking

## LIFO without the Include physical value option

In this LIFO illustration, the item model group is not marked to include physical value.

The following transactions are illustrated in the graphic below:

  - 1a. Inventory physical receipt for a quantity of 1 at a cost of USD 10.00 each.

  - 1b. Inventory financial receipt for a quantity of 1 at a cost of USD 10.00 each.

  - 2a. Inventory physical receipt for a quantity of 1 at a cost of USD 20.00 each.

  - 2b. Inventory financial receipt for a quantity of 1 at a cost of USD 20.00 each.

  - 3a. Inventory physical receipt for a quantity of 1 at a cost of USD 25.00 each.

  - 4a. Inventory physical receipt for a quantity of 1 at a cost of USD 30.00 each.

  - 4b. Inventory financial receipt for a quantity of 1 at a cost of USD 30.00 each.

  - 5a. Inventory physical issue for a quantity of 1 at a cost price of USD 20.00 each (running average of financially updated transactions).

  - 5b. Inventory financial issue for a quantity of 1 at a cost price of USD 20.00 each (running average of financially updated transactions).

  - 6\. Inventory close is performed. Based on the LIFO method, the last financially updated issue will be settled to the last financially updated receipt. An adjustment of USD 10.00 will be made on the issue transaction.

The new running average cost price reflects the average of the financially updated transactions at USD 15.00.

The following diagram illustrates this series of transactions with the effects of choosing the LIFO inventory model without the **Include physical value** option.

![LIFO without Include Physical Value](images/Gg213162.LIFOwithoutIncludePhysicalValue(AX.60).gif "LIFO without Include Physical Value")

**Key to diagram**

  - Inventory transactions are represented by vertical arrows.

  - Receipts into inventory are represented by vertical arrows above the timeline.

  - Issues out of inventory are represented by vertical arrows below the timeline.

  - Above (or below) each vertical arrow, the value of the inventory transaction is specified in the format *Quantity@Unit price*.

  - An inventory transaction value surrounded by brackets indicates that the inventory transaction is physically posted into inventory.

  - An inventory transaction value without brackets indicates that the inventory transaction is financially posted into inventory.

  - Each new receipt or issue transaction is designated with a new label.

  - Each vertical arrow is labeled with a sequential identifier, such as *1a*. The identifiers indicate the sequence of inventory transaction postings in the timeline.

  - Inventory closings are represented by a red vertical dashed line and the label Inventory Close.

  - Settlements that are performed by inventory close are represented by dotted red arrows going diagonally from a receipt to an issue.

## LIFO with the Include physical value option

If the **Include physical value** box is selected for an item in the **Item model groups** form, Microsoft Dynamics AX will use both physical and financial receipt transactions to calculate the running average cost price. Where applicable, the system will also make adjustments to the physically updated issue transaction. When the **Include physical value** box is cleared, inventory close with the LIFO inventory model will make settlements only to transactions that are financially updated.

The following transactions are illustrated in the graphic below:

  - 1a. Inventory physical receipt for a quantity of 1 at a cost of USD 10.00 each.

  - 1b. Inventory financial receipt for a quantity of 1 at a cost of USD 10.00 each.

  - 2a. Inventory physical receipt for a quantity of 1 at a cost of USD 20.00 each.

  - 2b. Inventory financial receipt for a quantity of 1 at a cost of USD 20.00 each.

  - 3a. Inventory physical receipt for a quantity of 1 at a cost of USD 25.00 each.

  - 4a. Inventory physical receipt for a quantity of 1 at a cost of USD 30.00 each.

  - 4b. Inventory financial receipt for a quantity of 1 at a cost of USD 30.00 each.

  - 5a. Inventory physical issue for a quantity of 1 at a cost price of USD 21.25 each (running average of financial and physical updated transactions).

  - 5b. Inventory financial issue for a quantity of 1 at a cost price of USD 21.25 each (running average of financial and physical updated transactions).

  - 6a. Inventory physical issue for a quantity of 1 at a cost price of USD 21.25 each.

  - 7\. Inventory close is performed. Based on the LIFO method, the last issue transaction will be adjusted or settled to the last updated receipt.

Transaction 6a will be adjusted to the receipt transaction 4b. The system will not settle these transactions since the receipt is updated only physically and not financially. Instead, only an adjustment of USD 8.75 will be posted to the physical issue transaction.

Transaction 5b will be adjusted to the physical receipt transaction 3a. The system will not settle these transactions since they are not both financially updated. Instead, only an adjustment of negative USD 3.75 will be made to this issue transaction.

The new running average cost price reflects the average of the financially and physically updated transactions at USD 20.00.

The following diagram illustrates this series of transactions with the effects of choosing the LIFO inventory model with the **Include physical value** option.

![LIFO with Include Physical Value](images/Gg213162.LIFOwithIncludePhysicalValue(AX.60).gif "LIFO with Include Physical Value")

**Key to diagram**

  - Inventory transactions are represented by vertical arrows.

  - Receipts into inventory are represented by vertical arrows above the timeline.

  - Issues out of inventory are represented by vertical arrows below the timeline.

  - Above (or below) each vertical arrow, the value of the inventory transaction is specified in the format *Quantity@Unit price*.

  - An inventory transaction value enclosed in brackets indicates that the inventory transaction is physically posted into inventory.

  - An inventory transaction value without brackets indicates that the inventory transaction is financially posted into inventory.

  - Each new receipt or issue transaction is designated with a new label.

  - Each vertical arrow is labeled with a sequential identifier, such as *1a*. The identifiers indicate the sequence of inventory transaction postings in the timeline.

  - Inventory closings are represented by a red vertical dashed line and the label Inventory Close.

  - Settlements that are performed by inventory close are represented by dotted red arrows going diagonally from a receipt to an issue.

## LIFO with marking

Marking is process in Microsoft Dynamics AX that lets you link, or mark, an issue transaction to a receipt transaction. Marking can occur either before or after a transaction is posted. You can use marking when you want to make sure of the exact cost of the inventory when the transaction is posted or when the inventory close is performed.

For example, suppose the Customer Service department accepted a rush order from an important customer. Because this is a rush order, you will have to pay more for this item to service your customer’s request. You must be certain the cost of this inventory item is reflected in the margin, or cost of goods sold (COGS), for this sales order invoice.

When the purchase order is posted, the inventory is received at a cost of USD 120.00. If this sales order document is marked to the purchase order before the packing slip or invoice is posted, the COGS will be USD 120.00 instead of the current running average cost for the item. If the sales order packing slip or invoice is posted before the marking occurs, the COGS will be posted at the running average cost price.

Before inventory close is performed these two transactions can still be marked to each other.

To mark an issue transaction to a receipt before the transaction is posted:

1.  Open the **Sales order** form.

2.  Select a transaction line.

3.  Click the **Inventory** button on the transaction line and select **Marking**.

4.  The **Marking** form will open and display all the open receipt transactions.

5.  You can then select one of these transactions to match to, or mark, this issue transaction.

To mark an issue transaction to a receipt after the transaction is posted, navigate to the **Transactions on Item** form and then click the **Transaction**. Select the issue transaction that you want to mark, and then click the **Inventory** button and select **Marking**. The **Marking** form will open and display all the open receipt transactions. You can then select one of these transactions to match to, or mark, this issue transaction.

The following transactions are illustrated in the graphic below:

  - 1a. Inventory physical receipt for a quantity of 1 at a cost of USD 10.00 each.

  - 1b. Inventory financial receipt for a quantity of 1 at a cost of USD 10.00 each.

  - 2a. Inventory physical receipt for a quantity of 1 at a cost of USD 20.00 each.

  - 2b. Inventory financial receipt for a quantity of 1 at a cost of USD 20.00 each.

  - 3a. Inventory physical receipt for a quantity of 1 at a cost of USD 25.00 each.

  - 4a. Inventory physical receipt for a quantity of 1 at a cost of USD 30.00 each.

  - 4b. Inventory financial receipt for a quantity of 1 at a cost of USD 30.00 each.

  - 5a. Inventory physical issue for a quantity of 1 at a cost price of USD 21.25 each (running average of financial and physical updated transactions).

  - 5b. Inventory financial issue for a quantity of 1 is marked to the inventory receipt 2b before the transaction is posted. This transaction is posted with a cost price of USD 20.00 each.

  - 6a. Inventory physical issue for a quantity of 1 at a cost price of USD 21.25 each.

  - 7\. Inventory close is performed. Since the financially updated FIFO transaction is marked to an existing receipt, these transactions are settled to each other and no adjustment is made.

The new running average cost price reflects the average of the financially and physically updated transactions at USD 27.50.

The following diagram illustrates this series of transactions with the effects of choosing the LIFO inventory model with marking between issues and receipts.

![LIFO with Marking](images/Gg213162.LIFOwithMarking(AX.60).gif "LIFO with Marking")

**Key to diagram**

  - Inventory transactions are represented by vertical arrows.

  - Receipts into inventory are represented by vertical arrows above the timeline.

  - Issues out of inventory are represented by vertical arrows below the timeline.

  - Above (or below) each vertical arrow, the value of the inventory transaction is specified in the format *Quantity@Unit price*.

  - An inventory transaction value enclosed in brackets indicates that the inventory transaction is physically posted into inventory.

  - An inventory transaction value without brackets indicates that the inventory transaction is financially posted into inventory.

  - Each new receipt or issue transaction is designated with a new label.

  - Each vertical arrow is labeled with a sequential identifier, such as *1a*. The identifiers indicate the sequence of inventory transaction postings in the timeline.

  - Inventory closings are represented by a red vertical dashed line and the label Inventory Close.

  - Settlements that are performed by inventory close are represented by dotted red arrows going diagonally from a receipt to an issue.

## See also

[Specify an inventory model for inventory close](specify-an-inventory-model-for-inventory-close.md)

[About FIFO with physical value and marking](about-fifo-with-physical-value-and-marking.md)

[About LIFO Date with physical value and marking](about-lifo-date-with-physical-value-and-marking.md)

[About weighted average with physical value and marking](about-weighted-average-with-physical-value-and-marking.md)

[About weighted average date](about-weighted-average-date.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

