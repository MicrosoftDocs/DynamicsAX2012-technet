---
title: About cost prices, sales prices, and transfer prices in projects
TOCTitle: About cost prices, sales prices, and transfer prices in projects
ms:assetid: 6c213e6c-b925-4211-a050-80770f99f85c
ms:mtpsurl: https://technet.microsoft.com/library/Aa571201(v=AX.60)
ms:contentKeyID: 36966727
ms.date: 10/15/2014
mtps_version: v=AX.60
f1_keywords:
- sales prices
audience: Application User
ms.search.region: Global
---

# About cost prices, sales prices, and transfer prices in projects 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

In Microsoft Dynamics AX, you can use three types of prices in projects that you manage in **Project management and accounting**:

  - **Cost prices** – Set up cost prices for project hours and expenses. Cost prices do not apply to fees or subscriptions. Cost prices apply to all project types in Microsoft Dynamics AX.

  - **Sales prices** – Set up sales prices for project hours, expenses, fees, and subscriptions. Sales prices only apply to Time and material projects.

  - **Transfer prices** – Set up transfer prices for project hours and expenses. Transfer prices for hours are the sales prices that you charge a related legal entity for a project worker that the related legal entity borrows from your legal entity.

All three types of prices are applied when a transaction is entered into a journal.


> [!NOTE]
> <P>Cost prices and sales prices for items are set up in <STRONG>Inventory management</STRONG>. For information about how to create item prices, see <A href="https://technet.microsoft.com/library/hh803026(v=ax.60)">Item price (form)</A>.</P>



## About criteria for creating cost prices, sales prices, and transfer prices

When the system searches for a price in Microsoft Dynamics AX, the price that is selected is always the price that matches the most criteria.

For example, two prices have been created for a particular project. One price specifies an effective date and a project number. The other price specifies an effective date, a project number, and a specific worker. The price that specifies the worker as an additional criterion is selected.

The primary criterion for all price types is the effective date, or the date on which the price first applies. For sales prices, currency is also a mandatory criterion. After a price match is found by using these criteria, the secondary criteria are matched. In this matching, the price that has the most matching criteria is selected.

## Criteria for creating cost prices

An effective date is required in the definition of every cost price. You can define a cost price for any combination of an effective date and the following additional criteria:

  - **Project**

  - **Category**

  - **Worker**

## Criteria for creating sales prices

An effective date and a currency are required in the definition of every sales price. You can define a sales price for any combination of these criteria and the following additional criteria:

  - **Project**

  - **Category**

  - **Worker**

  - **Pricing**

  - **Transfer price model**

## Criteria for creating transfer prices

An effective date is required in the definition of every transfer price. You can define a transfer price for any combination of an effective date and the following additional criteria:

  - **Borrowing legal entity**

  - **Transaction type**
    

    > [!NOTE]
    > <P>This control is not available in versions of Microsoft Dynamics AX 2012 prior to cumulative update 7 for AX 2012 R2.</P>



  - **Project**

  - **Worker**

  - **Category**

  - **Sales currency**

  - **Transfer price model**
    

    > [!NOTE]
    > <P>This control is not available in versions of Microsoft Dynamics AX 2012 prior to cumulative update 7 for AX 2012 R2.</P>



  - **Pricing**

## Search priority for project prices

When the system searches for the price that should be applied for a transaction, the price that is selected is always the price that matches the most criteria.

For example, two prices have been created for a particular project. One price specifies an effective date and a project number. The other price specifies an effective date, a project number, and a specific worker. The price that specifies the worker as an additional criterion is selected.

## Search priority for cost prices

Cost prices are set up for categories, projects, and workers. The following table displays the search priority for cost prices. Search matches have a priority from 1 to 8 in the table.

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
<th><p>Priority</p></th>
<th><p>Project</p></th>
<th><p>Worker</p></th>
<th><p>Category</p></th>
<th><p>Effective date</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>1</p></td>
<td><p>x</p></td>
<td><p>x</p></td>
<td><p>x</p></td>
<td><p>x</p></td>
</tr>
<tr class="even">
<td><p>2</p></td>
<td><p>x</p></td>
<td><p>x</p></td>
<td><p></p></td>
<td><p>x</p></td>
</tr>
<tr class="odd">
<td><p>3</p></td>
<td><p></p></td>
<td><p>x</p></td>
<td><p>x</p></td>
<td><p>x</p></td>
</tr>
<tr class="even">
<td><p>4</p></td>
<td><p>x</p></td>
<td><p></p></td>
<td><p>x</p></td>
<td><p>x</p></td>
</tr>
<tr class="odd">
<td><p>5</p></td>
<td><p>x</p></td>
<td><p></p></td>
<td><p></p></td>
<td><p>x</p></td>
</tr>
<tr class="even">
<td><p>6</p></td>
<td><p></p></td>
<td><p>x</p></td>
<td><p></p></td>
<td><p>x</p></td>
</tr>
<tr class="odd">
<td><p>7</p></td>
<td><p></p></td>
<td><p></p></td>
<td><p>x</p></td>
<td><p>x</p></td>
</tr>
<tr class="even">
<td><p>8</p></td>
<td><p></p></td>
<td><p></p></td>
<td><p></p></td>
<td><p>x</p></td>
</tr>
</tbody>
</table>


