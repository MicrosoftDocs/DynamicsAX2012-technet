---
title: About LIFO Date with physical value and marking
TOCTitle: About LIFO Date with physical value and marking
ms:assetid: a8790364-b8c1-4764-bab7-1d5e0d71b4bf
ms:mtpsurl: https://technet.microsoft.com/library/Gg243064(v=AX.60)
ms:contentKeyID: 36058886
author: tfehr
ms.author: daxcpft
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# About LIFO Date with physical value and marking 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Last in, First out Date (LIFO Date) is an inventory model based on the LIFO principle. Issues from inventory are settled against the last receipts into inventory based on the date of the inventory transaction. By using LIFO Date, if there is no receipt before the issue, the issue is settled against any receipts that occur after the date of the issue. Several issues on the same date may be settled in the order of last issue, last receipt.

When using LIFO Date, you can mark inventory transactions so that a specific item receipt is settled against a specific issue instead of using the LIFO Date rule.

We recommend a periodic inventory closing when you use the LIFO Date inventory model.

The following examples illustrate the effect of using LIFO Date with three different configurations:

  - LIFO Date without the Include physical value option

  - LIFO Date with the Include physical value option

  - LIFO Date with marking

## LIFO Date without the Include physical value option

In this LIFO Date illustration, the item model group is not marked to include physical value.

The following transactions are illustrated in the graphic that is shown here:

  - 1a. Inventory physical receipt for a quantity of 1 at a cost of USD 10.00 each.

  - 1b. Inventory financial receipt for a quantity of 1 at a cost of USD 10.00 each.

  - 2a. Inventory physical receipt for a quantity of 1 at a cost of USD 20.00 each.

  - 2b. Inventory financial receipt for a quantity of 1 at a cost of USD 20.00 each.

  - 3a. Inventory physical receipt for a quantity of 1 at a cost of USD 25.00 each.

  - 4a. Inventory physical issue for a quantity of 1 at a cost price of USD 15.00 (running average of financially updated transactions).

  - 4b. Inventory financial issue for a quantity of 1 at a cost price of USD 15.00 (running average of financially updated transactions).

  - 5a. Inventory physical receipt for a quantity of 1 at a cost of USD 30.00 each.

  - 5b. Inventory financial receipt for a quantity of 1 at a cost of USD 30.00 each.

  - 6\. Inventory close is performed. Based on the LIFO Date method, the last financially updated issue will be settled to the last financially updated receipt by date. An adjustment of USD 5.00 will be made on the issue transaction. These transactions will be settled to each other.

The new running average cost price reflects the average of the financially updated transactions at USD 15.00.

The following diagram illustrates the effects of choosing the LIFO Date inventory model without the **Include physical value** option.

![LIFO Date with Include Physical Value](images/Gg243064.LIFODatewithoutIncludePhysicalValue(AX.60).gif "LIFO Date with Include Physical Value")

**Key to diagram**

  - Inventory transactions are represented by vertical arrows.

  - Receipts into inventory are represented by vertical arrows earlier in this section the timeline.

  - Issues out of inventory are represented by vertical arrows below the timeline.

  - Above (or below) each vertical arrow, the value of the inventory transaction is specified in the format Quantity@Unitprice.

  - An inventory transaction value enclosed in brackets indicates that the inventory transaction is physically posted into inventory.

  - An inventory transaction value without brackets indicates that the inventory transaction is financially posted into inventory.

  - Each new receipt or issue transaction is designated with a new label.

  - Each vertical arrow is labeled with a sequential identifier, such as *1a*. The identifiers indicate the sequence of inventory transaction postings in the timeline.

  - Inventory closings are represented by a red vertical dashed line and the label Inventory Close.

  - Settlements that are performed by inventory close are represented by dotted red arrows going diagonally from a receipt to an issue.

## LIFO Date with the Include physical value option

You can select the **Include physical value** check box for an item in the **Item model groups** form. Then, Microsoft Dynamics AX will use both physical and financial receipt transactions to calculate the running average cost price. Where applicable, the system will also make adjustments to the physically updated issue transaction. When the **Include physical value** box is cleared, inventory close with the LIFO Date inventory model will make settlements only to transactions that are financially updated.

In this LIFO Date illustration, the item model group is marked to include physical value.

