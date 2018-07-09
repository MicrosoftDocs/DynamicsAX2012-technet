---
title: (ITA) About the calculation engine
TOCTitle: (ITA) About the calculation engine
ms:assetid: 8abe97a3-49ca-46f6-84d6-a7685b33bf70
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa498244(v=AX.60)
ms:contentKeyID: 36058469
ms.date: 05/02/2014
mtps_version: v=AX.60
f1_keywords:
- calculate fiscal LIFO
- fiscal LIFO
- calculation engine for fiscal LIFO
---

# (ITA) About the calculation engine [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can calculate the fiscal Last In, First Out (LIFO) value for internal and final reports that are based on the average inventory value or normal value. You can also include the work in progress (WIP) of production items in the calculation.

## The basis for the calculation of the average inventory value

The calculation of the average inventory value includes purchased and produced items, and is based on the financial cost amount of the items.

The financial cost amount is the total of the **Financial cost amount** and **Adjustment** fields in the **Transactions** form.

If the cost of an item has not yet been updated against a vendor invoice, the physical cost amount in the **Physical cost amount** field is used instead of the cost amount.


> [!NOTE]
> <P>In addition to purchased and produced items, the final report also includes goods that have been received but not yet invoiced.</P>



## Purchased items

The calculation of purchased items is based on the acquisition cost minus value added tax (VAT).

## Produced items

The calculation of produced items is based on the production cost posted in General ledger. In some cases, the cost of unfinished production orders (work in progress) must be included. For more information, see the last section in this topic.


> [!TIP]
> <P>When working with credit lines, mark item transactions against specific purchase orders to help make sure that a correct crediting amount is registered. For information about how to set up marking, see <A href="mark-orders.md">Mark orders</A>.</P>



## Discounts

Discounts are either included in or excluded from the fiscal LIFO calculation, depending on the setup of the costing profile. The inventory value always matches the value that has been posted as a transaction with a type of **Inventory, receipt** in General ledger.

## Normal value

The inventory value is based on the average inventory value for the year. If the following applies, it is allowed by law to calculate the value of the inventory according to the average purchase price in the last period of the year:

  - The price increase in the last period was negative.

  - The organization experiences a depreciation of items in stock.

This is referred to as the normal value.

If you change the inventory value to the normal value, the change applies to the current year and all previous years.

You can calculate the normal value automatically or you can set it manually. When calculated automatically, the normal value is set to the average purchase price of items for the calculation period (month, quarter, or half year). The normal value is not set to the average for the year.

You can calculate the normal value for fiscal LIFO reporting groups or for individual items.

## Normal value example

The following example illustrates how using the normal value affects the calculation of the inventory value. The normal value is set to be applied if the average for the last month of the year is at least 5 percent less than the average inventory value for the year.

The first table lists the inventory values that are based on the year's average, without using the normal value.

<table>
<colgroup>
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Grand total</p></th>
<th><p>Year</p></th>
<th><p>Remaining quantity</p></th>
<th><p>Unit value by using the average method</p></th>
<th><p>Total</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td></td>
<td><p>2011</p></td>
<td><p>10</p></td>
<td><p>25</p></td>
<td><p>250</p></td>
</tr>
<tr class="even">
<td></td>
<td><p>2012</p></td>
<td><p>5</p></td>
<td><p>30</p></td>
<td><p>150</p></td>
</tr>
<tr class="odd">
<td></td>
<td><p>2013</p></td>
<td><p>1</p></td>
<td><p>35</p></td>
<td><p>35</p></td>
</tr>
<tr class="even">
<td></td>
<td><p>2014</p></td>
<td><p>0</p></td>
<td><p>0</p></td>
<td><p>0</p></td>
</tr>
<tr class="odd">
<td></td>
<td><p>2015</p></td>
<td><p>10</p></td>
<td><p>50</p></td>
<td><p>500</p></td>
</tr>
<tr class="even">
<td></td>
<td><p>2016</p></td>
<td><p>2</p></td>
<td><p>35</p></td>
<td><p>70</p></td>
</tr>
<tr class="odd">
<td><p>2016</p></td>
<td></td>
<td><p>28</p></td>
<td><p>35.90</p></td>
<td><p>1005</p></td>
</tr>
</tbody>
</table>


During the last month of 2016, the price of items in item group XYZ drops significantly. This results in an average purchase price of 20 for the month. Because an average purchase price of 20 is at least 5 percent less than the average inventory value of 35.90, the normal value is applied.

The normal value is 20, and the inventory value is set to 20 for all items in item group XYZ for 2016 and previous years.

<table>
<colgroup>
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Grand total</p></th>
<th><p>Year</p></th>
<th><p>Remaining quantity</p></th>
<th><p>Unit value by using the normal method</p></th>
<th><p>Total</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td></td>
<td><p>2011</p></td>
<td><p>10</p></td>
<td><p>20</p></td>
<td><p>200</p></td>
</tr>
<tr class="even">
<td></td>
<td><p>2012</p></td>
<td><p>5</p></td>
<td><p>20</p></td>
<td><p>100</p></td>
</tr>
<tr class="odd">
<td></td>
<td><p>2013</p></td>
<td><p>1</p></td>
<td><p>20</p></td>
<td><p>20</p></td>
</tr>
<tr class="even">
<td></td>
<td><p>2014</p></td>
<td><p>0</p></td>
<td><p>0</p></td>
<td><p>0</p></td>
</tr>
<tr class="odd">
<td></td>
<td><p>2015</p></td>
<td><p>10</p></td>
<td><p>20</p></td>
<td><p>200</p></td>
</tr>
<tr class="even">
<td></td>
<td><p>2016</p></td>
<td><p>2</p></td>
<td><p>20</p></td>
<td><p>40</p></td>
</tr>
<tr class="odd">
<td><p>2016</p></td>
<td></td>
<td><p>28</p></td>
<td><p>20</p></td>
<td><p>560</p></td>
</tr>
</tbody>
</table>


## Normal value calculation

When you start the calculation of fiscal LIFO from a fiscal LIFO journal, you can specify whether to apply the normal value in the calculation. The options in the fiscal LIFO reporting group determine whether the calculation is automatic or manual. If you have items that are calculated individually, you can specify for an individual item whether the calculation should be automatic or manual.

## WIP in the calculation of inventory value

If the production time is very long, WIP items must be included when you calculate the inventory value.

To control whether WIP items should be included in the calculation, you define the maximum number of days for a production period before WIP items are included. When you calculate fiscal LIFO from a fiscal LIFO journal, you can specify that you want to include WIP items. For information about how to define the WIP period and request a WIP calculation in a journal, see [(ITA) Calculate fiscal LIFO journal lines](ita-calculate-fiscal-lifo-journal-lines.md).

The status of a production line must be **Started** or **Reported as finished** to be included in the WIP calculation. You can check the status of a production line in the **Status** field in the **Production orders** form.

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

