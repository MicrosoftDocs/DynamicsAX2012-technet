---
title: (ITA) About fiscal LIFO workflow
TOCTitle: (ITA) About fiscal LIFO workflow
ms:assetid: eb6ea692-bc8e-43bc-9b06-fd7c2a4b8ab1
ms:mtpsurl: https://technet.microsoft.com/library/Aa551504(v=AX.60)
ms:contentKeyID: 36059869
author: Khairunj
ms.date: 05/02/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Italy
---

# (ITA) About fiscal LIFO workflow 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can use the fiscal Last In, First Out (LIFO) calculation to create a yearly report that declares the value of your inventory. The report can be used as the basis for a tax report.

To calculate fiscal LIFO, all items in stock must be set up to be included in the fiscal LIFO calculation. However, you can exclude individual items.

The calculation for the final yearly fiscal LIFO report is set up in a journal, and the report is printed from the journal. You can also create several internal reports for your own reference. These can serve as drafts for the final report.

Various methods can be used to control how the inventory and the contents of the yearly report are assessed. For example, you can set the value to a normal value or you can include work in progress in the calculation. For more information, see [(ITA) About the calculation engine](ita-about-the-calculation-engine.md).

## Fiscal LIFO calculations

You must attach all items on the **Released products** list page to a fiscal LIFO reporting group to calculate fiscal LIFO. You can also exclude items from the calculation by specifying each item to be excluded.

## Exclude an item from the fiscal LIFO calculation

1.  Click **Product information management** \> **Common** \> **Released products**.

2.  Double-click an item to open the **Released product details** form.

3.  Click the **Manage costs** tab.

4.  Select the **Avoid LIFO calculation** check box to exclude the item from the fiscal LIFO calculation.
    

    > [!NOTE]
    > <P>Items of the <STRONG>Service</STRONG> type are created when this check box is selected.</P>



5.  Close the form.

## Inventory value

The yearly average value of an inventory item is calculated as the financial value of purchased plus produced items divided by the current quantity. If the stock from previous years has decreased, the value of the items that remain in stock is calculated according to the LIFO principle.

## Example of the LIFO principle applied to an item group

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Year</p></th>
<th><p>Number of items</p></th>
<th><p>Total value</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>2009</p></td>
<td><p>10</p></td>
<td><p>100 (EUR 10 per item)</p></td>
</tr>
<tr class="even">
<td><p>2010</p></td>
<td><p>15</p></td>
<td><p>200 (EUR 20 per item)</p></td>
</tr>
<tr class="odd">
<td><p>2011</p></td>
<td><p>5</p></td>
<td><p>100 (EUR 20 per item)</p></td>
</tr>
</tbody>
</table>


At the start of 2011, you have 30 items in stock. By the end of the year, you have nine items left. The amount of stock has decreased by 21 items.

The decrease in stock is deducted in the following order, where items that were most recently added to the stock are deducted first.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Year</p></th>
<th><p>Items deducted</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>2011</p></td>
<td><p>5 (EUR 20 per item)</p></td>
</tr>
<tr class="even">
<td><p>2010</p></td>
<td><p>15 (EUR 20 per item)</p></td>
</tr>
<tr class="odd">
<td><p>2009</p></td>
<td><p>1 (EUR 10 per item)</p></td>
</tr>
</tbody>
</table>


By the end of 2011, the value of the inventory is 9 X 10 = EUR 90. That is, the nine remaining items in stock have appreciated by EUR 10 per item, which is the value registered for the items in 2009.

## See also

[(ITA) About internal and final reports](ita-about-internal-and-final-reports.md)

[(ITA) Set up fiscal LIFO reporting groups](ita-set-up-fiscal-lifo-reporting-groups.md)

[(ITA) Calculate fiscal LIFO journal lines](ita-calculate-fiscal-lifo-journal-lines.md)

  