The following transactions are illustrated in the graphic that is shown here:

  - 1a. Inventory physical receipt for a quantity of 1 at a cost of USD 10.00 each.

  - 1b. Inventory financial receipt for a quantity of 1 at a cost of USD 10.00 each.

  - 2a. Inventory physical receipt for a quantity of 1 at a cost of USD 20.00 each.

  - 2b. Inventory financial receipt for a quantity of 1 at a cost of USD 20.00 each.

  - 3a. Inventory physical receipt for a quantity of 1 at a cost of USD 25.00 each.

  - 4a. Inventory physical issue for a quantity of 1 at a cost price of USD 18.33 each (running average of financially updated transactions).

  - 4b. Inventory financial issue for a quantity of 1 at a cost price USD 18.33 each (running average of financially updated transactions).

  - 5a. Inventory physical receipt for a quantity of 1 at a cost of USD 30.00 each.

  - 5b. Inventory financial receipt for a quantity of 1 at a cost of USD 30.00 each.

  - 6\. Inventory close is performed. Based on the LIFO Date method, the last updated issue will be adjusted or settled to the last updated receipt by date. These transactions will not be settled by each other because the financial receipt transaction is adjusted to a physical update transaction. Instead only an adjustment of USD 6.67 will be made on the issue transaction.

The new running average cost price reflects the average of the financially updated transactions at USD 20.00.

The following diagram illustrates the effects of choosing the LIFO inventory model with the **Include physical value** option.

![LIFO Date with Include Physical Value](images/Gg243064.LIFODatewithIncludePhysicalValue(AX.60).gif "LIFO Date with Include Physical Value")

**Key to diagram**

  - Inventory transactions are represented by vertical arrows.

  - Receipts into inventory are represented by vertical arrows above the timeline.

  - Issues out of inventory are represented by vertical arrows below the timeline.

  - Above (or below) each vertical arrow, the value of the inventory transaction is specified in the format Quantity@Unitprice..

  - An inventory transaction value enclosed in brackets indicates that the inventory transaction is physically posted into inventory.

  - An inventory transaction value without brackets indicates that the inventory transaction is financially posted into inventory.

  - Each new receipt or issue transaction is designated with a new label.

  - Each vertical arrow is labeled with a sequential identifier, such as *1a*. The identifiers indicate the sequence of inventory transaction postings in the timeline.

  - Inventory closings are represented by a red vertical dashed line and the label Inventory Close.

  - Settlements that are performed by inventory close are represented by dotted red arrows going diagonally from a receipt to an issue.

## LIFO Date with marking

Marking is process in Microsoft Dynamics AX that lets you link, or mark, an issue transaction to a receipt transaction. Marking can occur either before or after a transaction is posted. You can use marking when you want to make sure of the exact cost of the inventory when the transaction is posted or when the inventory close is performed.

For example, suppose the Customer Service department accepted a rush order from an important customer. Because this is a rush order, you will have to pay more for this item to service your customer’s request. You must make sure that the cost of this inventory item is reflected in the margin, or cost of goods sold (COGS), for this sales order invoice.

When the purchase order is posted, the inventory is received at a cost of USD 120.00. If this sales order document is marked to the purchase order before the packing slip or invoice is posted, the COGS will be USD 120.00. It will not be the current running average cost for the item. If the sales order packing slip or invoice is posted before the marking occurs, the COGS will be posted at the running average cost price.

Before Inventory close is performed these two transactions can still be marked to each other.

For example, a receipt transaction is marked for an issue transaction. Then the valuation method defined in the item’s item model group will be disregarded and Microsoft Dynamics AX will settle these transactions to each other.

You can mark an issue transaction to a receipt before the transaction is posted. Open the **Sales order** form, select a transaction line, and then click the **Inventory** button on the transaction line and select **Marking**. The **Marking** form will open and display all the open receipt transactions. You can then select one of these transactions to match to, or mark, this issue transaction.

You can mark an issue transaction to a receipt after the transaction has been posted. Navigate to the inventory item on the **Inventory transactions** form and then click the **Transaction** button. Select the issue transaction that you want to mark, and then click the **Inventory** button and select **Marking**. The **Marking** form will open and display all the open receipt transactions. You can then select one of these transactions to match to, or mark, this issue transaction.

The following transactions are illustrated in the graphic that is shown here:

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

The following diagram illustrates the effects of choosing the LIFO inventory model with marking between issues and receipts.

![LIFO Date with Marking](images/Gg243064.LIFODatewithMarking(AX.60).gif "LIFO Date with Marking")

**Key to diagram**

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

[About FIFO with physical value and marking](about-fifo-with-physical-value-and-marking.md)

[About LIFO with physical value and marking](about-lifo-with-physical-value-and-marking.md)

[About weighted average with physical value and marking](about-weighted-average-with-physical-value-and-marking.md)

[About weighted average date](about-weighted-average-date.md)

  