## Search priority for sales prices

Sales prices are set up for categories, workers, projects, transaction dates, and currencies. The following table displays the search priority for sales prices. Search matches have a priority from 1 to 8 in the table. The currency and the effective date are the primary criteria. When prices have been found that have the correct currency, the search continues for a project and then a worker. The system then searches for a category to find the most detailed match. The last criterion that the system searches for is the transaction date.

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
<th><p>Priority</p></th>
<th><p>Category</p></th>
<th><p>Worker</p></th>
<th><p>Project</p></th>
<th><p>Currency</p></th>
<th><p>Effective date</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>1</p></td>
<td><p>x</p></td>
<td><p>x</p></td>
<td><p>x</p></td>
<td><p>x</p></td>
<td><p>x</p></td>
</tr>
<tr class="even">
<td><p>2</p></td>
<td><p></p></td>
<td><p>x</p></td>
<td><p>x</p></td>
<td><p>x</p></td>
<td><p>x</p></td>
</tr>
<tr class="odd">
<td><p>3</p></td>
<td><p>x</p></td>
<td><p></p></td>
<td><p>x</p></td>
<td><p>x</p></td>
<td><p>x</p></td>
</tr>
<tr class="even">
<td><p>4</p></td>
<td><p></p></td>
<td><p></p></td>
<td><p>x</p></td>
<td><p>x</p></td>
<td><p>x</p></td>
</tr>
<tr class="odd">
<td><p>5</p></td>
<td><p>x</p></td>
<td><p>x</p></td>
<td><p></p></td>
<td><p>x</p></td>
<td><p>x</p></td>
</tr>
<tr class="even">
<td><p>6</p></td>
<td><p></p></td>
<td><p>x</p></td>
<td><p></p></td>
<td><p>x</p></td>
<td><p>x</p></td>
</tr>
<tr class="odd">
<td><p>7</p></td>
<td><p>x</p></td>
<td><p></p></td>
<td><p></p></td>
<td><p>x</p></td>
<td><p>x</p></td>
</tr>
<tr class="even">
<td><p>8</p></td>
<td><p></p></td>
<td><p></p></td>
<td><p></p></td>
<td><p>x</p></td>
<td><p>x</p></td>
</tr>
</tbody>
</table>


## Search priority for transfer prices

Transfer prices are set up for workers, products, projects, legal entities, and categories. The following table displays the search priority for transfer prices. Search matches have a priority from 1 to 8 in the table.

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
<th><p>Priority</p></th>
<th><p>Borrowing legal entity</p></th>
<th><p>Project</p></th>
<th><p>Worker and product</p></th>
<th><p>Category</p></th>
<th><p>Effective date</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>1</p></td>
<td><p>x</p></td>
<td><p>x</p></td>
<td><p>x</p></td>
<td><p>x</p></td>
<td><p>x</p></td>
</tr>
<tr class="even">
<td><p>2</p></td>
<td><p>x</p></td>
<td><p>x</p></td>
<td><p>x</p></td>
<td><p></p></td>
<td><p>x</p></td>
</tr>
<tr class="odd">
<td><p>3</p></td>
<td><p>x</p></td>
<td><p></p></td>
<td><p>x</p></td>
<td><p>x</p></td>
<td><p>x</p></td>
</tr>
<tr class="even">
<td><p>4</p></td>
<td><p>x</p></td>
<td><p>x</p></td>
<td><p></p></td>
<td><p>x</p></td>
<td><p>x</p></td>
</tr>
<tr class="odd">
<td><p>5</p></td>
<td><p>x</p></td>
<td><p>x</p></td>
<td><p></p></td>
<td><p></p></td>
<td><p>x</p></td>
</tr>
<tr class="even">
<td><p>6</p></td>
<td><p>x</p></td>
<td><p></p></td>
<td><p>x</p></td>
<td><p></p></td>
<td><p>x</p></td>
</tr>
<tr class="odd">
<td><p>7</p></td>
<td><p>x</p></td>
<td><p></p></td>
<td><p></p></td>
<td><p>x</p></td>
<td><p>x</p></td>
</tr>
<tr class="even">
<td><p>8</p></td>
<td><p>x</p></td>
<td><p></p></td>
<td><p></p></td>
<td><p></p></td>
<td><p>x</p></td>
</tr>
</tbody>
</table>


## See also

[About subscription sales prices](about-subscription-sales-prices.md)

[Update and index subscription sales prices](update-and-index-subscription-sales-prices.md)

[About indexed sales prices](about-indexed-sales-prices.md)

[About subscription sales prices](about-subscription-sales-prices.md)

  


