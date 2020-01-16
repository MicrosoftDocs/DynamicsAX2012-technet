---
title: About moving average
TOCTitle: About moving average
ms:assetid: c297cafe-18a8-468f-a598-41cc49caf6c5
ms:mtpsurl: https://technet.microsoft.com/library/Hh597235(v=AX.60)
ms:contentKeyID: 39519308
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- moving average
audience: Application User
ms.search.region: Global
---

# About moving average 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Moving average is a perpetual costing method. Moving average is based on the average principle, where the costs on inventory issues do not change when the purchase cost does. The difference is capitalized and is based on a proportional calculation. The amount that remains is expensed.


> [!NOTE]
> <P>When you use moving average, inventory settlements and inventory marking are not supported. Inventory close does not affect products that have moving average as the inventory model group, and it does not generate any settlements between the transactions.</P>



The following are prerequisites when you use moving average cost as a costing method.

1.  In the **Item model groups** form, set up an item model group that has **Moving average** selected in the **Inventory model** field.
    

    > [!NOTE]
    > <P>By default, when <STRONG>Moving average</STRONG> is selected, the <STRONG>Post physical inventory</STRONG> and <STRONG>Post financial inventory</STRONG> fields are also selected.</P>



2.  In the **Posting** form, assign accounts to the **Price difference for moving average** and the **Cost revaluation for moving average** accounts on the **Inventory** tab. You use the **Price difference for moving average** account when cost has to be proportionally expensed. This occurs because of a difference in cost between a purchase receipt and the purchase invoice, and because of a difference between the original inventory quantity and the current on-hand quantity. Use the **Cost revaluation for moving average** account when you want to adjust the moving average cost for a product to a new unit price.

3.  In the **Products** form, assign the moving average item model group to the product.


> [!NOTE]
> <P>The inventory close process only closes the accounting period. It does not affect products that have moving average assigned to them as an item model group.</P>



## Conversion to the moving average costing method

Products can be converted to use the moving average inventory valuation method. This type of conversion is usually done at the end of the year, after the last month of the current year is closed. It is done by using the product’s current costing model.

You can change your inventory costing method from a costing method that is based on average cost or standard cost to a method that is based on moving average. If you are changing your costing method from a standard costing method to a moving average method, you have to complete the following tasks:

1.  Make adjustments to get inventory quantities and values down to 0 (zero).

2.  After the inventory value and quantity are 0 (zero), change the item model group to moving average.

3.  Make adjustments to get the quantity and value back into inventory.

You cannot change your inventory costing method from a moving average method to a first in, first out (FIFO) method, a last in, first out (LIFO) method, or a weighted average method.


> [!NOTE]
> <P>Converting from standard cost to moving weighted average is a manual process.</P>



The following examples illustrate the effect of using the moving average costing method. There are four configurations:

  - Purchase order and proportionally expensed cost difference

  - Moving average product and inventory adjustment

  - Moving average with production

  - Moving average with a backdated transaction

## Purchase order and proportionally expensed cost difference

With moving average, the product’s cost is determined by the purchase receipt. When the purchase invoice is posted, if there is a difference in cost between the purchase receipt and the purchase invoice, the difference is proportionally adjusted to the current products in stock, and any remaining amount is expensed.

In this example, a purchase order is created and received at one cost, and the purchase invoice is posted with a different cost.

1.  Create a purchase order for a quantity of 2 and a unit price of 10.00.

2.  Create a purchase receipt of the product.

3.  Create a sales order for a quantity of 1 and a unit price of 10.00.

4.  Create a purchase invoice for a quantity of 2 and a unit price of 12.00.

The difference in unit price, 2.00, is posted to the **Price difference for moving average** account when the purchase invoice is posted. The reason is that two products were purchased for a cost of 20.00. One of the products was sold for a unit price of 10.00. The purchase invoice was posted at a unit price of 12.00 with a quantity of 2. The unit price of the product cannot be posted at 14.00.

## Moving average product and inventory adjustment

If you need to adjust the moving average cost of a product, inventory adjustments are allowed as of today’s date. You cannot backdate an inventory adjustment to correct the moving average cost of a product. You cannot have the cost flow through subsequent transactions.

In this example, the moving average cost is adjusted for a product.

1.  Select the product you want to adjust the moving average cost for.
    

    > [!NOTE]
    > <P>The <STRONG>Revaluation for moving average</STRONG> form examines the inventory available for a product.</P>

    
    The product selected has a posted quantity of 1, a posted a value of 12.00, a posted unit cost of 12.00, and a unit cost of 12.00.

