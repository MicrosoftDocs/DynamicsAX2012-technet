---
title: (RUS) Calculation of the storage service amount for items
TOCTitle: (RUS) Calculation of the storage service amount for items
ms:assetid: 11f313eb-d4e0-47e0-ac7f-7abf734664f0
ms:mtpsurl: https://technet.microsoft.com/library/JJ711401(v=AX.60)
ms:contentKeyID: 49387221
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Russia
---

# (RUS) Calculation of the storage service amount for items 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

The storage service amount for an item is calculated based on the calculation method. The calculation method can be selected for the stored item, price agreement, and item movement during the storage period.

To determine the calculation method for the storage service amount, you must define the following item types that have **Item** selected in the **Product type** field in the **Create product** form:

  - Storage items, such as electronic devices and edible items.

  - Storage calculation items, such as the storage service that is associated with user-defined formulas for storage calculation. For more information, see [(RUS) Create a calculation item and assign an inventory unit to the item](rus-create-a-calculation-item-and-assign-an-inventory-unit-to-the-item.md).

You must select the **Inventory profile**, **Owner**, and **Batch number** check boxes in the **Dimensions display** form when you create a calculation item and a storage item. You must also update the price agreements and the free storage days that are allowed for the calculation item, based on the contract that is signed for bailment. You must define an inventory unit to calculate the storage service amount, and you must assign a mathematical operator to the inventory unit. You must also associate the inventory unit with the calculation item. For more information, see [(RUS) Associate a calculation item with the items in storage](rus-associate-a-calculation-item-with-the-items-in-storage.md). The calculation item is associated with the storage item that is based on the combinations of customers, items, and warehouse relations. You can customize these combinations to suit your requirements. For more information, see [(RUS) Set up a matching priority and a number sequence to calculate a storage service amount](rus-set-up-a-matching-priority-and-a-number-sequence-to-calculate-a-storage-service-amount.md). The association between the calculation item and the storage item can be based on the following combinations:

  - Customer – Warehouse – Item

  - Customer – Item – Warehouse

  - Warehouse – Customer – Item

  - Warehouse – Item – Customer

  - Item – Customer – Warehouse

  - Item – Warehouse – Customer

Storage calculation operation journals are created for each item, based on the item movement. These journals contain details about the storage period, calculation item, storage item, storage service amount, owner, warehouse, and bailment contract. Journal lines are created for each transaction, based on the item movement date. You must calculate the balance quantity of storage items and then calculate the storage service amount for the items.

**Calculation of the balance quantity of storage items**

The balance quantity of items on each day is positive for receipt transactions and negative for expenditure transactions. The balance quantity of storage items is calculated based on the selected **Packing slip** and **Invoice** check boxes in the **Return** field group. If these check boxes are not selected, the item movement date is the date when the items are received or returned from the warehouse (the physical receipt or expenditure date). If one of the check boxes is selected, the item movement date is the date that follows the physical receipt or expenditure date of the item movement. You can adjust the balance quantity of items for the previous period during the current period.

Example 1 The balance quantity of storage items is calculated for the current period without adjusting the balance quantity of items for the previous period. The balance quantity of the storage item, pianos, is calculated for the period of May 1, 2012, to May 10, 2012, as illustrated in the following table.

<table style="width:100%;">
<colgroup>
<col style="width: 16%" />
<col style="width: 16%" />
<col style="width: 16%" />
<col style="width: 16%" />
<col style="width: 16%" />
<col style="width: 16%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Item</p></th>
<th><p>Date</p></th>
<th><p>Warehouse</p></th>
<th><p>Owner</p></th>
<th><p>Batch</p></th>
<th><p>Balance</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Piano</p></td>
<td><p>April 29, 2012</p></td>
<td><p>A</p></td>
<td><p>P1</p></td>
<td><p>1</p></td>
<td><p>–3</p></td>
</tr>
<tr class="even">
<td><p>Piano</p></td>
<td><p>May 1, 2012</p></td>
<td><p>A</p></td>
<td><p>P1</p></td>
<td><p>1</p></td>
<td><p>12</p></td>
</tr>
<tr class="odd">
<td><p>Piano</p></td>
<td><p>May 4, 2012</p></td>
<td><p>A</p></td>
<td><p>P1</p></td>
<td><p>1</p></td>
<td><p>9</p></td>
</tr>
<tr class="even">
<td><p>Piano</p></td>
<td><p>May 10, 2012</p></td>
<td><p>A</p></td>
<td><p>P1</p></td>
<td><p>1</p></td>
<td><p>5</p></td>
</tr>
</tbody>
</table>


Here, the pianos in batch 1 are stored in warehouse A for the owner, P1. On May 1, 2012, 15 pianos from batch 1 were received in warehouse A. On May 3, 2012, three pianos were returned from warehouse A. On May 7, 2012, four pianos were again returned from warehouse A. Therefore, the balance quantity of pianos for the period of May 1, 2012, to May 10, 2012, is eight.

