---
title: About default offset accounts for expense transactions
TOCTitle: About default offset accounts for expense transactions
ms:assetid: 8c464cec-e47f-48c0-8042-b3fa71cfe5ea
ms:mtpsurl: https://technet.microsoft.com/library/Hh209348(v=AX.60)
ms:contentKeyID: 36058479
author: Khairunj
ms.author: daxcpft
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# About default offset accounts for expense transactions 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

When you enter an expense transaction on a journal line, the system suggests the offset account that best matches the project, category, and worker on the transaction line.

The type of default offset account can be vendor, customer, ledger, or bank. The most common practice is to set up the default offset account as a vendor account. However, some companies set up a ledger offset account for individual workers or they use prepayments and set up the default offset accounts as customer accounts.


> [!NOTE]
> <P>If you set up an offset account on a journal header, it overrides accounts from the default offset account when you enter expenses in that journal.</P>



## Example

Workers who pay for meals, hotels, and transportation when they travel on business must be reimbursed by the company. For reimbursement purposes, it is helpful to have a default offset account. When you set up a system for default offset accounts, an offset account is suggested when workers register expenses in the expense journal.

The following table illustrates a scenario in which a company has set up four default offset accounts.

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
<th><p>Worker</p></th>
<th><p>Category</p></th>
<th><p>Project</p></th>
<th><p>Type</p></th>
<th><p>Default offset account</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Worker 1</p></td>
<td><p>Blank</p></td>
<td><p>Blank</p></td>
<td><p>Vendor</p></td>
<td><p>1356</p></td>
</tr>
<tr class="even">
<td><p>Worker 2</p></td>
<td><p>Blank</p></td>
<td><p>Blank</p></td>
<td><p>Vendor</p></td>
<td><p>1367</p></td>
</tr>
<tr class="odd">
<td><p>Blank</p></td>
<td><p>Flight</p></td>
<td><p>Blank</p></td>
<td><p>Vendor</p></td>
<td><p>205085</p></td>
</tr>
<tr class="even">
<td><p>Blank</p></td>
<td><p>Hotel</p></td>
<td><p>13000</p></td>
<td><p>Vendor</p></td>
<td><p>206068</p></td>
</tr>
</tbody>
</table>


When workers 1 and 2 enter expense transactions, the system uses the default offset accounts 1356 and 1367. However, if the expense is an airline ticket, offset account 205085 is suggested because the airline, which in this case is the vendor, will be reimbursed, rather than the worker.

The company has an agreement with a hotel chain in the area where project 13000 is located. Therefore, they have set up a default offset account for all hotel expenses on project 13000. If a worker enters an expense transaction that has category Hotel on project 13000, the system suggests offset account 206068.

## Search priority for offset accounts

You set up offset accounts for projects, categories, and workers. When the system searches for an offset account to assign an expense transaction to, it selects the account that most closely matches the details of the expense for project, category, and worker. For example, when the system identifies a set of accounts that have the correct project, it continues the search for category, and then worker, to find the closest match. If no offset account is assigned at the worker level, the account that is assigned to the category is used. If no account is assigned to the category, the account that is assigned to the project is used.

## See also

[Create invoice proposals for projects with and without billing rules](create-invoice-proposals-for-projects-with-and-without-billing-rules.md)

[About expense-related cost price fields](about-expense-related-cost-price-fields.md)

[Default offset account for expenses (form)](https://technet.microsoft.com/library/aa616251\(v=ax.60\))

  