2.  Now update the unit cost field to 16.00. The system calculates the remaining fields.

3.  The adjustment is posted.


> [!NOTE]
> <P>You can only adjust the moving average cost as of today’s date.</P>



In the **Settlements for voucher** form, you can see an adjustment of 4.00 posted to the **Cost revaluation for moving average** account.

## Moving average with production

Moving average supports produced items. If you plan to use moving average in a production environment, the **Use estimated cost price** check box in the **Production control parameters** form should be marked. This means that the cost price that is calculated during estimation is used instead of the actual BOM calculation cost price.

## Moving average with a backdated transaction

Backdated transactions are assigned the current moving average cost, and the product’s physical quantity is updated, but the product’s moving average cost is not affected.

In this moving average example, a backdated transaction for a moving average product is posted.

1.  Create an inventory adjustment for the moving average product for a quantity of 1 and a cost of 20.00.

2.  The inventory transaction history for the product would resemble the following:
    
      - An inventory transaction of 1, a cost of 16.00, a posting date of January 15, and a transaction date of January 15.
    
      - An inventory adjustment of 1, a cost of 20.00, a posting date of January 1, and a transaction date of January 15.

3.  Post the adjustment.

In the **Inventory transactions** form, you can see that 4.00 expensed as the current moving average for the product is 16.00. You can post in the past, but the difference in cost is expensed, so the moving average cost is not affected.

## Inventory value report

In this moving average example, the inventory value report is printed to support the current moving average calculation for a product. The **Inventory value** report can print the transactions in chronological order, together with the cost to support the moving average cost calculation of a product. The report displays the moving average cost for the product.

In the **Inventory value reports** form, a **Range** field has been added. You can select the **Transaction time** option or the **Posting date** option to sort the report. The **Posting date** option is how the report is traditionally printed. The **Transaction time** option is the actual date that the transaction is reported and the moving average cost for the product is updated.

You would print the **Inventory value** report by using the **Transaction time** sorting option if you want to see the moving average cost calculation over time.

The following table displays the transactions for the product that the report is printed for when the **Transaction time** sorting option is used.

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
<th><p>Transaction time</p></th>
<th><p>Date</p></th>
<th><p>Transaction type</p></th>
<th><p>Quantity</p></th>
<th><p>Amount</p></th>
<th><p>Average unit cost</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p></p></td>
<td><p>October 1</p></td>
<td><p>Beginning balance</p></td>
<td><p>0</p></td>
<td><p>0.00</p></td>
<td><p>0.00</p></td>
</tr>
<tr class="even">
<td><p>October 8</p></td>
<td><p>September 28</p></td>
<td><p>Backdated receipt</p></td>
<td><p>1</p></td>
<td><p>16.00</p></td>
<td><p>16.00</p></td>
</tr>
<tr class="odd">
<td><p>October 3</p></td>
<td><p>October 3</p></td>
<td><p>Purchase receipt</p></td>
<td><p>2</p></td>
<td><p>20.00</p></td>
<td><p>12.00</p></td>
</tr>
<tr class="even">
<td><p>October 5</p></td>
<td><p>October 5</p></td>
<td><p>Sales order</p></td>
<td><p>-1</p></td>
<td><p>-10.00</p></td>
<td><p>13.00</p></td>
</tr>
<tr class="odd">
<td><p>October 7</p></td>
<td><p>October 7</p></td>
<td><p>Purchase invoice</p></td>
<td><p></p></td>
<td><p>2.00</p></td>
<td><p>14.00</p></td>
</tr>
<tr class="even">
<td><p>October 8</p></td>
<td><p>October 8</p></td>
<td><p>Moving average revaluation</p></td>
<td><p></p></td>
<td><p>4.00</p></td>
<td><p>16.00</p></td>
</tr>
<tr class="odd">
<td><p></p></td>
<td><p>October 31</p></td>
<td><p>Total</p></td>
<td><p>2</p></td>
<td><p>32.00</p></td>
<td><p>16.00</p></td>
</tr>
</tbody>
</table>



> [!NOTE]
> <P>You cannot reconcile the general ledger with inventory by using the <STRONG>Transaction time</STRONG> sorting option. The report must be printed by using the <STRONG>Posting date</STRONG> option.</P>


  