Example 2 The balance quantity of storage items is calculated for the current period after the balance quantity of items is adjusted for the previous period. The balance quantity of the storage item, pianos, is calculated for the period of May 1, 2012, to May 10, 2012, as illustrated in the following table.

<table style="width:100%;">
<colgroup>
<col style="width: 16%" />
<col style="width: 16%" />
<col style="width: 16%" />
<col style="width: 16%" />
<col style="width: 16%" />
<col style="width: 16%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Item</p></th>
<th><p>Date</p></th>
<th><p>Warehouse</p></th>
<th><p>Owner</p></th>
<th><p>Batch</p></th>
<th><p>Balance</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Piano</p></td>
<td><p>May 1, 2012</p></td>
<td><p>A</p></td>
<td><p>P1</p></td>
<td><p>1</p></td>
<td><p>15</p></td>
</tr>
<tr class="even">
<td><p>Piano</p></td>
<td><p>May 4, 2012</p></td>
<td><p>A</p></td>
<td><p>P1</p></td>
<td><p>1</p></td>
<td><p>12</p></td>
</tr>
<tr class="odd">
<td><p>Piano</p></td>
<td><p>May 8, 2012</p></td>
<td><p>A</p></td>
<td><p>P1</p></td>
<td><p>1</p></td>
<td><p>8</p></td>
</tr>
<tr class="even">
<td><p>Piano</p></td>
<td><p>May 10, 2012</p></td>
<td><p>A</p></td>
<td><p>P1</p></td>
<td><p>1</p></td>
<td><p>8</p></td>
</tr>
</tbody>
</table>


Here, the pianos in batch 1 are stored in warehouse A for the owner, P1. On April 28, 2012, a day in the previous period, three pianos were returned from warehouse A. On May 1, 2012, 15 pianos from batch 1 were received in warehouse A, and because the balance quantity of pianos for the previous period must be adjusted during the current period, the balance on May 1, 2012, is 12. On May 3, 2012, three pianos were returned from warehouse A, and on May 11, 2012, four pianos were returned from warehouse A. Therefore, the balance quantity of pianos for the period of May 1, 2012, to May 11, 2012, is five.

**Calculation of the storage service amount**

The storage service amount is calculated based on the inventory unit, the price agreement, and the free storage days that are assigned to the calculation item. Example The storage service amount is calculated as follows: The inventory unit for the calculation item, Storage1, is quantity \* days, and the storage service amount is calculated for the period from May 1, 2012, to May 5, 2012, as illustrated in the following table.

<table style="width:100%;">
<colgroup>
<col style="width: 14%" />
<col style="width: 14%" />
<col style="width: 14%" />
<col style="width: 14%" />
<col style="width: 14%" />
<col style="width: 14%" />
<col style="width: 14%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Storage item</p></th>
<th><p>Date</p></th>
<th><p>Calculation item</p></th>
<th><p>Rate</p></th>
<th><p>Quantity</p></th>
<th><p>Volume</p></th>
<th><p>Currency</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Piano</p></td>
<td><p>May 1, 2012</p></td>
<td><p>Storage 1</p></td>
<td><p>10</p></td>
<td><p>15</p></td>
<td><p>15</p></td>
<td><p>RUB</p></td>
</tr>
<tr class="even">
<td><p>Piano</p></td>
<td><p>May 4, 2012</p></td>
<td><p>Storage</p></td>
<td><p>10</p></td>
<td><p>12</p></td>
<td><p>12</p></td>
<td><p>RUB</p></td>
</tr>
</tbody>
</table>


From May 1, 2012, to May 4, 2012, the quantity of the storage item, pianos, is 15. Based on the inventory unit that is assigned to the calculation item, quantity \* days = 15 \* 4 = 60. On May 5, 2012, the quantity of the storage item is 12, and the inventory unit, quantity \* days = 12 \* 1 = 12, is applied. The rate per unit for the item is RUB 10. The storage service amount is calculated as follows: Balance quantity of the storage item for the current period \* rate per unit of the storage item \[(60 + 12) \* 10\] = 720 The storage service amount for the period of May 1, 2012, to May 5, 2012, is RUB 720. If two free storage days are assigned to the calculation item, the storage service amount is calculated as follows: From May 1, 2012, to May 4, 2012: 15 \* 2 = 30 On May 5, 2012: 12 \* 1 = 12 The storage service amount for the period of May 1, 2012, to May 5, 2012, is RUB 420 (\[30 + 12\] \* 10).

## See also

[(RUS) Set up an inventory unit and unit operator to calculate the storage service amount](rus-set-up-an-inventory-unit-and-unit-operator-to-calculate-the-storage-service-amount.md)

  


